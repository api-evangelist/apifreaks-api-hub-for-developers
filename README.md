# APIFreaks - API Hub for Developers (apifreaks-api-hub-for-developers)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

APIFreaks is a first-party REST API hub built by JFreaks Software Solutions (Lahore, Pakistan) that ships more than 100 production endpoints behind a single API key and a single shared credit pool. The catalog spans IP geolocation and threat intelligence, WHOIS (live, historical, reverse, ASN), DNS (live, history, reverse), SSL certificate inspection, domain availability and subdomain discovery, forward and reverse geocoding, email and phone validation, VAT/IBAN/SWIFT financial validation, web scraping, website screenshots, an asynchronous PDF processing pipeline, currency and commodity market data, ZIP code and GeoDB reference data, weather (current, forecast, historical, marine, air quality, flood), timezones, user-agent parsing and astronomy. Credits are charged only on successful 2xx responses and refunded on errors, new accounts get 10,000 free credits with no card, and the whole surface is published as 102 OpenAPI 3.1 specifications plus an official Apache-2.0 MCP server exposing 59 agent tools.

**APIs.json:** [https://apifreaks-api-hub-for-developers.apievangelist.com/apis.yml](https://apifreaks-api-hub-for-developers.apievangelist.com/apis.yml)

## Tags

- IP intelligence
- geolocation
- WHOIS
- domain intelligence
- DNS
- geocoding
- email validation
- phone validation
- SSL
- web scraping
- screenshots
- PDF processing
- currency
- forex
- commodities
- financial validation
- ZIP codes
- weather
- timezone
- GeoDB
- user-agent parsing
- astronomy
- developer tools
- MCP
- agent-ready
- OCR

## Timestamps

- **Created:** 2026-07-29
- **Modified:** 2026-08-09

## APIs

### APIFreaks MCP Server

Official first-party Model Context Protocol server (Apache-2.0) exposing 59 read-only tools across 13 categories — IP intelligence, WHOIS, DNS, SSL, domain, weather, currency, commodity, ZIP code, screenshot, timezone, user-agent and astronomy. Distributed on npm as @apifreaks/mcp and run locally over stdio with `npx -y @apifreaks/mcp`; there is no hosted remote endpoint. Authenticates with the same single APIFREAKS_API_KEY as the REST API.

- **Human URL:** [https://apifreaks.com/integrations/mcp-server](https://apifreaks.com/integrations/mcp-server)
- **Base URL:** `https://api.apifreaks.com/v1.0/`

#### Tags

- MCP
- agent-ready
- developer tools
- IP intelligence
- WHOIS
- DNS
- weather
- currency

#### Properties

- [M C P Server](mcp/apifreaks-api-hub-for-developers-mcp.yml)
- [Tool Crosswalk](mcp/apifreaks-api-hub-for-developers-tool-crosswalk.yml)
- [Documentation](https://apifreaks.com/integrations/mcp-server)
- [API Reference](https://apifreaks.com/integrations/mcp-server/supported-tools)
- [Source Code](https://github.com/api-freaks/apifreaks-mcp)
- [Postman Collection](collections/apifreaks-api-hub-for-developers-commodity-apis-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apifreaks-api-hub-for-developers-commodity-apis-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/apifreaks-api-hub-for-developers-currency-apis-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apifreaks-api-hub-for-developers-currency-apis-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/apifreaks-api-hub-for-developers-dns-apis-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apifreaks-api-hub-for-developers-dns-apis-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/apifreaks-api-hub-for-developers-domain-apis-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apifreaks-api-hub-for-developers-domain-apis-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/apifreaks-api-hub-for-developers-email-validation-apis-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apifreaks-api-hub-for-developers-email-validation-apis-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/apifreaks-api-hub-for-developers-financial-apis-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apifreaks-api-hub-for-developers-financial-apis-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/apifreaks-api-hub-for-developers-flags-apis-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apifreaks-api-hub-for-developers-flags-apis-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/apifreaks-api-hub-for-developers-general-apis-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apifreaks-api-hub-for-developers-general-apis-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/apifreaks-api-hub-for-developers-geocoder-apis-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apifreaks-api-hub-for-developers-geocoder-apis-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/apifreaks-api-hub-for-developers-geodb-apis-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apifreaks-api-hub-for-developers-geodb-apis-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/apifreaks-api-hub-for-developers-ip-geolocation-apis-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apifreaks-api-hub-for-developers-ip-geolocation-apis-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/apifreaks-api-hub-for-developers-other-apis-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apifreaks-api-hub-for-developers-other-apis-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/apifreaks-api-hub-for-developers-pdf-operations-apis-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apifreaks-api-hub-for-developers-pdf-operations-apis-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/apifreaks-api-hub-for-developers-pdf-security-apis-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apifreaks-api-hub-for-developers-pdf-security-apis-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/apifreaks-api-hub-for-developers-pdf-to-image-apis-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apifreaks-api-hub-for-developers-pdf-to-image-apis-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/apifreaks-api-hub-for-developers-pdf-upload-and-download-apis-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apifreaks-api-hub-for-developers-pdf-upload-and-download-apis-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/apifreaks-api-hub-for-developers-phone-validation-apis-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apifreaks-api-hub-for-developers-phone-validation-apis-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/apifreaks-api-hub-for-developers-scraping-apis-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apifreaks-api-hub-for-developers-scraping-apis-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/apifreaks-api-hub-for-developers-screenshot-apis-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apifreaks-api-hub-for-developers-screenshot-apis-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/apifreaks-api-hub-for-developers-ssl-apis-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apifreaks-api-hub-for-developers-ssl-apis-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/apifreaks-api-hub-for-developers-task-status-and-file-info-apis-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apifreaks-api-hub-for-developers-task-status-and-file-info-apis-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/apifreaks-api-hub-for-developers-timezone-apis-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apifreaks-api-hub-for-developers-timezone-apis-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/apifreaks-api-hub-for-developers-user-agent-apis-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apifreaks-api-hub-for-developers-user-agent-apis-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/apifreaks-api-hub-for-developers-weather-apis-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apifreaks-api-hub-for-developers-weather-apis-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/apifreaks-api-hub-for-developers-whois-apis-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apifreaks-api-hub-for-developers-whois-apis-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/apifreaks-api-hub-for-developers-zip-code-apis-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apifreaks-api-hub-for-developers-zip-code-apis-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### APIFreaks - API Hub for Developers Commodity APIs API

The Commodity APIs API from APIFreaks - API Hub for Developers — 5 operation(s) for commodity apis.

- **Human URL:** [https://apifreaks.com/api](https://apifreaks.com/api)
- **Base URL:** `https://api.apifreaks.com/v1.0/`

#### Tags

- Commodity APIs

#### Properties

- [OpenAPI](openapi/apifreaks-api-hub-for-developers-commodity-apis-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/apifreaks-api-hub-for-developers-commodity-apis-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apifreaks-api-hub-for-developers-commodity-apis-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://apifreaks.com/docs)
- [API Reference](https://apifreaks.com/api/swagger)
- [Playground](https://apifreaks.com/api/playground)
- [Authentication](authentication/apifreaks-api-hub-for-developers-authentication.yml)
- [Conventions](conventions/apifreaks-api-hub-for-developers-conventions.yml)
- [Error Catalog](errors/apifreaks-api-hub-for-developers-problem-types.yml)
- [Rate Limits](rate-limits/apifreaks-api-hub-for-developers-rate-limits.yml)
- [Webhooks](asyncapi/apifreaks-api-hub-for-developers-pdf-webhooks.yml)

### APIFreaks - API Hub for Developers Currency APIs API

The Currency APIs API from APIFreaks - API Hub for Developers — 10 operation(s) for currency apis.

- **Human URL:** [https://apifreaks.com/api](https://apifreaks.com/api)
- **Base URL:** `https://api.apifreaks.com/v1.0/`

#### Tags

- Currency APIs

#### Properties

- [OpenAPI](openapi/apifreaks-api-hub-for-developers-currency-apis-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/apifreaks-api-hub-for-developers-currency-apis-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apifreaks-api-hub-for-developers-currency-apis-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://apifreaks.com/docs)
- [API Reference](https://apifreaks.com/api/swagger)
- [Playground](https://apifreaks.com/api/playground)
- [Authentication](authentication/apifreaks-api-hub-for-developers-authentication.yml)
- [Conventions](conventions/apifreaks-api-hub-for-developers-conventions.yml)
- [Error Catalog](errors/apifreaks-api-hub-for-developers-problem-types.yml)
- [Rate Limits](rate-limits/apifreaks-api-hub-for-developers-rate-limits.yml)
- [Webhooks](asyncapi/apifreaks-api-hub-for-developers-pdf-webhooks.yml)

### APIFreaks - API Hub for Developers DNS APIs API

The DNS APIs API from APIFreaks - API Hub for Developers — 3 operation(s) for dns apis.

- **Human URL:** [https://apifreaks.com/api](https://apifreaks.com/api)
- **Base URL:** `https://api.apifreaks.com/v1.0/`

#### Tags

- DNS APIs

#### Properties

- [OpenAPI](openapi/apifreaks-api-hub-for-developers-dns-apis-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/apifreaks-api-hub-for-developers-dns-apis-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apifreaks-api-hub-for-developers-dns-apis-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://apifreaks.com/docs)
- [API Reference](https://apifreaks.com/api/swagger)
- [Playground](https://apifreaks.com/api/playground)
- [Authentication](authentication/apifreaks-api-hub-for-developers-authentication.yml)
- [Conventions](conventions/apifreaks-api-hub-for-developers-conventions.yml)
- [Error Catalog](errors/apifreaks-api-hub-for-developers-problem-types.yml)
- [Rate Limits](rate-limits/apifreaks-api-hub-for-developers-rate-limits.yml)
- [Webhooks](asyncapi/apifreaks-api-hub-for-developers-pdf-webhooks.yml)

### APIFreaks - API Hub for Developers Domain APIs API

The Domain APIs API from APIFreaks - API Hub for Developers — 3 operation(s) for domain apis.

- **Human URL:** [https://apifreaks.com/api](https://apifreaks.com/api)
- **Base URL:** `https://api.apifreaks.com/v1.0/`

#### Tags

- Domain APIs

#### Properties

- [OpenAPI](openapi/apifreaks-api-hub-for-developers-domain-apis-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/apifreaks-api-hub-for-developers-domain-apis-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apifreaks-api-hub-for-developers-domain-apis-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://apifreaks.com/docs)
- [API Reference](https://apifreaks.com/api/swagger)
- [Playground](https://apifreaks.com/api/playground)
- [Authentication](authentication/apifreaks-api-hub-for-developers-authentication.yml)
- [Conventions](conventions/apifreaks-api-hub-for-developers-conventions.yml)
- [Error Catalog](errors/apifreaks-api-hub-for-developers-problem-types.yml)
- [Rate Limits](rate-limits/apifreaks-api-hub-for-developers-rate-limits.yml)
- [Webhooks](asyncapi/apifreaks-api-hub-for-developers-pdf-webhooks.yml)

### APIFreaks - API Hub for Developers Email Validation APIs API

The Email Validation APIs API from APIFreaks - API Hub for Developers — 2 operation(s) for email validation apis.

- **Human URL:** [https://apifreaks.com/api](https://apifreaks.com/api)
- **Base URL:** `https://api.apifreaks.com/v1.0/`

#### Tags

- Email Validation APIs

#### Properties

- [OpenAPI](openapi/apifreaks-api-hub-for-developers-email-validation-apis-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/apifreaks-api-hub-for-developers-email-validation-apis-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apifreaks-api-hub-for-developers-email-validation-apis-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://apifreaks.com/docs)
- [API Reference](https://apifreaks.com/api/swagger)
- [Playground](https://apifreaks.com/api/playground)
- [Authentication](authentication/apifreaks-api-hub-for-developers-authentication.yml)
- [Conventions](conventions/apifreaks-api-hub-for-developers-conventions.yml)
- [Error Catalog](errors/apifreaks-api-hub-for-developers-problem-types.yml)
- [Rate Limits](rate-limits/apifreaks-api-hub-for-developers-rate-limits.yml)
- [Webhooks](asyncapi/apifreaks-api-hub-for-developers-pdf-webhooks.yml)

### APIFreaks - API Hub for Developers Financial APIs API

The Financial APIs API from APIFreaks - API Hub for Developers — 7 operation(s) for financial apis.

- **Human URL:** [https://apifreaks.com/api](https://apifreaks.com/api)
- **Base URL:** `https://api.apifreaks.com/v1.0/`

#### Tags

- Financial APIs

#### Properties

- [OpenAPI](openapi/apifreaks-api-hub-for-developers-financial-apis-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/apifreaks-api-hub-for-developers-financial-apis-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apifreaks-api-hub-for-developers-financial-apis-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://apifreaks.com/docs)
- [API Reference](https://apifreaks.com/api/swagger)
- [Playground](https://apifreaks.com/api/playground)
- [Authentication](authentication/apifreaks-api-hub-for-developers-authentication.yml)
- [Conventions](conventions/apifreaks-api-hub-for-developers-conventions.yml)
- [Error Catalog](errors/apifreaks-api-hub-for-developers-problem-types.yml)
- [Rate Limits](rate-limits/apifreaks-api-hub-for-developers-rate-limits.yml)
- [Webhooks](asyncapi/apifreaks-api-hub-for-developers-pdf-webhooks.yml)

### APIFreaks - API Hub for Developers Flags APIs API

The Flags APIs API from APIFreaks - API Hub for Developers — 2 operation(s) for flags apis.

- **Human URL:** [https://apifreaks.com/api](https://apifreaks.com/api)
- **Base URL:** `https://api.apifreaks.com/v1.0/`

#### Tags

- Flags APIs

#### Properties

- [OpenAPI](openapi/apifreaks-api-hub-for-developers-flags-apis-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/apifreaks-api-hub-for-developers-flags-apis-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apifreaks-api-hub-for-developers-flags-apis-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://apifreaks.com/docs)
- [API Reference](https://apifreaks.com/api/swagger)
- [Playground](https://apifreaks.com/api/playground)
- [Authentication](authentication/apifreaks-api-hub-for-developers-authentication.yml)
- [Conventions](conventions/apifreaks-api-hub-for-developers-conventions.yml)
- [Error Catalog](errors/apifreaks-api-hub-for-developers-problem-types.yml)
- [Rate Limits](rate-limits/apifreaks-api-hub-for-developers-rate-limits.yml)
- [Webhooks](asyncapi/apifreaks-api-hub-for-developers-pdf-webhooks.yml)

### APIFreaks - API Hub for Developers General APIs API

The General APIs API from APIFreaks - API Hub for Developers — 1 operation(s) for general apis.

- **Human URL:** [https://apifreaks.com/api](https://apifreaks.com/api)
- **Base URL:** `https://api.apifreaks.com/v1.0/`

#### Tags

- General APIs

#### Properties

- [OpenAPI](openapi/apifreaks-api-hub-for-developers-general-apis-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/apifreaks-api-hub-for-developers-general-apis-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apifreaks-api-hub-for-developers-general-apis-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://apifreaks.com/docs)
- [API Reference](https://apifreaks.com/api/swagger)
- [Playground](https://apifreaks.com/api/playground)
- [Authentication](authentication/apifreaks-api-hub-for-developers-authentication.yml)
- [Conventions](conventions/apifreaks-api-hub-for-developers-conventions.yml)
- [Error Catalog](errors/apifreaks-api-hub-for-developers-problem-types.yml)
- [Rate Limits](rate-limits/apifreaks-api-hub-for-developers-rate-limits.yml)
- [Webhooks](asyncapi/apifreaks-api-hub-for-developers-pdf-webhooks.yml)

### APIFreaks - API Hub for Developers Geocoder APIs API

The Geocoder APIs API from APIFreaks - API Hub for Developers — 2 operation(s) for geocoder apis.

- **Human URL:** [https://apifreaks.com/api](https://apifreaks.com/api)
- **Base URL:** `https://api.apifreaks.com/v1.0/`

#### Tags

- Geocoder APIs

#### Properties

- [OpenAPI](openapi/apifreaks-api-hub-for-developers-geocoder-apis-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/apifreaks-api-hub-for-developers-geocoder-apis-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apifreaks-api-hub-for-developers-geocoder-apis-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://apifreaks.com/docs)
- [API Reference](https://apifreaks.com/api/swagger)
- [Playground](https://apifreaks.com/api/playground)
- [Authentication](authentication/apifreaks-api-hub-for-developers-authentication.yml)
- [Conventions](conventions/apifreaks-api-hub-for-developers-conventions.yml)
- [Error Catalog](errors/apifreaks-api-hub-for-developers-problem-types.yml)
- [Rate Limits](rate-limits/apifreaks-api-hub-for-developers-rate-limits.yml)
- [Webhooks](asyncapi/apifreaks-api-hub-for-developers-pdf-webhooks.yml)

### APIFreaks - API Hub for Developers GeoDB APIs API

The GeoDB APIs API from APIFreaks - API Hub for Developers — 8 operation(s) for geodb apis.

- **Human URL:** [https://apifreaks.com/api](https://apifreaks.com/api)
- **Base URL:** `https://api.apifreaks.com/v1.0/`

#### Tags

- GeoDB APIs

#### Properties

- [OpenAPI](openapi/apifreaks-api-hub-for-developers-geodb-apis-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/apifreaks-api-hub-for-developers-geodb-apis-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apifreaks-api-hub-for-developers-geodb-apis-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://apifreaks.com/docs)
- [API Reference](https://apifreaks.com/api/swagger)
- [Playground](https://apifreaks.com/api/playground)
- [Authentication](authentication/apifreaks-api-hub-for-developers-authentication.yml)
- [Conventions](conventions/apifreaks-api-hub-for-developers-conventions.yml)
- [Error Catalog](errors/apifreaks-api-hub-for-developers-problem-types.yml)
- [Rate Limits](rate-limits/apifreaks-api-hub-for-developers-rate-limits.yml)
- [Webhooks](asyncapi/apifreaks-api-hub-for-developers-pdf-webhooks.yml)

### APIFreaks - API Hub for Developers IP Geolocation APIs API

The IP Geolocation APIs API from APIFreaks - API Hub for Developers — 2 operation(s) for ip geolocation apis.

- **Human URL:** [https://apifreaks.com/api](https://apifreaks.com/api)
- **Base URL:** `https://api.apifreaks.com/v1.0/`

#### Tags

- IP Geolocation APIs

#### Properties

- [OpenAPI](openapi/apifreaks-api-hub-for-developers-ip-geolocation-apis-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/apifreaks-api-hub-for-developers-ip-geolocation-apis-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apifreaks-api-hub-for-developers-ip-geolocation-apis-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://apifreaks.com/docs)
- [API Reference](https://apifreaks.com/api/swagger)
- [Playground](https://apifreaks.com/api/playground)
- [Authentication](authentication/apifreaks-api-hub-for-developers-authentication.yml)
- [Conventions](conventions/apifreaks-api-hub-for-developers-conventions.yml)
- [Error Catalog](errors/apifreaks-api-hub-for-developers-problem-types.yml)
- [Rate Limits](rate-limits/apifreaks-api-hub-for-developers-rate-limits.yml)
- [Webhooks](asyncapi/apifreaks-api-hub-for-developers-pdf-webhooks.yml)

### APIFreaks - API Hub for Developers Other APIs API

The Other APIs API from APIFreaks - API Hub for Developers — 1 operation(s) for other apis.

- **Human URL:** [https://apifreaks.com/api](https://apifreaks.com/api)
- **Base URL:** `https://api.apifreaks.com/v1.0/`

#### Tags

- Other APIs

#### Properties

- [OpenAPI](openapi/apifreaks-api-hub-for-developers-other-apis-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/apifreaks-api-hub-for-developers-other-apis-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apifreaks-api-hub-for-developers-other-apis-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://apifreaks.com/docs)
- [API Reference](https://apifreaks.com/api/swagger)
- [Playground](https://apifreaks.com/api/playground)
- [Authentication](authentication/apifreaks-api-hub-for-developers-authentication.yml)
- [Conventions](conventions/apifreaks-api-hub-for-developers-conventions.yml)
- [Error Catalog](errors/apifreaks-api-hub-for-developers-problem-types.yml)
- [Rate Limits](rate-limits/apifreaks-api-hub-for-developers-rate-limits.yml)
- [Webhooks](asyncapi/apifreaks-api-hub-for-developers-pdf-webhooks.yml)

### APIFreaks - API Hub for Developers PDF Operations APIs API

The PDF Operations APIs API from APIFreaks - API Hub for Developers — 7 operation(s) for pdf operations apis.

- **Human URL:** [https://apifreaks.com/api](https://apifreaks.com/api)
- **Base URL:** `https://api.apifreaks.com/v1.0/`

#### Tags

- PDF Operations APIs

#### Properties

- [OpenAPI](openapi/apifreaks-api-hub-for-developers-pdf-operations-apis-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/apifreaks-api-hub-for-developers-pdf-operations-apis-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apifreaks-api-hub-for-developers-pdf-operations-apis-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://apifreaks.com/docs)
- [API Reference](https://apifreaks.com/api/swagger)
- [Playground](https://apifreaks.com/api/playground)
- [Authentication](authentication/apifreaks-api-hub-for-developers-authentication.yml)
- [Conventions](conventions/apifreaks-api-hub-for-developers-conventions.yml)
- [Error Catalog](errors/apifreaks-api-hub-for-developers-problem-types.yml)
- [Rate Limits](rate-limits/apifreaks-api-hub-for-developers-rate-limits.yml)
- [Webhooks](asyncapi/apifreaks-api-hub-for-developers-pdf-webhooks.yml)

### APIFreaks - API Hub for Developers PDF Security APIs API

The PDF Security APIs API from APIFreaks - API Hub for Developers — 4 operation(s) for pdf security apis.

- **Human URL:** [https://apifreaks.com/api](https://apifreaks.com/api)
- **Base URL:** `https://api.apifreaks.com/v1.0/`

#### Tags

- PDF Security APIs

#### Properties

- [OpenAPI](openapi/apifreaks-api-hub-for-developers-pdf-security-apis-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/apifreaks-api-hub-for-developers-pdf-security-apis-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apifreaks-api-hub-for-developers-pdf-security-apis-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://apifreaks.com/docs)
- [API Reference](https://apifreaks.com/api/swagger)
- [Playground](https://apifreaks.com/api/playground)
- [Authentication](authentication/apifreaks-api-hub-for-developers-authentication.yml)
- [Conventions](conventions/apifreaks-api-hub-for-developers-conventions.yml)
- [Error Catalog](errors/apifreaks-api-hub-for-developers-problem-types.yml)
- [Rate Limits](rate-limits/apifreaks-api-hub-for-developers-rate-limits.yml)
- [Webhooks](asyncapi/apifreaks-api-hub-for-developers-pdf-webhooks.yml)

### APIFreaks - API Hub for Developers PDF To Image APIs API

The PDF To Image APIs API from APIFreaks - API Hub for Developers — 5 operation(s) for pdf to image apis.

- **Human URL:** [https://apifreaks.com/api](https://apifreaks.com/api)
- **Base URL:** `https://api.apifreaks.com/v1.0/`

#### Tags

- PDF To Image APIs

#### Properties

- [OpenAPI](openapi/apifreaks-api-hub-for-developers-pdf-to-image-apis-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/apifreaks-api-hub-for-developers-pdf-to-image-apis-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apifreaks-api-hub-for-developers-pdf-to-image-apis-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://apifreaks.com/docs)
- [API Reference](https://apifreaks.com/api/swagger)
- [Playground](https://apifreaks.com/api/playground)
- [Authentication](authentication/apifreaks-api-hub-for-developers-authentication.yml)
- [Conventions](conventions/apifreaks-api-hub-for-developers-conventions.yml)
- [Error Catalog](errors/apifreaks-api-hub-for-developers-problem-types.yml)
- [Rate Limits](rate-limits/apifreaks-api-hub-for-developers-rate-limits.yml)
- [Webhooks](asyncapi/apifreaks-api-hub-for-developers-pdf-webhooks.yml)

### APIFreaks - API Hub for Developers PDF Upload and Download APIs API

The PDF Upload and Download APIs API from APIFreaks - API Hub for Developers — 3 operation(s) for pdf upload and download apis.

- **Human URL:** [https://apifreaks.com/api](https://apifreaks.com/api)
- **Base URL:** `https://api.apifreaks.com/v1.0/`

#### Tags

- PDF Upload and Download APIs

#### Properties

- [OpenAPI](openapi/apifreaks-api-hub-for-developers-pdf-upload-and-download-apis-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/apifreaks-api-hub-for-developers-pdf-upload-and-download-apis-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apifreaks-api-hub-for-developers-pdf-upload-and-download-apis-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://apifreaks.com/docs)
- [API Reference](https://apifreaks.com/api/swagger)
- [Playground](https://apifreaks.com/api/playground)
- [Authentication](authentication/apifreaks-api-hub-for-developers-authentication.yml)
- [Conventions](conventions/apifreaks-api-hub-for-developers-conventions.yml)
- [Error Catalog](errors/apifreaks-api-hub-for-developers-problem-types.yml)
- [Rate Limits](rate-limits/apifreaks-api-hub-for-developers-rate-limits.yml)
- [Webhooks](asyncapi/apifreaks-api-hub-for-developers-pdf-webhooks.yml)

### APIFreaks - API Hub for Developers Phone Validation APIs API

The Phone Validation APIs API from APIFreaks - API Hub for Developers — 2 operation(s) for phone validation apis.

- **Human URL:** [https://apifreaks.com/api](https://apifreaks.com/api)
- **Base URL:** `https://api.apifreaks.com/v1.0/`

#### Tags

- Phone Validation APIs

#### Properties

- [OpenAPI](openapi/apifreaks-api-hub-for-developers-phone-validation-apis-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/apifreaks-api-hub-for-developers-phone-validation-apis-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apifreaks-api-hub-for-developers-phone-validation-apis-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://apifreaks.com/docs)
- [API Reference](https://apifreaks.com/api/swagger)
- [Playground](https://apifreaks.com/api/playground)
- [Authentication](authentication/apifreaks-api-hub-for-developers-authentication.yml)
- [Conventions](conventions/apifreaks-api-hub-for-developers-conventions.yml)
- [Error Catalog](errors/apifreaks-api-hub-for-developers-problem-types.yml)
- [Rate Limits](rate-limits/apifreaks-api-hub-for-developers-rate-limits.yml)
- [Webhooks](asyncapi/apifreaks-api-hub-for-developers-pdf-webhooks.yml)

### APIFreaks - API Hub for Developers Scraping APIs API

The Scraping APIs API from APIFreaks - API Hub for Developers — 1 operation(s) for scraping apis.

- **Human URL:** [https://apifreaks.com/api](https://apifreaks.com/api)
- **Base URL:** `https://api.apifreaks.com/v1.0/`

#### Tags

- Scraping APIs

#### Properties

- [OpenAPI](openapi/apifreaks-api-hub-for-developers-scraping-apis-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/apifreaks-api-hub-for-developers-scraping-apis-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apifreaks-api-hub-for-developers-scraping-apis-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://apifreaks.com/docs)
- [API Reference](https://apifreaks.com/api/swagger)
- [Playground](https://apifreaks.com/api/playground)
- [Authentication](authentication/apifreaks-api-hub-for-developers-authentication.yml)
- [Conventions](conventions/apifreaks-api-hub-for-developers-conventions.yml)
- [Error Catalog](errors/apifreaks-api-hub-for-developers-problem-types.yml)
- [Rate Limits](rate-limits/apifreaks-api-hub-for-developers-rate-limits.yml)
- [Webhooks](asyncapi/apifreaks-api-hub-for-developers-pdf-webhooks.yml)

### APIFreaks - API Hub for Developers Screenshot APIs API

The Screenshot APIs API from APIFreaks - API Hub for Developers — 1 operation(s) for screenshot apis.

- **Human URL:** [https://apifreaks.com/api](https://apifreaks.com/api)
- **Base URL:** `https://api.apifreaks.com/v1.0/`

#### Tags

- Screenshot APIs

#### Properties

- [OpenAPI](openapi/apifreaks-api-hub-for-developers-screenshot-apis-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/apifreaks-api-hub-for-developers-screenshot-apis-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apifreaks-api-hub-for-developers-screenshot-apis-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://apifreaks.com/docs)
- [API Reference](https://apifreaks.com/api/swagger)
- [Playground](https://apifreaks.com/api/playground)
- [Authentication](authentication/apifreaks-api-hub-for-developers-authentication.yml)
- [Conventions](conventions/apifreaks-api-hub-for-developers-conventions.yml)
- [Error Catalog](errors/apifreaks-api-hub-for-developers-problem-types.yml)
- [Rate Limits](rate-limits/apifreaks-api-hub-for-developers-rate-limits.yml)
- [Webhooks](asyncapi/apifreaks-api-hub-for-developers-pdf-webhooks.yml)

### APIFreaks - API Hub for Developers SSL APIs API

The SSL APIs API from APIFreaks - API Hub for Developers — 2 operation(s) for ssl apis.

- **Human URL:** [https://apifreaks.com/api](https://apifreaks.com/api)
- **Base URL:** `https://api.apifreaks.com/v1.0/`

#### Tags

- SSL APIs

#### Properties

- [OpenAPI](openapi/apifreaks-api-hub-for-developers-ssl-apis-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/apifreaks-api-hub-for-developers-ssl-apis-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apifreaks-api-hub-for-developers-ssl-apis-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://apifreaks.com/docs)
- [API Reference](https://apifreaks.com/api/swagger)
- [Playground](https://apifreaks.com/api/playground)
- [Authentication](authentication/apifreaks-api-hub-for-developers-authentication.yml)
- [Conventions](conventions/apifreaks-api-hub-for-developers-conventions.yml)
- [Error Catalog](errors/apifreaks-api-hub-for-developers-problem-types.yml)
- [Rate Limits](rate-limits/apifreaks-api-hub-for-developers-rate-limits.yml)
- [Webhooks](asyncapi/apifreaks-api-hub-for-developers-pdf-webhooks.yml)

### APIFreaks - API Hub for Developers Task Status and File Info APIs API

The Task Status and File Info APIs API from APIFreaks - API Hub for Developers — 4 operation(s) for task status and file info apis.

- **Human URL:** [https://apifreaks.com/api](https://apifreaks.com/api)
- **Base URL:** `https://api.apifreaks.com/v1.0/`

#### Tags

- Task Status and File Info APIs

#### Properties

- [OpenAPI](openapi/apifreaks-api-hub-for-developers-task-status-and-file-info-apis-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/apifreaks-api-hub-for-developers-task-status-and-file-info-apis-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apifreaks-api-hub-for-developers-task-status-and-file-info-apis-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://apifreaks.com/docs)
- [API Reference](https://apifreaks.com/api/swagger)
- [Playground](https://apifreaks.com/api/playground)
- [Authentication](authentication/apifreaks-api-hub-for-developers-authentication.yml)
- [Conventions](conventions/apifreaks-api-hub-for-developers-conventions.yml)
- [Error Catalog](errors/apifreaks-api-hub-for-developers-problem-types.yml)
- [Rate Limits](rate-limits/apifreaks-api-hub-for-developers-rate-limits.yml)
- [Webhooks](asyncapi/apifreaks-api-hub-for-developers-pdf-webhooks.yml)

### APIFreaks - API Hub for Developers Timezone APIs API

The Timezone APIs API from APIFreaks - API Hub for Developers — 2 operation(s) for timezone apis.

- **Human URL:** [https://apifreaks.com/api](https://apifreaks.com/api)
- **Base URL:** `https://api.apifreaks.com/v1.0/`

#### Tags

- Timezone APIs

#### Properties

- [OpenAPI](openapi/apifreaks-api-hub-for-developers-timezone-apis-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/apifreaks-api-hub-for-developers-timezone-apis-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apifreaks-api-hub-for-developers-timezone-apis-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://apifreaks.com/docs)
- [API Reference](https://apifreaks.com/api/swagger)
- [Playground](https://apifreaks.com/api/playground)
- [Authentication](authentication/apifreaks-api-hub-for-developers-authentication.yml)
- [Conventions](conventions/apifreaks-api-hub-for-developers-conventions.yml)
- [Error Catalog](errors/apifreaks-api-hub-for-developers-problem-types.yml)
- [Rate Limits](rate-limits/apifreaks-api-hub-for-developers-rate-limits.yml)
- [Webhooks](asyncapi/apifreaks-api-hub-for-developers-pdf-webhooks.yml)

### APIFreaks - API Hub for Developers User Agent APIs API

The User Agent APIs API from APIFreaks - API Hub for Developers — 1 operation(s) for user agent apis.

- **Human URL:** [https://apifreaks.com/api](https://apifreaks.com/api)
- **Base URL:** `https://api.apifreaks.com/v1.0/`

#### Tags

- User Agent APIs

#### Properties

- [OpenAPI](openapi/apifreaks-api-hub-for-developers-user-agent-apis-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/apifreaks-api-hub-for-developers-user-agent-apis-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apifreaks-api-hub-for-developers-user-agent-apis-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://apifreaks.com/docs)
- [API Reference](https://apifreaks.com/api/swagger)
- [Playground](https://apifreaks.com/api/playground)
- [Authentication](authentication/apifreaks-api-hub-for-developers-authentication.yml)
- [Conventions](conventions/apifreaks-api-hub-for-developers-conventions.yml)
- [Error Catalog](errors/apifreaks-api-hub-for-developers-problem-types.yml)
- [Rate Limits](rate-limits/apifreaks-api-hub-for-developers-rate-limits.yml)
- [Webhooks](asyncapi/apifreaks-api-hub-for-developers-pdf-webhooks.yml)

### APIFreaks - API Hub for Developers Weather APIs API

The Weather APIs API from APIFreaks - API Hub for Developers — 7 operation(s) for weather apis.

- **Human URL:** [https://apifreaks.com/api](https://apifreaks.com/api)
- **Base URL:** `https://api.apifreaks.com/v1.0/`

#### Tags

- Weather APIs

#### Properties

- [OpenAPI](openapi/apifreaks-api-hub-for-developers-weather-apis-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/apifreaks-api-hub-for-developers-weather-apis-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apifreaks-api-hub-for-developers-weather-apis-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://apifreaks.com/docs)
- [API Reference](https://apifreaks.com/api/swagger)
- [Playground](https://apifreaks.com/api/playground)
- [Authentication](authentication/apifreaks-api-hub-for-developers-authentication.yml)
- [Conventions](conventions/apifreaks-api-hub-for-developers-conventions.yml)
- [Error Catalog](errors/apifreaks-api-hub-for-developers-problem-types.yml)
- [Rate Limits](rate-limits/apifreaks-api-hub-for-developers-rate-limits.yml)
- [Webhooks](asyncapi/apifreaks-api-hub-for-developers-pdf-webhooks.yml)

### APIFreaks - API Hub for Developers WHOIS APIs API

The WHOIS APIs API from APIFreaks - API Hub for Developers — 5 operation(s) for whois apis.

- **Human URL:** [https://apifreaks.com/api](https://apifreaks.com/api)
- **Base URL:** `https://api.apifreaks.com/v1.0/`

#### Tags

- WHOIS APIs

#### Properties

- [OpenAPI](openapi/apifreaks-api-hub-for-developers-whois-apis-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/apifreaks-api-hub-for-developers-whois-apis-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apifreaks-api-hub-for-developers-whois-apis-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://apifreaks.com/docs)
- [API Reference](https://apifreaks.com/api/swagger)
- [Playground](https://apifreaks.com/api/playground)
- [Authentication](authentication/apifreaks-api-hub-for-developers-authentication.yml)
- [Conventions](conventions/apifreaks-api-hub-for-developers-conventions.yml)
- [Error Catalog](errors/apifreaks-api-hub-for-developers-problem-types.yml)
- [Rate Limits](rate-limits/apifreaks-api-hub-for-developers-rate-limits.yml)
- [Webhooks](asyncapi/apifreaks-api-hub-for-developers-pdf-webhooks.yml)

### APIFreaks - API Hub for Developers ZIP Code APIs API

The ZIP Code APIs API from APIFreaks - API Hub for Developers — 6 operation(s) for zip code apis.

- **Human URL:** [https://apifreaks.com/api](https://apifreaks.com/api)
- **Base URL:** `https://api.apifreaks.com/v1.0/`

#### Tags

- ZIP Code APIs

#### Properties

- [OpenAPI](openapi/apifreaks-api-hub-for-developers-zip-code-apis-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/apifreaks-api-hub-for-developers-zip-code-apis-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apifreaks-api-hub-for-developers-zip-code-apis-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://apifreaks.com/docs)
- [API Reference](https://apifreaks.com/api/swagger)
- [Playground](https://apifreaks.com/api/playground)
- [Authentication](authentication/apifreaks-api-hub-for-developers-authentication.yml)
- [Conventions](conventions/apifreaks-api-hub-for-developers-conventions.yml)
- [Error Catalog](errors/apifreaks-api-hub-for-developers-problem-types.yml)
- [Rate Limits](rate-limits/apifreaks-api-hub-for-developers-rate-limits.yml)
- [Webhooks](asyncapi/apifreaks-api-hub-for-developers-pdf-webhooks.yml)

## Common Properties

- [Issue Tracker](https://github.com/api-freaks/apifreaks-mcp/issues)
- [Releases](https://github.com/api-freaks/apifreaks-mcp/releases)
- [License](https://github.com/api-freaks/apifreaks-mcp/blob/main/LICENSE)
- [Developer Portal](https://apifreaks.com/api)
- [Documentation](https://apifreaks.com/docs)
- [API Reference](https://apifreaks.com/api/swagger)
- [Getting Started](https://apifreaks.com/docs)
- [Support](https://apifreaks.com/contact)
- [GitHub Organization](https://github.com/api-freaks)
- [Blog](https://apifreaks.com/resources/blogs)
- [Pricing](https://apifreaks.com/pricing)
- [Sign Up](https://apifreaks.com/signup)
- [Login](https://apifreaks.com/login)
- [Terms of Service](https://apifreaks.com/terms)
- [Privacy Policy](https://apifreaks.com/privacy-policy)
- [Status Page](https://status.apifreaks.com/)
- [Changelog](https://apifreaks.com/announcements)
- [Postman](https://www.postman.com/apifreaks-official/apifreaks/overview) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Plans](plans/apifreaks-api-hub-for-developers-plans.yml)
- [Rate Limits](rate-limits/apifreaks-api-hub-for-developers-rate-limits.yml)
- [L L Ms Txt](llms/apifreaks-api-hub-for-developers-llms.txt)
- [Well Known](well-known/apifreaks-api-hub-for-developers-well-known.yml)
- [Packages](packages/apifreaks-api-hub-for-developers-packages.yml)
- [S D Ks](packages/apifreaks-api-hub-for-developers-packages.yml)
- [M C P Server](mcp/apifreaks-api-hub-for-developers-mcp.yml)
- [Tool Crosswalk](mcp/apifreaks-api-hub-for-developers-tool-crosswalk.yml)
- [Agent Skill](skills/_index.yml)
- [Authentication](authentication/apifreaks-api-hub-for-developers-authentication.yml)
- [Conventions](conventions/apifreaks-api-hub-for-developers-conventions.yml)
- [Error Catalog](errors/apifreaks-api-hub-for-developers-problem-types.yml)
- [Lifecycle](lifecycle/apifreaks-api-hub-for-developers-lifecycle.yml)
- [Deprecation](https://apifreaks.com/announcements)
- [Changelog](changelog/apifreaks-api-hub-for-developers-changelog.yml)
- [Conformance](conformance/apifreaks-api-hub-for-developers-conformance.yml)
- [Sandbox](sandbox/apifreaks-api-hub-for-developers-sandbox.yml)
- [Webhooks](asyncapi/apifreaks-api-hub-for-developers-pdf-webhooks.yml)
- [Overlay](overlays/apifreaks-api-hub-for-developers-auth-errors-overlay.yaml)
- [Domain Security](security/apifreaks-api-hub-for-developers-domain-security.yml)

## Maintainers

**FN:** JFreaks Software Solutions
**Email:** support@apifreaks.com
**URL:** https://apifreaks.com
