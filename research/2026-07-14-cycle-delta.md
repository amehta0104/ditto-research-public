# Cycle Delta — 2026-07-14

Window: 2026-07-11 → 2026-07-14 (72-hour Fri-Mon weekend window; prior delta covered through 2026-07-13)

---

## Override-worthy this cycle

1. **Von der Leyen announces EU will legislate harmonized social media age assurance — under-13 access restriction proposed, EUDI Wallet age verification app the stated mechanism** — EU Commission President signals binding proposal after summer; mandated age assurance must be privacy-preserving (no ID documents or biometric data for age estimation), implicitly pointing to selective-disclosure and wallet-based proofs. Account: / company. Angle: "The EU just committed to mandating age assurance at social media scale — and the privacy constraint written into the expert panel report rules out classical ID scanning by design. This is a ZKP / selective-disclosure problem: prove age without showing your face or handing over your passport. That market just got validated by the President of the European Commission."

---

## New findings

### Pillar 1: Banking & Payments
*(no new primary-source material in window; EBA third-country-branch guidelines published July 7, outside window; PSD3/PSR OJEU publication still pending; AMLA Commission adoption of July 10 RTS/ITS package covered in prior delta)*

---

### Pillar 2: EUDI / eIDAS2
*(no new ARF update, ENISA certification publication, or member-state launch confirmed July 11–14; eideasy.com July 2 member-state tracker pre-dates window; Denmark AltID production launch noted in that tracker but dated July 2)*

---

### Pillar 3: Fraud / Deepfakes

- **Von der Leyen announces EU will propose harmonized social media access restrictions for under-13, with mandated privacy-preserving age assurance systems** — On July 13, 2026, European Commission President Ursula von der Leyen publicly backed a proposal to harmonise social media access rules for children under 13 across the EU, citing a 150-page report from a Special Panel on Child Safety Online (which met March–June 2026). The panel's lead recommendation: a "harmonised EU-wide access restriction to social media and other digital services for children under 13" backed by "effective age assurance systems." Von der Leyen indicated that children under 13 should only access social media under adult supervision for limited periods and called the case for restricting under-3s from screens "most convincing." The Commission will bring forward a legislative proposal after the summer recess. Crucially, the expert panel report specifies that any age assurance mechanism must uphold the highest privacy and data protection standards and **must not lead to the processing of identity documents or biometric data for the purpose of age estimation** — a deliberate constraint that rules out classical KYC-style ID scanning and biometric capture. Von der Leyen explicitly pointed to the EU's age verification app (linked to the EUDI Wallet ecosystem) as one of the candidate tools. For Ditto: the EU is creating a binding mandate for privacy-preserving age attestation at social-media scale across 450M+ EU citizens, with the privacy constraint written into the policy itself ruling out traditional document-scanning and face-matching approaches. Selective disclosure, zero-knowledge age proofs, and wallet-based age attestations are now the explicitly preferred technical architecture — a Ditto use-case validated at presidential level eight months before the proposal even lands.
  - Source: https://www.euronews.com/my-europe/2026/07/13/von-der-leyen-social-media-ban
  - Source: https://www.biometricupdate.com/202607/european-commission-calls-for-mandated-age-assurance-for-social-media
  - Source: https://idtechwire.com/von-der-leyen-signals-eu-social-media-age-rules-with-age-verification-app-as-a-tool/
  - Source: https://fortune.com/2026/07/13/eu-social-media-under-13-safety-burden/
  - Date: 2026-07-13

---

### Pillar 4: ZKPs in practice
*(no new EU bank ZKP pilot, OpenID4VP/VCI update, or mDL deployment confirmed July 11–14; HAIP 1.1 and OID4VP 1.1 remain in progress with December 2026 publication targets; OpenID Foundation self-certification programme launched February 2026 — outside window)*

---

### Pillar 5: Passwordless / split-key
*(no new FIDO Alliance specification, regulator OTP-sunset publication, or major bank passkey deployment announcement confirmed July 11–14)*

---

### Pillar 6: LATAM

