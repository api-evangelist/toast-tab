# Toast (toast-tab)

Toast (NYSE: TOST) is a cloud-based restaurant technology platform that unifies point-of-sale (POS), payments, online ordering, delivery, digital marketing, loyalty, gift cards, kitchen display, inventory, and team management for restaurants of every size. The Toast platform exposes a substantial REST API surface at `https://ws-api.toasttab.com/`, authenticated via OAuth 2.0 client credentials, and is used by restaurants, internal IT teams, and the Toast Partner Integrations program.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/toast-tab/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Specification Version:** 0.19

## Tags

- Restaurants
- Point Of Sale
- Payments
- Online Ordering
- Delivery
- Loyalty
- Gift Cards
- Menus
- Orders
- Kitchen
- Labor
- Scheduling
- Inventory
- Hospitality
- Partner Integrations

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### Toast Authentication API

OAuth 2.0 client-credentials authentication for Toast APIs. Exchanges a clientId and clientSecret for a bearer access token.

- **Base URL:** `https://ws-api.toasttab.com/authentication/v1`
- **Human URL:** [https://doc.toasttab.com/openapi/authentication/overview/](https://doc.toasttab.com/openapi/authentication/overview/)

### Toast Restaurants API

Restaurant-level information including locations, addresses, hours, schedules, and reference identifiers that anchor every other Toast API call.

- **Base URL:** `https://ws-api.toasttab.com/restaurants/v1`
- **Human URL:** [https://doc.toasttab.com/openapi/restaurants/overview/](https://doc.toasttab.com/openapi/restaurants/overview/)

### Toast Configuration API

Read-access to a restaurant's configuration entities — menus, modifier groups, employees, jobs, dining options, service areas, revenue centers, sales categories, discounts, service charges, and table topology.

- **Base URL:** `https://ws-api.toasttab.com/config/v2`
- **Human URL:** [https://doc.toasttab.com/openapi/configuration/overview/](https://doc.toasttab.com/openapi/configuration/overview/)

### Toast Menus API (V2)

Returns published menu data for a restaurant — menus, menu groups, items, modifier groups, options, prices, and tax info — in the legacy V2 shape used by ordering and POS integrations.

- **Base URL:** `https://ws-api.toasttab.com/menus/v2`
- **Human URL:** [https://doc.toasttab.com/openapi/menus/overview/](https://doc.toasttab.com/openapi/menus/overview/)

### Toast Menus API (V3)

Next-generation read API for Toast menus, exposing the same model as V2 in a refreshed shape aligned with Toast's newer platform services.

- **Base URL:** `https://ws-api.toasttab.com/menus/v3`
- **Human URL:** [https://doc.toasttab.com/openapi/menusv3/overview/](https://doc.toasttab.com/openapi/menusv3/overview/)

### Toast Orders API

Create, retrieve, modify, and void orders, checks, and selections; attach payments and refunds; manage dining options and service charges. The workhorse of Toast integrations.

- **Base URL:** `https://ws-api.toasttab.com/orders/v2`
- **Human URL:** [https://doc.toasttab.com/openapi/orders/overview/](https://doc.toasttab.com/openapi/orders/overview/)

### Toast Order Management Configuration API

Read configuration that governs how orders flow through Toast — throttling, prep-time rules, surge controls, and order-management settings.

- **Base URL:** `https://ws-api.toasttab.com/ordermgmt-config/v1`
- **Human URL:** [https://doc.toasttab.com/openapi/ordermgmt.configuration/overview/](https://doc.toasttab.com/openapi/ordermgmt.configuration/overview/)

### Toast Restaurant Availability API

Whether a restaurant is currently accepting online orders, its expected prep times, and per-channel availability.

- **Base URL:** `https://ws-api.toasttab.com/restaurants/v1/availability`
- **Human URL:** [https://doc.toasttab.com/openapi/rx.availability.service/overview/](https://doc.toasttab.com/openapi/rx.availability.service/overview/)

### Toast Credit Cards API

Read tokenized credit-card information attached to orders for receipts, returns, and reconciliation.

- **Base URL:** `https://ws-api.toasttab.com/creditcards/v1`
- **Human URL:** [https://doc.toasttab.com/openapi/creditcards/overview/](https://doc.toasttab.com/openapi/creditcards/overview/)

### Toast Cash Management API

Records and retrieves cash entries — paid in, paid out, deposits, drawer counts — that flow into a restaurant's cash-management ledger.

- **Base URL:** `https://ws-api.toasttab.com/cashmgmt/v1`
- **Human URL:** [https://doc.toasttab.com/openapi/cashmanagement/overview/](https://doc.toasttab.com/openapi/cashmanagement/overview/)

### Toast Labor API

Manages employees, jobs, time entries, breaks, and shifts — the integration point used by scheduling, payroll, and HR vendors.

- **Base URL:** `https://ws-api.toasttab.com/labor/v1`
- **Human URL:** [https://doc.toasttab.com/openapi/labor/overview/](https://doc.toasttab.com/openapi/labor/overview/)

### Toast Kitchen API

Surfaces kitchen tickets, prep stations, ticket items, and ticket events to support kitchen-display integrations.

- **Base URL:** `https://ws-api.toasttab.com/kitchen/v1`
- **Human URL:** [https://doc.toasttab.com/openapi/kitchen/overview/](https://doc.toasttab.com/openapi/kitchen/overview/)

### Toast Packaging Configuration API

Read configuration about packaging — containers, lids, utensils, and packaging instructions — for off-premises and delivery workflows.

- **Base URL:** `https://ws-api.toasttab.com/packaging/v1`
- **Human URL:** [https://doc.toasttab.com/openapi/packaging/overview/](https://doc.toasttab.com/openapi/packaging/overview/)

### Toast Stock API

Read and update menu-item stock levels — what is in stock, sold out, or limited — so online-ordering and inventory tools stay in sync with the sellable catalog.

- **Base URL:** `https://ws-api.toasttab.com/stock/v1`
- **Human URL:** [https://doc.toasttab.com/openapi/stock/overview/](https://doc.toasttab.com/openapi/stock/overview/)

### Toast Analytics API

Analytics and reporting endpoints for Restaurant Management Suites Pro customers — sales, labor, productivity, and operational performance data.

- **Base URL:** `https://ws-api.toasttab.com/analytics/v1`
- **Human URL:** [https://doc.toasttab.com/openapi/analytics/overview/](https://doc.toasttab.com/openapi/analytics/overview/)

### Toast Partners API

Enables Toast Partner Integration clients to enumerate the restaurants that have authorized them — "accessible" and "connected" restaurants.

- **Base URL:** `https://ws-api.toasttab.com/partners/v1`
- **Human URL:** [https://doc.toasttab.com/openapi/partners/overview/](https://doc.toasttab.com/openapi/partners/overview/)

### Toast Gift Cards Integration

Specification for integrating third-party gift-card programs with Toast — balance lookup, authorization, redemption, and reload callbacks.

- **Human URL:** [https://doc.toasttab.com/openapi/giftcards/overview/](https://doc.toasttab.com/openapi/giftcards/overview/)

### Toast Loyalty Integration

Specification for integrating third-party loyalty programs with Toast — discovery, lookup, accrual, and redemption callbacks.

- **Human URL:** [https://doc.toasttab.com/openapi/loyalty/overview/](https://doc.toasttab.com/openapi/loyalty/overview/)

### Toast Tender Integration

Specification for integrating alternative tender types into Toast — validate, authorize, and reconcile non-card forms of payment at checkout.

- **Human URL:** [https://doc.toasttab.com/openapi/tender/overview/](https://doc.toasttab.com/openapi/tender/overview/)

## Common Properties

- [Website](https://pos.toasttab.com/)
- [Developer Portal](https://dev.toasttab.com/)
- [Documentation](https://doc.toasttab.com/)
- [API Reference](https://doc.toasttab.com/openapi/)
- [Developer Guide](https://doc.toasttab.com/doc/devguide/index.html)
- [How-to Guides](https://doc.toasttab.com/doc/cookbook/index.html)
- [Platform Guide](https://doc.toasttab.com/doc/platformguide/index.html)
- [Release Notes](https://doc.toasttab.com/doc/relnotes/index.html)
- [Authentication](https://doc.toasttab.com/doc/devguide/authentication.html)
- [Webhooks](https://doc.toasttab.com/doc/devguide/webhooks.html)
- [Partner Program](https://pos.toasttab.com/integrations)
- [GitHub Organization](https://github.com/toasttab)
- [LinkedIn](https://www.linkedin.com/company/toast-inc)
- [Investors](https://investors.toasttab.com/)
- [Status](https://status.toasttab.com/)
- [Support](https://central.toasttab.com/)
- [Pricing](https://pos.toasttab.com/pricing)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
