# SAP Commerce Cloud

SAP Commerce Cloud (formerly Hybris) provides enterprise e-commerce and omnichannel customer experience management capabilities including product content management, order management, and personalization.

**URL:** https://www.sap.com/products/crm/commerce-cloud.html

## Tags

B2B, B2C, Commerce, Customer Experience, Ecommerce, Omnichannel, Retail

## Timestamps

- **Created:** 2024
- **Modified:** 2026-05-02

## APIs

### Commerce Web Services API

RESTful OCC v2 API for commerce operations including product catalog, cart, checkout, and order management.

- **Base URL:** https://{tenant}.{region}.commercecloud.sap/occ/v2
- **Human URL:** https://help.sap.com/docs/SAP_COMMERCE_CLOUD_PUBLIC_CLOUD/9d346683b0084da2938be8a285c0c27a/
- **OpenAPI:** [openapi/sap-commerce-cloud-commerce-web-services-openapi.yml](openapi/sap-commerce-cloud-commerce-web-services-openapi.yml)

### Assisted Service Module API

API for assisted service capabilities enabling customer service representatives to assist customers.

- **Base URL:** https://{tenant}.{region}.commercecloud.sap/assistedservicewebservices
- **Human URL:** https://help.sap.com/docs/SAP_COMMERCE/9d346683b0084da2938be8a285c0c27a/8b571515866910148fc18b9e59d3e084.html
- **OpenAPI:** [openapi/sap-commerce-cloud-assisted-service-openapi.yml](openapi/sap-commerce-cloud-assisted-service-openapi.yml)

### Integration API

OData-based integration API for data integration and synchronization with external systems.

- **Base URL:** https://{tenant}.{region}.commercecloud.sap/odata2webservices
- **OpenAPI:** [openapi/sap-commerce-cloud-integration-openapi.yml](openapi/sap-commerce-cloud-integration-openapi.yml)

### Admin API

Administrative API for system configuration, maintenance, and monitoring.

- **OpenAPI:** [openapi/sap-commerce-cloud-admin-openapi.yml](openapi/sap-commerce-cloud-admin-openapi.yml)

### Product Content Management API

API for managing product content including images, descriptions, and attributes.

- **OpenAPI:** [openapi/sap-commerce-cloud-product-content-management-openapi.yml](openapi/sap-commerce-cloud-product-content-management-openapi.yml)

## Artifacts

### OpenAPI Specifications

| API | File |
|-----|------|
| Commerce Web Services API | [openapi/sap-commerce-cloud-commerce-web-services-openapi.yml](openapi/sap-commerce-cloud-commerce-web-services-openapi.yml) |
| Assisted Service Module API | [openapi/sap-commerce-cloud-assisted-service-openapi.yml](openapi/sap-commerce-cloud-assisted-service-openapi.yml) |
| Integration API | [openapi/sap-commerce-cloud-integration-openapi.yml](openapi/sap-commerce-cloud-integration-openapi.yml) |
| Admin API | [openapi/sap-commerce-cloud-admin-openapi.yml](openapi/sap-commerce-cloud-admin-openapi.yml) |
| Product Content Management API | [openapi/sap-commerce-cloud-product-content-management-openapi.yml](openapi/sap-commerce-cloud-product-content-management-openapi.yml) |

### Capabilities

Workflow-oriented Naftiko capability compositions:

| Workflow | Description |
|----------|-------------|
| [Shopping and Checkout](capabilities/shopping-and-checkout.yaml) | Customer product discovery, cart management, checkout, and order tracking |
| [Catalog and Content Management](capabilities/catalog-and-content-management.yaml) | Product catalog governance, content authoring, and assisted customer service |

**Shared per-API definitions (`capabilities/shared/`):**

- [commerce-web-services.yaml](capabilities/shared/commerce-web-services.yaml) — Commerce Web Services OCC v2 API
- [assisted-service.yaml](capabilities/shared/assisted-service.yaml) — Assisted Service Module API
- [product-content-management.yaml](capabilities/shared/product-content-management.yaml) — Product Content Management API

### Rules

- [rules/sap-commerce-cloud-rules.yml](rules/sap-commerce-cloud-rules.yml) — Spectral ruleset for SAP Commerce Cloud API conventions

### JSON Schema

- [json-schema/sap-commerce-cloud-product-schema.json](json-schema/sap-commerce-cloud-product-schema.json)
- [json-schema/sap-commerce-cloud-order-schema.json](json-schema/sap-commerce-cloud-order-schema.json)
- [json-schema/sap-commerce-cloud-cart-schema.json](json-schema/sap-commerce-cloud-cart-schema.json)
- [json-schema/sap-commerce-cloud-customer-schema.json](json-schema/sap-commerce-cloud-customer-schema.json)

### JSON Structure

- [json-structure/sap-commerce-cloud-product-structure.json](json-structure/sap-commerce-cloud-product-structure.json)
- [json-structure/sap-commerce-cloud-order-structure.json](json-structure/sap-commerce-cloud-order-structure.json)

### JSON-LD

- [json-ld/sap-commerce-cloud-context.jsonld](json-ld/sap-commerce-cloud-context.jsonld)

### Examples

- [examples/sap-commerce-cloud-search-products-example.json](examples/sap-commerce-cloud-search-products-example.json)
- [examples/sap-commerce-cloud-get-order-example.json](examples/sap-commerce-cloud-get-order-example.json)

### Vocabulary

- [vocabulary/sap-commerce-cloud-vocabulary.yml](vocabulary/sap-commerce-cloud-vocabulary.yml)

## Common Resources

- **Portal:** https://api.sap.com/
- **Getting Started:** https://help.sap.com/docs/SAP_COMMERCE_CLOUD_PUBLIC_CLOUD/0996ba68e5794b8ab51db8d25d4c9f8c/
- **Authentication:** https://help.sap.com/docs/SAP_COMMERCE/d0224eca81e249cb821f2cdf45a82ace/627c92dbdb7648449c840c07dd9cac7b.html
- **Support:** https://support.sap.com/
- **Community:** https://community.sap.com/topics/commerce-cloud
- **Terms of Service:** https://www.sap.com/about/legal/terms-of-use.html
- **Privacy Policy:** https://www.sap.com/about/legal/privacy.html
- **Status:** https://www.sap.com/about/trust-center/cloud-service-status.html

## Maintainers

- **Kin Lane** — kin@apievangelist.com
