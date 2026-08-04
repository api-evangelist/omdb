# OMDb (omdb)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

OMDb (Open Movie Database) is a community-maintained REST API providing movie and TV show metadata, ratings, poster images, and episode data. It supports lookup by IMDb ID or title, full-text search, aggregated ratings from IMDb, Rotten Tomatoes, and Metacritic, and a dedicated high-resolution Poster API for Patreon patrons.

APIs.json: https://raw.githubusercontent.com/api-evangelist/omdb/refs/heads/main/apis.yml

Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=omdb-api-evangelist&utm_content=repo

## Tags

- Movies
- Television
- Entertainment
- Metadata
- Ratings
- Posters
- IMDb
- Open Data

## APIs

| Name | Description | Base URL |
|------|-------------|----------|
| OMDb API | Movie, series, and episode metadata by IMDb ID or title search | https://www.omdbapi.com/ |
| OMDb Poster API | High-resolution poster art for 280,000+ titles (patron only) | https://img.omdbapi.com/ |

## Plans, Rate Limits, and FinOps

| Resource | Path |
|----------|------|
| Plans & Pricing | [plans/omdb-plans-pricing.yml](plans/omdb-plans-pricing.yml) |
| Rate Limits | [rate-limits/omdb-rate-limits.yml](rate-limits/omdb-rate-limits.yml) |
| FinOps | [finops/omdb-finops.yml](finops/omdb-finops.yml) |

OMDb uses a Patreon-based donation model. The free tier allows 1,000 requests/day. Patron tiers (starting at $1/month) unlock the Poster API and higher daily quotas (up to 100,000+ requests/day for higher pledge levels). There is no metered billing; cost is a flat monthly Patreon pledge.

## Timestamps

- **Created:** 2026-06-12
- **Modified:** 2026-06-12

## Common Resources

| Type | URL |
|------|-----|
| Website | https://www.omdbapi.com/ |
| Documentation | https://www.omdbapi.com/ |
| GitHub | https://github.com/omdbapi/OMDb-API |
| Pricing / API Key | https://www.omdbapi.com/apikey.aspx |
| Patreon | https://www.patreon.com/omdb |

## Maintainers

| Name | Email |
|------|-------|
| Kin Lane | kin@apievangelist.com |
