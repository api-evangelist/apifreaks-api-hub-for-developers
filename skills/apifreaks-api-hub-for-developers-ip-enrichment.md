---
name: Enrich an IP address with location and threat signal
description: >-
  Resolve an IPv4/IPv6 address (or hostname) to location, network and currency data, then add a
  VPN/proxy/Tor/bot threat score, using the APIFreaks IP intelligence APIs. Covers the single and bulk
  paths, the credit cost of the optional modules, and the failure codes the contract does not declare.
api: openapi/apifreaks-api-hub-for-developers-ip-locator-openapi.json
operations: [ipLookup, bulkIpLookup, ipSecurityLookup, bulkIpSecurityLookup, getCreditsUsage]
generated: '2026-08-09'
method: generated
---

# Enrich an IP address

## Auth
Send `X-apiKey: <key>` as a request header. The query form (`?apiKey=`) works but leaks the key into
proxy and CDN logs — prefer the header. One key covers every APIFreaks API; there are no scopes.

## Steps

1. **Geolocate.** `GET https://api.apifreaks.com/v2.0/geolocation/lookup?ip=<ip>` — `ipLookup`.
   Returns `location` (continent, country, region, city, coordinates, timezone), `asn` (ASN, ISP/company,
   route) and `currency` by default.
   - Narrow the payload with `fields=location.city,asn.organization` (dot-path allowlist) or
     `excludes=` (denylist).
   - Localize names with `lang=` (en, de, ru, ja, fr, cn, es, cs, it, ko, fa, pt).
   - Note the path is **v2.0**. The v1.0 form still works but is on the announced retirement track.

2. **Add threat signal.** Either add `include=security` to step 1, or call
   `GET /v1.0/ip/security?ip=<ip>` — `ipSecurityLookup` — for the standalone 0-100 threat score with
   VPN / proxy / Tor / bot detection.
   - `include=security` and `include=abuse` **cost extra credits** on top of the base lookup. Only ask
     for them when the answer will be used.
   - `include=*` turns on every module (security, hostname, liveHostname, hostnameFallbackLive,
     user_agent, abuse, dma_code, geo_accuracy) and is the most expensive call on this API.

3. **Go bulk when you have more than a handful.** POST the same paths:
   `bulkIpLookup` (`POST /v2.0/geolocation/lookup`) and `bulkIpSecurityLookup`
   (`POST /v1.0/ip/security`). Bulk threat intelligence accepts up to 50,000 IPs per request.

4. **Watch the balance.** `GET /v1.0/credits/usage/info` — `getCreditsUsage` — before a large batch.

## Rules

- Credits are charged **only on 2xx**. A 4xx or 5xx is never billed, and anything already charged is
  refunded. Read `X-AF-Credits-Cost` on each success to track spend.
- A reserved, bogon or unrecognized IP returns **423 Locked**, not a partial result. Treat 423 as
  "not a routable public address", not as an outage.
- **401 and 402 are not declared in the OpenAPI** but are real: 401 = invalid key or blocked IP,
  402 = credits exhausted. Handle both explicitly; a generated client will not know they exist.
- There is no idempotency key. These operations are read-only and safe to retry.
- No pagination anywhere on this API; batches are bounded by hard caps, and exceeding one returns 413.

## See also
- `conventions/apifreaks-api-hub-for-developers-conventions.yml`
- `errors/apifreaks-api-hub-for-developers-problem-types.yml`
- `rate-limits/apifreaks-api-hub-for-developers-rate-limits.yml`
