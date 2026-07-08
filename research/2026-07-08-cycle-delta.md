# Cycle Delta — 2026-07-08

Window: 2026-07-06 → 2026-07-08 (last 48 hours — Wednesday run). Quiet mid-week window: the July 6 ID Tech digest cluster (eIDAS Dashboard trust registry, IETF age-verification draft, Incode×Auth0, CaixaBank×Visa) was fully mined by the July 6 and July 7 deltas. Two genuinely new, in-window items this cycle: (1) a **Biometric Update July 6 feature** documenting the industry shift from one-time onboarding checks to **continuous / behavioural identity verification** in banking, carrying fresh hard loss stats and a concrete EU banking deployment (Air Bank / Innovatrics, PSD2); (2) **Biometric Update July 7** reporting the **UK Digital ID Advisory Group will not publish its minutes or budget** — a governance/transparency signal for the UK DVS ecosystem. AMLA's four CDD/business-relationship/sanctions RTS are due to the Commission **July 10 (2 days)** — the single biggest near-term KYC/identity regulatory event — but no early submission is confirmed inside the window.

## Override-worthy this cycle

1. **"One-time KYC is over": a Biometric Update July 6 feature frames continuous / behavioural verification as the new banking baseline, backed by fresh loss data — one institution logged 8,065 deepfake attempts in eight months tied to $347M in verified losses; US account-takeover losses hit $15.6B in 2024 (up from $12.7B in 2023, Fed data); synthetic-identity fraud rose ~8× YoY to ~11% of all global fraud (Biometric Update, July 6, 2026).** Account: company /. Angle: the onboarding check was never the finish line — it's the moment an identity is *cleanest*, and fraud has moved to everything after it (session takeover, deepfake-assisted re-auth, synthetic identities aged over months). The market is now openly repricing identity from a one-time gate to a continuous assurance surface — exactly the orchestration + mobile-threat-defence layer, not the point capture step. POV hook: "You verified them at signup. Then a deepfake re-authenticated as them at month six. Identity is not an event; it's a state you have to keep proving." Critique the pattern; do not name a vendor. Cross-listed P1, P6, P8.

## New findings

### Pillar 1: Banking & Payments
- **Air Bank (Czechia) deploys Innovatrics face verification for mobile-app device pairing to satisfy PSD2 strong customer authentication — a concrete in-window banking-channel biometric deployment (reported Biometric Update, July 6, 2026; cross-listed from P7)** — Inside the same July 6 fraud-escalation feature, Air Bank is cited deploying passive facial verification to bind a customer to their device during mobile-app pairing, meeting PSD2 SCA requirements. For Ditto: a tier-2 EU bank using biometric device-binding as the SCA factor is a datapoint that the wallet/passkey/biometric SCA convergence (baseline standing theme: "the wallet becomes the canonical SCA factor") is happening at the mid-market, not just the tier-1s — and that device-binding, not document capture, is where banks are spending. Ecosystem datapoint — critique the pattern, never name a vendor.
  - Source: https://www.biometricupdate.com/202607/global-fraud-escalation-drives-new-wave-of-biometric-and-continuous-verification-in-banking
  - Date: 2026-07-06
- **(Anchor — 2 days out) AMLA CDD / business-relationship / ongoing-monitoring / sanctions-screening RTS final drafts due to the European Commission July 10** — Four Level-2 mandates legally due under AMLR Art. 28(1) etc.; these define what "compliant" customer due diligence and identity verification look like under the AMLR (underlying requirements apply from July 10, 2027). AMLA consulted on the draft RTS (consultations opened Feb 9, 2026; first two closed May 8). No early submission or publication confirmed inside July 6–8. Watch amla.europa.eu after July 10.
  - Source: https://www.amla.europa.eu/policy/regulatory-instruments_en
  - Date: 2026-07-10 (due date)

