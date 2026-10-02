---
name: videogen-io-export-project
description: Export a project as MP4 and retrieve the export details.
api: openapi/videogen-io-openapi.json
operations:
- listProjects
- getProject
- exportProject
- listProjectExports
- getProjectExport
generated: '2026-10-02'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/videogen-io-openapi.json ; every operationId checked against the contract
---

# videogen-io-export-project

Export a project as MP4 and retrieve the export details.

## Steps

1. 1. `listProjects` – optional query parameters: `limit`, `cursor` for pagination.
2. 2. `getProject` – path parameter: `projectId`.
3. 3. `exportProject` – path parameter: `projectId`; include any required request body as defined by the API.
4. 4. `listProjectExports` – path parameter: `projectId`; optional query parameters: `limit`, `cursor` for pagination.
5. 5. `getProjectExport` – path parameters: `projectId`, `exportId`.

## Rules

- Include an `Authorization: Bearer <token>` header (bearerAuth).
- Rate limit: 500 requests per hour; exceeding returns HTTP 429.
- Pagination uses `limit` and `cursor` query parameters where supported.
- Handle HTTP 429 responses by implementing retry/back‑off logic.
