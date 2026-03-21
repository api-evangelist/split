# Split (split)
Split, now part of Harness Feature Management and Experimentation, is a feature flag and experimentation platform that enables teams to safely release features with controlled rollouts and measure their impact. Their developer platform provides REST APIs for managing feature flags, environments, segments, and workspaces, along with SDKs for evaluating feature flags across multiple languages and platforms.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/split/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

 - Feature Flags, Experimentation, Feature Management, SDKs, Rollouts

## Timestamps

- **Created:** 2026-03-20
- **Modified:** 2026-03-20

## APIs

### Split Admin API
The Split Admin API is a REST API that enables programmatic management of feature flags, environments, segments, and workspaces within the Split platform (now Harness Feature Management and Experimentation). Using this API, developers can create, update, delete, and retrieve feature flags, as well as configure targeting rules and segment definitions across environments. The API uses resource-oriented URLs, returns JSON responses, and requires Admin API keys for authentication.

**Human URL:** [https://docs.split.io/reference/introduction](https://docs.split.io/reference/introduction)


#### Tags:

 - Feature Flags, Experimentation, Feature Management, Administration

#### Properties

- [Documentation](https://docs.split.io/reference/introduction)
- [OpenAPI](openapi/split-admin-api-openapi.yml)

### Split Feature Flag API
The Split Feature Flag API provides endpoints for creating, editing, and deleting feature flags and their definitions within specific environments. Developers can use this API to define treatments, configure targeting rules, set percentage-based rollouts, and manage feature flag lifecycles programmatically. It supports operations like creating feature flag definitions in environments, updating targeting configurations, and retrieving flag status across workspaces.

**Human URL:** [https://docs.split.io/reference/feature-flag-overview](https://docs.split.io/reference/feature-flag-overview)


#### Tags:

 - Feature Flags, Targeting, Rollouts, Treatments

#### Properties

- [Documentation](https://docs.split.io/reference/feature-flag-overview)
- [OpenAPI](openapi/split-feature-flag-api-openapi.yml)

### Split Evaluator API
The Split Evaluator is an HTTP service that wraps Split SDKs to provide feature flag evaluation via a REST API. It enables applications that cannot directly embed an SDK to request treatment evaluations over HTTP, making it suitable for architectures where a centralized evaluation service is preferred. The Evaluator can be deployed as a standalone microservice that processes getTreatment calls and returns the appropriate treatments for given users and feature flags.

**Human URL:** [https://help.split.io/hc/en-us/articles/360020037072-Split-Evaluator](https://help.split.io/hc/en-us/articles/360020037072-Split-Evaluator)


#### Tags:

 - Feature Flags, Evaluation, Treatments, Microservices

#### Properties

- [Documentation](https://help.split.io/hc/en-us/articles/360020037072-Split-Evaluator)
- [OpenAPI](openapi/split-evaluator-api-openapi.yml)

### Split JavaScript SDK
The Split JavaScript SDK provides client-side integration for feature flag evaluation in browser-based applications. It handles real-time feature flag synchronization, treatment evaluation, event tracking, and impression management. The SDK supports streaming updates for instant flag changes, local evaluation for low-latency treatment decisions, and built-in support for React and Redux integrations.

**Human URL:** [https://help.split.io/hc/en-us/articles/360020448791-JavaScript-SDK](https://help.split.io/hc/en-us/articles/360020448791-JavaScript-SDK)


#### Tags:

 - JavaScript, SDK, Feature Flags, Browser

#### Properties

- [Documentation](https://help.split.io/hc/en-us/articles/360020448791-JavaScript-SDK)

### Split Node.js SDK
The Split Node.js SDK enables server-side feature flag evaluation for Node.js applications. It provides local evaluation of feature flags with low latency, automatic synchronization of flag definitions, event tracking for experimentation metrics, and impression logging. The SDK is designed for backend services and supports both polling and streaming modes for keeping flag definitions up to date.

**Human URL:** [https://help.split.io/hc/en-us/articles/360020564931-Node-js-SDK](https://help.split.io/hc/en-us/articles/360020564931-Node-js-SDK)


#### Tags:

 - Node.js, SDK, Feature Flags, Server Side

#### Properties

- [Documentation](https://help.split.io/hc/en-us/articles/360020564931-Node-js-SDK)

### Split Java SDK
The Split Java SDK provides server-side feature flag evaluation for Java and JVM-based applications. It enables local treatment evaluation with minimal latency, automatic flag definition synchronization, and event tracking for experimentation. The SDK supports streaming and polling update modes and is suitable for integration into Spring, Micronaut, and other Java-based frameworks and microservice architectures.

**Human URL:** [https://help.split.io/hc/en-us/articles/360020405151-Java-SDK](https://help.split.io/hc/en-us/articles/360020405151-Java-SDK)


#### Tags:

 - Java, SDK, Feature Flags, Server Side

#### Properties

- [Documentation](https://help.split.io/hc/en-us/articles/360020405151-Java-SDK)

### Split Python SDK
The Split Python SDK enables server-side feature flag evaluation for Python applications. It provides local treatment evaluation, automatic synchronization of feature flag definitions, event tracking, and impression management. The SDK is well-suited for Django, Flask, and other Python web frameworks, as well as data pipelines and backend services that need controlled feature rollouts and experimentation.

**Human URL:** [https://help.split.io/hc/en-us/articles/360020359652-Python-SDK](https://help.split.io/hc/en-us/articles/360020359652-Python-SDK)


#### Tags:

 - Python, SDK, Feature Flags, Server Side

#### Properties

- [Documentation](https://help.split.io/hc/en-us/articles/360020359652-Python-SDK)

### Split Android SDK
The Split Android SDK provides feature flag evaluation for native Android applications. It supports local evaluation for low-latency treatment decisions, streaming updates for real-time flag changes, event tracking for experimentation, and impression management. The SDK is available as an open-source library on GitHub and integrates with the Android application lifecycle for efficient resource management.

**Human URL:** [https://www.split.io/product/languages/android-sdk/](https://www.split.io/product/languages/android-sdk/)


#### Tags:

 - Android, SDK, Feature Flags, Mobile

#### Properties

- [Documentation](https://www.split.io/product/languages/android-sdk/)

### Split iOS SDK
The Split iOS SDK provides feature flag evaluation for native iOS applications built with Swift or Objective-C. It supports local treatment evaluation, streaming updates for real-time flag synchronization, event tracking for experimentation metrics, and impression logging. The SDK is distributed via CocoaPods and Swift Package Manager and integrates with the iOS application lifecycle.

**Human URL:** [https://help.split.io/hc/en-us/articles/360020401491-iOS-SDK](https://help.split.io/hc/en-us/articles/360020401491-iOS-SDK)


#### Tags:

 - iOS, SDK, Feature Flags, Mobile, Swift

#### Properties

- [Documentation](https://help.split.io/hc/en-us/articles/360020401491-iOS-SDK)

### Split React SDK
The Split React SDK provides React-specific components and hooks for integrating feature flags into React applications. It wraps the Split JavaScript SDK with React-native patterns including a SplitProvider context, useTreatments hooks, and conditional rendering components. The SDK handles automatic re-rendering when feature flag values change and supports both client-side and server-side rendering scenarios.

**Human URL:** [https://help.split.io/hc/en-us/articles/360038825091-React-SDK](https://help.split.io/hc/en-us/articles/360038825091-React-SDK)


#### Tags:

 - React, SDK, Feature Flags, Frontend, JavaScript

#### Properties

- [Documentation](https://help.split.io/hc/en-us/articles/360038825091-React-SDK)

## Common Properties

- [Portal](https://docs.split.io/reference/introduction)
- [Documentation](https://help.split.io/hc/en-us)
- [Website](https://www.split.io/)
- [PrivacyPolicy](https://www.harness.io/legal/privacy)
- [TermsOfService](https://www.harness.io/legal/terms-of-use)
- [Blog](https://www.split.io/blog/)
- [Login](https://app.split.io/login)

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com
