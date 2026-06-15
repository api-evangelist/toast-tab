# Toast (toast-tab)

Toast (NYSE: TOST) is a cloud-based restaurant technology platform that unifies point-of-sale (POS), payments, online ordering, delivery, digital marketing, loyalty, gift cards, kitchen display, inventory, and team management for restaurants of every size — from independent operators to enterprise chains. The Toast platform exposes a substantial REST API surface at https://ws-api.toasttab.com/, authenticated via OAuth 2.0 client credentials, and is used by restaurants, internal IT teams, and the Toast Partner Integrations program to read and write menus, orders, payments, employees, schedules, time entries, cash entries, kitchen tickets, restaurant configuration, gift cards, loyalty balances, and partner-restaurant connections. Toast offers three flavors of API access: Standard API Access (self-service for restaurant operators), Analytics API Access (Restaurant Management Suites Pro), and Partner Integrations (technology companies building productized integrations).

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/toast-tab/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/toast-tab/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

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
- **Modified:** 2026-06-03

## APIs

### Toast Authentication API

OAuth 2.0 client-credentials authentication for Toast APIs. Exchanges a clientId and clientSecret (with userAccessType TOAST_MACHINE_CLIENT) for a bearer access token at /authentication/v1/authentication/login. Token lifetime is returned in the response and varies by environment.

