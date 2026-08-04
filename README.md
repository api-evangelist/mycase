# MyCase (mycase)

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

MyCase is a cloud-based legal practice and case management platform used by more than 18,000 law firms for matter management, contacts and companies, calendaring, events, tasks, documents, time tracking, billing and invoicing, payments via LawPay, lead intake, eSignature, and client communications through a secure portal. MyCase was acquired by AffiniPay (now 8am, LLC — which also owns LawPay, CasePeer, and Docketwise) in 2022. In late 2023 MyCase released a public Open API available exclusively on its Advanced tier, with documentation hosted at mycaseapi.stoplight.io. The Open API exposes the firm, cases, contacts, companies, case stages, events, tasks, documents, client relationships, and webhook subscriptions, and is positioned as the integration surface for third-party software vendors building on MyCase.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/mycase/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/mycase/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** 3rd-Party

## Tags

- Billing
- Calendaring
- Case Management
- Client Portal
- Document Management
- Invoicing
- Law Firms
- Legal
- Legal Practice Management
- LegalTech
- Matter Management
- OAuth 2.0
- Payments
- Practice Management
- Time Tracking
- Webhooks

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### MyCase Open API

The MyCase Open API is a public REST/JSON API that lets MyCase Advanced-tier subscribers and their integration partners share data with the MyCase platform, programmatically trigger tasks or events, and build connected workflows. The API surface covers the authorized firm, cases, case stages, contacts, companies, client relationships, calendar events, tasks, documents and document folders, and time zones. Documentation is hosted on Stoplight at mycaseapi.stoplight.io. The API is available only to customers on the Advanced subscription tier; access must be requested through MyCase support and certified consultants are listed for implementation assistance.

- **Human URL:** [https://mycaseapi.stoplight.io/](https://mycaseapi.stoplight.io/)

#### Tags

- Cases
- Case Stages
- Companies
- Contacts
- Documents
- Events
- Firm
- Legal
- Practice Management
- REST
- Tasks

#### Properties

- [Documentation](https://mycaseapi.stoplight.io/docs/mycase-api-documentation/k5xpc4jyhkom7-getting-started)
- [Reference](https://mycaseapi.stoplight.io/)
- [Support  Article](https://supportcenter.mycase.com/en/articles/9370198-open-api)
- [OpenAPI](openapi/mycase-open-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/mycase-open-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mycase-open-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### MyCase Webhooks

MyCase Webhooks deliver event notifications when records change in the MyCase platform (for example case, event, task, and document lifecycle events). Webhook subscriptions are documented alongside the Open API on Stoplight and are intended for integration partners that need near real-time triggers rather than polling the REST endpoints.

- **Human URL:** [https://mycaseapi.stoplight.io/docs/mycase-api-documentation/fdtu5r8u47pku-webhooks](https://mycaseapi.stoplight.io/docs/mycase-api-documentation/fdtu5r8u47pku-webhooks)

#### Tags

- Events
- Legal
- Notifications
- Webhooks

#### Properties

- [Documentation](https://mycaseapi.stoplight.io/docs/mycase-api-documentation/fdtu5r8u47pku-webhooks)
- [Postman Collection](collections/mycase-open-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mycase-open-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.mycase.com/)
- [Parent  Company](https://www.8am.com/)
- [Affini Pay](https://www.affinipay.com/)
- [Pricing](https://www.mycase.com/pricing/)
- [Sign Up](https://www.mycase.com/lp/free-trial/)
- [Login](https://auth.mycase.com/login)
- [Portal](https://mycaseapi.stoplight.io/)
- [Documentation](https://mycaseapi.stoplight.io/docs/mycase-api-documentation/k5xpc4jyhkom7-getting-started)
- [Reference](https://mycaseapi.stoplight.io/)
- [Support](https://supportcenter.mycase.com/)
- [Support  Article](https://supportcenter.mycase.com/en/articles/9370198-open-api)
- [Certified  Consultants](https://www.mycase.com/consultants/)
- [Blog](https://www.mycase.com/blog/)
- [News](https://www.mycase.com/news/)
- [Webinars](https://www.mycase.com/webinars/)
- [Case Studies](https://www.mycase.com/case-studies/)
- [Customers](https://www.mycase.com/customers/)
- [Integrations](https://www.mycase.com/integrations/)
- [Mobile](https://www.mycase.com/features/mobile-app/)
- [Privacy Policy](https://www.mycase.com/privacy-policy/)
- [Terms of Service](https://www.mycase.com/terms-of-service/)
- [Security](https://www.mycase.com/security/)
- [Careers](https://www.8am.com/careers/)
- [Git Hub](https://github.com/mycase)
- [LinkedIn](https://www.linkedin.com/company/mycase-inc-)
- [Twitter](https://twitter.com/mycaseinc)
- [Facebook](https://www.facebook.com/mycaseinc)
- [YouTube](https://www.youtube.com/user/MyCaseInc)
- [JSON-LD](json-ld/mycase-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Spectral Rules](rules/mycase-rules.yml) — [Spectral](https://docs.stoplight.io/docs/spectral)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
