# Awesome-Tax-Automation-Platform

## Top Tax Automation Platforms Ecosystem

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

| Platform | Description | Starting Pricing | Free Tier / Trial Limit |
| :--- | :--- | :--- | :--- |
| **[Avalara](https://www.avalara.com/)** | Market-leading tax automation platform covering sales tax, VAT, GST, and excise across 190+ countries, with calculation, returns, exemption certificates, and extensive integrations. | Starts at **$799/state/year** (Core Compliance, 3-state minimum = ~$2,397/yr); basic services starting at ~$119/license | **90-day free developer trial** (API/SDK testing capped at 1,000 transactions/day, 5 req/min, no credit card required; no free live filing tier) |
| **[Vertex](https://www.vertexinc.com/)** | Enterprise-grade tax determination and compliance platform used by large organizations for complex global indirect tax scenarios and multi-entity environments. | Starts at **~$5,000/year** for SMB Cloud connectors; enterprise multi-entity deployments scale from $10,000–$100,000+/year | **No free-forever tier**; guided sandbox pilot/demo available upon enterprise sales request |
| **[Thomson Reuters ONESOURCE](https://www.thomsonreuters.com/)** | Comprehensive tax technology suite spanning indirect tax, corporate income tax, transfer pricing, and provision, with strong content and workflow capabilities. | Starts at **~$10,000/year** (base modular packages for indirect/direct tax and reporting) | **No free-forever tier**; 30-day limited trial available for select modules upon sales evaluation |
| **[Sovos](https://sovos.com/)** | Global tax compliance platform specializing in e-invoicing, indirect tax, information reporting, and regulatory obligations across many jurisdictions. | Starts at **~$3,000/year** (base indirect tax and 1099 reporting tiers) | **No free-forever tier**; 7-day sandbox trial on select modules/APIs upon sales consultation |
| **[Anrok](https://www.anrok.com/)** | Modern tax automation platform built for SaaS and subscription businesses, focusing on sales tax/VAT calculation and compliance for digital products. | Starts at **$499/month** ($5,988/year billed annually) + 0.30%–0.40% per taxable transaction (Starter tier) | **No free-forever tier**; 7-day trial available via select marketplace/partner integrations |
| **[Stripe Tax](https://stripe.com/tax)** | Tax calculation and collection product tightly integrated with Stripe payments, supporting sales tax, VAT, and GST for online businesses. | **0.5% per transaction** (no-code/Checkout) or **$0.50/transaction** (API); **0.4% per transaction** with Stripe Billing (no monthly minimums) | **Free-forever Test Mode** with unlimited sandbox calculations + 100% free automated economic nexus and threshold monitoring across all jurisdictions |
| **[TaxJar (Avalara)](https://www.taxjar.com/)** | Popular sales-tax automation solution (now part of Avalara) known for real-time calculation, nexus monitoring, and automated filing, especially for ecommerce. | Starts at **$39/month** (Starter tier, up to 200 orders/month, 3 integrations, 2 AutoFile credits/yr); Professional from $99/month | **30-day free trial** (up to 200 orders, full access to integrations and nexus dashboard, no credit card required) |
| **[Blue dot](https://www.bluedotcorp.com/)** | Tax automation and compliance solutions focused on AI-driven indirect tax, taxable employee benefits, and VAT recovery. | Starts at **~$15,000/year** (based on employee expense volume and ERP/SAP Concur connectors) | **No free-forever tier**; custom proof-of-concept (POC) sandbox trial upon enterprise sales evaluation |
| **[Corptax](https://www.corptax.com/)** | Corporate tax software covering provision, compliance, and related tax processes for larger organizations. | Starts at **~$80,000/year** (average enterprise deployment for corporate tax provision & compliance modules) | **No free-forever tier**; guided sandbox demonstration and proof-of-concept on request via sales team |
| **[Canopy](https://www.canopytax.com/)** | Tax practice management and automation platform used by tax professionals and accounting firms. | Starts at **$74/user/month** (Standard plan billed annually) / $109/user/month (Plus plan) | **Free-forever tier** for Client Management (up to 500 contacts, includes client portal & mobile app); **14-day free trial** for full practice management features |



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
