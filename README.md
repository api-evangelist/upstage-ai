# Upstage

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

Upstage is a Korean AI company offering the Solar LLM family and document AI (Document Parse, OCR, Information Extract, Classify) through Upstage Console at https://api.upstage.ai/v1. Its Solar Decide model (beta, built on Solar Mini 4) is exposed at POST /v1/systemone, a System One-style endpoint taking a state plus typed questions (choice, score, noul) and returning calibrated decisions; output tokens are not billed. API references are published as markdown under console.upstage.ai/api/ with an llms.txt index; the reference pages cite OpenAPI files (e.g. ./openapi/openapi-systemone.yaml) that are not publicly retrievable, so no provider-published OpenAPI was saved.

**Areas:** Artificial Intelligence · LLM · Document AI · OCR · Decision Support · Structured Outputs · Embeddings

## Upstage on APIs.io

Everything profiled for Upstage is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/upstage-ai/](https://apis.io/providers/upstage-ai/)** — or go straight to one of the APIs or properties below.

### APIs (12)

- [Upstage Chat Completions API](https://apis.io/apis/upstage-ai/chat-completions/) — POST /chat/completions for Solar models (OpenAI-compatible).
- [Upstage Responses API](https://apis.io/apis/upstage-ai/responses/) — OpenAI-compatible Responses API with structured outputs, tool calling, reasoning and file_search.
- [Upstage Embeddings API](https://apis.io/apis/upstage-ai/embeddings/) — Solar Embedding vectors for passages and queries.
- [Upstage Document Parse API](https://apis.io/apis/upstage-ai/document-parse/) — Parse documents into structured HTML or Markdown, sync and async.
- [Upstage Document OCR API](https://apis.io/apis/upstage-ai/document-ocr/) — OCR for scanned documents and images.
- [Upstage Universal Information Extraction API](https://apis.io/apis/upstage-ai/information-extraction/) — Schema-driven structured extraction from documents, with async and schema generation.
- [Upstage Document Classification API](https://apis.io/apis/upstage-ai/document-classification/) — Classify documents into user-defined classes.
- [Upstage Groundedness Check API](https://apis.io/apis/upstage-ai/groundedness-check/) — Check LLM answers against source context.
- [Upstage Translation API](https://apis.io/apis/upstage-ai/translation/) — Korean, English and Japanese translation models.
- [Upstage Vector Stores API](https://apis.io/apis/upstage-ai/vector-stores/) — Create, manage and search vector stores and file batches for file search.
- [Upstage Agents API](https://apis.io/apis/upstage-ai/agents/) — Run Studio document agents: upload files and create/retrieve jobs.
- [Upstage System One API](https://apis.io/apis/upstage-ai/upstage-ai-system-one-api/) — The System One API from Upstage — 1 operation(s) for system one.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (2)

Model Context Protocol servers that expose the API to agents.

- [MCP server guide](https://apis.io/servers/upstage-ai/mcp-server-guide/)
- [mcp-upstage](https://apis.io/servers/upstage-ai/mcp-upstage/)

#### JSON Schema (2)

The data models the API reads and writes.

- [SystemOneRequest](https://apis.io/schemas/upstage-ai/upstage-ai-system-one-request/)
- [SystemOneResponse](https://apis.io/schemas/upstage-ai/upstage-ai-system-one-response/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Upstage Ai Context](https://apis.io/jsonld/upstage-ai/upstage-ai-context/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Upstage API Rules](https://apis.io/rules/upstage-ai/upstage-ai-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Upstage Ai Authentication](https://apis.io/security/upstage-ai/upstage-ai-authentication/)
- [Upstage Ai Domain Security](https://apis.io/security/upstage-ai/upstage-ai-domain-security/)

#### Rate limits (1)

Published request limits.

- [Upstage Ai Rate Limits](https://apis.io/rate-limits/upstage-ai/upstage-ai-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://upstage.ai)
- [Documentation](https://console.upstage.ai/docs/getting-started)
- [API reference](https://console.upstage.ai/api/chat)
- [Support](https://support.upstage.ai)
- [Changelog](https://console.upstage.ai/docs/resources/changelog)
- [Blog](https://www.upstage.ai/blog)
- [Terms of service](https://console.upstage.ai/docs/terms/terms-of-use)
- [Privacy policy](https://console.upstage.ai/docs/terms/privacy-policy)
- [GitHub](https://github.com/UpstageAI)
- [Status](https://status.upstage.ai/)

## API Evangelist rating

**Kin Score 43.5** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 80.0 |
| Contract quality | 27.7 |
| Contract governance | 22.0 |
| Operational transparency | 86.8 |
| Developer ergonomics | 50.0 |
| Access clarity | 21.1 |

**Agent readiness 24.3** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | documented (partial credit) |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | documented (partial credit) |
| OpenAPI Examples | — |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | na |

**Regulatory alignment 22.7** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/upstage-ai/](https://apis.io/providers/upstage-ai/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Upstage: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/upstage-ai/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
