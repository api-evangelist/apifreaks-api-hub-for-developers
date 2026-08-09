---
name: Run an asynchronous PDF job and collect the result
description: >-
  Drive the APIFreaks PDF pipeline end to end — upload or reference files, start a transform, then either
  poll the task or receive a webhook, download the output, and clean up. This is the only write-bearing,
  stateful and event-producing part of the platform, and the only place where retry semantics matter.
api: openapi/apifreaks-api-hub-for-developers-merge-pdf-openapi.json
operations: [uploadResource, mergePdf, getTaskStatus, downloadResource, getFiles, deleteFile]
generated: '2026-08-09'
method: generated
---

# Asynchronous PDF pipeline

## Auth
`X-apiKey: <key>` header.

## Steps

1. **Get the input in.** Either upload with `POST /v1.0/pdf/resource/upload` — `uploadResource` — and keep
   the returned file id, or attach the PDFs directly as `multipart/form-data` on the transform call.
   Already-uploaded files are referenced with the repeated `file_id` query parameter.

2. **Start the transform.** e.g. `POST https://api.apifreaks.com/v1.0/pdf/merge` — `mergePdf`.
   Up to 100 files per request, merged in the order given.
   Useful parameters: `output` (result filename), `destroy=true` (delete inputs as soon as the output
   exists).
   The response is **not the document** — it is `{ "taskId": "...", "inputIds": [...] }`.

3. **Pick one completion path.**
   - **Poll:** `GET /v1.0/pdf/task-status?task_id=<taskId>` — `getTaskStatus`. Terminal states are
     `completed` (with `outputUrls`, `outputIds`, `expiresAt`) and `failed` (with `error` and `message`).
   - **Webhook:** pass `webhook_url=<https url>` on step 2 and APIFreaks will call it when the task
     finishes. Add `webhook_failure_notification=true` to also get an email if every delivery attempt
     fails, and `X-Webhook-Authorization: Key:Value` to have a header echoed back on the callback.

4. **Download.** `GET /v1.0/pdf/resource/download?resource_id=<outputId>` — `downloadResource`.

5. **Clean up.** `GET /v1.0/pdf/files` — `getFiles` — to list what is still stored, and
   `DELETE /v1.0/pdf/file` — `deleteFile` — to remove it. Outputs expire on their own after **7 days**
   (`expiresAt` is exactly 7 days after `createdAt` in the published example).

## Rules — read these before you retry anything

- **There is no idempotency key on this API.** Re-POSTing `mergePdf` after a timeout creates a *second*
  task and spends credits again. Before retrying a transform, poll `getTaskStatus` for the taskId you
  already have, or list `getFiles`.
- The webhook callback is **not signed**. There is no HMAC, no timestamp and no replay protection —
  only the static header you supplied yourself in `X-Webhook-Authorization`. Verify the taskId against
  your own records before acting on a callback, and never treat the callback body as authoritative
  without re-reading `getTaskStatus`.
- No published retry schedule or attempt count for webhook delivery.
- Failure codes here: **415** unsupported file type, **413** body too large, **400** bad file id or
  neither file nor id supplied. Credits are refunded on all of them.
- A task can also fail *after* a 200 — `getTaskStatus` returns `status: failed` with an `error` such as
  `Invalid Page Range`. A 200 on the transform call means "accepted", not "succeeded".

## See also
- `asyncapi/apifreaks-api-hub-for-developers-pdf-webhooks.yml`
- `conventions/apifreaks-api-hub-for-developers-conventions.yml`
- `errors/apifreaks-api-hub-for-developers-problem-types.yml`
