# Cycle Delta — 2026-07-03

Window: 2026-06-30 → 2026-07-03 (last 72 hours — Friday run, weekend-extended). Note: 2026-06-30 → 2026-07-02 was already covered by the June 30–July 2 deltas; the fresh in-window cluster this cycle is the **July 2 ID Tech digest** (yesterday's delta was built off the July 1 digest), plus scans for any July 2–3 primary-source material.

## Override-worthy this cycle

1. **The dominant IDV attack vector has flipped from presentation attacks to digital injection attacks — synthetic deepfake streams fed straight into the onboarding API, bypassing the device camera entirely (Unico network data, July 2).** Account: company /. Angle: The whole "hold your face up to the camera" liveness model is being outflanked. Injection attacks never touch the optical sensor — they inject a pre-recorded or AI-generated video into the API pipeline, so camera-side presentation-attack detection is blind to them. The structural answer is device-integrity attestation + server-side liveness, not prettier selfie UX. This is the fraud-side proof of the "document/selfie checks are commoditising, assurance moves up the stack" thesis — and a clean POV hook for Ditto Verify's anti-injection posture. Cite the trend (injection attacks now the primary remote-IDV vector), never the vendor.

## New findings

### Pillar 1: Banking & Payments
(no new discrete in-window item. MiCA CASP transitional period closed July 1 and remains the live anchor — ESMA/NCA coordinated wind-down enforcement now active, penalties to €15M or 12.5% of annual revenue under Art. 111, ~14 licensed exchanges / 40+ full CASP authorisations; France's AMF ran a targeted enforcement sweep against continuing unlicensed operators. All covered in the July 1–2 deltas. PSD3/PSR: ECON confirmed (May 18) it will recommend second-reading adoption without amendment if Council transmits its current position; OJEU publication still expected H2 2026 — no confirmed date inside June 30–July 3. No new EBA/ECB/DORA publication confirmed in window.)

### Pillar 2: Identity orchestration
- **authID certified into the Microsoft Entra Verified ID partner ecosystem — facial-biometric IDV becomes a plug-in to Microsoft's decentralised-identity / verifiable-credential rails, with no raw template storage (July 2, 2026)** — Biometric-authentication vendor **authID** achieved formal certification as a **Microsoft Entra Verified ID** integration partner, letting enterprises embed authID's facial-biometric verification directly into Microsoft's decentralised-identity workflows as "automated, phishing-resistant" tooling for Zero Trust frameworks, without storing raw biometric templates. For Ditto: this is the orchestration-convergence thesis playing out on the largest possible platform — a biometric IDV specialist is no longer selling a standalone stack, it's becoming a composable component inside Microsoft's verifiable-credential orchestration layer. The value migrates to whoever governs the composition (which credential formats, which trust framework, which relying-party obligations, who owns liability) — the layer Ditto occupies. Reinforces the Jumio×Trinsic (June 25) and Experian Identity Connect (July 1) pattern: incumbents and specialists converging on credential-acceptance + orchestration. Cross-listed P6, P9. Ecosystem/competitive datapoint — critique the pattern (IDV commoditising into platform-orchestrated components), never name the vendor.
  - Source: https://idtechwire.com/id-tech-digest-july-2-2026/
  - Date: 2026-07-02

### Pillar 3: EUDI / eIDAS2
(no new discrete in-window item. Hard anchor unchanged: every member state must offer at least one certified EUDI Wallet by **December 6, 2026**; regulated sectors (banking, healthcare, telecom, transport, energy) must accept it by end-2027. France Identité, Austria eAusweise and Italy IT-Wallet live and absorbing certified private wallets (Namirial/France Identité, July 1 delta). Germany DIdG → January 2, 2027 launch. No new ARF update, Commission implementing act, or ENISA certification announcement confirmed inside June 30–July 3.)

### Pillar 4: KYC / AML compliance
(no new material in window. AMLA package on track for final-draft RTS submission to the Commission by **July 10, 2026** (7 days); AMLR/AMLD6 apply from July 10, 2027; ~23 Level-2/3 measures due through 2026. FATF seventh targeted update on VA/VASP standards (approved June 17–19 plenary) still due July 2026. No new AMLA consultation, FATF publication, or named sanctions action confirmed inside June 30–July 3.)

### Pillar 5: Customer onboarding
(no new discrete onboarding-KPI benchmark or sector study published inside June 30–July 3. The onboarding-adjacent signal this cycle is the Unico injection-attack data (P7/P6) — it reframes the onboarding-fraud threat model: the friction-reduction race (fewer document uploads, faster selfie capture) is exactly the surface injection attacks exploit, so lower friction without device-integrity + server-side liveness raises onboarding-fraud exposure.)

### Pillar 6: Identity verification (IDV)
- **Digital injection attacks now the dominant remote-IDV threat vector, displacing physical presentation attacks — synthetic/deepfake video injected straight into the onboarding API (Unico network data, July 2, 2026)** — See override #1 and P7 for full detail. IDV-pillar read: **Unico**'s classified fraud data shows injection attacks have overtaken presentation attacks as the primary vector against remote identity verification — the attack bypasses the device camera and feeds a pre-recorded or synthetic deepfake stream directly into the API onboarding pipeline, which camera-side presentation-attack detection cannot see. Unico's prescribed mitigation is **device-integrity validation + server-side liveness**. Corroborating industry datapoint circulating the same window: only ~3 of the top-20 global biometric vendors hold certifications capable of detecting injection attacks, against deepfake-assisted onboarding fraud reportedly up ~300%. Leading indicator that IDV assurance is bifurcating — commodity selfie/document capture below, injection-resistant + server-side-liveness verification above (Ditto Verify's layer). Cross-listed P7.
  - Source: https://idtechwire.com/id-tech-digest-july-2-2026/
  - Source: https://www.threatmark.com/latam-digital-fraud/
  - Date: 2026-07-02
- **authID → Microsoft Entra Verified ID certified integration (cross-listed from P2)** — See P2. IDV read: a facial-biometric verification vendor becoming a certified plug-in inside Microsoft's verifiable-credential ecosystem, template-free — another signal that standalone biometric IDV is being absorbed into platform-orchestrated credential rails, and the differentiation moves to the orchestration + assurance layer above the individual check.
  - Source: https://idtechwire.com/id-tech-digest-july-2-2026/
  - Date: 2026-07-02
- **(Minor / education vertical) UK Maritime and Coastguard Agency deploys automated biometric proctoring for remote seafarer certification exams — continuous facial tracking, gaze detection, voiceprint monitoring (July 2, 2026)** — Credential-exam integrity via multimodal biometrics in a UK government remote-certification context. On-pillar only as a leading-indicator that biometric identity + integrity checks are industrialising into regulated credentialing (education/credential-security flavour), not a core IDV market move. Watch-item, not a headline.
  - Source: https://idtechwire.com/id-tech-digest-july-2-2026/
  - Date: 2026-07-02

### Pillar 7: Fraud / Deepfakes
- **Injection attacks displace presentation attacks as the #1 remote-IDV fraud vector — deepfake streams injected into the onboarding API, camera bypassed (Unico network data, July 2, 2026)** — **Unico** reports that digital injection attacks have become the dominant vector targeting remote identity-verification systems, replacing traditional physical presentation attacks; the technique feeds a pre-recorded or synthetic deepfake video directly into the API onboarding pipeline, bypassing the device camera so that camera-side presentation-attack detection is structurally blind. Prescribed defence: device-integrity validation + server-side liveness. For Ditto: this is a fraud-model shift, not an incremental stat — it invalidates "we do liveness" claims that rely solely on the capture device, and validates the anti-injection / server-side-verification posture Ditto Verify is built around. Strong POV material (fraud-side proof that verification assurance must move above the device). Cite the trend, not the vendor. Cross-listed P6.
  - Source: https://idtechwire.com/id-tech-digest-july-2-2026/
  - Date: 2026-07-02
- (Context, out-of-window — not a new finding) Circulating deepfake-fraud projections remain the Shufti Identity Fraud Index (up to ~495% deepfake identity-fraud growth / ~3,892% document-deepfake growth projected for 2026; covered June 26 delta) and PYMNTS synthetic-borrower reporting (covered June 30 delta). No new named-bank deepfake incident dated June 30–July 3 confirmed. Anchor: EU AI Act Art. 50 — July 22 CoP signatory deadline / August 2 deepfake-labelling enforcement.

### Pillar 8: Mobile trust & app security
(no new named Android-malware family or SS7/SIM-swap breach dated June 30–July 3 confirmed. Landscape unchanged: Anatsa (650+ FIs, overlay/keylogging/device-takeover, NFC-relay increasingly bundled), ToxicPanda, RatOn, NGate/NFCShare NFC-relay families remain active per 2026 threat-intel, but no in-window disclosure this cycle. Note: the Unico injection-attack data (P7) is device-side-relevant — device-integrity attestation is the shared mitigation between mobile-trust and injection-resistant IDV.)

### Pillar 9: Passwordless / split-key
- **authID's Microsoft Entra Verified ID integration framed explicitly as "phishing-resistant" biometric auth for Zero Trust (cross-listed from P2, July 2, 2026)** — Minor/on-pillar: the passwordless-adjacent read is that phishing-resistant biometric authentication is being packaged as a certified component of Microsoft's decentralised-identity stack, reinforcing the regulatory/architectural direction of travel (phishing-resistant auth as default, OTP sunsets) that the BSP Circular 1213 hard stop and Yubico×ECSO policy move (prior deltas) exemplify. No new FIDO spec, passkey-adoption stat, or regulator OTP-sunset publication confirmed inside June 30–July 3. Ecosystem/policy datapoint (do not name in posts).
  - Source: https://idtechwire.com/id-tech-digest-july-2-2026/
  - Date: 2026-07-02

### Pillar 10: ZKPs in practice
- **Walmart hit with Illinois BIPA class action over call-centre voiceprints — biometric captured/stored without consent (July 2, 2026)** — A class action alleges **Walmart**'s interactive-voice-response customer-service lines violate Illinois's **Biometric Information Privacy Act (BIPA)** by extracting, analysing and storing unique voiceprint characteristics from inbound callers without consent or retention disclosure. On-pillar as a privacy-by-design proof point: it is a concrete, dated example of the *liability of holding raw biometric templates* — precisely the exposure that ZKP / selective-disclosure / template-free architectures (Ditto's privacy-first posture) are designed to remove. Ties to authID's "no raw template storage" framing (P2) as the same market pressure from two directions (litigation risk + platform expectation). No new bank ZKP pilot or OpenID4VP/VCI deployment confirmed in window (ZKP compliance-reporting pilots still tracking toward late-2026 production readiness per prior deltas). Cross-listed P11.
  - Source: https://idtechwire.com/id-tech-digest-july-2-2026/
  - Date: 2026-07-02

### Pillar 11: Age assurance & privacy attributes
- **Walmart BIPA voiceprint class action (cross-listed from P10)** — See P10. Privacy-attributes read: fresh, dated evidence that biometric-data-retention liability is live in US courts — a data-minimisation argument for privacy-preserving attribute checks over raw biometric capture-and-store. No new platform age-assurance enforcement action or EU age-verification-app update confirmed inside June 30–July 3. Hard anchors unchanged: **Ofcom statutory age-assurance effectiveness report due end-July (≈July 17–31, 2026)**; enforcement to date totals £125k in information-request fines (4chan £20k; Itai Tech £55k; AVS Group £50k) plus a £1M fine to AVS Group for failing to implement "highly effective" age assurance — evidence Ofcom is now moving from information requests to substantive age-assurance penalties.
  - Source: https://idtechwire.com/id-tech-digest-july-2-2026/
  - Source: https://natlawreview.com/article/whats-coming-over-hill-ofcoms-heavy-fines-age-assurance-failures
  - Date: 2026-07-02

---

## Next-cycle anchors (updated)

- **AMLA CDD / sanctions / business-relationship RTS final drafts → Commission (July 10)** — 7 days.
- **FATF seventh targeted update on VA/VASP Standards (July 2026)** — DeFi, stablecoins, unhosted wallets.
- **Ofcom statutory age-assurance effectiveness report (end-July, ≈July 17–31)** — watch for publication; Ofcom already levying substantive "highly effective age assurance" fines (£1M AVS Group).
- **UK Online Safety Act "highly effective age assurance" milestone (~July 25, per legal analysis)** — confirm exact obligation/date.
- **EU AI Act Code of Practice signatory deadline (July 22)** — 19 days.
- **FSB AI Sound Practices consultation deadline (July 22)** — 19 days; final report to G20 October 2026.
- **EU AI Act Article 50 enforcement (August 2)** — 30 days; deepfake labelling, AI-content marking, chatbot disclosure become binding.
- **UK DVS Trust Framework 1.0 enforcement (September 1)** — 60 days; first conformity-assessment-body accreditation; OSP certification active; UK CertifID trust mark.
- **MiCA post-deadline enforcement** — watch for first named ESMA/NCA action against a continuing unlicensed cross-border CASP; Binance France AMF application timeline.
- **Philippines BSP Circular 1213 compliance data** — post-June-30 compliance rate / first enforcement statement still pending.
- **US AI AGENT Act (Warner)** — watch for formal introduction / committee referral and any FTC-registration mandate for custodial AI agents.
- **EU Entry-Exit System (EES) summer operations** — airlines/airports requesting temporary suspension authority over biometric border checks; watch Commission response.
- **EUDI wallet member-state deadline** — at least one certified wallet per member state by December 6, 2026; France/Austria/Italy live; Germany January 2, 2027.
- **PSD3/PSR OJEU publication** — H2 2026, no confirmed date (may slip to September); ECON will recommend second-reading adoption without amendment on current Council text.
- **PSR APP-fraud reimbursement independent review report (Q2/Q3 2026)** — watch for publication.
- **Japan JSDA phishing-resistant MFA mandatory deadline** — "summer 2026".
- **Injection-attack detection certification** — new watch item; only ~3 of top-20 biometric vendors reportedly certified to detect injection attacks — watch for iBeta/lab certification schemes or NIST/FIDO guidance on injection-attack resistance.

---

## Run summary

- Findings count by pillar: P1 Banking: 0 new (MiCA anchor live) | P2 Identity orchestration: **1 new** (authID → Microsoft Entra Verified ID certified integration) | P3 EUDI: 0 | P4 KYC/AML: 0 | P5 Onboarding: cross-listed P7 | P6 IDV: **2** (Unico injection-attack dominance cross-list; authID cross-list) + 1 minor (UK Maritime biometric proctoring) | P7 Fraud/Deepfakes: **1 new** (injection attacks displace presentation attacks — Unico) | P8 Mobile trust: 0 new | P9 Passwordless: cross-listed P2 | P10 ZKP: **1 new** (Walmart BIPA voiceprint class action) | P11 Age assurance/privacy: **1** (Walmart BIPA cross-list) — **Total: 4 new in-window findings across 4 pillars (P2, P6/P7, P10) + 1 minor**
- Override-worthy: **1** — Injection attacks have displaced presentation attacks as the dominant remote-IDV fraud vector (deepfake injected into the onboarding API, device camera bypassed; device-integrity + server-side liveness is the structural fix — Ditto Verify territory). Account: company /.
- Delta path: research/2026-07-03-cycle-delta.md
- Note: fresh cluster is the July 2 ID Tech digest (Unico injection-attack data; authID×Microsoft Entra Verified ID; Walmart BIPA voiceprint; UK Maritime proctoring). No July 3 digest published yet at run time (early ET). Government foundational-ID / surveillance items in the July 2 digest (Honduras fingerprint, Somalia passport-to-ID, Lagos facial-recognition) excluded as outside Ditto's regulated-enterprise ICP. Deepfake-fraud projection reports (Shufti, PYMNTS) checked and excluded as out-of-window (June deltas).
