# 1inch (one-inch)

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

1inch is the leading DEX aggregator. The 1inch Developer Portal exposes 13+ APIs covering Swap (classic, Fusion intent, cross-chain), Orderbook, Balance, Spot Price, Token, Token Details, Portfolio, Gas Price, NFT, Traces, History, Transaction Gateway, Web3 RPC, Charts, and Domains. APIs serve 12+ EVM chains. Authentication via Authorization Bearer header.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/one-inch/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/one-inch/refs/heads/main/apis.yml)

## Tags

- Web3
- DeFi
- DEX
- Aggregator
- Swap
- Multi-chain
- Limit Orders
- Fusion
- Cross-chain

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## APIs

### 1inch Swap API

Quote and swap endpoints supporting classic aggregation, Fusion intent-based swaps, and cross-chain (Fusion+).

- **Human URL:** [https://business.1inch.com/portal/documentation/swap-api](https://business.1inch.com/portal/documentation/swap-api)
- **Base URL:** `https://api.1inch.dev/swap/v6.0`

#### Tags

- Swap
- Aggregator
- Fusion
- Cross-chain

#### Properties

- [Documentation](https://business.1inch.com/portal/documentation/swap-api)
- [Postman Collection](collections/one-inch.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/one-inch.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### 1inch Orderbook API

Limit-order placement, query, fill, and cancellation endpoints.

- **Human URL:** [https://business.1inch.com/portal/documentation/orderbook-api](https://business.1inch.com/portal/documentation/orderbook-api)
- **Base URL:** `https://api.1inch.dev/orderbook/v4.0`

#### Tags

- Limit Orders
- Orderbook

#### Properties

- [Documentation](https://business.1inch.com/portal/documentation/orderbook-api)
- [Postman Collection](collections/one-inch.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/one-inch.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### 1inch Balance API

Wallet balance lookup across supported EVM chains.

- **Human URL:** [https://business.1inch.com/portal/documentation/balance-api](https://business.1inch.com/portal/documentation/balance-api)
- **Base URL:** `https://api.1inch.dev/balance/v1.2`

#### Tags

- Balances
- Wallet

#### Properties

- [Documentation](https://business.1inch.com/portal/documentation/balance-api)
- [Postman Collection](collections/one-inch.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/one-inch.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### 1inch Spot Price API

On-chain spot price feeds for tokens across supported EVM chains.

- **Human URL:** [https://business.1inch.com/portal/documentation/spot-price-api](https://business.1inch.com/portal/documentation/spot-price-api)
- **Base URL:** `https://api.1inch.dev/price/v1.1`

#### Tags

- Prices
- Spot

#### Properties

- [Documentation](https://business.1inch.com/portal/documentation/spot-price-api)
- [Postman Collection](collections/one-inch.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/one-inch.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### 1inch Token API

Token metadata and discovery endpoints.

- **Human URL:** [https://business.1inch.com/portal/documentation/token-api](https://business.1inch.com/portal/documentation/token-api)
- **Base URL:** `https://api.1inch.dev/token/v1.2`

#### Tags

- Tokens
- Metadata

#### Properties

- [Documentation](https://business.1inch.com/portal/documentation/token-api)
- [Postman Collection](collections/one-inch.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/one-inch.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### 1inch Portfolio API

Portfolio composition, P&L, and historical valuation across supported networks.

- **Human URL:** [https://business.1inch.com/portal/documentation/portfolio-api](https://business.1inch.com/portal/documentation/portfolio-api)
- **Base URL:** `https://api.1inch.dev/portfolio/portfolio/v4`

#### Tags

- Portfolio
- Wallet

#### Properties

- [Documentation](https://business.1inch.com/portal/documentation/portfolio-api)
- [Postman Collection](collections/one-inch.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/one-inch.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### 1inch Gas Price API

Gas price estimates for EIP-1559 across supported EVM chains.

- **Human URL:** [https://business.1inch.com/portal/documentation/gas-price-api](https://business.1inch.com/portal/documentation/gas-price-api)
- **Base URL:** `https://api.1inch.dev/gas-price/v1.5`

#### Tags

- Gas
- Estimation

#### Properties

- [Documentation](https://business.1inch.com/portal/documentation/gas-price-api)
- [Postman Collection](collections/one-inch.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/one-inch.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/1inch)
- [Portal](https://business.1inch.com/)
- [Documentation](https://business.1inch.com/portal/documentation/overview)
- [Pricing](https://business.1inch.com/pricing)
- [Git Hub](https://github.com/1inch)
- [Plans](plans/one-inch-plans-pricing.yml)
- [Rate Limits](rate-limits/one-inch-rate-limits.yml)
- [Fin Ops](finops/one-inch-finops.yml)
- [L L Ms Txt](https://1inch.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
