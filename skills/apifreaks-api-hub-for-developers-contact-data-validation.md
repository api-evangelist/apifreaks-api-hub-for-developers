---
name: Validate a list of emails and phone numbers
description: >-
  Clean a contact list with the APIFreaks validation APIs — deliverability, disposable/role-based and
  catch-all detection on emails; carrier, line type and E.164 formatting on phone numbers — using the
  bulk paths and respecting the 100-item cap and the email concurrency limit.
api: openapi/apifreaks-api-hub-for-developers-bulk-email-validation-openapi.json
operations: [checkEmail, bulkCheckEmail, validatePhoneNumber, bulkValidatePhoneNumbers, getCreditsUsage]
generated: '2026-08-09'
method: generated
---

# Validate a contact list

## Auth
`X-apiKey: <key>` header.

## Steps

1. **Size the job.** `GET /v1.0/credits/usage/info` — `getCreditsUsage`. Credits are shared across every
   API, so a large validation run competes with everything else on the account.

2. **Chunk to 100.** Every bulk endpoint on this platform caps at **100 items** per request. Over the cap
   is a **413 Payload Too Large**, not a truncated result.

3. **Emails.** `POST https://api.apifreaks.com/v1.0/email-validation/bulk` — `bulkCheckEmail`.
   Returns syntax, MX, disposable, role-based, catch-all and deliverability per address, with per-address
   errors rather than a whole-batch failure. For a single address use
   `POST /v1.0/email-validation/single` — `checkEmail`.

4. **Phones.** `POST /v1.0/phone/validation/bulk` — `bulkValidatePhoneNumbers`. Returns carrier, line
   type, location and E.164/RFC3966 formats across 200+ countries. Single-number form is
   `POST /v1.0/phone/validation` — `validatePhoneNumber`.

## Rules

- **The Email Checker API is concurrency-limited.** Read `X-Concurrent-Threads` and
  `X-Concurrent-Threads-Active` and cap in-flight batches accordingly. A 429 here means too many
  simultaneous requests, not too many per second. Phone validation is not concurrency-limited.
- Per-item errors come back inside a 200 batch response — a 200 does **not** mean every address in the
  batch validated. Inspect each entry.
- POST bodies must be `application/json`. Response format is `json` by default; `format=xml` or an
  `Accept: application/xml` header switches it.
- Credits are charged only on 2xx and refunded on failures.
- No idempotency key; these are read-only classifications, so re-running a batch is safe apart from
  the credit cost.

## See also
- `conventions/apifreaks-api-hub-for-developers-conventions.yml`
- `rate-limits/apifreaks-api-hub-for-developers-rate-limits.yml`
