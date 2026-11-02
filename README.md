# Awesome-Dedicated-Threat-Hunting-Services

# Awesome-Dedicated-Threat-Hunting-Services

**Top Dedicated Threat Hunting Services (Opensource) 🌟 Star if you like it! 🌟**



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Managed Threat Hunting, 24/7 SOC Coverage, Adversary-Focused Detection & Self-Hosted Hunting Infrastructure*

**Last updated: November 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Dedicated Threat Hunting Services**. These services and tools enable organizations to augment their security operations with human-led threat hunting, 24/7 monitoring, and proactive adversary detection—from fully managed MDR and elite hunting teams to open-source hunting platforms that give teams complete control over their telemetry and hunt logic.



**Examples** include CrowdStrike Falcon OverWatch Elite, Mandiant Managed Defense, SentinelOne Vigilance Respond Pro, Red Canary, Rapid7 Managed Threat Complete, Arctic Wolf, Secureworks Counter Threat Unit, Kroll, eSentire, and Group-IB (the category leaders in commercial space).



**Open-source emphasis**: This section is expanded with every relevant project for self-hosted threat hunting, detection engineering, and open SOC infrastructure. **Critical note**: Open-source projects cannot replace human threat hunters—but they provide the telemetry, detection rules, and hunting workbenches that make human hunting possible. **Velociraptor** provides endpoint interrogation at scale, **Sigma** delivers portable detection rules, and **MISP** handles intelligence sharing. No open-source project matches CrowdStrike OverWatch's human expertise and global telemetry, but for building an internal hunting capability, the foundational tools are mature.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)



## Sector Overview & Market Dynamics

The global dedicated threat hunting and Managed Detection & Response (MDR) market is estimated at **$4.6B–$5.7B** for specialized threat hunting solutions and **$6.2B–$11.2B** when encompassing broader MDR platforms in 2026, compounding at an annual growth rate (CAGR) of **15% to 23%**. Rather than a winner-take-all monopoly, the sector remains **moderately to highly fragmented** and fiercely competitive, split among platform EDR giants (CrowdStrike, SentinelOne), pure-play concierge MDR providers (Arctic Wolf, eSentire), global incident response consultancies (Mandiant/Google Cloud, Kroll), and regional SOC service providers catering to diverse enterprise toolchains and local data-sovereignty mandates.



## SaaS/Hosted Platforms

