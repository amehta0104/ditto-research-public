# Cycle Delta — 2026-07-01

Window: 2026-06-29 → 2026-07-01 (last 48 hours — Wednesday run)

## Override-worthy this cycle

1. **MiCA's transitional period ends TODAY (July 1): the deadline the last two cycles previewed is now live, and the AMF has put criminal prosecution behind it — unlicensed firms serving EU customers after today face prosecution, not just wind-down letters.** Account: / company. Angle: The eve-of-deadline math (244 authorised CASPs vs 3,000+ pre-MiCA registrants; Binance out; Poland 1,400→1) is now the reality, and France's AMF president Marie-Anne Barbat-Layani has said firms that keep serving EU customers without a licence face **criminal prosecution** — the enforcement teeth are real. The single market opens to whoever built licensable identity, KYC and compliance infrastructure and closes to everyone who didn't. That's the moat, and today is the day it gets tested.

2. **Network-layer identity goes mainstream in France: Bouygues Telecom joins Aduna (the Ericsson-founded telco JV) to sell carrier-level, silent identity verification and SIM-swap defence via CAMARA network APIs — a fresh alternative to the document-and-selfie stack.** Account:. Angle: While document-and-selfie IDV buckles under deepfakes, a parallel model is scaling — the network operator answering true/false questions ("did this SIM change recently?", "does this number match this line?") invisibly at the carrier layer, no user friction. It's an orchestration story: banks and fintechs now have another signal source to compose into onboarding and step-up. Ditto's platform is the layer that orchestrates these signals; the news is that the signals are proliferating.

## New findings

### Pillar 1: Banking & Payments
- **MiCA transitional period ends July 1 (TODAY) — deadline live; AMF confirms criminal prosecution for unlicensed firms that keep serving EU customers** — The bloc-wide MiCA hard deadline the June 29/30 deltas previewed is now in force. As of the run, ~244 CASPs are authorised against 3,000+ pre-MiCA VASP registrations (under-18% conversion by the widely-cited denominator); ESMA holds firm on no extensions. New in-window enforcement detail: France's **AMF** has instructed unlicensed crypto firms to cease operations from July 1, and AMF president **Marie-Anne Barbat-Layani** warned that companies continuing to serve EU customers without a licence after the deadline face **criminal prosecution** — under MiCA Art. 111, penalties reach €5M for individuals and up to 12.5% of annual turnover for legal entities, plus permanent bans and register removal. Unlicensed entities' five options: license, stop, orderly wind-down, transfer clients to an authorised CASP, or merge. Same event as the June 29/30 override (Binance exit / 244-vs-3,000 math); logged here for the deadline-day transition and the AMF criminal-prosecution posture, not as a fresh discovery. For Ditto: the demand-side proof that MiCA is an identity/KYC/compliance filter is now live, with criminal liability behind it.
  - Source: https://finance.yahoo.com/markets/crypto/articles/july-1-mica-deadline-looms-103215096.html
  - Source: https://www.pymnts.com/cryptocurrency/2026/july-1-mica-deadline-threatens-thousands-of-european-crypto-firms/
  - Date: 2026-07-01 (deadline) / AMF prosecution warning in-window
- **Philippines BSP Circular 1213 SMS-OTP hard stop passed June 30 — no in-window sector compliance data yet** — The BSP Circular 1213 deadline requiring every BSP-supervised bank, e-money issuer and payment operator to stop using SMS/email OTPs for high-risk transactions passed **June 30, 2026** with no extension (Deputy Governor Elmore Capule: "we are not extending it"). Under AFASA the deadline is a liability shift — non-compliant institutions must reimburse scam losses; compliant ones get liability protection. As of this run no sector-wide compliance-rate figure or BSP enforcement statement has been published inside the window. Anchor firing; watch July 1–3 for the first compliance data. (See P9 for the passwordless/passkey angle.)
  - Source: https://ipid.tech/blog/bsp-circular-1213-philippines-compliance
  - Date: 2026-06-30 (deadline)

