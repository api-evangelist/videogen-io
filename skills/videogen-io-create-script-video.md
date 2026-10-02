---
name: videogen-io-create-script-video
description: Create a video from a script and monitor its execution.
api: openapi/videogen-io-openapi.json
operations:
- scriptToVideo
- getWorkflowRun
- listWorkflowRuns
generated: '2026-10-02'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/videogen-io-openapi.json ; every operationId checked against the contract
---

# videogen-io-create-script-video

Create a video from a script and monitor its execution.

## Steps

1. 1. `scriptToVideo` – send the script in the request body as defined by the API contract.
2. 2. `getWorkflowRun` – retrieve the status of the workflow run using the `workflowRunId` returned from the previous step.
3. 3. `listWorkflowRuns` – optionally list recent workflow runs to verify the new run appears.

## Rules

- Auth: Include a Bearer token in the `Authorization` header (bearerAuth).
- Rate limiting: Maximum 500 requests per hour; exceeding returns HTTP 429.
- Pagination: Use `limit` and `cursor` query parameters when listing workflow runs.
