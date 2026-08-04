# Carlisle Companies (carlisle)

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
