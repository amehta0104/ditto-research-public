# Cycle Delta — 2026-08-10

Window: 2026-08-07 → 2026-08-10 (last 72 hours — Monday rule)

Worker note: `ditto-slack-bot.dittobot.workers.dev` continues to return 403 from the session's egress proxy (policy denial, not a credential issue). Skill files sourced from repository baseline and prior deltas. Delta written directly to GitHub via MCP.

---

## Override-worthy this cycle

1. **OfDIA opens consultation on supplemental DVS code for digital age verification — new certification layer landing 22 days before September 1 DVS enforcement** — The UK Office for Digital Identities and Attributes has signalled it is exploring a dedicated supplementary code for digital age verification within the DVS trust framework, separate from the main trust framework certification. A provider must first hold DVS trust framework certification before seeking the supplemental age code — creating a two-layer certification system. With the DVS ecosystem at 46 providers and September 1 enforcement now 22 days away, the bar for UK age assurance is moving again mid-deployment. Account:. Angle: "The UK DVS Trust Framework goes live in 22 days. OfDIA has just floated a supplemental certification track specifically for digital age verification — on top of the main trust framework. 46 providers just certified. Now age assurance checks need a second badge. The vendors that build for both tracks own the channel — the ones that built only for the first don't."

---

## New findings

### Pillar 1: Banking & Payments

(no new PSD3/PSR OJEU publication, AMLA RTS package, EBA enforcement press release, or FCA/PSR APP fraud reimbursement review conclusion in window. Financial Services and Markets Bill 2026-27 — which consolidates PSR into FCA — introduced to Parliament May 19 and now in passage; PSR Q3 post-implementation review of APP fraud reimbursement has sent survey to 50 firms in August — watch for report publication. PSD3/PSR OJEU still tracking to September 2026. No new in-window print.)

### Pillar 2: EUDI / eIDAS2

- **Germany's SPRIND sandbox identifies EU-wide relying-party onboarding as the systemic EUDI bottleneck — shifts risk narrative from wallet issuance to wallet usability (August 2026)** — Germany's SPRIND innovation sandbox, which is piloting EUDI wallet technical integrations, has documented an EU-wide structural problem: relying-party onboarding infrastructure is lagging wallet-issuance infrastructure. The finding shifts the December 24 deadline risk from "member states won't have wallets ready" to "even where wallets exist, too few relying parties will be integrated to make them usable at launch." Additional Germany context in the August 2026 update: Germany is pursuing a deliberate multi-provider model — accrediting private wallet providers on top of its national eID infrastructure alongside a state wallet — and has allocated €79.3M to the project through 2026. The state wallet remains on a January 2, 2027 timeline (nine days late, confirmed). For Ditto: the relying-party integration bottleneck is precisely the position Ditto can occupy. Identity vendors with deployment-ready EUDI relying-party integrations have a structural advantage: wallet holders have nowhere to use their wallet without institutions willing to accept it. The relying-party layer is the commercial moat, not the wallet layer. Not in prior deltas as a technical root-cause analysis of the bottleneck; the Aug 7 delta covered the member-state availability slippage (Forbes piece) but not this systemic relying-party finding.
  - Source: https://www.biometricupdate.com/202608/germanys-eudi-wallet-push-highlights-europes-implementation-gap
  - Source: https://www.europesays.com/3174549/
  - Date: August 2026

### Pillar 3: Fraud / Deepfakes

(no new bank deepfake enforcement action, named iProov/Onfido/Sumsub/Veriff report, or FATF guidance in window. iProov 2026 Threat Report, Biometric Update Deepfake Market Report ($3B→$6.1B), Reality Defender Google selfie bypass, and Shufti Identity Fraud Index (495% surge projection) all covered in Aug 4-5 deltas. GetReal Deepfake Summit content and LexisNexis 8× synthetic identity fraud figure pre-date the window. No new in-window print.)

### Pillar 4: ZKPs in practice

(no new bank ZKP pilot, OpenID4VP/VCI deployment announcement, or selective-disclosure mDL milestone in window. FDD ZKP critical-infrastructure oversight analysis (Aug 4) covered in Aug 6 delta. OpenID4VP 1.0 self-certification (February 2026) and EU ARF v3.0.0 (July 21) remain the benchmark anchors. No new in-window print.)

### Pillar 5: Passwordless / split-key

