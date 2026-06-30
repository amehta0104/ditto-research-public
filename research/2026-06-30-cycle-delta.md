# Cycle Delta — 2026-06-30

Window: 2026-06-28 → 2026-06-30 (last 48 hours — Tuesday run, Mon–Tue window)

## Override-worthy this cycle

1. **July 22 is the date two independent regulatory frameworks both close for industry input on AI and identity — the FSB's G20 AI sound-practices consultation and the EU AI Act Article 50 Code of Practice signatory window both expire on the same day, 22 days from now.** Account: / company. Angle: "July 22 is the last day two different regulators will take voluntary commitments from the industry on AI and identity. The FSB sets the standard your banking clients will be audited against globally; the EU AI Act code gives you legal presumption of conformity on deepfake disclosure. After July 22, both doors close and regulators decide without you."

2. **BSP Circular 1213's SMS-OTP hard stop completed today (June 30, 2026) — the liability-shift is now live in the Philippines, the first G20-adjacent jurisdiction to ban SMS OTPs for high-risk transactions with a full liability backstop.** Account: / / company. Angle: The timeline from regulator guidance (June 2025) to hard enforcement (June 2026) is 13 months. The same liability-shift architecture — fraud losses become direct institutional liability for non-compliant FIs — is what PSR (EU) and APP-fraud reimbursement rules (UK) are building. Philippines just ran the proof of concept.

## New findings

### Pillar 1: Banking & Payments
- **BSP Circular 1213 SMS-OTP hard stop completes today: liability-shift is live in the Philippines (2026-06-30)** — The Bangko Sentral ng Pilipinas' June 30, 2026 deadline for all BSP-supervised entities to cease SMS/email OTP authentication for high-risk transactions has now passed. From today, any covered institution (universal, commercial, digital banks; e-money issuers and payment operators averaging >₱75M/month in online transactions) that still uses SMS OTP for a high-risk transaction loses AFASA liability protection — fraud losses become direct institutional liability. Deputy Governor Elmore Capule confirmed no extension on June 29. No post-deadline compliance rate data or BSP enforcement statement confirmed in the June 28–30 window yet; those are the next anchors to watch. For Ditto: this resolves the June 29 T-1 anchor and is the cleanest proof-of-concept available that a liability-shift mandate — not just guidance — is what moves banks to ditch OTPs at scale. The EU PSR and UK APP-fraud rules are building the same architecture.
  - Source: https://www.sunstar.com.ph/cebu/bsp-to-drop-sms-otp-by-june-30
  - Source: https://www.gmanetwork.com/news/money/economy/992561/no-more-sms-email-otps-for-high-risk-financial-transactions-starting-june-25/story/
  - Source: https://ipid.tech/blog/bsp-circular-1213-philippines-compliance
  - Date: 2026-06-30 (deadline completion; follow-on compliance data not yet published)

### Pillar 2: EUDI / eIDAS2
(no new material in window — September 2026 member-state wallet-availability deadline confirmed by multiple implementation guides, consistent with prior deltas. No new ARF update, LSP status report, or Commission implementing act confirmed June 28–30. Germany DIdG Bundestag first-reading still unscheduled post-EUDI ON.)

### Pillar 3: Fraud / Deepfakes
- **PYMNTS: Deepfake synthetic borrowers now targeting bank lending and underwriting — not just account opening (approx. 2026-06-09, missed by prior cycles)** — PYMNTS documented a new attack category distinct from the KYC/onboarding deepfake coverage in prior deltas: AI-engineered synthetic borrowers arrive with AI-generated driver's licences, AI-written employment verification correspondence, and a live onboarding video featuring a deepfake face synchronized with cloned speech patterns — engineered to appear as "statistically perfect consumers" to automated underwriting models and human reviewers, then disappear after loans fund. AI-driven lenders are uniquely exposed because fraud models are designed to flag anomalies, while synthetic borrowers are explicitly optimized to eliminate anomalies. PYMNTS Intelligence / Block: 46% of FIs report increasing fraud sophistication; fraud now spans the full member life cycle, from onboarding to authentication to transaction activity. New angle distinct from Shufti Deepfake Fraud Index and Proof.com infostealer-shelf-life findings (June 26 and June 29 deltas): the *lending/underwriting channel* is an expanding attack surface as automated credit decisioning grows — document fraud, biometric fraud, and voice cloning converge in a single engineered persona designed for one specific transaction. For Ditto: the identity verification layer must extend through the credit decision, not stop at the account-opening gate.
  - Source: https://www.pymnts.com/news/security-and-risk/2026/banks-are-falling-deepfake-borrowers/
  - Date: ~2026-06-09 (approx.; not in prior deltas; treated as missed)

