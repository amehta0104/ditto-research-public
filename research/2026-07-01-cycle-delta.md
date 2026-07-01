# Cycle Delta — 2026-07-01

Window: 2026-06-29 → 2026-07-01 (last 48 hours — Tuesday run)

## Override-worthy this cycle

1. **UK DVS Trust Framework v1.0 final — first statutory rules for orchestration service providers take effect September 1.** Account: / company. Angle: The UK government has formally codified the orchestration layer into law. DVS Trust Framework 1.0 creates the first statutory certification category for orchestration service providers — the companies that connect verified credentials to relying parties. OSPs must register and confirm their orchestrated services are on the DVS register. Certified providers earn the UK CertifID trust mark. After September 1, the regulatory perimeter is drawn and the category is named.

## New findings

### Pillar 1: Banking & Payments
- **MiCA CASP enforcement now live (July 1, 2026) — ESMA, EBA, AMLA in tripartite coordinated enforcement mode; ~83% of EU crypto firms remain unlicensed** — The MiCA CASP transitional period has officially expired as of today. ESMA's June 23 public statement (ESMA75-113276571-1710) formalised the coordinated enforcement architecture: ESMA and NCAs are now actively monitoring significant unauthorised cross-border CASPs and will take coordinated action where needed, working jointly with EBA and AMLA. NCAs must verify that wind-down plans exist and are being implemented; penalties for unauthorised operation reach €5M or 3% of global annual turnover. As of today, approximately 204 firms hold full CASP authorisation out of 1,200+ pre-MiCA registrants — an ~83% unlicensed rate. Named exits confirmed before the deadline: Binance (EU, France relicensing pending), KuCoin (banned Austria, February 2026), Gemini (withdrew April 2026). Named licensed survivors: Coinbase, Kraken, OKX, Crypto.com. The AMLA involvement is notable: this is the first enforcement context in which AMLA coordinates directly with ESMA on a named-sector action, signalling how the AML authority intends to operate alongside capital markets regulators going forward. For Ditto: the post-July 1 EU crypto market concentrates KYC/AML/identity demand into a smaller set of highly regulated firms — the firms most likely to procure enterprise-grade identity infrastructure with robust CDD controls.
  - Source: https://www.esma.europa.eu/sites/default/files/2026-06/ESMA75-113276571-1710_Public_Statement_MiCA_transitional_period_ends.pdf
  - Source: https://finance.yahoo.com/markets/crypto/articles/july-1-mica-deadline-looms-103215096.html
  - Source: https://blog.kraken.com/product/kraken-institutional/mica-enforcement-begins-july-1
  - Date: 2026-07-01 (enforcement active); ESMA public statement 2026-06-23

