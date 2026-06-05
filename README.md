# Coupa (coupa)

Coupa is a leading Business Spend Management (BSM) platform that provides cloud-based solutions for procurement, invoicing, expenses, payments, sourcing, contracts, and supply chain design & planning.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/coupa/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/coupa/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- BSM
- Business Spend Management
- Cloud Platform
- Enterprise
- Financial Management
- Invoicing
- Procurement
- Supply Chain

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-19

## APIs

### Coupa Core API

The primary RESTful API for accessing and managing core Coupa resources including suppliers, purchase orders, invoices, and requisitions.

- **Human URL:** [https://compass.coupa.com/en-us/products/core-platform](https://compass.coupa.com/en-us/products/core-platform)
- **Base URL:** `https://instance.coupahost.com/api`

#### Tags

- Invoices
- Procurement
- Purchase Orders
- Requisitions
- REST

#### Properties

- [Documentation](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/coupa-core-api)
- [OpenAPI](https://compass.coupa.com/en-us/api_docs) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Authentication](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/coupa-core-api/authentication)
- [Getting Started](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/the-coupa-core-api/get-started-with-the-api)
- [Errors](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/the-coupa-core-api/get-started-with-the-api/exception-handling-and-error-codes)
- [A P I Return Formats](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/the-coupa-core-api/get-started-with-the-api/api-return-formats)
- [X M Lvs J S O N](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/the-coupa-core-api/get-started-with-the-api/differences-between-xml-and-json-in-coupa)
- [Sample Requests](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/the-coupa-core-api/get-started-with-the-api/sample-requestsresponses-xml-vs-json)
- [Special Actions](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/the-coupa-core-api/get-started-with-the-api/special-actions-and-api-notes)
- [Open A P I Spec](openapi/coupa-core-api-openapi.yml)
- [JSON Schema](json-schema/coupa-purchase-order-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/coupa-invoice-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/coupa-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Vocabulary](vocabulary/coupa-vocabulary.yml)
- [Rules](rules/coupa-core-api-rules.yml)
- [Capabilities](capabilities/coupa-procure-to-pay-capabilities.yml)
- [Postman Collection](collections/coupa-core-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/coupa-core-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Coupa Integration API

API designed for enterprise integrations with ERP systems and other third-party applications.

- **Human URL:** [https://compass.coupa.com/en-us/products/core-platform/integration](https://compass.coupa.com/en-us/products/core-platform/integration)
- **Base URL:** `https://instance.coupahost.com/api`

#### Tags

- Enterprise
- ERP
- Integration
- Webhooks

#### Properties

- [Documentation](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation)
- [Webhooks](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/webhooks)
- [Best  Practices](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/integration-best-practices)
- [Integration Guide](https://compass.coupa.com/en-us/products/total-spend-management-platform/integration-playbooks-and-resources/other-integration-playbooks/erp-integration-adapters/build-your-integration)
- [R E S T A P I Integration](https://compass.coupa.com/en-us/products/total-spend-management-platform/integration-playbooks-and-resources/other-integration-playbooks/erp-integration-adapters/build-your-integration/integration-methods/coupa-rest-api-integration)
- [Postman Collection](collections/coupa-core-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/coupa-core-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Coupa Supplier API

API for supplier-specific operations including supplier information management, catalogs, and supplier collaboration.

- **Human URL:** [https://compass.coupa.com/en-us/products/supplier-portal](https://compass.coupa.com/en-us/products/supplier-portal)
- **Base URL:** `https://instance.coupahost.com/api/suppliers`

#### Tags

- Catalogs
- Suppliers
- Vendor Management

#### Properties

- [Documentation](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/supplier-api)
- [Getting Started](https://compass.coupa.com/en-us/products/supplier-portal/getting-started)
- [Punchout Documentation](https://compass.coupa.com/en-us/products/product-documentation/supplier-resources/for-suppliers/integration-resources/purchase-orders-and-punchouts)
- [c X M L Documentation](https://compass.coupa.com/en-us/products/product-documentation/suppliers/supplier-integration-resources/cxml-supplier-enablement)
- [Suppliers Reference A P I](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/the-coupa-core-api/resources/reference-data-resources/suppliers-api-(suppliers))
- [Postman Collection](collections/coupa-core-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/coupa-core-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Coupa Analytics API

API for accessing Coupa's analytics and reporting data for business intelligence and custom reporting needs.

- **Human URL:** [https://compass.coupa.com/en-us/products/analytics](https://compass.coupa.com/en-us/products/analytics)
- **Base URL:** `https://instance.coupahost.com/api/analytics`

#### Tags

- Analytics
- Business Intelligence
- Data Export
- Reporting

#### Properties

- [Documentation](https://compass.coupa.com/en-us/products/product-documentation/analytics-reporting)
- [Data  Dictionary](https://compass.coupa.com/en-us/products/product-documentation/analytics-reporting/data-dictionary)
- [Postman Collection](collections/coupa-core-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/coupa-core-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Coupa CCW API

The Coupa Contingent Workforce (CCW) REST API enables customers and partners to build applications and integrate with CCW for managing contingent workforce operations including candidate lookup, worker management, and requisition handling.

- **Human URL:** [https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/the-ccw-api](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/the-ccw-api)
- **Base URL:** `https://instance.coupahost.com/api`

#### Tags

- Candidates
- Contingent Workforce
- REST
- Staffing
- Workers

#### Properties

- [Documentation](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/the-ccw-api)
- [Overview](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/the-ccw-api/ccw-api-overview)
- [A P I Explorer](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/the-ccw-api/api-explorer)
- [Authentication](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/the-ccw-api/managing-your-api-consumer-apps-and-credentials)
- [Postman Collection](collections/coupa-core-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/coupa-core-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Coupa CSO API

The Coupa Sourcing Optimization (CSO) API is a RESTful web service for importing and exporting fact sheet data, enabling integration between CSO and third-party systems for sourcing optimization workflows including markets, companies, users, and events.

- **Human URL:** [https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/the-cso-api](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/the-cso-api)
- **Base URL:** `https://instance.cso.coupahost.com/api`

#### Tags

- Fact Sheets
- Markets
- Optimization
- REST
- Sourcing

#### Properties

- [Documentation](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/the-cso-api)
- [Getting Started](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/the-cso-api/get-started-with-cso-openapi)
- [User A P I](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/the-cso-api/user-api)
- [Company A P I](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/the-cso-api/company-api)
- [Market A P I](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/the-cso-api/market-api)
- [Events A P I](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/the-cso-api/events-api)
- [Postman Collection](collections/coupa-core-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/coupa-core-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Coupa Treasury API

REST API for retrieving and updating Coupa Treasury Management data such as cash flows and account balances. Treasury APIs follow the Coupa Core API structure but support JSON only.

- **Human URL:** [https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/treasury-integrations/treasury-apis](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/treasury-integrations/treasury-apis)
- **Base URL:** `https://instance.ctm.coupahost.com/v1`

#### Tags

- Account Balances
- Cash Management
- Payments
- REST
- Treasury

#### Properties

- [Documentation](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/treasury-integrations/treasury-apis)
- [A P I Documentation](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/treasury-integrations/treasury-apis/view-treasury-api-documentation)
- [Authentication](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/the-coupa-core-api/oauth-2.0-and-oidc)
- [Postman Collection](collections/coupa-core-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/coupa-core-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Coupa Open Buy API

The Open Buy API provides a faster, standard, and secure interface for searching and purchasing items in real-time. It follows common eCommerce API patterns and supports authentication, search, detail, and checkout operations for all suppliers.

- **Human URL:** [https://compass.coupa.com/en-us/products/product-documentation/supplier-resources/for-suppliers/integration-resources/open-buy-api-reference](https://compass.coupa.com/en-us/products/product-documentation/supplier-resources/for-suppliers/integration-resources/open-buy-api-reference)
- **Base URL:** `https://instance.coupahost.com`

#### Tags

- Catalog
- eCommerce
- Open Buy
- REST
- Search
- Suppliers

#### Properties

- [Documentation](https://compass.coupa.com/en-us/products/product-documentation/supplier-resources/for-suppliers/integration-resources/open-buy-api-reference)
- [Supplier Integration Resources](https://compass.coupa.com/en-us/products/product-documentation/supplier-resources/for-suppliers/integration-resources)
- [Support](mailto:openbuy-support@coupa.com)
- [Postman Collection](collections/coupa-core-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/coupa-core-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Coupa Payments API

API for managing Coupa Pay invoice payments and expense payments, including retrieval, export tracking, and payment status management. Accessed through the Coupa Pay payments endpoint.

- **Human URL:** [https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/the-coupa-core-api/resources/transactional-resources/payments-api-(coupa_paypayments-)](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/the-coupa-core-api/resources/transactional-resources/payments-api-(coupa_paypayments-))
- **Base URL:** `https://instance.coupahost.com/api/coupa_pay/payments`

#### Tags

- Coupa Pay
- Expense Payments
- Invoice Payments
- Payments
- REST

#### Properties

- [Documentation](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/the-coupa-core-api/resources/transactional-resources/payments-api-(coupa_paypayments-))
- [Shared Payments A P I](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/the-coupa-core-api/resources/shared-resources/payments-api)
- [Postman Collection](collections/coupa-core-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/coupa-core-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Coupa Procurement API

The Coupa Procurement API provides RESTful endpoints for managing the full procure-to-order lifecycle including requisitions, purchase orders, contracts, and sourcing (quote requests). It enables programmatic creation, querying, and updating of procurement transactions within the Coupa platform.

- **Human URL:** [https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/the-coupa-core-api/resources/transactional-resources](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/the-coupa-core-api/resources/transactional-resources)
- **Base URL:** `https://instance.coupahost.com/api`

#### Tags

- Contracts
- Procurement
- Purchase Orders
- Requisitions
- REST
- Sourcing

#### Properties

- [Documentation](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/the-coupa-core-api/resources/transactional-resources)
- [Requisitions A P I](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/the-coupa-core-api/resources/transactional-resources/requisitions-api-(requisitions))
- [Purchase Orders A P I](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/the-coupa-core-api/resources/transactional-resources/purchase-orders-api-(purchase_orders))
- [Contracts A P I](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/the-coupa-core-api/resources/transactional-resources/contracts-api-(contracts))
- [Sourcing A P I](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/the-coupa-core-api/resources/transactional-resources/sourcing-api-(quote_requests))
- [Approvals A P I](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/the-coupa-core-api/resources/transactional-resources/approvals-api-(approvals))
- [Postman Collection](collections/coupa-core-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/coupa-core-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Coupa Invoicing API

The Coupa Invoicing API provides RESTful endpoints for creating, updating, and querying invoices associated with purchase orders. It supports the full invoice lifecycle including invoice lines, charge allocations, and integration with invoicing platform workflows.

- **Human URL:** [https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/the-coupa-core-api/resources/transactional-resources/invoices-api-(invoices)](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/the-coupa-core-api/resources/transactional-resources/invoices-api-(invoices))
- **Base URL:** `https://instance.coupahost.com/api/invoices`

#### Tags

- Accounts Payable
- Charge Allocations
- Invoices
- Invoicing
- REST

#### Properties

- [Documentation](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/the-coupa-core-api/resources/transactional-resources/invoices-api-(invoices))
- [Example Calls](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/the-coupa-core-api/resources/transactional-resources/invoices-api-(invoices)/invoices-api-example-calls)
- [Invoice Charge Allocation A P I](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/the-coupa-core-api/resources/transactional-resources/invoices-api-(invoices)/invoice-charge-allocation-api)
- [Invoicing Platform Integration](https://compass.coupa.com/en-us/products/total-spend-management-platform/integration-playbooks-and-resources/other-integration-playbooks/invoicing-platform-integration/build-your-integration/using-the-api)
- [Postman Collection](collections/coupa-core-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/coupa-core-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Coupa Expenses API

The Coupa Expenses API provides RESTful endpoints for managing expense reports, expense lines, expense categories, and related data. It supports creation, querying, and updating of expense transactions including itemized lines, per diem calculations, and tax details.

- **Human URL:** [https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/the-coupa-core-api/resources/transactional-resources/expenses-api-(expense_reports)](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/the-coupa-core-api/resources/transactional-resources/expenses-api-(expense_reports))
- **Base URL:** `https://instance.coupahost.com/api/expense_reports`

#### Tags

- Expense Lines
- Expense Reports
- Expenses
- Per Diem
- REST

#### Properties

- [Documentation](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/the-coupa-core-api/resources/transactional-resources/expenses-api-(expense_reports))
- [Expense Reports A P I](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/the-coupa-core-api/resources/transactional-resources/expenses-api-(expense_reports)/expense-reports-api)
- [Expense Lines A P I](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/the-coupa-core-api/resources/transactional-resources/expenses-api-(expense_reports)/expense-lines-api)
- [Example Calls](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/the-coupa-core-api/resources/transactional-resources/expenses-api-(expense_reports)/expense-api-example-calls)
- [Postman Collection](collections/coupa-core-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/coupa-core-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Coupa Inventory and Receipts API

The Coupa Inventory and Receipts API provides RESTful endpoints for managing receiving transactions, inventory adjustments, inventory consumptions, pick lists, fulfillment reservations, warehouse operations, and advance ship notices (ASN). It supports the full goods receipt and inventory management lifecycle.

- **Human URL:** [https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/the-coupa-core-api/resources/transactional-resources/receipts-api](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/the-coupa-core-api/resources/transactional-resources/receipts-api)
- **Base URL:** `https://instance.coupahost.com/api`

#### Tags

- Advance Ship Notices
- Fulfillment
- Inventory
- Receipts
- REST
- Warehouse

#### Properties

- [Documentation](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/the-coupa-core-api/resources/transactional-resources/receipts-api)
- [Receiving Transactions A P I](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/the-coupa-core-api/resources/transactional-resources/receipts-api/receiving-transactions-api-(receiving_transactions))
- [Inventory Adjustments A P I](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/the-coupa-core-api/resources/transactional-resources/receipts-api/inventory-adjustments-api-(inventory_adjustments))
- [Inventory Consumptions A P I](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/the-coupa-core-api/resources/transactional-resources/receipts-api/inventory-consumptions-api-(inventory_consumptions))
- [Pick Lists A P I](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/the-coupa-core-api/resources/transactional-resources/pick-listsfulfillment-reservations-api-(pick-lists))
- [Warehouse A P I](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/the-coupa-core-api/resources/transactional-resources/pick-listsfulfillment-reservations-api-(pick-lists)/warehouse-api)
- [Advance Ship Notices A P I](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/the-coupa-core-api/resources/transactional-resources/advance-ship-notices-api-(asn))
- [Inventory Balance A P I](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/the-coupa-core-api/resources/transactional-resources/pick-listsfulfillment-reservations-api-(pick-lists)/inventory-balance-api)
- [Postman Collection](collections/coupa-core-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/coupa-core-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/coupa)
- [Developer  Portal](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation)
- [Authentication](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/coupa-core-api/authentication)
- [O Auth2 Transition Guide](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/the-coupa-core-api/oauth-2.0-and-oidc/oauth-2.0-transition-guide)
- [Open I D Connect](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/the-coupa-core-api/oauth-2.0-and-oidc/openid-connect-clients)
- [Getting Started](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/the-coupa-core-api/get-started-with-the-api)
- [Rate Limits](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/api-rate-limits)
- [Errors](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/the-coupa-core-api/get-started-with-the-api/exception-handling-and-error-codes)
- [A P I Resources](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/the-coupa-core-api/resources)
- [Transactional Resources](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/the-coupa-core-api/resources/transactional-resources)
- [Reference Data Resources](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/the-coupa-core-api/resources/reference-data-resources)
- [I P Addresses](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/coupa-core-application-ip-addresses)
- [Release Notes](https://compass.coupa.com/en-us/products/release-notes)
- [Integration Knowledge Base](https://compass.coupa.com/en-us/products/total-spend-management-platform/integration-playbooks-and-resources/integration-knowledge-articles)
- [Status Page](https://trust.coupa.com/)
- [Trust](https://compass.coupa.com/en-us/trust)
- [Terms of Service](https://www.coupa.com/company/trust/agreements)
- [Privacy Policy](https://www.coupa.com/company/trust/privacy)
- [Support](https://compass.coupa.com/en-us/support)
- [Community](https://compass.coupa.com/en-us/community)
- [Blog](https://www.coupa.com/blog)
- [LinkedIn](https://www.linkedin.com/company/coupa-software)
- [Twitter](https://twitter.com/Coupa)
- [O Auth2 And O I D C](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/the-coupa-core-api/oauth-2.0-and-oidc)
- [O Auth2 Getting Started](https://compass.coupa.com/en-us/products/total-spend-management-platform/integration-playbooks-and-resources/integration-knowledge-articles/oauth-2.0-getting-started-with-coupa-api)
- [Shared Resources](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/the-coupa-core-api/resources/shared-resources)
- [A P I Return Formats](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/the-coupa-core-api/get-started-with-the-api/api-return-formats)
- [X M Lvs J S O N](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/the-coupa-core-api/get-started-with-the-api/differences-between-xml-and-json-in-coupa)
- [Sample Requests Responses](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/the-coupa-core-api/get-started-with-the-api/sample-requestsresponses-xml-vs-json)
- [Special Actions](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/the-coupa-core-api/get-started-with-the-api/special-actions-and-api-notes)
- [Flat File C S V](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/coupa-core-flat-files-(csv))
- [Flat File Import](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/coupa-core-flat-files-(csv)/flat-file-(csv)-import)
- [Flat File Export](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/coupa-core-flat-files-(csv)/flat-file-(csv)-export)
- [Integration Playbooks](https://compass.coupa.com/en-us/products/total-spend-management-platform/integration-playbooks-and-resources/other-integration-playbooks)
- [R E S T A P I Integration](https://compass.coupa.com/en-us/products/total-spend-management-platform/integration-playbooks-and-resources/other-integration-playbooks/erp-integration-adapters/build-your-integration/integration-methods/coupa-rest-api-integration)
- [Integrations](https://compass.coupa.com/integrations)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
