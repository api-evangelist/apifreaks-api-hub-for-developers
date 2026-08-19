# APIFreaks - API Hub for Developers (apifreaks-api-hub-for-developers)

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
