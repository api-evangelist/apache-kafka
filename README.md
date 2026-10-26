# Apache Kafka (apache-kafka)

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
