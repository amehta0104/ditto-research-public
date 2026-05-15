# Cycle Delta — 2026-05-15

Window: 2026-05-13 → 2026-05-15 (last 48 hours)

## Override-worthy this cycle

1. **OpenID Connect Advanced Syntax for Claims (ASC) 1.0 — two-week member vote to advance to Implementer's Draft concludes today, 15 May 2026** — The eKYC & IDA working group recommended ASC 1.0 for approval; the vote ran 1–15 May and closes today, advancing the spec to Implementer's Draft (the milestone signalling readiness for trial implementations and interop testing across wallet ecosystems). The two components — "Selective Abort and Omit" and "Transformed Claims" — include deriving an age-verification result from a birthdate without exposing the full date of birth: the canonical privacy-preserving, claim-level disclosure control. The 05-13 and 05-14 deltas both flagged this as the item today's delta should capture. Angle: "ZKP gets the headlines; claim-level transformation is the part that ships. OpenID just moved the spec that lets a relying party get 'over 18 = true' from a birthdate — no DOB, no residue — to implementer's-draft status. Privacy-preserving disclosure is now a protocol feature, not a research demo."

2. **Unico launches Brazil's first national-scale digital age verification tool — 14 May 2026** — Unico (Latin America's largest digital identity network, 1.5 billion identity checks in 2025) launched a Privacy by Design age verification product powered by a single selfie, 99.98% accuracy, liveness detection, AES encryption, and automatic PII masking; the product delivers a binary yes/no age-assurance response — no date of birth, no identity data transmitted — in direct response to Brazil's Digital ECA (Law No. 15,211/2025, in force 17 March 2026). Brazil mandated age assurance and got a production-grade national-scale solution within 60 days. Angle: "Brazil set a deadline in March, and by May the largest identity network in LATAM had a production tool in market. The technical answer — single selfie, binary response, no data residue — is the same design pattern France Identité shipped in the EUDI sandbox last week. Privacy-preserving age assurance is converging on a single architecture across continents."

---

## New findings

### Pillar 1: Banking & Payments

(no new material in window — PSD3/PSR: ECON adopted the final compromise texts 5 May; the European Parliament plenary vote remains "expected later this month" with no plenary held in window; OJEU publication still anticipated June/July 2026. No new DORA enforcement actions, CTPP designations or penalty announcements disclosed in window — the ECB Elderson AI-cyber supervisory warning + Mistral cyber-AI response were captured in the 05-14 delta and remain the live banking-cyber story. No fresh FCA/PSR APP-fraud framework announcement; post-implementation review still expected Q2/Q3 2026.)

### Pillar 2: Identity orchestration

- **Trinsic 2026 Digital ID Opportunity Zones report — published 14 May 2026** — Drawing on a database of 300+ digital identity schemes, Trinsic ranked countries by the maturity and commercial usability of their digital identity ecosystems for relying parties wanting to accept reusable digital IDs at onboarding. Green-zone countries (strong adoption, usable today): Netherlands, Denmark, Estonia, Latvia, Lithuania, Brazil, India, Italy — with South Korea and Nigeria as new 2026 entrants. Yellow-zone (adoption potential, higher complexity): US, France, Sweden, Norway, Singapore, Indonesia, UAE, Japan, Poland, Philippines. The US remains yellow because mDL and private-sector IDs cover ~38% of the adult population (roughly 100 million people). Practical significance: first 2026 market-readiness map for vendors and relying parties accepting reusable IDs — Brazil's green-zone status is a direct LATAM anchor; the US yellow classification will be a relevant benchmark for any post arguing the EU is ahead on deployability. Complements the idLAC MVP story from 05-14 on the "LATAM is in the production tier now" narrative.
  - Source: https://www.biometricupdate.com/202605/trinsic-maps-top-global-markets-for-reusable-digital-identity-in-2026
  - Source: https://trinsic.id/digital-id-opportunity-zones/
  - Date: 2026-05-14

