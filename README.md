# Awesome-Corporate-Wellness

# Awesome-Corporate-Wellness

**Top Corporate Wellness (Opensource) 🌟 Star if you like it! 🌟**



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Employee Wellbeing Check-ins, Mental Health Support, Burnout Prevention & Workplace Analytics*

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Corporate Wellness**. These tools enable organizations to support employee physical and mental health, run wellbeing check-ins, detect burnout risk, provide anonymous mental health resources, and give HR teams aggregated insights—from fully managed enterprise wellness platforms with clinical networks and global benefits to self-hosted applications that give organizations complete control over sensitive employee health data.



**Examples** include Virgin Pulse, Wellable, Wellhub, Calm for Business, Headspace for Work, Spring Health, Lyra Health, WebMD Health Services, Limeade, and Workday Wellness (the category leaders in commercial space).



**Open-source emphasis**: This section is expanded with every relevant project for self-hosting, wellbeing tracking, and open mental health infrastructure. **Critical note**: Dedicated open-source corporate wellness platforms are sparse and early-stage. Most projects below are individual developer efforts, hackathon prototypes, or narrow-scope tools—none replicate the clinical networks and global content libraries of Spring Health or Lyra Health.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global corporate wellness market is valued between **$55B and $76B** (projected to reach over $100B by 2030 at ~7–9% CAGR), driven by preventive digital health, remote workplace ergonomics, and corporate mental health investments. The industry is currently **moderately fragmented**—with no single leader controlling more than 10% market share and the top 10 providers capturing 35–40%—though it is rapidly consolidating through M&A as enterprise buyers migrate away from point solutions toward unified, all-in-one health and benefits platforms.

## SaaS/Hosted Platforms

