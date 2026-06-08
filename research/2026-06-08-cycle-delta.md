# Cycle Delta — 2026-06-08

Window: 2026-06-05 → 2026-06-08 (last 72 hours, Mon — weekend coverage)

## Override-worthy this cycle

1. **Wired reveals Meta secretly shipped dormant facial recognition code to 50 million+ phones via its Ray-Ban smart-glasses app (June 4–5, 2026)** — The "NameTag" system — three on-device AI models that detect a face, generate a biometric fingerprint, and fire a "Person Recognized" notification — has been bundled in the Meta AI app since at least January 2026, before any public disclosure. Account: / company. Angle: "Meta quietly put a face-recognition engine on 50 million phones before telling anyone. This is what identity infrastructure looks like when consent is optional and the architecture is centralised. The alternative — ZKP-bound selective disclosure where the user controls what biometric data is presented and to whom — isn't a privacy nicety. It's the structural safeguard that makes this kind of silent deployment impossible."

## New findings

### Pillar 1: Banking & Payments

(no new material — PSD3/PSR: ECON voted 5 May; plenary vote expected imminently but not yet scheduled; OJEU publication June/July 2026, may slip to September — no change from prior delta. MiCA CASP hard deadline 1 July now 23 days out; ESMA no extension confirmed April 17 — recurring anchor. AMLA CDD RTS final draft → Commission 10 July — unchanged calendar anchor.)

### Pillar 2: EUDI / eIDAS2

(no new material — EUDI ON Hackathon (4–5 June, remote) results still pending; winning teams present at Berlin Community Event 25 June. ARF v2.8 current version; no new Commission or ENISA certification announcement in window. Member-state readiness status (Germany sandbox, France H2 testing, Italy IT-Wallet) unchanged from prior cycle.)

### Pillar 3: Fraud / Deepfakes

- **Wired reveals Meta has been silently shipping dormant facial recognition code — "NameTag" — to 50 million+ smartphones via the Meta AI companion app for Ray-Ban and Oakley smart glasses (June 4–5, 2026).** — Security researchers reviewed the Meta AI app and found three AI models packaged inside since at least January 2026: (1) a face detector, (2) a biometric fingerprint generator stored on-device, and (3) a "Person Recognized" notification trigger. The system works by matching faceprints against a saved local database, deliberately avoiding a central cloud server to let Meta argue it is not maintaining a centralised biometric repository. The code is dormant — not currently running or transmitting data — but described by researchers as "close to functional." Meta's statement: "We're exploring these features; nothing has shipped to consumers and no final decision has been made." Regulatory significance: The code was distributed to 50M+ devices without public disclosure, predating any GDPR Article 9 (biometric data) or eIDAS-aligned consent process. Under the EU AI Act's biometric identification classification and GDPR, deploying live recognition — even on-device — for identification of individuals in public would require explicit consent and likely a high-risk AI conformity assessment. Ditto significance: The NameTag architecture is the commercial inverse of ZKP/selective-disclosure — centralised biometric fingerprinting where the platform controls the credential rather than the user. The story sharpens the "who owns the biometric layer?" argument at exactly the moment EUDI wallets are defining the consent framework for European identity.
  - Source: https://www.wired.com/story/meta-ray-ban-smart-glasses-facial-recognition-nametag (original Wired report, June 4, 2026)
  - Source: https://www.techtimes.com/articles/317870/20260605/meta-smart-glasses-facial-recognition-code-already-millions-phones-wired-finds.htm
  - Source: https://techbriefly.com/2026/06/05/meta-facial-recognition-smart-glasses-ai-app/
  - Source: https://9to5google.com/2026/06/05/meta-ray-ban-glasses-may-soon-recognize-faces/
  - Date: 2026-06-05 (Wired broke June 4; secondary coverage and public awareness peaked June 5; not captured in any prior delta)

### Pillar 4: ZKPs in practice

(no new material — DIF KYA-OS v1.0 vote result still not published — multi-cycle carry-forward. OpenID4VP v1.0 reached Final status July 2025; v1.1 in active development. No new bank pilot or mDL selective-disclosure deployment announcement in window.)

