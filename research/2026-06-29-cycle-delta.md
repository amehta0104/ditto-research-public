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
  - Source: https://cryip.co/spain-mica-deadline-no-extension-unlicensed-crypto-firms-july-1/
  - Source: https://www.cryptotimes.io/2026/06/29/micas-july-1-deadline-what-it-means-for-your-crypto-in-europe/
  - Date: 2026-06-26 (CoinDesk) / 2026-06-25 (Euronews) / 2026-06-27 (follow-on analysis) / 2026-06-29 (France confirmed in-window)
- **Philippines BSP Circular 1213 SMS-OTP hard stop — June 30 (T-1; no extension confirmed by named official)** — BSP Deputy Governor Elmore Capule publicly confirmed: "As of now we are not extending it, so they have to catch up." Every BSP-supervised bank, e-money issuer and payment operator must stop using SMS/email OTPs for high-risk transactions by **June 30, 2026**. Non-compliant institutions lose AFASA liability protection with no grace period — fraud losses become direct institutional liability. GMA News Online confirmed the AFASA FMS layer switched June 25; the full OTP hard stop completes tomorrow. For Ditto: BSP moved from Circular 1213 issuance (June 2025) to hard enforcement in 13 months; the liability-shift architecture is structurally identical to what the EU PSR and UK APP-fraud reimbursement rules are building.
  - Source: https://www.sunstar.com.ph/cebu/bsp-to-drop-sms-otp-by-june-30
  - Source: https://www.gmanetwork.com/news/money/economy/992561/no-more-sms-email-otps-for-high-risk-financial-transactions-starting-june-25/story/
  - Source: https://ipid.tech/blog/bsp-circular-1213-philippines-compliance
  - Date: 2026-06-30 (deadline) / 2026-06-29 (T-1; no-extension confirmation by named official)

### Pillar 2: Identity orchestration
- **UK Finance confirms major banks completed proof-of-concept on a bank-led digital identity / reusable-KYC service (announced June 25; analysis published in-window June 28)** — UK Finance confirmed that major UK retail banking groups have finished proof-of-concept testing of a **voluntary, consent-based digital identity service** that lets customers verify name, age or address straight from their banking app — no passport or utility-bill upload — and reuse those pre-verified attributes for onboarding with utilities, legal platforms and other relying parties. The model is proven elsewhere: Sweden's BankID reaches ~99% of adults, Norway's ~97%, Belgium's itsme ~80%. It arrives precisely as document-and-selfie remote checks buckle under AI deepfakes and injection attacks. Three questions stay open by design and define the commercial opportunity: (i) **liability** — the relying institution still owns the regulatory obligation even when it trusts a bank-issued attribute; (ii) **pricing** — UK open banking already exposes account data for free, so monetizing higher-assurance identity is unsettled; (iii) **go-to-market** — who operates and distributes it. For Ditto: this is an orchestration-layer story — the credential is the easy part; trust framework, liability allocation, consent and relying-party integration are the hard part Ditto's platform is built for.
  - Source: https://www.retailbankerinternational.com/comment/uk-bank-id-scheme-transform-remote-kyc/
  - Source: https://idtechwire.com/id-tech-digest-june-26-2026/
  - Date: 2026-06-25 (UK Finance announcement) / 2026-06-28 (Retail Banker International analysis)
- **Incode acquires Identiq — biometric IDV incumbent buys a privacy-preserving, peer-to-peer identity-validation network (June 25, 2026)** — Incode acquired Identiq, blending Incode's biometric onboarding pipeline with Identiq's cryptographic, no-data-sharing identity-validation framework that lets parties "cross-verify user trustworthiness indicators" without exposing personal data — part of a pledged $100M privacy-infrastructure investment. The deal signals IDV incumbents buying *privacy-preserving* (data-minimising, cryptographic) validation rather than building it — the same thesis (prove trust without exposing data) Ditto markets via ZKPs. Watch as a competitive/ecosystem datapoint (do not name in posts).
  - Source: https://idtechwire.com/incode-acquires-identiq-for-privacy-preserving-fraud-intelligence/
  - Source: https://www.businesswire.com/news/home/20260625366040/en/Incode-Acquires-Identiq-to-Expand-Its-Privacy-First-Architecture-for-Identity-and-Fraud-Prevention
  - Date: 2026-06-25 (per ID Tech Digest / BusinessWire)

