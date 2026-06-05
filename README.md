# Apache Hive (apache-hive)

Apache Hive is a data warehouse software that facilitates reading, writing, and managing large datasets residing in distributed storage using SQL. It provides a SQL-like interface called HiveQL for querying data stored in Hadoop, along with a WebHCat REST API for job submission and metastore access.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/apache-hive/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/apache-hive/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Apache
- Big Data
- Data Warehouse
- ETL
- Hadoop
- Open Source
- SQL

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-19

## APIs

### Apache Hive WebHCat REST API

WebHCat (Templeton) REST API for Apache Hive providing DDL operations, HiveQL job submission, and Hive Metastore metadata access over HTTP.

- **Human URL:** [https://cwiki.apache.org/confluence/display/Hive/WebHCat](https://cwiki.apache.org/confluence/display/Hive/WebHCat)
- **Base URL:** `http://localhost:50111/templeton/v1`

#### Tags

- Databases
- Jobs
- Metastore
- REST
- Tables

#### Properties

- [Documentation](https://cwiki.apache.org/confluence/display/Hive/WebHCat)
- [OpenAPI](openapi/apache-hive-webhcat-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/apache-hive-webhcat.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apache-hive-webhcat.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/hive-webhcat-table-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/apache-hive-webhcat-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Apache Hive JDBC API

JDBC interface to HiveServer2 for standard SQL client connectivity, supporting parameterized queries, result sets, and connection pooling from Java and ODBC-bridge applications.

- **Human URL:** [https://cwiki.apache.org/confluence/display/Hive/HiveServer2+Clients#HiveServer2Clients-JDBC](https://cwiki.apache.org/confluence/display/Hive/HiveServer2+Clients#HiveServer2Clients-JDBC)

#### Tags

- JDBC
- SQL
- SDK

#### Properties

- [Documentation](https://cwiki.apache.org/confluence/display/Hive/HiveServer2+Clients#HiveServer2Clients-JDBC)
- [SDK](https://search.maven.org/artifact/org.apache.hive/hive-jdbc)
- [Postman Collection](collections/apache-hive-webhcat.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apache-hive-webhcat.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/apache-hive)
- [Documentation](https://cwiki.apache.org/confluence/display/Hive/Home)
- [Getting Started](https://cwiki.apache.org/confluence/display/Hive/GettingStarted)
- [GitHub Organization](https://github.com/apache)
- [GitHub Repository](https://github.com/apache/hive)
- [Spectral Rules](rules/apache-hive-spectral-rules.yml)
- [Vocabulary](vocabulary/apache-hive-vocabulary.yaml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Integrations](https://cwiki.apache.org/confluence/display/connectors)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com
