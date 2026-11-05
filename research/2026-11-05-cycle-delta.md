# Cycle Delta — 2026-11-05

Window: 2026-11-03 → 2026-11-05 (last 48 hours, Thu run)

## Provenance notes

- Worker (ditto-slack-bot.dittobot.workers.dev) blocked by egress proxy policy (host not in allowed network domains). Consistent with all runs since at least 2026-10-22. Brand brief, pillar guides, and baseline not fetched from the worker this run.
- Prior-delta deduplication based on 2026-11-04-cycle-delta.md (most recent).
- 12 web searches executed across all 7 pillars.
- **Delta written to GitHub** (worker unavailable): `research/2026-11-05-cycle-delta.md`
- **Watch-item follow-ups confirmed this run:**
  - BCB VASP bank-counterparty ban (Nov 6): Effective tomorrow. No enforcement pre-announcements or last-minute VASP authorizations found as of this run. The Oct 30 vs. Nov 6 date conflict (Resolution 589 amendment) remains unresolved in secondary sources; Nov 6 is the operative date per FCM Law. Watch BCB official registry.
  - Apple Cash ID check (Nov 9): 4 days away. Apple Support page confirms iOS 27 enables Wallet ID credential pathway; no new primary source this window.
  - AMLA central AML/CFT database RTS consultation closed November 3: No post-hearing summary or amendment flag published as of this run. Watch amla.europa.eu.
  - EUDI ARF Iteration 6: Closes Nov 18; nothing published.
  - Fourthline + Veridas merger: Closed November 3 — covered in Nov 4 delta. No follow-up material (financial filings, integration announcements) in window.
- **Checked and rejected (outside window or already covered):**
  - New York AI chatbot age verification law (Chapter 368, Laws of 2026): Signed October 29; outside window.
  - UK Police Reform Bill (facial recognition watchdog): No confirmed November bill introduction; latest development is July 2026 Home Secretary statement; outside window and unconfirmed.
  - FIDO 7 billion passkeys (October 2026): Outside window; already covered.
  - Fourthline/Veridas merger: Covered in Nov 4 delta.
  - DHS OBIM biometric contracts: Solicitation planned for December 1; below on-pillar threshold for Ditto (US federal, non-EU regulated banking context).

---

## Override-worthy this cycle

(none)

---

## New findings

### Pillar 1: Banking & Payments

(no new material in window. No new EBA, ECB, FCA, or PSR guidance dated Nov 3–5 found. PSD3/PSR: no OJEU publication in window; Q4 2026 timeline holds. DORA enforcement: First confirmed DORA fine remains the FMA €42,000 penalty against Western Union International Bank GmbH on July 14, 2026, for incident-reporting breaches; no November enforcement action found. AMLA: central database RTS public consultation closed November 3; no post-consultation summary published.)

### Pillar 2: EUDI / eIDAS2

(no new material in window. EUDI ARF Iteration 6 (Digital Credentials API refinement) closes November 18 — nothing published. Latest confirmed ARF version remains v3.0.0, published July 21, 2026 on GitHub (aligning with Commission Implementing Regulations 2026/1730, 2026/1731, 2026/1735). National relying-party registers apply from December 24, 2026. 24/27 member states still tracking to miss the December 24 wallet-availability deadline. Germany confirmed January 2, 2027 launch (d-you wallet); Italy's IT-Wallet and Denmark's AltID remain most advanced nationally as of October 2026.)

### Pillar 3: Fraud / Deepfakes

- **OCR Studio launches single-capture face-matching for KYC with no biometric template storage.** OCR Studio released a face-matching product on November 4 that compares an applicant's live face against their identity document in a single capture step. Key design choice: the product does not generate or store biometric templates, addressing emerging regulatory and privacy objections to biometric data retention (see GDPR Article 9 and forthcoming AMLR CDD rules). It supports native mobile SDKs and browser-based verification via WebAssembly, enabling offline operation. Relevance for identity vendors: signals that the KYC market is bifurcating — template-free liveness products position for GDPR-conservative banking clients, while template-based players offer stronger fraud signals. Ditto's angle: a no-template approach may satisfy some EU data-minimisation interpretations but cannot support continuous monitoring or watchlist matching, reinforcing the case for selective-disclosure architectures.
  - Source: https://www.biometricupdate.com/202611/ocr-studio-brings-single-capture-face-matching-to-kyc
  - Date: 2026-11-04
  - Drafting caution: Product claim ("no biometric template stored") is vendor-asserted; independent technical validation not found. Confirm GDPR-compliance positioning against primary CNIL/ICO guidance before citing as regulatory compliant.

### Pillar 4: ZKPs in practice

(no new material in window. No bank pilot announcements or OpenID Foundation spec updates dated Nov 3–5 found. EUDI ZKP age-proof pathway confirmed riding W3C Digital Credentials API; Google Wallet mso_mdoc_zk format via Longfellow library remains the clearest production reference implementation. No Deutsche Bank / Polygon update.)

### Pillar 5: Passwordless / split-key

(no new material in window. No FIDO Alliance announcements or regulator OTP-sunset notices dated Nov 3–5 found. FIDO Passkey Index data (October 2026) holds: 7 billion passkeys, 42% eligible-account enrollment, 93% passkey sign-in success vs. 78% for passwords/MFA. W3C WebAuthn Level 3 proposed as full Recommendation in July 2026. FIDO Passkey Rubric checklist forthcoming on Passkey Central — watch for November publication.)

### Pillar 6: LATAM

(no new material in window. BCB VASP bank-counterparty ban effective tomorrow (November 6). No enforcement pre-announcements, last-minute VASP authorizations, or BCB press releases found in window. No new CNBV, Superfinanciera, CMF, or SBS developments. Pix/Drex: no new material. Watch BCB open authorization registry at bcb.gov.br post-November 6 for first enforcement notices or any VASPs receiving authorization.)

### Pillar 7: Identity ecosystem

(no new material meeting the bar this cycle. DHS Office of Biometric Identity Management (OBIM) is planning to solicit two contracts valued $50–100M each (December 1 solicitation, January 2027 award target) — noted but below threshold for Ditto's EU/LATAM banking audience; held for context. Nigeria's $430M World Bank digital ID project received a one-year extension to December 31, 2027 (restructuring paper dated October 22, 2026) — outside window. Fourthline + Veridas merger: no post-close follow-up material (integration announcements, revenue filings, analyst reactions) published in window beyond the November 3 close covered in the Nov 4 delta. No Forrester, KuppingerCole, or Gartner digital identity report dated Nov 3–5 found.)

---

## Upcoming watch items (next 7 days)

- **2026-11-06 (Thu, tomorrow):** BCB VASP bank-counterparty ban effective — watch BCB official authorization registry for enforcement notices, last-minute authorizations, or any official clarification on firms in-process (Onda Finance per BCB Comunicado 45.986).
- **2026-11-09 (Mon):** Apple Cash ID check goes live (US) — verify user experience; iOS 27 Wallet ID credential pathway may be the primary mechanism. Signal: P2P payments requiring identity gating by a major tech platform, possible influence on EU payment identity architecture discussions.
- **2026-11-18 (Tue):** EUDI ARF Iteration 6 closes — check for updated ARF version release on GitHub (eu-digital-identity-wallet/eudi-doc-architecture-and-reference-framework).
- **~Days ahead:** AMLA central AML/CFT database RTS consultation outcomes — watch amla.europa.eu for post-hearing statement or summary of feedback received.
- **December 2026:** FATF mutual evaluation reports for US and Mexico.
- **2026-12-24:** EUDI wallet-availability deadline — 49 days; 24/27 member states tracking to miss it.
