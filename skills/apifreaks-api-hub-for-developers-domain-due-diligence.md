---
name: Run domain due diligence — WHOIS, DNS, SSL and subdomains
description: >-
  Build a full picture of a domain from the APIFreaks domain intelligence APIs: live WHOIS, registration
  history, DNS records, TLS certificate, subdomains, and the other domains the same registrant owns.
api: openapi/apifreaks-api-hub-for-developers-whois-domain-lookup-openapi.json
operations: [lookupDomainWhois, whoisHistoryLookup, reverseWhoisLookup, dnsLookup, sslCertificateLookup, lookupSubdomains, asnLookup]
generated: '2026-08-09'
method: generated
---

# Domain due diligence

## Auth
`X-apiKey: <key>` header. One key, one shared credit pool.

## Steps

1. **Who owns it now.** `GET https://api.apifreaks.com/v2.0/domain/whois/live?domain=<domain>` —
   `lookupDomainWhois`. Live registration, registrar, nameservers and contacts.
   Some TLDs are not supported for live WHOIS and return **403 Forbidden — domain extension not supported**;
   that is a coverage answer, not an error to retry.

2. **Who owned it before.** `GET /v1.0/domain/whois/history?domain=<domain>` — `whoisHistoryLookup`.
   History reaches back to 1986.

3. **What else the same owner holds.** `GET /v1.0/domain/whois/reverse` — `reverseWhoisLookup`.
   Search by owner, company, email or keyword. This endpoint is **concurrency-limited** (see below).

4. **How it resolves.** `GET /v1.0/domain/dns/live?domain=<domain>` — `dnsLookup`.
   A, AAAA, MX, NS, SOA, SPF, TXT, CNAME.

5. **What it presents on TLS.** `GET /v1.0/domain/ssl/live?domain=<domain>` — `sslCertificateLookup`.
   Issuer, validity window, SANs. Use the chain variant when you need the full chain.

6. **What else lives underneath.** `GET /v1.0/subdomains/lookup?domain=<domain>` — `lookupSubdomains`.
   Returns first-seen / last-seen and activity status per subdomain.

7. **Whose network it sits on.** Take the ASN from the DNS/IP step and call
   `GET /v1.0/asn/whois/live` — `asnLookup` — for RIR data, ranges and BGP peering.

## Rules

- **Reverse WHOIS and Reverse DNS are concurrency-capped**, not rate-capped. Read
  `X-Concurrent-Threads` and `X-Concurrent-Threads-Active` from the response and keep in-flight requests
  under the cap. Exceeding it returns **429 "Please slow down"** — back off on concurrency, not on rate.
- These lookups hit third-party upstreams. **408 Request Timeout** is a normal, retryable outcome on
  WHOIS in particular.
- Bulk variants exist for WHOIS, DNS and domain availability, each capped at **100 items** per request;
  over the cap returns 413.
- All read-only — safe to retry. No idempotency key exists, and none is needed here.

## See also
- `conventions/apifreaks-api-hub-for-developers-conventions.yml`
- `rate-limits/apifreaks-api-hub-for-developers-rate-limits.yml`
