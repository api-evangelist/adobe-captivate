# Adobe Captivate
Adobe Captivate is an eLearning authoring tool used to create responsive eLearning content, software demonstrations, and interactive training modules.

**URL:** [https://raw.githubusercontent.com/api-evangelist/adobe-captivate/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/adobe-captivate/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Authoring, Education, eLearning, LMS, SCORM, Training, xAPI

## Timestamps

- **Created:** 2024-01-20
- **Modified:** 2026-04-19

## APIs

### Adobe Captivate Prime API
Learning Management System API for managing courses, learners, and learning content.

**Human URL:** [https://www.adobe.com/products/captivateprime.html](https://www.adobe.com/products/captivateprime.html)

#### Tags:

 - Courses, Learners, Learning Management, LMS

#### Properties

- [Documentation](https://captivateprime.adobe.com/docs/primeapi/v2/)
- [OpenAPI](https://learningmanager.adobe.com/primeapi/v2/swagger.json)
- [OpenAPI](openapi/adobe-captivate-prime-api-openapi.yml)
- [Authentication](https://captivateprime.adobe.com/docs/primeapi/v2/#authentication)
- [Postman Collection](https://www.postman.com/adobe-captivate-prime)
- [JSONSchema](json-schema/prime-api-account-response-schema.json)
- [JSONSchema](json-schema/prime-api-account-schema.json)
- [JSONSchema](json-schema/prime-api-badge-list-response-schema.json)
- [JSONStructure](json-structure/prime-api-account-response-structure.json)
- [JSONStructure](json-structure/prime-api-account-structure.json)
- [JSONStructure](json-structure/prime-api-badge-list-response-structure.json)

### Adobe Captivate SCORM API
API for SCORM-compliant content delivery and tracking.

**Human URL:** [https://helpx.adobe.com/captivate/using/publish-projects-scorm-compliant-lms.html](https://helpx.adobe.com/captivate/using/publish-projects-scorm-compliant-lms.html)

#### Tags:

 - Content Delivery, LMS Integration, SCORM

#### Properties

- [Documentation](https://scorm.com/scorm-explained/technical-scorm/)
- [Specification](https://adlnet.gov/projects/scorm/)

### Adobe Captivate xAPI (Tin Can API)
Experience API for tracking learning experiences.

**Human URL:** [https://helpx.adobe.com/captivate/using/xapi-tin-can-support.html](https://helpx.adobe.com/captivate/using/xapi-tin-can-support.html)

#### Tags:

 - Learning Analytics, Tin Can, xAPI

#### Properties

- [Documentation](https://xapi.com/overview/)
- [Specification](https://github.com/adlnet/xAPI-Spec)

### Adobe Captivate Review API
API for collaborative review and commenting on eLearning projects.

**Human URL:** [https://helpx.adobe.com/captivate/using/shared-review.html](https://helpx.adobe.com/captivate/using/shared-review.html)

#### Tags:

 - Collaboration, Comments, Review

#### Properties

- [Documentation](https://helpx.adobe.com/captivate/using/shared-review.html)

### Adobe Learning Manager Webhooks API
Webhooks API for Adobe Learning Manager that enables real-time event notifications for learner activities, course completions, enrollments, and other learning management events.

**Human URL:** [https://experienceleague.adobe.com/docs/learning-manager/using/integration/feature-summary/webhooks.html](https://experienceleague.adobe.com/docs/learning-manager/using/integration/feature-summary/webhooks.html)

#### Tags:

 - Events, Learning Management, Notifications, Webhooks

#### Properties

- [Documentation](https://experienceleague.adobe.com/docs/learning-manager/using/integration/feature-summary/webhooks.html)
- [AsyncAPI](asyncapi/adobe-captivate-learning-manager-webhooks-asyncapi.yml)
- [JSONSchema](json-schema/learning-manager-webhooks-badge-awarded-payload-schema.json)
- [JSONSchema](json-schema/learning-manager-webhooks-certification-completed-payload-schema.json)
- [JSONSchema](json-schema/learning-manager-webhooks-course-created-payload-schema.json)
- [JSONStructure](json-structure/learning-manager-webhooks-badge-awarded-payload-structure.json)
- [JSONStructure](json-structure/learning-manager-webhooks-certification-completed-payload-structure.json)
- [JSONStructure](json-structure/learning-manager-webhooks-course-created-payload-structure.json)

## Common Properties

- [Support](https://helpx.adobe.com/support/captivate.html)
- [Community](https://community.adobe.com/t5/adobe-captivate/ct-p/ct-captivate)
- [Blog](https://elearning.adobe.com/)
- [StatusPage](https://status.adobe.com/)
- [TermsOfService](https://www.adobe.com/legal/terms.html)
- [PrivacyPolicy](https://www.adobe.com/privacy.html)
- [Contact](https://www.adobe.com/products/captivate/contact.html)
- [Portal](https://experienceleague.adobe.com/docs/learning-manager/using/introduction.html)
- [GettingStarted](https://experienceleague.adobe.com/docs/learning-manager/using/getting-started/getting-started.html)
- [Documentation](https://experienceleague.adobe.com/docs/learning-manager/using/home.html)
- [Console](https://developer.adobe.com/console/)
- [ChangeLog](https://experienceleague.adobe.com/docs/learning-manager/using/whats-new.html)
- [Website](https://business.adobe.com/products/learning-manager/adobe-learning-manager.html)
- [Login](https://learningmanager.adobe.com/)
- [YouTube](https://www.youtube.com/user/AdobeELearning)
- [GitHubOrganization](https://github.com/adobe)
- [JSONSchema](json-schema/adobe-captivate-learning-object-schema.json)
- [JSON-LD](json-ld/adobe-captivate-context.jsonld)
- [SpectralRules](rules/adobe-captivate-spectral-rules.yml)
- [NaftikoCapability](capabilities/learning-management.yaml)
- [Vocabulary](vocabulary/adobe-captivate-vocabulary.yaml)
- [JSON-LD](json-ld/adobe-captivate-learning-manager-webhooks-context.jsonld)
- [JSON-LD](json-ld/adobe-captivate-prime-api-context.jsonld)

## Features

| Name | Description |
|------|-------------|
| Learning Object Management | Create and manage courses, learning programs, certifications, and job aids with full CRUD operations via REST API. |
| Learner Enrollment and Tracking | Programmatically enroll learners, track progress, and retrieve completion status across all learning objects. |
| Webhook Event Notifications | Receive real-time HTTP POST notifications for enrollment, completion, badge, and certification events. |
| Gamification and Badges | Manage gamification points, leaderboards, and badge awards to motivate learners. |
| Catalog Management | Organize and expose learning content through catalogs with filtering and tagging capabilities. |
| Skill Tracking | Associate skills with learning content and track learner skill attainment through the API. |
| OAuth 2.0 Authentication | Secure API access using OAuth 2.0 with role-based scopes for admin, learner, manager, and author roles. |
| SCORM and xAPI Support | Deliver and track SCORM-compliant and xAPI (Tin Can) learning content for LMS interoperability. |
| Bulk Data Import/Export | Use the Jobs API to import and export users, enrollments, and completion data in bulk. |
| Notification Management | Manage announcements and notifications sent to learners, managers, and administrators. |

## Use Cases

| Name | Description |
|------|-------------|
| HR System Integration | Automatically provision users from HRIS systems like Workday or SAP SuccessFactors into Adobe Learning Manager. |
| Custom Learning Portal | Build branded training portals that surface Adobe Learning Manager content through the REST API. |
| Compliance Training Automation | Auto-enroll new hires in mandatory compliance courses and track completion for regulatory reporting. |
| Learning Analytics Dashboard | Extract learner progress and completion data to build custom analytics and reporting dashboards. |
| E-Commerce Integration | Integrate course purchases with e-commerce platforms and auto-enroll paying customers. |
| Real-Time Progress Monitoring | Use webhooks to monitor learner activity in real time and trigger downstream workflows on completion. |
| Certification Management | Automate certification enrollment, renewal reminders, and expiry tracking using the REST API. |

## Integrations

| Name | Description |
|------|-------------|
| Salesforce | Sync learner data and completion status between Adobe Learning Manager and Salesforce CRM. |
| Microsoft Teams | Surface learning content and notifications directly within Microsoft Teams via connector. |
| Workday | Import organizational user data from Workday HCM to manage learner accounts automatically. |
| SAP SuccessFactors | Bi-directional sync with SAP SuccessFactors for user provisioning and learning record exchange. |
| Adobe Experience Manager | Embed learning content and catalogs within Adobe Experience Manager sites. |
| Zoom | Schedule and launch virtual classroom sessions directly from Adobe Learning Manager. |
| LinkedIn Learning | Import LinkedIn Learning content into Adobe Learning Manager catalogs for blended learning. |
| SCORM Cloud | Host and launch SCORM content packages through SCORM Cloud integration. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Adobe Captivate Prime Api Openapi](openapi/adobe-captivate-prime-api-openapi.yml)

### AsyncAPI

- [Adobe Captivate Learning Manager Webhooks Asyncapi](asyncapi/adobe-captivate-learning-manager-webhooks-asyncapi.yml)

### JSON Schema

- [Adobe Captivate Learning Object](json-schema/adobe-captivate-learning-object-schema.json)
- [Learning Manager Webhooks Badge Awarded Payload](json-schema/learning-manager-webhooks-badge-awarded-payload-schema.json)
- [Learning Manager Webhooks Certification Completed Payload](json-schema/learning-manager-webhooks-certification-completed-payload-schema.json)
- [Learning Manager Webhooks Course Created Payload](json-schema/learning-manager-webhooks-course-created-payload-schema.json)
- [Learning Manager Webhooks Course Updated Payload](json-schema/learning-manager-webhooks-course-updated-payload-schema.json)
- [Learning Manager Webhooks Job Completed Payload](json-schema/learning-manager-webhooks-job-completed-payload-schema.json)
- [Learning Manager Webhooks Learner Completion Payload](json-schema/learning-manager-webhooks-learner-completion-payload-schema.json)
- [Learning Manager Webhooks Learner Enrollment Payload](json-schema/learning-manager-webhooks-learner-enrollment-payload-schema.json)
- [Learning Manager Webhooks Learner Progress Payload](json-schema/learning-manager-webhooks-learner-progress-payload-schema.json)
- [Learning Manager Webhooks Learner Reference](json-schema/learning-manager-webhooks-learner-reference-schema.json)
- [Learning Manager Webhooks Learner Unenrollment Payload](json-schema/learning-manager-webhooks-learner-unenrollment-payload-schema.json)
- [Learning Manager Webhooks Learning Object Reference](json-schema/learning-manager-webhooks-learning-object-reference-schema.json)
- [Learning Manager Webhooks Skill Achieved Payload](json-schema/learning-manager-webhooks-skill-achieved-payload-schema.json)
- [Learning Manager Webhooks User Created Payload](json-schema/learning-manager-webhooks-user-created-payload-schema.json)
- [Learning Manager Webhooks User Deleted Payload](json-schema/learning-manager-webhooks-user-deleted-payload-schema.json)
- [Learning Manager Webhooks User Updated Payload](json-schema/learning-manager-webhooks-user-updated-payload-schema.json)
- [Learning Manager Webhooks Webhook Event Base](json-schema/learning-manager-webhooks-webhook-event-base-schema.json)
- [Prime Api Account Response](json-schema/prime-api-account-response-schema.json)
- [Prime Api Account](json-schema/prime-api-account-schema.json)
- [Prime Api Badge List Response](json-schema/prime-api-badge-list-response-schema.json)
- [Prime Api Badge Response](json-schema/prime-api-badge-response-schema.json)
- [Prime Api Badge](json-schema/prime-api-badge-schema.json)
- [Prime Api Catalog List Response](json-schema/prime-api-catalog-list-response-schema.json)
- [Prime Api Catalog Response](json-schema/prime-api-catalog-response-schema.json)
- [Prime Api Catalog](json-schema/prime-api-catalog-schema.json)
- [Prime Api Certification List Response](json-schema/prime-api-certification-list-response-schema.json)
- [Prime Api Enrollment Create Request](json-schema/prime-api-enrollment-create-request-schema.json)
- [Prime Api Enrollment List Response](json-schema/prime-api-enrollment-list-response-schema.json)
- [Prime Api Enrollment Response](json-schema/prime-api-enrollment-response-schema.json)
- [Prime Api Enrollment](json-schema/prime-api-enrollment-schema.json)
- [Prime Api Gamification Points Response](json-schema/prime-api-gamification-points-response-schema.json)
- [Prime Api Gamification Points](json-schema/prime-api-gamification-points-schema.json)
- [Prime Api Job Create Request](json-schema/prime-api-job-create-request-schema.json)
- [Prime Api Job List Response](json-schema/prime-api-job-list-response-schema.json)
- [Prime Api Job Response](json-schema/prime-api-job-response-schema.json)
- [Prime Api Job](json-schema/prime-api-job-schema.json)
- [Prime Api Learning Object Instance List Response](json-schema/prime-api-learning-object-instance-list-response-schema.json)
- [Prime Api Learning Object Instance](json-schema/prime-api-learning-object-instance-schema.json)
- [Prime Api Learning Object List Response](json-schema/prime-api-learning-object-list-response-schema.json)
- [Prime Api Learning Object Response](json-schema/prime-api-learning-object-response-schema.json)
- [Prime Api Learning Object](json-schema/prime-api-learning-object-schema.json)
- [Prime Api Localized Metadata](json-schema/prime-api-localized-metadata-schema.json)
- [Prime Api Notification List Response](json-schema/prime-api-notification-list-response-schema.json)
- [Prime Api Notification](json-schema/prime-api-notification-schema.json)
- [Prime Api Pagination Links](json-schema/prime-api-pagination-links-schema.json)
- [Prime Api Relationship](json-schema/prime-api-relationship-schema.json)
- [Prime Api Resource Identifier](json-schema/prime-api-resource-identifier-schema.json)
- [Prime Api Skill List Response](json-schema/prime-api-skill-list-response-schema.json)
- [Prime Api Skill Response](json-schema/prime-api-skill-response-schema.json)
- [Prime Api Skill](json-schema/prime-api-skill-schema.json)
- [Prime Api User Badge List Response](json-schema/prime-api-user-badge-list-response-schema.json)
- [Prime Api User Group List Response](json-schema/prime-api-user-group-list-response-schema.json)
- [Prime Api User Group Response](json-schema/prime-api-user-group-response-schema.json)
- [Prime Api User Group](json-schema/prime-api-user-group-schema.json)
- [Prime Api User List Response](json-schema/prime-api-user-list-response-schema.json)
- [Prime Api User Response](json-schema/prime-api-user-response-schema.json)
- [Prime Api User](json-schema/prime-api-user-schema.json)
- [Prime Api User Skill List Response](json-schema/prime-api-user-skill-list-response-schema.json)
- [Prime Api User Update Request](json-schema/prime-api-user-update-request-schema.json)

### JSON Structure

- [Adobe Captivate Learning Object](json-structure/adobe-captivate-learning-object-structure.json)
- [Learning Manager Webhooks Badge Awarded Payload](json-structure/learning-manager-webhooks-badge-awarded-payload-structure.json)
- [Learning Manager Webhooks Certification Completed Payload](json-structure/learning-manager-webhooks-certification-completed-payload-structure.json)
- [Learning Manager Webhooks Course Created Payload](json-structure/learning-manager-webhooks-course-created-payload-structure.json)
- [Learning Manager Webhooks Course Updated Payload](json-structure/learning-manager-webhooks-course-updated-payload-structure.json)
- [Learning Manager Webhooks Job Completed Payload](json-structure/learning-manager-webhooks-job-completed-payload-structure.json)
- [Learning Manager Webhooks Learner Completion Payload](json-structure/learning-manager-webhooks-learner-completion-payload-structure.json)
- [Learning Manager Webhooks Learner Enrollment Payload](json-structure/learning-manager-webhooks-learner-enrollment-payload-structure.json)
- [Learning Manager Webhooks Learner Progress Payload](json-structure/learning-manager-webhooks-learner-progress-payload-structure.json)
- [Learning Manager Webhooks Learner Reference](json-structure/learning-manager-webhooks-learner-reference-structure.json)
- [Learning Manager Webhooks Learner Unenrollment Payload](json-structure/learning-manager-webhooks-learner-unenrollment-payload-structure.json)
- [Learning Manager Webhooks Learning Object Reference](json-structure/learning-manager-webhooks-learning-object-reference-structure.json)
- [Learning Manager Webhooks Skill Achieved Payload](json-structure/learning-manager-webhooks-skill-achieved-payload-structure.json)
- [Learning Manager Webhooks User Created Payload](json-structure/learning-manager-webhooks-user-created-payload-structure.json)
- [Learning Manager Webhooks User Deleted Payload](json-structure/learning-manager-webhooks-user-deleted-payload-structure.json)
- [Learning Manager Webhooks User Updated Payload](json-structure/learning-manager-webhooks-user-updated-payload-structure.json)
- [Learning Manager Webhooks Webhook Event Base](json-structure/learning-manager-webhooks-webhook-event-base-structure.json)
- [Prime Api Account Response](json-structure/prime-api-account-response-structure.json)
- [Prime Api Account](json-structure/prime-api-account-structure.json)
- [Prime Api Badge List Response](json-structure/prime-api-badge-list-response-structure.json)
- [Prime Api Badge Response](json-structure/prime-api-badge-response-structure.json)
- [Prime Api Badge](json-structure/prime-api-badge-structure.json)
- [Prime Api Catalog List Response](json-structure/prime-api-catalog-list-response-structure.json)
- [Prime Api Catalog Response](json-structure/prime-api-catalog-response-structure.json)
- [Prime Api Catalog](json-structure/prime-api-catalog-structure.json)
- [Prime Api Certification List Response](json-structure/prime-api-certification-list-response-structure.json)
- [Prime Api Enrollment Create Request](json-structure/prime-api-enrollment-create-request-structure.json)
- [Prime Api Enrollment List Response](json-structure/prime-api-enrollment-list-response-structure.json)
- [Prime Api Enrollment Response](json-structure/prime-api-enrollment-response-structure.json)
- [Prime Api Enrollment](json-structure/prime-api-enrollment-structure.json)
- [Prime Api Gamification Points Response](json-structure/prime-api-gamification-points-response-structure.json)
- [Prime Api Gamification Points](json-structure/prime-api-gamification-points-structure.json)
- [Prime Api Job Create Request](json-structure/prime-api-job-create-request-structure.json)
- [Prime Api Job List Response](json-structure/prime-api-job-list-response-structure.json)
- [Prime Api Job Response](json-structure/prime-api-job-response-structure.json)
- [Prime Api Job](json-structure/prime-api-job-structure.json)
- [Prime Api Learning Object Instance List Response](json-structure/prime-api-learning-object-instance-list-response-structure.json)
- [Prime Api Learning Object Instance](json-structure/prime-api-learning-object-instance-structure.json)
- [Prime Api Learning Object List Response](json-structure/prime-api-learning-object-list-response-structure.json)
- [Prime Api Learning Object Response](json-structure/prime-api-learning-object-response-structure.json)
- [Prime Api Learning Object](json-structure/prime-api-learning-object-structure.json)
- [Prime Api Localized Metadata](json-structure/prime-api-localized-metadata-structure.json)
- [Prime Api Notification List Response](json-structure/prime-api-notification-list-response-structure.json)
- [Prime Api Notification](json-structure/prime-api-notification-structure.json)
- [Prime Api Pagination Links](json-structure/prime-api-pagination-links-structure.json)
- [Prime Api Relationship](json-structure/prime-api-relationship-structure.json)
- [Prime Api Resource Identifier](json-structure/prime-api-resource-identifier-structure.json)
- [Prime Api Skill List Response](json-structure/prime-api-skill-list-response-structure.json)
- [Prime Api Skill Response](json-structure/prime-api-skill-response-structure.json)
- [Prime Api Skill](json-structure/prime-api-skill-structure.json)
- [Prime Api User Badge List Response](json-structure/prime-api-user-badge-list-response-structure.json)
- [Prime Api User Group List Response](json-structure/prime-api-user-group-list-response-structure.json)
- [Prime Api User Group Response](json-structure/prime-api-user-group-response-structure.json)
- [Prime Api User Group](json-structure/prime-api-user-group-structure.json)
- [Prime Api User List Response](json-structure/prime-api-user-list-response-structure.json)
- [Prime Api User Response](json-structure/prime-api-user-response-structure.json)
- [Prime Api User Skill List Response](json-structure/prime-api-user-skill-list-response-structure.json)
- [Prime Api User](json-structure/prime-api-user-structure.json)
- [Prime Api User Update Request](json-structure/prime-api-user-update-request-structure.json)

### JSON-LD

- [Adobe Captivate Context](json-ld/adobe-captivate-context.jsonld)
- [Adobe Captivate Learning Manager Webhooks Context](json-ld/adobe-captivate-learning-manager-webhooks-context.jsonld)
- [Adobe Captivate Prime Api Context](json-ld/adobe-captivate-prime-api-context.jsonld)

### Examples

- [Adobe Captivate Learning Object](examples/adobe-captivate-learning-object-example.json)
- [Learning Manager Webhooks Badge Awarded Payload](examples/learning-manager-webhooks-badge-awarded-payload-example.json)
- [Learning Manager Webhooks Certification Completed Payload](examples/learning-manager-webhooks-certification-completed-payload-example.json)
- [Learning Manager Webhooks Course Created Payload](examples/learning-manager-webhooks-course-created-payload-example.json)
- [Learning Manager Webhooks Course Updated Payload](examples/learning-manager-webhooks-course-updated-payload-example.json)
- [Learning Manager Webhooks Job Completed Payload](examples/learning-manager-webhooks-job-completed-payload-example.json)
- [Learning Manager Webhooks Learner Completion Payload](examples/learning-manager-webhooks-learner-completion-payload-example.json)
- [Learning Manager Webhooks Learner Enrollment Payload](examples/learning-manager-webhooks-learner-enrollment-payload-example.json)
- [Learning Manager Webhooks Learner Progress Payload](examples/learning-manager-webhooks-learner-progress-payload-example.json)
- [Learning Manager Webhooks Learner Reference](examples/learning-manager-webhooks-learner-reference-example.json)
- [Learning Manager Webhooks Learner Unenrollment Payload](examples/learning-manager-webhooks-learner-unenrollment-payload-example.json)
- [Learning Manager Webhooks Learning Object Reference](examples/learning-manager-webhooks-learning-object-reference-example.json)
- [Learning Manager Webhooks Skill Achieved Payload](examples/learning-manager-webhooks-skill-achieved-payload-example.json)
- [Learning Manager Webhooks User Created Payload](examples/learning-manager-webhooks-user-created-payload-example.json)
- [Learning Manager Webhooks User Deleted Payload](examples/learning-manager-webhooks-user-deleted-payload-example.json)
- [Learning Manager Webhooks User Updated Payload](examples/learning-manager-webhooks-user-updated-payload-example.json)
- [Learning Manager Webhooks Webhook Event Base](examples/learning-manager-webhooks-webhook-event-base-example.json)
- [Prime Api Account](examples/prime-api-account-example.json)
- [Prime Api Account Response](examples/prime-api-account-response-example.json)
- [Prime Api Badge](examples/prime-api-badge-example.json)
- [Prime Api Badge List Response](examples/prime-api-badge-list-response-example.json)
- [Prime Api Badge Response](examples/prime-api-badge-response-example.json)
- [Prime Api Catalog](examples/prime-api-catalog-example.json)
- [Prime Api Catalog List Response](examples/prime-api-catalog-list-response-example.json)
- [Prime Api Catalog Response](examples/prime-api-catalog-response-example.json)
- [Prime Api Certification List Response](examples/prime-api-certification-list-response-example.json)
- [Prime Api Enrollment Create Request](examples/prime-api-enrollment-create-request-example.json)
- [Prime Api Enrollment](examples/prime-api-enrollment-example.json)
- [Prime Api Enrollment List Response](examples/prime-api-enrollment-list-response-example.json)
- [Prime Api Enrollment Response](examples/prime-api-enrollment-response-example.json)
- [Prime Api Gamification Points](examples/prime-api-gamification-points-example.json)
- [Prime Api Gamification Points Response](examples/prime-api-gamification-points-response-example.json)
- [Prime Api Job Create Request](examples/prime-api-job-create-request-example.json)
- [Prime Api Job](examples/prime-api-job-example.json)
- [Prime Api Job List Response](examples/prime-api-job-list-response-example.json)
- [Prime Api Job Response](examples/prime-api-job-response-example.json)
- [Prime Api Learning Object](examples/prime-api-learning-object-example.json)
- [Prime Api Learning Object Instance](examples/prime-api-learning-object-instance-example.json)
- [Prime Api Learning Object Instance List Response](examples/prime-api-learning-object-instance-list-response-example.json)
- [Prime Api Learning Object List Response](examples/prime-api-learning-object-list-response-example.json)
- [Prime Api Learning Object Response](examples/prime-api-learning-object-response-example.json)
- [Prime Api Localized Metadata](examples/prime-api-localized-metadata-example.json)
- [Prime Api Notification](examples/prime-api-notification-example.json)
- [Prime Api Notification List Response](examples/prime-api-notification-list-response-example.json)
- [Prime Api Pagination Links](examples/prime-api-pagination-links-example.json)
- [Prime Api Relationship](examples/prime-api-relationship-example.json)
- [Prime Api Resource Identifier](examples/prime-api-resource-identifier-example.json)
- [Prime Api Skill](examples/prime-api-skill-example.json)
- [Prime Api Skill List Response](examples/prime-api-skill-list-response-example.json)
- [Prime Api Skill Response](examples/prime-api-skill-response-example.json)
- [Prime Api User Badge List Response](examples/prime-api-user-badge-list-response-example.json)
- [Prime Api User](examples/prime-api-user-example.json)
- [Prime Api User Group](examples/prime-api-user-group-example.json)
- [Prime Api User Group List Response](examples/prime-api-user-group-list-response-example.json)
- [Prime Api User Group Response](examples/prime-api-user-group-response-example.json)
- [Prime Api User List Response](examples/prime-api-user-list-response-example.json)
- [Prime Api User Response](examples/prime-api-user-response-example.json)
- [Prime Api User Skill List Response](examples/prime-api-user-skill-list-response-example.json)
- [Prime Api User Update Request](examples/prime-api-user-update-request-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Captivate Prime Api](capabilities/shared/captivate-prime-api.yaml)

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Learning Management](capabilities/learning-management.yaml) | Adobe Captivate Prime API | 12 | L&D Administrator |

## Vocabulary

- [Adobe Captivate Vocabulary](vocabulary/adobe-captivate-vocabulary.yaml) — Unified taxonomy mapping 13 resources, 6 actions, 1 workflow, and 2 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Adobe Captivate Spectral Rules](rules/adobe-captivate-spectral-rules.yml) — 30 rules across 13 categories enforcing Adobe Captivate API conventions

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
