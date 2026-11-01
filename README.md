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

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **CrowdStrike Falcon OverWatch Elite**

  **Elite managed threat hunting** with dedicated hunters and adversary intelligence. **Pricing**: **License per endpoint/server** for OverWatch; **Elite tier requires Falcon Adversary Intelligence Premium**—custom quote required; no public pricing . **Free tier**: None. **Best for**: enterprises wanting the most mature human-led hunting with adversary intelligence—**trade-off**: premium pricing; requires existing Falcon investment.



- **Mandiant Managed Defense**

  **Frontline MDR** from incident response experts. **Pricing**: **CDW-G lists $53.86 per license** (likely per-endpoint/month or similar unit) . Third-party estimates place average Mandiant software cost at **~$83,000/year** . **Free tier**: None. **Best for**: organizations wanting intelligence-driven hunting grounded in real breach response—**trade-off**: premium pricing excludes SMBs; IR retainer separate.



- **SentinelOne Vigilance Respond Pro**

  **MDR with DFIR** and incident response retainer hours. **Pricing**: **CDW listed $17,115.99** for a subscription upgrade license (discontinued June 2026); Singularity Platform Pro listed at **$26,413.99** . **Free tier**: None. **Best for**: SentinelOne customers wanting MDR with forensic analysis—**trade-off**: product discontinuation suggests portfolio changes; verify current offering.



- **Red Canary**

  **MDR with threat hunting** across endpoint, identity, and cloud. **Pricing**: **Core (single domain)**: AWS Marketplace **$120/endpoint, $100/user account, $250/cloud resource** for 12 months. **Complete (multi-domain)**: includes Copilot, API, exporter. **Enterprise**: adds dedicated support and threat hunter collaboration. Negotiated pricing for 1,000 endpoints: **~$35,000–$50,000/year** . **Free tier**: None. **Best for**: mid-market teams wanting modular MDR with strong threat hunting—**trade-off**: identity/cloud require Complete tier; dedicated hunter access requires Enterprise.



- **Rapid7 Managed Threat Complete**

  **MDR with exposure management included**. **Pricing**: **Based on endpoints, servers, and networks protected**—not data volume or incidents . AppDirect lists **starting from $5.86/year** (likely per-unit) . Quote-only for full scope. **Free tier**: None. **Best for**: teams wanting MDR with built-in risk reduction—**trade-off**: pricing requires scoping call; add-ons extra.



- **Arctic Wolf**

  **Managed detection and response** with concierge security. **Pricing**: **Small deployments (50–250 endpoints)**: **$30,000–$75,000/year**; **Mid-market (250–1,000)**: **$75,000–$200,000/year** . Implementation fees **$5,000–$25,000+**; annual escalation **3–7%** . **Free tier**: None. **Best for**: mid-market teams wanting comprehensive MDR with security awareness training—**trade-off**: hidden costs (implementation, retention, true-ups); multi-year required for best pricing.



- **Secureworks Counter Threat Unit (Taegis ManagedXDR)**

  **MDR with proprietary countermeasures**. **Pricing**: Public procurement record shows **Taegis XDR and ManagedXDR at $42.41/unit** for 600 units (**$25,446**) and combined **$93,678** for 1,200 units . **Free tier**: None. **Best for**: network-focused teams wanting managed IPS with CTU countermeasures—**trade-off**: quote-only for most; public sector pricing visible.



- **Kroll Cyber Threat Hunting**

  **MDR with threat intelligence** and flexible deployment. **Pricing**: Quote-only; no public pricing. Optiv Leadership Compass notes **rapid and flexible deployment**, **strong threat intelligence**, but **OOTB integrations with only five third-party SIEMs** . **Free tier**: None. **Best for**: teams wanting flexible MDR with strong intelligence—**trade-off**: limited SIEM integrations; no cloud posture management.



- **eSentire Threat Hunting**

  **MDR with multi-surface coverage**. **Pricing**: **Small (50–200 assets)**: **$50,000–$150,000/year**; **Mid-market (200–1,000)**: **$150,000–$500,000/year**; **Enterprise (1,000+)**: **$500,000+** . Negotiated discounts **15–25%** common. **Free tier**: None. **Best for**: teams wanting multi-surface MDR with incident response—**trade-off**: asset-based pricing; overage fees for growth.



- **Group-IB Managed XDR**

  **Platform-native Managed XDR** with threat intelligence. **Pricing**: **Quote-only**; no public unit price; AWS Marketplace custom/private offer . Requires deploying **Group-IB's own sensors**—cannot run on competing EDR. **Free tier**: None. **Best for**: teams wanting threat-intelligence-native MDR—**trade-off**: sensor lock-in; IR retainer separate; no identity/OT coverage.



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