| Platform / Service | Company Size (Valuation / Revenue) | Pricing | Free Tier / Trial Limit | Key Focus & Trade-offs |
| :--- | :--- | :--- | :--- | :--- |
| **CrowdStrike Falcon OverWatch Elite** | **~$80B–$95B Market Cap** (NASDAQ: CRWD; ~$4B+ ARR) | Starting at **$59.99/endpoint/year** (Falcon Pro entry base) up to **$180–$250+/endpoint/year** with OverWatch managed hunting & threat intel modules; custom enterprise contracts | **15-day free trial** of Falcon platform (no credit card required; OverWatch human hunting evaluation via sales PoC) | Elite managed threat hunting with proprietary telemetry. *Trade-off*: Premium pricing; Elite hunting tier requires existing Falcon agent and Falcon Adversary Intelligence Premium. |
| **SentinelOne Vigilance Respond Pro** | **~$8.5B Market Cap** (NYSE: S; ~$700M+ ARR) | Starting at **$45–$60/endpoint/year** (Singularity Core base) up to **$17,115.99/bundle** (Singularity Platform Pro / Vigilance upgrade tier per CDW listings) | **30-to-90-day PoC evaluation** with dedicated sales engineering support (no permanent free tier) | MDR with DFIR and incident response retainer hours. *Trade-off*: Vigilance Respond Pro SKU evolution/transition into Singularity MDR tiers; verify active licensing bundle. |
| **Mandiant Managed Defense** | **$5.4B Valuation** (Acquired by Alphabet / Google Cloud; parent market cap ~$2.1T) | Starting at **$53.86/license/year** (CDW-G procurement listing per endpoint); average enterprise deployments track at **~$83,000/year** | **No free trial for Managed Defense** (14-day free trial available for standalone Mandiant Threat Intelligence; 30-day trial for Attack Surface Management) | Frontline MDR directly backed by frontline Google/Mandiant breach investigators. *Trade-off*: Strict enterprise focus and pricing model excludes SMBs; full IR retainers billed separately. |
| **Arctic Wolf Managed Detection & Response** | **$4.3B Valuation** (Series F / pre-IPO funding) | Starting at **$30,000–$75,000/year** for small deployments (50–250 endpoints) up to **$75,000–$200,000/year** for mid-market (250–1,000 endpoints) | **No free trial for core MDR** (complimentary access to Cyber JumpStart risk posture portal & security training modules; demo/PoC via sales) | Turnkey Concierge Security Team model with continuous posture assessments. *Trade-off*: Hidden deployment costs ($5,000–$25,000+ onboarding fee, 3–7% annual escalation, log retention add-ons). |
| **Kroll Cyber Threat Hunting** | **~$1.3B–$1.5B Revenue** (Stone Point Capital / CD&R private equity) | Starting at **$12,000–$25,000/year** base retainer up to **$60,000–$150,000+/year** for continuous threat hunting; quote-based | **No free trial** (enterprise consultation, demo walkthrough, and scoped pilot assessment upon request) | Flexible MDR paired with elite digital forensics and threat intelligence. *Trade-off*: Out-of-the-box integrations limited to primary SIEM stacks; no native CSPM. |
| **eSentire Threat Hunting** | **$1.0B Valuation** (Series E unicorn status; $100M+ ARR) | Starting at **$50,000–$150,000/year** for small environments (50–200 assets); **$150,000–$500,000/year** for mid-market (200–1,000 assets) | **30-day free trial of Atlas SecOps Platform** (trial deployment of AI/Atlas platform; full human SOC MDR requires scoped PoC) | 24/7 multi-surface response (endpoint, cloud, network, log). *Trade-off*: Asset-based scaling creates overage charges; onboarding fees apply. |
| **Rapid7 Managed Threat Complete** | **~$870M Market Cap** (NASDAQ: RPD; ~$800M ARR) | Starting at **$5.86/asset/month** (AppDirect listing for basic coverage) or **~$108/asset/year**; full Managed Threat Complete scopes at **$35,000–$80,000/year** | **30-day free trial of InsightIDR software** (no free trial for Managed Threat Complete human SOC service; custom PoC available) | Blends MDR with vulnerability and exposure management in one agent. *Trade-off*: Multi-surface telemetry requires full Insight platform buy-in; add-ons increase price. |
| **Secureworks Taegis ManagedXDR (Sophos)** | **$859M Valuation** (Acquired by Sophos / Thoma Bravo in 2025; public procurement: $42.41/unit) | Starting at **$42.41/endpoint/year** (public procurement price schedule for 600+ seats; $25,446 total minimum) | **14-day free trial of Taegis XDR** (limited to max 200 endpoint agents and up to 3 users; 30-day PoC via Azure/AWS Marketplace) | Threat hunting bolstered by proprietary Counter Threat Unit (CTU) research. *Trade-off*: Quote-only for commercial enterprise tiers; requires Taegis agent migration. |
| **Red Canary** | **$675M Valuation** (Acquired by Zscaler in 2025) | Starting at **$120/endpoint/year**, **$100/identity user/year**, and **$250/cloud resource/year** (AWS Marketplace Core tier); 1,000 endpoints negotiate at **$35,000–$50,000/year** | **No public free trial** (discretionary proof-of-value sandbox evaluation arranged directly via sales) | MDR with premier threat hunting across endpoint, identity, and cloud. *Trade-off*: Identity and cloud require Complete tier; dedicated threat hunter collaboration restricted to Enterprise tier. |
| **Group-IB Managed XDR** | **~$30M–$50M Revenue** (Privately held, HQ Singapore) | Starting at **$30–$45/endpoint/year** (estimated minimum $15,000/year platform baseline; quote-based via AWS Marketplace private offers) | **No free trial for Managed XDR** (free community Malware Reports database & demo on request; 14-day trials occasionally granted for Attack Surface Management) | Native adversary intelligence and deep telemetry tracking APT groups. *Trade-off*: Sensor lock-in (must run Group-IB proprietary agents, cannot hunt on 3rd-party EDR); IR retainer separate. |




## Open-Source GitHub Projects



- **Velociraptor**

  **Endpoint visibility and digital forensics platform** (Apache 2.0) — **the leading open-source tool for endpoint threat hunting at scale**. **Features**: **VQL (Velociraptor Query Language)** for interrogating endpoints; **real-time monitoring**; **hunts across thousands of endpoints**; artifact collection for DFIR; client-side caching for offline endpoints. **Tech stack**: Go. **Deploy**: Self-hosted server + agents. **Trade-off**: **Requires VQL expertise**—powerful but steep learning curve; you write hunts and analyze results. **Best for**: DFIR and threat hunting teams wanting deep endpoint interrogation without commercial EDR licensing—the closest open-source analog to a hunting platform.



- **Sigma**

  **Generic signature format for SIEM systems** (Detection Rule License) — **the de facto standard for vendor-agnostic detection rules**, enabling hunters to write once and deploy across SIEMs. **Features**: Hundreds of community-contributed detection rules covering MITRE ATT&CK techniques; conversion tools (sigmac, pySigma) for Splunk, Elastic, QRadar, and more. **Tech stack**: YAML rules, Python tooling. **Deploy**: Rules deployed to your SIEM via conversion. **Trade-off**: **Rules, not a platform**—Sigma provides detection content but no execution engine, no telemetry collection. **Best for**: detection engineers wanting portable, community-maintained rules to operationalize in any SIEM.