### Pillar 4: ZKPs in practice
(no new material in window — no bank ZKP pilot, OpenID4VP, OpenID4VCI or mDL deployment announcement confirmed June 28–30.)

### Pillar 5: Passwordless / split-key
(covered under P1 Banking above — BSP OTP hard stop is the primary passwordless/liability event this cycle. FIDO Alliance 5B passkey milestone (World Passkey Day, May 6, 2026; OpenAI FIDO membership, April 2026) are outside the window and likely covered in earlier cycles.)

### Pillar 6: LATAM
(no new material in window — Chile CMF's June 2 amendment setting the SFA's entry into force for July 2027 was outside the window; Brazil Drex architecture pivot and Open Finance 128M-consent milestone are prior-cycle material. No new BCB/CNBV/Superfinanciera/SBS announcement confirmed June 28–30.)

### Pillar 7: Identity ecosystem
- **FSB publishes 12 Sound Practices for Responsible AI Adoption in financial institutions — covers agentic AI, deepfake detection, and AI-monitors-AI governance (2026-06-10, missed by prior cycles)** — The Financial Stability Board published a consultation report on June 10, 2026 setting out 12 sound practices for financial institutions' responsible adoption of AI. Key elements directly on Ditto's territory: (i) the FSB explicitly addresses the limits of human oversight of agentic AI systems, recommending AI-monitoring-AI architectures for when continuous human review of individual agent decisions becomes impractical; (ii) one of the FSB's own case studies covers a digital bank using facial recognition to detect suspicious image backgrounds associated with mule accounts and fraudulent identity attempts — validating the biometric/deepfake detection market; (iii) the practices cover the full AI lifecycle: board-level governance, risk appetite, data governance, explainability, model validation and third-party AI risk. The consultation closes July 22, 2026; the FSB will deliver a final report to G20 Finance Ministers and Central Bank Governors in October 2026. This is a G20-level signal: the vocabulary your banking clients will be audited against globally is being written now. For Ditto: submitting to the FSB consultation (or advising clients who do) positions Ditto as an AI governance partner, not just a vendor.
  - Source: https://www.fsb.org/2026/06/sound-practices-for-responsible-adoption-of-artificial-intelligence-ai-consultation-report/
  - Source: https://www.pymnts.com/artificial-intelligence-2/2026/agentic-ai-risk-catches-eye-of-financial-stability-board/
  - Source: https://bankingjournal.aba.com/2026/06/financial-stability-board-releases-sound-practices-for-ai-adoption/
  - Date: 2026-06-10 (published; missed by prior cycles; consultation closes 2026-07-22; final to G20 October 2026)

- **EU AI Act Article 50 Code of Practice final published (June 10) — deepfake disclosure mandatory from August 2, signatory window closes July 22 (22 days)** — The European Commission published the final Code of Practice on marking and labelling AI-generated content on June 10, 2026 — a voluntary compliance framework for Article 50's transparency obligations, which become binding from August 2, 2026. Key Article 50 obligations: providers of generative AI systems must mark outputs in machine-readable format; deployers using AI to create deepfakes (defined as AI-generated/manipulated image, audio, or video content that resembles real persons and could falsely appear authentic) must disclose this even without intent to deceive; chatbot disclosure required in real time. Companies signing the Code by July 22 at 18:00 CEST receive a legal presumption of conformity with Article 50. Non-signatories face more intensive regulatory scrutiny and fines up to €15M or 3% of global turnover. Importantly, this framework applies both to legitimate AI deployers AND establishes a regulatory definition of "deepfake" that identity verification vendors can reference when characterizing the attacks their systems detect. For Ditto: the August 2 enforcement date means EU-regulated clients deploying any AI-generated content (including synthetic test identities, verification flows, or AI-assisted communications) need to assess Article 50 exposure now. The deepfake definition in law is also a reference point for Ditto's fraud-prevention claims.
  - Source: https://digital-strategy.ec.europa.eu/en/policies/code-practice-ai-generated-content
  - Source: https://www.techtimes.com/articles/318822/20260622/eu-ai-act-chatbot-disclosure-deepfake-labeling-july-22-signatory-deadline.htm
  - Source: https://www.gtlaw.com/en/insights/2026/6/deepfakes-chatbots-ai-generated-text-european-commission-details-transparency-obligations-under-the-ai-act
  - Source: https://getactready.com/blog/eu-ai-act-code-of-practice-signatory-deadline-july-22
  - Date: 2026-06-10 (Code published); 2026-06-22 (TechTimes analysis); signatory deadline 2026-07-22; enforcement 2026-08-02

