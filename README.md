# Apache Druid (apache-druid)

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

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/apache-druid/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/apache-druid/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Analytics
- Apache
- Database
- Kafka
- OLAP
- Open Source
- Real-Time
- SQL
- Time Series

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-19

## APIs

### Apache Druid REST API

Druid exposes REST APIs for Druid SQL (POST /druid/v2/sql), native JSON queries (POST /druid/v2), batch and streaming data ingestion tasks, supervisor management for Kafka/Kinesis ingestion, data segment management, coordinator and overlord operations, process status, and dynamic configuration. A JDBC driver is also available for SQL access via JDBC clients.

- **Human URL:** [https://druid.apache.org/docs/latest/api-reference/](https://druid.apache.org/docs/latest/api-reference/)

#### Tags

- Analytics
- Data Ingestion
- Datasources
- JSON Query
- Kafka
- OLAP
- REST
- SQL
- Segments
- Supervisors

#### Properties

- [Documentation](https://druid.apache.org/docs/latest/api-reference/)
- [OpenAPI](openapi/apache-druid-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/apache-druid.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apache-druid.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Getting Started](https://druid.apache.org/docs/latest/tutorials/tutorial-batch-hadoop)
- [API Reference](https://druid.apache.org/docs/latest/api-reference/)
- [GitHub Repository](https://github.com/apache/druid)
- [Tools](https://github.com/apache/druid-operator)
- [SDK](https://mvnrepository.com/artifact/org.apache.druid/druid-sql)
- [SDK](https://pypi.org/project/pydruid/)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/apache-druid/refs/heads/main/json-schema/apache-druid-ingestion-task-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/apache-druid/refs/heads/main/json-schema/apache-druid-sql-query-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/apache-druid/refs/heads/main/json-schema/apache-druid-sql-query-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/apache-druid/refs/heads/main/json-schema/apache-druid-supervisor-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/apache-druid/refs/heads/main/json-structure/apache-druid-ingestion-task-structure.json)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/apache-druid/refs/heads/main/json-structure/apache-druid-sql-query-request-structure.json)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/apache-druid/refs/heads/main/json-structure/apache-druid-sql-query-response-structure.json)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/apache-druid/refs/heads/main/json-structure/apache-druid-supervisor-structure.json)
- [JSON-LD](https://raw.githubusercontent.com/api-evangelist/apache-druid/refs/heads/main/json-ld/apache-druid-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](https://raw.githubusercontent.com/api-evangelist/apache-druid/refs/heads/main/examples/apache-druid-ingestion-task-example.json)
- [Example](https://raw.githubusercontent.com/api-evangelist/apache-druid/refs/heads/main/examples/apache-druid-sql-query-request-example.json)
- [Example](https://raw.githubusercontent.com/api-evangelist/apache-druid/refs/heads/main/examples/apache-druid-sql-query-response-example.json)
- [Example](https://raw.githubusercontent.com/api-evangelist/apache-druid/refs/heads/main/examples/apache-druid-supervisor-example.json)

## Common Properties

- [Portal](https://druid.apache.org/)
- [Documentation](https://druid.apache.org/docs/latest/)
- [Getting Started](https://druid.apache.org/docs/latest/tutorials/)
- [Blog](https://druid.apache.org/blog/)
- [GitHub Organization](https://github.com/apache)
- [GitHub Repository](https://github.com/apache/druid)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/druid)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/apache-druid/refs/heads/main/vocabulary/apache-druid-vocabulary.yaml)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com
