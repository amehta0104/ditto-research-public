# Cycle Delta — 2026-08-06

Window: 2026-08-04 → 2026-08-06 (last 48 hours)

Worker note: `ditto-slack-bot.dittobot.workers.dev` continues to return 403 from the session's egress proxy (policy denial, not a credential issue). Skill files sourced from repository baseline and prior deltas. Delta written directly to GitHub via MCP.

---

## Override-worthy this cycle

1. **Nu México launches as full banco múltiple today — largest digital bank in Mexico hits KYC/AML cliff with 15M customers** — Nu México (Nubank's Mexico subsidiary) began full commercial banking operations on August 6 after receiving joint authorization from CNBV and SHCP. The transition from SOFIPO to banco múltiple triggers bank-grade CDD, full CNBV/Banxico/SHCP supervision, and expanded product obligations across its existing 15M-user base. David Vélez met President Sheinbaum to formalize a US$4.2B investment commitment for 2026–2030. Account: /. Angle: "Nu México just became Mexico's largest banco múltiple — 15 million customers, full CNBV/Banxico supervision, and a $4.2B investment pledge to the Mexican government. The identity cliff is real: every SOFIPO-to-bank transition requires bank-grade CDD on the existing base, at digital speed. The banks scaling identity verification this fast are the reference architecture for the next decade."

---

## New findings

### Pillar 1: Banking & Payments

(no new PSD3/PSR OJEU publication, EBA press release, ECB SREP action, or AMLA RTS update dated 2026-08-04 to 2026-08-06. PSD3/PSR OJEU publication continues to track to September 2026 — multiple law-firm trackers confirm summer/September window; no OJEU notice number found. No new in-window print.)

### Pillar 2: EUDI / eIDAS2

(no new ARF release, ENISA certification update, Commission implementing act, or member-state wallet launch announcement dated 2026-08-04 to 2026-08-06. ARF v3.0.0 released July 21 is already anchored in the July 30 delta. December 24 wallet-availability deadline remains the next hard date — 140 days. No new in-window print.)

### Pillar 3: Fraud / Deepfakes

(no new bank deepfake enforcement action, iProov/Onfido/Sumsub/Veriff report, or FATF guidance dated 2026-08-04 to 2026-08-06. Reality Defender Google selfie bypass (Aug 4) and Biometric Update Deepfake Market Report ($3B→$6.1B, Aug 4) already covered in Aug 4–5 deltas. No new in-window print.)

### Pillar 4: ZKPs in practice

- **FDD publishes "Zero-Knowledge Proofs" technical note framing ZKPs as critical-infrastructure oversight tool (August 4, 2026)** — The Foundation for Defense of Democracies (FDD) published a TCIL Technical Note by Georgianna Shea, Cason Smith, and Haden Snyder arguing that ZKPs resolve the fundamental impasse in critical-infrastructure cybersecurity oversight: "operators and vendors will not share data they cannot afford to expose, and the government cannot act on information it cannot obtain." The note demonstrates that ZKPs allow a government regulator to generate sector-level cybersecurity insight — confirming aggregate risk metrics such as capital exposure, patch compliance rates, or network segmentation status — without requiring operators to hand over the underlying transaction-level or configuration data. The research explored whether government can generate sector-level insight into systemic cyber risk without compelling operators to disclose what they will not share. For Ditto: the FDD framing applies directly to financial supervision — a bank can prove to a regulator that it meets a capital or exposure threshold without revealing granular position data; a payments network can certify SCA compliance without exposing customer transaction flows. This is the regulatory-grade selective disclosure use case that links eIDAS2/EUDI Wallet ZKP mandates to real prudential supervision needs. Not in prior deltas.
  - Source: https://www.fdd.org/analysis/2026/08/04/zero-knowledge-proofs/
  - Date: 2026-08-04

### Pillar 5: Passwordless / split-key

(no new FIDO Alliance spec release, regulator OTP-sunset announcement, or bank passkey mandate dated 2026-08-04 to 2026-08-06. Microsoft Entra passkeys-by-default + SMS/voice OTP retirement campaign confirmed September 1 start — 26 days away. No new in-window print.)

### Pillar 6: LATAM

- **Nu México launches full commercial banking operations August 6, 2026 — largest digital bank in Mexico becomes a banco múltiple** — Nu México, Nubank's Mexico subsidiary, began commercial banking operations as a fully licensed banco múltiple on August 6, 2026, following a technical migration on August 5. The CNBV granted the Operations Authorization on July 10; SHCP co-authorized the transition from SOFIPO (Sociedad Financiera Popular) status. As a banco múltiple, Nu México is now jointly supervised by CNBV, Banco de México, and SHCP — the same regulatory category as BBVA México, Santander, and Citibanamex. Key operational changes: payroll accounts now permitted, deposit limits raised significantly, expanded credit and investment products, and IPAB deposit insurance increased to approximately US$201,000 per client (up from ~US$12,614 under the SOFIPO scheme). User base: ~15 million Mexican customers, making it the country's largest digital bank by users. CEO David Vélez met President Claudia Sheinbaum at the National Palace to formalize a US$4.2 billion investment commitment for 2026–2030. Identity/KYC implications for Ditto: the SOFIPO-to-banco múltiple transition triggers bank-grade Customer Due Diligence obligations across Nu México's full 15M customer base — enhanced CDD, full AML/CTF reporting (SMRs, TTRs), and CNBV identity verification standards that exceed the lighter SOFIPO regime. Executing this at digital-bank speed and scale — without a branch network — is the exact identity-verification-at-scale problem that drives demand for Ditto's architecture. Not in prior deltas.
  - Source: https://mexicobusiness.news/finance/news/nu-mexico-launch-commercial-banking-operations-aug-6
  - Source: https://thepaypers.com/fintech/news/nu-mexico-to-begin-operating-as-a-bank-from-6-august
  - Source: https://international.nubank.com.br/company/nu-mexico-receives-authorization-to-begin-operations-as-a-bank/
  - Source: https://www.pymnts.com/news/banking/2026/nubank-unit-secures-authorization-to-become-mexican-bank/
  - Date: 2026-08-06

### Pillar 7: Identity ecosystem

(no new M&A announcement, Forrester/KuppingerCole/Liminal Leadership Compass release, or major keynote dated 2026-08-04 to 2026-08-06. Visa×BioCatch $2.4B, Cyera×Oasis $1B, Okta CISO Insights, and Daon patent all covered in Aug 4–5 deltas. No new in-window print.)

---

## Next-cycle anchors (updated)

- **PSD3/PSR OJEU publication** — September 2026 tracking window confirmed by multiple law-firm trackers. Any OJEU notice number is an immediate content trigger.
- **UK DVS Trust Framework 1.0 enforcement (September 1 — 26 days)** — BSI confirmed as second accredited CAB alongside Kantara Initiative (both authorized under UKAS). UK CertifID trust mark launches September 1. OfDIA 6-week security review of DVS ecosystem running concurrently (completes approximately mid-September). Watch for provider refused certification or UKAS-recognition completion notice.
- **Microsoft Entra passkeys-by-default / SMS-voice OTP retirement (September 1 — 26 days)** — Hard date now <4 weeks. Active posting window. Temporary opt-out available Sept 1–Feb 1. Final SMS/voice retirement February 1, 2027.
- **Ofcom Use of Age Assurance statutory report (published July 27, 2026)** — Note: this first-party Ofcom report was published July 27 and not captured in prior deltas (cycles were tracking enforcement actions, not the statutory report). Report confirms 23× increase in age checks completed in H2 2025 and warns tougher enforcement coming. Source: https://www.ofcom.org.uk/online-safety/protecting-children/use-of-age-assurance-report-2026 — review for first-capture in a future cycle if not yet posted. Ofcom enforcement actions (post-July-31 deadline): still none named as of August 6.
- **AUSTRAC Tranche 2 compliance assessments (effective July 1)** — AUSTRAC confirmed "educative approach" for good-faith actors; enforcement focus on wilful non-compliance. Civil penalties up to AU$36.4M per contravention. No Federal Court filing or civil penalty notice found as of August 6.
- **EUDI wallet-availability deadline (December 24, 2026 — 140 days)** — Watch for member-state launch announcements and Commission deadline-risk statements.
- **EU AI Act Article 50 machine-readable content marking deadline for pre-August 2 GPAI systems (December 2, 2026)** — Watch for EU AI Office implementation guidance.
- **Mercosur cross-border digital ID (Decision 4/2026)** — Awaiting national-congress ratification in Argentina, Brazil, Paraguay, Uruguay.
- **Nu México banco múltiple KYC uplift watch** — CNBV/Banxico supervision begins August 6. Watch for CNBV compliance examination schedule or Nu México public CDD/onboarding roadmap announcement — a confirmed bank-grade identity rollout at 15M-customer scale is a LATAM case study.
- **Visa × BioCatch regulatory approval watch** — Expected to close Visa fiscal Q2 2027. Any competition-authority filing or conditional approval in EU/UK is a content trigger.
- **September NHI/agentic identity sweep** — Cyera×Oasis ($1B), Okta CISO data (58% of CISOs say AI governance + IAM is their biggest agentic concern), Daon three-patent governance series all pointing to September as the month NHI/agentic identity becomes a mainstream CISO topic.

---

## Run summary

- Findings count by pillar: P1 Banking: 0 | P2 EUDI: 0 | P3 Fraud/Deepfakes: 0 | P4 ZKP: **1** (FDD ZKP critical-infrastructure oversight analysis, Aug 4) | P5 Passwordless: 0 | P6 LATAM: **1** (Nu México full banco múltiple launch, Aug 6) | P7 Identity ecosystem: 0 — **Total: 2 findings across 2 pillars**
- Override-worthy: **1** — Nu México launches as banco múltiple August 6, 2026: largest digital bank in Mexico triggering bank-grade CDD across 15M customers, $4.2B investment commitment with Mexican government.
- Delta path: research/2026-08-06-cycle-delta.md