### Pillar 5: Passwordless / split-key

(no new material — FIDO Member Plenary (4–5 June, Grand Hyatt Singapore) concluded; members-only event; no post-plenary public specification release or announcement confirmed in window. Philippines BSP Circular 1213 OTP hard sunset deadline June 30 confirmed firm — 22 days out; BSP Deputy Governor "we are not extending it" repeated across March–June 2026. Recurring calendar anchor, not a new finding. FIDO State of Passkeys 2026 report (World Passkey Day, May 6): 5 billion passkeys in use globally, 75% of people have enabled at least one passkey — published May 6, outside window; was not captured in prior deltas but falls outside this window; note for next full-baseline update.)

### Pillar 6: LATAM

(no new material — Colombia open finance Decree 0368 technical deadline 7 August 2026 unchanged. Brazil Drex: architecture pivot to non-blockchain v1 confirmed; initial lien-reconciliation focus; no new BCB announcement in window. Mexico CNBV Open Finance rules delay continues; no in-window regulatory action. Standing CNBV/Superfinanciera/CMF anchors unchanged.)

### Pillar 7: Identity ecosystem

(Cross-reference Pillar 3: Meta NameTag is the lead identity-ecosystem story this cycle — see full writeup above. No separate new analyst report, M&A, or funding event confirmed in window. DIF Trusted AI Agents WG (KYA-OS) and FIDO Agentic Authentication TWG both in active development with no new public output in window. Microsoft Entra "What's New: June 2026" — published June 1–2 per helpnetsecurity coverage, outside this window; documents agent identity lifecycle automation and passkey registration campaign GA features; flag for next full-baseline refresh rather than delta inclusion.)

---

## Next-cycle anchors

- **FIDO Member Plenary post-session readout** — any public summary, spec draft, or announcement from the June 4–5 Singapore plenary; primary interest: Agentic Authentication TWG progress (Google AP2 v0.2 / Mastercard Verifiable Intent toward a FIDO spec)
- **Money20/20 "Fighting Deepfakes" session write-up** — Incode presented "A Year on the Front Line" at MoneyPot Stage (June 4); no published post-session write-up confirmed; sweep upcoming cycles
- **EUDI ON Hackathon results** — winners to be announced at Berlin Community Event June 25
- **Philippines BSP Circular 1213 deadline (June 30)** — 22 days out; any last-minute compliance-rate data or extension reversal
- **MiCA CASP hard deadline (July 1)** — 23 days; watch for named CASPs ceasing EU services or NCA enforcement announcements
- **FATF Best Practices on Travel Rule Supervision** — flagged for June 26, 2026; verify exact publication date next cycle
- **EUDI Wallet Community Event "EUDI ON" (June 25, Berlin)** — member-state status updates, hackathon winning-team presentations
- **UK People's Panel on digital ID — Workshop 2 (June 20–21)** — second in-person session; watch for interim recommendations
- **AMLA CDD RTS final draft → Commission (July 10)** — calendar anchor; watch for AMLA press release or leaked final text
- **PSD3/PSR plenary vote** — still unscheduled; OJEU publication June/July 2026 (may slip to September); watch EU Parliament legislative train
- **DIF KYA-OS v1.0 vote result** — multi-cycle carry-forward
- **Meta NameTag regulatory response** — EU DPA or EDPB reaction to dormant facial recognition code in Meta AI app; any Article 9 GDPR enforcement inquiry announcement
- **Microsoft Entra June 2026 "What's New"** — published June 1–2; agent identity lifecycle automation + passkey Registration Campaigns GA; include in next full-baseline refresh

---

## Run summary

- Findings count by pillar: P1: 0 | P2: 0 | P3: 1 (Meta NameTag — dormant facial recognition covertly shipped to 50M+ devices) | P4: 0 | P5: 0 | P6: 0 | P7: 0 (cross-ref P3) → **Total: 1 unique finding**
- Override-worthy: **1** — Meta NameTag
- Delta path: research/2026-06-08-cycle-delta.md
