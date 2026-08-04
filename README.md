# DatoCMS (datocms)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

DatoCMS is a headless content management system that enables users to create, manage, and deliver digital content across websites, mobile apps, and other digital experiences. The platform exposes a JSON:API-based Content Management API for content and schema, and a CDN-fronted GraphQL Content Delivery API for read-heavy client applications.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/datocms/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/datocms/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- CMS
- Content Delivery
- Content Management
- GraphQL
- Headless CMS

## Timestamps

- **Created:** 2025-01-08
- **Modified:** 2026-05-19

## APIs

### DatoCMS Content Management API

The DatoCMS Content Management API (CMA) is a JSON:API REST API for managing items, item types, fields, uploads, environments, webhooks, plugins, workflows, and roles on a DatoCMS site. It exposes 150+ endpoints across 40+ resources, authenticated with API tokens.

- **Human URL:** [https://www.datocms.com/docs/content-management-api](https://www.datocms.com/docs/content-management-api)
- **Base URL:** `https://site-api.datocms.com`

#### Tags

- CMA
- CMS
- Content Management
- Headless CMS
- JSON:API

#### Properties

- [Documentation](https://www.datocms.com/docs/content-management-api)
- [Authentication](https://www.datocms.com/docs/content-management-api/authentication)
- [Hyperschema](https://site-api.datocms.com/docs/site-api-hyperschema.json)
- [OpenAPI](openapi/datocms-content-management-api.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/datocms-content-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datocms-content-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/item.json) — [JSON Schema](https://json-schema.org/specification)

### DatoCMS Content Delivery API

The DatoCMS Content Delivery API is a CDN-fronted GraphQL endpoint optimized for low-latency reads of published content from client applications such as Jamstack and SSR sites.

- **Human URL:** [https://www.datocms.com/docs/content-delivery-api](https://www.datocms.com/docs/content-delivery-api)
- **Base URL:** `https://graphql.datocms.com`

#### Tags

- CDN
- Content Delivery
- GraphQL
- Read API

#### Properties

- [Documentation](https://www.datocms.com/docs/content-delivery-api)
- [Postman Collection](collections/datocms-content-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datocms-content-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/datocms)
- [Website](https://www.datocms.com)
- [Documentation](https://www.datocms.com/docs)
- [Pricing](https://www.datocms.com/pricing)
- [Sign Up](https://dashboard.datocms.com/signup)
- [Login](https://dashboard.datocms.com/login)
- [Blog](https://www.datocms.com/blog)
- [Git Hub](https://github.com/datocms)
- [Status Page](https://status.datocms.com)
- [Support](https://www.datocms.com/support)
- [JSON-LD](json-ld/datocms-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Vocabulary](vocabulary/datocms-vocabulary.yml)
- [Capabilities](capabilities/datocms-capabilities.yml)
- [Rules](rules/datocms-rules.yml)
- [Integrations](https://www.datocms.com/marketplace)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
