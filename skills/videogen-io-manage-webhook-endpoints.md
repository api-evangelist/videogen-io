---
name: videogen-io-manage-webhook-endpoints
description: Create, list, and delete webhook endpoints for the Videogen API.
api: openapi/videogen-io-openapi.json
operations:
- listWebhookEndpoints
- createWebhookEndpoint
- deleteWebhookEndpoint
generated: '2026-10-02'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/videogen-io-openapi.json ; every operationId checked against the contract
---

# videogen-io-manage-webhook-endpoints

Create, list, and delete webhook endpoints for the Videogen API.

## Steps

1. 1. `listWebhookEndpoints` – send a GET request to `/v1/webhooks/endpoints` with optional query parameters `limit` and `cursor` for pagination; include `Authorization: Bearer <token>` header.
2. 2. `createWebhookEndpoint` – send a POST request to `/v1/webhooks/endpoints` with a JSON body defining the webhook endpoint (fields not specified in documentation); include `Authorization: Bearer <token>` header.
3. 3. `deleteWebhookEndpoint` – send a DELETE request to `/v1/webhooks/endpoints/{endpointId}` replacing `{endpointId}` with the target ID; include `Authorization: Bearer <token>` header.

## Rules

- All requests require an `Authorization: Bearer <token>` header (bearerAuth).
- Pagination uses `limit` and `cursor` query parameters on list operations.
- Rate limit is 500 requests per hour; exceeding returns HTTP 429.
