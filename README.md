# Amazon CloudSearch (amazon-cloudsearch)

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
