# Adobe Captivate (adobe-captivate)

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

Adobe Captivate is an eLearning authoring tool used to create responsive eLearning content, software demonstrations, and interactive training modules.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/adobe-captivate/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/adobe-captivate/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Authoring
- Education
- eLearning
- LMS
- SCORM
- Training
- xAPI

## Timestamps

- **Created:** 2024-01-20
- **Modified:** 2026-04-19

## APIs

### Adobe Captivate Prime API

Learning Management System API for managing courses, learners, and learning content.

- **Human URL:** [https://www.adobe.com/products/captivateprime.html](https://www.adobe.com/products/captivateprime.html)
- **Base URL:** `https://learningmanager.adobe.com/primeapi/v2`

#### Tags

- Courses
- Learners
- Learning Management
- LMS

#### Properties

- [Documentation](https://captivateprime.adobe.com/docs/primeapi/v2/)
- [OpenAPI](https://learningmanager.adobe.com/primeapi/v2/swagger.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/adobe-captivate-prime-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/adobe-captivate-prime-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adobe-captivate-prime-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://captivateprime.adobe.com/docs/primeapi/v2/#authentication)
- [Postman  Collection](https://www.postman.com/adobe-captivate-prime)
- [JSON Schema](json-schema/prime-api-account-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prime-api-account-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prime-api-badge-list-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/prime-api-account-response-structure.json)
- [JSON Structure](json-structure/prime-api-account-structure.json)
- [JSON Structure](json-structure/prime-api-badge-list-response-structure.json)

### Adobe Captivate SCORM API

API for SCORM-compliant content delivery and tracking.

- **Human URL:** [https://helpx.adobe.com/captivate/using/publish-projects-scorm-compliant-lms.html](https://helpx.adobe.com/captivate/using/publish-projects-scorm-compliant-lms.html)

#### Tags

- Content Delivery
- LMS Integration
- SCORM

#### Properties

- [Documentation](https://scorm.com/scorm-explained/technical-scorm/)
- [Specification](https://adlnet.gov/projects/scorm/)
- [Postman Collection](collections/adobe-captivate-prime-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adobe-captivate-prime-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Adobe Captivate xAPI (Tin Can API)

Experience API for tracking learning experiences.

- **Human URL:** [https://helpx.adobe.com/captivate/using/xapi-tin-can-support.html](https://helpx.adobe.com/captivate/using/xapi-tin-can-support.html)

#### Tags

- Learning Analytics
- Tin Can
- xAPI

#### Properties

- [Documentation](https://xapi.com/overview/)
- [Specification](https://github.com/adlnet/xAPI-Spec)
- [Postman Collection](collections/adobe-captivate-prime-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adobe-captivate-prime-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Adobe Captivate Review API

API for collaborative review and commenting on eLearning projects.

- **Human URL:** [https://helpx.adobe.com/captivate/using/shared-review.html](https://helpx.adobe.com/captivate/using/shared-review.html)

#### Tags

- Collaboration
- Comments
- Review

#### Properties

- [Documentation](https://helpx.adobe.com/captivate/using/shared-review.html)
- [Postman Collection](collections/adobe-captivate-prime-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adobe-captivate-prime-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Adobe Learning Manager Webhooks API

Webhooks API for Adobe Learning Manager that enables real-time event notifications for learner activities, course completions, enrollments, and other learning management events.

- **Human URL:** [https://experienceleague.adobe.com/docs/learning-manager/using/integration/feature-summary/webhooks.html](https://experienceleague.adobe.com/docs/learning-manager/using/integration/feature-summary/webhooks.html)

#### Tags

- Events
- Learning Management
- Notifications
- Webhooks

#### Properties

- [Documentation](https://experienceleague.adobe.com/docs/learning-manager/using/integration/feature-summary/webhooks.html)
- [AsyncAPI](asyncapi/adobe-captivate-learning-manager-webhooks-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [JSON Schema](json-schema/learning-manager-webhooks-badge-awarded-payload-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/learning-manager-webhooks-certification-completed-payload-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/learning-manager-webhooks-course-created-payload-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/learning-manager-webhooks-badge-awarded-payload-structure.json)
- [JSON Structure](json-structure/learning-manager-webhooks-certification-completed-payload-structure.json)
- [JSON Structure](json-structure/learning-manager-webhooks-course-created-payload-structure.json)
- [Postman Collection](collections/adobe-captivate-prime-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adobe-captivate-prime-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [LinkedIn](https://www.linkedin.com/company/adobe-captivate)
- [Support](https://helpx.adobe.com/support/captivate.html)
- [Community](https://community.adobe.com/t5/adobe-captivate/ct-p/ct-captivate)
- [Blog](https://elearning.adobe.com/)
- [Status Page](https://status.adobe.com/)
- [Terms of Service](https://www.adobe.com/legal/terms.html)
- [Privacy Policy](https://www.adobe.com/privacy.html)
- [Contact](https://www.adobe.com/products/captivate/contact.html)
- [Portal](https://experienceleague.adobe.com/docs/learning-manager/using/introduction.html)
- [Getting Started](https://experienceleague.adobe.com/docs/learning-manager/using/getting-started/getting-started.html)
- [Documentation](https://experienceleague.adobe.com/docs/learning-manager/using/home.html)
- [Console](https://developer.adobe.com/console/)
- [Changelog](https://experienceleague.adobe.com/docs/learning-manager/using/whats-new.html)
- [Website](https://business.adobe.com/products/learning-manager/adobe-learning-manager.html)
- [Login](https://learningmanager.adobe.com/)
- [YouTube](https://www.youtube.com/user/AdobeELearning)
- [GitHub Organization](https://github.com/adobe)
- [JSON Schema](json-schema/adobe-captivate-learning-object-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/adobe-captivate-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Spectral Rules](rules/adobe-captivate-spectral-rules.yml)
- [Vocabulary](vocabulary/adobe-captivate-vocabulary.yaml)
- [JSON-LD](json-ld/adobe-captivate-learning-manager-webhooks-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON-LD](json-ld/adobe-captivate-prime-api-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
