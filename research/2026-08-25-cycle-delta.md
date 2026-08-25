# Cycle Delta — 2026-08-25

Window: 2026-08-23 → 2026-08-25 (last 48 hours — Tuesday cycle)

Worker URL blocked by session network policy (proxy policy blocks `ditto-slack-bot.dittobot.workers.dev`); delta written directly to GitHub via MCP. Skill files read from baseline and prior delta context.

This cycle has 2 new findings across Pillars 3 and 7 — both in the age assurance / biometric identity track. All primary regulatory pillars (PSD3/PSR, AMLA, EBA/ECB, FATF, FIDO Alliance, EUDI) produced no primary-source output in the 48-hour window, consistent with the prior 13 cycles. The two findings are laterally adjacent — NZ age assurance legislation and India DoT biometric SIM mandate — and together describe a widening global regulatory mandate for liveness/biometric verification at the infrastructure layer.

---

## Override-worthy this cycle

1. **New Zealand introduces Social Media (Age-Restricted Users) Bill** — NZ government moved legislation on 2026-08-25 mandating that high-risk social platforms verify users are 16+, with facial age estimation, digital ID, or formal documents as permitted methods; 10% global revenue penalty. This is the fifth major jurisdiction (after UK Ofcom, Australia eSafety, EU DSA, and US KOSA) to move age assurance into law — the wave is now cross-continental and creates clear demand signal for liveness and digital ID vendors. Account:. Angle: "The age-verification regulatory wave just became a five-continent policy stack."

---

## New findings

### Pillar 1: Banking & Payments

(no new material)

### Pillar 2: EUDI / eIDAS2

(no new material)

### Pillar 3: Fraud / Deepfakes

- **New Zealand Social Media (Age-Restricted Users) Bill introduced** — On 2026-08-25 the NZ government introduced legislation requiring high-risk social media platforms (Instagram, TikTok, Snapchat, Facebook, YouTube, X) to take reasonable steps to confirm that account holders are 16 or older before granting access. Permitted verification methods include: facial age estimation, digital identity services, and formal identity documents — a self-declared date of birth alone is explicitly disallowed. Non-compliant platforms face penalties of up to 10% of global revenue. Discord, WhatsApp, Roblox, Spotify, LinkedIn, and general-purpose AI assistants (ChatGPT) are excluded. The bill is unlikely to pass before a November 7 general election, and at least one coalition partner has indicated it will not support it, so implementation risk is real — but its introduction marks NZ joining the regulatory wave and adds legislative pressure on platforms globally.
  - Source: https://www.bloomberg.com/news/articles/2026-08-24/new-zealand-plans-social-media-ban-for-under-16s
  - Source (primary): https://www.beehive.govt.nz/release/government-moves-ban-u16s-social-media
  - Date: 2026-08-25
  - Angle: Links directly to the age assurance wave — Australia eSafety/Roblox auditor undertaking (covered 2026-08-21 delta), UK Ofcom "highly effective" test, and EU DSA — now with NZ adding a fifth major jurisdiction.

### Pillar 4: ZKPs in Practice

(no new material)

### Pillar 5: Passwordless / Split-key

(no new material)

### Pillar 6: LATAM

(no new material)

### Pillar 7: Identity Ecosystem

- **India DoT mandates biometric verification for all SIM issuance** — On 2026-08-21, India's Department of Telecommunications notified the Telecom (User Identification) Rules, 2026, making biometric identification mandatory before any person can obtain, change, or disconnect a mobile SIM connection or internet telephony service. Two methods are prescribed: (i) e-KYC via Aadhaar UIDAI authentication (for Aadhaar holders); (ii) D-KYC — live face capture plus document image capture plus face-to-document match — for non-Aadhaar holders or those unable to complete biometric capture due to physical impairment. Every Indian MNO (Jio 470M+ subs, Airtel 370M+, Vi, BSNL) must deploy biometric capture and liveness detection across their retail distribution networks (~600,000 outlets). This is the world's largest mandated liveness-at-infrastructure-layer deployment to date. Note: date is 2026-08-21, technically adjacent to this cycle's window but absent from the 08-24 weekend delta — included here as missed new material not in any prior delta.
  - Source: https://www.medianama.com/2026/08/223-dot-biometric-identification-mobile-sims/
  - Source: https://officenewz.com/2026/08/22/sim-card-new-rules-2026-biometric-verification-required-for-new-connections-and-kyc-changes/
  - Date: 2026-08-21 (coverage continued 2026-08-22; not in any prior delta)
  - Angle: "India just made liveness detection a telecom infrastructure requirement across 1.4 billion potential users. That's not a use case — that's a market."

---

## Cycle notes

- Worker URL blocked again by session network policy. All reads from GitHub repo; delta written via GitHub API. See prior cycle notes; this is now a recurring session constraint.
- Age assurance is the active regulatory sub-theme this week: NZ joins Australia, UK, EU, and the US — five jurisdictions in active legislative or enforcement motion simultaneously. Watch for vendor response (Yoti, iProov, Veriff, Incode positioning announcements) as a follow-up post angle.
- India DoT item warrants flagging to Amol / as a potential post — it is the largest single mandatory liveness deployment in history and a clear demand signal for identity vendors operating in South Asia.
- Next weekday cycle (2026-08-26, Wednesday): watch for EBA/AMLA publications (none in 14 cycles now), any EC implementing act updates on EUDI, and FIDO Alliance September conference pre-announcements.