### Pillar 3: Fraud / Deepfakes
- **Proof.com Fraud Files (June 2026): 74% of infostealer-stolen payment card numbers remained valid nine months later; AI-assembled synthetic IDs cost as little as $5** — Proof.com's "Fraud Files" June 2026 edition documents that 74% of payment card numbers harvested by infostealers in 2025 were still active as of March 2026 — a nine-month operational shelf life that makes credential stores a durable fraud asset. Combined with generative-AI tools enabling full synthetic identity packages for as little as $5 and deepfake images for $10–$50, the attack economics have inverted: it is now cheaper and more persistent to build a fraud pipeline from real stolen credentials plus AI-augmented fabrication than to conduct traditional account takeover. Between Jan–Aug 2025, Group-IB documented 8,065 deepfake liveness-bypass attempts at a single financial institution (nearly 1,000/month). New angle distinct from the Shufti Deepfake Fraud Index (June 26 delta): the *persistence* of stolen real-world credential data as the raw material that AI-assembled synthetic identities are built on — not just deepfake generation volume.
  - Source: https://www.proof.com/blog/the-fraud-files-stolen-credentials-fake-biometrics-and-the-synthetic-identity-wave-june-2026
  - Date: 2026-06 (June 2026; specific date unconfirmed in window; not in any prior delta)

