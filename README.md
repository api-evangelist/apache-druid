# Apache Druid (apache-druid)

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
