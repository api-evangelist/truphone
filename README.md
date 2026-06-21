# Truphone (1GLOBAL) (truphone)

Truphone is a global eSIM, IoT, and enterprise connectivity provider now operating as 1GLOBAL after its 2022 acquisition. It runs its own global mobile network supplemented by roaming across 600+ partner networks in 190+ countries, and exposes REST APIs for SIM/eSIM lifecycle management, data usage and connectivity, rate plans, and IoT device management across its 1GLOBAL IoT Portal, 1GLOBAL Connect, and the 1GLOBAL platform API.

> Rebrand note: Truphone was acquired in 2022 and rebranded to **1GLOBAL**. Product and documentation now live on 1global.com, while several API hosts and GitHub repositories still use the legacy `truphone.com` / `Truphone` namespaces (e.g. `iot.truphone.com`, `services.truphone.com`, `github.com/Truphone`).

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/truphone/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/truphone/refs/heads/main/apis.yml)

## Tags

- eSIM
- IoT
- Connectivity
- SIM Management
- Telecom
- Mobile Network

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Truphone (1GLOBAL) SIMs / eSIMs API

List, retrieve, update, and change the status of SIM cards and eSIMs (TEST, PROVISIONED, PRE-ACTIVE, ACTIVE, SUSPENDED, RETIRED) and activate or suspend data services across the 1GLOBAL IoT Portal. eSIM ordering and activation are also available through 1GLOBAL Connect via POST /connect-api/v2/orders.

- **Human URL:** [https://docs.things.1global.com/apireference/](https://docs.things.1global.com/apireference/)
- **Base URL:** `https://iot.truphone.com/api`

#### Tags

- SIM
- eSIM
- Lifecycle
- Provisioning

#### Properties

- [Documentation](https://docs.things.1global.com/apireference/)
- [API Reference](https://docs.things.1global.com/apireference/)
- [OpenAPI](openapi/truphone-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/truphone.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/truphone.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Truphone (1GLOBAL) Connectivity / Usage API

Inspect ongoing data sessions, retrieve call detail records (CDRs) for usage tracking, check SIM service status with data/time limits, and review location updates for connected SIMs.

- **Human URL:** [https://docs.things.1global.com/apireference/](https://docs.things.1global.com/apireference/)
- **Base URL:** `https://iot.truphone.com/api`

#### Tags

- Connectivity
- Usage
- Data Sessions
- CDR

#### Properties

- [Documentation](https://docs.things.1global.com/apireference/)
- [API Reference](https://docs.things.1global.com/apireference/)
- [OpenAPI](openapi/truphone-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/truphone.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/truphone.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Truphone (1GLOBAL) Plans API

List available rate plans, retrieve plan detail, and read or modify a SIM's subscription and current service pack with immediate or next-billing-cycle application.

- **Human URL:** [https://docs.things.1global.com/apireference/](https://docs.things.1global.com/apireference/)
- **Base URL:** `https://iot.truphone.com/api`

#### Tags

- Plans
- Rate Plans
- Subscriptions

#### Properties

- [Documentation](https://docs.things.1global.com/apireference/)
- [API Reference](https://docs.things.1global.com/apireference/)
- [OpenAPI](openapi/truphone-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Plans](plans/truphone-plans-pricing.yml)
- [Postman Collection](collections/truphone.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/truphone.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Truphone (1GLOBAL) Device Management API

List and configure connected devices, manage event-based and usage-based automation rules, and organize fleets with tags and custom attributes across the 1GLOBAL IoT Portal.

- **Human URL:** [https://docs.things.1global.com/apireference/](https://docs.things.1global.com/apireference/)
- **Base URL:** `https://iot.truphone.com/api`

#### Tags

- Devices
- Device Management
- Rules
- Automation

#### Properties

- [Documentation](https://docs.things.1global.com/apireference/)
- [API Reference](https://docs.things.1global.com/apireference/)
- [OpenAPI](openapi/truphone-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/truphone.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/truphone.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/Truphone)
- [LinkedIn](https://www.linkedin.com/company/1global)
- [Website](https://www.1global.com)
- [Documentation](https://docs.1global.com)
- [Plans](plans/truphone-plans-pricing.yml)
- [Rate Limits](rate-limits/truphone-rate-limits.yml)
- [Fin Ops](finops/truphone-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
