# Threads API

The Meta Threads API enables developers to build integrations for the Threads social media platform. It supports publishing text, image, video, carousel, and quote posts, reading and managing replies, accessing profile information, retrieving media insights, and managing account settings.

**Developer Documentation:** [https://developers.facebook.com/docs/threads/](https://developers.facebook.com/docs/threads/)

## APIs

| Name | Description | Documentation |
|------|-------------|---------------|
| [Threads API](https://developers.facebook.com/docs/threads/) | Publish posts, manage replies, read insights, and access profiles on the Threads platform. | [Docs](https://developers.facebook.com/docs/threads/) |

## Common Resources

- **Getting Started:** [https://developers.facebook.com/docs/threads/get-started](https://developers.facebook.com/docs/threads/get-started)
- **Authentication:** [OAuth 2.0 Access Tokens](https://developers.facebook.com/docs/threads/get-started/get-access-tokens-and-permissions)
- **Changelog:** [https://developers.facebook.com/docs/threads/changelog](https://developers.facebook.com/docs/threads/changelog)
- **Webhooks:** [https://developers.facebook.com/docs/threads/webhooks](https://developers.facebook.com/docs/threads/webhooks)
- **Postman Workspace:** [https://www.postman.com/meta/threads/overview](https://www.postman.com/meta/threads/overview)

## OpenAPI Specifications

| File | Description |
|------|-------------|
| [threads-api-openapi.yml](openapi/threads-api-openapi.yml) | Threads API - authorization, publishing, profiles, insights, replies |

## JSON Schemas

| File | Description |
|------|-------------|
| [threads-api-thread-schema.json](json-schema/threads-api-thread-schema.json) | Thread media object schema |

## JSON Structures

| File | Description |
|------|-------------|
| [threads-api-thread-structure.json](json-structure/threads-api-thread-structure.json) | Thread, insight, and pagination structure documentation |

## JSON-LD

| File | Description |
|------|-------------|
| [threads-api-context.jsonld](json-ld/threads-api-context.jsonld) | JSON-LD context mapping Threads vocabulary to schema.org |

## Examples

| File | Description |
|------|-------------|
| [threads-api-get-list-threads-example.json](examples/threads-api-get-list-threads-example.json) | List user threads request/response |
| [threads-api-get-post-insights-example.json](examples/threads-api-get-post-insights-example.json) | Get post insights request/response |

## Spectral Rules

| File | Description |
|------|-------------|
| [threads-api-rules.yml](rules/threads-api-rules.yml) | Spectral ruleset enforcing Threads API conventions |

## Naftiko Capabilities

### Shared Definitions

| File | Description |
|------|-------------|
| [capabilities/shared/threads-api.yaml](capabilities/shared/threads-api.yaml) | Per-API consumed definition for the Threads API |

### Workflow Capabilities

| File | Description | Tools |
|------|-------------|-------|
| [capabilities/social-publishing.yaml](capabilities/social-publishing.yaml) | Social publishing, analytics, and reply management for Threads | 7 tools |

## Vocabulary

| File | Description |
|------|-------------|
| [threads-api-vocabulary.yml](vocabulary/threads-api-vocabulary.yml) | Domain vocabulary for Threads API concepts |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com

---

*Profiled by [API Evangelist](https://apievangelist.com) on 2026-05-03*