### Pillar 2: Identity orchestration
- **Bouygues Telecom joins Aduna to offer network-based identity verification and SIM-swap defence via CAMARA APIs (June 30, 2026)** — French operator **Bouygues Telecom** joined **Aduna** — the Ericsson-founded joint venture backed by major global telcos — to expose three network APIs (identity verification and fraud prevention) to banking, insurance, e-commerce and social platforms. Built on the **GSMA CAMARA** open-standard framework, the model matches real-time SIM cryptographic tokens and network-routing telemetry at the carrier layer to answer simple true/false questions — e.g. the date of a subscriber's last SIM-card change, or whether a mobile number matches its line — stopping **SIM-swap fraud and account takeover** during high-stakes financial transactions with no end-user friction. For Ditto: a fresh, fast-scaling identity signal source that composes into onboarding and step-up alongside document/biometric checks — an orchestration-layer story (more signals to unify), and a mobile-trust one (silent anti-SIM-swap). Cross-listed P8/P9.
  - Source: https://idtechwire.com/bouygues-telecom-joins-aduna-to-offer-network-based-identity-services/
  - Source: https://adunaglobal.com/newsroom/aduna-and-bts-partner-to-tackle-fraud-prevention-and-identity-verification/
  - Date: 2026-06-30
- **Hopae integrates India's digital-identity stack into its Hopae Connect orchestration platform (June 30, 2026)** — Orchestration vendor **Hopae** added India's digital-identity components to Hopae Connect, letting enterprises verify credentials against India's public identity infrastructure to simplify cross-border corporate onboarding and compliance. Minor but on-pillar: the orchestration layer is where national identity stacks get plugged into enterprise onboarding — the same integration problem Ditto's platform addresses. Ecosystem datapoint (do not name in posts).
  - Source: https://idtechwire.com/id-tech-digest-june-30-2026/
  - Date: 2026-06-30

### Pillar 3: EUDI / eIDAS2
- **Romania will build its national EUDI Wallet (RoEUDIW) on Germany's open-source architecture — first named cross-border reuse of a member-state wallet stack (June 30, 2026)** — Romania announced it will adopt **Germany's open-source EUDI Wallet solution** for its national wallet (RoEUDIW), following "a rigorous evaluation of EUDI Wallet solutions at various implementation stages in other member states," explicitly to cut cost and avoid building complex infrastructure from scratch ahead of the **end-2026** "at least one wallet per member state" deadline. RoEUDIW will store national ID, driving licence, diplomas and health card with selective disclosure and user-held data control; Romania's Ministry of Internal Affairs will provide the app and issue the PID. For Ditto: a concrete signal that the EUDI wallet layer is consolidating onto shared open-source stacks (Germany's model as a de-facto reference implementation) — the credential/wallet becomes commoditised infrastructure, and the differentiated value moves up to orchestration, relying-party integration and trust-framework compliance, which is Ditto's layer. Ties to the confirmed **January 2, 2027** German state-driven wallet launch tracked in prior deltas.
  - Source: https://www.biometricupdate.com/202606/romania-chooses-german-eudi-wallet-for-national-customization
  - Source: https://www.romania-insider.com/romania-digital-wallet-german-solution-june-2026
  - Date: 2026-06-30

### Pillar 4: KYC / AML compliance
(no new material in window — AMLA's three Feb 9 draft RTS remain on track for final-draft submission to the Commission by **July 10, 2026** (9 days); AMLR single rulebook applies from July 10, 2027. FATF's seventh targeted update on VA/VASP standards (approved June 17–19 plenary) still due "next month" — July 2026. No new AMLA consultation, FATF publication or named sanctions action confirmed inside June 29–July 1.)

### Pillar 5: Customer onboarding
(no new material in window — no discrete onboarding-KPI benchmark or sector study published inside June 29–July 1. The onboarding-adjacent items this cycle are the network-API signal source (P2, Bouygues/Aduna) and the mDL certification scheme (P6, Fime), both of which reduce document-upload friction in third-party onboarding.)