- **MISP**

  **Open Source Threat Intelligence Platform** (AGPL-3.0) — **the most widely deployed open-source intelligence sharing platform** for IOC management and community collaboration. **Features**: IOC management and correlation; sharing communities; taxonomies and galaxies; STIX/TAXII support; MISP Workflows for automation. **Tech stack**: PHP, MySQL. **Deploy**: Self-hosted. **Trade-off**: **Sharing platform, not a hunting workbench**—it stores and shares intelligence but does not execute hunts. **Best for**: teams wanting to consume and share threat intelligence as input to hunting—the intelligence layer that feeds hunt hypotheses.



### Additional Strong Open-Source Options



- **TheHive (legacy)** — Case management platform (AGPL-3.0 for v3/v4). **Note**: **No longer maintained**—latest version commercially licensed. **Do not adopt for new deployments.** **Best for**: historical reference only.

- **Cortex** — Observable analysis and active response (license per repo). Enriches indicators with multiple analyzers. **Best for**: enriching IOCs during hunting investigations.



**Frameworks for building custom systems**: Combine **Velociraptor** for endpoint hunting with **Sigma** for detection rules and **MISP** for intelligence input—creating a composable internal hunting stack. **None of these replace human hunters or match CrowdStrike OverWatch's global telemetry**, but for teams building an internal hunting capability, the foundational tools are mature.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, license (for open-source), and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Threat hunting services handle sensitive security telemetry and incident data. Ensure your use complies with data protection regulations (GDPR, CCPA, etc.) and your organization's security policies.

- **The "managed threat hunting service" vs. "MDR" vs. "self-hosted hunting platform" distinction is critical.** **CrowdStrike OverWatch Elite, Mandiant Managed Defense, SentinelOne Vigilance Respond Pro, Red Canary, Rapid7, Arctic Wolf, Secureworks, Kroll, eSentire, and Group-IB** are **managed services**—they provide human hunters, global telemetry, and often response actions . **Velociraptor** is a **hunting platform**—it provides endpoint interrogation but requires your own hunters . **Sigma** is **detection content**—rules, not execution . **MISP** is **intelligence sharing**—input to hunting, not hunting itself . **Choose based on whether you need managed expertise, internal tooling, or intelligence input.**

- **CrowdStrike OverWatch Elite requires Falcon Adversary Intelligence Premium** and is custom-quoted—no public pricing . **For organizations already on Falcon, it is the most integrated hunting option; for others, the barrier is high.**

- **Mandiant Managed Defense is enterprise-only.** Third-party estimates place costs at **~$83,000/year**, excluding SMBs and budget-constrained organizations . **CDW-G lists $53.86 per license**—verify the billing unit (likely per-endpoint) before budgeting .

- **SentinelOne Vigilance Respond Pro was discontinued June 12, 2026** according to CDW . **Verify current SentinelOne MDR offerings before evaluating.**

- **Red Canary's modular pricing is a strength and a trap.** Core covers one domain (e.g., endpoint) at **$120/endpoint/year** on AWS Marketplace; Complete adds identity and cloud; Enterprise adds **dedicated threat hunter collaboration** . **Dedicated hunter access is Enterprise-only—do not assume it is included in lower tiers.**

- **Arctic Wolf and eSentire both have significant hidden costs.** Arctic Wolf: **$5,000–$25,000+ implementation**, **$500–$3,000+/month extended retention**, **3–7% annual escalation** . eSentire: onboarding fees, add-on modules, **3–7% escalation**, overage fees for asset growth . **Negotiate expansion pricing and escalation caps upfront.**

- **Group-IB requires deploying its own sensors**—it cannot run on competing EDR . **This is a significant lock-in factor if you have existing endpoint investments.**

- **Kroll has limited SIEM integrations**—only five OOTB third-party SIEMs per Optiv . **If you have a non-standard SIEM, validate integration support before committing.**

- **Velociraptor is the most powerful open-source hunting tool** but requires VQL expertise and self-hosted infrastructure . **Sigma provides the detection content that makes hunting repeatable** . **MISP feeds the intelligence that drives hunt hypotheses** . **Together they form the foundation of an internal hunting program.**

- **Pricing opacity is universal** across CrowdStrike, Mandiant, SentinelOne, Red Canary, Rapid7, Arctic Wolf, Secureworks, Kroll, eSentire, and Group-IB. All require sales contact or quote requests. **Validate with direct vendor conversations against your endpoint count and hunting requirements.**

- Self-hosted open-source solutions require proper infrastructure (servers for Velociraptor, SIEM for Sigma deployment, PHP/MySQL for MISP), security hardening, and ongoing maintenance. **Hunting platforms have deep visibility into endpoints and networks**—ensure your deployment meets your organization's security standards before deploying agents.



---



**Made for SOC teams, threat hunters, and organizations building transparent threat hunting solutions.**

Let's make Dedicated Threat Hunting Services more open, data-driven, and adversary-aware.
