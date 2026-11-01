# VideoGen

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

VideoGen provides an AI-powered platform that automates video creation from scripts, voiceovers, and storyboards. Users can generate explainer videos, ads, tutorials, and social media clips at scale via a single API call. The service includes tools for text‑to‑video, image‑to‑video, AI avatars, and customizable workflows, targeting creators, marketers, and enterprises seeking fast, cost‑effective video production.

**Areas:** Company · Artificial Intelligence · Video · Automation · Platform

## VideoGen on APIs.io

Everything profiled for VideoGen is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/videogen-io/](https://apis.io/providers/videogen-io/)** — or go straight to one of the APIs or properties below.

### APIs (11)

- [VideoGen Account API](https://apis.io/apis/videogen-io/videogen-io-account-api/) — Look up the account and team behind the API key. Useful as a connection test to confirm a key is valid.
- [VideoGen Assistant API](https://apis.io/apis/videogen-io/videogen-io-assistant-api/) — Converse with the VideoGen AI assistant inside a project. Start a chat, send messages, and act on the assistant's suggestions (pick a workflow, approve a…
- [VideoGen Entities API](https://apis.io/apis/videogen-io/videogen-io-entities-api/) — Reusable actors and visual styles. Attach their reference images to workflows for consistent characters and looks across generations.
- [VideoGen Files API](https://apis.io/apis/videogen-io/videogen-io-files-api/) — List and retrieve metadata for generated files.
- [VideoGen Projects API](https://apis.io/apis/videogen-io/videogen-io-projects-api/) — Read project metadata and status.
- [VideoGen Resources API](https://apis.io/apis/videogen-io/videogen-io-resources-api/) — Discover available TTS voices and supported languages to use in requests.
- [VideoGen Text API](https://apis.io/apis/videogen-io/videogen-io-text-api/) — Generate text with a general-purpose language model. Synchronous — the response includes the generated text.
- [VideoGen Tools API](https://apis.io/apis/videogen-io/videogen-io-tools-api/) — Generate images, videos, audio, and more. All tool endpoints are asynchronous.
- [VideoGen Webhook events API](https://apis.io/apis/videogen-io/videogen-io-webhook-events-api/) — Event payloads delivered to your registered webhook endpoints.
- [VideoGen Webhooks API](https://apis.io/apis/videogen-io/videogen-io-webhooks-api/) — Register endpoints to receive `tool_execution.*` and `workflow_run.*` events instead of polling.
- [VideoGen Workflows API](https://apis.io/apis/videogen-io/videogen-io-workflows-api/) — End-to-end async video workflows. Each endpoint starts a workflow run that creates a project and generates a video.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Videogen Io Webhooks](https://apis.io/asyncapis/videogen-io/videogen-io-webhooks/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Videogen Io Agentic Access](https://apis.io/agentic-access/videogen-io/videogen-io-agentic-access/)

#### JSON Schema (6)

The data models the API reads and writes.

- [FileInfo](https://apis.io/schemas/videogen-io/videogen-io-file-info/)
- [GenerateVideoClipRequest](https://apis.io/schemas/videogen-io/videogen-io-generate-video-clip-request/)
- [ScriptToVideoRequest](https://apis.io/schemas/videogen-io/videogen-io-script-to-video-request/)
- [SlideshowToVideoRequest](https://apis.io/schemas/videogen-io/videogen-io-slideshow-to-video-request/)
- [VoiceoverToVideoRequest](https://apis.io/schemas/videogen-io/videogen-io-voiceover-to-video-request/)
- [WorkflowRun](https://apis.io/schemas/videogen-io/videogen-io-workflow-run/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Videogen Io Context](https://apis.io/jsonld/videogen-io/videogen-io-context/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [VideoGen API Rules](https://apis.io/rules/videogen-io/videogen-io-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Videogen Io Authentication](https://apis.io/security/videogen-io/videogen-io-authentication/)
- [Videogen Io Domain Security](https://apis.io/security/videogen-io/videogen-io-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Videogen Io Plans Pricing](https://apis.io/plans/videogen-io/videogen-io-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Videogen Io Rate Limits](https://apis.io/rate-limits/videogen-io/videogen-io-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://videogen.io)
- [Documentation](https://docs.videogen.io/introduction)
- [Getting started](https://docs.videogen.io/getting-started)
- [Pricing](https://videogen.io/pricing)
- [Sign up](https://app.videogen.io/signup?internalReferrerPath=%2F)
- [Support](https://help.videogen.io/en/)
- [Changelog](https://videogen.io/changelog)
- [Blog](https://videogen.io/blog)
- [Terms of service](https://videogen.io/terms-of-service)
- [Privacy policy](https://videogen.io/privacy-policy)

## API Evangelist rating

**Kin Score 64.8** — strong · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 75.0 |
| Contract quality | 68.8 |
| Contract governance | 22.0 |
| Operational transparency | 65.8 |
| Developer ergonomics | 66.1 |
| Access clarity | 76.3 |

**Agent readiness 34.1** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | derived (partial credit) |
| OpenAPI Examples | — |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | yes |
| Agent Skills | derived (partial credit) |
| Well Known Catalog | yes |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | distinct |

**Regulatory alignment 22.7** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/videogen-io/](https://apis.io/providers/videogen-io/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for VideoGen: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/videogen-io/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