- **OfDIA signals supplemental DVS code for digital age verification — second certification track within UK trust framework (August 2026)** — The UK Office for Digital Identities and Attributes is exploring a dedicated supplementary code for digital age verification that would sit within the DVS trust framework as a separate certification layer. To be certified against the supplemental code, a provider must first hold a current DVS trust framework certification. The supplemental code would govern age assurance checks specifically — covering age verification, age estimation, and age inference methods — and explicitly addresses under-16 social media gating (supporting the government's social media age restriction regulations expected to be laid by year-end) and the Licensing Act 2003 update (permitting certified DVS providers for alcohol age checks in England and Wales, coming into effect Autumn 2026). DVS ecosystem context: 46 providers, 64 certified services as of July 2026; BSI and Kantara Initiative confirmed as the two accredited Conformity Assessment Bodies; CertifID UK trust mark launches September 1. OfDIA's 6-week security review of the DVS ecosystem is running concurrently (completing approximately mid-September). For Ditto: the supplemental code creates a market segmentation event — DVS-certified vendors without the age code will be excluded from the age assurance channel at a moment when online age verification is becoming mandatory for alcohol retail, social media, financial services, and adult content. This is a second-mover disadvantage play: vendors that anticipated the supplemental code can certify across both tracks; vendors that certified only for the baseline framework face a second certification cycle. Not in prior deltas (prior deltas tracked September 1 DVS enforcement date, Ofcom enforcement, and Ofcom's Tech Secretary rapid assessment by October, but not this supplemental code development).
  - Source: https://www.biometricupdate.com/202608/uks-ofdia-considering-supplemental-dvs-code-for-age-assurance
  - Date: August 2026

### Pillar 6: LATAM

- **Brazil ANPD publishes definitive Digital ECA Phase II age assurance guidelines — monitoring expands from app stores to all sectors, enforcement starts November 2026 (August 2026)** — Brazil's National Data Protection Authority (ANPD) has published the final definitive guidelines under the Digital ECA framework (Lei 15,211/2025 — Brazil's child online safety law), marking the start of Phase II. Phase I monitoring focused on app stores and proprietary operating systems; Phase II extends supervision to all sectors and groups of providers based on product and service risk levels. Enforcement calendar: administrative sanctions begin November 2026; formal compliance verification begins January 2027. Accepted methods: document verification, biometric age estimation, and CPF-based database checks for Brazilian nationals; the guidelines emphasise data minimisation and privacy-by-design and caution against unconstrained biometric collection. The law applies to any digital product or service accessible to Brazilian minors regardless of the company's location — extraterritorial reach, similar to GDPR. Context: the guidelines follow a June 2026 public consultation on updates; the ANPD is structured as an independent agency, strengthening enforcement credibility. Expected near-term test: Google Play Store's Brazil-specific age verification changes are scheduled for September 2026 and will be the first high-visibility enforcement signal under Phase II. For Ditto: Brazil's Digital ECA Phase II is the LATAM equivalent of Ofcom's July-31 OSA enforcement — any identity vendor with Brazilian fintech or digital-service customers needs CPF-compatible age verification in its stack before November 2026. This is a new market requirement that did not exist six months ago. Not in prior deltas (prior deltas tracked Digital ECA as background context but did not capture Phase II guidelines publication as a datable enforcement event).
  - Source: https://www.biometricupdate.com/202608/brazil-age-assurance-challenge-overlooks-privacy-preserving-options
  - Source: https://eurocloud.org/news/article/the-digital-eca-brazils-new-age-verification-framework-and-enforcement-timeline/
  - Source: https://www.mayerbrown.com/en/insights/publications/2026/04/enforcement-of-brazils-eca-digital-introduces-new-obligations-for-companies
  - Date: August 2026

### Pillar 7: Identity ecosystem

- **Biometrics market consolidation: Precise Biometrics + Fingerprint Cards (FPC) now one entity — multi-modal anti-fraud platform active, rights issue closes August 12 (August 2026)** — Precise Biometrics and Fingerprint Cards have completed their merger, with the combined company operating under the Precise Biometrics brand since July 2026 (FPC is now a product brand within the entity). The combined entity covers face, fingerprint, palm, and iris modalities, positioning it as a multi-modal fraud platform designed for the layered attack surface created by deepfake and synthetic identity fraud. Financial detail: a rights issue of approximately $11.6M (SEK 110M) closes August 12, 2026; expected annual cost synergies of approximately $4.8M (45M SEK), representing 29% of combined 2025 pro forma revenue. For Ditto: the Precise/FPC combination is part of the broader Nordic biometric consolidation trend — alongside Idemia, Thales digital security, and IDEX Biometrics — reducing the number of independent modality vendors and concentrating multi-modal coverage. The market signal for identity ecosystem players: acquirers and large integrators are building multi-modal fraud defense stacks, which means single-modal identity verification is being repositioned as a commodity layer. Vendors with differentiated architecture (split-key, ZKP-backed selective disclosure) maintain positioning above commodity; vendors with one-and-done eKYC are under margin pressure. Not in prior deltas (prior deltas covered Visa×BioCatch $2.4B and Cyera×Oasis $1B for identity M&A but not this Nordic biometrics combination).
  - Source: https://www.biometricupdate.com/202608/merged-precise-biometrics-fpc-can-cover-more-ground-in-tackling-fraud-crisis
  - Source: https://www.fpc.com/investor/more/merger-with-precise-biometrics/
  - Date: July 2026 (merger effective); August 2026 (rights issue close August 12; post-merger profile published)

---

## Next-cycle anchors (updated)

- **PSD3/PSR OJEU publication** — September 2026 tracking window confirmed. ECON committee deadline target was September; no OJEU notice number found as of August 10. Any OJEU notice number is an immediate content trigger.
- **UK DVS Trust Framework 1.0 enforcement (September 1 — 22 days)** — BSI and Kantara Initiative confirmed as the two accredited CABs. CertifID UK trust mark launches September 1. OfDIA 6-week security review completes approximately mid-September. **New**: OfDIA considering supplemental DVS code for age assurance — watch for consultation launch date and timeline. Watch for provider refused certification or UKAS-recognition completion notice.
- **Microsoft Entra passkeys-by-default / SMS-voice OTP retirement (September 1 — 22 days)** — Hard date now <4 weeks. September 18: Microsoft opens Security Store for customer-managed telecom provider configuration (route for orgs that need to retain SMS/voice via third-party). February 1, 2027: full SMS/voice retirement (blocking prompt). Active posting window.
- **OpenAI hardware-backed passkeys mandatory for Trusted Access Cyber members (September 1 — 22 days)** — Partnership with Yubico (YubiKey C NFC and C Nano); access to GPT-5.6 and advanced cyber models reverts to default without hardware passkey compliance.
- **Philippines BSP NIDAS final circular watch** — Draft circular issued August 6-7. Watch for final memorandum circular publication, which starts the 3-month (major banks) / 6-month (smaller institutions) compliance clocks. Any named bank announcing early integration is a case-study signal.
- **EUDI wallet-availability deadline (December 24, 2026 — 136 days)** — Confirmed status: Italy (live), Spain (pilot), Germany (Jan 2, 2027 — 9 days late), Netherlands (likely miss), Malta (partial), Bulgaria (not started). **New angle**: SPRIND sandbox identifies relying-party onboarding as the EU-wide systemic bottleneck — not wallet issuance. Watch for Commission deadline-extension statement or major relying-party (bank, public service) integration announcement.
- **Brazil Digital ECA Phase II enforcement (November 2026)** — Final guidelines published August 2026. Administrative sanctions begin November 2026; formal enforcement begins January 2027. Watch for Google Play Store September 2026 age verification changes in Brazil as the first major enforcement signal.
- **OfDIA supplemental DVS code for age assurance** — Consultation expected to launch. Watch for formal consultation publication date and scope. September 2026 window for first detail.
- **AUSTRAC Tranche 2 enforcement watch** — No Federal Court filing or civil penalty notice as of August 10 (beyond the May 26 Castra $50K penalty). Enrollment deadline was July 29. Watch for first significant civil penalty post-enrollment deadline.
- **Ofcom post-July-31 age-verification enforcement watch** — No named enforcement action beyond the February 2026 Kick Online Entertainment SA £800K fine as of August 10. Ofcom's October rapid assessment to Parliament on "highly effective" age verification for under-16s is the next policy milestone.
- **PSR/FCA consolidation watch** — Financial Services and Markets Bill 2026-27 in Parliament. PSR Q3 APP fraud reimbursement post-implementation review: survey sent to 50 firms in August, report expected Q3 2026. Watch for report publication and any named enforcement action.
- **Visa × BioCatch regulatory approval watch** — Expected to close Visa fiscal Q2 2027. Any competition-authority filing or conditional approval in EU/UK is a content trigger.
- **September NHI/agentic identity sweep** — Cyera×Oasis ($1B), Okta CISO data (58% of CISOs cite AI governance + IAM as biggest agentic concern), Daon three-patent governance series — all pointing to September as the month NHI/agentic identity becomes a mainstream CISO topic. Watch for KuppingerCole Non-Human Identity Management Leadership Compass or EU AI Act GPAI guidance naming agent identity.
- **Mercosur cross-border digital ID (Decision 4/2026)** — Awaiting national-congress ratification in Argentina, Brazil, Paraguay, Uruguay. Agreement finalized at 68th Mercosur Summit (Asunción, June 29, 2026). No ratification news as of August 10.
- **Precise Biometrics rights issue closes August 12** — Watch for post-merger company positioning update and any partnership announcements from the combined entity.

---

## Run summary

- Findings count by pillar: P1 Banking: 0 | P2 EUDI: **1** (SPRIND relying-party bottleneck finding, Aug 2026) | P3 Fraud/Deepfakes: 0 | P4 ZKP: 0 | P5 Passwordless/DVS: **1** (OfDIA supplemental DVS age code, Aug 2026) | P6 LATAM: **1** (Brazil ANPD Digital ECA Phase II guidelines, Aug 2026) | P7 Identity ecosystem: **1** (Precise Biometrics + FPC merger complete, rights issue closes Aug 12) — **Total: 4 findings across 4 pillars**
- Override-worthy: **1** — OfDIA supplemental DVS code for digital age verification: new two-layer certification system announced 22 days before UK DVS Trust Framework 1.0 enforcement. Account:.
- Delta path: research/2026-08-10-cycle-delta.md
