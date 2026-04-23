# Carlisle Companies (carlisle)
Carlisle Companies Incorporated (NYSE: CSL) is a global diversified manufacturer of highly engineered building envelope products and solutions, serving commercial and residential construction, insulation, roofing, waterproofing, and specialty markets. Carlisle's primary operating segment is Carlisle Construction Materials (CCM), which includes brands such as Carlisle SynTec Systems, Hunter Panels, Henry Company, MB Technology, and WIP Industrial. Carlisle does not publish a public developer API; distributors and direct contractors transact through the Carlisle Customer Success Portal, and commercial trading partners integrate with Carlisle using standard X12 EDI transactions (850, 855, 856, 810) over AS2/SFTP.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/carlisle/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **x-type:** company
- **Position:** Consumer
- **Access:** Partner

## Tags

- Building Envelope
- Building Products
- Construction
- Contractor Portal
- Distributors
- EDI
- Insulation
- Manufacturing
- Roofing
- Waterproofing

## Overview

Carlisle historically operated across diverse industrial segments but in recent years divested its non-core businesses to focus on the building envelope, making CCM the dominant segment. Distributors and roofing contractors transact with Carlisle through the Customer Success Portal (customersuccesslogin.com), which consolidates SKU-level product data, net pricing, real-time order status, and transactional documents across all CCM roofing brands. Upstream supply-chain partners and national-account retailers integrate via X12 EDI - typically 850/855/856/810 - over AS2 or SFTP, onboarded through Carlisle's trading-partner team.

## APIs

### Carlisle Customer Success Portal
The Carlisle Customer Success Portal is the primary digital channel for Carlisle Construction Materials distributors and direct contractor customers across the continental United States and Canada. It covers all commercial roofing brands under CCM and exposes web-based access to SKU-level product information, net pricing, order status, invoices, confirmations, shipping notices, and packing lists. The portal is accessed at customersuccesslogin.com or through individual brand sites and is gated by contractor or distributor credentials.

**Human URL:** [https://customersuccesslogin.com](https://customersuccesslogin.com)

#### Features

- SKU catalog with descriptions, images, and UOM
- Customer-specific net pricing
- Real-time open-order tracking and ship dates
- Order history across CCM brands
- Invoice, order confirmation, ASN, and packing list retrieval
- Covers all CCM commercial roofing brands
- Available in the continental US and Canada

#### Use Cases

- Distributor self-service order management
- Direct contractor pricing and order tracking
- Accounting team invoice retrieval and reconciliation
- Project-level material status for roofing contractors

### Carlisle EDI Trading Partner Integration
Carlisle Construction Materials and Carlisle's other operating segments exchange purchase orders, acknowledgments, advance ship notices, and invoices with distributors, retailers, and large contractors via X12 EDI. Typical transaction set usage includes 850 Purchase Order, 855 PO Acknowledgment, 856 Advance Ship Notice, and 810 Invoice over AS2 or SFTP, provisioned through Carlisle trading partner onboarding.

**Human URL:** [https://www.carlisle.com/our-businesses/default.aspx](https://www.carlisle.com/our-businesses/default.aspx)

#### Features

- X12 EDI 850, 855, 856, 810 transactions
- AS2 and SFTP connectivity
- Distributor, retailer, and national account onboarding
- Trading-partner-specific mapping and conformance testing

#### Use Cases

- Distributor replenishment automation
- National retailer purchase order flow
- Advance ship notice to WMS systems
- Invoice ingestion into AP automation platforms

## Common Properties

- [Website](https://www.carlisle.com/)
- [Businesses](https://www.carlisle.com/our-businesses/default.aspx)
- [Construction Materials](https://www.carlisleconstructionmaterials.com/)
- [SynTec Systems](https://www.carlislesyntec.com/)
- [Investor Relations](https://ir.carlisle.com/)
- [Careers](https://careers.carlisle.com/)
- [Contact](https://www.carlisle.com/contact-us/default.aspx)
- [Privacy Policy](https://www.carlisle.com/privacy-policy/default.aspx)
- [Terms of Use](https://www.carlisle.com/terms-of-use/default.aspx)
- [LinkedIn](https://www.linkedin.com/company/carlisle-companies-incorporated/)

## Timestamps

- **Created:** 2026-03-23
- **Modified:** 2026-04-23

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
