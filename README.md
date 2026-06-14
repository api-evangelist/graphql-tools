# GraphQL Tools

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