### Pillar 2: EUDI / eIDAS2
(no new material in window — EUDI ON Community Event (June 25, Berlin) brought ~400 stakeholders including German Federal Digital Minister Karsten Wildberger; Germany's DIdG advances through Bundestag with January 2, 2027 EUDI Wallet launch confirmed; no new ARF update, Commission implementing act, or ENISA announcement published in June 29–July 1 window. September 2026 member-state wallet-readiness deadline remains the next hard anchor.)

### Pillar 3: Fraud / Deepfakes
(no new primary-source report or named bank incident published in window — Shufti Deepfake Fraud Index covered in June 26 delta; PYMNTS synthetic borrower report covered in June 30 delta; WEF "Unmasking Cybercrime" report is January 2026.)

### Pillar 4: ZKPs in practice
(no new bank ZKP pilot, OpenID4VP, or mDL deployment announced in window.)

### Pillar 5: Passwordless / split-key
(no new material in window — BSP Circular 1213 hard stop and liability-shift covered as completed in June 30 delta. FIDO Alliance World Passkey Day data (5B passkeys, May 6) and OpenAI FIDO membership (April) covered in prior cycles. No new FIDO spec or regulator OTP-sunset publication in window.)

### Pillar 6: LATAM
(no new material in window — Brazil Drex privacy bill second committee passage (June 12) covered in June 15 delta; BCB architecture unchanged. No new BCB, CNBV, Superfinanciera, CMF, or SBS publication confirmed in June 29–July 1 window.)

### Pillar 7: Identity ecosystem
- **Jumio integrates Trinsic — first major IDV incumbent to accept EUDI wallets, mDLs, and reusable credentials across 60+ countries/territories at scale (June 25, 2026 — missed by June 29 cycle)** — Jumio announced a partnership with Trinsic (a digital ID gateway) that embeds acceptance of mobile driver's licences, EU Digital Identity Wallet credentials, eIDs, and reusable credentials directly into Jumio's verification pipeline alongside its existing biometric checks. Jumio claims this makes it "the first identity intelligence provider to offer Global Digital ID acceptance at scale," covering 60+ countries and territories. Mechanism: Trinsic's credential gateway handles credential-type accreditation so Jumio customers do not each bear the per-format integration burden; Jumio brings liveness detection, biometric matching, and risk analysis on top. Strategic signal for Ditto: the major IDV incumbents are no longer treating credential wallets as a competitive threat — they are integrating them. The competitive battleground shifts to *which* credential formats a relying-party integration supports and how smoothly the biometric + credential composition layer works. The orchestration question — who manages the composition of credential types, trust frameworks, and relying-party obligations — is the layer Ditto occupies and the layer the UK DVS Framework (below) has now formally named.
  - Source: https://www.jumio.com/about/press-releases/global-digital-id-acceptance/
  - Source: https://fintechnews.sg/133677/regtech/jumio-digital-id-acceptance-trinsic/
  - Source: https://www.biometricupdate.com/202606/jumio-integrates-trinsic-to-expand-reach-in-growing-idv-market
  - Date: 2026-06-25 (Jumio press release / Morningstar 20260625046687); missed by June 29 cycle which covered the same window

- **UK DVS Trust Framework v1.0 final — first statutory rules for orchestration service providers; September 1 enforcement; UK CertifID trust mark introduced (June 10, 2026 — missed by all prior cycles)** — GOV.UK published the final v1.0 of the UK Digital Verification Services Trust Framework on June 10, 2026, following a March 3 pre-release. The most significant change for Ditto's market: the first dedicated statutory rules for **orchestration service providers (OSPs)** have been formalised. Key requirements: (1) OSPs must be able to confirm whether the services they orchestrate are on the DVS register — either via live API or cached register lookups; (2) a single service can be certified as an OSP concurrently with other roles (identity SP, attribute SP, holder SP), enabling compound-architecture certification; (3) the framework has been renamed from DIATF to "UK digital verification services trust framework" to align with the Data (Use and Access) Act. Enforcement date: September 1, 2026, when the framework comes into force once the first conformity assessment body is accredited. Providers already certified at the gamma (0.4) stage move across via a tailored delta uplift rather than a full re-audit. Certified providers earn the UK CertifID trust mark — a government-endorsed signal of statutory compliance that relying parties and procurers can use to assess vendors. For Ditto: this is the regulatory moment that formalises the orchestration layer as a certifiable, regulated category in the UK's statutory identity framework. The orchestration service provider role is now explicitly recognised and separately regulated, distinct from identity providers, attribute providers, and holder services — each role now carries its own certification requirement and trust-mark eligibility. Ditto's go-to-market in the UK has a formal regulatory hook from September 1. The Jumio/Trinsic integration above shows incumbents converging on the same orchestration/composition problem from the IDV side.
  - Source: https://www.gov.uk/government/publications/uk-digital-verification-services-trust-framework-1-0/uk-digital-verification-services-trust-framework-1-0-pre-release
  - Source: https://enablingdigitalidentity.blog.gov.uk/2026/06/10/final-release-of-the-1-0-trust-framework-what-does-it-mean-for-you/
  - Source: https://idtechwire.com/uk-publishes-pre-release-of-dvs-trust-framework-1-0-for-digital-verification-services/
  - Date: 2026-06-10 (final published); pre-release 2026-03-03; enforcement 2026-09-01; missed by all prior cycles

---

## Next-cycle anchors (updated)

- **AMLA CDD / sanctions / business-relationship RTS final drafts → Commission (July 10)** — 9 days. Four mandates legally due. Watch for AMLA publication and Commission delegated act timeline.
- **FATF seventh targeted update on VA/VASP Standards (July 2026)** — Approved at June 17–19 plenary; due for publication July 2026; addresses DeFi, stablecoins, unhosted wallets. Watch fatf-gafi.org.
- **Ofcom statutory age-assurance effectiveness report (July 17)** — 16 days.
- **FSB AI Sound Practices consultation deadline (July 22)** — 21 days. G20-level AI governance vocabulary being written now; final report to G20 Finance Ministers October 2026.
- **EU AI Act Code of Practice signatory deadline (July 22)** — 21 days. Window closes 18:00 CEST; signatories receive legal presumption of conformity with Article 50 deepfake/AI-content disclosure obligations.
- **EU AI Act Article 50 enforcement (August 2)** — 32 days. Deepfake labelling, chatbot disclosure, AI-content marking become binding.
- **UK DVS Trust Framework 1.0 enforcement (September 1)** — 62 days. First conformity assessment body accreditation; OSP certification active; UK CertifID trust mark introduced. New anchor.
- **France AMF MiCA enforcement** — Watch for AMF action against continuing unlicensed operators now July 1 deadline has passed; Binance France application timeline.
- **BSP Circular 1213 post-deadline compliance data** — Watch for BSP compliance rate announcement or first enforcement action.
- **Germany DIdG Bundestag first reading** — TBD; summer recess likely delays to September; EUDI Wallet launch confirmed January 2, 2027.
- **UK People's Panel on Digital ID — report publication** — TBD post-June 21 deliberation close (Ipsos writing final report).
- **PSR APP-fraud reimbursement independent review (Frontier Economics)** — Q2/Q3 2026; not yet published.
- **PSD3/PSR OJEU publication** — H2 2026; no confirmed date; may slip to September.
- **Japan JSDA phishing-resistant MFA mandatory deadline** — "summer 2026"; watch for JSDA formal finalization.
- **FSB AI Sound Practices final report → G20 Finance Ministers (October 2026).**

---

## Run summary

- Findings count by pillar: P1 Banking: 1 (MiCA enforcement now live — July 1 anchor closure + AMLA coordination angle) | P2 EUDI: 0 | P3 Fraud: 0 | P4 ZKP: 0 | P5 Passwordless: 0 | P6 LATAM: 0 | P7 Identity ecosystem: 2 (Jumio × Trinsic global credential acceptance — missed; UK DVS Trust Framework v1.0 OSP rules — missed) → **Total: 3 findings across 2 pillars**
- Override-worthy: **1** — UK DVS Trust Framework v1.0: first statutory certification category for orchestration service providers, September 1 enforcement, UK CertifID trust mark — the regulatory moment that names and legitimises the orchestration layer Ditto occupies. Account: / company.
- Delta path: research/2026-07-01-cycle-delta.md

---

_Note: Worker API (ditto-slack-bot.dittobot.workers.dev) is blocked by the environment's network egress allowlist; skill/pillar files were not loaded from the worker. Delta written directly to GitHub. To restore full skill-file context, add `ditto-slack-bot.dittobot.workers.dev` to the environment's network egress allowlist._
