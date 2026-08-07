# Cycle Delta — 2026-08-07

Window: 2026-08-04 → 2026-08-07 (last 72 hours — Friday rule)

Worker note: `ditto-slack-bot.dittobot.workers.dev` continues to return 403 from the session's egress proxy (policy denial, not a credential issue). Skill files sourced from repository baseline and prior deltas. Delta written directly to GitHub via MCP.

---

## Override-worthy this cycle

1. **Philippines central bank mandates NIDAS integration for all supervised banks and e-wallets — government national ID becomes mandatory KYC infrastructure** — The BSP (Bangko Sentral ng Pilipinas) issued a draft circular on August 6-7, 2026 requiring every BSP-supervised institution (banks, e-wallets, VASPs) to integrate with NIDAS (the Philippine Statistics Authority's National ID Authentication Services) for customer due diligence; major retail banks get three months after the final circular, smaller institutions get six. The Philippine Statistics Authority officially welcomed the issuance. Account: / company. Angle: "The Philippines just made government biometric identity verification mandatory for every bank and e-wallet in the country — 120M+ people, one national ID layer, zero optional. This is what government-mandated identity infrastructure looks like at scale. The countries that have already run this play are the ones you benchmark against."

2. **Forbes: Fewer than half of EU member states on track for the December 24 EUDI Wallet deadline — named countries confirmed slipping** — A Forbes synthesis piece published August 5, 2026 documents that Germany (launching January 2, 2027 — nine days late), the Netherlands (likely to miss), Malta (partial functionality only), and Bulgaria (not started as of late 2025) are confirmed delays. A January 2026 assessment found only ~12 of 27 on track. Account: / company. Angle: "The EUDI Wallet deadline is 139 days away and fewer than half of EU member states will make it. Germany is nine days late, the Netherlands likely misses, Malta ships partial. The relying parties that planned around December 24 now have to decide: wait for their member state, or build for the ones that are ready."

---

## New findings

### Pillar 1: Banking & Payments

- **Philippines BSP issues draft circular mandating NIDAS integration for all supervised financial institutions (August 6-7, 2026)** — The Bangko Sentral ng Pilipinas issued a draft circular requiring all BSP-supervised institutions — commercial banks, rural banks, digital banks, e-money issuers, virtual asset service providers, and e-wallets — to integrate with the Philippine Statistics Authority's National ID Authentication Services (NIDAS) for customer due diligence. Under the proposed framework, NIDAS verification (which uses facial recognition, fingerprint scans, and the PhilSys number) replaces the requirement to present physical ID cards at onboarding. Phased timeline: major retail banks with large digital onboarding volumes get three months after the final memorandum circular is issued; smaller institutions get six months. Enforcement mechanism: the BSP warned it may deploy supervisory enforcement actions, including corrective orders, against laggards. GoTyme Bank (a Philippine digital bank) has already integrated its onboarding flow with PhilSys/NIDAS, enabling account opening without physical ID cards. The Philippine Statistics Authority officially welcomed the BSP issuance. For Ditto: the Philippines scenario demonstrates that mandatory government-biometric KYC integration is the logical endpoint for central banks that want to close the paper-document loophole in digital onboarding — and that the primary architecture challenge is integrating government identity rails with bank-side KYC and CDD flows at speed and scale, without a branch network. Not in prior deltas.
  - Source: https://mb.com.ph/2026/08/06/big-banks-digital-lenders-face-first-wave-of-mandatory-national-id-integration
  - Source: https://bworldonline.com/banking-finance/2026/08/07/768645/bsp-wants-banks-to-use-national-id-authentication-in-kyc-processes/
  - Source: https://www.philstar.com/business/2026/08/07/2547472/banks-e-wallets-be-required-link-national-id-says-bsp
  - Source: https://bitpinas.com/regulation/vasp-bank-3month-national-id/
  - Source: https://psa.gov.ph/content/psa-welcomes-bsp-issuance-digital-national-id-acceptance-use-national-id-authentication-financial-transactions
  - Date: 2026-08-06 (draft circular issued); 2026-08-07 (multi-source coverage)

### Pillar 2: EUDI / eIDAS2

- **Forbes: Fewer than half of EU member states on track for December 24 EUDI Wallet deadline — Germany, Netherlands, Malta, Bulgaria confirmed slipping (August 5, 2026)** — A Forbes article (Boaz Sobrado, August 5, 2026) is the first major English-language synthesis documenting the breadth of member-state slippage against the December 24, 2026 EUDI Wallet availability deadline. Key named status updates: Germany's state-run wallet will launch January 2, 2027 — nine days after the legal date — and faces expert doubts about its enabling statute; the Netherlands has signalled it is likely to miss the deadline; Malta expects to launch with only partial functionality; Bulgaria had not started serious work on a wallet as of December 2025 (per Evrotrust chairman statement to Biometric Update). Context: a January 2026 assessment found that only approximately 12 of 27 member states were on track for a functioning wallet by year-end — meaning the majority of the EU will miss the legally mandated date. The article frames the deadline as "visibly slipping" with five months remaining. For Ditto: the confirmed multi-country slippage creates two distinct dynamics: (1) relying parties that scoped integrations for December 24 now face an uneven rollout landscape and must prioritise the compliant member states (Italy is already live, Spain is in pilot); (2) the gap between compliant and non-compliant member states becomes a market-segmentation signal — identity vendors with deployment-ready EUDI Wallet integrations can demonstrate production capability to relying parties in the compliant states while the majority of competitors wait for all 27. The Germany TechTimes piece (August 1) provides additional detail on expert doubts and the missing enabling statute. Not in prior deltas as a multi-country slippage synthesis.
  - Source: https://www.forbes.com/sites/boazsobrado/2026/08/05/you-can-fake-everything-27-nations-race-one-digital-id-deadline/
  - Source: https://www.techtimes.com/articles/322583/20260801/germanys-digital-id-wallet-faces-expert-doubts-missing-statute-before-january-launch.htm
  - Date: 2026-08-05 (Forbes); 2026-08-01 (TechTimes Germany detail)

### Pillar 3: Fraud / Deepfakes

(no new bank deepfake enforcement action, major identity vendor report, or FATF guidance dated 2026-08-05 to 2026-08-07 that is not already in prior deltas. Reality Defender Google selfie bypass, Biometric Update Deepfake Market Report, and iProov 2026 Threat Report all covered in Aug 4-5 deltas. No new in-window print.)

### Pillar 4: ZKPs in practice

(no new bank ZKP pilot, OpenID4VP/VCI deployment announcement, or selective-disclosure mDL milestone dated 2026-08-05 to 2026-08-07. FDD ZKP critical-infrastructure oversight analysis (Aug 4) covered in Aug 6 delta. No new in-window print.)

### Pillar 5: Passwordless / split-key

(no new FIDO Alliance spec release or standalone regulator OTP-sunset announcement dated 2026-08-05 to 2026-08-07. Microsoft Entra passkeys-by-default (September 1) and full SMS/voice retirement (February 1, 2027) remain tracked anchors; new sub-detail: Microsoft opens customer-managed telecom provider details via the Security Store on September 18, 2026 — organisations that need to maintain SMS/voice must configure a third-party provider through that route. OpenAI mandatory hardware-backed passkey for Trusted Access Cyber members (September 1) also tracked; covered in prior deltas as next-cycle anchor. No standalone new in-window print.)

### Pillar 6: LATAM



### Pillar 7: Identity ecosystem

(no new M&A announcement, analyst report (Forrester, KuppingerCole, Gartner, Liminal), or major funding round dated 2026-08-05 to 2026-08-07. Visa×BioCatch $2.4B, Cyera×Oasis $1B, Okta CISO Insights 2026, and Daon patent #3 all covered in Aug 4-5 deltas. No new in-window print.)

---

## Next-cycle anchors (updated)

- **PSD3/PSR OJEU publication** — September 2026 tracking window. Law-firm trackers unchanged. Check each cycle; any OJEU notice number is an immediate content trigger.
- **UK DVS Trust Framework 1.0 enforcement (September 1 — 25 days)** — BSI confirmed as second accredited CAB alongside Kantara Initiative. UK CertifID trust mark launches September 1. OfDIA 6-week security review of DVS ecosystem completes approximately mid-September. Watch for provider refused certification or UKAS-recognition completion notice.
- **Microsoft Entra passkeys-by-default / SMS-voice OTP retirement (September 1 — 25 days)** — Hard date now <4 weeks. September 18: Microsoft opens details on customer-managed telecom providers in Security Store (route for orgs that need to retain SMS/voice via third-party). February 1, 2027: full SMS/voice retirement (blocking prompt).
- **OpenAI hardware-backed passkeys mandatory for Trusted Access Cyber members (September 1 — 25 days)** — Partnership with Yubico (YubiKey C NFC and C Nano); access to GPT-5.6 and advanced cyber models reverts to default without hardware passkey compliance.
- **Ofcom rapid assessment to Parliament (by end-October 2026)** — UK Tech Secretary asked Ofcom to deliver by October a rapid assessment of what "highly effective age verification" looks like for under-16s. Will inform parliamentary debate on social media age restriction regulations intended to be laid by year-end. Content trigger for October: first-party Ofcom definition of "highly effective" will shape DVS Trust Framework demands and could name identity vendors.
- **Philippines BSP NIDAS final circular watch** — Draft circular issued August 6-7. Watch for final memorandum circular publication date, which starts the 3-month (major banks) / 6-month (smaller institutions) compliance clocks. Any named bank announcing GoTyme-style early integration is a case-study signal.
- **EUDI wallet-availability deadline (December 24, 2026 — 139 days)** — Fewer than half of 27 member states confirmed on track. Watch: Italy (live), Spain (pilot), Germany (Jan 2 launch — 9 days late), Netherlands (likely miss), Malta (partial), Bulgaria (not started). Any Commission deadline-extension statement or member-state launch announcement is a content trigger.
- **AUSTRAC Tranche 2 enforcement watch** — No Federal Court filing or civil penalty notice as of August 7 (beyond the May 26 Castra $50K penalty). Watch for first significant civil penalty post-July 1.
- **Ofcom post-July-31 age-verification enforcement watch** — Still no named enforcement action beyond the February 2026 Kick Online Entertainment SA £800K fine. Watch for fresh Ofcom investigation announcement.
- **Visa × BioCatch regulatory approval watch** — Expected to close Visa fiscal Q2 2027. Any competition-authority filing or conditional approval in EU/UK is a content trigger.
- **September NHI/agentic identity sweep** — Cyera×Oasis ($1B), Okta CISO data (58% of CISOs cite AI governance + IAM as biggest agentic concern), Daon three-patent governance series — all pointing to September as the month NHI/agentic identity becomes a mainstream CISO topic. Watch for KuppingerCole NHI Leadership Compass or EU AI Act GPAI guidance naming agent identity as a control.
- **Mercosur cross-border digital ID (Decision 4/2026)** — Awaiting national-congress ratification in Argentina, Brazil, Paraguay, Uruguay.

---

## Run summary

- Findings count by pillar: P1 Banking: **1** (Philippines BSP NIDAS mandate, Aug 6-7) | P2 EUDI: **1** (Forbes multi-country slippage synthesis, Aug 5) | P3 Fraud/Deepfakes: 0 | P4 ZKP: 0 | P5 Passwordless: 0 | P6 LATAM: 0 | P7 Identity ecosystem: 0 — **Total: 2 findings across 2 pillars**
- Override-worthy: **2** — (1) Philippines BSP mandates NIDAS integration for all supervised banks and e-wallets — government national ID becomes mandatory KYC infrastructure, August 6-7; (2) Forbes: fewer than half of EU member states confirmed on track for December 24 EUDI Wallet deadline, August 5.
- Delta path: research/2026-08-07-cycle-delta.md
