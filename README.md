# US Foods

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