- **Human URL:** [https://doc.toasttab.com/openapi/authentication/overview/](https://doc.toasttab.com/openapi/authentication/overview/)
- **Base URL:** `https://ws-api.toasttab.com/authentication/v1`

#### Tags

- Authentication
- OAuth
- Tokens

#### Properties

- [Documentation](https://doc.toasttab.com/openapi/authentication/overview/)
- [Authentication Guide](https://doc.toasttab.com/doc/devguide/authentication.html)
- [OpenAPI](openapi/toast-tab-authentication-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/toast-tab-authentication.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-authentication.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/authentication-authentication-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/authentication-authentication-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/authentication-authentication-token-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/authentication-authentication-request-structure.json)
- [JSON Structure](json-structure/authentication-authentication-response-structure.json)
- [JSON Structure](json-structure/authentication-authentication-token-structure.json)
- [Example](examples/authentication-authentication-request-example.json)
- [Example](examples/authentication-authentication-response-example.json)
- [Example](examples/authentication-authentication-token-example.json)
- [J S O N- L D](json-ld/toast-tab-authentication-context.jsonld)

### Toast Restaurants API

Returns restaurant-level information including locations, addresses, hours, schedules, urls, closeout hour, and reference identifiers that anchor every other Toast API call (restaurantGuid).

- **Human URL:** [https://doc.toasttab.com/openapi/restaurants/overview/](https://doc.toasttab.com/openapi/restaurants/overview/)
- **Base URL:** `https://ws-api.toasttab.com/restaurants/v1`

#### Tags

- Restaurants
- Locations
- Configuration

#### Properties

- [Documentation](https://doc.toasttab.com/openapi/restaurants/overview/)
- [OpenAPI](openapi/toast-tab-restaurants-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/toast-tab-restaurants.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-restaurants.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/restaurants-day-schedule-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/restaurants-delivery-payment-options-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/restaurants-delivery-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/restaurants-general-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/restaurants-hours-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/restaurants-image-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/restaurants-location-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/restaurants-online-ordering-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/restaurants-payment-options-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/restaurants-prep-times-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/restaurants-restaurant-info-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/restaurants-restaurant-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/restaurants-schedules-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/restaurants-service-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/restaurants-takeout-payment-options-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/restaurants-urls-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/restaurants-week-schedule-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/restaurants-day-schedule-structure.json)
- [JSON Structure](json-structure/restaurants-delivery-payment-options-structure.json)
- [JSON Structure](json-structure/restaurants-delivery-structure.json)
- [JSON Structure](json-structure/restaurants-general-structure.json)
- [JSON Structure](json-structure/restaurants-hours-structure.json)
- [JSON Structure](json-structure/restaurants-image-structure.json)
- [JSON Structure](json-structure/restaurants-location-structure.json)
- [JSON Structure](json-structure/restaurants-online-ordering-structure.json)
- [JSON Structure](json-structure/restaurants-payment-options-structure.json)
- [JSON Structure](json-structure/restaurants-prep-times-structure.json)
- [JSON Structure](json-structure/restaurants-restaurant-info-structure.json)
- [JSON Structure](json-structure/restaurants-restaurant-structure.json)
- [JSON Structure](json-structure/restaurants-schedules-structure.json)
- [JSON Structure](json-structure/restaurants-service-structure.json)
- [JSON Structure](json-structure/restaurants-takeout-payment-options-structure.json)
- [JSON Structure](json-structure/restaurants-urls-structure.json)
- [JSON Structure](json-structure/restaurants-week-schedule-structure.json)
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
- [J S O N- L D](json-ld/toast-tab-restaurants-context.jsonld)

### Toast Configuration API

Read-access to a restaurant's configuration entities — menus, modifier groups, employees, jobs, dining options, service areas, revenue centers, sales categories, discounts, service charges, and table topology — that drive POS behavior.

- **Human URL:** [https://doc.toasttab.com/openapi/configuration/overview/](https://doc.toasttab.com/openapi/configuration/overview/)
- **Base URL:** `https://ws-api.toasttab.com/config/v2`

#### Tags

- Configuration
- Employees
- Discounts
- Service Charges

#### Properties

- [Documentation](https://doc.toasttab.com/openapi/configuration/overview/)
- [Postman Collection](collections/toast-tab-authentication.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-authentication.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-labor.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-labor.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-menus.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-menus.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-orders.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-orders.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-partners.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-partners.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-restaurants.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-restaurants.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-stock.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-stock.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Toast Menus API (V2)

Returns published menu data for a restaurant — menus, menu groups, menu items, modifier groups, options, prices, and tax info — in the legacy V2 shape used by ordering and POS integrations.

- **Human URL:** [https://doc.toasttab.com/openapi/menus/overview/](https://doc.toasttab.com/openapi/menus/overview/)
- **Base URL:** `https://ws-api.toasttab.com/menus/v2`

#### Tags

- Menus
- Pricing
- Modifiers

#### Properties

- [Documentation](https://doc.toasttab.com/openapi/menus/overview/)
- [OpenAPI](openapi/toast-tab-menus-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/toast-tab-menus.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-menus.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/menus-alcohol-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/menus-allergen-item-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/menus-availability-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/menus-catalog-product-info-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/menus-catalog-product-option-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/menus-catalog-product-option-value-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/menus-catalog-product-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/menus-catalog-product-variant-option-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/menus-catalog-product-variant-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/menus-content-advisories-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/menus-dimension-unit-of-measure-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/menus-guest-count-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/menus-height-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/menus-image-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/menus-images-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/menus-item-tag-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/menus-length-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/menus-master-id-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/menus-menu-group-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/menus-menu-item-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/menus-menu-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/menus-metadata-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/menus-modifier-group-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/menus-modifier-option-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/menus-modifier-option-tax-info-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/menus-multi-location-id-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/menus-portion-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/menus-pos-button-color-dark-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/menus-pos-button-color-light-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/menus-pos-name-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/menus-pre-modifier-group-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/menus-pre-modifier-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/menus-pricing-rules-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/menus-restaurant-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/menus-sales-category-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/menus-schedule-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/menus-sequence-price-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/menus-size-sequence-pricing-rule-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/menus-time-range-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/menus-time-specific-price-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/menus-visibility-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/menus-weight-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/menus-weight-unit-of-measure-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/menus-width-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/menus-alcohol-structure.json)
- [JSON Structure](json-structure/menus-allergen-item-structure.json)
- [JSON Structure](json-structure/menus-availability-structure.json)
- [JSON Structure](json-structure/menus-catalog-product-info-structure.json)
- [JSON Structure](json-structure/menus-catalog-product-option-structure.json)
- [JSON Structure](json-structure/menus-catalog-product-option-value-structure.json)
- [JSON Structure](json-structure/menus-catalog-product-structure.json)
- [JSON Structure](json-structure/menus-catalog-product-variant-option-structure.json)
- [JSON Structure](json-structure/menus-catalog-product-variant-structure.json)
- [JSON Structure](json-structure/menus-content-advisories-structure.json)
- [JSON Structure](json-structure/menus-dimension-unit-of-measure-structure.json)
- [JSON Structure](json-structure/menus-guest-count-structure.json)
- [JSON Structure](json-structure/menus-height-structure.json)
- [JSON Structure](json-structure/menus-image-structure.json)
- [JSON Structure](json-structure/menus-images-structure.json)
- [JSON Structure](json-structure/menus-item-tag-structure.json)
- [JSON Structure](json-structure/menus-length-structure.json)
- [JSON Structure](json-structure/menus-master-id-structure.json)
- [JSON Structure](json-structure/menus-menu-group-structure.json)
- [JSON Structure](json-structure/menus-menu-item-structure.json)
- [JSON Structure](json-structure/menus-menu-structure.json)
- [JSON Structure](json-structure/menus-metadata-structure.json)
- [JSON Structure](json-structure/menus-modifier-group-structure.json)
- [JSON Structure](json-structure/menus-modifier-option-structure.json)
- [JSON Structure](json-structure/menus-modifier-option-tax-info-structure.json)
- [JSON Structure](json-structure/menus-multi-location-id-structure.json)
- [JSON Structure](json-structure/menus-portion-structure.json)
- [JSON Structure](json-structure/menus-pos-button-color-dark-structure.json)
- [JSON Structure](json-structure/menus-pos-button-color-light-structure.json)
- [JSON Structure](json-structure/menus-pos-name-structure.json)
- [JSON Structure](json-structure/menus-pre-modifier-group-structure.json)
- [JSON Structure](json-structure/menus-pre-modifier-structure.json)
- [JSON Structure](json-structure/menus-pricing-rules-structure.json)
- [JSON Structure](json-structure/menus-restaurant-structure.json)
- [JSON Structure](json-structure/menus-sales-category-structure.json)
- [JSON Structure](json-structure/menus-schedule-structure.json)
- [JSON Structure](json-structure/menus-sequence-price-structure.json)
- [JSON Structure](json-structure/menus-size-sequence-pricing-rule-structure.json)
- [JSON Structure](json-structure/menus-time-range-structure.json)
- [JSON Structure](json-structure/menus-time-specific-price-structure.json)
- [JSON Structure](json-structure/menus-visibility-structure.json)
- [JSON Structure](json-structure/menus-weight-structure.json)
- [JSON Structure](json-structure/menus-weight-unit-of-measure-structure.json)
- [JSON Structure](json-structure/menus-width-structure.json)
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
- [J S O N- L D](json-ld/toast-tab-menus-context.jsonld)

### Toast Menus API (V3)

Next-generation read API for Toast menus, exposing the same menu / menu group / item / modifier / option model as V2 in a refreshed shape aligned with Toast's newer platform services.

- **Human URL:** [https://doc.toasttab.com/openapi/menusv3/overview/](https://doc.toasttab.com/openapi/menusv3/overview/)
- **Base URL:** `https://ws-api.toasttab.com/menus/v3`

#### Tags

- Menus
- Pricing
- Modifiers

#### Properties

- [Documentation](https://doc.toasttab.com/openapi/menusv3/overview/)
- [Postman Collection](collections/toast-tab-authentication.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-authentication.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-labor.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-labor.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-menus.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-menus.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-orders.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-orders.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-partners.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-partners.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-restaurants.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-restaurants.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-stock.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-stock.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Toast Orders API

Create, retrieve, modify, and void orders, checks, and selections; attach payments and refunds; manage dining options and service charges. The Orders API is the workhorse of Toast integrations — online-ordering channels, delivery providers, kiosks, and POS-aware tools all post orders here.

- **Human URL:** [https://doc.toasttab.com/openapi/orders/overview/](https://doc.toasttab.com/openapi/orders/overview/)
- **Base URL:** `https://ws-api.toasttab.com/orders/v2`

#### Tags

- Orders
- Checks
- Payments
- Online Ordering
- Delivery

#### Properties

- [Documentation](https://doc.toasttab.com/openapi/orders/overview/)
- [OpenAPI](openapi/toast-tab-orders-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/toast-tab-orders.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-orders.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/orders-applicable-discount-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/orders-applicable-discounts-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/orders-applied-discount-reason-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/orders-applied-discount-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/orders-applied-discount-trigger-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/orders-applied-loyalty-info-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/orders-applied-packaging-info-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/orders-applied-packaging-item-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/orders-applied-service-charge-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/orders-applied-tax-rate-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/orders-check-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/orders-config-reference-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/orders-curbside-pickup-info-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/orders-customer-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/orders-delivery-info-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/orders-delivery-service-info-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/orders-device-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/orders-external-reference-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/orders-fulfillment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/orders-gift-card-info-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/orders-loyalty-details-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/orders-marketplace-facilitator-tax-info-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/orders-order-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/orders-order-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/orders-payment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/orders-refund-details-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/orders-refund-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/orders-refund-transaction-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/orders-selection-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/orders-toast-reference-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/orders-update-payment-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/orders-void-information-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/orders-applicable-discount-structure.json)
- [JSON Structure](json-structure/orders-applicable-discounts-request-structure.json)
- [JSON Structure](json-structure/orders-applied-discount-reason-structure.json)
- [JSON Structure](json-structure/orders-applied-discount-structure.json)
- [JSON Structure](json-structure/orders-applied-discount-trigger-structure.json)
- [JSON Structure](json-structure/orders-applied-loyalty-info-structure.json)
- [JSON Structure](json-structure/orders-applied-packaging-info-structure.json)
- [JSON Structure](json-structure/orders-applied-packaging-item-structure.json)
- [JSON Structure](json-structure/orders-applied-service-charge-structure.json)
- [JSON Structure](json-structure/orders-applied-tax-rate-structure.json)
- [JSON Structure](json-structure/orders-check-structure.json)
- [JSON Structure](json-structure/orders-config-reference-structure.json)
- [JSON Structure](json-structure/orders-curbside-pickup-info-structure.json)
- [JSON Structure](json-structure/orders-customer-structure.json)
- [JSON Structure](json-structure/orders-delivery-info-structure.json)
- [JSON Structure](json-structure/orders-delivery-service-info-structure.json)
- [JSON Structure](json-structure/orders-device-structure.json)
- [JSON Structure](json-structure/orders-external-reference-structure.json)
- [JSON Structure](json-structure/orders-fulfillment-structure.json)
- [JSON Structure](json-structure/orders-gift-card-info-structure.json)
- [JSON Structure](json-structure/orders-loyalty-details-structure.json)
- [JSON Structure](json-structure/orders-marketplace-facilitator-tax-info-structure.json)
- [JSON Structure](json-structure/orders-order-response-structure.json)
- [JSON Structure](json-structure/orders-order-structure.json)
- [JSON Structure](json-structure/orders-payment-structure.json)
- [JSON Structure](json-structure/orders-refund-details-structure.json)
- [JSON Structure](json-structure/orders-refund-structure.json)
- [JSON Structure](json-structure/orders-refund-transaction-structure.json)
- [JSON Structure](json-structure/orders-selection-structure.json)
- [JSON Structure](json-structure/orders-toast-reference-structure.json)
- [JSON Structure](json-structure/orders-update-payment-request-structure.json)
- [JSON Structure](json-structure/orders-void-information-structure.json)
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
- [J S O N- L D](json-ld/toast-tab-orders-context.jsonld)

### Toast Order Management Configuration API

Read configuration that governs how orders flow through Toast — throttling, prep-time rules, surge controls, and order-management settings used by online-ordering and delivery integrations.

- **Human URL:** [https://doc.toasttab.com/openapi/ordermgmt.configuration/overview/](https://doc.toasttab.com/openapi/ordermgmt.configuration/overview/)
- **Base URL:** `https://ws-api.toasttab.com/ordermgmt-config/v1`

#### Tags

- Orders
- Throttling
- Configuration

#### Properties

- [Documentation](https://doc.toasttab.com/openapi/ordermgmt.configuration/overview/)
- [Postman Collection](collections/toast-tab-authentication.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-authentication.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-labor.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-labor.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-menus.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-menus.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-orders.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-orders.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-partners.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-partners.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-restaurants.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-restaurants.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-stock.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-stock.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Toast Restaurant Availability API

Returns whether a restaurant is currently accepting online orders, its expected prep times, and per-channel availability so ordering partners and delivery marketplaces can route demand appropriately.

- **Human URL:** [https://doc.toasttab.com/openapi/rx.availability.service/overview/](https://doc.toasttab.com/openapi/rx.availability.service/overview/)
- **Base URL:** `https://ws-api.toasttab.com/restaurants/v1/availability`

#### Tags

- Availability
- Online Ordering
- Delivery

#### Properties

- [Documentation](https://doc.toasttab.com/openapi/rx.availability.service/overview/)
- [Postman Collection](collections/toast-tab-authentication.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-authentication.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-labor.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-labor.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-menus.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-menus.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-orders.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-orders.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-partners.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-partners.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-restaurants.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-restaurants.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-stock.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-stock.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Toast Credit Cards API

Read tokenized credit-card information attached to orders for receipts, returns, and reconciliation. Toast Payments handles acceptance natively; this API exposes the resulting tokenized card records.

- **Human URL:** [https://doc.toasttab.com/openapi/creditcards/overview/](https://doc.toasttab.com/openapi/creditcards/overview/)
- **Base URL:** `https://ws-api.toasttab.com/creditcards/v1`

#### Tags

- Payments
- Credit Cards
- Tokens

#### Properties

- [Documentation](https://doc.toasttab.com/openapi/creditcards/overview/)
- [Postman Collection](collections/toast-tab-authentication.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-authentication.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-labor.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-labor.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-menus.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-menus.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-orders.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-orders.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-partners.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-partners.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-restaurants.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-restaurants.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-stock.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-stock.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Toast Cash Management API

Records and retrieves cash entries — paid in, paid out, deposits, drawer counts — that flow into a restaurant's cash-management ledger and reconciliation reports.

- **Human URL:** [https://doc.toasttab.com/openapi/cashmanagement/overview/](https://doc.toasttab.com/openapi/cashmanagement/overview/)
- **Base URL:** `https://ws-api.toasttab.com/cashmgmt/v1`

#### Tags

- Cash Management
- Reconciliation
- Payments

#### Properties

- [Documentation](https://doc.toasttab.com/openapi/cashmanagement/overview/)
- [Postman Collection](collections/toast-tab-authentication.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-authentication.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-labor.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-labor.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-menus.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-menus.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-orders.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-orders.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-partners.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-partners.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-restaurants.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-restaurants.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-stock.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-stock.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Toast Labor API

Manages employees, jobs, time entries, breaks, and shifts for Toast's labor-management surface — the integration point used by scheduling, payroll, and HR vendors.

- **Human URL:** [https://doc.toasttab.com/openapi/labor/overview/](https://doc.toasttab.com/openapi/labor/overview/)
- **Base URL:** `https://ws-api.toasttab.com/labor/v1`

#### Tags

- Labor
- Employees
- Time Tracking
- Scheduling
- Payroll

#### Properties

- [Documentation](https://doc.toasttab.com/openapi/labor/overview/)
- [OpenAPI](openapi/toast-tab-labor-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/toast-tab-labor.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-labor.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/labor-employee-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/labor-external-reference-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/labor-job-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/labor-job-wage-override-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/labor-schedule-config-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/labor-shift-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/labor-time-entry-break-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/labor-time-entry-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/labor-toast-reference-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/labor-employee-structure.json)
- [JSON Structure](json-structure/labor-external-reference-structure.json)
- [JSON Structure](json-structure/labor-job-structure.json)
- [JSON Structure](json-structure/labor-job-wage-override-structure.json)
- [JSON Structure](json-structure/labor-schedule-config-structure.json)
- [JSON Structure](json-structure/labor-shift-structure.json)
- [JSON Structure](json-structure/labor-time-entry-break-structure.json)
- [JSON Structure](json-structure/labor-time-entry-structure.json)
- [JSON Structure](json-structure/labor-toast-reference-structure.json)
- [Example](examples/labor-employee-example.json)
- [Example](examples/labor-external-reference-example.json)
- [Example](examples/labor-job-example.json)
- [Example](examples/labor-job-wage-override-example.json)
- [Example](examples/labor-schedule-config-example.json)
- [Example](examples/labor-shift-example.json)
- [Example](examples/labor-time-entry-break-example.json)
- [Example](examples/labor-time-entry-example.json)
- [Example](examples/labor-toast-reference-example.json)
- [J S O N- L D](json-ld/toast-tab-labor-context.jsonld)

### Toast Kitchen API

Surfaces kitchen tickets, prep stations, ticket items, and ticket events to support kitchen-display integrations and out-of-band prep orchestration.

- **Human URL:** [https://doc.toasttab.com/openapi/kitchen/overview/](https://doc.toasttab.com/openapi/kitchen/overview/)
- **Base URL:** `https://ws-api.toasttab.com/kitchen/v1`

#### Tags

- Kitchen
- Tickets
- Prep

#### Properties

- [Documentation](https://doc.toasttab.com/openapi/kitchen/overview/)
- [Postman Collection](collections/toast-tab-authentication.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-authentication.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-labor.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-labor.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-menus.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-menus.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-orders.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-orders.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-partners.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-partners.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-restaurants.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-restaurants.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-stock.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-stock.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Toast Packaging Configuration API

Read configuration about packaging — containers, lids, utensils, and packaging instructions — that off-premises orders and delivery handoff workflows must respect.

- **Human URL:** [https://doc.toasttab.com/openapi/packaging/overview/](https://doc.toasttab.com/openapi/packaging/overview/)
- **Base URL:** `https://ws-api.toasttab.com/packaging/v1`

#### Tags

- Packaging
- Delivery
- Off Premises

#### Properties

- [Documentation](https://doc.toasttab.com/openapi/packaging/overview/)
- [Postman Collection](collections/toast-tab-authentication.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-authentication.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-labor.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-labor.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-menus.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-menus.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-orders.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-orders.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-partners.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-partners.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-restaurants.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-restaurants.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-stock.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-stock.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Toast Stock API

Read and update menu-item stock levels — what is in stock, what is sold out, what is limited — so online-ordering, delivery, and inventory tools stay in sync with the restaurant's true sellable catalog.

- **Human URL:** [https://doc.toasttab.com/openapi/stock/overview/](https://doc.toasttab.com/openapi/stock/overview/)
- **Base URL:** `https://ws-api.toasttab.com/stock/v1`

#### Tags

- Stock
- Inventory
- 86ing
- Online Ordering

#### Properties

- [Documentation](https://doc.toasttab.com/openapi/stock/overview/)
- [OpenAPI](openapi/toast-tab-stock-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/toast-tab-stock.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-stock.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/stock-inventory-search-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/stock-menu-item-inventory-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/stock-inventory-search-request-structure.json)
- [JSON Structure](json-structure/stock-menu-item-inventory-structure.json)
- [Example](examples/stock-inventory-search-request-example.json)
- [Example](examples/stock-menu-item-inventory-example.json)
- [J S O N- L D](json-ld/toast-tab-stock-context.jsonld)

### Toast Analytics API

Analytics and reporting endpoints for Restaurant Management Suites Pro customers — sales, labor, productivity, and operational performance data exposed for BI integrations and warehouse pipelines.

- **Human URL:** [https://doc.toasttab.com/openapi/analytics/overview/](https://doc.toasttab.com/openapi/analytics/overview/)
- **Base URL:** `https://ws-api.toasttab.com/analytics/v1`

#### Tags

- Analytics
- Reporting
- BI

#### Properties

- [Documentation](https://doc.toasttab.com/openapi/analytics/overview/)
- [Postman Collection](collections/toast-tab-authentication.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-authentication.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-labor.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-labor.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-menus.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-menus.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-orders.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-orders.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-partners.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-partners.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-restaurants.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-restaurants.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-stock.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-stock.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Toast Partners API

Enables Toast Partner Integration clients to enumerate the restaurants that have authorized them. Exposes "accessible restaurants" and "connected restaurants" so a partner can discover and provision its tenant base across the Toast network.

- **Human URL:** [https://doc.toasttab.com/openapi/partners/overview/](https://doc.toasttab.com/openapi/partners/overview/)
- **Base URL:** `https://ws-api.toasttab.com/partners/v1`

#### Tags

- Partners
- Tenancy
- Onboarding

#### Properties

- [Documentation](https://doc.toasttab.com/openapi/partners/overview/)
- [OpenAPI](openapi/toast-tab-partners-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/toast-tab-partners.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-partners.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/partners-paginated-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/partners-partner-access-external-rep-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/partners-partner-access-external-webhook-rep-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/partners-paginated-response-structure.json)
- [JSON Structure](json-structure/partners-partner-access-external-rep-structure.json)
- [JSON Structure](json-structure/partners-partner-access-external-webhook-rep-structure.json)
- [Example](examples/partners-paginated-response-example.json)
- [Example](examples/partners-partner-access-external-rep-example.json)
- [Example](examples/partners-partner-access-external-webhook-rep-example.json)
- [J S O N- L D](json-ld/toast-tab-partners-context.jsonld)

### Toast Gift Cards Integration

Specification for integrating third-party gift-card programs with Toast — Toast calls the partner's endpoints to look up balances, authorize, redeem, and reload gift cards inline with a check.

- **Human URL:** [https://doc.toasttab.com/openapi/giftcards/overview/](https://doc.toasttab.com/openapi/giftcards/overview/)
- **Base URL:** `https://doc.toasttab.com/openapi/giftcards`

#### Tags

- Gift Cards
- Integrations
- Partners

#### Properties

- [Documentation](https://doc.toasttab.com/openapi/giftcards/overview/)
- [Postman Collection](collections/toast-tab-authentication.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-authentication.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-labor.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-labor.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-menus.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-menus.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-orders.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-orders.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-partners.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-partners.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-restaurants.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-restaurants.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-stock.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-stock.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Toast Loyalty Integration

Specification for integrating third-party loyalty programs with Toast — discovery, lookup, accrual, and redemption callbacks that Toast invokes against partner endpoints during a transaction.

- **Human URL:** [https://doc.toasttab.com/openapi/loyalty/overview/](https://doc.toasttab.com/openapi/loyalty/overview/)
- **Base URL:** `https://doc.toasttab.com/openapi/loyalty`

#### Tags

- Loyalty
- Integrations
- Partners

#### Properties

- [Documentation](https://doc.toasttab.com/openapi/loyalty/overview/)
- [Postman Collection](collections/toast-tab-authentication.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-authentication.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-labor.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-labor.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-menus.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-menus.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-orders.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-orders.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-partners.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-partners.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-restaurants.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-restaurants.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-stock.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-stock.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Toast Tender Integration

Specification for integrating alternative tender types into Toast — callback endpoints partners implement so Toast can validate, authorize, and reconcile non-card forms of payment at checkout.

- **Human URL:** [https://doc.toasttab.com/openapi/tender/overview/](https://doc.toasttab.com/openapi/tender/overview/)
- **Base URL:** `https://doc.toasttab.com/openapi/tender`

#### Tags

- Tender
- Payments
- Integrations
- Partners

#### Properties

- [Documentation](https://doc.toasttab.com/openapi/tender/overview/)
- [Postman Collection](collections/toast-tab-authentication.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-authentication.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-labor.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-labor.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-menus.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-menus.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-orders.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-orders.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-partners.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-partners.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-restaurants.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-restaurants.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/toast-tab-stock.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toast-tab-stock.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://pos.toasttab.com/)
- [Developer Portal](https://dev.toasttab.com/)
- [Documentation](https://doc.toasttab.com/)
- [API Reference](https://doc.toasttab.com/openapi/)
- [Developer Guide](https://doc.toasttab.com/doc/devguide/index.html)
- [How To Guides](https://doc.toasttab.com/doc/cookbook/index.html)
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
- [Sign Up](https://pos.toasttab.com/get-a-demo)
- [Spectral Rules](rules/toast-tab-spectral-rules.yml)
- [Vocabulary](vocabulary/toast-tab-vocabulary.yaml)
- [Plans](plans/toast-tab-plans-pricing.yml)
- [Rate Limits](rate-limits/toast-tab-rate-limits.yml)
- [Fin Ops](finops/toast-tab-finops.yml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
