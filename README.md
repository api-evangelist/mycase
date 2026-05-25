# mycase

MyCase — cloud-based legal practice and case management software (part of 8am, LLC, an AffiniPay company).

This repository is part of [API Evangelist](https://apievangelist.com/) and profiles the **MyCase Open API**, the public REST/JSON API that MyCase released in late 2023 for Advanced-tier subscribers and their integration partners.

## What is MyCase?

MyCase is used by more than 18,000 law firms for matter management, contacts and companies, calendaring, events, tasks, documents, time tracking, billing and invoicing, payments via LawPay, lead intake, eSignature, and client communications through a secure portal. MyCase was acquired by AffiniPay (now 8am, LLC — which also owns LawPay, CasePeer, and Docketwise) in 2022.

## APIs profiled

| Name | Type | Notes |
| --- | --- | --- |
| [MyCase Open API](https://mycaseapi.stoplight.io/) | REST / JSON | Advanced-tier only. Auth requested through MyCase support. |
| [MyCase Webhooks](https://mycaseapi.stoplight.io/docs/mycase-api-documentation/fdtu5r8u47pku-webhooks) | Webhooks | Event notifications for record lifecycle changes. |

## Artifacts in this repository

- [`apis.yml`](./apis.yml) — APIs.json 0.20 catalog entry
- [`openapi/mycase-open-api-openapi.yml`](./openapi/mycase-open-api-openapi.yml) — profile-only OpenAPI 3.0.3 description of the publicly documented endpoints
- [`capabilities/mycase.yaml`](./capabilities/mycase.yaml) — Naftiko capability definitions
- [`json-ld/mycase-context.jsonld`](./json-ld/mycase-context.jsonld) — JSON-LD context aligning MyCase resources with schema.org / Dublin Core
- [`rules/mycase-rules.yml`](./rules/mycase-rules.yml) — Spectral ruleset reflecting MyCase's documented naming conventions

## Scope and caveat

The MyCase Open API reference on Stoplight is partially gated behind a sign-in flow, so request/response schemas in this profile reflect only the public surface area that is visible on Stoplight's index without authentication: firm, case stages, companies, cases for a client, client relationships on a case, documents and the case documents folder, calendar events, tasks, and time zones. The base URL and exact authentication endpoint are documented inside the authenticated Stoplight reference; values in `openapi/mycase-open-api-openapi.yml` that cannot be confirmed without sign-in are marked as placeholders.

## Links

- Website: <https://www.mycase.com/>
- Parent company (8am): <https://www.8am.com/>
- API documentation: <https://mycaseapi.stoplight.io/>
- Getting Started: <https://mycaseapi.stoplight.io/docs/mycase-api-documentation/k5xpc4jyhkom7-getting-started>
- Open API support article: <https://supportcenter.mycase.com/en/articles/9370198-open-api>
- GitHub org: <https://github.com/mycase>

## Maintainer

Kin Lane — <kin@apievangelist.com>
