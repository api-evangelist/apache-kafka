# Apache Kafka (apache-kafka)

Apache Kafka is an open-source distributed event streaming platform used by thousands of companies for high-performance data pipelines, streaming analytics, data integration, and mission-critical applications. It provides a REST Proxy API, Kafka Connect REST API, and AsyncAPI for event streaming.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/apache-kafka/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/apache-kafka/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Distributed Systems
- Event Streaming
- Messaging
- Open Source
- Pub-Sub

## Timestamps

- **Created:** 2025-06-05
- **Modified:** 2026-05-19

## APIs

### Kafka REST Proxy API

The Kafka REST Proxy provides a RESTful interface to a Kafka cluster for producing and consuming messages, managing topics, partitions, consumer groups, and viewing cluster state without native Kafka clients.

- **Human URL:** [https://docs.confluent.io/platform/current/kafka-rest/](https://docs.confluent.io/platform/current/kafka-rest/)
- **Base URL:** `http://localhost:8082`

#### Tags

- Consumer Groups
- Proxy
- REST
- Topics

#### Properties

- [Documentation](https://docs.confluent.io/platform/current/kafka-rest/api.html)
- [OpenAPI](openapi/kafka-rest-proxy.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/kafka-rest-proxy.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kafka-rest-proxy.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Kafka Connect REST API

Kafka Connect REST API for managing connectors, their configurations, tasks, and offsets for integrating Kafka with external data systems including databases, object stores, and search indexes.

- **Human URL:** [https://kafka.apache.org/documentation/#connect_rest](https://kafka.apache.org/documentation/#connect_rest)
- **Base URL:** `http://localhost:8083`

#### Tags

- Connect
- Connectors
- Integration

#### Properties

- [Documentation](https://kafka.apache.org/documentation/#connect_rest)
- [OpenAPI](openapi/kafka-connect.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/kafka-connect.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kafka-connect.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Apache Kafka Messaging API

The core Kafka messaging protocol for producing and consuming records to/from topics using the native Kafka binary protocol, supporting exactly-once semantics, compaction, and partitioned log storage.

- **Human URL:** [https://kafka.apache.org/documentation/#producerapi](https://kafka.apache.org/documentation/#producerapi)

#### Tags

- Messaging
- Pub-Sub
- Streaming

#### Properties

- [Documentation](https://kafka.apache.org/documentation/)
- [AsyncAPI](asyncapi/kafka-messaging.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/kafka-connect.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kafka-connect.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/kafka-rest-proxy.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kafka-rest-proxy.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/apachekafka)
- [GitHub Organization](https://github.com/apache)
- [GitHub Repository](https://github.com/apache/kafka)
- [Documentation](https://kafka.apache.org/documentation/)
- [Getting Started](https://kafka.apache.org/quickstart)
- [Terms of Service](https://www.apache.org/licenses/LICENSE-2.0)
- [Versioning](https://kafka.apache.org/downloads)
- [Spectral Rules](rules/apache-kafka-spectral-rules.yml)
- [Vocabulary](vocabulary/apache-kafka-vocabulary.yaml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com