### Pillar 6: Identity verification (IDV)
- **Fime launches an mDL certification scheme against ISO/IEC 18013-5:2021 + 18013-7:2025 — first of a planned family of digital-identity certification schemes (June 30, 2026)** — Testing and certification specialist **Fime** launched a **mobile driving licence (mDL) certification scheme** validating wallet providers, reader providers and governments against **ISO/IEC 18013-5:2021** and **ISO/IEC TS 18013-7:2025**, covering both in-person and remote mDL presentation, with governance aligned to ISO/IEC 17065 and testing under ISO/IEC 17025. Fime frames it as a response to the industry "moving quickly from fragmented pilots to large-scale deployments, where trust and interoperability are critical." For Ditto: independent, standards-based certification infrastructure is a leading indicator that mDL/verifiable-credential verification is industrialising — the market is shifting from "can we do liveness" to "can we prove interoperability and trust at scale," which is the higher-assurance verification layer Ditto Verify plays in. Cross-listed P10 (mDL selective disclosure / ISO 18013-5).
  - Source: https://www.fime.com/blog/news-21/post/fime-launches-mobile-driving-license-mdl-certification-scheme-711
  - Source: https://idtechwire.com/fime-launches-certification-scheme-for-mobile-drivers-licenses/
  - Date: 2026-06-30

