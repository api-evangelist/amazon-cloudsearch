# Amazon CloudSearch (amazon-cloudsearch)
Amazon CloudSearch is a managed search service that makes it easy to set up, manage, and scale a search solution for your website or application. Supports full-text search, Boolean search, faceted search, autocomplete, geospatial search, and 34 languages.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/amazon-cloudsearch/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AWS, CloudSearch, Search, Full-Text Search, Managed

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Amazon CloudSearch API
API for creating and managing CloudSearch domains, uploading documents, configuring search fields and suggesters, and executing search queries.

**Human URL:** [https://aws.amazon.com/cloudsearch/](https://aws.amazon.com/cloudsearch/)

#### Tags:

 - AWS, CloudSearch, Search, Full-Text Search

#### Properties

- [Documentation](https://docs.aws.amazon.com/cloudsearch/latest/developerguide/what-is-cloudsearch.html)
- [OpenAPI](openapi/amazon-cloudsearch-openapi.yml)
- [APIReference](https://docs.aws.amazon.com/cloudsearch/latest/developerguide/what-is-cloudsearch.html)

## Common Properties

- [Portal](https://aws.amazon.com/)
- [Website](https://aws.amazon.com/cloudsearch/)
- [SpectralRules](rules/amazon-cloudsearch-spectral-rules.yml)
- [Vocabulary](vocabulary/amazon-cloudsearch-vocabulary.yaml)
- [NaftikoCapability](capabilities/search-management.yaml)

## Features

| Name | Description |
|------|-------------|
| Managed Search Infrastructure | Set up, manage, and scale search without becoming a search expert. |
| Multi-Language Support | Full-text search across 34 languages with language-specific analyzers. |
| Faceted Search | Narrow search results by category with faceted navigation. |
| Autocomplete Suggestions | Real-time search suggestions as users type. |
| Automatic Scaling | Automatically scale resources as data volume and query traffic change. |
| High Availability | Distribute search traffic across multiple availability zones with Multi-AZ. |

## Use Cases

| Name | Description |
|------|-------------|
| Website Search | Add powerful full-text search capabilities to websites and web applications. |
| E-Commerce Product Search | Enable customers to find products with faceted filtering and relevance ranking. |
| Document Search | Search across large document repositories with Boolean and proximity search. |
| Geospatial Search | Find resources by location with geospatial search queries. |

## Integrations

| Name | Description |
|------|-------------|
| Amazon S3 | Index documents stored in S3 buckets. |
| Amazon DynamoDB | Search DynamoDB data by exporting to CloudSearch. |
| AWS IAM | Control access to search domains with IAM policies. |
| Amazon CloudFront | Cache search results at CloudFront edge for lower latency. |

## Artifacts

### OpenAPI

- [Amazon CloudSearch API](openapi/amazon-cloudsearch-openapi.yml)

### JSON Schema

- [CreateDomainRequest](json-schema/cloudsearch-create-domain-request-schema.json)
- [CreateDomainResponse](json-schema/cloudsearch-create-domain-response-schema.json)
- [DescribeDomainsResponse](json-schema/cloudsearch-describe-domains-response-schema.json)
- [DeleteDomainResponse](json-schema/cloudsearch-delete-domain-response-schema.json)
- [DomainStatus](json-schema/cloudsearch-domain-status-schema.json)

### JSON-LD

- [Amazon CloudSearch Context](json-ld/amazon-cloudsearch-context.jsonld)

## Capabilities

### Shared Per-API Definitions

- [Amazon CloudSearch](capabilities/shared/cloudsearch.yaml) — 6 operations

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Search Domain Management](capabilities/search-management.yaml) | Amazon CloudSearch | 6 | Application Developer |

## Vocabulary

- [Amazon CloudSearch Vocabulary](vocabulary/amazon-cloudsearch-vocabulary.yaml) — Unified taxonomy covering operations, workflows, and personas

## Rules

- [Amazon CloudSearch Spectral Rules](rules/amazon-cloudsearch-spectral-rules.yml) — 19 rules enforcing Amazon CloudSearch API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
