# Awesome-Environmental-Social-Governance-ESG-Trackers

## Top Environmental Social Governance (ESG) Trackers Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Carbon Accounting, Regulatory Reporting & Supply Chain ESG*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Environmental, Social & Governance (ESG) Trackers**. These tools enable organizations to calculate carbon footprints, track ESG metrics, manage supplier data, and produce audit-ready disclosures aligned with CSRD, ISSB, and SEC climate rules.



**Examples** include Watershed, Persefoni, Novata, Sweep, Workiva, Sphera, Measurabl, Diligent ESG, Sustainalytics, and EcoVadis (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, ISO 14064-1 inventories, and open carbon accounting — ideal for sustainability teams, developers, and organizations seeking transparent, vendor-independent ESG infrastructure.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Watershed](https://watershed.com/)**  

  End-to-end carbon accounting and reduction platform for companies. Features Scope 1/2/3 measurement, supplier data collection, CSRD/ISSB reporting, and clean energy procurement.



- **[Persefoni](https://persefoni.com/)**  

  AI-native carbon accounting and sustainability management platform. Features Scope 1/2/3 measurement, **Persefoni Copilot** (GPT-style chat for carbon accounting expertise), anomaly detection for statistical outliers, natural language emission factor mapping (coming soon), PCAF-compliant financed emissions, and Sustainability Report Builder (CSRD, ISSB, CDP) . Freemium with ADVANCED tier requiring custom quote .



- **[Novata](https://www.novata.com/)**  

  ESG data management platform designed for private markets. Features carbon accounting, ESG metrics tracking, and regulatory reporting for portfolio companies.



- **[Sweep](https://www.sweep.net/)**  

  Carbon and ESG data management platform. Features Scope 1/2/3 tracking, supplier engagement, CSRD reporting, and decarbonization planning.



- **[Workiva](https://www.workiva.com/)**  

  Enterprise reporting platform with **Sustainability Cloud (Workiva Carbon)** addressing EU CSRD and U.S. SEC climate requirements . Features audit trails, data lineage, connected reports, and XBRL tagging . Often builds on existing financial workflows since governance and controls principles overlap . Best for companies needing one platform for both SEC financial and ESG filings.



- **[Sphera](https://sphera.com/)**  

  Enterprise sustainability, operational risk, EHS, and life-cycle assessment platform. Features configurable calculation logic with **auditable traceability** for inventory reviews, ERP/procurement integrations, and workflow controls for review/approval across departments . Strong governance needs for maintaining factor libraries and boundary settings. Best for large, industrial, or product-intensive organizations combining sustainability with EHS and supply-chain risk .



- **[Measurabl](https://www.measurabl.com/)**  

  Real estate industry's most widely adopted ESG platform for collecting, analyzing, and reporting building-level data. Features **Cohort Insights** drawing from a database of nearly **13 billion square feet** of commercial real estate for peer benchmarking . Automates utility data consolidation, API integration with GRESB, Energy Star, and USGBC. Role-based permissions for site managers. Best for real estate portfolios requiring building-level ESG tracking .



- **[Diligent ESG](https://www.diligent.com/)**  

  Governance, risk, and compliance platform with ESG reporting capabilities. Features board-level oversight tools and regulatory disclosure management.



- **[Sustainalytics](https://www.sustainalytics.com/)**  

  ESG research and ratings provider. Features company ESG risk ratings, controversy analysis, and portfolio screening.



- **[EcoVadis](https://ecovadis.com/)**  

  Sustainability ratings for global supply chains. Features supplier ESG assessments, scorecards, and improvement tracking.



## Open-Source GitHub Projects



- **[CarbonInk](https://github.com/lxzxl/carbonink)**  

  **Free, open-source, local-first GHG carbon accounting for the desktop** (MIT). Import your bills, let AI extract activity data, and produce an **ISO 14064-1 inventory report** — entirely on your own machine. **No account, no cloud, no subscription.** Features Scope 1/2/3 tracking with audit-grade calculation snapshots, AI extraction from utility bills/fuel receipts/freight/travel, questionnaires for customer/rating-agency disclosures and supplier Scope 3 Cat 1 data collection, one-click PDF report generation, and **MCP server** exposing inventory to Claude/Cursor/Pi. macOS + Windows. **Your data never leaves your device.** The most accessible open-source carbon accounting tool available .



- **[OpenGHG Carbon Calculator](https://github.com/mindsongreen/OpenGHG)**  

  **Open-source, transparent carbon footprint calculator** designed for robust, auditable, and methodology-driven carbon inventories. Key principles: **separation of data domains** (activity data, emission factors, conversions, parameters), **federated database architecture** allowing customer-hosted sensitive data, **explicit unit and pair-of-units algebra**, **no black-box calculations**, and **full traceability from input to results**. Backend: PHP/PostgreSQL with federated databases. **Mapping decisions remain under user responsibility** — the calculator guides through reliable calculations once mapping is done. Functional updates twice per year (June/December). The most methodology-transparent open-source carbon calculator .



- **[Equinox](https://github.com/open-risk/equinox)**  

  **Open-source platform for sustainable portfolio management** (Apache-2.0) supporting holistic risk management and reporting of sustainable finance projects. Features: **Data Center Environmental impact reporting**, Green Public Procurement portfolio management, **Energy Accounting with Scope 2 accounting and reporting**, GHG Accounting Protocol for Projects, **PCAF coalition approaches for mortgage portfolio and project finance GHG emissions**, Equator Principles for Project Finance, and EBA Criteria for Credit Risk Assessment of Project Finance. Python/Django with sqlite for easy installation. Running instance at Sustainability.Town. **The most comprehensive open-source sustainable finance platform** .



- **[ESG Data Tracker](https://github.com/kritinkaul/automated-esg-tracker)**  

  Open-source ESG data tracker with **real data sources** (News API for ESG news, Alpha Vantage for financial data, AI sentiment analysis, Supabase database). Features professional project structure with Streamlit dashboard, error handling, and logging. **No mock data — live news articles, real company information, real financial metrics**. Quick start via interactive menu, quick start script, or direct dashboard. **The most accessible open-source ESG news and sentiment tracker** .



- **[Carmen (GitLab)](https://github.com/Green-Software-Foundation/if-carmen)**  

  Open-source **Carbon Measurement Engine** for cloud infrastructure and applications (draft software from Green Software Foundation). Measures carbon emissions from: **Infrastructure** (energy consumption and emissions from VMs and cloud workloads using VM usage data in CSV), and **Application** (emissions from individual workloads and pods running in Kubernetes, using Prometheus metrics). Outputs CSV reports for Grafana, FinOps dashboards, or custom tooling. Python 3.12 with CI/CD integration. **Note**: Draft software — not approved for corporate ESG reporting or compliance disclosures. The most focused open-source tool for cloud carbon measurement .



- **[Moja Global FLINT](https://moja.global/)**  

  **Open-source Full Lands Integration Tool (FLINT)** for land sector carbon accounting, operating under the Linux Foundation. Software brings together data and models in a coherent flexible manner — integrates spatial and aspatial data without losing information, manages huge volumes of data. **Data agnostic**, scalable and supports nesting, ensures comparability of indices. Implementations include: **GCBM** (Canada, Yucatan, Mexico at 1ha resolution for 50M ha), **INCAS** (Indonesia), **SLEEK** (Kenya), and **FLINTpro** (global application for 40+ countries). **Commercial-grade open source** with users on the Strategy Board controlling strategy and budget. **The most comprehensive open-source land sector carbon accounting platform** .



### Additional Strong Open-Source Options



- **[OS-Climate](https://os-climate.org/)** — Open-source platform for climate risk analysis and scenario modeling. Features physical risk, transition risk, and portfolio climate alignment. Free (open-source) .

- **[GHG Protocol Calculation Tools](https://ghgprotocol.org/)** — Free Excel-based tools for calculating Scope 1, 2, and 3 emissions across sectors. The foundational standard for corporate carbon footprinting .

- **[Climatiq API](https://www.climatiq.io/)** — Open API for carbon emission calculations with global emission factor database .

- **[Community Carbon Accounting Projects](https://github.com/brandonhimpfen/awesome-carbon-accounting-offsets)** — Curated list of tools, frameworks, datasets, standards, platforms, and projects for carbon accounting, offsetting, and sustainability tracking .

- Community **n8n** workflows for ESG data collection automation and supplier engagement.



**Frameworks for building custom systems**: Combine **CarbonInk** for local-first ISO 14064-1 inventories with **OpenGHG** for methodology-transparent calculations, **Equinox** for sustainable finance portfolio management, **Carmen** for cloud carbon measurement, and **PostgreSQL** for persistence — creating a fully self-hosted, enterprise-grade ESG tracking platform.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- ESG tracking systems handling sustainability data must comply with reporting regulations (CSRD, ISSB, SEC climate rules, GHG Protocol, ISO 14064) and data protection requirements.

- **Open-source ESG tracking is emerging but incomplete for enterprise compliance.** CarbonInk provides ISO 14064-1 inventories . OpenGHG provides methodology transparency . Equinox provides sustainable finance portfolio management . **No single open-source tool provides the end-to-end CSRD/ISSB disclosure workflow of Workiva or Persefoni.** Integration with assurance providers and reporting specialists remains necessary.

- **The "raw bill audit" capability varies significantly.** CarbonInk extracts activity data from utility bills via AI . Measurabl automates utility data consolidation . **Document parsing quality determines inventory accuracy** — a critical differentiator between tools.

- **Methodology transparency is the open-source advantage.** OpenGHG's "no black-box calculations" principle with full traceability from input to results  provides auditability that commercial platforms claim but rarely expose. This matters for assurance cycles where auditors must verify calculation logic.

- **Assurance consultants remain essential.** A system holding evidence per figure and keeping previously published values retrievable turns an assurance cycle from reconstruction into review . Open-source tools provide the evidence layer; professional judgment and sign-off remain human responsibilities.

- Self-hosted open-source solutions require proper security hardening, emission factor validation, and ongoing maintenance. Carbon accounting outputs require external assurance before regulatory submission.



---



**Made for sustainability teams, ESG analysts, compliance officers, and developers building transparent ESG tracking solutions.**  

Let's make ESG Trackers more open, data-driven, and auditable.