### Pillar 7: Fraud / Deepfakes
(no new named in-window incident — the circulating deepfake-fraud coverage (Shufti Deepfake Fraud Index; synthetic ID now #1 fraud threat; PYMNTS "banks falling for deepfake borrowers") is earlier-2026/republished material already logged in prior deltas. No named-bank deepfake event dated June 29–July 1 confirmed. Anchor: EU AI Act Art. 50 — July 22 Code-of-Practice signatory deadline / August 2 enforcement of deepfake labelling.)

### Pillar 8: Mobile trust & app security
- **Network-layer anti-SIM-swap goes commercial in France (Bouygues Telecom × Aduna) — cross-listed from P2** — The carrier-layer identity/fraud-prevention APIs Bouygues Telecom is exposing via Aduna (CAMARA) directly target **SIM-swap fraud and account takeover** at the network signalling layer — the same attack surface that the accessibility-abusing banking trojans logged in prior deltas (Rokarolla, OverlayPhantom) exploit downstream. The mobile-trust thesis reads both sides: malware intercepts OTPs on-device; network APIs verify SIM/line integrity off-device. No new named Android-malware family or SS7/SIM-swap breach dated June 29–July 1 confirmed this cycle. (Full detail in P2.)
  - Source: https://idtechwire.com/bouygues-telecom-joins-aduna-to-offer-network-based-identity-services/
  - Date: 2026-06-30

### Pillar 9: Passwordless / split-key
- **Singpass adds device-biometric passkey login — Singapore's national digital ID moves off SMS OTP (June 30, 2026)** — Singapore's **Singpass** national digital-identity platform added **passkey** support, letting citizens access government services with on-device face or fingerprint hardware, eliminating SMS one-time passwords and cutting phishing exposure. For Ditto: a national-scale datapoint on the exact OTP-sunset trajectory the BSP Circular 1213 hard stop (P1, June 30) is forcing on Philippine banks — device-bound, phishing-resistant auth is becoming the default at the population level, not just a regulator mandate. Reusable as the "this is where authentication is going, everywhere" companion to the OTP-ban regulatory story. (BSP OTP hard stop cross-listed from P1.)
  - Source: https://idtechwire.com/id-tech-digest-june-30-2026/
  - Date: 2026-06-30
- **BSP Circular 1213 SMS-OTP hard stop (June 30) — the live passwordless regulatory event; cross-listed from P1.** BSP points firms to biometrics, FIDO passkeys and adaptive auth. No new FIDO/passkey-adoption release inside June 29–July 1 (FIDO's World Passkey Day 2026 figures — 5B passkeys, 90% awareness — and the Agentic Authentication WG are out of window, logged earlier).

### Pillar 10: ZKPs in practice
(no standalone new material in window — the Fime mDL certification scheme (P6) is the cycle's ZKP/selective-disclosure-adjacent item: ISO/IEC 18013-5/18013-7 mDL verification is the transport for selective-disclosure credential presentation. No new bank ZKP pilot or OpenID4VP/VCI deployment confirmed inside June 29–July 1.)

### Pillar 11: Age assurance & privacy attributes
(no new platform enforcement action or EU age-verification-app update confirmed inside June 29–July 1. South Korea's June 30 move to formalise optional facial-recognition (with mandatory liveness) for mobile-phone subscriber sign-up is IDV/age-adjacent but not core age-assurance policy — noted as a watch item only. Next hard anchor: **Ofcom's statutory age-assurance effectiveness report, due July 17, 2026**.)

---

## Next-cycle anchors (updated)

- **MiCA CASP deadline — LIVE (July 1 today)** — transitional period ended bloc-wide; AMF criminal-prosecution posture confirmed. Watch July 1–4 for named cease-operations/relocation confirmations and the first post-deadline NCA/ESMA enforcement actions.
- **Binance France MiCA application** — Binance is out of the EU as of today, pursuing an AMF licence (existing DASP registration E2022-037); any French CASP licence lands well after July 1. Watch the AMF process.
- **Philippines BSP Circular 1213 compliance data** — deadline passed June 30; watch July 1–3 for sector compliance-rate data or a BSP enforcement statement.
- **AMLA CDD / sanctions / business-relationship RTS final drafts → Commission (July 10)** — 9 days.
- **FATF seventh targeted update on VA/VASP Standards (July 2026)** — DeFi, stablecoins, unhosted wallets.
- **Ofcom statutory age-assurance effectiveness report (July 17)** — 16 days.
- **EU AI Act Code of Practice signatory deadline (July 22)** — 21 days.
- **EU AI Act Article 50 enforcement (August 2)** — 32 days; deepfake labelling, AI-content marking, chatbot disclosure become binding.
- **Germany DIdG Bundestag first reading** — TBD; state-driven EUDI Wallet launch confirmed January 2, 2027; now also the open-source reference stack for Romania's RoEUDIW (P3) — watch for further member-state adoptions.
- **EUDI Wallet biometric-portrait opt-out implementing rule — formal adoption** — TBD (agreed at Committee June 18).
- **UK People's Panel on Digital ID — report publication** — TBD; deliberation concluded June 21; relevant to the UK Finance bank-led ID / Select ID model.
- **UK Finance bank-led digital ID / TISA Select ID** — watch for operator/liability/pricing resolution (six banks named: Barclays, HSBC, Lloyds, Nationwide, NatWest, Santander).
- **PSR APP-fraud reimbursement independent review report (Q2/Q3 2026)** — watch for publication.
- **PSD3/PSR OJEU publication** — H2 2026, no confirmed date.
- **Japan JSDA phishing-resistant MFA mandatory deadline** — "summer 2026".

---

## Run summary

- Findings count by pillar: P1 Banking: MiCA deadline-day (anchor firing + AMF criminal-prosecution posture) + BSP June 30 passed (anchor, no compliance data yet) | P2 Identity orchestration: **2 new** (Bouygues×Aduna network-identity/CAMARA; Hopae India stack) | P3 EUDI: **1 new** (Romania → Germany open-source RoEUDIW) | P4 KYC/AML: 0 | P5 Onboarding: cross-listed P2/P6 | P6 IDV: **1 new** (Fime mDL certification scheme) | P7 Fraud/Deepfakes: 0 new | P8 Mobile trust: cross-listed P2 (network anti-SIM-swap) | P9 Passwordless: **1 new** (Singpass passkey) + BSP cross-ref | P10 ZKP: cross-listed P6 | P11 Age assurance: 0 (South Korea facial-rec noted as watch item) — **Total: 5 new in-window findings across 4 pillars + MiCA/BSP anchors firing**
- Override-worthy: **2** — (1) MiCA transitional period ends today with AMF criminal-prosecution teeth; (2) network-layer identity goes commercial in France (Bouygues × Aduna / CAMARA) as a fresh orchestration angle.
- Delta path: research/2026-07-01-cycle-delta.md
- Note: healthier cycle than June 30's — the June 30 ID-Tech cluster (Romania EUDI, Bouygues/Aduna, Singpass passkey, Fime mDL) delivered four genuinely fresh, on-pillar, in-window findings alongside the MiCA/BSP anchors landing today. Vouched IAL2 (Kantara, June 23) and Facephi Mexico +77% (2024 CONDUSEF data) checked and excluded as out-of-window.
