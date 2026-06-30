# Cycle Delta — 2026-06-30

Window: 2026-06-28 → 2026-06-30 (last 48 hours — Tuesday run)

## Override-worthy this cycle

1. **MiCA enforcement eve (July 1 tomorrow): only 244 of 3,000+ pre-MiCA crypto firms are now authorised — Poland's 1,400+ legacy registrants produced exactly one MiCA licensee.** Account: / company. Angle: The MiCA single market opens tomorrow, and the conversion math is brutal — ~244 authorised CASPs against 3,000+ pre-MiCA VASP registrations, an ~80% wipeout by the industry's own estimate. Poland is the cleanest microcosm: 1,400+ legacy registrations, one licensed survivor. The dividing line was never size or liquidity (Binance is out; OKX, Kraken, Coinbase, BitGo are in) — it's whether a firm built licensable identity, KYC and compliance infrastructure a regulator will sign off on. That's the moat, and tomorrow is when the market finds out who actually has it.

## New findings

### Pillar 1: Banking & Payments
- **MiCA deadline-eve "wipeout": 244 authorised CASPs vs 3,000+ pre-MiCA VASPs; Poland's 1,400+ registrants yield a single licensee (CoinDesk, June 29, 2026)** — On the eve of the **July 1, 2026** MiCA hard deadline, CoinDesk reported sharper, in-window figures than prior cycles logged: **244 CASPs authorised** across the EU as of June 2026 (up from the ~210 figure tracked through late June), against **3,000+ VASP registrations** that existed pre-MiCA in 2024 (a materially higher denominator than the "1,200+" earlier deltas used). Industry executives — including **OKX Europe's** CEO — estimate **~80% of existing crypto platforms won't survive** the transition. **Poland** is the starkest case: **1,400+** pre-MiCA registrations producing reportedly **one** MiCA licensee, **Morphic Financial Group** (London-HQ'd, Polish operations) — the national-implementation vacuum first logged June 26 now quantified. Named survivors offering continuity/custody alternatives include **BitGo Europe** (BaFin-authorised). ESMA reiterated its call for unauthorised providers to "wind down their businesses in an orderly manner" while protecting clients. For Ditto: the cleanest demand-side proof that MiCA is an identity/KYC/compliance-infrastructure filter — the ~80% being forced out couldn't demonstrate licensable controls, and the survivors are precisely the firms that built them.
  - Source: https://www.coindesk.com/policy/2026/06/29/europe-s-unlicensed-crypto-firms-face-wipeout-as-final-regulatory-deadline-falls
  - Source: https://www.financemagnates.com/cryptocurrency/regulation/europes-crypto-market-after-july-1-who-stays-who-leaves-and-what-changes-under-mica/
  - Date: 2026-06-29
- **Philippines BSP Circular 1213 SMS-OTP hard stop — TODAY (June 30); anchor firing, no in-window compliance data yet** — The BSP Circular 1213 deadline requiring every BSP-supervised bank, e-money issuer and payment operator to stop using SMS/email OTPs for high-risk transactions lands **today, June 30, 2026**, with Deputy Governor Elmore Capule confirming no extension ("As of now we are not extending it, so they have to catch up"). Under AFASA the deadline is a liability shift: institutions without phishing-resistant, device-bound auth (server-side biometrics validated against bank-held templates, or FIDO2/WebAuthn passkeys with device attestation) must reimburse customers for scam losses; compliant institutions get liability protection. No sector-wide compliance-rate figure or BSP enforcement statement published inside the window — expect it in the July 1–2 cluster.
  - Source: https://ipid.tech/blog/bsp-circular-1213-philippines-compliance
  - Source: https://hemosph.com/the-bsp-otp-ban-is-a-liability-shift
  - Date: 2026-06-30 (deadline)

