# Apache Kafka (apache-kafka)
Apache Kafka is an open-source distributed event streaming platform used by thousands of companies for high-performance data pipelines, streaming analytics, data integration, and mission-critical applications.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/apache-kafka/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Distributed Systems, Event Streaming, Messaging, Open Source, Pub-Sub

## Timestamps

- **Created:** 2025-06-05
- **Modified:** 2026-04-19

## APIs

### Kafka REST Proxy API
The Kafka REST Proxy provides a RESTful interface to a Kafka cluster for producing and consuming messages, managing topics, partitions, and consumer groups.

**Human URL:** [https://docs.confluent.io/platform/current/kafka-rest/](https://docs.confluent.io/platform/current/kafka-rest/)

#### Tags:

 - Consumer Groups, Proxy, REST, Topics

#### Properties

- [Documentation](https://docs.confluent.io/platform/current/kafka-rest/api.html)
- [OpenAPI](openapi/kafka-rest-proxy.yml)

### Kafka Connect REST API
Kafka Connect REST API for managing connectors, their configurations, tasks, and offsets.

**Human URL:** [https://kafka.apache.org/documentation/#connect_rest](https://kafka.apache.org/documentation/#connect_rest)

#### Tags:

 - Connect, Connectors, Integration

#### Properties

- [Documentation](https://kafka.apache.org/documentation/#connect_rest)
- [OpenAPI](openapi/kafka-connect.yml)

### Apache Kafka Messaging API
The core Kafka messaging protocol for producing and consuming records using the native Kafka binary protocol.

**Human URL:** [https://kafka.apache.org/documentation/#producerapi](https://kafka.apache.org/documentation/#producerapi)

#### Tags:

 - Messaging, Pub-Sub, Streaming

#### Properties

- [Documentation](https://kafka.apache.org/documentation/)
- [AsyncAPI](asyncapi/kafka-messaging.yml)

## Common Properties

- [GitHubOrganization](https://github.com/apache)
- [GitHubRepository](https://github.com/apache/kafka)
- [Documentation](https://kafka.apache.org/documentation/)
- [GettingStarted](https://kafka.apache.org/quickstart)
- [TermsOfService](https://www.apache.org/licenses/LICENSE-2.0)
- [Versioning](https://kafka.apache.org/downloads)
- [SpectralRules](rules/apache-kafka-spectral-rules.yml)
- [Vocabulary](vocabulary/apache-kafka-vocabulary.yaml)
- [NaftikoCapability](capabilities/event-streaming.yaml)

## Features

| Name | Description |
|------|-------------|
| High Throughput | Handle millions of messages per second with low latency at massive scale. |
| Exactly-Once Semantics | Guarantee exactly-once message delivery with idempotent producers and transactional APIs. |
| Distributed Replication | Automatic replication across brokers for fault tolerance and high availability. |
| Stream Processing | Real-time stream processing via Kafka Streams library and KSQL. |
| Connector Ecosystem | 200+ pre-built Kafka Connect connectors for databases, clouds, and SaaS. |
| Log Compaction | Retain the latest value for each key with topic log compaction. |
| Consumer Groups | Horizontally scalable consumers with automatic partition rebalancing. |

## Use Cases

| Name | Description |
|------|-------------|
| Event-Driven Architecture | Build event-driven microservices with reliable message delivery. |
| Data Pipeline | Move data between systems at scale with exactly-once delivery guarantees. |
| Real-Time Analytics | Process and analyze event streams in real time with Kafka Streams. |
| Log Aggregation | Centralize application and infrastructure logs for analysis and alerting. |
| CDC (Change Data Capture) | Capture database changes and stream them to data warehouses and caches. |

## Integrations

| Name | Description |
|------|-------------|
| Apache Spark | Spark Structured Streaming integration for batch and streaming analytics. |
| Apache Flink | Native Flink Kafka connector for low-latency stream processing. |
| Debezium | CDC platform using Kafka Connect to capture database change events. |
| Elasticsearch | Kafka Connect Elasticsearch sink for indexing event data. |
| Amazon S3 | Kafka Connect S3 sink for archiving event streams to object storage. |
| Apache Hadoop | HDFS sink connector for streaming data into Hadoop data lake. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Kafka REST Proxy](openapi/kafka-rest-proxy.yml)
- [Kafka Connect](openapi/kafka-connect.yml)

### JSON Schema

19 schema files extracted from the REST Proxy and Connect API OpenAPI specifications.

### JSON Structure

19 JSON Structure files converted from JSON Schema files.

### JSON-LD

Context files generated from JSON Schema definitions.

### Examples

19 example JSON files generated from JSON Schema definitions.

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Kafka REST Proxy API](capabilities/shared/kafka-rest-proxy.yaml) — 2 operations for topic listing and message production
- [Kafka Connect REST API](capabilities/shared/kafka-connect.yaml) — 2 operations for connector management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Apache Kafka Event Streaming](capabilities/event-streaming.yaml) | Kafka REST Proxy API, Kafka Connect REST API | 6 | Data Engineer, Platform Architect |

## Vocabulary

- [Apache Kafka Vocabulary](vocabulary/apache-kafka-vocabulary.yaml) — Unified taxonomy mapping 5 resources, 9 actions, 1 workflow, and 2 personas

## Rules

- [Apache Kafka Spectral Rules](rules/apache-kafka-spectral-rules.yml) — 17 rules across 9 categories enforcing Kafka REST API conventions

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
