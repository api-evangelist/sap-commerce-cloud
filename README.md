# SAP Commerce Cloud (sap-commerce-cloud)

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

SAP Commerce Cloud (formerly Hybris) provides enterprise e-commerce and omnichannel customer experience management capabilities including product content management, order management, personalization, and assisted service for B2B and B2C commerce scenarios.

**APIs.json:** [https://www.sap.com/products/crm/commerce-cloud.html](https://www.sap.com/products/crm/commerce-cloud.html)

## Tags

- B2B
- B2C
- Commerce
- Customer Experience
- Ecommerce
- Omnichannel
- Retail

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-19

## APIs

### Commerce Web Services API

RESTful API for commerce operations including product catalog, cart, checkout, and order management.

- **Human URL:** [https://help.sap.com/docs/SAP_COMMERCE_CLOUD_PUBLIC_CLOUD/9d346683b0084da2938be8a285c0c27a/](https://help.sap.com/docs/SAP_COMMERCE_CLOUD_PUBLIC_CLOUD/9d346683b0084da2938be8a285c0c27a/)
- **Base URL:** `https://{tenant}.{region}.commercecloud.sap/occ/v2`

#### Tags

- Cart
- Checkout
- Orders
- Products
- REST

#### Properties

- [Documentation](https://help.sap.com/docs/SAP_COMMERCE/d0224eca81e249cb821f2cdf45a82ace/8c19398686691014a8c0fd6c3e5d44a0.html)
- [OpenAPI](https://api.sap.com/api/commerce_web_services/overview) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Authentication](https://help.sap.com/docs/SAP_COMMERCE/d0224eca81e249cb821f2cdf45a82ace/627c92dbdb7648449c840c07dd9cac7b.html)
- [OpenAPI](openapi/sap-commerce-cloud-commerce-web-services-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sap-commerce-cloud-commerce-web-services.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-commerce-cloud-commerce-web-services.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Assisted Service Module API

API for assisted service capabilities enabling customer service representatives to help customers with their shopping experience.

- **Human URL:** [https://help.sap.com/docs/SAP_COMMERCE/9d346683b0084da2938be8a285c0c27a/8b571515866910148fc18b9e59d3e084.html](https://help.sap.com/docs/SAP_COMMERCE/9d346683b0084da2938be8a285c0c27a/8b571515866910148fc18b9e59d3e084.html)
- **Base URL:** `https://{tenant}.{region}.commercecloud.sap/assistedservicewebservices`

#### Tags

- Assisted Service
- Customer Service
- REST

#### Properties

- [Documentation](https://help.sap.com/docs/SAP_COMMERCE/9d346683b0084da2938be8a285c0c27a/8b571515866910148fc18b9e59d3e084.html)
- [OpenAPI](openapi/sap-commerce-cloud-assisted-service-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sap-commerce-cloud-assisted-service.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-commerce-cloud-assisted-service.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Integration API

OData-based integration API for data integration and synchronization with external systems.

- **Human URL:** [https://help.sap.com/docs/SAP_COMMERCE_CLOUD_PUBLIC_CLOUD/50c996852b32456c96d3161a95544cdb/](https://help.sap.com/docs/SAP_COMMERCE_CLOUD_PUBLIC_CLOUD/50c996852b32456c96d3161a95544cdb/)
- **Base URL:** `https://{tenant}.{region}.commercecloud.sap/odata2webservices`

#### Tags

- Data Sync
- Integration
- OData

#### Properties

- [Documentation](https://help.sap.com/docs/SAP_COMMERCE_CLOUD_PUBLIC_CLOUD/50c996852b32456c96d3161a95544cdb/8696c1e06fce461a862d7f0eb60cca7b.html)
- [API Reference](https://help.sap.com/docs/SAP_COMMERCE_CLOUD_PUBLIC_CLOUD/b490bb4e85bc42a7aa09d513d0bcb18e/)
- [OpenAPI](openapi/sap-commerce-cloud-integration-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sap-commerce-cloud-integration.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-commerce-cloud-integration.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Admin API

Administrative API for system configuration, maintenance, and monitoring.

- **Human URL:** [https://help.sap.com/docs/SAP_COMMERCE_CLOUD_PUBLIC_CLOUD/](https://help.sap.com/docs/SAP_COMMERCE_CLOUD_PUBLIC_CLOUD/)
- **Base URL:** `https://{tenant}.{region}.commercecloud.sap/`

#### Tags

- Admin
- Configuration
- Monitoring

#### Properties

- [Documentation](https://help.sap.com/docs/SAP_COMMERCE_CLOUD_PUBLIC_CLOUD/)
- [OpenAPI](openapi/sap-commerce-cloud-admin-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sap-commerce-cloud-admin.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-commerce-cloud-admin.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Product Content Management API

API for managing product content including images, descriptions, and attributes.

- **Human URL:** [https://help.sap.com/docs/SAP_COMMERCE/d0224eca81e249cb821f2cdf45a82ace/](https://help.sap.com/docs/SAP_COMMERCE/d0224eca81e249cb821f2cdf45a82ace/)
- **Base URL:** `https://{tenant}.{region}.commercecloud.sap/occ/v2`

#### Tags

- Catalog
- Content
- Products
- REST

#### Properties

- [Documentation](https://help.sap.com/docs/SAP_COMMERCE/d0224eca81e249cb821f2cdf45a82ace/)
- [OpenAPI](openapi/sap-commerce-cloud-product-content-management-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sap-commerce-cloud-product-content-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-commerce-cloud-product-content-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/SAP)
- [LinkedIn](https://www.linkedin.com/showcase/sap-cx-commerce-cloud)
- [Portal](https://api.sap.com/)
- [Getting Started](https://help.sap.com/docs/SAP_COMMERCE_CLOUD_PUBLIC_CLOUD/0996ba68e5794b8ab51db8d25d4c9f8c/)
- [Authentication](https://help.sap.com/docs/SAP_COMMERCE/d0224eca81e249cb821f2cdf45a82ace/627c92dbdb7648449c840c07dd9cac7b.html)
- [Support](https://support.sap.com/)
- [Community](https://community.sap.com/topics/commerce-cloud)
- [Terms of Service](https://www.sap.com/about/legal/terms-of-use.html)
- [Privacy Policy](https://www.sap.com/about/legal/privacy.html)
- [Status Page](https://www.sap.com/about/trust-center/cloud-service-status.html)
- [OpenAPI](openapi/sap-commerce-cloud-commerce-web-services-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/sap-commerce-cloud-assisted-service-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/sap-commerce-cloud-integration-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/sap-commerce-cloud-admin-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/sap-commerce-cloud-product-content-management-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON-LD](json-ld/sap-commerce-cloud-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/sap-commerce-cloud-product-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sap-commerce-cloud-order-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sap-commerce-cloud-cart-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sap-commerce-cloud-customer-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/sap-commerce-cloud-product-structure.json)
- [JSON Structure](json-structure/sap-commerce-cloud-order-structure.json)
- [Spectral Rules](rules/sap-commerce-cloud-rules.yml)
- [Vocabulary](vocabulary/sap-commerce-cloud-vocabulary.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
