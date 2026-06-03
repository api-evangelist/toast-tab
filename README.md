# Toast (toast-tab)
Toast (NYSE: TOST) is a cloud-based restaurant technology platform that unifies point-of-sale (POS), payments, online ordering, delivery, digital marketing, loyalty, gift cards, kitchen display, inventory, and team management for restaurants of every size — from independent operators to enterprise chains. The Toast platform exposes a substantial REST API surface at https://ws-api.toasttab.com/, authenticated via OAuth 2.0 client credentials, and is used by restaurants, internal IT teams, and the Toast Partner Integrations program to read and write menus, orders, payments, employees, schedules, time entries, cash entries, kitchen tickets, restaurant configuration, gift cards, loyalty balances, and partner-restaurant connections. Toast offers three flavors of API access: Standard API Access (self-service for restaurant operators), Analytics API Access (Restaurant Management Suites Pro), and Partner Integrations (technology companies building productized integrations).

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/toast-tab/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Restaurants, Point Of Sale, Payments, Online Ordering, Delivery, Loyalty, Gift Cards, Menus, Orders, Kitchen, Labor, Scheduling, Inventory, Hospitality, Partner Integrations

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-06-03

## APIs

### Toast Authentication API
OAuth 2.0 client-credentials authentication for Toast APIs. Exchanges a clientId and clientSecret (with userAccessType TOAST_MACHINE_CLIENT) for a bearer access token at /authentication/v1/authentication/login. Token lifetime is returned in the response and varies by environment.

