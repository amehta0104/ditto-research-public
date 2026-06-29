# Cycle Delta — 2026-06-29

Window: 2026-06-26 → 2026-06-29 (last 72 hours — Monday run, weekend window Fri→Mon)

## Override-worthy this cycle

1. **Binance tells EU users it will cease all crypto services after failing to secure a MiCA licence — the first named major CASP exit, two days before the July 1 hard deadline.** Account: / company. Angle: MiCA's licensing wall just claimed the biggest name in crypto. The line between who stays and who leaves the EU on July 1 isn't size or liquidity — it's whether you built the identity, KYC and compliance infrastructure a regulator will license. That's the real moat, and most of the ~80% who didn't convert never had it.
2. **UK Finance confirms major UK banks completed proof-of-concept for a bank-led digital identity service — the BankID model (99% adoption in Sweden) finally reaches the UK, arriving exactly as document-and-selfie checks buckle under deepfakes.** Account: / company /. Angle: bank-led digital ID works where it's been tried — 99% of Swedish adults, 97% Norwegian, 80% on Belgium's itsme. The UK's open question isn't the credential, it's the orchestration layer: who owns liability when a relying party trusts a bank-issued attribute, and who pays when open-banking data is already free. That's the layer Ditto sells.

## New findings

### Pillar 1: Banking & Payments
- **Binance notifies EU users it will suspend all crypto-asset services from July 1 after failing to obtain a MiCA licence; will pursue authorization in France (June 25–26, 2026)** — Binance emailed customers in France, Italy, Poland and Spain (and across the bloc) that it will halt new registrations and stop providing crypto-asset services in the EU ahead of the **July 1, 2026** MiCA hard deadline, telling users their assets "remain safe and secure, and will remain accessible at all times" during an orderly wind-down. Having withdrawn its MiCA application in **Greece on June 24** (logged in the June 26 delta as "next jurisdiction not yet named"), Binance has now confirmed it will instead seek a licence in **France**, saying it expects to secure one "in the coming months." This is the in-window resolution of the June 26 anchor: the first named major-CASP cease-operations announcement, landing as ESMA holds firm on no extensions and only ~210 of 1,200+ pre-MiCA registrants (~17%) have converted to full authorization. For Ditto: the cleanest possible demand-side proof that MiCA is an identity/KYC/compliance-infrastructure filter, not a paperwork formality — the firms that can't demonstrate licensable controls are being forced out of the single market.
  - Source: https://www.coindesk.com/policy/2026/06/26/binance-tells-eu-users-it-will-no-longer-provide-services-after-failing-to-secure-mica-license
  - Source: https://www.euronews.com/business/2026/06/25/binance-to-halt-crypto-services-across-eu-countries-after-failing-to-secure-mica-approval
  - Source: https://en.cryptonomist.ch/2026/06/27/binance-mica-license-withdrawal/
  - Date: 2026-06-26 (CoinDesk) / 2026-06-25 (Euronews) / 2026-06-27 (follow-on analysis)
- **Philippines BSP Circular 1213 SMS-OTP hard stop — June 30 (anchor-tracking; no new in-window event)** — In-window coverage (SunStar, BitPinas, iPiD) restates the confirmed position: BSP Deputy Governor Elmore Capule reiterated "as of now we are not extending it" — every BSP-supervised bank, e-money issuer and payment operator must stop using SMS/email OTPs for high-risk transactions by **June 30, 2026** (OTPs retained only for confirming mobile-number ownership). No sector-wide compliance-rate data or last-mile enforcement statement published inside June 26–29; expect it in the June 30 / July 1 cluster.
  - Source: https://www.sunstar.com.ph/cebu/bsp-to-drop-sms-otp-by-june-30
  - Source: https://ipid.tech/blog/bsp-circular-1213-philippines-compliance
  - Date: 2026-06-30 (deadline)

