# Tiendanube (tiendanube)

Tiendanube (branded Nuvemshop in Brazil) is the leading e-commerce platform for small and medium-sized businesses across Latin America. Its REST API lets partner applications manage a merchant's store data - products, variants, categories, orders, customers, coupons, webhooks, scripts, fulfillment orders, and payment/shipping providers - using OAuth 2.0 and a per-store authentication token.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/tiendanube/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/tiendanube/refs/heads/main/apis.yml)

## Tags

- E-commerce
- Retail
- Latin America
- Storefront
- Products
- Orders

## Timestamps

- **Created:** 2026-07-01
- **Modified:** 2026-07-01

## APIs

### Tiendanube Products API

Create, read, update, and delete products in a merchant's catalog, including titles, descriptions, SEO fields, pricing, brand, and publish state.

- **Human URL:** [https://tiendanube.github.io/api-documentation/resources/product](https://tiendanube.github.io/api-documentation/resources/product)
- **Base URL:** `https://api.tiendanube.com/v1/{store_id}`

#### Tags

- Products
- Catalog
- Inventory

#### Properties

- [Documentation](https://tiendanube.github.io/api-documentation/resources/product)
- [API Reference](https://tiendanube.github.io/api-documentation/resources/product)
- [OpenAPI](openapi/tiendanube-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tiendanube.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tiendanube.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tiendanube Product Variants API

Manage per-product variants (SKUs) with price, promotional price, stock, weight, dimensions, and variant-level values, plus attach and order product images.

- **Human URL:** [https://tiendanube.github.io/api-documentation/resources/product_variant](https://tiendanube.github.io/api-documentation/resources/product_variant)
- **Base URL:** `https://api.tiendanube.com/v1/{store_id}`

#### Tags

- Variants
- SKU
- Images

#### Properties

- [Documentation](https://tiendanube.github.io/api-documentation/resources/product_variant)
- [API Reference](https://tiendanube.github.io/api-documentation/resources/product_image)
- [OpenAPI](openapi/tiendanube-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tiendanube.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tiendanube.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tiendanube Categories API

Organize a storefront's catalog into a hierarchical tree of categories with parent/child relationships, subcategories, and localized names and descriptions.

- **Human URL:** [https://tiendanube.github.io/api-documentation/resources/category](https://tiendanube.github.io/api-documentation/resources/category)
- **Base URL:** `https://api.tiendanube.com/v1/{store_id}`

#### Tags

- Categories
- Taxonomy
- Merchandising

#### Properties

- [Documentation](https://tiendanube.github.io/api-documentation/resources/category)
- [OpenAPI](openapi/tiendanube-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tiendanube.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tiendanube.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tiendanube Orders API

List and retrieve orders with line items, customer, shipping and billing addresses, and payment status; open, close, cancel, and pack orders.

- **Human URL:** [https://tiendanube.github.io/api-documentation/resources/order](https://tiendanube.github.io/api-documentation/resources/order)
- **Base URL:** `https://api.tiendanube.com/v1/{store_id}`

#### Tags

- Orders
- Checkout
- Transactions

#### Properties

- [Documentation](https://tiendanube.github.io/api-documentation/resources/order)
- [OpenAPI](openapi/tiendanube-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tiendanube.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tiendanube.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tiendanube Customers API

Create and manage store customers, their contact details, default addresses, and order history for CRM and marketing integrations.

- **Human URL:** [https://tiendanube.github.io/api-documentation/resources/customer](https://tiendanube.github.io/api-documentation/resources/customer)
- **Base URL:** `https://api.tiendanube.com/v1/{store_id}`

#### Tags

- Customers
- CRM
- Contacts

#### Properties

- [Documentation](https://tiendanube.github.io/api-documentation/resources/customer)
- [OpenAPI](openapi/tiendanube-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tiendanube.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tiendanube.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tiendanube Coupons API

Create percentage, fixed-amount, absolute, and shipping discount coupons with usage limits, validity windows, and minimum-price conditions.

- **Human URL:** [https://tiendanube.github.io/api-documentation/resources/coupon](https://tiendanube.github.io/api-documentation/resources/coupon)
- **Base URL:** `https://api.tiendanube.com/v1/{store_id}`

#### Tags

- Coupons
- Discounts
- Promotions

#### Properties

- [Documentation](https://tiendanube.github.io/api-documentation/resources/coupon)
- [OpenAPI](openapi/tiendanube-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tiendanube.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tiendanube.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tiendanube Webhooks API

Subscribe to store events (order/created, product/updated, app/uninstalled, and more) delivered as HMAC-signed POST callbacks to an app's configured URL.

- **Human URL:** [https://tiendanube.github.io/api-documentation/resources/webhook](https://tiendanube.github.io/api-documentation/resources/webhook)
- **Base URL:** `https://api.tiendanube.com/v1/{store_id}`

#### Tags

- Webhooks
- Events
- Notifications

#### Properties

- [Documentation](https://tiendanube.github.io/api-documentation/resources/webhook)
- [OpenAPI](openapi/tiendanube-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tiendanube.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tiendanube.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tiendanube Scripts API

Register JavaScript scripts that an app injects into the storefront or checkout, scoped by event and location, for analytics, chat, and conversion tooling.

- **Human URL:** [https://tiendanube.github.io/api-documentation/resources/script](https://tiendanube.github.io/api-documentation/resources/script)
- **Base URL:** `https://api.tiendanube.com/v1/{store_id}`

#### Tags

- Scripts
- Storefront
- Injection

#### Properties

- [Documentation](https://tiendanube.github.io/api-documentation/resources/script)
- [OpenAPI](openapi/tiendanube-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tiendanube.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tiendanube.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tiendanube Fulfillment Orders API

Manage the fulfillment of order line items - assignments, tracking, and status - for logistics and 3PL integrations, alongside draft orders.

- **Human URL:** [https://tiendanube.github.io/api-documentation/resources/fulfillment_order](https://tiendanube.github.io/api-documentation/resources/fulfillment_order)
- **Base URL:** `https://api.tiendanube.com/v1/{store_id}`

#### Tags

- Fulfillment
- Shipping
- Logistics

#### Properties

- [Documentation](https://tiendanube.github.io/api-documentation/resources/fulfillment_order)
- [OpenAPI](openapi/tiendanube-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tiendanube.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tiendanube.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tiendanube Payment and Shipping Providers API

Register and manage third-party payment providers and shipping carriers - including checkout options, rates, and transactions - so apps can offer native payment and shipping at checkout.

- **Human URL:** [https://tiendanube.github.io/api-documentation/resources/payment_provider](https://tiendanube.github.io/api-documentation/resources/payment_provider)
- **Base URL:** `https://api.tiendanube.com/v1/{store_id}`

#### Tags

- Payment Providers
- Shipping Carriers
- Checkout

#### Properties

- [Documentation](https://tiendanube.github.io/api-documentation/resources/payment_provider)
- [API Reference](https://tiendanube.github.io/api-documentation/resources/shipping_carrier)
- [OpenAPI](openapi/tiendanube-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tiendanube.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tiendanube.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/TiendaNube)
- [LinkedIn](https://www.linkedin.com/company/tiendanube)
- [Website](https://www.tiendanube.com/)
- [Documentation](https://tiendanube.github.io/api-documentation/)
- [Plans](plans/tiendanube-plans-pricing.yml)
- [Rate Limits](rate-limits/tiendanube-rate-limits.yml)
- [Fin Ops](finops/tiendanube-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
