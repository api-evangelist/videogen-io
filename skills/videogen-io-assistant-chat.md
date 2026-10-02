---
name: videogen-io-assistant-chat
description: Start an assistant chat, send a message, and retrieve the assistant's response.
api: openapi/videogen-io-openapi.json
operations:
- startAssistantChat
- sendAssistantMessage
- getAssistantMessage
generated: '2026-10-02'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/videogen-io-openapi.json ; every operationId checked against the contract
---

# videogen-io-assistant-chat

Start an assistant chat, send a message, and retrieve the assistant's response.

## Steps

1. 1. `startAssistantChat` – send a POST to `/v1/assistants` with the required Authorization: Bearer <token> header.
2. 2. `sendAssistantMessage` – POST to `/v1/assistants/{assistantId}/messages` using the `assistantId` returned from step 1 and the Authorization header.
3. 3. `getAssistantMessage` – GET `/v1/assistant-messages/{messageId}` with the `messageId` returned from step 2 and the Authorization header.

## Rules

- Authentication: Include an `Authorization: Bearer <token>` header for every request (bearerAuth).
- Rate limiting: Maximum 500 requests per hour; exceeding returns HTTP 429.
- Pagination (if applicable): Use `limit` and `cursor` query parameters.