### Pillar 2: Identity orchestration
- **UK Finance confirms major banks completed proof-of-concept on a bank-led digital identity / reusable-KYC service (announced June 25; analysis published in-window June 28)** — UK Finance confirmed that major UK retail banking groups have finished proof-of-concept testing of a **voluntary, consent-based digital identity service** that lets customers verify name, age or address straight from their banking app — no passport or utility-bill upload — and reuse those pre-verified attributes for onboarding with utilities, legal platforms and other relying parties. The model is proven elsewhere: Sweden's BankID reaches ~99% of adults, Norway's ~97%, Belgium's itsme ~80%. It arrives precisely as document-and-selfie remote checks buckle under AI deepfakes and injection attacks. Three questions stay open by design and define the commercial opportunity: (i) **liability** — the relying institution still owns the regulatory obligation even when it trusts a bank-issued attribute; (ii) **pricing** — UK open banking already exposes account data for free, so monetizing higher-assurance identity is unsettled; (iii) **go-to-market** — who operates and distributes it. Corroborated independently in the June 26 ID Tech Digest, which frames it as a cross-industry service for "pre-verified banking profile attributes." For Ditto: this is an orchestration-layer story — the credential is the easy part; trust framework, liability allocation, consent and relying-party integration are the hard part Ditto's platform is built for.
  - Source: https://www.retailbankerinternational.com/comment/uk-bank-id-scheme-transform-remote-kyc/
  - Source: https://idtechwire.com/id-tech-digest-june-26-2026/
  - Date: 2026-06-25 (UK Finance announcement) / 2026-06-28 (Retail Banker International analysis)
- **Incode acquires Identiq — biometric IDV incumbent buys a privacy-preserving, peer-to-peer identity-validation network (June 26, 2026 per ID Tech Digest)** — Incode acquired Identiq, blending Incode's biometric onboarding pipeline with Identiq's cryptographic, no-data-sharing identity-validation framework that lets parties "cross-verify user trustworthiness indicators" without exposing personal data — part of a pledged $100M privacy-infrastructure investment. The deal signals IDV incumbents buying *privacy-preserving* (data-minimising, cryptographic) validation rather than building it — the same thesis (prove trust without exposing data) Ditto markets via ZKPs. Watch as a competitive/ecosystem datapoint (do not name in posts). Secondary in-window biometrics M&A: **onsemi agreed to acquire Synaptics (~$7B)**, folding edge-AI fingerprint sensing into automotive/IoT — adjacent to Ditto's lane, noted for the record only.
  - Source: https://idtechwire.com/incode-acquires-identiq-for-privacy-preserving-fraud-intelligence/
  - Source: https://idtechwire.com/id-tech-digest-june-26-2026/
  - Date: 2026-06-26 (per ID Tech Digest)

