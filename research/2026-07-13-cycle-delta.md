# Cycle Delta — 2026-07-13

Window: 2026-07-11 → 2026-07-13 (72-hour Fri-Mon weekend window; prior delta covered through 2026-07-10)

---

## Override-worthy this cycle

1. **EU AI Act Article 50 deepfake-labelling enforcement is 20 days away — July 22 is the last day to sign the Code of Practice and secure a presumption of regulatory conformity** — Commission Adequacy Assessment cleared July 8; AI Board endorsed July 9; Article 50 applies August 2. Account: / company. Angle: "In 20 days, unlabelled deepfakes and undisclosed AI chatbots become a €15M regulatory exposure in the EU. Every identity vendor whose product touches AI-generated content — liveness, synthetic voice, document generation — needs to have signed the Code of Practice by July 22 or prepare to argue conformity on its own merits in front of a national AI authority."

---

## New findings

### Pillar 1: Banking & Payments
*(no new primary-source material in window beyond the AMLA 23-measure package covered in the 2026-07-10 delta; PSD3/PSR OJEU publication still pending — expected H2 2026, possibly September)*

---

### Pillar 2: EUDI / eIDAS2
*(no new ARF update, ENISA certification publication, or member-state launch announcement confirmed July 11–13; eideasy.com July 2026 tracker pre-dates window; Germany's January 2027 staged rollout plan announced June 15 is outside window)*

---

### Pillar 3: Fraud / Deepfakes

- **EU AI Act Article 50 transparency obligations enter their final compliance sprint — signatory deadline July 22, enforcement August 2, 2026** — The European Commission published its Adequacy Assessment of the Code of Practice on Transparency of AI-Generated Content on July 8, confirming the Code adequately covers Article 50(2), (4) and (5). The EU AI Board endorsed the assessment on July 9. From August 2, providers of AI systems that generate or manipulate images, audio, and video (including synthetic faces and voice) must implement machine-readable marking and detectability mechanisms; deployers must disclose to users when AI-generated content including deepfakes is being shown to them, with harmonised EU labels at first exposure. Non-compliance: fines up to €15M or 3% of global annual turnover. The Code of Practice is voluntary but confers a presumption of conformity — signatories face a materially lower evidentiary burden in enforcement proceedings. The July 22 deadline is the last date to appear on the initial signatory list published by the EU AI Office ahead of August 2.
  - Source: https://digital-strategy.ec.europa.eu/en/policies/code-practice-ai-generated-content
  - Source: https://ec.europa.eu/commission/presscorner/detail/en/ip_26_1328
  - Source: https://bratby.law/ai-act-transparency-obligations-2026/
  - Date: 2026-07-08 (Commission Assessment) / 2026-07-09 (AI Board endorsement) / deadline 2026-07-22 / enforcement 2026-08-02

- **AU10TIX Q1 2026 Financial Services Fraud Intelligence Report: AI-generated identity fraud surpasses physical forgery for the first time across all financial services sub-sectors** — AU10TIX released its Q1 2026 Financial Services Identity Fraud Intelligence Report on July 9, 2026 (not captured in prior delta). Drawing on a validated ground-truth dataset of identity verification transactions across Payments, Banking, and Trading platforms, the report finds a confirmed fraud rate of 3.89% industry-wide — nearly 1 in 26 verification requests was a confirmed fraud attempt. Critically, AI-generated identities, synthetic documents, and digitally manipulated credentials now represent the dominant fraud methods across all three sub-sectors, surpassing physical document forgery for the first time. Confirmed fraud rates increased across every sub-sector and every document type compared to prior periods. This is not a forecast: it is observed transaction data from production verification pipelines. For Ditto: the 3.89% fraud rate means that in any financial services onboarding or authentication flow at scale, roughly 1 in 26 verification attempts is already adversarial — and the attack surface has structurally shifted from physical forgeries (which traditional document inspection can catch) to AI-generated synthetic identities (which require liveness detection, injection-attack defences, and network-level signal intelligence). Any identity stack relying on classical document scanning as its primary control is operating outside its design envelope in Q1 2026.
  - Source: https://www.prnewswire.com/news-releases/ai-generated-identity-fraud-dominates-financial-services-as-confirmed-fraud-rates-rise-across-every-sub-sector-new-au10tix-data-shows-302821547.html
  - Source: https://www.morningstar.com/news/pr-newswire/20260527da68530/identity-fraud-has-industrialized-au10tix-finds-ai-generated-fraud-surpassed-physical-forgery-for-the-first-time
  - Date: 2026-07-09 (released 1 day before prior delta's 48h window opened; not included in that delta)

---

### Pillar 4: ZKPs in practice
*(no new EU bank ZKP pilot, OpenID4VP/VCI update, or mDL deployment confirmed July 11–13)*

---

### Pillar 5: Passwordless / split-key
*(no new FIDO Alliance specification, regulator OTP-sunset publication, or major bank passkey deployment announcement confirmed July 11–13; FIDO + HID enterprise identity report published June 15 at Identiverse is outside window)*

---

### Pillar 6: LATAM
*(no new material from BCB, CNBV, Superfinanciera, CMF, or SBS confirmed July 11–13; Brazil's Drex centralised architecture pivot is August 2025; Mexico DiMo and CNBV Fintech Festival 2026 signals are broader background, not specific window events)*

---

### Pillar 7: Identity ecosystem

- **Lissi GmbH and Gataca both close new funding rounds to build EUDI Wallet integration infrastructure — European capital backing the identity plumbing layer ahead of December 2026 deadline** — Lissi GmbH (Berlin) closed a €3.5M seed round on July 9, 2026, led by Ventech with participation from BM H Beteiligungs-Managementgesellschaft Hessen (the German state tech fund) and existing investors including main incubator (Commerzbank Group's innovation arm) and Ninepointfive Ventures. Lissi builds the EUDI Wallet Connector Suite and a new SDK that allows financial institutions to integrate wallet-based verifiable credentials directly into their onboarding apps without building the interoperability layer from scratch; the explicit commercial thesis is AMLR 2027 compliance demand. In parallel, Gataca (Spain) also announced a new funding round in the same period (amount undisclosed) to expand EUDI Wallet support into media, iGaming, and financial services in Europe. Coverage of both rounds appeared in trade media (Biometric Update) during the July 11-13 window. Two separate European identity infrastructure companies raising in the same week, both targeting the EUDI Wallet relying-party integration problem, is a signal: the institutional market is starting to fund the "plumbing" between government-issued wallets and commercial onboarding flows. For Ditto: this is the layer immediately above Ditto's own selective-disclosure and credential verification stack — Lissi and Gataca are building the connectors; Ditto builds the cryptographic primitives. The market is bifurcating between connector vendors and deep-protocol vendors.
  - Source: https://tech.eu/2026/07/09/lissi-raises-eur35m-to-power-europes-sovereign-digital-identity-future/
  - Source: https://www.ventechvc.com/stories/independence-for-europes-financial-sector-lissi-gmbh-secures-3-5-million-euros-led-by-ventech-for-european-amlr-compliant-eudi-wallet-integration
  - Source: https://www.biometricupdate.com/202607/investors-back-lissi-gatacas-expansions-to-meet-eu-digital-identity-wallet-moment
  - Date: 2026-07-09 (Lissi primary announcement); Gataca concurrent, exact date TBC; trade roundup coverage July 11-13

---

## Next-cycle anchors (updated)

- **EU AI Act Code of Practice signatory deadline (July 22, 18:00 CEST) — 9 days.** Sign or forego presumption of conformity for Article 50 deepfake/AI-content disclosure obligations. Enforcement August 2.
- **FSB AI Sound Practices consultation deadline (July 22) — 9 days.** FSB published its 12 sound practices for responsible AI adoption in financial institutions June 10, 2026. Virtual outreach July 7. Responses due July 22; final report October 2026.
- **Ofcom age-assurance effectiveness report (by end of July) — ~18 days.** Statutory first-year report under the Online Safety Act; Ofcom + ICO issued joint statement March 2026; written to major platforms; companies with Ofcom legal notices must submit risk-assessment records by July 31.
- **AUSTRAC Tranche 2 enrolment deadline (July 29) — 16 days.** ~100,000 newly-regulated Australian entities (lawyers, accountants, real estate agents, conveyancers) must enrol with AUSTRAC by July 29 or face criminal penalty; compliance obligations commenced July 1. This is an identity onboarding event at scale: each entity must establish a CDD/KYC program and name an AML/CTF compliance officer.
- **EU AI Act Article 50 enforcement (August 2) — 20 days.** Deepfake labelling, chatbot disclosure, AI-content marking become legally binding. Fines: up to €15M or 3% global turnover.
- **UK DVS Trust Framework 1.0 (no earlier than September 1) — ~50 days.** First CAB accreditation triggers the framework; all existing DVS providers have at least 15 months to uplift.
- **EUDI Wallet hard deadline (December 24, 2026) — ~164 days.** All 27 member states must have at least one certified wallet available.
- **PSD3/PSR OJEU publication** — Expected H2 2026; may slip to September. Still politically agreed but not formally adopted or in force.
- **AMLA Commission adoption process** — 23 RTS/ITS delivered July 10 to the Commission; adoption typically 3–6 months; measures apply directly across 27 member states July 10, 2027.

---

## Run summary

- **Findings count by pillar:** P1: 0 | P2: 0 | P3: 2 (EU AI Act Art. 50 enforcement sprint; AU10TIX Q1 2026 fraud data) | P4: 0 | P5: 0 | P6: 0 | P7: 1 (Lissi + Gataca EUDI Wallet infrastructure double-raise) → **Total: 3 findings across 2 pillars**
- **Override-worthy: 1** — EU AI Act Article 50 deepfake-labelling enforcement 20 days away; July 22 is the last day to sign the Code of Practice for presumption of conformity. Account: / company. Window to act is now.
- **Delta path:** `research/2026-07-13-cycle-delta.md`

---

_Window note: July 11–12 were Saturday–Sunday with minimal primary regulatory/vendor announcements. Two findings (AU10TIX Q1 report, Lissi seed) are dated July 9 — 1 day outside the prior delta's stated 48h window and not captured in that delta; trade-media coverage of both appeared July 11–13. Dates noted explicitly. EU AI Act item dates July 8–9 but the active signatory window runs through July 22 making it live this cycle. Worker API (ditto-slack-bot.dittobot.workers.dev) remains blocked by environment proxy; delta written directly to GitHub via MCP._
