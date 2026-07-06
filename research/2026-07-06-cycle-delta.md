# Cycle Delta — 2026-07-06

Window: 2026-07-03 → 2026-07-06 (last 72 hours — Sunday run, weekend window Fri→Sun)

## Override-worthy this cycle

1. **Switzerland delays Swiyu national e-ID to H1 2027, explicitly citing AI deepfakes and malware as the security threats it cannot yet defeat** — Switzerland's Federal Office of Justice confirmed that the planned July 2026 internal testing phase for the Swiyu e-ID has been postponed, with full public launch not expected until the first half of 2027. The stated reasons are specific: additional technical measures are needed to resist deepfake-based issuance fraud and malware infiltration during online identity enrollment. Account:. Angle: the first major non-EU nation to publicly state that deepfakes have delayed its national digital identity infrastructure — the inverse of Australia's mandate moment; here, deepfakes are the blocker, not the demand driver.

## New findings

### Pillar 1: Banking & Payments
(no new material in window — AMLA July 10 deadline now 4 days away; no early submission confirmed; no new EBA, ECB, FCA/PSR, or PSD3/PSR OJEU announcement confirmed July 3–6.)

### Pillar 2: EUDI / eIDAS2
- **Switzerland delays Swiyu national e-ID to H1 2027, citing deepfakes and malware infiltration as disqualifying security risks** — The Federal Office of Justice (FOJ) announced that the internal testing phase planned for July 2026 has been postponed; the full public launch of Switzerland's state-issued, open-source Swiyu e-ID wallet will not occur until H1 2027. The FOJ statement is unusually specific: the system needs additional technical measures to (i) resist malware infiltration on end-user devices during online issuance, (ii) detect deepfakes during enrollment, and (iii) incorporate opposition-party proposals on data protection and security standards — all of which remain unfinished. This is Switzerland's third announced delay: original timeline was early 2026 (pre-voter referendum completion), then December 2026 (after the March 2026 slip), now H1 2027. The explicit deepfake rationale is significant: Switzerland is the first sovereign government to publicly cite AI-generated deepfakes as a security concern serious enough to block a national digital identity rollout. Context: Switzerland is not EU but closely mirrors eIDAS 2 architecture; Swiyu is already built on open-source OID4VCI/VP standards and its delay signals to EU member states still finalising online-issuance security models that the liveness + cryptographic issuance problem is real and unsolved.
  - Source: https://www.biometricupdate.com/202607/switzerland-delays-digital-id-rollout-to-strengthen-trust-infrastructure
  - Source: https://www.thelocal.ch/20260701/why-the-introduction-of-switzerlands-e-id-being-is-being-delayed
  - Source: https://www.swissinfo.ch/eng/swiss-ai/introduction-of-e-id-delayed-for-security-reasons/91675866
  - Date: 2026-07-01 (FOJ announcement; missed by July 3 delta)

### Pillar 3: Fraud / Deepfakes
(no new primary-source report or named bank deepfake incident in window — Persona H1 2026 selfie fraud report covered in July 2 delta; no new iProov, Veriff, or Sumsub publication confirmed July 3–6.)

### Pillar 4: ZKPs in practice
(no new bank ZKP pilot, OpenID4VP/VCI update, or mDL deployment confirmed in window.)

### Pillar 5: Passwordless / split-key
(no new material in window — no new FIDO Alliance specification, passkey deployment announcement, or regulator OTP-sunset publication confirmed July 3–6.)

### Pillar 6: LATAM
(no new material in window — Brazil DeCripto effective July 1 covered in July 2 delta; no new BCB, CNBV, Superfinanciera, CMF, or SBS publication confirmed July 3–6.)

