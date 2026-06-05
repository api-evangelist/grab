# Grab (grab)

Grab is Southeast Asia's leading on-demand superapp, offering
ride-hailing (GrabCar / GrabBike / GrabTaxi), food delivery
(GrabFood), package delivery (GrabExpress), grocery and retail
(GrabMart), digital payments (GrabPay), financial services
(GrabFin), and a B2B / enterprise business unit (Grab for
Business). Grab exposes a partner-grade developer platform at
developer.grab.com covering ride pricing (Farefeed), delivery
(Express, GrabFood, GrabMart), payments (GrabPay QR, One-Time
Charge, Tokenisation, Grab POS), identity (Login with Grab),
loyalty (GrabRewards / Points / GrabGifts), corporate accounts
(Grab for Business), and digital products / bill payments via
Grab Kios. The platform is OAuth 2.0 based with partner-issued
client credentials.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/grab/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/grab/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** Partner

## Tags

- Ride Hailing
- Food Delivery
- Last-Mile Logistics
- Digital Payments
- Superapp
- Southeast Asia
- Identity
- Loyalty
- QR Payments
- OAuth2

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

### Login With Grab (Grab ID) API

Grab ID is Grab's OAuth 2.0 / OpenID Connect identity provider.
Partner applications use the Login With Grab flow to authenticate
Grab consumers and obtain ID and access tokens scoped to a
specific Grab product (Pay, Rewards, etc.).