| Platform | Company Size (Valuation / Revenue) | Pricing (Starting Tiers) | Free Tier / Trial Limits | Key Capabilities & Best For |
| :--- | :--- | :--- | :--- | :--- |
| **[Workday Wellness](https://www.workday.com/)** | **~$52B Market Cap** (~$8.4B–$10B ARR) | Core HCM suite starts at **~$3–$8/employee/month** at scale ($35–$100/employee/year; Wellness module quoted as enterprise add-on) | **No perpetual free tier**; enterprise sales demo & custom sandbox environments available upon RFP qualification | Best for Workday enterprise customers seeking integrated benefits administration and unified HR data. |
| **[Lyra Health](https://www.lyrahealth.com/)** | **~$5.6B Valuation** (Series F) | Starting tiers structured via clinical baseline models at **~$3–$10 PEPM** (utilization & value-based outcomes models) | **No perpetual free tier**; structured prospective client evaluation demos with no public self-service sandbox | Comprehensive clinical mental health, therapist networks, digital coaching, and outcome-guaranteed enterprise care. |
| **[Spring Health](https://www.springhealth.com/)** | **~$3.3B Valuation** (Series E) | Bundled enterprise mental health starting tiers at **~$3–$10 PEPM** based on workforce size & coverage scope | **No perpetual free tier**; enterprise sales demo & clinical ROI consultation with no direct self-serve trial | Precision mental health, clinical navigation, employee therapy sessions, and psychiatric medication management. |
| **[Virgin Pulse](https://www.virginpulse.com/)** *(Personify Health)* | **~$3.0B Valuation** (~$500M ARR post-merger) | Starting enterprise packages at **~$3–$6 PEPM** (typical annual minimum commitments start at ~$15,000–$18,000/year) | **No perpetual free tier**; sales-guided interactive partner portal demo and pilot scoping (no public self-serve trial) | Large employers seeking holistic engagement, physical activity rewards, social challenges, and health benefits navigation. |
| **[Wellhub](https://wellhub.com/)** *(Gympass)* | **~$2.4B Valuation** (Series F) | Employer corporate baseline access fee starts at **$1.00/employee/month** (Premium packages from $10–$50 PEPM; employee gym tiers separate) | **No perpetual free tier**; employer pilot walkthroughs available on request (requires corporate email domain) | Subsidized global gym, fitness studio, and digital wellness app networks for distributed workforces. |
| **[Calm for Business](https://www.calm.com/business)** | **~$2.0B Valuation** (~$200M–$210M ARR) | Starting self-serve business tiers at **~$60–$70/employee/year** (~$5.00–$5.83/seat/month, min. 5 seats billed annually) | **Perpetual consumer free tier** (limited rotating meditations, 1 breathing exercise; business admin portal has 0 free days / demo-only) | Turnkey self-guided mindfulness, sleep stories, guided breathing, and workplace stress reduction. |
| **[Headspace for Work](https://www.headspace.com/work)** | **~$300M Acquisition** (~$200M ARR) | Core mindfulness tiers start at **$12–$36/employee/year** ($1–$3/seat/month for 100+ seats; clinical coaching at $3–$12 PEPM) | **14-day free trial** with full library access on consumer accounts (business tiers evaluated via consultative sales pilot) | Evidence-based mindfulness sessions, mood check-ins, focus music, and integrated behavioral health coaching. |
| **[WebMD Health Services](https://www.webmdhealthservices.com/)** | **Sub-division of KKR / WebMD** (~$75M Limeade acquisition) | Digital-only wellness starting tiers at **~$3–$8 PEPM** (full-service clinical/coaching packages start at $8–$15+ PEPM) | **No perpetual free tier**; guided platform demonstration and organizational pilot scoping via sales consultants | Clinically oriented population health management, biometric screening integration, and chronic condition support. |
| **[Limeade](https://www.limeade.com/)** *(WebMD ONE)* | **$75M Acquisition Price** (~$56M annual revenue) | Employee listening and wellbeing suites start at **~$3–$7 PEPM** (minimum employee headcount thresholds apply) | **No perpetual free tier**; custom employer demo of TINYpulse and Limeade Well-Being suites upon request | Holistic employee engagement, organizational inclusion, pulse survey analytics, and well-being habit tracking. |
| **[Wellable](https://www.wellable.co/)** | **~$22M–$26M ARR** (Private Growth Stage) | *Essentials* tier starts at **$4.00/user/month** ($100/mo platform minimum; *Pro* tier starts at $6.00/user/month) | **No perpetual free tier**; interactive product tours and personalized 1-on-1 team demonstrations on request | Mid-market structured wellness challenges, customizable rewards programs, and wearable health tracker syncing. |

## Open-Source GitHub Projects



- **[WorkMate](https://github.com/karlis0099/WorkMate)**

  **Employee wellbeing platform** (license per repo) — **the most complete open-source wellbeing check-in system** found in this research. **Features**: Weekly 7-dimension psychological check-ins (mood, energy, motivation, stress, work-life balance, team connection, accomplishment), real-time composite wellbeing scores, burnout risk alerts with Slack/Teams webhooks, manager dashboard with team analytics, and CSV export . **Tech stack**: Java (desktop app serving local web UI), SQLite. **Deploy**: Self-hosted on local network. **Trade-off**: Desktop-application architecture limits remote access; no clinical resources, EAP integration, or content library. **Best for**: small teams wanting a private, self-hosted weekly check-in tool with burnout detection and manager visibility.



- **[MindBridge](https://github.com/guopanqi/mindbridge)**

  **Anonymous employee psychological support system for DingTalk organizations** (license per repo) — **the most privacy-architected open-source mental health platform** in this list. **Features**: Anonymous employee counseling sessions, mood tracking, community posts, counselor case management, and HR aggregate dashboards with **hardcoded privacy thresholds** (no data shown when sample size < 10). Employee conversations encrypted with AES-GCM; crisis detection via deterministic rules engine; HR can only see aggregates, never individual identities . **Tech stack**: Cloudflare Pages/Workers, D1 databases (physically separated identity/care/staff), Node.js DingTalk bot. **Deploy**: Cloudflare ecosystem (requires DingTalk for auth). **Trade-off**: DingTalk-dependent; Chinese-language; no physical wellness features. **Best for**: organizations in the DingTalk ecosystem wanting genuinely anonymous mental health support with strict privacy guarantees.



- **[AI Wellness Hub](https://github.com/Saikumar1801/AI-Wellness-Hub)**

  **Dual-AI workplace mental health platform** (license per repo) — **a sophisticated diagnostic tool for HR plus a safe employee chatbot**. **Features**: XGBoost predictive model forecasting employee mental health treatment likelihood; SHAP explainability showing actionable workplace factors; Google Gemini-powered advisor for HR recommendations and an employee-facing informational chatbot with crisis hotline safety protocols; downloadable PDF reports . **Tech stack**: Python, Streamlit, Scikit-learn/XGBoost, SHAP, Google Gemini API. **Deploy**: Self-hosted (Streamlit). **Trade-off**: **Hackathon project**—no authentication, no persistent multi-tenant data, no production deployment model. **Best for**: HR analysts wanting a reference implementation for predictive workplace mental health analytics.



- **[Sanicle-AI](https://github.com/ChanMeng666/sanicle-ai)**

  **Women's health platform designed for workplace wellness** (license per repo) — **a specialized FemTech application with enterprise privacy architecture**. **Features**: Personalized health tracking for female employees (menstrual health, menopause support), dual AI integration (IBM WatsonX for quick chat, Google Gemini for deep consultations), HR dashboards with **anonymized aggregate insights only**, multi-tenant isolation, GDPR-compliant data handling, and role-based access control . **Tech stack**: Next.js, TypeScript, IBM WatsonX, Google Gemini. **Deploy**: Self-hosted. **Trade-off**: **Narrow scope** (women's health only); small community (1 star); enterprise features unvalidated at scale. **Best for**: organizations wanting to offer specialized women's health support with strict data separation between employees and HR.



- **[Sentio](https://hub.docker.com/r/padi2312/sentio)**

  **Team mood tracker** (license per repo) — **a lightweight, privacy-conscious daily check-in tool** modeled on the Niko-Niko calendar. **Features**: One-click daily mood logging, anonymous mode per team, team dashboards with wellbeing trends, personal mood history, browser push notifications, custom recurring reminders, Google Calendar integration for event-based check-ins, and admin-configurable mood options . **Tech stack**: Docker, PostgreSQL, pnpm/Vite frontend. **Deploy**: Docker Compose (recommended). **Trade-off**: Mood tracking only—no clinical resources, EAP integration, or burnout analytics. **Best for**: small teams wanting a simple, self-hosted daily mood pulse without complex setup.



- **[Impulse Wellness Platform (Move On)](https://github.com/Matheussoranco/Unified_industrial_HR_System)**

  **Comprehensive corporate wellness platform** (AGPL-3.0) — **a frontend prototype covering physical, mental, and nutritional health**. **Features**: Health tracking (heart rate, weight, mood, stress, hydration), corporate wellness programs with rankings, community posts and leaderboards, healthy recipes, and HR benefits management . **Tech stack**: React, TypeScript, Tailwind CSS. **Deploy**: Self-hosted (Node.js). **Trade-off**: **Discontinued project**—developer explicitly states lack of corporate support ended development; no backend, simulated authentication only. **Best for**: developers wanting a UI reference for a multi-dimensional wellness platform to fork and complete.



- **[wellness-agent](https://github.com/ChanMeng666/wellness-agent)**

  **Enterprise-grade workplace wellness platform** (license per repo) with 5 specialized AI agents. **Features**: Privacy-first multi-role support (employees, HR managers, employers), persistent memory system, real-time wellness tracking, and role-based access . **Tech stack**: TypeScript. **Deploy**: Self-hosted. **Trade-off**: **Zero stars, zero forks**—unvalidated, undocumented, and likely a portfolio project. **Best for**: developers wanting a starting point for AI-agent-based wellness architecture.



### Additional Strong Open-Source Options



- **Reflect (Microsoft Teams)** — Custom Teams message extension (MIT) for safe emotional wellbeing check-ins. **Features**: Share state of emotional wellbeing with colleagues or group leaders directly in Teams; check-in response can be public, private-to-sender, or fully anonymous . **Best for**: Microsoft Teams organizations wanting a native, low-friction wellbeing pulse tool.

- **Aura Health AI** — Python Dash prototype (license per repo) with employee wellness dashboard and HR analytics. **Note**: Rule-based AI simulation; mock data only; no real backend . **Best for**: developers wanting a UI/UX reference for a dual-dashboard wellness prototype.

- **health-frontend** — React wellness check-in UI with manager dashboard (license per repo). **Features**: Daily wellness questionnaire, manager aggregated view, HIPAA/GDPR-oriented design . **Best for**: frontend developers needing a starting point for a compliant check-in interface.



**Frameworks for building custom systems**: Combine **WorkMate** for weekly psychological check-ins with burnout alerts, **MindBridge** for anonymous mental health support with strict privacy architecture, **Sentio** for lightweight daily mood pulses, and **AI Wellness Hub** as a reference for predictive analytics—creating a corporate wellness stack matched to each organization's privacy requirements and depth of support needed. **None of these replace a full clinical network** like Spring Health or Lyra Health.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, license (for open-source), and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Corporate wellness platforms handling employee health and mental health data must comply with data protection regulations (HIPAA where applicable, GDPR, CCPA, etc.) and implement appropriate access controls, anonymization, and audit trails. **Mental health data is among the most sensitive categories**—privacy architecture must be evaluated carefully before deployment.

- **Dedicated open-source corporate wellness platforms are sparse and immature.** No mature open-source project matches Virgin Pulse, Spring Health, or Lyra Health in scope (clinical networks, global content libraries, EAP integration, outcomes measurement). **WorkMate** is the most complete check-in system; **MindBridge** has the strongest privacy architecture; **Sanicle-AI** is the most specialized. **Most others are prototypes, hackathon projects, or discontinued efforts.** Organizations with genuine enterprise wellness needs will likely require SaaS or significant custom development.

- **The "check-in tool" vs. "mental health platform" vs. "clinical benefit" distinction matters.** **WorkMate, Sentio, and Reflect** are **pulse/check-in tools**—they measure how employees feel. **MindBridge** and **AI Wellness Hub** provide **support and analytics**. **Spring Health and Lyra Health** provide **clinical care**. **Do not confuse a mood tracker with a mental health benefit.**

- **Privacy architecture varies dramatically.** **MindBridge** physically separates identity, care, and staff databases; encrypts conversations with AES-GCM; and hardcodes HR aggregate thresholds at <10 samples . **Sanicle-AI** claims multi-tenant isolation and anonymized HR dashboards . **WorkMate** stores check-in data in a local SQLite database with SHA-256 hashed PINs . **Aura Health AI** is a prototype with **no real data handling** . **Evaluate privacy design before trusting any tool with employee mental health data.**

- **Pricing opacity is universal across commercial vendors.** Virgin Pulse, Wellable, Wellhub, Calm for Business, Headspace for Work, Spring Health, Lyra Health, WebMD Health Services, Limeade, and Workday Wellness all require sales contact for quotes. **Validate with direct vendor conversations against your employee count and desired scope.**

- **Several open-source projects are explicitly discontinued or unvalidated.** **Impulse Wellness Platform** states development ended due to lack of support . **wellness-agent** has zero stars and no documentation . **AI Wellness Hub** and **Aura Health AI** are hackathon/prototype efforts with no production path . **Do not deploy abandoned or unvalidated software with sensitive employee health data.**

- Self-hosted open-source solutions require proper server setup, backup configuration, and ongoing maintenance. **Employee wellness data is highly sensitive**—ensure your hosting meets your organization's security and privacy requirements before deploying.



---



**Made for developers, HR teams, and organizations building transparent corporate wellness solutions.**

Let's make Corporate Wellness more open, data-driven, and employee-friendly.
