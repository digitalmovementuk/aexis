# AEXIS — Market & Competitive Research Dossier

*Grounding research for the AEXIS business plan. Every material figure is sourced. Where sources disagree (different scope/methodology/currency), the range is shown rather than a single number. Forward-looking estimates and any number used in the financial model are flagged as **[ASSUMPTION]** and are not presented as fact.*

**Prepared:** June 2026 · **Scope:** Germany · United Kingdom · Singapore · **Segment focus:** Regulated mid-market (financial services, healthcare, critical infrastructure)

---

## 1. The thesis — why now

The trigger for this venture is a structural change in the cyber threat surface caused by frontier AI, not a marketing narrative. The evidence:

### 1.1 AI has crossed the offensive-capability threshold
- **Anthropic "Mythos" preview (April 2026)** documented an AI model that autonomously discovered **thousands of high- and critical-severity vulnerabilities** across operating systems, browsers and cryptographic libraries — including a **27-year-old OpenBSD TCP SACK bug** and a **16-year-old FFmpeg H.264 flaw that "had evaded every fuzzer and human who has reviewed the code."** It autonomously **chained four vulnerabilities** into a working browser exploit that escaped both renderer and OS sandboxes, and wrote remote-code-execution exploits granting *"full root access to unauthenticated users."* Crucially: **N-day exploitation (turning a known-but-unpatched flaw into a working attack) now happens "in hours that expert penetration testers said would have taken weeks."** Anthropic's own conclusion: *"the transitional period may be tumultuous regardless"* — attackers may hold a temporary advantage as capable models proliferate. ([red.anthropic.com/2026/mythos-preview](https://red.anthropic.com/2026/mythos-preview/))
- **First confirmed agentic-AI espionage operation (Anthropic, November 2025):** AI was used across the *entire* attack lifecycle — reconnaissance, exploitation, exfiltration — against major technology companies and government agencies. A follow-up analysis of **832 banned malicious accounts (March 2025 – March 2026)** shows AI-enabled cyber-offence is now an operational reality, not a lab demo. ([startuphub.ai](https://www.startuphub.ai/ai-news/artificial-intelligence/2026/ai-escalates-cyber-threats-in-2026))

### 1.2 The criminal ecosystem is industrialising AI fast
- **Flashpoint:** a **1,500% rise in AI-related illicit discussions** between Nov and Dec 2025 (362,000 → 6M+ mentions); **11.1M machines infected with infostealers in 2025**, producing an inventory of **3.3 billion compromised credentials and cloud tokens.** ([startuphub.ai](https://www.startuphub.ai/ai-news/artificial-intelligence/2026/ai-escalates-cyber-threats-in-2026))
- **2026 Global Threat Intelligence reporting** (HS Today, Check Point, Barracuda, LevelBlue, WEF) converges on one message: **agentic AI is a 2026 "threat multiplier"** — autonomous attack chains automate reconnaissance, phishing generation, credential testing and infrastructure rotation **without direct human control.** Check Point's framing: *"AI attacks are no longer experimental."* ([Check Point](https://blog.checkpoint.com/research/ai-attacks-are-no-longer-experimental-key-findings-from-the-march-april-2026-ai-threat-landscape/) · [Barracuda](https://blog.barracuda.com/2026/02/27/agentic-ai--the-2026-threat-multiplier-reshaping-cyberattacks) · [WEF Global Cybersecurity Outlook 2026](https://www.weforum.org/publications/global-cybersecurity-outlook-2026/in-full/3-the-trends-reshaping-cybersecurity/))

### 1.3 Defenders are not ready — and know it
- **IBM Cost of a Data Breach 2025:** global average breach cost **USD 4.44M**. The kicker for our thesis: **97% of organisations that suffered an AI-related security incident lacked proper AI access controls**, and **63% had no AI governance policy at all.** Shadow AI added **+USD 670,000** per breach; conversely, extensive AI/automation in defence **saved USD 1.9M** and cut the breach lifecycle by 80 days. The gap between AI-attack capability and AI-defence maturity is the wedge. ([IBM](https://www.ibm.com/reports/data-breach) · [Help Net Security](https://www.helpnetsecurity.com/2025/08/04/ibm-cost-data-breach-report-2025/))
- **UK Cyber Security Breaches Survey 2025/26:** **only ~24%** of organisations using/adopting/considering AI have security practices to manage the associated risks — *"AI adoption is beginning to outpace security readiness."* Only **25%** of businesses have a formal incident-response plan; only **15%** review the cyber risk of their immediate suppliers. ([GOV.UK](https://www.gov.uk/government/statistics/cyber-security-breaches-survey-20252026/cyber-security-breaches-survey-20252026))

**Synthesis:** offensive AI capability is compounding monthly; defensive maturity, governance and skilled headcount are not. That divergence is the market AEXIS is built to serve — and regulation (Section 3) is converting it from "should fix" to "must fix, by law."

---

## 2. Market sizing (TAM / SAM / SOM)

### 2.1 Total cyber-security market by country (TAM inputs)

| Market | Headline size | Growth | Source(s) |
|---|---|---|---|
| **Germany** | **€12.2bn** IT-security spend forecast for 2026 (+9.9%); was €11.1bn in 2024 (+10.1%). Broader-scope estimates: **USD 15.55bn (2026)** rising to **USD 20.61bn by 2030**. | Double-digit, sustained | [Bitkom/PAC](https://silicon-saxony.de/en/bitkom-german-market-for-it-security-sees-double-digit-growth/) · [GTAI](https://www.gtai.de/en/invest/industries/digital-economy/german-cybersecurity-continues-double-digit-growth-1935730) · [MarketsandMarkets](https://www.marketsandmarkets.com/PressReleases/germany-cybersecurity.asp) |
| **United Kingdom** | Dedicated UK cyber sector: **£14.7bn revenue, £9.1bn GVA, ~70,000 employed, 2,603 firms (+20% YoY)** (DSIT). Broader-scope: **USD 18.36bn (2026) → USD 30.19bn (2031), 10.46% CAGR.** | ~10% CAGR | [DSIT Sectoral Analysis 2026](https://www.gov.uk/government/publications/cyber-security-sectoral-analysis-2026/cyber-security-sectoral-analysis-2026) · [Mordor](https://www.mordorintelligence.com/industry-reports/uk-cybersecurity-market) |
| **Singapore** | **USD 2.65bn (2025) → USD 3.07bn (2026)**, on a path to **USD 5.60bn by 2030 (16.14% CAGR)** — fastest-growing of the three. | ~16% CAGR | [Mordor](https://www.mordorintelligence.com/industry-reports/singapore-cybersecurity-market) · [Research & Markets](https://www.researchandmarkets.com/reports/5937806/singapore-cybersecurity-market-share-analysis) |

**Combined TAM (3 markets, total cyber spend):** **≈ €30–33bn (2026)**, growing low-double-digit. *(EUR-equivalent; UK £14.7bn ≈ €17bn, SG USD 3.07bn ≈ €2.8bn, DE €12.2bn. **[ASSUMPTION]** on FX ≈ GBP 1.17, USD 0.92.)*

### 2.2 SAM — what AEXIS actually sells
AEXIS does **not** sell the whole cyber market (no hardware, no commodity AV, no SOC-in-a-box for the Fortune 100). The serviceable market is **AI-threat assurance + managed security + compliance services for the regulated mid-market (≈250–5,000 employees)** in the three countries.

- Security **services** (advisory, testing, MDR, compliance) are typically **~35–45%** of total cyber spend (the rest is product/licences/hardware). **[ASSUMPTION]**
- The **regulated mid-market** is roughly **25–30%** of that services spend (large enterprise and micro-SME excluded). **[ASSUMPTION]**
- ⇒ **SAM ≈ €30bn × 40% × 30% ≈ €3.6–4.8bn.** We carry **€4.5bn** as the working SAM, with sensitivity shown in the model.

### 2.3 SOM — realistic obtainable share
- 3-year revenue target **€9.0M** ⇒ **≈ 0.2% of SAM** — deliberately conservative; this is a sales-execution story, not a market-share-fantasy story.
- 5-year line of sight **€25–30M** ⇒ **≈ 0.6% of SAM.** Penetration this low de-risks the top-down sizing: AEXIS does not need the market to grow to hit plan; it needs to win a few hundred mid-market accounts.

---

## 3. Regulation — the forcing function (the "why pay, why now")

Regulation is what turns AI-threat anxiety into **board-mandated, budgeted, deadline-driven** spend. All three markets have just moved.

### 3.1 Germany / EU
- **NIS2 (German implementation, NIS2UmsuCG / new BSIG):** **in force 6 December 2025, with no transition period.** Scope expands the number of regulated entities **from ~4,500 to ~30,000** — anyone with **>€10M turnover OR ≥50 employees** in covered sectors. **Fines up to €10M or 2% of global turnover**, plus **personal liability for management** and **mandatory recurring management cyber-risk training.** Registration with the BSI was due **6 March 2026.** ([Reed Smith](https://www.reedsmith.com/articles/germany-implements-nis2-immediate-effect-broad-scope-near-term-registration/) · [Greenberg Traurig](https://www.gtlaw.com/en/insights/2025/12/nis2-in-germany-the-new-bsi-act-makes-cybersecurity-a-board-level-issue) · [Morrison Foerster](https://www.mofo.com/resources/insights/251208-flipping-the-nis2-switch-what-germanys-implementation))
- **DORA (Digital Operational Resilience Act):** **enforceable since 17 January 2025**, covering **20 types of financial entity + their ICT third parties.** Requires ICT risk management, **digital operational resilience testing**, major-incident reporting within hours, third-party risk management, and an EU oversight regime for critical ICT providers. **Fines up to 10% of annual turnover / €10M; senior managers personally liable up to €1M.** ([ESMA](https://www.esma.europa.eu/esmas-activities/digital-finance-and-innovation/digital-operational-resilience-act-dora) · [Mayer Brown](https://www.mayerbrown.com/en/insights/publications/2025/01/cybersecurity-in-the-financial-sector-eus-digital-operational-resilience-act-takes-effect))

### 3.2 United Kingdom
- **Cyber Security and Resilience (NIS) Bill:** introduced **12 Nov 2025**, second reading **6 Jan 2026**, committee stage **Feb 2026.** Critically, it **brings medium/large Managed Service Providers ("RMSPs") and data centres into scope for the first time**, overseen by the Information Commission (the future ICO). Firms providing IT management, help-desk and security services become directly regulated. ([Commons Library](https://commonslibrary.parliament.uk/research-briefings/cbp-10442/) · [Clifford Chance](https://www.cliffordchance.com/insights/resources/blogs/talking-tech/en/articles/2025/11/cyber-security-and-resilience--network-and-information-systems--.html) · [Industrial Cyber](https://industrialcyber.co/regulation-standards-and-compliance/uk-cyber-resilience-bill-extends-oversight-to-ot-suppliers-and-managed-service-providers-raises-security-baseline/))
- *Strategic note:* the Bill regulating MSPs is a **double-edged sword** — AEXIS, as a security service provider, must itself be exemplary/accredited; that bar is a moat against under-qualified competitors and a trust signal to buyers.

### 3.3 Singapore
- **Cybersecurity (Amendment) Act 2024:** passed May 2024, key provisions **in force 31 Oct 2025.** Expands obligations on **Critical Information Infrastructure** owners (responsible even when using cloud), introduces **Systems of Temporary Cybersecurity Concern (STCC)**, **Entities of Special Cybersecurity Interest (ESCI)** and **Foundational Digital Infrastructure (FDI)** categories, and mandates **incident reporting to CSA within 2 hours** for APT-suspected or essential-service-disrupting incidents. ([Hogan Lovells](https://www.hoganlovells.com/en/publications/provisions-in-singapores-cybersecurity-amendment-act-came-into-force-on-31-october-2025) · [Allen & Gledhill](https://www.allenandgledhill.com/sg/perspectives/articles/31414/sgkh-amendments-to-cybersecurity-act-2018-to-update-provisions-related-to-critical-information-infrastructure-and-systems-of-temporary-cybersecurity-concern-in-force-on-31-october-2025))
- **MAS Technology Risk Management:** TRM Guidelines (Jan 2021) plus the **TRM Notice and Cyber Hygiene Notice (both effective 10 May 2024)** impose binding controls on financial institutions. MAS is an active enforcer — **163 enforcement actions, S$4.4M financial + S$7.16M civil penalties (Jul 2023–Dec 2024).** ([MAS](https://www.mas.gov.sg/regulation/guidelines/technology-risk-management-guidelines) · [Tripwire](https://www.tripwire.com/state-of-security/mas-compliance-key-regulations-financial-institutions-singapore))

**Synthesis:** in all three markets, within the last 18 months, cyber resilience has become a **board-level, personally-liable, deadline-bound legal obligation for exactly our target segment** — finance, healthcare and critical infrastructure in the mid-market. This is the rare case where the regulatory clock and the technology shock fire at the same time.

---

## 4. Demand-side evidence (corporate & SME reaction)

### 4.1 Germany — the damage is now existential
- **Bitkom "Wirtschaftsschutz 2025":** total damage to the German economy **€289.2bn (+8% YoY)**; **cyber-attacks' share rose to 70% = €202.4bn** (from €178.6bn). **87% of companies** report data/IT theft, espionage or sabotage; **34% hit by ransomware** (nearly 3× the 12% of 2022); **59% say cyber-attacks threaten their existence**; Russia and China each implicated by 46% of affected firms. ([Bitkom](https://www.bitkom.org/Bitkom/Publikationen/Wirtschaftsschutz) · [BfV](https://www.verfassungsschutz.de/SharedDocs/kurzmeldungen/DE/2025/2025-09-18-studie-bitkom.html))
- The German *Mittelstand* is uniquely exposed: high-value IP, deep supply chains, historically under-invested in security, now swept into NIS2 scope.

### 4.2 United Kingdom — breached, but unprepared
- **UK Cyber Security Breaches Survey 2025/26:** **43% of businesses** breached in the last 12 months (~**612,000 businesses**); **phishing hits 38%**, with **AI impersonation going mainstream.** Year-on-year, revenue/share-value loss rose **2%→5%** and reputational damage **1%→3%.** Readiness gaps: only **24%** of AI-adopters manage AI risk, **25%** have an incident-response plan, **15%** review supplier risk. ([GOV.UK](https://www.gov.uk/government/statistics/cyber-security-breaches-survey-20252026/cyber-security-breaches-survey-20252026) · [NCC Group](https://www.nccgroup.com/newsroom/news-reaction-uk-cyber-security-breaches-survey-20252026-shows-persistent-risk-and-gaps-in-readiness/))

### 4.3 The structural enabler: the skills gap
- **ISC2 2025 Workforce Study:** record **4.8M unfilled cyber roles globally (+19% YoY)**; **88% of organisations report skills gaps** on their security teams and **88% suffered a significant security consequence** because of them. For the **first time, budget/economic pressure overtook talent scarcity** as the top staffing constraint — meaning buyers increasingly **cannot afford to build in-house and will buy outcome-based services instead.** Europe carries ~4M of the gap and faces extra pressure from GDPR + NIS2. ([ISC2](https://www.isc2.org/Insights/2025/12/2025-ISC2-Cybersecurity-Workforce-Study) · [digital4business](https://digital4business.eu/cybersecurity-skills-crisis-europe/))

**Synthesis:** demand is not a hypothesis. Companies are being breached, the damage is existential, regulation now compels action, and **they structurally cannot hire their way out** — the textbook setup for an outcome-based, productised security service.

---

## 5. Competitive landscape

### 5.1 The four competitor tiers

**Tier 1 — Global consultancies / Big-4 + Accenture, IBM, Deloitte, PwC, KPMG.**
- *Strengths:* brand, board access, scale, audit relationships.
- *Weaknesses for our segment:* priced for the enterprise (day rates €2,000–3,500+), slow, generalist, treat the mid-market as an afterthought; AI-threat practices are nascent and bolted onto legacy frameworks. **They define the premium "feel" we emulate — but they don't serve our customer profitably.**

**Tier 2 — Pure-play national security-services firms (our true peer set).**
- **Germany:** **SECUINFRA** (Berlin, founded 2010, MDR + incident response, leading SIEM/MDR house, no external investors), **secunet**, **G DATA**, plus T-Systems / Atos / NTT / Orange Cyberdefense at the larger end. ([SECUINFRA](https://www.secuinfra.com/en/))
- **UK:** **Bridewell** (founded 2013, CNI focus, holds the most NCSC-assured services of any UK provider, CREST/CHECK, blends MDR + pen-test + privacy), **NCC Group**, **Nettitude.** Recommended outsourcing partners for 250+ staff orgs. ([Bridewell](https://www.bridewell.com/) · [NCSC](https://www.ncsc.gov.uk/organisation/bridewell))
- **Singapore:** **Ensign InfoSecurity** (founded 2000, Asia's largest pure-play MSSP, **#7 globally** in the 2025 MSSP Alert Top 250, strong public-sector/finance), plus Horangi, Attila Cybertech, InsiderSecurity. ([Ensign](https://www.ensigninfosecurity.com/) · [Manila Times](https://www.manilatimes.net/2026/01/07/tmt-newswire/pr-newswire/ensign-infosecurity-maintains-top-10-global-managed-security-service-providers-mssp-ranking-remains-asia-pacifics-leading-mssp-for-the-fourth-year/2254197))
- *Gap they leave:* each is **strong in one country** and built around **classical** MDR/SIEM/pen-test. None is positioned as **AI-threat-native** or operating a **single cross-border (DE+UK+SG) compliance-aligned offer.**

**Tier 3 — "Security *for* AI" product start-ups.**
- **Protect AI** (acquired by Palo Alto Networks, Apr 2025, ~$400M valuation), **Lakera** (being acquired by Check Point, ~$300M, Q4 2025), **Pangea** (acquired by CrowdStrike), **HiddenLayer** ($50M, M12/Moore), **Cranium.** ~**$1.2bn across four AI-security M&A deals in 2025.** ([Menlo Ventures](https://menlovc.com/perspective/security-for-ai-genai-risks-and-the-emerging-startup-landscape/) · [CyberScoop](https://cyberscoop.com/check-point-lakera-acquistion-ai-security/))
- *What they do:* secure the customer's *own* AI/LLM stack (prompt-injection, model security). *What they don't do:* defend the customer against **AI-powered attackers** on their *whole* estate, or carry compliance accountability. **They are potential product partners/acquisition comps, not direct competitors** — and the M&A wave proves strategic appetite and exit paths in this category.

**Tier 4 — Generalist regional IT/MSPs.** Cheap, broad, **not credible** on AI-threat or regulated-sector compliance; increasingly *regulated themselves* (UK CSR Bill). A source of displaceable incumbent spend, not a real competitor on capability.

### 5.2 The white space AEXIS occupies
> **AI-threat-native, outcome-based cyber assurance for the regulated mid-market, delivered identically across Germany, the UK and Singapore, with compliance evidence (NIS2 / DORA / UK-CSR / SG-CSA / MAS) built into every engagement.**

No incumbent combines all four: (1) **AI-era threat model** as the core, not a bolt-on; (2) **mid-market** economics and speed; (3) **cross-border** single-vendor coverage for the many mid-market groups that operate in 2–3 of these hubs; (4) **regulatory evidence as a product**, not a by-product.

---

## 6. Risks to the thesis (and why they're manageable)

| Risk | Evidence / reality | Mitigation |
|---|---|---|
| "AI defence eventually favours defenders, eroding urgency" | Anthropic itself says the **transitional period is tumultuous** and may last years; defence advantage is *eventual*, not imminent. | AEXIS sells the transition *and* the steady state (continuous assurance + compliance never expire). |
| Incumbents (Big-4, Bridewell, Ensign) move down-market | Their cost base and enterprise focus make profitable mid-market service hard; AI-threat reposition is slow. | Speed, productisation, AI-native delivery, cross-border single-vendor offer. |
| Platform players (CrowdStrike/Palo Alto) bundle "AI security" | They secure the AI stack, not the whole-estate AI-threat posture for mid-market; they sell product, not assured outcomes. | Partner/resell their telemetry; own the **outcome + compliance** layer they don't want to staff. |
| Commoditisation of audits | A one-off audit alone is commoditisable. | Audit is the **wedge**, not the business; recurring managed safeguarding + platform is the moat (NRR, switching cost, compliance lock-in). |
| Regulation slips/softens | NIS2 in force, DORA enforceable, SG provisions live, UK Bill mid-passage — **already enacted, not pending.** | Demand is anchored in *current law*, not anticipated law. |

---

## 7. Source index
All figures above carry inline links. Primary sources: Anthropic Red (Mythos preview), Bitkom Wirtschaftsschutz 2025, UK DSIT Cyber Security Sectoral Analysis 2026 & Breaches Survey 2025/26, IBM Cost of a Data Breach 2025, ISC2 Workforce Study 2025, Mordor Intelligence / MarketsandMarkets (market sizing), and primary-law commentary from Reed Smith, Greenberg Traurig, Morrison Foerster, Clifford Chance, Hogan Lovells, Allen & Gledhill, Mayer Brown, ESMA, MAS, CSA and GOV.UK.

*Research compiled via built-in web tools (no external paid-API cost). Forward-looking figures are estimates; figures used in the financial model are labelled **[ASSUMPTION]** there and in §2.*
