# Tiendanube (tiendanube)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
