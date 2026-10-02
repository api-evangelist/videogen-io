---
name: videogen-io-create-and-retrieve-entity
description: Create a new entity and then retrieve its details.
api: openapi/videogen-io-openapi.json
operations:
- createEntity
- getEntity
generated: '2026-10-02'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/videogen-io-openapi.json ; every operationId checked against the contract
---

# videogen-io-create-and-retrieve-entity

Create a new entity and then retrieve its details.

## Steps

1. 1. Use `createEntity` with required body fields for the new entity.
2. 2. Use `getEntity` with the `entityId` returned from the creation step.

## Rules

- Include an `Authorization: Bearer <token>` header (bearerAuth).
- Rate limit is 500 requests per hour; exceeding returns HTTP 429.