### Pillar 7: Identity ecosystem
- **Google Wallet credential acceptance wave: OneID (UK), Authologic (global), and Signicat × TrustTech announce integrations in the same week — Google Wallet emerging as a de facto B2B credential layer ahead of EUDI** — Three separate identity verification vendors announced Google Wallet credential acceptance in the same week (published ID Tech Digest July 3, 2026; Biometric Update July 2026). (1) **OneID** (UK-based, backed by major banks) announced it will support identity verification using credentials presented via Google Wallet, enabling organisations to facilitate KYC onboarding, age assurance, account access and fraud prevention using government-issued digital credentials; live in the UK market and complements OneID's bank-based verification network under the DVS Trust Framework. (2) Polish IDV vendor **Authologic** announced a partnership with Google enabling businesses to accept Google ID Pass — digital passports and government-issued credentials — through Google Wallet for corporate onboarding workflows via its OmniID platform; supports U.S. and UK-issued credentials. (3) Nordic eID vendor **Signicat** announced a partnership with TrustTech to help regulated businesses build eIDAS 2.0-compliant reusable identity processes through private wallet ecosystems. Taken together: Google Wallet is moving into position as the pre-EUDI credential acceptance layer for commercial KYC, with commercial IDV vendors using Google's distribution to solve the relying-party integration problem before EUDI wallets hit critical mass. For Ditto: the orchestration layer question — who connects which credentials to which relying parties — is being answered by commercial partnerships rather than EUDI ARF alone; the identity ecosystem is not waiting for the December 24, 2026 wallet deadline.
  - Source: https://idtechwire.com/id-tech-digest-july-3-2026/
  - Source: https://www.biometricupdate.com/202607/wallet-interoperability-takes-shape-as-googles-influence-grows
  - Source: https://oneid.uk/news-and-events/oneid-expands-its-digital-verification-access-network-with-google-wallet-credentials
  - Source: https://www.pymnts.com/authentication/digital-identity/2026/google-launches-digital-id-partnership-with-polands-authologic/
  - Date: 2026-07-03 (ID Tech Digest July 3, 2026)

---

## Next-cycle anchors (updated)

- **AMLA 23 RTS/ITS/guidelines → Commission (July 10)** — 4 DAYS. Single biggest EU KYC/identity regulatory event of July 2026: CDD, business-relationship, and ongoing-monitoring standards that define what "compliant" identity verification looks like under the AMLR from July 2027. Watch amla.europa.eu for post-submission publication.
- **FSB AI Sound Practices virtual outreach event (July 7 — TOMORROW, 13:00–15:00 CEST)** — 12 sound practices across the full AI lifecycle for financial institutions; publicly accessible, register at fsb.org. Consultation deadline July 22.
- **Ofcom statutory age-assurance effectiveness report (by July 17)** — 11 days. Statutory first-year report on Online Safety Act child-safety duties; will set public compliance baseline for age-assurance vendors.
- **EU AI Act Code of Practice signatory deadline (July 22, 18:00 CEST)** — 16 days. Sign for legal presumption of conformity with Article 50 deepfake/AI-content disclosure obligations; final Code published June 10.
- **FSB AI Sound Practices consultation deadline (July 22)** — 16 days.
- **EU AI Act Article 50 enforcement (August 2)** — 27 days. Deepfake labelling, chatbot disclosure, AI-content marking become binding; fines up to €15M or 3% global turnover.
- **AUSTRAC Tranche 2 enrolment deadline (July 29)** — 23 days. ~100,000 newly in-scope entities must enrol with AUSTRAC.
- **FATF seventh targeted update on VA/VASP Standards** — Approved at June 17–19 plenary; not yet published; addresses DeFi, stablecoins, unhosted wallets. Watch fatf-gafi.org.
- **UK People's Panel on Digital ID — report publication** — TBD; deliberation concluded June 21.
- **UK DVS Trust Framework 1.0 enforcement (September 1)** — 57 days. OSP certification active; UK CertifID trust mark.
- **EUDI Wallet hard deadline (December 24, 2026)** — All EU member states must make wallet available; Ireland in pilot stage; Germany DIdG confirmed January 2, 2027 launch.
- **Japan JSDA phishing-resistant MFA mandatory deadline** — "summer 2026"; watch for JSDA finalization.
- **PSD3/PSR OJEU publication** — H2 2026; no confirmed date.

---

## Run summary

- Findings count by pillar: P2 EUDI/eIDAS2: 1 (Switzerland Swiyu e-ID delayed to H1 2027 — deepfakes and malware cited as security disqualifiers; missed by July 3 delta) | P7 Identity ecosystem: 1 (Google Wallet credential acceptance wave — OneID, Authologic, Signicat × TrustTech — July 3, 2026) → **Total: 2 findings across 2 pillars**
- Override-worthy: **1** — Switzerland Swiyu e-ID delay to H1 2027 citing deepfakes: first national government to publicly state that deepfakes have blocked its digital identity rollout. Account:.
- Delta path: research/2026-07-06-cycle-delta.md

---

_Note: Worker API (ditto-slack-bot.dittobot.workers.dev) is blocked by the environment's network egress allowlist (403 policy denial on CONNECT); skill/pillar files were not loaded from the worker. Delta written directly to GitHub via MCP. To restore full skill-file context, add `ditto-slack-bot.dittobot.workers.dev` to the environment's network egress allowlist._
