# OMDb

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

Open Movie Database REST API providing movie and TV show metadata, ratings, poster images, and episode data from a community-maintained database. Supports lookup by IMDb ID or title, full-text search, and a dedicated Poster API for high-resolution cover art available to patrons.

**Areas:** Movies · Television · Entertainment · Metadata · Ratings · Posters · IMDb · Open Data

## OMDb on APIs.io

Everything profiled for OMDb is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/omdb/](https://apis.io/providers/omdb/)** — or go straight to one of the APIs or properties below.

### APIs (4)

- [OMDb Poster API](https://apis.io/apis/omdb/omdb-poster-api/) — Dedicated image endpoint returning high-resolution movie and TV show poster art (up to 2000×3000 px) for over 280,000 titles, updated daily. Access is…
- [OMDb ID Parameter API](https://apis.io/apis/omdb/omdb-id-parameter-api/) — The ID Parameter API from OMDb — 1 operation(s) for id parameter.
- [OMDb Search Parameter API](https://apis.io/apis/omdb/omdb-search-parameter-api/) — The Search Parameter API from OMDb — 1 operation(s) for search parameter.
- [OMDb Title Parameter API](https://apis.io/apis/omdb/omdb-title-parameter-api/) — The Title Parameter API from OMDb — 1 operation(s) for title parameter.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Omdb Agentic Access](https://apis.io/agentic-access/omdb/omdb-agentic-access/)

#### JSON Schema (2)

The data models the API reads and writes.

- [OMDb Search Result](https://apis.io/schemas/omdb/omdb-search-result/)
- [OMDb Title Result](https://apis.io/schemas/omdb/omdb-title-result/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Omdb Context](https://apis.io/jsonld/omdb/omdb-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [OMDb Vocabulary](https://apis.io/vocabularies/omdb/omdb-vocabulary/)

#### Examples (3)

Example requests and responses.

- [Omdb Error Response](https://apis.io/examples/omdb/omdb-error-response/)
- [Omdb Search Results](https://apis.io/examples/omdb/omdb-search-results/)
- [Omdb Title By Id](https://apis.io/examples/omdb/omdb-title-by-id/)

#### Collections (3)

Postman and Open Collection request collections.

- [OMDb ID Parameter API](https://apis.io/collections/omdb/open-omdb-id-parameter-api/)
- [OMDb ID Parameter Search Parameter API](https://apis.io/collections/omdb/open-omdb-search-parameter-api/)
- [OMDb ID Parameter Title Parameter API](https://apis.io/collections/omdb/open-omdb-title-parameter-api/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [OMDb — jsonschema rules](https://apis.io/rules/omdb/omdb-jsonschema-spectral-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Omdb Authentication](https://apis.io/security/omdb/omdb-authentication/)
- [Omdb Domain Security](https://apis.io/security/omdb/omdb-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Omdb Plans Pricing](https://apis.io/plans/omdb/omdb-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Omdb Rate Limits](https://apis.io/rate-limits/omdb/omdb-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Omdb Finops](https://apis.io/finops/omdb/omdb-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.omdbapi.com/)
- [Documentation](https://www.omdbapi.com/)
- [Pricing](https://www.omdbapi.com/apikey.aspx)

## API Evangelist rating

**Kin Score 36.4** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 57.1 |
| Contract quality | 62.4 |
| Contract governance | 23.5 |
| Operational transparency | 13.2 |
| Developer ergonomics | 21.4 |
| Access clarity | 28.9 |

**Agent readiness 26.6** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | na |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | na |
| Error Semantics | — |
| OpenAPI Examples | verified |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | na |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 16.7** — Government & Public Sector

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/omdb/](https://apis.io/providers/omdb/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for OMDb: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/omdb/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
