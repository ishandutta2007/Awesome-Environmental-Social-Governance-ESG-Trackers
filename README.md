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

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## Sector Overview & Market Dynamics

The global ESG reporting and carbon management software market is estimated at approximately **$1.3B to $2.5B** (projected to reach over **$5.6B by 2030**, growing at a CAGR of ~20%–26%), driven by mandatory disclosure mandates such as EU CSRD, ISSB standards, and SEC climate rules. The market remains **moderately fragmented**—while enterprise GRC and established giants (Workiva, Diligent, Sphera) command heavy compliance market share, no single player dominates, leaving substantial room for vertical-specific and fast-growing climate accounting specialists (Watershed, Persefoni, Measurabl).

## SaaS/Hosted Platforms

| Platform | Company Size (Valuation / Revenue) | Starting Tier Pricing | Free Tier / Trial Limits | Description & Key Strengths |
| :--- | :--- | :--- | :--- | :--- |
| **[Diligent ESG](https://www.diligent.com/)** | ~$7.0B valuation (~$350M+ ARR) | ~$5,000/year (base tier; ~$23,800–$45,000/year typical deployment; ~£700/seat/year) | No free plan; custom proof-of-concept / sales-assisted trial only (feature & seat caps set per evaluation) | Enterprise GRC & ESG platform with board-level oversight and regulatory disclosure management. |
| **[Workiva](https://www.workiva.com/)** | ~$4.0B market cap (~$965M TTM revenue) | ~$25,000/year (modular starting tier; ~$59,000/year average contract) | No free plan; no self-serve free trial (guided product demos only) | Enterprise reporting platform with **Sustainability Cloud (Workiva Carbon)** for EU CSRD and SEC compliance with XBRL tagging. |
| **[Sphera](https://sphera.com/)** | ~$3.0B valuation (~$300M+ revenue) | ~€329/user/year (Sphera BOMcheck base; ~$40,000/year entry enterprise suite) | No permanent free plan; 45-day free trial for *LCA for Experts* (read-only BOMcheck Manufacturer tier) | Enterprise sustainability, EHS, operational risk, and life-cycle assessment platform with auditable calculation logic. |
| **[Watershed](https://watershed.com/)** | $1.8B valuation (Series C) | ~$37,000/year (entry annual subscription; typical deployments ~$50,000–$70,000+/year) | No free plan; no time-bounded self-serve free trial (custom pilots/demos; free Open CEDA emission database access) | End-to-end carbon accounting and reduction platform covering Scope 1/2/3, supplier data, and clean power procurement. |
| **[EcoVadis](https://ecovadis.com/)** | $1.0B valuation (~$160M–$500M estimated revenue) | ~€500–€1,500/year (Basic Plan for suppliers < €25M revenue) | Up to 6-week free questionnaire completion window (scorecard evaluation & submission requires paid annual plan) | Global supply chain sustainability ratings, supplier ESG assessments, and improvement tracking across 150k+ entities. |
| **[Measurabl](https://www.measurabl.com/)** | $433M valuation (~$36M–$42M ARR) | $15–$25/building/month (Reporter / Standard paid tiers; ~$180–$300/building/year) | Free-forever basic tier (unlimited duration; centralized utility metrics & benchmarks; framework reporting gated) | Real estate ESG platform collecting and benchmarking building-level energy, water, carbon, and waste metrics. |
| **[Persefoni](https://persefoni.com/)** | $300M valuation (~$4M–$25M ARR) | $55,000/year (Advanced enterprise tier starting contract) | Free-forever plan (*Persefoni Pro*): 1 user seat, full Scope 1/2/3 calculations, limited to standard factors & no custom export packs | AI-native carbon accounting platform with Persefoni Copilot, anomaly detection, PCAF financed emissions, and CSRD reporting. |
| **[Novata](https://www.novata.com/)** | ~$100M–$250M valuation (~$19M ARR) | $20,000/year (*Manage* tier) | Promotional Free Carbon Trial (limited feature set and transactional limits; full suite requires demo/contract) | ESG data management platform for private markets, tracking carbon and ESG metrics for portfolio companies (up to 10 facilities/100 suppliers on base tier). |
| **[Sustainalytics](https://www.sustainalytics.com/)** | ~$185M acquisition value (~$79M+ revenue at acquisition, now Morningstar) | ~$5,000–$10,000+/year (entry portfolio licensing / API data feeds) | No free commercial API tier; limited free company ESG risk summary lookups on public web directory | Institutional ESG research, corporate risk ratings, controversy screening, and sustainable finance data. |
| **[Sweep](https://www.sweep.net/)** | ~$100M+ total funding raised (Series B) | ~$254/month (entry base edition; comprehensive enterprise contracts quote-based) | No self-serve free trial (guided demo & custom evaluation sandboxes only) | Carbon and ESG data management platform for Scope 1/2/3 tracking, supplier engagement, and CSRD compliance. |



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
