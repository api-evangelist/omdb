# OMDb (omdb)

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