### Pillar 2: Identity orchestration
- **UK Finance bank-led digital ID — new in-window detail: the service is being built on TISA's Select ID marketplace; six named banks confirmed (update to the June 25 story)** — Follow-on in-window coverage answers one of the three open questions flagged in the June 29 delta (who operates/distributes it): the technical layer of the UK Finance bank-led digital verification service is being developed on **Select ID**, the digital-identity marketplace launched in 2024 by TISA (The Investing and Saving Alliance) with backing from Barclays, Visa and Northern Trust. Participating banks now named: **Barclays, HSBC, Lloyds Banking Group, Nationwide, NatWest and Santander**. The service shares only the single verified attribute (name / age / address) needed per transaction, per-transaction consent each time — no document scan. Liability allocation and pricing remain unresolved. For Ditto: confirms the model is an orchestration/marketplace play (a shared trust framework banks plug into), not a single-bank credential — exactly the layer Ditto's platform addresses. Same event as June 25; logged here only for the new operator/participant detail, not as a fresh finding.
  - Source: https://www.biometricupdate.com/202606/major-uk-banks-back-reusable-digital-id-network-for-financial-services
  - Source: https://www.bobsguide.com/uk-lenders-launch-open-standard-digital-id-framework-to-eliminate-kyc-document-friction/
  - Date: 2026-06-25 (announcement) / in-window follow-on detail

### Pillar 3: EUDI / eIDAS2
(no new material in window — ARF remains at v2.x with the late-December 2026 "at least one wallet per member state" deadline unchanged; no discrete Commission/ENISA/member-state announcement confirmed inside June 28–30. Germany DIdG still at cabinet-draft stage with the state-driven EUDI Wallet launch confirmed for January 2, 2027; no Bundestag first-reading date scheduled. Biometric-portrait opt-out implementing rule still has no adopted text.)

### Pillar 4: KYC / AML compliance
(no new material in window — AMLA's three Feb 9 draft RTS remain on track for final-draft submission to the Commission by **July 10, 2026**; AMLR single rulebook applies from July 10, 2027. No new AMLA consultation, FATF publication or sanctions action confirmed inside June 28–30. FATF's seventh targeted update on VA/VASP standards (approved at the June 17–19 plenary) is still due "next month" — July 2026.)