### Pillar 2: Identity orchestration
- **UK Digital ID Advisory Group declines to publish its minutes or disclose budget details — transparency gap around the UK's digital-ID programme complicates the DVS-certified vendor ecosystem's ability to shape policy (Biometric Update, July 7, 2026)** — The advisory group supporting the UK government's digital-ID work (operationally supported by the Cabinet Office Digital ID Task Force) said it will not publish meeting minutes or disclose budget allocation, on the grounds that it is "not a decision-making body." A Conservative MP criticised the response; broader political uncertainty around the UK scheme persists. For Ditto: the firms certified under the UK **DVS Trust Framework** have been positioning as ready-made infrastructure for whatever digital-ID mandate emerges, and governmental opacity plus political flux weakens their ability to influence direction — a reminder that in the UK the orchestration/relying-party layer is being shaped as much by governance and politics as by technology. Ecosystem/governance datapoint — do not name a vendor. Watch the DVS Trust Framework 1.0 enforcement (Sept 1) and any People's-Panel/advisory output for the actual policy signal.
  - Source: https://www.biometricupdate.com/202607/uk-digital-id-advisory-group-will-not-publish-minutes-disclose-budget-details
  - Date: 2026-07-07

### Pillar 3: EUDI / eIDAS2
(no new discrete in-window item. The July 4 Biometric Update wallet roundup — Romania adopting Germany's EUDI model, Ireland moving to pilot, Zetes/Belgium MyGov e-signatures, TrustED Consortium pilots — is out of the July 6–8 window and its net-new pieces (Wultra €6.8M, Signicat×TrustTech, Google Wallet acceptance wave) were captured in the July 3/6/7 deltas. eIDAS Dashboard → operational trust registry and the December 6, 2026 wallet-availability deadline remain the standing anchors, both covered July 7.)

### Pillar 4: KYC / AML compliance
(no new discrete in-window publication. **AMLA four RTS drafts due to the Commission July 10 (2 days)** is the dominant near-term event — see P1 anchor. FATF seventh targeted update on VA/VASP standards (approved June 17–19 plenary) still pending publication; last *published* update remains June 2025. AUSTRAC Tranche 2 enrolment deadline July 29. No new AMLA/FATF/sanctions action confirmed inside July 6–8.)

### Pillar 5: Customer onboarding
(no new discrete onboarding-KPI benchmark published inside July 6–8. Standing benchmarks unchanged: Signicat ~68% average fintech onboarding drop-off; Fenergo Oct 2025 — 70% of FIs lost prospects to slow/complex onboarding, up from 67% in 2024; ~€5.7B/yr wasted EU acquisition spend; document re-upload makes abandonment 3× more likely. The in-window signal is indirect: the continuous-verification shift (override; P7) moves onboarding economics toward "verify once, keep proving" — friction and cost migrate to the layer that maintains assurance over the lifecycle, not just at signup.)

### Pillar 6: Identity verification (IDV)
- **Continuous / behavioural verification reframes IDV from a signup gate to a lifecycle assurance surface (cross-listed from P7/override, July 6, 2026)** — IDV read: the July 6 feature makes the case that a passed onboarding check is no longer sufficient assurance — deepfake-assisted re-authentication, session takeover and slow-built synthetic identities all defeat one-time verification, pushing banks toward continuous biometric + behavioural signals. The differentiator becomes *sustained* identity confidence, not the accuracy of a single capture. Convergence of IDV and authentication into one assurance layer continues (cf. Incode×Auth0, July 7 delta). See override / P7. No new iBeta/NIST IAL/FIDO Document Authenticity WG output confirmed in window.
  - Source: https://www.biometricupdate.com/202607/global-fraud-escalation-drives-new-wave-of-biometric-and-continuous-verification-in-banking
  - Date: 2026-07-06

### Pillar 7: Fraud / Deepfakes
- **Biometric Update feature: global fraud escalation drives a new wave of biometric + continuous verification in banking — one institution logged 8,065 deepfake attempts in 8 months ($347M verified losses); synthetic-identity fraud up ~8× YoY to ~11% of all global fraud; US account-takeover losses $15.6B in 2024 (from $12.7B in 2023, Fed data); ATO affected 6M victims in 2025, +141% since 2021; LATAM = 48.3% of synthetic-identity cases (Biometric Update, July 6, 2026)** — A synthesis feature arguing that one-time KYC no longer holds against AI-driven fraud, and that banks are moving to continuous / behavioural / biometric verification across the session lifecycle. Named datapoints: **Air Bank** (Czechia) deployed **Innovatrics** face verification for PSD2 app-pairing; **YEO Messaging × ReconIQ** partnered to roll continuous biometric verification across US banks; **Liminal + Unico** released a fraud-intelligence report on the "sophistication ladder" of attacks. For Ditto: this is the clearest in-window articulation of the core thesis — identity assurance is a *continuous* state, not a one-time event — and the loss numbers make the market case for layered liveness + injection-attack resistance + device binding + behavioural signals. This is the fresh cluster of the cycle. Flagged honestly: it is a synthesis/roundup piece, not a single primary threat-intel disclosure; the underlying stats aggregate multiple sources. No new named-bank deepfake *incident* dated July 6–8 confirmed. Anchor: EU AI Act Art. 50 deepfake-labelling enforcement August 2 (Code of Practice signatory deadline July 22). Cross-listed P1, P6, P8; see override #1.
  - Source: https://www.biometricupdate.com/202607/global-fraud-escalation-drives-new-wave-of-biometric-and-continuous-verification-in-banking
  - Date: 2026-07-06

### Pillar 8: Mobile trust & app security
(no new in-window disclosure. Anatsa (now targeting 800+ FIs, added Germany/South Korea), RatOn NFC-relay and related banking-malware families remain active per prior deltas and threat-intel, but no new named campaign or CVE dated July 6–8 confirmed; no SS7/SIM-swap breach in window. The continuous-verification theme (override/P7) is the mobile-trust-adjacent signal: device binding + behavioural signals on the handset are where banks are hardening the session beyond the login moment.)

### Pillar 9: Passwordless / split-key
(no new material in window. No new FIDO Alliance specification, passkey-adoption stat (State of Passkeys 2026 / 5B-passkey data is World Passkey Day, May 6), or regulator OTP-sunset publication confirmed inside July 6–8.)

### Pillar 10: ZKPs in practice
(no new bank ZKP pilot, OpenID4VP/VCI deployment or mDL milestone confirmed inside July 6–8. IETF "Age Verification Architecture" draft evaluating ZKPs vs. verifiable credentials was July 6 and is covered in the July 7 delta.)

### Pillar 11: Age assurance & privacy attributes
(no new discrete in-window item. Hard anchor unchanged: **Ofcom statutory age-assurance effectiveness report due end-July 2026** (first-year Online Safety Act report; will set the public compliance baseline; ~100 services under investigation, Kick fined £800k in Feb 2026). IETF age-verification draft and eIDAS Age Verification Trusted List were July 6 and are covered in the July 7 delta. No new Ofcom enforcement action confirmed inside July 6–8.)

---

## Next-cycle anchors (updated)

- **AMLA CDD / business-relationship / ongoing-monitoring / sanctions RTS final drafts → Commission (July 10)** — 2 DAYS. Four Level-2 mandates legally due; single biggest near-term identity/KYC regulatory event. Watch amla.europa.eu for publication after submission.
- **Ofcom statutory age-assurance effectiveness report (end-July)** — first-year OSA report; establishes the public compliance baseline for age-assurance vendors/platforms.
- **EU AI Act Code of Practice signatory deadline (July 22)** — 14 days; signatories gain presumption of conformity with Art. 50.
- **FSB AI Sound Practices consultation deadline (July 22)** — 14 days; 12 sound practices across the AI lifecycle for financial institutions.
- **AUSTRAC Tranche 2 enrolment deadline (July 29)** — 21 days; ~100,000 newly in-scope entities must enrol.
- **EU AI Act Article 50 enforcement (August 2)** — 25 days; deepfake labelling, AI-content marking, chatbot disclosure become binding (fines up to €15M / 3% global turnover).
- **UK DVS Trust Framework 1.0 enforcement (September 1)** — first conformity-assessment-body accreditation; OSP certification active; UK CertifID trust mark. Linked to the alcohol-age-check SI and (informally) the City of London DVO orchestration model. Watch alongside the Digital ID Advisory Group transparency question (P2 this cycle).
- **FATF seventh targeted update on VA/VASP Standards (2026)** — DeFi, stablecoins, unhosted wallets; approved June 17–19 plenary; not yet published (last published update June 2025).
- **Continuous / behavioural verification** — new watch: the July 6 Biometric Update feature signals a market repricing of identity from one-time gate to continuous assurance. Track for a named-bank continuous-verification deployment, an analyst (Liminal/Datos/KuppingerCole) framing report, and whether "continuous identity" consolidates as a category label.
- **Agentic identity / agentic payments** — Visa Intelligent Commerce / Agentic Ready in production across European banks (CaixaBank, BBVA, July 7 delta); watch the next tier-1 launch and FIDO Agentic Authentication WG output.
- **EUDI trust infrastructure** — eIDAS Dashboard registries (Catalogue of Attributes, Schemes registry, EAA providers) moving from "in development" to operational ahead of the December 6, 2026 wallet-availability deadline (Germany January 2, 2027).
- **PSD3/PSR OJEU publication** — expected H2 2026; rules apply 21 months post-publication; Verification-of-Payee already live for euro-area PSPs since Oct 9, 2025.

---

## Run summary

- Findings count by pillar: P1 Banking: **1** (Air Bank/Innovatrics PSD2 face-verification deployment; cross-list P7) + AMLA July 10 anchor | P2 Identity orchestration: **1** (UK Digital ID Advisory Group won't publish minutes/budget) | P3 EUDI: 0 new (July 4 roundup out of window / already covered) | P4 KYC/AML: 0 (AMLA RTS July 10 anchor, 2 days) | P5 Onboarding: 0 (indirect via continuous-verification shift) | P6 IDV: cross-list P7 (continuous verification reframes IDV) | P7 Fraud/Deepfakes: **1** (Biometric Update July 6 continuous-verification / fraud-escalation feature — the fresh cluster) | P8 Mobile trust: 0 new | P9 Passwordless: 0 new | P10 ZKP: 0 new | P11 Age assurance: 0 new (Ofcom end-July anchor) — **Total: 2 substantive in-window findings (P7 continuous-verification feature incl. Air Bank/Innovatrics; P2 UK Advisory Group opacity)**
- Override-worthy: **1** — "One-time KYC is over": continuous / behavioural verification framed as the new banking baseline, backed by fresh loss data (8,065 deepfake attempts → $347M at one institution; ATO $15.6B in 2024; synthetic ~8× YoY to ~11% of fraud). Account: company /.
- Delta path: research/2026-07-08-cycle-delta.md
- Note: quiet mid-week window — the July 6 ID Tech digest cluster was mined by the July 6/7 deltas. Excluded as out-of-window or already covered: Signicat×TrustTech, Wultra €6.8M, Authologic/Google Wallet, UK alcohol digital-ID SI, Veratad AI-agent SDK, eIDAS Dashboard registry, IETF age-verification draft, Incode×Auth0, CaixaBank×Visa. Excluded as outside Ditto's regulated-enterprise ICP: Vietnam VNeID saturation, The Gambia sovereign ID, Thailand airport facial recognition, IDfy (June, India). AMLA July 10 and Ofcom end-July flagged as anchors, not in-window events.