---

## Next-cycle anchors (updated)

- **AMLA CDD / sanctions / business-relationship RTS final drafts → Commission (July 10)** — 10 days. Four mandates legally due. Watch for AMLA publication.
- **EU AI Act Code of Practice signatory deadline (July 22) — 22 days.** Download, complete and submit form to CNECT-AIOFFICE-CODE-OF-PRACTICE-TRANSPARENCY@ec.europa.eu by 18:00 CEST.
- **FSB AI Sound Practices consultation deadline (July 22) — 22 days.** Respond via secure online form; final report to G20 Finance Ministers October 2026.
- **EU AI Act Article 50 enforcement (August 2) — 33 days.** Deepfake labelling, chatbot disclosure, AI-content marking become binding.
- **MiCA CASP enforcement live (July 1 — TOMORROW's anchor closes)** — Binance EU services suspended as of July 1; Coinbase/Kraken/OKX/Crypto.com confirmed licensed survivors. Watch for France AMF enforcement action against continuing unlicensed operators.
- **Binance France AMF MiCA application** — Watch for AMF filing date and timeline.
- **Philippines BSP Circular 1213 compliance data** — Watch for post-June-30 BSP compliance rate announcement or first enforcement action.
- **FATF seventh targeted update on VA/VASP Standards (July 2026)** — Approved at June 17–19 plenary; addresses DeFi, stablecoins, unhosted wallets.
- **Ofcom statutory age-assurance effectiveness report (July 17)** — 17 days.
- **UK People's Panel on Digital ID — report publication** — TBD; deliberation concluded June 21 (Ipsos); relevant to UK Finance bank-led ID model.
- **PSR APP-fraud reimbursement independent review report (Q2/Q3 2026)** — Watch for publication.
- **PSD3/PSR OJEU publication** — H2 2026; may slip to September; no confirmed date.
- **Germany DIdG Bundestag first reading** — TBD; summer recess likely delays to September; EUDI Wallet launch confirmed January 2, 2027.
- **Japan JSDA phishing-resistant MFA mandatory deadline** — "summer 2026"; watch for finalization.
- **FSB AI Sound Practices final report → G20 Finance Ministers (October 2026)** — New anchor.

---

## Run summary

- Findings count by pillar: P1 Banking: 1 (BSP OTP hard stop completes today) | P3 Fraud/Deepfakes: 1 (PYMNTS deepfake synthetic borrowers — lending channel) | P7 Identity ecosystem: 2 (FSB AI sound practices consultation — missed; EU AI Act Article 50 Code of Practice — missed) — **Total: 4 findings across 3 pillars**
- Override-worthy: **2** — (1) July 22 regulatory convergence: FSB G20 AI consultation + EU AI Act Article 50 Code of Practice signatory window both close on the same date, now 22 days away; (2) BSP OTP liability-shift now live — Philippines proves the liability-backstop model that EU/UK regulators are building.
- Delta path: research/2026-06-30-cycle-delta.md

---

_Note: Worker API (ditto-slack-bot.dittobot.workers.dev) is blocked by the environment's network egress allowlist; skill/pillar files were not loaded from the worker. Delta written directly to GitHub. To restore full skill-file context, add `ditto-slack-bot.dittobot.workers.dev` to the environment's network egress allowlist._
