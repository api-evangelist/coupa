# Coupa (coupa)

Coupa is a leading Business Spend Management (BSM) platform that provides cloud-based solutions for procurement, invoicing, expenses, payments, sourcing, contracts, and supply chain design and planning.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/coupa/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party
- **x-type:** company

## Tags

- BSM, Business Spend Management, Cloud Platform, Enterprise, Financial Management, Invoicing, Procurement, Supply Chain

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-28

## APIs

### Coupa Core API

The primary RESTful API for accessing and managing core Coupa Business Spend Management resources including suppliers, purchase orders, invoices, requisitions, contracts, and reference data. Supports both JSON and XML formats with OAuth 2.0 or API key authentication.

**Human URL:** https://compass.coupa.com/en-us/products/core-platform
**Base URL:** `https://instance.coupahost.com/api`

### Coupa Integration API

API designed for enterprise integrations with ERP systems and other third-party applications, including webhooks and integration best practices.

### Coupa Supplier API

API for supplier-specific operations including supplier information management, catalogs, cXML, punchout, and supplier collaboration.

### Coupa Analytics API

API for accessing Coupa's analytics and reporting data for business intelligence and custom reporting needs.

### Coupa CCW API

The Coupa Contingent Workforce REST API for managing candidates, workers, and requisitions in contingent workforce operations.

### Coupa CSO API

The Coupa Sourcing Optimization API for importing and exporting fact sheet data for sourcing optimization workflows.

### Coupa Treasury API

REST API for retrieving and updating Coupa Treasury Management data such as cash flows and account balances.

### Coupa Open Buy API

A standard, secure interface for searching and purchasing items in real time across Coupa-enabled suppliers.

### Coupa Payments API

API for managing Coupa Pay invoice payments and expense payments, including retrieval, export tracking, and status management.

### Coupa Procurement API

RESTful endpoints for managing the full procure-to-order lifecycle including requisitions, purchase orders, contracts, and sourcing quote requests.

### Coupa Invoicing API

RESTful endpoints for creating, updating, and querying invoices, including invoice lines, charge allocations, and invoicing platform integration.

### Coupa Expenses API

RESTful endpoints for managing expense reports, expense lines, expense categories, and per diem calculations.

### Coupa Inventory and Receipts API

RESTful endpoints for receiving transactions, inventory adjustments and consumptions, pick lists, fulfillment reservations, warehouse operations, and advance ship notices.

## Repository Artifacts

- `apis.yml` - APIs.json index
- `openapi/coupa-core-api-openapi.yml` - OpenAPI specification for the Core API
- `json-schema/` - JSON Schema definitions for purchase orders and invoices
- `json-ld/coupa-context.jsonld` - JSON-LD context mapping Coupa resources to schema.org
- `vocabulary/coupa-vocabulary.yml` - Controlled vocabulary of Coupa resources and fields
- `rules/coupa-core-api-rules.yml` - Spectral linting rules for Coupa API design
- `capabilities/coupa-procure-to-pay-capabilities.yml` - Workflow capabilities mapping

## Common Properties

- [Developer Portal](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation)
- [Authentication](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/coupa-core-api/authentication)
- [Rate Limits](https://compass.coupa.com/en-us/products/product-documentation/integration-technical-documentation/api-rate-limits)
- [Status](https://trust.coupa.com/)
- [Support](https://compass.coupa.com/en-us/support)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
