# Split (split)

Split, now part of Harness Feature Management and Experimentation, is a feature flag and experimentation platform that enables teams to safely release features with controlled rollouts and measure their impact. Their developer platform provides REST APIs for managing feature flags, environments, segments, and workspaces, along with SDKs for evaluating feature flags across multiple languages and platforms.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/split/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/split/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Experimentation
- Feature Flags
- Feature Management
- Rollouts
- SDKs

## Timestamps

- **Created:** 2026-03-20
- **Modified:** 2026-05-19

## APIs

### Split Admin API

The Split Admin API is a REST API that enables programmatic management of workspaces (projects), environments, traffic types, attributes, users, groups, API keys, and change requests within the Split platform (now Harness Feature Management and Experimentation). The API uses resource-oriented URLs, returns JSON responses, and requires Admin API keys for authentication. All endpoints are prefixed with /internal/api/v2 on the api.split.io host.

- **Human URL:** [https://docs.split.io/reference/introduction](https://docs.split.io/reference/introduction)

#### Tags

- Administration
- Experimentation
- Feature Flags
- Feature Management

#### Properties

- [Documentation](https://docs.split.io/reference/introduction)
- [OpenAPI](openapi/split-admin-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/split-admin-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/split-admin-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Structure](json-structure/split-feature-flag-structure.json)

### Split Feature Flag API

The Split Feature Flag API provides endpoints for creating, editing, and deleting feature flags (splits) and their definitions within specific environments. Developers can use this API to define treatments, configure targeting rules, set percentage-based rollouts, and manage feature flag lifecycles programmatically.

- **Human URL:** [https://docs.split.io/reference/feature-flag-overview](https://docs.split.io/reference/feature-flag-overview)

#### Tags

- Feature Flags
- Rollouts
- Targeting
- Treatments

#### Properties

- [Documentation](https://docs.split.io/reference/feature-flag-overview)
- [OpenAPI](openapi/split-feature-flag-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/split-feature-flag-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/split-feature-flag-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Structure](json-structure/split-feature-flag-definition-structure.json)

### Split Evaluator API

The Split Evaluator is an HTTP service that wraps Split SDKs to provide feature flag evaluation via a REST API. It enables applications that cannot directly embed an SDK to request treatment evaluations over HTTP, making it suitable for architectures where a centralized evaluation service is preferred.

- **Human URL:** [https://help.split.io/hc/en-us/articles/360020037072-Split-Evaluator](https://help.split.io/hc/en-us/articles/360020037072-Split-Evaluator)

#### Tags

- Evaluation
- Feature Flags
- Microservices
- Treatments

#### Properties

- [Documentation](https://help.split.io/hc/en-us/articles/360020037072-Split-Evaluator)
- [OpenAPI](openapi/split-evaluator-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/split-evaluator-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/split-evaluator-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Split JavaScript SDK

The Split JavaScript SDK provides client-side integration for feature flag evaluation in browser-based applications. It handles real-time feature flag synchronization, treatment evaluation, event tracking, and impression management.

- **Human URL:** [https://help.split.io/hc/en-us/articles/360020448791-JavaScript-SDK](https://help.split.io/hc/en-us/articles/360020448791-JavaScript-SDK)

#### Tags

- Browser
- Feature Flags
- JavaScript
- SDK

#### Properties

- [Documentation](https://help.split.io/hc/en-us/articles/360020448791-JavaScript-SDK)
- [Postman Collection](collections/split-admin-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/split-admin-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/split-evaluator-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/split-evaluator-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/split-feature-flag-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/split-feature-flag-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Split Node.js SDK

The Split Node.js SDK enables server-side feature flag evaluation for Node.js applications with local evaluation, automatic synchronization, event tracking, and impression logging.

- **Human URL:** [https://help.split.io/hc/en-us/articles/360020564931-Node-js-SDK](https://help.split.io/hc/en-us/articles/360020564931-Node-js-SDK)

#### Tags

- Feature Flags
- Node.js
- SDK
- Server Side

#### Properties

- [Documentation](https://help.split.io/hc/en-us/articles/360020564931-Node-js-SDK)
- [Postman Collection](collections/split-admin-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/split-admin-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/split-evaluator-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/split-evaluator-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/split-feature-flag-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/split-feature-flag-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Split Java SDK

The Split Java SDK provides server-side feature flag evaluation for Java and JVM-based applications with local treatment evaluation and streaming updates.

- **Human URL:** [https://help.split.io/hc/en-us/articles/360020405151-Java-SDK](https://help.split.io/hc/en-us/articles/360020405151-Java-SDK)

#### Tags

- Feature Flags
- Java
- SDK
- Server Side

#### Properties

- [Documentation](https://help.split.io/hc/en-us/articles/360020405151-Java-SDK)
- [Postman Collection](collections/split-admin-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/split-admin-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/split-evaluator-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/split-evaluator-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/split-feature-flag-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/split-feature-flag-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Split Python SDK

The Split Python SDK enables server-side feature flag evaluation for Python applications, suitable for Django, Flask, and other frameworks.

- **Human URL:** [https://help.split.io/hc/en-us/articles/360020359652-Python-SDK](https://help.split.io/hc/en-us/articles/360020359652-Python-SDK)

#### Tags

- Feature Flags
- Python
- SDK
- Server Side

#### Properties

- [Documentation](https://help.split.io/hc/en-us/articles/360020359652-Python-SDK)
- [Postman Collection](collections/split-admin-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/split-admin-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/split-evaluator-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/split-evaluator-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/split-feature-flag-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/split-feature-flag-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Split React SDK

The Split React SDK provides React-specific components and hooks for integrating feature flags including a SplitProvider context, useTreatments hooks, and conditional rendering components.

- **Human URL:** [https://help.split.io/hc/en-us/articles/360038825091-React-SDK](https://help.split.io/hc/en-us/articles/360038825091-React-SDK)

#### Tags

- Feature Flags
- Frontend
- JavaScript
- React
- SDK

#### Properties

- [Documentation](https://help.split.io/hc/en-us/articles/360038825091-React-SDK)
- [Postman Collection](collections/split-admin-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/split-admin-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/split-evaluator-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/split-evaluator-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/split-feature-flag-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/split-feature-flag-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/splitio)
- [LinkedIn](https://www.linkedin.com/company/split-software)
- [Portal](https://docs.split.io/reference/introduction)
- [Documentation](https://help.split.io/hc/en-us)
- [Website](https://www.split.io/)
- [Privacy Policy](https://www.harness.io/legal/privacy)
- [Terms of Service](https://www.harness.io/legal/terms-of-use)
- [Blog](https://www.split.io/blog/)
- [Login](https://app.split.io/login)
- [JSON Schema](json-schema/split-feature-flag-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/split-feature-flag-definition-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/split-segment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/split-feature-flag-structure.json)
- [JSON Structure](json-structure/split-feature-flag-definition-structure.json)
- [JSON-LD](json-ld/split-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Spectral Rules](rules/split-rules.yml)
- [Capabilities](capabilities/feature-flag-management.yaml)
- [Vocabulary](vocabulary/split-vocabulary.yml)
- [Features](undefined)
- [L L Ms Txt](https://docs.split.io/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