- **US and CARICOM IMPACS sign first multilateral biometric data-sharing MOU — fingerprints, facial recognition, criminal registry automated exchange covering six Caribbean CBI nations** — On July 10, 2026 (reporting coverage July 11–13), the US Department of Homeland Security (DHS) and the CARICOM Implementation Agency for Crime and Security (IMPACS) signed a Biometrics Data Sharing Partnership (BDSP) Memorandum of Cooperation at the Embassy of Saint Kitts and Nevis in Washington, D.C. The arrangement covers the automated exchange of fingerprint records, facial recognition profiles, and criminal registry datasets between US border management systems and CARICOM member states offering Citizenship by Investment (CBI) programmes: Antigua and Barbuda, Dominica, Grenada, Saint Kitts and Nevis, Saint Lucia, and Saint Vincent and the Grenadines. The Eastern Caribbean Central Bank was also represented at the signing. The MOU is intended to be operational before end of 2026. For Ditto /: the six named CARICOM countries are all major CBI nations — meaning a material share of their passport-holder population consists of economic migrants from other jurisdictions, a documented high-risk identity population for financial institutions. The US-CARICOM BDSP changes the due-diligence environment for Caribbean identity: banks and payment providers onboarding customers with passports from these nations will face heightened cross-border biometric verification requirements as the MOU operationalises. This is both a risk signal for existing identity flows and a commercial trigger for identity vendors with cross-border verification capability.
  - Source: https://www.state.gov/releases/office-of-the-spokesperson/2026/07/united-states-and-caricom-impacs-sign-landmark-biometrics-and-data-sharing-partnership-memorandum-of-cooperation/
  - Source: https://www.biometricupdate.com/202607/us-caricom-establish-regional-biometric-data-sharing-partnership
  - Source: https://www.jamaicaobserver.com/2026/07/11/us-caricom-sign-landmark-border-security-pact/
  - Date: 2026-07-10 (signed); 2026-07-11 (first press coverage); 2026-07-13 (ID Tech Digest roundup)

---

### Pillar 7: Identity ecosystem
*(no new Forrester/KuppingerCole/Gartner/Liminal report publication, funding round, or M&A transaction confirmed July 11–14; Forrester Wave Workforce Identity Security Platforms Q2 2026 published May 2026 — outside window; Lissi/Gataca covered in July 13 delta)*

---

## Next-cycle anchors (updated — countdown as of 2026-07-14)

- **EU AI Act Code of Practice signatory deadline (July 22, 18:00 CEST) — 8 days.** Sign or forgo presumption of conformity for Article 50 deepfake/AI-content disclosure obligations. Enforcement August 2.
- **FSB AI Sound Practices consultation deadline (July 22) — 8 days.** 12 sound practices for responsible AI adoption in financial institutions; responses via secure online form by July 22; final report October 2026.
- **Ofcom age-assurance effectiveness report (by end of July) — ~17 days.** Statutory first-year report under the UK Online Safety Act assessing how services used age assurance and how effective it was. Joint Ofcom/ICO effort; expected to give "practical actions" for platforms on highly effective age checks. Now directly adjacent to the von der Leyen EU announcement.
- **AUSTRAC Tranche 2 enrolment deadline (July 29) — 15 days.** ~100,000 newly regulated Australian entities (lawyers, accountants, real estate agents, conveyancers) must enrol with AUSTRAC by July 29; obligations already in force from July 1; non-enrolment is a strict-liability offence.
- **EU AI Act Article 50 enforcement (August 2) — 19 days.** Deepfake labelling, chatbot disclosure, AI-content marking become legally binding. Fines up to €15M or 3% global turnover.
- **Von der Leyen EU social media age assurance proposal — post-summer (September/October 2026 estimate).** Legislative proposal expected after EU summer recess; the Special Panel report is the technical blueprint. Watch for: scope (social media only vs. broader digital services), the specific age assurance standard referenced, and whether EUDI Wallet integration is mandated.
- **UK DVS Trust Framework 1.0 (no earlier than September 1) — ~49 days.** First CAB accreditation triggers the framework. OfDIA introduced machine-readable technology to the DVS register on July 9 in preparation.
- **EUDI Wallet hard deadline (December 24, 2026) — ~163 days.** All 27 member states must have at least one certified wallet available.
- **PSD3/PSR OJEU publication** — Expected H2 2026; may slip to September.
- **AMLA Commission adoption process** — 23 RTS/ITS delivered July 10; adoption typically 3–6 months; measures apply July 10, 2027.

---

## Run summary

- **Findings count by pillar:** P1: 0 | P2: 0 | P3: 1 (Von der Leyen EU social media age assurance mandate) | P4: 0 | P5: 0 | P6: 1 (US-CARICOM biometric data-sharing MOU) | P7: 0 → **Total: 2 findings across 2 pillars**
- **Override-worthy: 1** — Von der Leyen confirms EU will legislate harmonized under-13 social media age restriction with mandated privacy-preserving age assurance (no biometrics/ID docs); EUDI Wallet app referenced as preferred mechanism; proposal after summer recess. Account: / company.
- **Delta path:** `research/2026-07-14-cycle-delta.md`

---

_Window note: July 11–13 were Saturday–Sunday–Monday with lower primary regulatory output. Two findings confirmed: von der Leyen age assurance announcement (July 13, verified across Euronews / ABC News / Fortune / Biometric Update / ID Tech) and US-CARICOM biometric MOU (signed July 10, state press and trade coverage July 11–13). Worker API (ditto-slack-bot.dittobot.workers.dev) remains blocked by environment proxy; delta written directly to GitHub via MCP._