### Pillar 3: EUDI / eIDAS2
(no new material in window — Germany's Digital Identities Act (DIdG) remains at the cabinet-draft stage (adopted May 20; Library of Congress write-up June 15, both logged); German state-driven EUDI Wallet launch confirmed for **January 2, 2027** (identification/documentation functions first), no Bundestag first-reading date scheduled inside June 26–29 post-EUDI ON. The biometric-portrait opt-out compromise (Committee June 18) still has no adopted implementing-rule text. Watch for the DIdG first reading and the adopted opt-out text.)

### Pillar 4: KYC / AML compliance
(no new material in window — AMLA's three Feb 9 draft RTS (CDD under AMLR Art. 28; pecuniary sanctions; business-relationship/linked-transaction criteria) remain on track for **final-draft submission to the Commission by July 10, 2026**; the directly applicable AMLR single rulebook applies from **July 10, 2027**. No new AMLA consultation, FATF publication or sanctions action confirmed inside June 26–29. FATF's seventh targeted update on VA/VASP standards (approved at the June 17–19 plenary) is due "next month" — July 2026.)

### Pillar 5: Customer onboarding
(covered under Pillar 2 — the UK Finance bank-led reusable-KYC service is the cycle's onboarding story: document-free, consent-based attribute reuse for onboarding with utilities/legal/other relying parties. No separate onboarding-KPI benchmark or sector study published inside June 26–29.)

### Pillar 6: Identity verification (IDV)
(covered under Pillar 2 — Incode × Identiq is the in-window IDV move. No new NIST IAL update, iBeta/FIDO Document Authenticity output, or other discrete IDV-market event confirmed inside June 26–29.)

### Pillar 7: Fraud / Deepfakes
(no new named in-window incident — the Veriff Identity Fraud Report 2026 (net fraud rate >4% for a third year; ~1 in 25 verification attempts an impersonation; 300% rise in AI-altered media), Sumsub (deepfakes now ~11% of global fraud, up from 7% in 2024) and iProov (2,665% spike in virtual-camera attacks; 1,151% H2-2025 iOS injection rise) figures circulating in-window are republished earlier-2026 reports, not new releases. No named-bank deepfake event dated June 26–29 confirmed. Anchor: EU AI Act Art. 50 — July 22 Code-of-Practice signatory deadline / August 2 enforcement.)

### Pillar 8: Mobile trust & app security
- **Rokarolla — newly identified Android banking trojan targeting 217 banking/crypto apps via accessibility abuse and OTP interception (Zimperium, June 17, 2026; missed by prior cycles)** — Zimperium disclosed **Rokarolla**, a new Android banking-trojan family that targets **217 banking and cryptocurrency apps**, runs **137 distinct C2 commands**, abuses Android Accessibility Services for full device control, **disables Google Play Protect**, serves phishing overlays, **intercepts SMS one-time passwords and 2FA codes**, blocks incoming calls to suppress fraud alerts, and swaps copied crypto-wallet addresses. It spreads via sideloaded fakes of TikTok and Chrome using a two-stage dropper (the dropper poses as Play Protect). Published June 17 with IoCs on GitHub and full MITRE ATT&CK mapping; missed by the June 17–19 delta cycles. *Date note: published June 17, outside the strict June 26–29 window, but surfaced as the cleanest uncovered mobile-trust finding and squarely on-pillar.* For Ditto: a textbook case for the mobile-trust thesis — accessibility-service abuse intercepts exactly the SMS OTPs that BSP Circular 1213 (P1) is now banning, which is why device-side threat defence + phishing-resistant, split-key auth beats SMS-OTP-and-hope. Reusable as the threat-side companion to the OTP-sunset regulatory story.
  - Source: https://www.helpnetsecurity.com/2026/06/17/rokarolla-android-banking-trojan-device-takeover/
  - Source: https://www.bleepingcomputer.com/news/security/new-rokarolla-android-malware-targets-217-banking-crypto-apps/
  - Source: https://www.malwarebytes.com/blog/mobile/2026/06/rokarolla-android-malware-can-take-over-your-phone-and-steal-banking-logins
  - Date: 2026-06-17 (published; missed by prior cycles)

### Pillar 9: Passwordless / split-key
(covered under Pillar 1 — BSP Circular 1213's June 30 SMS-OTP hard stop is the live passwordless event; BSP confirms no extension and points firms toward biometrics, behavioural biometrics, security keys and adaptive auth. No new FIDO/regulator OTP-sunset or passkey-adoption release inside June 26–29; FIDO's "5 billion passkeys / 75% have enabled one" World Passkey Day 2026 figures (early May) are out of window.)

### Pillar 10: ZKPs in practice
(no new material in window — no new bank ZKP pilot or OpenID4VP/VCI/mDL deployment confirmed inside June 26–29. The Incode × Identiq "validate without exposing data" deal (P2) is the closest adjacent privacy-preserving signal; the California mDL Showcase (June 24) was logged June 25.)

### Pillar 11: Age assurance & privacy attributes
(no new material in window — the UK government's June 15 response to "Growing Up in the Online World" (under-16 social-media ban, regulations targeted for December 2026 / in force spring 2027) and Ofcom's June 16 feasibility letter to DSIT are both pre-window and logged context. Next hard anchor: **Ofcom's statutory age-assurance effectiveness report, due July 17, 2026**. No new platform enforcement action or EU age-verification-app update confirmed inside June 26–29.)

---

## Next-cycle anchors (updated)

- **Philippines BSP Circular 1213 SMS-OTP hard stop (June 30)** — TOMORROW; binary liability shift for non-compliant BSP-supervised institutions; watch for compliance-rate data or a BSP enforcement statement.
- **MiCA CASP hard deadline (July 1)** — 2 days; transitional period ends bloc-wide; expect more named cease-operations/relocation announcements week of June 30 following Binance's EU exit.
- **Binance France MiCA application** — new anchor; Binance has named France as its next licensing jurisdiction after withdrawing in Greece; watch the AMF process and timeline.
- **AMLA CDD / sanctions / business-relationship RTS final drafts → Commission (July 10)** — 11 days; first single EU CDD rulebook track; AMLR single rulebook applies from July 10, 2027.
- **FATF seventh targeted update on VA/VASP Standards (July 2026)** — approved at the June 17–19 plenary; will address DeFi, stablecoins, unhosted wallets; affects VASP KYC/identity globally.
- **Ofcom statutory age-assurance effectiveness report (July 17)** — 18 days; assesses how services have used age assurance and how effective it has been under the Online Safety Act.
- **EU AI Act Code of Practice signatory deadline (July 22)** — 23 days; presumption-of-conformity benefit for signatories.
- **EU AI Act Article 50 enforcement (August 2)** — 34 days; deepfake labelling, AI-content marking, chatbot disclosure become binding.
- **Germany DIdG Bundestag first reading** — TBD post-EUDI ON; state-driven EUDI Wallet launch confirmed for January 2, 2027; watch for first-reading scheduling and committee assignment.
- **EUDI Wallet biometric-portrait opt-out implementing rule — formal adoption** — TBD; agreed at Committee June 18; watch for adopted text and per-member-state divergence.
- **UK People's Panel on Digital ID — report publication** — TBD; deliberation concluded June 21 (Ipsos-run); watch for publication and public-acceptance findings — directly relevant to the UK Finance bank-led ID model (P2).
- **PSR APP-fraud reimbursement independent review report (Q2/Q3 2026)** — review commenced Oct 2025; final report due Q2 or Q3 2026 (sources vary); watch for publication.
- **PSD3/PSR OJEU publication** — H2 2026, no confirmed date; may slip to September.
- **Japan JSDA phishing-resistant MFA mandatory deadline** — "summer 2026"; watch for JSDA finalization.

---

## Run summary

- Findings count by pillar: P1 Banking: 1 substantive (**Binance EU/MiCA exit**) + BSP June 30 anchor-tracking | P2 Identity orchestration: 2 (**UK Finance bank-led digital ID POC**; **Incode × Identiq** acquisition + onsemi/Synaptics note) | P3 EUDI: 0 | P4 KYC/AML: 0 | P5 Onboarding: cross-listed P2 | P6 IDV: cross-listed P2 | P7 Fraud/Deepfakes: 0 new | P8 Mobile trust: 1 (**Rokarolla** banking trojan — June 17, missed by prior cycles) | P9 Passwordless: cross-listed P1 (BSP) | P10 ZKP: 0 | P11 Age assurance: 0 — **Total: 4 distinct findings (3 in-window event-driven + 1 missed-prior-cycle mobile-trust)**
- Override-worthy: **2** — (1) Binance's EU exit, the first named major-CASP cease-operations event two days before the July 1 MiCA deadline (resolves the June 26 anchor); (2) UK Finance bank-led digital ID POC, the BankID model reaching the UK as deepfakes break document-and-selfie checks — an orchestration/liability story landing on 's strongest territory.
- Delta path: research/2026-06-29-cycle-delta.md
- Note: event-heavy cycle as forecast — the June 30 (BSP) / July 1 (MiCA) compliance cluster has started firing, led by Binance. Expect the next two cycles (Tue June 30 / Wed July 1) to carry the rest of the named CASP exits and any BSP compliance data.