### Pillar 5: Customer onboarding
(no new material in window — no discrete onboarding-KPI benchmark or sector study published inside June 28–30. The UK Finance Select ID detail (P2) is the cycle's onboarding-adjacent item: document-free, consent-based attribute reuse for third-party onboarding.)

### Pillar 6: Identity verification (IDV)
(no new material in window — no new NIST IAL update, iBeta/FIDO Document Authenticity output, or discrete IDV-market move confirmed inside June 28–30. Incode × Identiq remains the most recent IDV M&A, logged June 25/29.)

### Pillar 7: Fraud / Deepfakes
(no new named in-window incident — the Shufti Deepfake Fraud Index (deepfake ID fraud +495% in 2026; document deepfakes +3,900%; synthetic identities 42% of AI fraud) and PYMNTS "banks falling for deepfake borrowers" coverage circulating in-window are republished/earlier-2026 material, already logged. No named-bank deepfake event dated June 28–30 confirmed. Anchor: EU AI Act Art. 50 — July 22 Code-of-Practice signatory deadline / August 2 enforcement.)

### Pillar 8: Mobile trust & app security
(no new material in window — Rokarolla (217 banking/crypto apps, Zimperium) was logged June 29; **OverlayPhantom** (180 apps, 10 countries, accessibility abuse, ID-Austria/TikTok dropper, Cyble) is on-pillar but pre-window — disclosed late May / June 1, 2026 — and is logged here only as a watch item, not a new finding. No mobile-threat report or named SS7/SIM-swap incident dated June 28–30 confirmed.)

### Pillar 9: Passwordless / split-key
(covered under Pillar 1 — BSP Circular 1213's June 30 SMS-OTP hard stop is the live passwordless event firing today; BSP points firms to biometrics, passkeys and adaptive auth. Broader regulator OTP-sunset context (UAE Central Bank March 2026, RBI April 1 2026) is out of window. No new FIDO/passkey-adoption release inside June 28–30.)

### Pillar 10: ZKPs in practice
(no new material in window — no new bank ZKP pilot or OpenID4VP/VCI/mDL deployment confirmed inside June 28–30.)

### Pillar 11: Age assurance & privacy attributes
(no new material in window — no new platform enforcement action or EU age-verification-app update confirmed inside June 28–30. Next hard anchor: **Ofcom's statutory age-assurance effectiveness report, due July 17, 2026**.)

---

## Next-cycle anchors (updated)

- **MiCA CASP hard deadline (July 1)** — TOMORROW; transitional period ends bloc-wide; expect named cease-operations/relocation confirmations and the first post-deadline enforcement posture from ESMA/NCAs.
- **Binance France MiCA application** — Binance confirmed it will not be licensed by June 30 and is pursuing France (existing AMF DASP registration E2022-037); any French CASP licence comes well after July 1, leaving a service gap. Watch the AMF process.
- **Philippines BSP Circular 1213 compliance data** — deadline passed today (June 30); watch July 1–2 for sector compliance-rate data or a BSP enforcement statement.
- **AMLA CDD / sanctions / business-relationship RTS final drafts → Commission (July 10)** — 10 days.
- **FATF seventh targeted update on VA/VASP Standards (July 2026)** — DeFi, stablecoins, unhosted wallets; affects VASP KYC/identity globally.
- **Ofcom statutory age-assurance effectiveness report (July 17)** — 17 days.
- **EU AI Act Code of Practice signatory deadline (July 22)** — 22 days.
- **EU AI Act Article 50 enforcement (August 2)** — 33 days; deepfake labelling, AI-content marking, chatbot disclosure become binding.
- **Germany DIdG Bundestag first reading** — TBD; state-driven EUDI Wallet launch confirmed for January 2, 2027.
- **EUDI Wallet biometric-portrait opt-out implementing rule — formal adoption** — TBD (agreed at Committee June 18).
- **UK People's Panel on Digital ID — report publication** — TBD; deliberation concluded June 21 (Ipsos-run, ~£630K, 100–120 sortition members); directly relevant to the UK Finance bank-led ID / Select ID model (P2).
- **PSR APP-fraud reimbursement independent review report (Q2/Q3 2026)** — watch for publication.
- **PSD3/PSR OJEU publication** — H2 2026, no confirmed date; PSR entry-into-force tracked for Feb–Apr 2026 window (slipping).
- **Japan JSDA phishing-resistant MFA mandatory deadline** — "summer 2026".

---

## Run summary

- Findings count by pillar: P1 Banking: 1 substantive (**MiCA deadline-eve wipeout — 244 CASPs vs 3,000+ VASPs; Poland 1,400→1**) + BSP June 30 anchor firing today | P2 Identity orchestration: 1 update (**UK Finance Select ID / TISA operator detail + 6 named banks** — same June 25 event, new detail) | P3 EUDI: 0 | P4 KYC/AML: 0 | P5 Onboarding: cross-listed P2 | P6 IDV: 0 | P7 Fraud/Deepfakes: 0 new | P8 Mobile trust: 0 new (OverlayPhantom noted as pre-window watch item) | P9 Passwordless: cross-listed P1 (BSP) | P10 ZKP: 0 | P11 Age assurance: 0 — **Total: 1 substantive in-window finding + 1 incremental update; BSP anchor firing today**
- Override-worthy: **1** — MiCA enforcement eve (244 of 3,000+ firms authorised; Poland's 1,400+ registrants produced one licensee), the day-before-deadline quantification of the single-market wipeout. Binance's EU exit (yesterday's override) remains the named hook.
- Delta path: research/2026-06-30-cycle-delta.md
- Note: thin, anchor-cluster cycle as forecast — the substantive news is the July 1 MiCA deadline and today's BSP OTP hard stop, both anchors rather than fresh discoveries. Expect the July 1 (Wed) and July 2 (Thu) cycles to carry named CASP cease-operations confirmations and BSP compliance data. Did not pad: shipping 1 strong finding + 1 update over manufacturing thin items.
