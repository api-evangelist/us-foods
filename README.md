# US Foods

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

US Foods is one of the largest foodservice distributors in the United States, serving restaurants, healthcare facilities, hospitality businesses, government institutions, and educational facilities. As a Fortune 500 company, US Foods operates a national distribution network with over 70 distribution centers and serves approximately 250,000 customers. The company's digital platform includes the MOXe eCommerce application for ordering and business management, EDI integration for B2B transactions, and a supplier PIM system for product data synchronization.

**URL:** [https://www.usfoods.com](https://www.usfoods.com)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

`Food Service` `Fortune 500` `Distribution` `Supply Chain` `eCommerce`

## Timestamps

- **Created:** 2026-03-21
- **Modified:** 2026-05-03

## APIs and Integrations

| Integration | Type | Description |
|-------------|------|-------------|
| [MOXe eCommerce Platform](https://www.usfoods.com/our-services/easy-ordering.html) | Portal | Customer ordering, inventory management, bill pay, menu analytics |
| [US Foods EDI Integration](https://www.cleo.com/trading-partner-network/us-foods) | EDI | B2B integration for purchase orders, invoices, and ASNs |
| [Supplier PIM System](https://www.usfoods.com/supplier-info.html) | Data Sync | GS1 GDSN product data synchronization for suppliers |

**Note:** US Foods does not currently publish a public REST API. Integration is primarily through EDI transactions (850/855/856/810) and the GS1 GDSN product data synchronization network. Customer ordering is via the MOXe platform at order.usfoods.com.

## JSON Schema

| Schema | Description |
|--------|-------------|
| [Order Schema](json-schema/us-foods-order-schema.json) | Schema for US Foods foodservice orders |
| [Product Schema](json-schema/us-foods-product-schema.json) | Schema for US Foods catalog product items |

## JSON Structure

| Structure | Description |
|-----------|-------------|
| [Order Structure](json-structure/us-foods-order-structure.json) | Field documentation for US Foods orders |

## JSON-LD

| Context | Description |
|---------|-------------|
| [US Foods Context](json-ld/us-foods-context.jsonld) | Linked data context mapping US Foods terms to schema.org and GS1 |

## Examples

| Example | Description |
|---------|-------------|
| [Order Example](examples/us-foods-order-example.json) | Example foodservice order structure |

## Vocabulary

| Vocabulary | Description |
|------------|-------------|
| [US Foods Vocabulary](vocabulary/us-foods-vocabulary.yml) | Domain vocabulary for foodservice distribution |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
