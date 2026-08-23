# Awesome-Tax-Automation-Platform

# Top Tax Automation Platforms Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Sales Tax, VAT/GST Calculation, Nexus Monitoring, Returns Filing, Exemption Management & Indirect Tax Compliance*
**Last updated: August 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Tax Automation**. These tools automate tax determination, calculation, nexus tracking, returns preparation, exemption certificate management, and broader indirect tax compliance for businesses selling across multiple jurisdictions.

**Examples** include Avalara, Vertex, ONESOURCE, Sovos, Anrok, Stripe Tax, TaxJar, Blue dot, Corptax, and Canopy (the category leaders).

**Open-source emphasis**: Fully featured open-source tax automation platforms with global content and filing capabilities are limited. This section is expanded with the strongest available open-source tax calculation engines, sales-tax APIs, VAT libraries, and related projects that developers and finance teams can self-host or integrate.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[Avalara](https://www.avalara.com/)**  
  Market-leading tax automation platform covering sales tax, VAT, GST, and excise across 190+ countries, with calculation, returns, exemption certificates, and extensive integrations.

- **[Vertex](https://www.vertexinc.com/)**  
  Enterprise-grade tax determination and compliance platform used by large organizations for complex global indirect tax scenarios and multi-entity environments.

- **[Thomson Reuters ONESOURCE](https://www.thomsonreuters.com/)**  
  Comprehensive tax technology suite spanning indirect tax, corporate income tax, transfer pricing, and provision, with strong content and workflow capabilities.

- **[Sovos](https://sovos.com/)**  
  Global tax compliance platform specializing in e-invoicing, indirect tax, information reporting, and regulatory obligations across many jurisdictions.

- **[Anrok](https://www.anrok.com/)**  
  Modern tax automation platform built for SaaS and subscription businesses, focusing on sales tax/VAT calculation and compliance for digital products.

- **[Stripe Tax](https://stripe.com/tax)**  
  Tax calculation and collection product tightly integrated with Stripe payments, supporting sales tax, VAT, and GST for online businesses.

- **[TaxJar (Avalara)](https://www.taxjar.com/)**  
  Popular sales-tax automation solution (now part of Avalara) known for real-time calculation, nexus monitoring, and automated filing, especially for ecommerce.

- **[Blue dot](https://www.bluedotcorp.com/)**  
  Tax automation and compliance solutions focused on indirect tax and related processes.

- **[Corptax](https://www.corptax.com/)**  
  Corporate tax software covering provision, compliance, and related tax processes for larger organizations.

- **[Canopy](https://www.canopytax.com/)**  
  Tax practice management and automation platform used by tax professionals and firms.

## Open-Source GitHub Projects
- **[OpenTax (Filed Open Tax Engine)](https://github.com/filedcom/opentax)**  
  Fully open-source US federal tax calculation engine delivered as a single binary CLI, designed for accuracy and use by developers and AI agents.

- **[OpenSalesTax](https://github.com/ejosterberg/open-sales-tax)**  
  Open-source, self-hostable US sales tax calculation API using Streamlined Sales Tax data and per-state modules, covering all major US jurisdictions.

- **[Open Collective Taxes](https://github.com/opencollective/opencollective-taxes)**  
  Shared open-source library for calculating VAT and related taxes on events, products, and services.

- **[Taxly and similar VAT calculation APIs](https://github.com/)**  
  Open-source flexible tax calculation services supporting multi-country VAT logic, reverse charge, and different transaction types.

- **[World-tax and offline rate libraries](https://github.com/)**  
  Open libraries for calculating sales tax / VAT rates offline across multiple countries and special regimes (EU, GCC, etc.).

- **[Indirect tax automation portfolios](https://github.com/)**  
  Python and other language toolkits demonstrating VAT liability calculation, reconciliation, validation, and reporting for EMEA and similar regions.

- **[Country-specific compliance tools](https://github.com/)**  
  Open projects automating local tax obligations (e.g., VAT filing helpers, e-invoicing connectors) for specific jurisdictions.

- **[Sales tax rate data pipelines](https://github.com/)**  
  Community efforts to collect, normalize, and serve public tax rate and boundary data for calculation engines.

- **[Exemption and certificate tracking prototypes](https://github.com/)**  
  Lightweight open tools for managing tax exemption certificates and related documentation.

- **[ERPNext / Odoo tax modules](https://github.com/)**  
  Open-source ERP tax engines and localization packs that handle basic tax calculation and reporting within broader business systems.

### Additional Strong Open-Source Options
- Spreadsheet-driven tax calculators and rate lookup tools maintained by communities.
- Custom rules engines that apply jurisdiction-specific taxability logic.
- Integration examples connecting open tax engines to e-commerce or billing systems.
- Audit-trail and reporting helpers built on open data warehouses.
- AI-assisted tax research and form-filling experiments (always requiring professional review).

**Frameworks for building custom systems**: For US sales tax, deploy **OpenSalesTax** or a similar self-hosted calculation API and keep rate data updated. For VAT-heavy businesses, combine open rate libraries with custom reverse-charge and place-of-supply logic. Use open ERP tax modules for basic needs and layer official government APIs where available for filing. These approaches give full control and transparency for calculation, but production compliance (especially multi-jurisdiction returns, nexus determination, and audit defense) still typically requires commercial content, continuous updates, and professional oversight.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Tax calculation and compliance are highly regulated and jurisdiction-specific. Open-source tools can assist with determination and automation but are not substitutes for professional tax advice, official rate content, or certified filing systems. Always verify results against official sources and consult qualified tax professionals before remitting or filing.
- Rates, rules, and nexus thresholds change frequently; any self-hosted solution requires ongoing maintenance.

---
**Made for finance, tax, and engineering teams seeking transparent approaches to tax automation.**
Let's make tax calculation more open and auditable while respecting the complexity of real-world compliance.
