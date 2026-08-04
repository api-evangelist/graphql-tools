# GraphQL Tools

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

The Guild toolkit for building and merging GraphQL schemas with schema stitching, federation, schema delegation, mocking, and schema transformation utilities.

## Overview

GraphQL Tools is a comprehensive monorepo of `@graphql-tools/*` npm packages maintained by [The Guild](https://the-guild.dev). Originally created by the Apollo team, the project is now stewarded by The Guild and follows a GraphQL-first, SDL-first development philosophy. It is MIT-licensed and free to use in any project.

**Website:** https://the-guild.dev/graphql/tools  
**Documentation:** https://the-guild.dev/graphql/tools/docs  
**GitHub:** https://github.com/ardatan/graphql-tools  
**LinkedIn:** https://www.linkedin.com/company/the-guild-software

## Key Capabilities

- **Schema Building** — create executable GraphQL schemas from SDL with full resolver support
- **Schema Stitching** — combine multiple GraphQL services into a single unified gateway
- **Schema Merging** — merge local schema instances without a remote proxy layer
- **Mocking** — generate fine-grained, per-type mock data for GraphQL APIs
- **Schema Transformation** — rename, filter, wrap, and delegate across schema boundaries
- **Federation Support** — consume Apollo Federation services inside a stitching gateway

## Core Packages

| Package | Purpose |
|---------|---------|
| `@graphql-tools/schema` | Build executable schemas from SDL |
| `@graphql-tools/stitch` | Schema stitching gateway |
| `@graphql-tools/merge` | Merge multiple schemas locally |
| `@graphql-tools/mock` | Mocking utilities |
| `@graphql-tools/utils` | Shared utility functions |
| `@graphql-tools/load` | Load GraphQL documents from files |
| `@graphql-tools/executor` | Execute GraphQL operations |

## Plans & Pricing

GraphQL Tools is free and open source. The Guild offers paid consulting and support services for enterprise teams. See [plans/graphql-tools-plans.md](plans/graphql-tools-plans.md).

## Rate Limits

GraphQL Tools is a client-side library with no imposed rate limits. See [rate-limits/graphql-tools-rate-limits.md](rate-limits/graphql-tools-rate-limits.md) for runtime and infrastructure considerations.

## FinOps

Direct cost is zero (MIT license). Operational costs relate to infrastructure and optional managed services. See [finops/graphql-tools-finops.md](finops/graphql-tools-finops.md).

## Maintainer

Kin Lane — kin@apievangelist.com
