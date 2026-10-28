# Apache Druid

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

Apache Druid is a high-performance, real-time analytics database governed by the Apache Software Foundation, designed for fast slice-and-dice OLAP queries on event-time data. It features a distributed, column-oriented storage engine with automatic rollup, supports both streaming (Kafka, Kinesis) and batch (S3, HDFS, local) data ingestion, and provides a SQL query interface plus a native JSON query API via REST. Druid is optimized for sub-second queries at petabyte scale with high concurrency.

**Areas:** Analytics · Apache · Database · Kafka · OLAP · Open Source · Real-Time · SQL · Time Series

## Apache Druid on APIs.io

Everything profiled for Apache Druid is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/apache-druid/](https://apis.io/providers/apache-druid/)** — or go straight to one of the APIs or properties below.

### APIs (1)

- [Apache Druid API](https://apis.io/apis/apache-druid/apache-druid-druid-api/) — The Druid API from Apache Druid — 10 operation(s) for druid.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Apache Druid Agentic Access](https://apis.io/agentic-access/apache-druid/apache-druid-agentic-access/)

#### JSON Schema (4)

The data models the API reads and writes.

- [IngestionTask](https://apis.io/schemas/apache-druid/apache-druid-ingestion-task/)
- [SqlQueryRequest](https://apis.io/schemas/apache-druid/apache-druid-sql-query-request/)
- [SqlQueryResponse](https://apis.io/schemas/apache-druid/apache-druid-sql-query-response/)
- [Supervisor](https://apis.io/schemas/apache-druid/apache-druid-supervisor/)

#### JSON Structure (4)

Data models expressed in JSON Structure.

- [Apache Druid Ingestion Task Structure](https://apis.io/json-structure/apache-druid/apache-druid-ingestion-task-structure/)
- [Apache Druid Sql Query Request Structure](https://apis.io/json-structure/apache-druid/apache-druid-sql-query-request-structure/)
- [Apache Druid Sql Query Response Structure](https://apis.io/json-structure/apache-druid/apache-druid-sql-query-response-structure/)
- [Apache Druid Supervisor Structure](https://apis.io/json-structure/apache-druid/apache-druid-supervisor-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Apache Druid Context](https://apis.io/jsonld/apache-druid/apache-druid-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Apache Druid Vocabulary](https://apis.io/vocabularies/apache-druid/apache-druid-vocabulary/)

#### Examples (4)

Example requests and responses.

- [Apache Druid Ingestion Task Example](https://apis.io/examples/apache-druid/apache-druid-ingestion-task-example/)
- [Apache Druid Sql Query Request Example](https://apis.io/examples/apache-druid/apache-druid-sql-query-request-example/)
- [Apache Druid Sql Query Response Example](https://apis.io/examples/apache-druid/apache-druid-sql-query-response-example/)
- [Apache Druid Supervisor Example](https://apis.io/examples/apache-druid/apache-druid-supervisor-example/)

#### Collections (2)

Postman and Open Collection request collections.

- [Apache Druid REST API](https://apis.io/collections/apache-druid/open-apache-druid/)
- [Apache REST Druid API](https://apis.io/collections/apache-druid/open-apache-druid-druid-api/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Apache Druid — jsonschema rules](https://apis.io/rules/apache-druid/apache-druid-jsonschema-spectral-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Apache Druid Domain Security](https://apis.io/security/apache-druid/apache-druid-domain-security/)
- [Apache Druid Vulnerability Disclosure](https://apis.io/security/apache-druid/apache-druid-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Apache Druid Plans Pricing](https://apis.io/plans/apache-druid/apache-druid-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Apache Druid Rate Limits](https://apis.io/rate-limits/apache-druid/apache-druid-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Apache Druid Finops](https://apis.io/finops/apache-druid/apache-druid-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.apache.org/)
- [Documentation](https://druid.apache.org/docs/latest/)
- [Getting started](https://druid.apache.org/docs/latest/tutorials/)
- [Blog](https://druid.apache.org/blog/)
- [GitHub](https://github.com/apache)

## API Evangelist rating

**Kin Score 36.7** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 57.1 |
| Contract quality | 50.6 |
| Contract governance | 9.8 |
| Operational transparency | 26.3 |
| Developer ergonomics | 47.6 |
| Access clarity | 7.9 |

**Agent readiness 18.4** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | — |
| Auth Clarity | — |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | documented (partial credit) |
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

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/apache-druid/](https://apis.io/providers/apache-druid/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Apache Druid: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/apache-druid/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
