---
name: Render a PDF from an APIFreaks template
description: >-
  Generate a finished PDF from a template designed in the APIFreaks PDF Template Builder — one document from a
  JSON payload, or one document per row of a CSV — and hand back a hosted URL with its expiry.
api: openapi/apifreaks-api-hub-for-developers-pdf-template-apis-api-openapi.yml
operations: [generatePdfFromTemplate, generatePdfsFromCsv, getCreditsUsage]
generated: '2026-09-04'
method: generated
source: >-
  openapi/_original/apifreaks-api-hub-for-developers-pdf-generator-openapi.json and
  ...-pdf-generator-bulk-openapi.json (published 2026-09-03 in @apifreaks/openapi-specs v0.3.2)
---

# Render a PDF from an APIFreaks template

Two operations, both synchronous. Unlike every other PDF operation on this platform they do **not**
return a `taskId` — they render inline and return a hosted URL.

## Before you start

- **The template is not an API resource.** Templates are designed in the browser (PDF Template Builder,
  shipped 2026-07-21) and there is no operation to create, list or version one. You must already have a
  `template_id` copied from the dashboard. If you do not have one, stop and ask — do not guess a UUID.
- **Auth:** `X-apiKey: <key>` header, or `?apiKey=<key>`. One key, one credit pool.
- **Every call is production.** There is no sandbox and no test key. A render spends credits and cannot
  be undone. Check the balance first with `getCreditsUsage` (`GET /v1.0/usage-credits`) — note that this
  operation is *not* exposed as an MCP tool, so over MCP you are spending blind.

## Single document — `generatePdfFromTemplate`

`POST /v1.0/pdf/template/generate`

Query parameters:

| Parameter | Required | Notes |
|---|---|---|
| `template_id` | yes | From the dashboard. |
| `version` | no | Must start with `v` (e.g. `v2`). **`latest` is rejected** — omit the parameter entirely to get the latest version. |
| `data_url` | no | A URL the API fetches your JSON from, *instead of* a request body. |

Supply the data exactly one of two ways: a JSON request body, **or** `data_url`. The body is a free-form
object whose keys are the fields you bound when designing the template, so its shape is yours, not the
API's — the spec declares `additionalProperties: true` and no required keys.

## Bulk — `generatePdfsFromCsv`

`POST /v1.0/pdf/template/generate/bulk`, `multipart/form-data`. One PDF per CSV row. The CSV column
headers must match the template's bound field names.

## Reading the response

```json
{
  "template_id": "…",
  "pdf_url": "https://…/Candidate%20Resume_2026….pdf",
  "created_at": "2026-08-10T14:12:17.673Z",
  "expiration_time": "2026-11-10T14:12:17.673Z"
}
```

**Read `expiration_time` and act on it.** The hosted PDF is temporary and this field is the only expiry
signal the platform publishes anywhere. APIFreaks does *not* state a retention policy in prose, so do not
assume the 90 days the published example happens to show — if the document matters, download it from
`pdf_url` and store it yourself.

## Failure handling

- Errors use the platform envelope `{timestamp, path, status, error, message}` — **not** RFC 9457
  problem+json. See `errors/apifreaks-api-hub-for-developers-problem-types.yml`.
- These two operations declare `400, 401, 403, 404, 415, 422, 500, 504`. A `404` here usually means the
  `template_id` or `version` does not exist, not that the endpoint is wrong.
- `402` (credits exhausted) is documented on the platform docs page but declared on **no** operation in
  the published contract. Handle it anyway.
- **Never blind-retry.** There is no `Idempotency-Key` on this API and no replay protection; the MCP
  server annotates these tools `idempotentHint: false`. A retried render produces a second document and
  charges a second time. Credits are refunded on 4xx/5xx but never on a successful call you did not want.
- `X-AF-Credits-Cost` on the response tells you what the call actually cost.