**Human URL:** [https://doc.toasttab.com/openapi/authentication/overview/](https://doc.toasttab.com/openapi/authentication/overview/)

#### Tags:

 - Authentication, OAuth, Tokens

#### Properties

- [Documentation](https://doc.toasttab.com/openapi/authentication/overview/)
- [AuthenticationGuide](https://doc.toasttab.com/doc/devguide/authentication.html)
- [OpenAPI](openapi/toast-tab-authentication-openapi.yml)
- [JSONSchema](json-schema/authentication-authentication-request-schema.json)
- [JSONSchema](json-schema/authentication-authentication-response-schema.json)
- [JSONSchema](json-schema/authentication-authentication-token-schema.json)
- [JSONStructure](json-structure/authentication-authentication-request-structure.json)
- [JSONStructure](json-structure/authentication-authentication-response-structure.json)
- [JSONStructure](json-structure/authentication-authentication-token-structure.json)
- [Example](examples/authentication-authentication-request-example.json)
- [Example](examples/authentication-authentication-response-example.json)
- [Example](examples/authentication-authentication-token-example.json)
- [JSON-LD](json-ld/toast-tab-authentication-context.jsonld)
- [NaftikoCapability](capabilities/authentication-authentication.yaml)

### Toast Restaurants API
Returns restaurant-level information including locations, addresses, hours, schedules, urls, closeout hour, and reference identifiers that anchor every other Toast API call (restaurantGuid).

**Human URL:** [https://doc.toasttab.com/openapi/restaurants/overview/](https://doc.toasttab.com/openapi/restaurants/overview/)

#### Tags:

 - Restaurants, Locations, Configuration

#### Properties

- [Documentation](https://doc.toasttab.com/openapi/restaurants/overview/)
- [OpenAPI](openapi/toast-tab-restaurants-openapi.yml)
- [JSONSchema](json-schema/restaurants-day-schedule-schema.json)
- [JSONSchema](json-schema/restaurants-delivery-payment-options-schema.json)
- [JSONSchema](json-schema/restaurants-delivery-schema.json)
- [JSONSchema](json-schema/restaurants-general-schema.json)
- [JSONSchema](json-schema/restaurants-hours-schema.json)
- [JSONSchema](json-schema/restaurants-image-schema.json)
- [JSONSchema](json-schema/restaurants-location-schema.json)
- [JSONSchema](json-schema/restaurants-online-ordering-schema.json)
- [JSONSchema](json-schema/restaurants-payment-options-schema.json)
- [JSONSchema](json-schema/restaurants-prep-times-schema.json)
- [JSONSchema](json-schema/restaurants-restaurant-info-schema.json)
- [JSONSchema](json-schema/restaurants-restaurant-schema.json)
- [JSONSchema](json-schema/restaurants-schedules-schema.json)
- [JSONSchema](json-schema/restaurants-service-schema.json)
- [JSONSchema](json-schema/restaurants-takeout-payment-options-schema.json)
- [JSONSchema](json-schema/restaurants-urls-schema.json)
- [JSONSchema](json-schema/restaurants-week-schedule-schema.json)
- [JSONStructure](json-structure/restaurants-day-schedule-structure.json)
- [JSONStructure](json-structure/restaurants-delivery-payment-options-structure.json)
- [JSONStructure](json-structure/restaurants-delivery-structure.json)
- [JSONStructure](json-structure/restaurants-general-structure.json)
- [JSONStructure](json-structure/restaurants-hours-structure.json)
- [JSONStructure](json-structure/restaurants-image-structure.json)
- [JSONStructure](json-structure/restaurants-location-structure.json)
- [JSONStructure](json-structure/restaurants-online-ordering-structure.json)
- [JSONStructure](json-structure/restaurants-payment-options-structure.json)
- [JSONStructure](json-structure/restaurants-prep-times-structure.json)
- [JSONStructure](json-structure/restaurants-restaurant-info-structure.json)
- [JSONStructure](json-structure/restaurants-restaurant-structure.json)
- [JSONStructure](json-structure/restaurants-schedules-structure.json)
- [JSONStructure](json-structure/restaurants-service-structure.json)
- [JSONStructure](json-structure/restaurants-takeout-payment-options-structure.json)
- [JSONStructure](json-structure/restaurants-urls-structure.json)
- [JSONStructure](json-structure/restaurants-week-schedule-structure.json)
- [Example](examples/restaurants-day-schedule-example.json)
- [Example](examples/restaurants-delivery-example.json)
- [Example](examples/restaurants-delivery-payment-options-example.json)
- [Example](examples/restaurants-general-example.json)
- [Example](examples/restaurants-hours-example.json)
- [Example](examples/restaurants-image-example.json)
- [Example](examples/restaurants-location-example.json)
- [Example](examples/restaurants-online-ordering-example.json)
- [Example](examples/restaurants-payment-options-example.json)
- [Example](examples/restaurants-prep-times-example.json)
- [Example](examples/restaurants-restaurant-example.json)
- [Example](examples/restaurants-restaurant-info-example.json)
- [Example](examples/restaurants-schedules-example.json)
- [Example](examples/restaurants-service-example.json)
- [Example](examples/restaurants-takeout-payment-options-example.json)
- [Example](examples/restaurants-urls-example.json)
- [Example](examples/restaurants-week-schedule-example.json)
- [JSON-LD](json-ld/toast-tab-restaurants-context.jsonld)
- [NaftikoCapability](capabilities/restaurants-general.yaml)

### Toast Configuration API
Read-access to a restaurant's configuration entities — menus, modifier groups, employees, jobs, dining options, service areas, revenue centers, sales categories, discounts, service charges, and table topology — that drive POS behavior.

**Human URL:** [https://doc.toasttab.com/openapi/configuration/overview/](https://doc.toasttab.com/openapi/configuration/overview/)

#### Tags:

 - Configuration, Employees, Discounts, Service Charges

#### Properties

- [Documentation](https://doc.toasttab.com/openapi/configuration/overview/)

### Toast Menus API (V2)
Returns published menu data for a restaurant — menus, menu groups, menu items, modifier groups, options, prices, and tax info — in the legacy V2 shape used by ordering and POS integrations.

**Human URL:** [https://doc.toasttab.com/openapi/menus/overview/](https://doc.toasttab.com/openapi/menus/overview/)

#### Tags:

 - Menus, Pricing, Modifiers

#### Properties

- [Documentation](https://doc.toasttab.com/openapi/menus/overview/)
- [OpenAPI](openapi/toast-tab-menus-openapi.yml)
- [JSONSchema](json-schema/menus-alcohol-schema.json)
- [JSONSchema](json-schema/menus-allergen-item-schema.json)
- [JSONSchema](json-schema/menus-availability-schema.json)
- [JSONSchema](json-schema/menus-catalog-product-info-schema.json)
- [JSONSchema](json-schema/menus-catalog-product-option-schema.json)
- [JSONSchema](json-schema/menus-catalog-product-option-value-schema.json)
- [JSONSchema](json-schema/menus-catalog-product-schema.json)
- [JSONSchema](json-schema/menus-catalog-product-variant-option-schema.json)
- [JSONSchema](json-schema/menus-catalog-product-variant-schema.json)
- [JSONSchema](json-schema/menus-content-advisories-schema.json)
- [JSONSchema](json-schema/menus-dimension-unit-of-measure-schema.json)
- [JSONSchema](json-schema/menus-guest-count-schema.json)
- [JSONSchema](json-schema/menus-height-schema.json)
- [JSONSchema](json-schema/menus-image-schema.json)
- [JSONSchema](json-schema/menus-images-schema.json)
- [JSONSchema](json-schema/menus-item-tag-schema.json)
- [JSONSchema](json-schema/menus-length-schema.json)
- [JSONSchema](json-schema/menus-master-id-schema.json)
- [JSONSchema](json-schema/menus-menu-group-schema.json)
- [JSONSchema](json-schema/menus-menu-item-schema.json)
- [JSONSchema](json-schema/menus-menu-schema.json)
- [JSONSchema](json-schema/menus-metadata-schema.json)
- [JSONSchema](json-schema/menus-modifier-group-schema.json)
- [JSONSchema](json-schema/menus-modifier-option-schema.json)
- [JSONSchema](json-schema/menus-modifier-option-tax-info-schema.json)
- [JSONSchema](json-schema/menus-multi-location-id-schema.json)
- [JSONSchema](json-schema/menus-portion-schema.json)
- [JSONSchema](json-schema/menus-pos-button-color-dark-schema.json)
- [JSONSchema](json-schema/menus-pos-button-color-light-schema.json)
- [JSONSchema](json-schema/menus-pos-name-schema.json)
- [JSONSchema](json-schema/menus-pre-modifier-group-schema.json)
- [JSONSchema](json-schema/menus-pre-modifier-schema.json)
- [JSONSchema](json-schema/menus-pricing-rules-schema.json)
- [JSONSchema](json-schema/menus-restaurant-schema.json)
- [JSONSchema](json-schema/menus-sales-category-schema.json)
- [JSONSchema](json-schema/menus-schedule-schema.json)
- [JSONSchema](json-schema/menus-sequence-price-schema.json)
- [JSONSchema](json-schema/menus-size-sequence-pricing-rule-schema.json)
- [JSONSchema](json-schema/menus-time-range-schema.json)
- [JSONSchema](json-schema/menus-time-specific-price-schema.json)
- [JSONSchema](json-schema/menus-visibility-schema.json)
- [JSONSchema](json-schema/menus-weight-schema.json)
- [JSONSchema](json-schema/menus-weight-unit-of-measure-schema.json)
- [JSONSchema](json-schema/menus-width-schema.json)
- [JSONStructure](json-structure/menus-alcohol-structure.json)
- [JSONStructure](json-structure/menus-allergen-item-structure.json)
- [JSONStructure](json-structure/menus-availability-structure.json)
- [JSONStructure](json-structure/menus-catalog-product-info-structure.json)
- [JSONStructure](json-structure/menus-catalog-product-option-structure.json)
- [JSONStructure](json-structure/menus-catalog-product-option-value-structure.json)
- [JSONStructure](json-structure/menus-catalog-product-structure.json)
- [JSONStructure](json-structure/menus-catalog-product-variant-option-structure.json)
- [JSONStructure](json-structure/menus-catalog-product-variant-structure.json)
- [JSONStructure](json-structure/menus-content-advisories-structure.json)
- [JSONStructure](json-structure/menus-dimension-unit-of-measure-structure.json)
- [JSONStructure](json-structure/menus-guest-count-structure.json)
- [JSONStructure](json-structure/menus-height-structure.json)
- [JSONStructure](json-structure/menus-image-structure.json)
- [JSONStructure](json-structure/menus-images-structure.json)
- [JSONStructure](json-structure/menus-item-tag-structure.json)
- [JSONStructure](json-structure/menus-length-structure.json)
- [JSONStructure](json-structure/menus-master-id-structure.json)
- [JSONStructure](json-structure/menus-menu-group-structure.json)
- [JSONStructure](json-structure/menus-menu-item-structure.json)
- [JSONStructure](json-structure/menus-menu-structure.json)
- [JSONStructure](json-structure/menus-metadata-structure.json)
- [JSONStructure](json-structure/menus-modifier-group-structure.json)
- [JSONStructure](json-structure/menus-modifier-option-structure.json)
- [JSONStructure](json-structure/menus-modifier-option-tax-info-structure.json)
- [JSONStructure](json-structure/menus-multi-location-id-structure.json)
- [JSONStructure](json-structure/menus-portion-structure.json)
- [JSONStructure](json-structure/menus-pos-button-color-dark-structure.json)
- [JSONStructure](json-structure/menus-pos-button-color-light-structure.json)
- [JSONStructure](json-structure/menus-pos-name-structure.json)
- [JSONStructure](json-structure/menus-pre-modifier-group-structure.json)
- [JSONStructure](json-structure/menus-pre-modifier-structure.json)
- [JSONStructure](json-structure/menus-pricing-rules-structure.json)
- [JSONStructure](json-structure/menus-restaurant-structure.json)
- [JSONStructure](json-structure/menus-sales-category-structure.json)
- [JSONStructure](json-structure/menus-schedule-structure.json)
- [JSONStructure](json-structure/menus-sequence-price-structure.json)
- [JSONStructure](json-structure/menus-size-sequence-pricing-rule-structure.json)
- [JSONStructure](json-structure/menus-time-range-structure.json)
- [JSONStructure](json-structure/menus-time-specific-price-structure.json)
- [JSONStructure](json-structure/menus-visibility-structure.json)
- [JSONStructure](json-structure/menus-weight-structure.json)
- [JSONStructure](json-structure/menus-weight-unit-of-measure-structure.json)
- [JSONStructure](json-structure/menus-width-structure.json)
- [Example](examples/menus-alcohol-example.json)
- [Example](examples/menus-allergen-item-example.json)
- [Example](examples/menus-availability-example.json)
- [Example](examples/menus-catalog-product-example.json)
- [Example](examples/menus-catalog-product-info-example.json)
- [Example](examples/menus-catalog-product-option-example.json)
- [Example](examples/menus-catalog-product-option-value-example.json)
- [Example](examples/menus-catalog-product-variant-example.json)
- [Example](examples/menus-catalog-product-variant-option-example.json)
- [Example](examples/menus-content-advisories-example.json)
- [Example](examples/menus-dimension-unit-of-measure-example.json)
- [Example](examples/menus-guest-count-example.json)
- [Example](examples/menus-height-example.json)
- [Example](examples/menus-image-example.json)
- [Example](examples/menus-images-example.json)
- [Example](examples/menus-item-tag-example.json)
- [Example](examples/menus-length-example.json)
- [Example](examples/menus-master-id-example.json)
- [Example](examples/menus-menu-example.json)
- [Example](examples/menus-menu-group-example.json)
- [Example](examples/menus-menu-item-example.json)
- [Example](examples/menus-metadata-example.json)
- [Example](examples/menus-modifier-group-example.json)
- [Example](examples/menus-modifier-option-example.json)
- [Example](examples/menus-modifier-option-tax-info-example.json)
- [Example](examples/menus-multi-location-id-example.json)
- [Example](examples/menus-portion-example.json)
- [Example](examples/menus-pos-button-color-dark-example.json)
- [Example](examples/menus-pos-button-color-light-example.json)
- [Example](examples/menus-pos-name-example.json)
- [Example](examples/menus-pre-modifier-example.json)
- [Example](examples/menus-pre-modifier-group-example.json)
- [Example](examples/menus-pricing-rules-example.json)
- [Example](examples/menus-restaurant-example.json)
- [Example](examples/menus-sales-category-example.json)
- [Example](examples/menus-schedule-example.json)
- [Example](examples/menus-sequence-price-example.json)
- [Example](examples/menus-size-sequence-pricing-rule-example.json)
- [Example](examples/menus-time-range-example.json)
- [Example](examples/menus-time-specific-price-example.json)
- [Example](examples/menus-visibility-example.json)
- [Example](examples/menus-weight-example.json)
- [Example](examples/menus-weight-unit-of-measure-example.json)
- [Example](examples/menus-width-example.json)
- [JSON-LD](json-ld/toast-tab-menus-context.jsonld)
- [NaftikoCapability](capabilities/menus-general.yaml)

### Toast Menus API (V3)
Next-generation read API for Toast menus, exposing the same menu / menu group / item / modifier / option model as V2 in a refreshed shape aligned with Toast's newer platform services.

**Human URL:** [https://doc.toasttab.com/openapi/menusv3/overview/](https://doc.toasttab.com/openapi/menusv3/overview/)

#### Tags:

 - Menus, Pricing, Modifiers

#### Properties

- [Documentation](https://doc.toasttab.com/openapi/menusv3/overview/)

### Toast Orders API
Create, retrieve, modify, and void orders, checks, and selections; attach payments and refunds; manage dining options and service charges. The Orders API is the workhorse of Toast integrations — online-ordering channels, delivery providers, kiosks, and POS-aware tools all post orders here.

**Human URL:** [https://doc.toasttab.com/openapi/orders/overview/](https://doc.toasttab.com/openapi/orders/overview/)

#### Tags:

 - Orders, Checks, Payments, Online Ordering, Delivery

#### Properties

- [Documentation](https://doc.toasttab.com/openapi/orders/overview/)
- [OpenAPI](openapi/toast-tab-orders-openapi.yml)
- [JSONSchema](json-schema/orders-applicable-discount-schema.json)
- [JSONSchema](json-schema/orders-applicable-discounts-request-schema.json)
- [JSONSchema](json-schema/orders-applied-discount-reason-schema.json)
- [JSONSchema](json-schema/orders-applied-discount-schema.json)
- [JSONSchema](json-schema/orders-applied-discount-trigger-schema.json)
- [JSONSchema](json-schema/orders-applied-loyalty-info-schema.json)
- [JSONSchema](json-schema/orders-applied-packaging-info-schema.json)
- [JSONSchema](json-schema/orders-applied-packaging-item-schema.json)
- [JSONSchema](json-schema/orders-applied-service-charge-schema.json)
- [JSONSchema](json-schema/orders-applied-tax-rate-schema.json)
- [JSONSchema](json-schema/orders-check-schema.json)
- [JSONSchema](json-schema/orders-config-reference-schema.json)
- [JSONSchema](json-schema/orders-curbside-pickup-info-schema.json)
- [JSONSchema](json-schema/orders-customer-schema.json)
- [JSONSchema](json-schema/orders-delivery-info-schema.json)
- [JSONSchema](json-schema/orders-delivery-service-info-schema.json)
- [JSONSchema](json-schema/orders-device-schema.json)
- [JSONSchema](json-schema/orders-external-reference-schema.json)
- [JSONSchema](json-schema/orders-fulfillment-schema.json)
- [JSONSchema](json-schema/orders-gift-card-info-schema.json)
- [JSONSchema](json-schema/orders-loyalty-details-schema.json)
- [JSONSchema](json-schema/orders-marketplace-facilitator-tax-info-schema.json)
- [JSONSchema](json-schema/orders-order-response-schema.json)
- [JSONSchema](json-schema/orders-order-schema.json)
- [JSONSchema](json-schema/orders-payment-schema.json)
- [JSONSchema](json-schema/orders-refund-details-schema.json)
- [JSONSchema](json-schema/orders-refund-schema.json)
- [JSONSchema](json-schema/orders-refund-transaction-schema.json)
- [JSONSchema](json-schema/orders-selection-schema.json)
- [JSONSchema](json-schema/orders-toast-reference-schema.json)
- [JSONSchema](json-schema/orders-update-payment-request-schema.json)
- [JSONSchema](json-schema/orders-void-information-schema.json)
- [JSONStructure](json-structure/orders-applicable-discount-structure.json)
- [JSONStructure](json-structure/orders-applicable-discounts-request-structure.json)
- [JSONStructure](json-structure/orders-applied-discount-reason-structure.json)
- [JSONStructure](json-structure/orders-applied-discount-structure.json)
- [JSONStructure](json-structure/orders-applied-discount-trigger-structure.json)
- [JSONStructure](json-structure/orders-applied-loyalty-info-structure.json)
- [JSONStructure](json-structure/orders-applied-packaging-info-structure.json)
- [JSONStructure](json-structure/orders-applied-packaging-item-structure.json)
- [JSONStructure](json-structure/orders-applied-service-charge-structure.json)
- [JSONStructure](json-structure/orders-applied-tax-rate-structure.json)
- [JSONStructure](json-structure/orders-check-structure.json)
- [JSONStructure](json-structure/orders-config-reference-structure.json)
- [JSONStructure](json-structure/orders-curbside-pickup-info-structure.json)
- [JSONStructure](json-structure/orders-customer-structure.json)
- [JSONStructure](json-structure/orders-delivery-info-structure.json)
- [JSONStructure](json-structure/orders-delivery-service-info-structure.json)
- [JSONStructure](json-structure/orders-device-structure.json)
- [JSONStructure](json-structure/orders-external-reference-structure.json)
- [JSONStructure](json-structure/orders-fulfillment-structure.json)
- [JSONStructure](json-structure/orders-gift-card-info-structure.json)
- [JSONStructure](json-structure/orders-loyalty-details-structure.json)
- [JSONStructure](json-structure/orders-marketplace-facilitator-tax-info-structure.json)
- [JSONStructure](json-structure/orders-order-response-structure.json)
- [JSONStructure](json-structure/orders-order-structure.json)
- [JSONStructure](json-structure/orders-payment-structure.json)
- [JSONStructure](json-structure/orders-refund-details-structure.json)
- [JSONStructure](json-structure/orders-refund-structure.json)
- [JSONStructure](json-structure/orders-refund-transaction-structure.json)
- [JSONStructure](json-structure/orders-selection-structure.json)
- [JSONStructure](json-structure/orders-toast-reference-structure.json)
- [JSONStructure](json-structure/orders-update-payment-request-structure.json)
- [JSONStructure](json-structure/orders-void-information-structure.json)
- [Example](examples/orders-applicable-discount-example.json)
- [Example](examples/orders-applicable-discounts-request-example.json)
- [Example](examples/orders-applied-discount-example.json)
- [Example](examples/orders-applied-discount-reason-example.json)
- [Example](examples/orders-applied-discount-trigger-example.json)
- [Example](examples/orders-applied-loyalty-info-example.json)
- [Example](examples/orders-applied-packaging-info-example.json)
- [Example](examples/orders-applied-packaging-item-example.json)
- [Example](examples/orders-applied-service-charge-example.json)
- [Example](examples/orders-applied-tax-rate-example.json)
- [Example](examples/orders-check-example.json)
- [Example](examples/orders-config-reference-example.json)
- [Example](examples/orders-curbside-pickup-info-example.json)
- [Example](examples/orders-customer-example.json)
- [Example](examples/orders-delivery-info-example.json)
- [Example](examples/orders-delivery-service-info-example.json)
- [Example](examples/orders-device-example.json)
- [Example](examples/orders-external-reference-example.json)
- [Example](examples/orders-fulfillment-example.json)
- [Example](examples/orders-gift-card-info-example.json)
- [Example](examples/orders-loyalty-details-example.json)
- [Example](examples/orders-marketplace-facilitator-tax-info-example.json)
- [Example](examples/orders-order-example.json)
- [Example](examples/orders-order-response-example.json)
- [Example](examples/orders-payment-example.json)
- [Example](examples/orders-refund-details-example.json)
- [Example](examples/orders-refund-example.json)
- [Example](examples/orders-refund-transaction-example.json)
- [Example](examples/orders-selection-example.json)
- [Example](examples/orders-toast-reference-example.json)
- [Example](examples/orders-update-payment-request-example.json)
- [Example](examples/orders-void-information-example.json)
- [JSON-LD](json-ld/toast-tab-orders-context.jsonld)
- [NaftikoCapability](capabilities/orders-discounts.yaml)
- [NaftikoCapability](capabilities/orders-orders.yaml)
- [NaftikoCapability](capabilities/orders-payments.yaml)

### Toast Order Management Configuration API
Read configuration that governs how orders flow through Toast — throttling, prep-time rules, surge controls, and order-management settings used by online-ordering and delivery integrations.

**Human URL:** [https://doc.toasttab.com/openapi/ordermgmt.configuration/overview/](https://doc.toasttab.com/openapi/ordermgmt.configuration/overview/)

#### Tags:

 - Orders, Throttling, Configuration

#### Properties

- [Documentation](https://doc.toasttab.com/openapi/ordermgmt.configuration/overview/)

### Toast Restaurant Availability API
Returns whether a restaurant is currently accepting online orders, its expected prep times, and per-channel availability so ordering partners and delivery marketplaces can route demand appropriately.

**Human URL:** [https://doc.toasttab.com/openapi/rx.availability.service/overview/](https://doc.toasttab.com/openapi/rx.availability.service/overview/)

#### Tags:

 - Availability, Online Ordering, Delivery

#### Properties

- [Documentation](https://doc.toasttab.com/openapi/rx.availability.service/overview/)

### Toast Credit Cards API
Read tokenized credit-card information attached to orders for receipts, returns, and reconciliation. Toast Payments handles acceptance natively; this API exposes the resulting tokenized card records.

**Human URL:** [https://doc.toasttab.com/openapi/creditcards/overview/](https://doc.toasttab.com/openapi/creditcards/overview/)

#### Tags:

 - Payments, Credit Cards, Tokens

#### Properties

- [Documentation](https://doc.toasttab.com/openapi/creditcards/overview/)

### Toast Cash Management API
Records and retrieves cash entries — paid in, paid out, deposits, drawer counts — that flow into a restaurant's cash-management ledger and reconciliation reports.

**Human URL:** [https://doc.toasttab.com/openapi/cashmanagement/overview/](https://doc.toasttab.com/openapi/cashmanagement/overview/)

#### Tags:

 - Cash Management, Reconciliation, Payments

#### Properties

- [Documentation](https://doc.toasttab.com/openapi/cashmanagement/overview/)

### Toast Labor API
Manages employees, jobs, time entries, breaks, and shifts for Toast's labor-management surface — the integration point used by scheduling, payroll, and HR vendors.

**Human URL:** [https://doc.toasttab.com/openapi/labor/overview/](https://doc.toasttab.com/openapi/labor/overview/)

#### Tags:

 - Labor, Employees, Time Tracking, Scheduling, Payroll

#### Properties

- [Documentation](https://doc.toasttab.com/openapi/labor/overview/)
- [OpenAPI](openapi/toast-tab-labor-openapi.yml)
- [JSONSchema](json-schema/labor-employee-schema.json)
- [JSONSchema](json-schema/labor-external-reference-schema.json)
- [JSONSchema](json-schema/labor-job-schema.json)
- [JSONSchema](json-schema/labor-job-wage-override-schema.json)
- [JSONSchema](json-schema/labor-schedule-config-schema.json)
- [JSONSchema](json-schema/labor-shift-schema.json)
- [JSONSchema](json-schema/labor-time-entry-break-schema.json)
- [JSONSchema](json-schema/labor-time-entry-schema.json)
- [JSONSchema](json-schema/labor-toast-reference-schema.json)
- [JSONStructure](json-structure/labor-employee-structure.json)
- [JSONStructure](json-structure/labor-external-reference-structure.json)
- [JSONStructure](json-structure/labor-job-structure.json)
- [JSONStructure](json-structure/labor-job-wage-override-structure.json)
- [JSONStructure](json-structure/labor-schedule-config-structure.json)
- [JSONStructure](json-structure/labor-shift-structure.json)
- [JSONStructure](json-structure/labor-time-entry-break-structure.json)
- [JSONStructure](json-structure/labor-time-entry-structure.json)
- [JSONStructure](json-structure/labor-toast-reference-structure.json)
- [Example](examples/labor-employee-example.json)
- [Example](examples/labor-external-reference-example.json)
- [Example](examples/labor-job-example.json)
- [Example](examples/labor-job-wage-override-example.json)
- [Example](examples/labor-schedule-config-example.json)
- [Example](examples/labor-shift-example.json)
- [Example](examples/labor-time-entry-break-example.json)
- [Example](examples/labor-time-entry-example.json)
- [Example](examples/labor-toast-reference-example.json)
- [JSON-LD](json-ld/toast-tab-labor-context.jsonld)
- [NaftikoCapability](capabilities/labor-employees.yaml)
- [NaftikoCapability](capabilities/labor-jobs.yaml)
- [NaftikoCapability](capabilities/labor-shifts.yaml)
- [NaftikoCapability](capabilities/labor-time-entries.yaml)

### Toast Kitchen API
Surfaces kitchen tickets, prep stations, ticket items, and ticket events to support kitchen-display integrations and out-of-band prep orchestration.

**Human URL:** [https://doc.toasttab.com/openapi/kitchen/overview/](https://doc.toasttab.com/openapi/kitchen/overview/)

#### Tags:

 - Kitchen, Tickets, Prep

#### Properties

- [Documentation](https://doc.toasttab.com/openapi/kitchen/overview/)

### Toast Packaging Configuration API
Read configuration about packaging — containers, lids, utensils, and packaging instructions — that off-premises orders and delivery handoff workflows must respect.

**Human URL:** [https://doc.toasttab.com/openapi/packaging/overview/](https://doc.toasttab.com/openapi/packaging/overview/)

#### Tags:

 - Packaging, Delivery, Off Premises

#### Properties

- [Documentation](https://doc.toasttab.com/openapi/packaging/overview/)

### Toast Stock API
Read and update menu-item stock levels — what is in stock, what is sold out, what is limited — so online-ordering, delivery, and inventory tools stay in sync with the restaurant's true sellable catalog.

**Human URL:** [https://doc.toasttab.com/openapi/stock/overview/](https://doc.toasttab.com/openapi/stock/overview/)

#### Tags:

 - Stock, Inventory, 86ing, Online Ordering

#### Properties

- [Documentation](https://doc.toasttab.com/openapi/stock/overview/)
- [OpenAPI](openapi/toast-tab-stock-openapi.yml)
- [JSONSchema](json-schema/stock-inventory-search-request-schema.json)
- [JSONSchema](json-schema/stock-menu-item-inventory-schema.json)
- [JSONStructure](json-structure/stock-inventory-search-request-structure.json)
- [JSONStructure](json-structure/stock-menu-item-inventory-structure.json)
- [Example](examples/stock-inventory-search-request-example.json)
- [Example](examples/stock-menu-item-inventory-example.json)
- [JSON-LD](json-ld/toast-tab-stock-context.jsonld)
- [NaftikoCapability](capabilities/stock-stock.yaml)

### Toast Analytics API
Analytics and reporting endpoints for Restaurant Management Suites Pro customers — sales, labor, productivity, and operational performance data exposed for BI integrations and warehouse pipelines.

**Human URL:** [https://doc.toasttab.com/openapi/analytics/overview/](https://doc.toasttab.com/openapi/analytics/overview/)

#### Tags:

 - Analytics, Reporting, BI

#### Properties

- [Documentation](https://doc.toasttab.com/openapi/analytics/overview/)

### Toast Partners API
Enables Toast Partner Integration clients to enumerate the restaurants that have authorized them. Exposes "accessible restaurants" and "connected restaurants" so a partner can discover and provision its tenant base across the Toast network.

**Human URL:** [https://doc.toasttab.com/openapi/partners/overview/](https://doc.toasttab.com/openapi/partners/overview/)

#### Tags:

 - Partners, Tenancy, Onboarding

#### Properties

- [Documentation](https://doc.toasttab.com/openapi/partners/overview/)
- [OpenAPI](openapi/toast-tab-partners-openapi.yml)
- [JSONSchema](json-schema/partners-paginated-response-schema.json)
- [JSONSchema](json-schema/partners-partner-access-external-rep-schema.json)
- [JSONSchema](json-schema/partners-partner-access-external-webhook-rep-schema.json)
- [JSONStructure](json-structure/partners-paginated-response-structure.json)
- [JSONStructure](json-structure/partners-partner-access-external-rep-structure.json)
- [JSONStructure](json-structure/partners-partner-access-external-webhook-rep-structure.json)
- [Example](examples/partners-paginated-response-example.json)
- [Example](examples/partners-partner-access-external-rep-example.json)
- [Example](examples/partners-partner-access-external-webhook-rep-example.json)
- [JSON-LD](json-ld/toast-tab-partners-context.jsonld)
- [NaftikoCapability](capabilities/partners-general.yaml)

### Toast Gift Cards Integration
Specification for integrating third-party gift-card programs with Toast — Toast calls the partner's endpoints to look up balances, authorize, redeem, and reload gift cards inline with a check.

**Human URL:** [https://doc.toasttab.com/openapi/giftcards/overview/](https://doc.toasttab.com/openapi/giftcards/overview/)

#### Tags:

 - Gift Cards, Integrations, Partners

#### Properties

- [Documentation](https://doc.toasttab.com/openapi/giftcards/overview/)

### Toast Loyalty Integration
Specification for integrating third-party loyalty programs with Toast — discovery, lookup, accrual, and redemption callbacks that Toast invokes against partner endpoints during a transaction.

**Human URL:** [https://doc.toasttab.com/openapi/loyalty/overview/](https://doc.toasttab.com/openapi/loyalty/overview/)

#### Tags:

 - Loyalty, Integrations, Partners

#### Properties

- [Documentation](https://doc.toasttab.com/openapi/loyalty/overview/)

### Toast Tender Integration
Specification for integrating alternative tender types into Toast — callback endpoints partners implement so Toast can validate, authorize, and reconcile non-card forms of payment at checkout.

**Human URL:** [https://doc.toasttab.com/openapi/tender/overview/](https://doc.toasttab.com/openapi/tender/overview/)

#### Tags:

 - Tender, Payments, Integrations, Partners

#### Properties

- [Documentation](https://doc.toasttab.com/openapi/tender/overview/)

## Common Properties

- [Website](https://pos.toasttab.com/)
- [DeveloperPortal](https://dev.toasttab.com/)
- [Documentation](https://doc.toasttab.com/)
- [APIReference](https://doc.toasttab.com/openapi/)
- [DeveloperGuide](https://doc.toasttab.com/doc/devguide/index.html)
- [HowToGuides](https://doc.toasttab.com/doc/cookbook/index.html)
- [PlatformGuide](https://doc.toasttab.com/doc/platformguide/index.html)
- [ReleaseNotes](https://doc.toasttab.com/doc/relnotes/index.html)
- [Authentication](https://doc.toasttab.com/doc/devguide/authentication.html)
- [Webhooks](https://doc.toasttab.com/doc/devguide/webhooks.html)
- [PartnerProgram](https://pos.toasttab.com/integrations)
- [GitHubOrganization](https://github.com/toasttab)
- [LinkedIn](https://www.linkedin.com/company/toast-inc)
- [Investors](https://investors.toasttab.com/)
- [Status](https://status.toasttab.com/)
- [Support](https://central.toasttab.com/)
- [Pricing](https://pos.toasttab.com/pricing)
- [SignUp](https://pos.toasttab.com/get-a-demo)
- [SpectralRules](rules/toast-tab-spectral-rules.yml)
- [Vocabulary](vocabulary/toast-tab-vocabulary.yaml)
- [Plans](plans/toast-tab-plans-pricing.yml)
- [RateLimits](rate-limits/toast-tab-rate-limits.yml)
- [FinOps](finops/toast-tab-finops.yml)

## Features

| Name | Description |
|------|-------------|
| OAuth 2.0 Client Credentials | Machine-to-machine authentication issuing bearer tokens for all Toast platform APIs. |
| Orders & Payments | Create, retrieve, modify, and void orders, checks, selections, payments, and refunds. |
| Menus | Read published menu, menu group, item, modifier, and pricing data in V2 and V3 shapes. |
| Labor Management | Manage employees, jobs, shifts, and time entries for scheduling and payroll vendors. |
| Stock / 86ing | Read and update menu-item stock levels to keep ordering channels in sync. |
| Partner Integrations | Discover accessible and connected restaurants across the Toast network for a partner client. |

## Use Cases

| Name | Description |
|------|-------------|
| Online Ordering Integration | Post orders and read menus/stock to power third-party ordering and delivery channels. |
| Payroll & Scheduling | Sync employees, jobs, shifts, and time entries into payroll, HR, and scheduling platforms. |
| BI & Reporting | Pull analytics and operational data into warehouses and BI tooling. |
| Gift Card & Loyalty Programs | Integrate third-party gift card, loyalty, and alternative tender programs via callback specs. |

## Integrations

| Name | Description |
|------|-------------|
| Delivery Marketplaces | Route demand and availability to delivery and online-ordering partners. |
| Payroll Providers | Labor API time entries feed payroll and workforce-management systems. |
| Loyalty & Gift Card Vendors | Inline callbacks let third-party loyalty/gift-card programs participate in checks. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [toast-tab-authentication-openapi.yml](openapi/toast-tab-authentication-openapi.yml)
- [toast-tab-labor-openapi.yml](openapi/toast-tab-labor-openapi.yml)
- [toast-tab-menus-openapi.yml](openapi/toast-tab-menus-openapi.yml)
- [toast-tab-orders-openapi.yml](openapi/toast-tab-orders-openapi.yml)
- [toast-tab-partners-openapi.yml](openapi/toast-tab-partners-openapi.yml)
- [toast-tab-restaurants-openapi.yml](openapi/toast-tab-restaurants-openapi.yml)
- [toast-tab-stock-openapi.yml](openapi/toast-tab-stock-openapi.yml)

### JSON Schema (110 files)

JSON Schema definitions extracted from the OpenAPI specifications, in `json-schema/`.

### JSON Structure (110 files)

JSON Structure representations, in `json-structure/`.

### JSON-LD

- [toast-tab-authentication-context.jsonld](json-ld/toast-tab-authentication-context.jsonld)
- [toast-tab-labor-context.jsonld](json-ld/toast-tab-labor-context.jsonld)
- [toast-tab-menus-context.jsonld](json-ld/toast-tab-menus-context.jsonld)
- [toast-tab-orders-context.jsonld](json-ld/toast-tab-orders-context.jsonld)
- [toast-tab-partners-context.jsonld](json-ld/toast-tab-partners-context.jsonld)
- [toast-tab-restaurants-context.jsonld](json-ld/toast-tab-restaurants-context.jsonld)
- [toast-tab-stock-context.jsonld](json-ld/toast-tab-stock-context.jsonld)

### Examples (110 files)

Realistic example payloads per schema, in `examples/`.

## Capabilities

Self-contained Naftiko capabilities, one per Toast API business surface (REST + MCP exposers inline).

| Capability | Tools | File |
|------------|-------|------|
| Toast authentication API — Authentication | 1 | [authentication-authentication.yaml](capabilities/authentication-authentication.yaml) |
| Toast Labor API — Employees | 10 | [labor-employees.yaml](capabilities/labor-employees.yaml) |
| Toast Labor API — Jobs | 4 | [labor-jobs.yaml](capabilities/labor-jobs.yaml) |
| Toast Labor API — Shifts | 5 | [labor-shifts.yaml](capabilities/labor-shifts.yaml) |
| Toast Labor API — Time entries | 2 | [labor-time-entries.yaml](capabilities/labor-time-entries.yaml) |
| Menus API — general | 2 | [menus-general.yaml](capabilities/menus-general.yaml) |
| Toast Orders API — Discounts | 3 | [orders-discounts.yaml](capabilities/orders-discounts.yaml) |
| Toast Orders API — Orders | 8 | [orders-orders.yaml](capabilities/orders-orders.yaml) |
| Toast Orders API — Payments | 4 | [orders-payments.yaml](capabilities/orders-payments.yaml) |
| Partners API — general | 2 | [partners-general.yaml](capabilities/partners-general.yaml) |
| Restaurants API — general | 2 | [restaurants-general.yaml](capabilities/restaurants-general.yaml) |
| Stock API — Stock | 3 | [stock-stock.yaml](capabilities/stock-stock.yaml) |

## Vocabulary

- [Toast Vocabulary](vocabulary/toast-tab-vocabulary.yaml) — Unified taxonomy mapping 10 resources, 5 actions, 2 workflows, and 3 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Toast Spectral Rules](rules/toast-tab-spectral-rules.yml) — 33 rules enforcing Toast API conventions

## Commercial

- [Plans & Pricing (API Commons Plans 0.1)](plans/toast-tab-plans-pricing.yml)
- [Rate Limits (API Commons Rate Limits 0.1)](rate-limits/toast-tab-rate-limits.yml)
- [FinOps / FOCUS Alignment](finops/toast-tab-finops.yml)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
