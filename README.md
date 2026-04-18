# Android (android)
Collection of APIs and services available in the Android ecosystem.

**URL:** [Visit APIs.json URL](https://developer.android.com/reference)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AI, Android, Automotive, Google, Machine Learning, Mobile Development, SDK, TV, Wearables

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-18

## APIs

### Android Platform APIs
Core Android framework APIs for building Android applications.

**Human URL:** [https://developer.android.com/reference](https://developer.android.com/reference)

#### Tags:

 - Android, Framework, Mobile, SDK

#### Properties

- [Documentation](https://developer.android.com/docs)
- [APIReference](https://developer.android.com/reference)
- [GettingStarted](https://developer.android.com/training/basics/firstapp)
- [CodeExamples](https://developer.android.com/samples)
- [ReleaseNotes](https://developer.android.com/tools/releases/platforms)
- [Features](https://developer.android.com/about/versions/16/features)

### Google Play Developer APIs
Suite of REST-based web service APIs for performing publishing, reporting, and app-management functions programmatically.

**Human URL:** [https://developer.android.com/google/play/developer-api](https://developer.android.com/google/play/developer-api)

#### Tags:

 - App Management, Google Play, Publishing, Purchases, Reporting, REST API, Reviews, Subscriptions

#### Properties

- [Documentation](https://developer.android.com/google/play/developer-api)
- [APIReference](https://developers.google.com/android-publisher/api-ref/rest)
- [OpenAPI](openapi/google-play-developer-api.yml)
- [JSONSchema](json-schema/android-app-schema.json)
- [JSONLD](json-ld/android-context.jsonld)
- [ReleaseNotes](https://developer.android.com/google/play/billing/play-developer-apis-release-notes)

### Firebase Android APIs
Firebase SDKs and APIs for Android app development.

**Human URL:** [https://firebase.google.com/docs/android/setup](https://firebase.google.com/docs/android/setup)

#### Tags:

 - Analytics, Authentication, Backend, Cloud Messaging, Database, Firebase

#### Properties

- [Documentation](https://firebase.google.com/docs/android/setup)
- [APIReference](https://firebase.google.com/docs/reference/android)
- [CodeExamples](https://github.com/firebase/quickstart-android)
- [Console](https://console.firebase.google.com)
- [ReleaseNotes](https://firebase.google.com/support/release-notes/android)

### Google Maps Android API
Add maps, location, and geospatial data to Android applications.

**Human URL:** [https://developers.google.com/maps/documentation/android-sdk](https://developers.google.com/maps/documentation/android-sdk)

#### Tags:

 - Geolocation, Location, Maps, Navigation

#### Properties

- [Documentation](https://developers.google.com/maps/documentation/android-sdk)
- [APIReference](https://developers.google.com/android/reference/com/google/android/gms/maps/package-summary)
- [Pricing](https://developers.google.com/maps/pricing-and-plans)
- [GettingStarted](https://developers.google.com/maps/documentation/android-sdk/start)
- [CodeExamples](https://github.com/googlemaps/android-samples)

### Android Jetpack APIs
Suite of libraries to help developers follow best practices.

**Human URL:** [https://developer.android.com/jetpack](https://developer.android.com/jetpack)

#### Tags:

 - Architecture, Compose, Jetpack, Libraries, UI

#### Properties

- [Documentation](https://developer.android.com/jetpack/getting-started)
- [APIReference](https://developer.android.com/jetpack/androidx)
- [ReleaseNotes](https://developer.android.com/jetpack/androidx/versions)
- [CodeExamples](https://developer.android.com/jetpack/samples)

### Gemini Nano On-Device AI API
On-device generative AI powered by Gemini Nano for summarization, proofreading, rewriting, and image description without network connectivity.

**Human URL:** [https://developer.android.com/ai/gemini-nano](https://developer.android.com/ai/gemini-nano)

#### Tags:

 - AI, Gemini Nano, Generative AI, LLM, Machine Learning, On-Device

#### Properties

- [Documentation](https://developer.android.com/ai/gemini-nano)

## Common Properties

- [Portal](https://developer.android.com)
- [Blog](https://android-developers.googleblog.com)
- [GitHubOrganization](https://github.com/android)
- [StackOverflow](https://stackoverflow.com/questions/tagged/android)
- [X](https://twitter.com/AndroidDev)
- [YouTube](https://www.youtube.com/user/androiddevelopers)
- [GettingStarted](https://developer.android.com/get-started/overview)
- [Training](https://developer.android.com/courses)
- [ReleaseNotes](https://developer.android.com/about/versions)

## Features

| Name | Description |
|------|-------------|
| Jetpack Compose | Modern declarative UI toolkit for building native Android interfaces with less code and powerful tools. |
| Material Design | Design system providing components, layouts, and guidelines for building consistent Android user experiences. |
| On-Device AI | Run machine learning models locally on devices with ML Kit and Gemini Nano for privacy-preserving AI features. |
| Health Connect | Unified health data platform allowing apps to share and access user health and fitness data with user consent. |
| Multi-Device Experiences | Build apps that work seamlessly across phones, tablets, wearables, TVs, and cars with adaptive layouts. |
| App Security | Protect apps with Play Integrity API, Credential Manager for passkeys, and built-in security best practices. |

## Use Cases

| Name | Description |
|------|-------------|
| Mobile App Development | Build native Android applications for phones and tablets using Kotlin, Jetpack, and Material Design. |
| Wearable Apps | Create watch face designs and health-focused apps for Wear OS smartwatches and fitness devices. |
| In-Vehicle Experiences | Build media, messaging, and navigation apps for Android Auto and Android Automotive OS. |
| TV Entertainment | Develop media streaming and entertainment apps optimized for the large-screen TV experience. |
| In-App Monetization | Implement subscriptions, in-app purchases, and advertising revenue using Google Play Billing and AdMob. |

## Integrations

| Name | Description |
|------|-------------|
| Firebase | Integrate cloud backend services including authentication, real-time database, cloud messaging, and analytics. |
| Google Maps | Add interactive maps, location services, and geospatial data to Android applications. |
| Google Play Services | Access Google platform capabilities including authentication, location, and Google Drive APIs. |
| TensorFlow Lite | Deploy custom machine learning models on Android devices for real-time inference with hardware acceleration. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Google Play Developer API](openapi/google-play-developer-api.yml)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Google Play Developer API](capabilities/shared/google-play-developer.yaml) — 7 operations for purchases, subscriptions, and reviews

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [App Monetization and Reviews](capabilities/app-monetization.yaml) | Google Play Developer | 7 | App Developer / Product Manager |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