(KuppingerCole EIC 2026 opens 19 May Berlin — "Digital Trust Through Intelligent Identity"; Identity Fabrics, NHI orchestration and decentralised identity on the agenda. No pre-event vendor announcements or category M&A landed in window. CSC Trust Without Borders Summit Bogotá (13–14 May) was captured in the 05-14 delta.)

### Pillar 3: EUDI / eIDAS2

(no new material in window — no new member-state launch announcements. Romania-Mastercard MoU and France Identité ZKP age verification were both covered in the 05-13 delta; Spain's MiDNI reached full legal parity for in-person identification on 2 April 2026 (Royal Decree 255/2025 12-month acceptance window), which is outside this window and earlier than this cycle. ENISA EUDIW certification scheme remains in post-consultation review (public review closed 30 April); scheme to be published as an Implementing Act by end-2026. Next inflection points: German EUDI Hackathon 4–5 June and Community Event 25 June Berlin.)

### Pillar 4: KYC / AML compliance

(no new material in window — AMLA's first public hearings on the draft RTS are imminent but fall after the window: group-wide minimum requirements RTS hearing 20 May, business-wide risk assessment Guidelines hearing 28 May (both captured in the 05-12 / 05-14 deltas). The CDD and Art. 19(9) consultations closed 8 May; next AMLA milestone is the 10 July submission of final CDD draft to the Commission. No fresh AMLA RTS package opened in this 48h window.)

### Pillar 5: Customer onboarding

(no new material in window — the Fenergo "State of the Industry" survey (70% of firms lost clients to inefficient onboarding, up from 67%/48%; KYC/AML AI adoption 42%→82%; ~$72.9m average annual AML/KYC spend) is a strong onboarding-economics anchor but was published 7 October 2025, well outside the window; flagged here so the drafter can cite it without re-running search, dated correctly as 2025 data.)

### LATAM

- **Unico launches Brazil's first national-scale digital age verification tool — 14 May 2026** — Unico (Latin America's largest digital identity network; 1.5 billion identity checks in 2025) launched a proprietary age verification product on 14 May. Architecture: single selfie, 99.98% accuracy, built-in liveness detection, AES encryption, automatic PII masking. The product returns a binary yes/no to an age-assurance query — no date of birth, no issuer reference, no identity data transmitted — complying with data-minimisation and selective-disclosure principles. Built with Privacy by Design architecture in response to Brazil's Law No. 15,211/2025 (Digital Statute of the Child and Adolescent / Digital ECA), which entered into force 17 March 2026 and imposed age assurance requirements on platforms and services. Brazil went from law in force to national-scale production tool in 60 days. Significance: Brazil is Unico's home market, the regulation is real and in force, and the architecture (binary response, zero data residue) mirrors what France Identité deployed in the EUDI sandbox. Cross-cite Pillar 11 for age-assurance read-across.
  - Source: https://www.biometricupdate.com/202605/unico-launches-digital-proof-of-age-tool-in-brazil
  - Date: 2026-05-14

### Pillar 6: Identity verification (IDV)

(no new material in window — no fresh iBeta PAD certifications, NIST IAL updates or vendor M&A in window. Shufti's iBeta PAD Level 2 (prior deltas) and Incode's first iBeta Level 3 in 2026 remain the current reference points; neither is new this cycle. NIST NCCoE draft SP 1800-42A on mDL for financial institutions comment period closed 8 May, outside window.)

### Pillar 7: Fraud / Deepfakes

(no new material in window — no named-bank deepfake or synthetic-ID incident disclosures in the 48h window; no fresh primary-source vendor fraud reports. Sumsub 2025-26, Veriff 2026 and iProov 2026 reports remain the strongest aggregate-data anchors from the baseline. The ECB Elderson / Mistral story (05-14) has a fraud read-across but is primarily an operational-resilience framing.)

### Pillar 8: Mobile trust & app security

(no new material in window — the multi-family Android PIN-stealing campaign (RecruitRat / SaferRat / Astrinox / Massiv, 800+ banking/crypto/social apps via overlay + Accessibility abuse) and the Anatsa Google Play campaign surfaced in research published April 2026, outside this window; no fresh named-bank mobile-malware disclosures or new ThreatLabz/Zimperium/Kaspersky publications dated in window.)

### Pillar 9: Passwordless / Split-key

(no new material in window — World Passkey Day 2026 data (5bn passkeys, 75% enabled, 68% enterprise), the FIDO Agentic Authentication Technical Working Group and FIDO Digital Credentials Initiative were all announced on/around 7 May (and the DCWG launch originally December 2025), all outside this window and captured in earlier deltas. The ASC 1.0 vote (see override + Pillar 10) is the only authentication-adjacent standards event landing in window. No fresh regulator OTP-sunset actions in window.)

### Pillar 10: ZKPs in practice

- **OpenID Connect Advanced Syntax for Claims (ASC) 1.0 — Implementer's Draft approval vote concludes today, 15 May 2026** — The OpenID Foundation member vote to advance ASC 1.0 to Implementer's Draft ran Friday 1 May → Friday 15 May 2026 and closes today; the eKYC & IDA working group recommended approval following the 60-day public review. ASC 1.0 defines a structured query syntax for requesting specific identity claims, with two components: "Selective Abort and Omit" (a relying party sets conditions under which certain claims must not be returned) and "Transformed Claims" (apply a function to an existing claim — e.g. derive an over-18 boolean from a birthdate without exposing the full date of birth). This is the production-grade, protocol-level expression of the privacy-preserving disclosure pattern ZKP age-checks demonstrate — the "claim transformation" half of the privacy story, credential-format agnostic and relevant to EUDI/mobile-wallet claim exchange. Implementer's Draft status signals readiness for trial implementations and interop testing. The official result is expected to be announced shortly after the vote closes; the substantive, dated, in-window event is the vote conclusion and recommended advancement.
  - Source: https://openid.net/notice-of-vote-to-approve-the-proposed-implementers-draft-of-openid-connect-advanced-syntax-for-claims-asc-1-0/
  - Source: https://www.biometricupdate.com/202605/openid-draft-spec-for-extended-identity-claims-assurance-up-for-approval
  - Source: https://idtechwire.com/openid-foundation-opens-vote-on-advanced-syntax-for-claims-specification/
  - Date: 2026-05-15 (vote concludes; voting period 2026-05-01 → 2026-05-15)

### Pillar 11: Age assurance & privacy attributes

- **Unico Brazil age verification (cross-pillar from LATAM): binary, Privacy by Design, no data residue — 14 May 2026** — See full finding under LATAM. The age-assurance design pattern is the signal: Unico's product delivers a yes/no result with liveness detection from a single selfie, exposing no date of birth and storing no PII — identical in architecture to France Identité's ZKP age-check sandbox (05-13 delta) and to the "Transformed Claims" pattern in OpenID ASC 1.0 (Pillar 10, this delta). A convergence signal: the major national-scale age-verification tools launched in 2026 — across Brazil (Unico), France (France Identité), and the OpenID standard track — all use the same privacy-preserving, binary-response, no-residue design. This is the architecture the age-assurance market is standardising on.
  - Source: https://www.biometricupdate.com/202605/unico-launches-digital-proof-of-age-tool-in-brazil
  - Date: 2026-05-14

(Ofcom's anticipated May report on platform responses to its 30 April age-assurance demands — Facebook, Instagram, Roblox, Snapchat, TikTok, YouTube — has still not published as of this cycle; the broader statutory age-assurance report (end-July 2026) and app-stores report (January 2027) remain the next published-date anchors.)

---

## Run summary

- Findings count by pillar: P1: 0 | P2: 1 (Trinsic Opportunity Zones) | P3: 0 | P4: 0 | P5: 0 | LATAM: 1 (Unico Brazil age verification) | P6: 0 | P7: 0 | P8: 0 | P9: 0 | P10: 1 (OpenID ASC 1.0) | P11: 1 (cross-pillar Unico) → Total: **3 distinct findings** (Unico counted once across LATAM/P11)
- Override-worthy: (1) OpenID Connect ASC 1.0 advancement to Implementer's Draft — vote concludes today; (2) Unico Brazil age verification launch — 60-day law-to-production-tool signal, converges with France Identité architecture
- Delta path: research/2026-05-15-cycle-delta.md
