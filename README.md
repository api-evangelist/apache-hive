# Apache Hive (apache-hive)
Apache Hive is a data warehouse software that facilitates reading, writing, and managing large datasets residing in distributed storage using SQL. It provides a SQL-like interface called HiveQL for querying data stored in Hadoop, along with a WebHCat REST API for job submission and metastore access.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/apache-hive/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Apache, Big Data, Data Warehouse, ETL, Hadoop, Open Source, SQL

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Apache Hive WebHCat REST API
WebHCat (Templeton) REST API for Apache Hive providing DDL operations, HiveQL job submission, and Hive Metastore metadata access over HTTP.

**Human URL:** [https://cwiki.apache.org/confluence/display/Hive/WebHCat](https://cwiki.apache.org/confluence/display/Hive/WebHCat)

#### Tags:

 - Databases, Jobs, Metastore, REST, Tables

#### Properties

- [Documentation](https://cwiki.apache.org/confluence/display/Hive/WebHCat)
- [OpenAPI](openapi/apache-hive-webhcat-openapi.yml)
- [JSONSchema](json-schema/hive-webhcat-table-schema.json)
- [JSON-LD](json-ld/apache-hive-webhcat-context.jsonld)

### Apache Hive JDBC API
JDBC interface to HiveServer2 for standard SQL client connectivity, supporting parameterized queries, result sets, and connection pooling from Java and ODBC-bridge applications.

**Human URL:** [https://cwiki.apache.org/confluence/display/Hive/HiveServer2+Clients#HiveServer2Clients-JDBC](https://cwiki.apache.org/confluence/display/Hive/HiveServer2+Clients#HiveServer2Clients-JDBC)

#### Tags:

 - JDBC, SDK, SQL

#### Properties

- [Documentation](https://cwiki.apache.org/confluence/display/Hive/HiveServer2+Clients#HiveServer2Clients-JDBC)
- [Java JDBC Driver (Maven Central)](https://search.maven.org/artifact/org.apache.hive/hive-jdbc)

## Common Properties

- [Documentation](https://cwiki.apache.org/confluence/display/Hive/Home)
- [GettingStarted](https://cwiki.apache.org/confluence/display/Hive/GettingStarted)
- [GitHubOrganization](https://github.com/apache)
- [GitHubRepository](https://github.com/apache/hive)

## Features

| Name | Description |
|------|-------------|
| HiveQL SQL Interface | SQL-like query language for reading, writing, and aggregating data stored in distributed storage. |
| WebHCat REST API | HTTP REST API (Templeton) for DDL operations, job submission, and metastore metadata access. |
| HiveServer2 JDBC/ODBC | Thrift-based server with JDBC and ODBC drivers for standard SQL client connectivity. |
| Hive Metastore | Central repository for table schema, partition metadata, and storage location information. |
| Partitioning | Partition tables by column values for efficient query pruning and data organization. |
| ORC and Parquet Storage | Optimized columnar storage formats with predicate pushdown and compression support. |
| ACID Transactions | Full ACID transaction support for inserts, updates, and deletes on managed ORC tables. |
| Vectorized Query Execution | Batch processing of rows in CPU register-width vectors for improved query throughput. |

## Use Cases

| Name | Description |
|------|-------------|
| Data Warehouse Analytics | Run SQL analytics on petabyte-scale datasets stored in HDFS or object storage. |
| ETL Pipeline Orchestration | Use HiveQL scripts to transform and load data between raw and curated data lake zones. |
| Ad-Hoc Data Exploration | Query structured data interactively using Beeline or JDBC-connected BI tools. |
| Log Analysis | Parse and aggregate application logs stored as text or JSON in HDFS using Hive SerDes. |
| Data Catalog Integration | Use the Hive Metastore as a shared schema registry for Spark, Flink, and Presto. |

## Integrations

| Name | Description |
|------|-------------|
| Apache Hadoop HDFS | Hive reads and writes data stored in HDFS as the primary storage layer. |
| Apache Spark | Spark uses the Hive Metastore for table discovery and supports Hive UDFs. |
| Apache HBase | Hive HBase storage handler enables HiveQL queries against HBase tables. |
| Apache Tez | Apache Tez DAG execution engine replaces MapReduce for faster Hive query processing. |
| Presto / Trino | Presto and Trino use the Hive Metastore for table metadata in federated SQL queries. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Apache Hive WebHCat REST API](openapi/apache-hive-webhcat-openapi.yml)

### JSON Schema

- 6 schema files in [json-schema/](json-schema/)

### JSON Structure

- 6 structure files in [json-structure/](json-structure/)

### JSON-LD

- [Apache Hive WebHCat Context](json-ld/apache-hive-webhcat-context.jsonld)

### Examples

- 6 example files in [examples/](examples/)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Apache Hive WebHCat REST API](capabilities/shared/hive-webhcat.yaml) — 5 operations for database, table, and job management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Apache Hive Data Querying](capabilities/hive-data-querying.yaml) | hive-webhcat | 5 | Data Analyst |

## Vocabulary

- [Apache Hive Vocabulary](vocabulary/apache-hive-vocabulary.yaml) — Unified taxonomy mapping 4 resources, 5 actions, 1 workflow, and 1 persona across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Apache Hive Spectral Rules](rules/apache-hive-spectral-rules.yml) — 8 rules across 4 categories enforcing Apache Hive API conventions

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
