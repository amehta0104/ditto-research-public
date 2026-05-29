# Cycle Delta — 2026-05-29

Window: 2026-05-26 → 2026-05-29 (last 72 hours — Friday window)

## Override-worthy this cycle

(none — Friday window is thin; two genuine in-window findings, neither override-grade on its own. Money20/20 Europe / FIDO Authenticate APAC / German EUDI Hackathon cluster starting June 2 will be the heaviest research week of the month.)

---

## New findings

### Pillar 1 / Pillar 4: Banking & KYC/AML compliance

- **AMLA BWRA hearing (28 May 2026): industry challenges simplified risk assessment — qualifying criteria still undefined** — At the public hearing on the draft Guidelines on business-wide risk assessment (BWRA) under AMLR Art. 10(4), held 28 May 2026 (10:00–12:00 CET), industry pushed back on AMLA's proposal to allow a simplified pathway for smaller obliged entities, with businesses arguing that AMLA has yet to define which firms will qualify. AMLA defended proportionality and a risk-based approach but could not specify the eligibility threshold during the hearing itself. The written-submission window for BWRA stays open until 15 July 2026; final guidelines due to the Commission by 10 July 2026. Companion hearing on Home-Host Supervisory Cooperation RTS (14:00–16:00 CET same day) completed without a published readout as of this scan. Why it matters for an identity vendor: the BWRA is the document that determines each obliged entity's KYC/CDD risk appetite — an undefined simplified pathway creates both uncertainty (entities cannot yet benchmark their own obligation level) and an opening (identity vendors who can demonstrate risk-reduction at proportionate cost will have a cleaner procurement argument once the threshold is set). Cross-pillar: pairs with the baseline AMLA CDD RTS anchor (consult closed 8 May; final draft to Commission 10 July) and the standing 'AMLA replaces 27 interpretations of KYC with one rulebook' framing.
  - Source: https://www.amlintelligence.com/2026/05/eu-businesses-challenge-amla-on-simplified-aml-risk-assessment/
  - Source: https://www.amla.europa.eu/events/public-hearing-draft-guidelines-business-wide-risk-assessment-2026-05-28_en
  - Date: 2026-05-28

### Pillar 2: Identity orchestration

