# Cycle Delta — 2026-06-09

Window: 2026-06-06 → 2026-06-09 (last 72 hours — Mon, weekend coverage)

## Override-worthy this cycle

1. **Meta removes NameTag facial recognition code under regulatory pressure; UK ICO contacts Meta (June 8, 2026)** — The removal of the covert biometric architecture — shipped to 50M+ devices without disclosure — is the direct follow-on to last cycle's discovery story, and the UK ICO's move to contact Meta marks the first concrete regulator-to-platform enforcement signal. Account: / company. Angle: "Meta's covert biometric stack had to be deleted under regulatory pressure. The UK ICO is already at the door. This is what happens when you build identity infrastructure without consent-first architecture from day one — ZKP/selective-disclosure wallets don't have a 'remove the illegal code' patch cycle because the user controls what's shared and to whom."

## New findings

### Pillar 1: Banking & Payments

(no new material — PSD3/PSR: ECON voted 5 May; plenary vote still unscheduled; OJEU publication June/July 2026, may slip to September — no change from prior delta. MiCA CASP hard deadline July 1 now 22 days out; no named CASP enforcement action or NCA announcement confirmed in window. AMLA CDD RTS final draft → Commission July 10 — unchanged calendar anchor. FCA/PSR APP fraud reimbursement independent review by Frontier Economics still expected Q2/Q3 2026; not published in window.)

### Pillar 2: EUDI / eIDAS2

(no new material — ARF v2.8 current; no new Commission or ENISA certification announcement in window. Member-state readiness status unchanged. EUDI ON Community Event Berlin June 25 approaching — hackathon results and member-state updates due then. No new in-window regulatory output.)

### Pillar 3: Fraud / Deepfakes

- **Meta quietly removes NameTag facial recognition code from Meta AI app after public outcry; UK ICO contacts Meta over data protection compliance (June 8, 2026).** — Following the Wired exposé (June 4–5, covered in 2026-06-08 delta), Meta stripped all three NameTag AI models from the latest version of the Meta AI app on June 8. The removal — described by the Electronic Frontier Foundation as a "victory" — was forced by public and regulatory pressure rather than any planned product decision. Meta VP of Communications Andy Stone complained publicly that Wired waited until the fourth paragraph to note the feature "was not enabled," signalling the company views the removal as unfair rather than appropriate. Separately, the UK's Information Commissioner's Office (ICO) has contacted Meta to request an explanation of how the covert code was distributed to more than 50 million devices without GDPR Article 9 (biometric data) or UK GDPR consent, representing the first direct regulator-to-platform enforcement signal in the story. No EDPB formal decision or named EU DPA inquiry confirmed in window, but the ICO contact establishes a supervisory record. Ditto significance: Meta's removal under pressure validates the structural critique — centralised, platform-controlled biometric architectures can be deployed covertly and must be removed covertly; consent-first ZKP/selective-disclosure design makes covert deployment architecturally impossible because the user controls the credential presentation layer. The UK ICO contact is the first step toward potential enforcement under UK GDPR Article 9 (special-category biometric data) and the EU AI Act high-risk classification for biometric identification systems.
  - Source: https://www.eff.org/deeplinks/2026/06/victory-meta-strips-facial-recognition-code-smart-glasses-app-after-public-outcry (EFF, June 8, 2026)
  - Source: https://yro.slashdot.org/story/26/06/08/1945252/meta-deletes-face-recognition-system-from-its-smart-glasses-app (Slashdot, June 8, 2026)
  - Source: https://gagadget.com/en/714147-meta-quietly-shipped-facial-recognition-code-to-millions-of-phones-then-pulled-it/ (GadGet, June 8, 2026)
  - Source: https://www.rappler.com/technology/meta-wired-facial-recognition-code-ai-app-smart-glasses/ (Rappler, June 8, 2026)
  - Date: 2026-06-08

### Pillar 4: ZKPs in practice

(no new material — DIF KYA-OS v1.0 vote result still not published — multi-cycle carry-forward. OpenID4VP v1.1 in active development. No new bank pilot or mDL selective-disclosure deployment announcement in window.)

### Pillar 5: Passwordless / split-key

(no new material — Philippines BSP Circular 1213 OTP hard sunset deadline June 30 now 21 days out; BSP Deputy Governor's "we are not extending it" stance unchanged — recurring calendar anchor, not a new finding. FIDO Agentic Authentication TWG (formed April 27) in active spec development; no public draft output confirmed in window following the June 4–5 Singapore Plenary. JSDA phishing-resistant MFA mandatory deadline for Japanese brokerages still flagged as "summer 2026" with no formal finalization announcement in window.)

### Pillar 6: LATAM

(no new material — Colombia open finance Decree 0368 technical deadline August 7, 2026 unchanged. Brazil Drex: non-blockchain architecture pivot confirmed; Phase 2 focus on credit-market plumbing; no new BCB announcement in window. Mexico CNBV Open Finance rules delay continues; no in-window regulatory action.)

### Pillar 7: Identity ecosystem

- **Cross-reference Pillar 3:** Meta NameTag removal + UK ICO contact is the lead identity-ecosystem story this cycle — see full writeup above. The EFF's "victory" framing and Meta VP's defensive public statement together indicate the story has entered a sustained regulatory-pressure phase rather than a single-day news cycle. Watch for: named EU DPA or EDPB inquiry; any EU AI Act high-risk conformity assessment notification; Meta's next product disclosure timeline. (No separate new analyst report, M&A, or funding event confirmed in window.)

---

## Next-cycle anchors (updated)

- **UK People's Panel on digital ID — Workshop 2 (June 20–21)** — second in-person session; watch for interim recommendations on public acceptance of EUDI-style wallets
- **EUDI Wallet Community Event "EUDI ON" (June 25, Berlin)** — hackathon winning-team presentations; member-state status updates on Germany, France, Italy readiness
- **FATF Best Practices on Travel Rule Supervision (June 26)** — publication confirmed for this date; covers supervisory approaches for VASP Travel Rule compliance
- **Philippines BSP Circular 1213 deadline (June 30)** — 21 days; any last-minute compliance data or extension reversal from BSP
- **MiCA CASP hard deadline (July 1)** — 22 days; watch for named CASPs ceasing EU services or NCA enforcement announcements
- **AMLA CDD RTS final draft → Commission (July 10)** — calendar anchor; watch for AMLA press release or leaked final text
- **PSD3/PSR plenary vote** — still unscheduled; OJEU publication June/July 2026 (may slip to September)
- **DIF KYA-OS v1.0 vote result** — multi-cycle carry-forward
- **Meta NameTag regulatory response** — UK ICO engaged; watch for named EU DPA inquiry, EDPB coordination, or EU AI Act high-risk notification
- **EUDI ON Hackathon results** — winners to be announced at Berlin Community Event June 25
- **FCA/PSR APP fraud reimbursement review (Frontier Economics)** — Q2/Q3 2026; not yet published
- **Japan JSDA phishing-resistant MFA mandatory deadline** — "summer 2026"; watch for JSDA formal finalization and FSA supervisory expectation update

---

## Run summary

- Findings count by pillar: P1: 0 | P2: 0 | P3: 1 (Meta removes NameTag; UK ICO contacts Meta — June 8, 2026) | P4: 0 | P5: 0 | P6: 0 | P7: 0 (cross-ref P3) → **Total: 1 unique finding**
- Override-worthy: **1** — Meta NameTag removal + UK ICO contact
- Delta path: research/2026-06-09-cycle-delta.md
