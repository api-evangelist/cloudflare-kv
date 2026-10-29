# Cloudflare KV

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

Cloudflare Workers KV is a globally distributed key-value store that allows developers to store and retrieve data at low latency from Cloudflare's edge network. It provides a REST API for reading, writing, deleting, and listing key-value pairs across namespaces, making it ideal for caching, configuration management, session storage, API authorization, and dynamic routing. KV supports eventual consistency across Cloudflare's global network with read latencies under 5ms, and is accessible both via Workers bindings and external REST API calls.

**Areas:** Key-Value Store · Edge Computing · Cloudflare Workers · Distributed Storage · Global Database · Cache · Configuration Management

## Cloudflare KV on APIs.io

Everything profiled for Cloudflare KV is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/cloudflare-kv/](https://apis.io/providers/cloudflare-kv/)** — or go straight to one of the APIs or properties below.

### APIs (1)

- [Cloudflare KV Workers KV Namespace API](https://apis.io/apis/cloudflare-kv/cloudflare-kv-workers-kv-namespace-api/) — The Workers KV Namespace API from Cloudflare KV — 8 operation(s) for workers kv namespace.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Cloudflare Kv Agentic Access](https://apis.io/agentic-access/cloudflare-kv/cloudflare-kv-agentic-access/)

#### JSON Schema (27)

The data models the API reads and writes.

- [Any](https://apis.io/schemas/cloudflare-kv/workers-kv_any/)
- [Api Response Collection](https://apis.io/schemas/cloudflare-kv/workers-kv_api-response-collection/)
- [Api Response Common](https://apis.io/schemas/cloudflare-kv/workers-kv_api-response-common/)
- [Api Response Common Failure](https://apis.io/schemas/cloudflare-kv/workers-kv_api-response-common-failure/)
- [Api Response Common No Result](https://apis.io/schemas/cloudflare-kv/workers-kv_api-response-common-no-result/)
- [Bulk Get Result](https://apis.io/schemas/cloudflare-kv/workers-kv_bulk-get-result/)
- [Bulk Get Result With Metadata](https://apis.io/schemas/cloudflare-kv/workers-kv_bulk-get-result-with-metadata/)
- [Bulk Result](https://apis.io/schemas/cloudflare-kv/workers-kv_bulk-result/)
- [Bulk Delete](https://apis.io/schemas/cloudflare-kv/workers-kv_bulk_delete/)
- [Bulk Write](https://apis.io/schemas/cloudflare-kv/workers-kv_bulk_write/)
- [Create Rename Namespace Body](https://apis.io/schemas/cloudflare-kv/workers-kv_create_rename_namespace_body/)
- [Cursor](https://apis.io/schemas/cloudflare-kv/workers-kv_cursor/)
- [Cursor Result Info](https://apis.io/schemas/cloudflare-kv/workers-kv_cursor_result_info/)
- [Expiration](https://apis.io/schemas/cloudflare-kv/workers-kv_expiration/)
- [Expiration Ttl](https://apis.io/schemas/cloudflare-kv/workers-kv_expiration_ttl/)
- [Identifier](https://apis.io/schemas/cloudflare-kv/workers-kv_identifier/)
- [Key](https://apis.io/schemas/cloudflare-kv/workers-kv_key/)
- [Key Name](https://apis.io/schemas/cloudflare-kv/workers-kv_key_name/)
- [Key Name Bulk](https://apis.io/schemas/cloudflare-kv/workers-kv_key_name_bulk/)
- [List Metadata](https://apis.io/schemas/cloudflare-kv/workers-kv_list_metadata/)
- [Messages](https://apis.io/schemas/cloudflare-kv/workers-kv_messages/)
- [Metadata](https://apis.io/schemas/cloudflare-kv/workers-kv_metadata/)
- [Namespace](https://apis.io/schemas/cloudflare-kv/workers-kv_namespace/)
- [Namespace Identifier](https://apis.io/schemas/cloudflare-kv/workers-kv_namespace_identifier/)
- [Namespace Title](https://apis.io/schemas/cloudflare-kv/workers-kv_namespace_title/)
- …and 2 more published on APIs.io

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Cloudflare Kv Context](https://apis.io/jsonld/cloudflare-kv/cloudflare-kv-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Cloudflare Workers KV Vocabulary](https://apis.io/vocabularies/cloudflare-kv/cloudflare-kv-vocabulary/)

#### Collections (1)

Postman and Open Collection request collections.

- [Cloudflare Workers KV Workers KV Namespace API](https://apis.io/collections/cloudflare-kv/open-cloudflare-kv-workers-kv-namespace-api/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Cloudflare KV — jsonschema rules](https://apis.io/rules/cloudflare-kv/cloudflare-kv-jsonschema-spectral-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Cloudflare Kv Domain Security](https://apis.io/security/cloudflare-kv/cloudflare-kv-domain-security/)
- [Cloudflare Kv Vulnerability Disclosure](https://apis.io/security/cloudflare-kv/cloudflare-kv-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Cloudflare Kv Plans Pricing](https://apis.io/plans/cloudflare-kv/cloudflare-kv-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Cloudflare Kv Rate Limits](https://apis.io/rate-limits/cloudflare-kv/cloudflare-kv-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Cloudflare Kv Finops](https://apis.io/finops/cloudflare-kv/cloudflare-kv-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.cloudflare.com/products/kv/)
- [Documentation](https://developers.cloudflare.com/kv/)
- [Getting started](https://developers.cloudflare.com/kv/get-started/)
- [Pricing](https://developers.cloudflare.com/kv/platform/pricing/)
- [Blog](https://blog.cloudflare.com/)
- [Status](https://www.cloudflarestatus.com/)

## API Evangelist rating

**Kin Score 34.7** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 52.6 |
| Contract governance | 9.8 |
| Operational transparency | 44.7 |
| Developer ergonomics | 23.8 |
| Access clarity | 15.8 |

**Agent readiness 21.1** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | — |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
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

**Regulatory alignment 16.7** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/cloudflare-kv/](https://apis.io/providers/cloudflare-kv/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Cloudflare KV: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/cloudflare-kv/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
