# Apache Druid (apache-druid)
Apache Druid is a high-performance, real-time analytics database governed by the Apache Software Foundation, designed for fast slice-and-dice OLAP queries on event-time data. It features a distributed, column-oriented storage engine with automatic rollup, supports both streaming (Kafka, Kinesis) and batch (S3, HDFS, local) data ingestion, and provides a SQL query interface plus a native JSON query API via REST. Druid is optimized for sub-second queries at petabyte scale with high concurrency.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/apache-druid/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Analytics, Apache, Database, Kafka, OLAP, Open Source, Real-Time, SQL, Time Series

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Apache Druid REST API
Druid exposes REST APIs for Druid SQL (POST /druid/v2/sql), native JSON queries (POST /druid/v2), batch and streaming data ingestion tasks, supervisor management for Kafka/Kinesis ingestion, data segment management, coordinator and overlord operations, process status, and dynamic configuration. A JDBC driver is also available for SQL access via JDBC clients.

**Human URL:** [https://druid.apache.org/docs/latest/api-reference/](https://druid.apache.org/docs/latest/api-reference/)

#### Tags:

 - Analytics, Data Ingestion, Datasources, JSON Query, Kafka, OLAP, REST, SQL, Segments, Supervisors

#### Properties

- [Documentation](https://druid.apache.org/docs/latest/api-reference/)
- [GettingStarted](https://druid.apache.org/docs/latest/tutorials/tutorial-batch-hadoop)
- [APIReference](https://druid.apache.org/docs/latest/api-reference/)
- [GitHubRepository](https://github.com/apache/druid)
- [Kubernetes Operator](https://github.com/apache/druid-operator)
- [JDBC Driver (Maven)](https://mvnrepository.com/artifact/org.apache.druid/druid-sql)
- [pydruid Python Client](https://pypi.org/project/pydruid/)
- [Ingestion Task](https://raw.githubusercontent.com/api-evangelist/apache-druid/refs/heads/main/json-schema/apache-druid-ingestion-task-schema.json)
- [Sql Query Request](https://raw.githubusercontent.com/api-evangelist/apache-druid/refs/heads/main/json-schema/apache-druid-sql-query-request-schema.json)
- [Sql Query Response](https://raw.githubusercontent.com/api-evangelist/apache-druid/refs/heads/main/json-schema/apache-druid-sql-query-response-schema.json)
- [Supervisor](https://raw.githubusercontent.com/api-evangelist/apache-druid/refs/heads/main/json-schema/apache-druid-supervisor-schema.json)
- [JSONStructure](https://raw.githubusercontent.com/api-evangelist/apache-druid/refs/heads/main/json-structure/apache-druid-ingestion-task-structure.json)
- [JSONStructure](https://raw.githubusercontent.com/api-evangelist/apache-druid/refs/heads/main/json-structure/apache-druid-sql-query-request-structure.json)
- [JSONStructure](https://raw.githubusercontent.com/api-evangelist/apache-druid/refs/heads/main/json-structure/apache-druid-sql-query-response-structure.json)
- [JSONStructure](https://raw.githubusercontent.com/api-evangelist/apache-druid/refs/heads/main/json-structure/apache-druid-supervisor-structure.json)
- [JSONLD](https://raw.githubusercontent.com/api-evangelist/apache-druid/refs/heads/main/json-ld/apache-druid-context.jsonld)
- [Example](https://raw.githubusercontent.com/api-evangelist/apache-druid/refs/heads/main/examples/apache-druid-ingestion-task-example.json)
- [Example](https://raw.githubusercontent.com/api-evangelist/apache-druid/refs/heads/main/examples/apache-druid-sql-query-request-example.json)
- [Example](https://raw.githubusercontent.com/api-evangelist/apache-druid/refs/heads/main/examples/apache-druid-sql-query-response-example.json)
- [Example](https://raw.githubusercontent.com/api-evangelist/apache-druid/refs/heads/main/examples/apache-druid-supervisor-example.json)

## Common Properties

- [Portal](https://druid.apache.org/)
- [Documentation](https://druid.apache.org/docs/latest/)
- [GettingStarted](https://druid.apache.org/docs/latest/tutorials/)
- [Blog](https://druid.apache.org/blog/)
- [GitHubOrganization](https://github.com/apache)
- [GitHubRepository](https://github.com/apache/druid)
- [StackOverflow](https://stackoverflow.com/questions/tagged/druid)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/apache-druid/refs/heads/main/vocabulary/apache-druid-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| Sub-Second OLAP Queries | Columnar storage with bitmap indexes, dictionary encoding, and pre-aggregation (rollup) enables sub-second queries on billions of events. |
| Druid SQL API | REST endpoint for submitting standard SQL queries with ANSI SQL support, time-based filtering, and streaming response options. |
| Native JSON Query API | Druid-native query format (Timeseries, TopN, GroupBy, Scan, Search) for maximum control and performance. |
| Streaming Ingestion | Real-time data ingestion from Apache Kafka and Amazon Kinesis with supervisor-managed offset tracking and exactly-once semantics. |
| Batch Ingestion | Parallel batch indexing tasks from local files, S3, GCS, HDFS, and other external storage systems. |
| Automatic Rollup | Pre-aggregates metrics at ingestion time to reduce storage and query time, configurable per datasource. |
| Time-Based Partitioning | All data is partitioned by time interval (segments), enabling efficient time-range query pruning. |
| Multi-Tenancy | Query isolation and resource management via query lanes, scheduler priorities, and row-level access control. |

## Use Cases

| Name | Description |
|------|-------------|
| Real-Time Event Analytics | Analyze click streams, IoT events, application logs, and user behavior data with sub-second query latency. |
| Business Intelligence Dashboards | Power interactive BI dashboards with high-concurrency low-latency queries backed by Druid's columnar engine. |
| Network and Security Monitoring | Ingest and analyze network flow data and security events in real time for threat detection and capacity planning. |
| Ad Tech Analytics | Process advertising impression, click, and conversion events at high volume with real-time aggregation. |
| Operational Analytics | Monitor application performance metrics and operational data with drilldown and filtering capabilities. |

## Integrations

| Name | Description |
|------|-------------|
| Apache Kafka | KafkaSupervisor for real-time continuous ingestion from Kafka topics into Druid datasources. |
| Amazon Kinesis | KinesisSupervisor for real-time data ingestion from AWS Kinesis data streams. |
| Apache Hadoop / HDFS | Native Hadoop batch indexing task for bulk loading data from HDFS or MapReduce job outputs. |
| Amazon S3 / GCS | Batch and streaming ingestion from object storage (S3, GCS, Azure Blob) using index tasks. |
| Apache Hive | Druid-Hive integration for querying Druid datasources from HiveQL and performing joins. |
| Kubernetes | Official Kubernetes operator for deploying and managing Druid clusters on Kubernetes. |
| Imply (Commercial) | Imply provides a commercial managed Druid service with additional features and enterprise support. |

## Artifacts

Machine-readable schemas for Apache Druid query, ingestion, and supervisor models.

### JSON Schema

- [Ingestion Task](json-schema/apache-druid-ingestion-task-schema.json)
- [Sql Query Request](json-schema/apache-druid-sql-query-request-schema.json)
- [Sql Query Response](json-schema/apache-druid-sql-query-response-schema.json)
- [Supervisor](json-schema/apache-druid-supervisor-schema.json)

### JSON Structure

- [Ingestion Task](json-structure/apache-druid-ingestion-task-structure.json)
- [Sql Query Request](json-structure/apache-druid-sql-query-request-structure.json)
- [Sql Query Response](json-structure/apache-druid-sql-query-response-structure.json)
- [Supervisor](json-structure/apache-druid-supervisor-structure.json)

### JSON-LD

- [Apache Druid](json-ld/apache-druid-context.jsonld)

### Examples

- [Ingestion Task](examples/apache-druid-ingestion-task-example.json)
- [Sql Query Request](examples/apache-druid-sql-query-request-example.json)
- [Sql Query Response](examples/apache-druid-sql-query-response-example.json)
- [Supervisor](examples/apache-druid-supervisor-example.json)

## Vocabulary

- [Apache Druid Vocabulary](vocabulary/apache-druid-vocabulary.yaml) — Taxonomy mapping 6 resources, 6 actions, and 3 personas across Apache Druid real-time OLAP analytics

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