- **Human URL:** [https://developer.grab.com/docs/grab-id/](https://developer.grab.com/docs/grab-id/)
- **Base URL:** `https://api.grab.com`

#### Tags

- Identity
- OAuth2
- OpenID Connect
- Login

#### Properties

- [Documentation](https://developer.grab.com/docs/grab-id/)
- [Postman Collection](collections/grab.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/grab.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### GrabFood API

The GrabFood API lets merchant POS / SaaS partners receive,
acknowledge, and fulfill GrabFood orders, manage menus and
store status, and surface delivery status to the merchant.

- **Human URL:** [https://developer.grab.com/docs/grabfood/](https://developer.grab.com/docs/grabfood/)
- **Base URL:** `https://partner-api.grab.com`

#### Tags

- Food Delivery
- Orders
- Menus
- Stores
- POS

#### Properties

- [Documentation](https://developer.grab.com/docs/grabfood/api/v1-1-3)
- [Postman Collection](collections/grab.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/grab.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### GrabMart API

The GrabMart API supports grocery, convenience, and retail
merchants integrating with Grab's on-demand marketplace —
including catalog ingestion, store-level inventory, order
acknowledgement, and fulfillment events.

- **Human URL:** [https://developer.grab.com/docs/grabmart/](https://developer.grab.com/docs/grabmart/)
- **Base URL:** `https://partner-api.grab.com`

#### Tags

- Grocery
- Retail
- Orders
- Inventory

#### Properties

- [Documentation](https://developer.grab.com/docs/grabmart/api/v1-1-3)
- [Postman Collection](collections/grab.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/grab.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### GrabExpress API

GrabExpress is Grab's on-demand same-city courier API for
ecommerce, retail, and SaaS partners. Partners create delivery
requests, fetch quotes, track couriers in real time, and
receive webhook updates over the delivery lifecycle.

- **Human URL:** [https://developer.grab.com/docs/grab-express/](https://developer.grab.com/docs/grab-express/)
- **Base URL:** `https://partner-api.grab.com`

#### Tags

- Last-Mile
- Couriers
- Deliveries
- Tracking

#### Properties

- [Documentation](https://developer.grab.com/docs/grab-express/)
- [Postman Collection](collections/grab.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/grab.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Farefeed (Partner Ride Pricing) API

The Farefeed API exposes ride pricing and supply information
to ecosystem partners (e.g. mapping, navigation, planning
apps) so they can render Grab fare estimates inline.

- **Human URL:** [https://developer.grab.com/docs/partner-farefeed/](https://developer.grab.com/docs/partner-farefeed/)
- **Base URL:** `https://partner-api.grab.com`

#### Tags

- Pricing
- Estimates
- Mobility

#### Properties

- [Documentation](https://developer.grab.com/docs/partner-farefeed/)
- [Postman Collection](collections/grab.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/grab.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Partner Apps Integration API

Partner Apps Integration lets third-party applications surface
services inside the Grab consumer app via a partner-app
framework — covering deep links, in-app activation, and event
callbacks.

- **Human URL:** [https://developer.grab.com/docs/partner-apps/](https://developer.grab.com/docs/partner-apps/)
- **Base URL:** `https://api.grab.com`

#### Tags

- Partner Apps
- In-App
- Deep Links

#### Properties

- [Documentation](https://developer.grab.com/docs/partner-apps/)
- [Postman Collection](collections/grab.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/grab.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Grab For Business Partner API

The Grab For Business Partner API supports corporate travel,
expense, and HR platforms that need to provision corporate
Grab accounts, set ride policies, and pull employee trip and
receipt data for expense reconciliation.

- **Human URL:** [https://developer.grab.com/docs/gfb/](https://developer.grab.com/docs/gfb/)
- **Base URL:** `https://partner-api.grab.com`

#### Tags

- Corporate
- Travel
- Expense
- HR

#### Properties

- [Documentation](https://developer.grab.com/docs/gfb/)
- [Postman Collection](collections/grab.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/grab.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### GrabGifts Integration API

GrabGifts Integration enables partner platforms to issue and
redeem Grab e-gift vouchers — used for employee rewards,
customer incentives, and loyalty programs across SEA.

- **Human URL:** [https://developer.grab.com/docs/grab-gifts/](https://developer.grab.com/docs/grab-gifts/)
- **Base URL:** `https://partner-api.grab.com`

#### Tags

- Vouchers
- Gift Cards
- Rewards

#### Properties

- [Documentation](https://developer.grab.com/docs/grab-gifts/)
- [Postman Collection](collections/grab.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/grab.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### GrabDefence Risk Evaluation API

GrabDefence exposes Grab's internal fraud, abuse, and risk
evaluation platform as an API for partners — covering device
risk scoring, account integrity checks, and transaction risk
signals.

- **Human URL:** [https://developer.grab.com/docs/grab-defence/](https://developer.grab.com/docs/grab-defence/)
- **Base URL:** `https://api.grab.com`

#### Tags

- Fraud
- Risk
- Trust and Safety

#### Properties

- [Documentation](https://developer.grab.com/docs/grab-defence/)
- [Postman Collection](collections/grab.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/grab.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### GrabPay QR API

GrabPay QR exposes both merchant-presented (MPM) and
consumer-presented (CPM) QR payment flows for in-store
merchants accepting GrabPay across SEA.

- **Human URL:** [https://developer.grab.com/docs/grabpay-qr/](https://developer.grab.com/docs/grabpay-qr/)
- **Base URL:** `https://partner-api.grab.com`

#### Tags

- Payments
- QR
- Merchant
- GrabPay

#### Properties

- [Documentation](https://developer.grab.com/docs/grabpay-qr/)
- [Postman Collection](collections/grab.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/grab.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### GrabPay One-Time Charge API

The One-Time Charge API supports online merchants charging
GrabPay wallets via a redirect or app-to-app handoff
checkout flow, with payment success and failure webhook
notifications.

- **Human URL:** [https://developer.grab.com/docs/payment-otc/](https://developer.grab.com/docs/payment-otc/)
- **Base URL:** `https://partner-api.grab.com`

#### Tags

- Payments
- Checkout
- GrabPay
- Webhooks

#### Properties

- [Documentation](https://developer.grab.com/docs/payment-otc/api/v2)
- [Postman Collection](collections/grab.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/grab.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### GrabPay Tokenisation API

Tokenisation lets partner merchants store a customer's GrabPay
payment instrument as a reusable token for recurring and
one-click checkouts, with PCI-scope reduction.

- **Human URL:** [https://developer.grab.com/docs/tokenisation-v4/](https://developer.grab.com/docs/tokenisation-v4/)
- **Base URL:** `https://partner-api.grab.com`

#### Tags

- Tokenisation
- Recurring
- GrabPay

#### Properties

- [Documentation](https://developer.grab.com/docs/tokenisation-v4/)
- [Postman Collection](collections/grab.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/grab.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Grab POS API

The Grab POS API integrates physical point-of-sale terminals
with GrabPay for in-store payment acceptance, including
transaction lifecycle, refund, and reconciliation flows.

- **Human URL:** [https://developer.grab.com/docs/pos-api-v3/](https://developer.grab.com/docs/pos-api-v3/)
- **Base URL:** `https://partner-api.grab.com`

#### Tags

- POS
- In-Store
- Payments
- GrabPay

#### Properties

- [Documentation](https://developer.grab.com/docs/pos-api-v3/)
- [Postman Collection](collections/grab.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/grab.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### GrabRewards (Points Earning & Tier) APIs

The Points Earning and GrabRewards Tier APIs let ecosystem
partners award GrabRewards points for qualifying activity and
check a user's loyalty tier for tier-based offers.

- **Human URL:** [https://developer.grab.com/](https://developer.grab.com/)
- **Base URL:** `https://partner-api.grab.com`

#### Tags

- Loyalty
- Rewards
- Points

#### Properties

- [Documentation](https://developer.grab.com/)
- [Postman Collection](collections/grab.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/grab.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Grab Kios Digital Products API

Grab Kios Digital Products API powers digital-goods commerce
for Grab Kios agents in Indonesia — covering top-ups for
mobile credit, data packages, gaming credits, and digital
vouchers.

- **Human URL:** [https://developer.grab.com/docs/grab-kios-digital-products-api/](https://developer.grab.com/docs/grab-kios-digital-products-api/)
- **Base URL:** `https://partner-api.grab.com`

#### Tags

- Digital Goods
- Top-Up
- Indonesia
- Kios

#### Properties

- [Documentation](https://developer.grab.com/docs/grab-kios-digital-products-api/)
- [Postman Collection](collections/grab.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/grab.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Grab Kios Biller Gateway API

The Biller Gateway API lets Grab Kios agents accept bill
payments for electricity, water, multifinance, and other
Indonesian billers, with inquiry, payment, and reversal
operations.

- **Human URL:** [https://developer.grab.com/docs/grab-kios-biller-gateway-api/](https://developer.grab.com/docs/grab-kios-biller-gateway-api/)
- **Base URL:** `https://partner-api.grab.com`

#### Tags

- Bill Payment
- Indonesia
- Kios

#### Properties

- [Documentation](https://developer.grab.com/docs/grab-kios-biller-gateway-api/)
- [Postman Collection](collections/grab.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/grab.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.grab.com/)
- [Developer Portal](https://developer.grab.com/)
- [Documentation](https://developer.grab.com/docs)
- [Grab Pay](https://www.grab.com/sg/pay/)
- [Grab For Business](https://business.grab.com/)
- [Newsroom](https://www.grab.com/sg/press/)
- [Sustainability](https://www.grab.com/sg/sustainability/)
- [Investor Relations](https://investors.grab.com/)
- [Careers](https://grab.careers/)
- [Git Hub](https://github.com/grab)
- [LinkedIn](https://www.linkedin.com/company/grabapp/)
- [L L Ms Txt](https://developer.grab.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