### Pillar 4: EUDI / eIDAS2
(no new material in window — Germany's Digital Identities Act (DIdG) remains at the cabinet-draft stage (adopted May 20); state-driven EUDI Wallet launch confirmed for **January 2, 2027** (identification/documentation functions first). No Bundestag first-reading date scheduled inside June 26–29 post-EUDI ON. The biometric-portrait opt-out compromise (Committee June 18) still has no adopted implementing-rule text. Watch for the DIdG first reading and the adopted opt-out text.)

### Pillar 5: KYC / AML compliance
(no new material in window — AMLA's three Feb 9 draft RTS (CDD under AMLR Art. 28; pecuniary sanctions; business-relationship/linked-transaction criteria) remain on track for **final-draft submission to the Commission by July 10, 2026**. No new AMLA consultation, FATF publication or sanctions action confirmed inside June 26–29. FATF's seventh targeted update on VA/VASP standards (approved at the June 17–19 plenary) is due "next month" — July 2026.)

### Pillar 6: Mobile trust & app security
- **Rokarolla — newly identified Android banking trojan targeting 217 banking/crypto apps via accessibility abuse and OTP interception (Zimperium, June 17, 2026; missed by prior cycles)** — Zimperium disclosed **Rokarolla**, a new Android banking-trojan family that targets **217 banking and cryptocurrency apps**, runs **137 distinct C2 commands**, abuses Android Accessibility Services for full device control, **disables Google Play Protect**, serves phishing overlays, **intercepts SMS one-time passwords and 2FA codes**, blocks incoming calls to suppress fraud alerts, and swaps copied crypto-wallet addresses. It spreads via sideloaded fakes of TikTok and Chrome using a two-stage dropper. Published June 17 with IoCs on GitHub and full MITRE ATT&CK mapping; missed by the June 17–19 delta cycles. *Date note: published June 17, outside the strict June 26–29 window, but surfaced as the cleanest uncovered mobile-trust finding and squarely on-pillar.* For Ditto: a textbook case for the mobile-trust thesis — accessibility-service abuse intercepts exactly the SMS OTPs that BSP Circular 1213 (P1) is now banning. Reusable as the threat-side companion to the OTP-sunset regulatory story.
  - Source: https://www.helpnetsecurity.com/2026/06/17/rokarolla-android-banking-trojan-device-takeover/
  - Source: https://www.bleepingcomputer.com/news/security/new-rokarolla-android-malware-targets-217-banking-crypto-apps/
  - Source: https://www.malwarebytes.com/blog/mobile/2026/06/rokarolla-android-malware-can-take-over-your-phone-and-steal-banking-logins
  - Date: 2026-06-17 (published; missed by prior cycles)

### Pillar 7: Identity ecosystem
- **Synthetic identity fraud explicitly ranked #1 fraud threat in financial services — Biometric Update synthesis (late June 2026)** — A Biometric Update analysis from late June 2026 synthesises multiple 2026 industry reports to confirm that synthetic identity fraud has become the single biggest fraud threat facing financial institutions, overtaking document fraud and account takeover for the first time. 84% of fraud-prevention leaders rate it high or moderate risk; 3 in 10 FIs are actively hit by impersonation fraud; U.S. unsecured credit losses from synthetic identity fraud are projected to exceed **$3.1B in 2026**, growing at ~16% annually (Mitek / Datos Insights). Key framing distinction from the June 26 delta's Shufti Deepfake Fraud Index (which tracked growth rates and document-deepfake volumes): this report establishes the threat-*ranking* shift — synthetic ID is now #1 overall, not just the fastest-growing subcategory. For Ditto: the identity verification layer is no longer a compliance checkbox — it is the primary operational battleground for financial fraud in 2026.
  - Source: https://www.biometricupdate.com/202606/report-finds-synthetic-identity-fraud-becoming-biggest-fraud-threat-in-2026
  - Date: 2026-06-27/28 (estimated; late June 2026; not in any prior delta)

### Pillar 8: ZKPs in practice
(no new material in window — no new bank ZKP pilot or OpenID4VP/VCI/mDL deployment confirmed inside June 26–29.)

### Pillar 9: Age assurance & privacy attributes
(no new material in window — next hard anchor: **Ofcom's statutory age-assurance effectiveness report, due July 17, 2026**.)

---

## Next-cycle anchors (updated)

- **Philippines BSP Circular 1213 SMS-OTP hard stop (June 30 — TOMORROW)** — Hard deadline; binary liability shift for non-compliant BSP-supervised institutions; watch for compliance-rate data or a BSP enforcement statement.
- **MiCA CASP hard deadline (July 1 — 2 DAYS)** — Transitional period ends bloc-wide; Binance EU exit confirmed. Expect more named cease-operations/relocation announcements week of June 30.
- **Binance France MiCA application** — New anchor; Binance named France (AMF) as next licensing jurisdiction; watch for AMF filing and timeline.
- **AMLA CDD / sanctions / business-relationship RTS final drafts → Commission (July 10)** — 11 days.
- **FATF seventh targeted update on VA/VASP Standards (July 2026)** — Approved at June 17–19 plenary; will address DeFi, stablecoins, unhosted wallets.
- **Ofcom statutory age-assurance effectiveness report (July 17)** — 18 days.
- **EU AI Act Code of Practice signatory deadline (July 22)** — 23 days.
- **EU AI Act Article 50 enforcement (August 2)** — 34 days; deepfake labelling, AI-content marking, chatbot disclosure become binding.
- **Germany DIdG Bundestag first reading** — TBD post-EUDI ON; state-driven EUDI Wallet launch confirmed January 2, 2027; Bundestag summer recess likely delays to September.
- **EUDI Wallet biometric-portrait opt-out implementing rule — formal adoption** — TBD.
- **UK People's Panel on Digital ID — report publication** — TBD; deliberation concluded June 21 (Ipsos); relevant to UK Finance bank-led ID model.
- **PSR APP-fraud reimbursement independent review report (Q2/Q3 2026)** — Watch for publication.
- **PSD3/PSR OJEU publication** — H2 2026; no confirmed date; may slip to September.
- **Japan JSDA phishing-resistant MFA mandatory deadline** — "summer 2026"; watch for JSDA finalization.

---

## Run summary

- Findings count by pillar: P1 Banking: 2 (Binance MiCA EU exit; BSP OTP T-1 no-extension confirmation) | P2 Identity orchestration: 2 (UK Finance bank-led digital ID POC; Incode × Identiq) | P3 Fraud: 1 (Proof.com credential longevity / infostealer shelf-life) | P4 EUDI: 0 | P5 AML: 0 | P6 Mobile trust: 1 (Rokarolla banking trojan — June 17, missed prior cycles) | P7 Identity ecosystem: 1 (synthetic ID now #1 fraud threat, Biometric Update synthesis) | P8 ZKP: 0 | P9 Age assurance: 0 — **Total: 6 findings across 5 pillars**
- Override-worthy: **2** — (1) Binance EU exit (named-CASP action resolving the June 26 anchor, 48h before July 1); (2) UK Finance bank-led digital ID POC.
- Delta path: research/2026-06-29-cycle-delta.md

---

_Note: Worker API (ditto-slack-bot.dittobot.workers.dev) is blocked by the environment's network egress allowlist; skill/pillar files were not loaded from the worker. Delta written directly to GitHub. To restore full skill-file context, add `ditto-slack-bot.dittobot.workers.dev` to the environment's network egress allowlist._
