# Cycle Delta — 2026-07-02

Window: 2026-06-30 → 2026-07-02 (last 48 hours — Thursday run)

## Override-worthy this cycle

1. **An IDV incumbent just bundled document + biometric + bureau + (soon) Open Banking into a single API under the UK's Digital Verification Services Trust Framework — Experian launched "Identity Connect" (July 1). The credential layer is commoditising; the orchestration layer is where the market is consolidating.** Account: / company. Angle: The "combine every verification method behind one integration, governed by a national trust framework" move is exactly the orchestration thesis — and now a bureau giant is selling it in Ditto's UK backyard. It lands the same week the UK Finance bank-led digital-ID POC (June 25) and the DVS Trust Framework go commercial. The differentiated value isn't any single check; it's the orchestration, liability allocation and trust-framework compliance around them — Ditto's layer. Use the pattern ("identity is consolidating onto orchestration under trust frameworks"), never the vendor name.

2. **Agentic identity is moving from FIDO working groups into US legislation: a draft bill (Sen. Warner's AI AGENT Act) would force "custodial user agents" to register with the FTC and maintain auditable traceability linking every agent action back to a legally responsible human (surfaced July 1).** Account: / company. Angle: The FSB (June 10) said human oversight of agentic AI is breaking down and recommended AI-monitors-AI governance; now a legislature is drafting the accountability layer — every autonomous agent needs a verifiable, revocable, attributable identity. That is an identity-orchestration problem before it is an AI problem. Ditto's territory: who issues, binds, and revokes an agent's credential, and who's liable when it acts.

## New findings

### Pillar 1: Banking & Payments
- **MiCA deadline-day, resolved: France's AMF discloses ~40% of registered French crypto providers never even filed a MiCA application; ~210 of 3,000+ EU firms authorised (July 1, 2026)** — With the transitional period now expired bloc-wide, France's **AMF** confirmed that roughly **40% of registered French crypto-asset service providers never submitted a MiCA licence application** at all — not rejected, never filed. ESMA's interim register shows only ~210 of 3,000+ firms fully authorised by the deadline. Named post-deadline positioning: Binance entered July without EU authorisation (pursuing a France/AMF licence after withdrawing its Greek application June 21); **Bybit** serves the EEA via a MiCAR-licensed Austrian entity (Vienna, ex-Malta); **Gemini** wound down UK/EEA retail in April 2026 despite holding MiCA/MiFID II authorisations. Same event as the June 29–July 1 overrides (Binance exit / conversion-rate math); logged here for the deadline-day resolution and the fresh AMF "never applied" datapoint, not as a new discovery. For Ditto: the demand-side proof that MiCA is an identity/KYC/compliance filter is now a closed fact — and the ~40%-never-applied figure says most of the shortfall wasn't firms that failed the bar, but firms that never had licensable controls to bring.
  - Source: https://www.financemagnates.com/cryptocurrency/regulation/europes-crypto-market-after-july-1-who-stays-who-leaves-and-what-changes-under-mica/
  - Source: https://news.bitcoin.com/mica-deadline-hits-july-1-as-unlicensed-crypto-platforms-face-eu-shutdown-risk/
  - Date: 2026-07-01

### Pillar 2: Identity orchestration
- **Experian launches "Identity Connect" — single-API UK verification bundling document + selfie/liveness + bureau + fraud-database checks under GPG45 and the DVS Trust Framework (July 1, 2026)** — Credit-bureau giant **Experian** launched **Identity Connect**, a UK-specific identity-verification platform that combines document capture and validation, selfie and liveness checks, Experian bureau activity data, PEP and mortality screening, and National Hunter fraud-database checks **through a single API**. It is explicitly built around two UK frameworks — the government's **Good Practice Guide 45** (identity proofing) and the **Digital Verification Services (DVS) Trust Framework** (certifying providers for Right to Work, Right to Rent, DBS checks). Experian says future updates will add **Open Banking**-based verification, with a longer-term goal of removing physical documents entirely. For Ditto: a bureau incumbent is now selling orchestration-as-a-product in the UK, governed by a national trust framework — validating the thesis that the credential/check layer is commoditising and the value is moving up to the orchestration + trust-framework-compliance layer. Lands the same fortnight as the UK Finance bank-led digital-ID POC (June 25). Competitive/ecosystem datapoint — critique the pattern (identity consolidating onto trust-framework orchestration), never name the vendor. Cross-listed P6.
  - Source: https://idtechwire.com/experian-launches-identity-connect-for-uk-digital-verification/
  - Source: https://ffnews.com/news/experian-launches-identity-connect-to-streamline-uk-digital-verification-and-fraud-prevention
  - Date: 2026-07-01
- **Draft US "AI AGENT Act" (Sen. Warner) would require custodial AI agents to register with the FTC and maintain auditable, human-attributable identity (surfaced July 1, 2026)** — A US legislative proposal — Senator Mark Warner's **Artificial Intelligence Access, Gatekeeper Exchange, and Nondiscriminatory Transfer (AI AGENT) Act of 2026** — would require providers of **"custodial user agents"** to **register with the FTC** before accessing large online-platform interfaces, and defines such agents as software a user authorises to act on their behalf in a "transparent, documented, limited, and revocable" way. The framework would create continuous traceability linking an agent's actions back to a legally responsible human or corporation. For Ditto: agentic identity is moving out of the FIDO/standards track and into statute — every autonomous agent needs an issuable, bindable, revocable, attributable credential, and someone must own liability when it transacts. That is an identity-orchestration problem, and it ties directly to the FSB's June 10 warning that human oversight of agentic AI is breaking down. Orchestration/agentic-identity angle; ecosystem-signal framing (name the trend, not the bill number, in posts).
  - Source: https://idtechwire.com/id-tech-digest-july-1-2026/
  - Source: https://www.cio.com/article/4191009/how-the-senates-ai-agent-act-could-reshape-enterprise-ai-governance.html
  - Date: 2026-07-01 (digest surfacing) / AI AGENT Act is a 2026 Warner proposal

### Pillar 3: EUDI / eIDAS2
- **Namirial Wallet integrated into the France Identité ecosystem — a certified private QTSP wallet plugs into a live national EUDI scheme (July 1, 2026)** — **Namirial**'s digital-identity wallet was integrated into **France Identité**, France's national digital-credentials system, complying with eIDAS requirements so citizens can store official credentials and qualified electronic signatures for government and commercial use. Namirial is an eIDAS 2-certified QTSP (and ANSSI-certified PVID remote-ID provider) across France, Italy and Spain. For Ditto: another concrete signal that the EUDI wallet layer is consolidating — national schemes (France Identité, already a live production service) absorbing certified private-sector wallets and QTSPs — so the credential/wallet becomes shared infrastructure and the differentiation moves to relying-party integration, orchestration and trust-framework compliance. Ties to the France Identité ZKP work tracked in prior deltas and the Romania→Germany open-source reuse (July 1 delta). Ecosystem datapoint.
  - Source: https://idtechwire.com/id-tech-digest-july-1-2026/
  - Source: https://www.biometricupdate.com/202605/namirial-advances-eudi-wallet-remote-id-infrastructure-with-eidas-2-compliance
  - Date: 2026-07-01

### Pillar 4: KYC / AML compliance
(no new material in window — AMLA's package remains on track for **final-draft submission to the Commission by July 10, 2026** (8 days); AMLA must deliver 23 RTS/ITS/guidelines across 2026. AMLR/AMLD6 apply from July 10, 2027. FATF's seventh targeted update on VA/VASP standards (approved June 17–19 plenary) still due July 2026. No new AMLA consultation, FATF publication or named sanctions action confirmed inside June 30–July 2.)

### Pillar 5: Customer onboarding
(no new discrete onboarding-KPI benchmark or sector study published inside June 30–July 2. The onboarding-adjacent items this cycle are the Experian single-API IDV bundle (P2/P6) and the Namirial/France Identité wallet integration (P3), both of which reduce document-upload friction in third-party onboarding.)

### Pillar 6: Identity verification (IDV)
- **Experian "Identity Connect" — single-API bundle of biometric + document + bureau + fraud-DB checks under UK DVS Trust Framework (cross-listed from P2)** — See P2 for full detail. IDV-pillar read: an incumbent is collapsing the verification stack (liveness, document, bureau, National Hunter, PEP/mortality) into one certified API and pre-announcing an Open-Banking-first, document-optional roadmap — a leading indicator that standalone point checks are commoditising and the market is buying orchestrated, trust-framework-certified verification. Ditto Verify plays in the higher-assurance layer this consolidation points toward.
  - Source: https://idtechwire.com/experian-launches-identity-connect-for-uk-digital-verification/
  - Date: 2026-07-01
- **Xailient's casino facial-recognition platform gets GLI validation — commercial green light for self-exclusion and underage-gambling detection (July 1, 2026)** — **Xailient** received **Gaming Laboratories International (GLI)** certification for its casino-focused facial-recognition system, enabling commercial deployment for self-exclusion enforcement, VIP identification and **underage gambling detection**. Gaming is a named Ditto target industry (age verification, AML, jurisdictional mandates). For Ditto: independent lab certification of face-based verification for a regulated vertical is a leading indicator that biometric IDV/age-checks are industrialising past pilots into certified, jurisdiction-mandated deployments — the same "prove interoperability and assurance at scale" shift the Fime mDL scheme signalled last cycle. Cross-listed P11.
  - Source: https://idtechwire.com/id-tech-digest-july-1-2026/
  - Date: 2026-07-01

### Pillar 7: Fraud / Deepfakes
(no new named in-window incident — the circulating fraud reports (Veriff Identity Fraud Report 2026 — >5.5% net fraud rate in financial services, crypto/lending +38% YoY; Sumsub deepfakes now 11% of fraud) are Nov–Dec 2025 releases, out of window and not fresh. No named-bank deepfake event dated June 30–July 2 confirmed. Anchor: EU AI Act Art. 50 — July 22 Code-of-Practice signatory deadline / August 2 enforcement of deepfake labelling.)

### Pillar 8: Mobile trust & app security
(no new named Android-malware family or SS7/SIM-swap breach dated June 30–July 2 confirmed. The network-layer anti-SIM-swap story (Bouygues Telecom × Aduna / CAMARA) is last cycle's material. Broader landscape unchanged: Anatsa (650+ FIs, accessibility abuse) and NGate/NFC-relay families remain active per 2026 threat-intel, but no in-window disclosure this cycle. Watch item: Yubico joined ECSO (July 1) to push FIDO/phishing-resistant MFA into EU policy under NIS2/eIDAS — policy-side mobile-trust signal, noted below in P9.)

### Pillar 9: Passwordless / split-key
- **Yubico joins the European Cyber Security Organisation (ECSO) to shape FIDO/phishing-resistant-MFA policy under NIS2 and eIDAS (July 1, 2026)** — Hardware-authentication vendor **Yubico** joined **ECSO** to influence European digital-security policy and standards, explicitly to broaden adoption of FIDO-based phishing-resistant MFA to meet **NIS2 and eIDAS** requirements. Minor but on-pillar: the passwordless/FIDO camp is organising at the EU policy layer, reinforcing the regulatory direction of travel (OTP sunsets, phishing-resistant auth as default) that the BSP Circular 1213 hard stop and Singpass passkey move (prior deltas) exemplify at the deployment layer. Ecosystem/policy datapoint (do not name in posts).
  - Source: https://idtechwire.com/id-tech-digest-july-1-2026/
  - Date: 2026-07-01

### Pillar 10: ZKPs in practice
(no standalone new material in window — the Namirial/France Identité wallet (P3) is the cycle's selective-disclosure-adjacent item (France Identité's ZKP work tracked previously). No new bank ZKP pilot or OpenID4VP/VCI deployment confirmed inside June 30–July 2.)

### Pillar 11: Age assurance & privacy attributes
- **Xailient casino facial recognition gets GLI validation for underage-gambling detection (cross-listed from P6)** — See P6. Age-assurance read: certified face-based age/identity checks for regulated gambling are reaching commercial deployment — a datapoint on age assurance industrialising in a Ditto target vertical. No new platform enforcement action or EU age-verification-app update confirmed inside June 30–July 2. Watch item: **EU airlines/airports petitioned to suspend Entry-Exit System (EES) biometric border checks during peak summer** (July 1) citing software bottlenecks — biometric-infrastructure-strain signal in the travel vertical, not core age-assurance policy. Next hard anchor: **Ofcom's statutory age-assurance effectiveness report, due July 17, 2026**; UK OSA "highly effective age assurance" milestone flagged around July 25 (per legal analysis — confirm).
  - Source: https://idtechwire.com/id-tech-digest-july-1-2026/
  - Date: 2026-07-01

---

## Next-cycle anchors (updated)

- **MiCA CASP deadline — CLOSED (July 1)** — transitional period expired bloc-wide; AMF discloses ~40% of French registrants never applied; ~210/3,000+ authorised. Watch July 2–8 for the first named post-deadline NCA/ESMA enforcement action against a continuing unlicensed operator.
- **Binance France MiCA application** — Binance out of the EU; pursuing an AMF licence "in coming months." Watch the AMF process.
- **Philippines BSP Circular 1213 compliance data** — deadline passed June 30; no sector compliance-rate figure or BSP enforcement statement yet confirmed. Watch for first data.
- **AMLA CDD / sanctions / business-relationship RTS final drafts → Commission (July 10)** — 8 days.
- **FATF seventh targeted update on VA/VASP Standards (July 2026)** — DeFi, stablecoins, unhosted wallets.
- **Ofcom statutory age-assurance effectiveness report (July 17)** — 15 days.
- **UK Online Safety Act "highly effective age assurance" milestone (~July 25, per legal analysis)** — confirm exact obligation/date.
- **EU AI Act Code of Practice signatory deadline (July 22)** — 20 days.
- **FSB AI Sound Practices consultation deadline (July 22)** — 20 days; final report to G20 October 2026.
- **EU AI Act Article 50 enforcement (August 2)** — 31 days; deepfake labelling, AI-content marking, chatbot disclosure become binding.
- **US AI AGENT Act (Warner)** — new anchor; watch for formal introduction / committee referral and any FTC-registration mandate for custodial AI agents.
- **EU Entry-Exit System (EES) summer operations** — new watch item; airlines/airports requesting temporary suspension authority over biometric border checks; watch Commission response.
- **EUDI wallet member-state deadline** — "at least one wallet per member state" by end-2026 (Dec 24, 2026); Germany state-driven launch confirmed January 2, 2027; France Identité live and absorbing certified private wallets (Namirial, P3). Watch further member-state adoptions.
- **Germany DIdG Bundestag first reading** — TBD (summer recess likely delays to September).
- **EUDI Wallet biometric-portrait opt-out implementing rule — formal adoption** — TBD (agreed at Committee June 18).
- **UK People's Panel on Digital ID — report publication** — TBD; deliberation concluded June 21.
- **UK Finance bank-led digital ID / TISA Select ID** — watch operator/liability/pricing resolution; DVS Trust Framework now going commercial (Experian Identity Connect, P2).
- **PSR APP-fraud reimbursement independent review report (Q2/Q3 2026)** — watch for publication.
- **PSD3/PSR OJEU publication** — H2 2026, no confirmed date.
- **Japan JSDA phishing-resistant MFA mandatory deadline** — "summer 2026".

---

## Run summary

- Findings count by pillar: P1 Banking: MiCA deadline closed (anchor resolved + fresh AMF "~40% never applied" stat) | P2 Identity orchestration: **2 new** (Experian Identity Connect single-API/DVS Trust Framework; US AI AGENT Act agentic-identity accountability) | P3 EUDI: **1 new** (Namirial Wallet → France Identité) | P4 KYC/AML: 0 | P5 Onboarding: cross-listed P2/P3 | P6 IDV: **2** (Experian cross-list; Xailient GLI casino facial-rec) | P7 Fraud/Deepfakes: 0 new (Veriff/Sumsub reports out of window) | P8 Mobile trust: 0 new (Yubico ECSO noted P9) | P9 Passwordless: **1 new** (Yubico joins ECSO) | P10 ZKP: cross-listed P3 | P11 Age assurance: **1** (Xailient GLI cross-list) + EES suspension watch item — **Total: 5 new in-window findings across 5 pillars + MiCA anchor closing**
- Override-worthy: **2** — (1) Experian Identity Connect: an IDV/bureau incumbent sells orchestration-as-a-product under the UK DVS Trust Framework; (2) US AI AGENT Act: agentic identity moves from FIDO working groups into legislation.
- Delta path: research/2026-07-02-cycle-delta.md
- Note: fresh cluster this cycle is the July 1 ID Tech digest (Experian Identity Connect, US AI AGENT Act, Namirial×France Identité, Xailient GLI, Yubico ECSO). Veriff Identity Fraud Report 2026 (Nov 2025) and Sumsub fraud-trends stats checked and excluded as out-of-window. MiCA deadline now closed; BSP compliance data still pending.