(No new dated-in-window finding. The 05-27 WSO2 ThunderID / Agent Fabric and the 05-27 Signicat ID Austria integration remain the live orchestration cluster. DIF KYA-OS Trusted Agentic AI WG vote: result STILL not published on the DIF blog/newsletter as of 29 May — sweep 05-30 / early next week. OpenID Connect Advanced Syntax for Claims (ASC) 1.0: formal 'approved' result page STILL not published on the OpenID Foundation site as of 29 May, 15 days since vote closed 15 May — drafter note: continue to treat as 'vote concluded, recommended for approval, formal Implementer's Draft confirmation pending.' Monitor both for weekend-Friday publication.)

### Pillar 3: EUDI / eIDAS2

(No new dated-in-window finding. No new ARF / Implementing-Act movement. PSD3/PSR plenary vote still not scheduled: ECON adopted 5 May (PSD3 50-3-5; PSR 50-2-2); no Strasbourg session date confirmed; OJEU publication now anticipated mid-to-late Q3 2026 rather than end Q2 as originally projected. Member-state calendar unchanged; German EUDI Wallet Hackathon starts 4 June — first community output expected at EUDI ON Berlin 25 June. The 05-27 Signicat ID Austria / 05-25 OneSpan EUDI LSP cluster remains the freshest relying-party operational signal.)

### Pillar 6: Identity verification (IDV) / Face morphing

- **EU Horizon Europe projects EINSTEIN and SafeTravellers publish morph-attack-detection capabilities — EINSTEIN reaches TRL 6; SafeTravellers runs through December 2026 — Biometric Update, 28 May 2026** — Two EU-funded Horizon Europe research programmes are moving from lab to deployment-ready stage on face morph attack detection (MAD). Project EINSTEIN has produced a usable MAD workflow at Technology Readiness Level 6, addressing quality, explainability and evolving attack vectors (including GAN and diffusion-model morphs); the team will continue refining the algorithm until funding expires end-2026. The SafeTravellers project (January 2024 – December 2026) is developing a full identity-management platform for border crossings that combines multi-modal biometrics (face + fingerprint), pre-travel voluntary enrolment and a layered morph-detection / digital travel credential verification stack — explicitly designed to detect and prevent morphing, replay and substitution attacks on biometric systems. Both projects presented at the European Association for Biometrics MAD workshop (26 May 2026, covered in the 05-27 delta) and the Biometric Update article capturing them is dated 28 May. Significance: the 05-27 delta quantified the attack side (diffusion-model morphs achieving up to 99.8% evasion) and the 05-28 delta quantified the defensive state of the art (NIST FATE MORPH 4B: D-MAD ~72% at 1% FPR). This article adds the third layer: EU public investment is now flowing into operational MAD systems at TRL 6 and multi-modal border-IV platforms specifically designed around the morph threat, validating that document-issuance-time morph detection is moving from research to procurement-spec. For Ditto: completes the morph-attack picture for the cycle — attack sophistication (99.8% evasion), best-available defense (72% machine D-MAD), and EU research investment converging on the same defensive architecture Ditto's provenance-over-liveness framing recommends.
  - Source: https://www.biometricupdate.com/202605/eu-research-projects-target-face-morph-attacks-threatening-border-identity-systems
  - Date: 2026-05-28

### Pillar 7: Fraud / Deepfakes

(No new named-bank deepfake or synthetic-ID incident with verified in-window date. The 05-28 ECB FSR override (AI-enabled fraud = systemic risk; mandatory disclosure) and the 05-28 Regula 87%/26% override remain the standing hooks. The EU EINSTEIN/SafeTravellers finding above (Pillar 6) is the freshest in-window defensive signal.)

### Pillar 8: Mobile trust & app security

(No new in-window finding. No new banking-trojan-family discovery. Standing reference patterns unchanged.)

### Pillar 9: Passwordless / Split-key

(No new in-window finding. Philippines BSP Circular 1213 OTP sunset now 32 days away (30 June 2026) — captured 05-27. Microsoft Entra passkeys on Windows / Entra External ID staged GA rollout (began late April, expected complete mid-June) continues; no discrete completion announcement landed in this window.)

### Pillar 10: ZKPs in practice

(No new in-window finding. Dual carry-forward STILL unresolved: (1) **OpenID ASC 1.0** — formal result page not live as of 29 May (15 days since vote closed); (2) **DIF KYA-OS** — 14-day review concluded ~22–25 May; vote result still not published on DIF blog or newsletter as of 29 May. Sweep both 05-30 and Monday 06-01.)

### Pillar 11: Age assurance & privacy attributes

(No new in-window finding. UK People's Panel on Digital ID weekend workshops run 30–31 May Birmingham — first weekend of deliberation; output expected after 20–21 June second workshop. Consultation concludes 21 June 2026. The 05-28 delta captured the panel launch and UK social-media law consultation closure (26 May).)

### Pillar 6

(No new dated-in-window LATAM finding. No new Pix/Drex/CNBV/SFC update within the 72-hour window. The 05-28 delta's Regula Brazil + Mexico cross-ref (87% AI-assisted IDV exposure; 7 markets including Brazil and Mexico in survey set) and the baseline Colombia Decree 0368 open-finance mandate (7 April 2026; technical deadline 8 August) remain the freshest standing anchors.)

---

## Run summary

- **Findings by pillar:** P1/P4: 1 (AMLA BWRA hearing — industry challenge on simplified-assessment threshold; companion Home-Host RTS hearing held, readout pending) | P2: 0 (DIF KYA-OS + OpenID ASC 1.0 both still pending) | P3: 0 (PSD3/PSR plenary still unscheduled; OJEU slipping to Q3) | P6/IDV: 1 (EU Horizon EINSTEIN TRL 6 + SafeTravellers MAD platform — in-window article May 28) | P7: 0 | P8: 0 | P9: 0 | P10: 0 | P11: 0 | LATAM: 0 → **Total: 2 unique findings**
- **Override-worthy:** (none this cycle)
- **Next-cycle anchors (heavy week):** Money20/20 Europe (2–4 June Amsterdam) — identity, deepfake, regulatory content expected; FIDO Authenticate APAC (2–3 June Singapore) — Singapore passkey-mainstream + agentic-auth WG news; German EUDI Wallet Hackathon (4–5 June, fully remote) — first community build output; UK People's Panel on Digital ID first weekend (30–31 May Birmingham — output next delta); DIF KYA-OS + OpenID ASC 1.0 both still pending; AMLA BWRA + Home-Host formal post-hearing readout (check amla.europa.eu); PSD3/PSR plenary — monitor for June Strasbourg session confirmation.
- **Delta path:** research/2026-05-29-cycle-delta.md (written directly to GitHub; worker at ditto-slack-bot.dittobot.workers.dev returns HTTP 403 host-not-allowed under sandbox network policy)
