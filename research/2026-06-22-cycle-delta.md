# Cycle Delta — 2026-06-22

Window: 2026-06-20 → 2026-06-22 (last 72 hours — Friday–Monday)

## Override-worthy this cycle

1. **GCash launches in-app push OTP today, retiring SMS auth for 90M+ users under BSP/AFASA mandate** — Philippines' largest e-wallet began rolling out in-app push authentication on June 22, replacing SMS OTPs entirely ahead of the June 30 BSP Circular 1213 hard stop; 8 days from now every non-compliant BSP-supervised institution faces mandatory victim reimbursement liability. Account: / company. Angle: "The largest phishing-resistant auth migration in Southeast Asia just happened overnight. When regulators mandate the switch and the market leader executes it at 90M-user scale, it stops being a theory — it's the proof-of-concept the whole industry has been waiting for."

## New findings

### Pillar 1: Banking & Payments
(no new material in window — Binance/HCMC formal board vote still pending before June 30; conflicting narratives unresolved as of June 22; MiCA 83%-unlicensed enforcement wave covered in June 19 delta; PSD3/PSR OJEU publication not yet issued)

### Pillar 2: EUDI / eIDAS2
(no new material in window — EUDI ON Berlin Community Event is June 25, 3 days away; Germany DIdG covered in prior deltas; no Commission, ENISA, or member-state announcement confirmed in window)

### Pillar 3: Fraud / Deepfakes
(no new material in window — no named bank deepfake incident, new regulator enforcement action, or primary vendor report published in window)

### Pillar 4: ZKPs in practice
(no new material in window — no new bank ZKP pilot or OpenID4VP / mDL deployment confirmed in window)

### Pillar 5: Passwordless / split-key
- **GCash begins in-app push OTP rollout (June 22, 2026) — Philippines' 90M-user SMS OTP retirement live under BSP Circular 1213 / AFASA** — GCash (Mynt), the Philippines' largest e-wallet with over 90 million users, began rolling out in-app OTPs delivered via secure push notifications on June 22, replacing all SMS-based authentication codes. The rollout is mandatory compliance with BSP Circular 1213 (June 2025) and the Anti-Financial Account Scamming Act (RA 12010/AFASA), which requires financial institutions to retire SMS OTPs for high-risk transactions by June 30, 2026. The liability structure is binary and enforced: institutions without compliant authentication by June 30 must reimburse scam victims; those that comply receive a regulatory liability shield. GCash is the sector bellwether — if the dominant e-wallet completes the migration at this scale, it de-risks the compliance path for the ~500 BSP-supervised institutions still in transition. A separate AFASA deadline also falls June 25 (3 days from now): mandatory real-time fraud management systems (FMS) for all entities processing ≥ ₱75M average monthly network value, covering behavioral analytics, device-change detection, and geolocation tracking. BSP Deputy Governor Elmore Capule confirmed no deadline extension for either requirement. For Ditto: this is the most concrete, regulatory-mandate-driven in-app phishing-resistant authentication deployment at consumer scale in Southeast Asia to date, and the liability-shift mechanic is a replicable model for every market where OTP sunset rules are pending.
  - Source: https://mynt.com.ph/newsroom/gcash-rolls-out-in-app-otps-via-push-notifications-to-combat-phishing-scams-fraud-this-june-2026
  - Source: https://www.gmanetwork.com/news/money/companies/990983/gcash-to-roll-out-in-app-otps-starting-june-22-2026/story/
  - Source: https://www.gizguide.com/2026/06/gcash-in-app-otp-roll-out.html
  - Source: https://fintechnews.ph/71657/security/gcash-otps-june-afasa-security-update/
  - Source: https://www.zigram.tech/article/afasa-compliance-upgrade-fraud-system-2/ (AFASA FMS June 25 deadline)
  - Source: https://bitpinas.com/fintech/bsp-otp/ (BSP Circular 1213 overview)
  - Date: 2026-06-22

### Pillar 6: LATAM
(no new material in window — Brazil Drex privacy bill not yet scheduled for Chamber vote; no BCB/CNBV/Superfinanciera/CMF announcement confirmed in window)

### Pillar 7: Identity ecosystem
(no new material in window — Forrester Wave: Workforce Identity Security Platforms Q2 2026 published May 21, outside window; no new M&A or funding round confirmed in window)

---

## Next-cycle anchors (updated)

- **Philippines AFASA FMS deadline (June 25)** — TODAY+3; real-time fraud management systems mandatory for high-volume BSP-supervised entities; watch for BSP enforcement commentary or sector compliance data.
- **Philippines BSP Circular 1213 OTP hard stop (June 30)** — 8 days; watch for compliance-rate data, late-mover bank statements, or any last-minute extension signal.
- **Binance HCMC board vote (before June 30)** — still pending; formal HCMC decision or ESMA statement expected; conflicting narratives (Reuters: rejection likely; Binance: application cleared review, board vote pending) unresolved.
- **EUDI ON Community Event (June 25, Berlin)** — hackathon team presentations, member-state progress updates, Germany DIdG context at ministerial level.
- **FATF Best Practices on Travel Rule Supervision (June 26)** — confirmed publication date; VASP KYC/identity data-sharing obligations globally.
- **MiCA CASP hard deadline (July 1)** — 9 days; France AMF June 30 hard stop; Binance EU exit confirmed; 83% of VASPs still unlicensed.
- **AMLA CDD RTS final draft → Commission (July 10)** — calendar anchor.
- **EU AI Act Article 50 enforcement (August 2, 2026)** — 41 days; deepfake disclosure and AI-generated content labelling obligations become enforceable.
- **UK People's Panel report publication** — consultation formally closed June 21; Ipsos writing final report; watch for government publication and public-acceptance findings.
- **Germany DIdG Bundestag first reading** — watch for scheduling and committee assignment post-EUDI ON June 25.
- **PSD3/PSR OJEU publication** — still expected H2 2026; no confirmed date.
- **Japan JSDA phishing-resistant MFA mandatory deadline** — "summer 2026"; watch for JSDA formal finalization.
- **FIDO Alliance Agentic Authentication TWG** — spec development ongoing; watch for draft specification publication.
- **SailPoint/Entro acquisition close** — Q3 FY2027; watch for integration roadmap.

---

## Run summary

- Findings count by pillar: P1: 0 | P2: 0 | P3: 0 | P4: 0 | P5: 1 (GCash in-app OTP rollout, June 22) | P6: 0 | P7: 0 — **Total: 1 unique finding**
- Override-worthy: **1** — GCash in-app push OTP rollout (June 22, 2026): Philippines' largest e-wallet retires SMS auth for 90M+ users today under BSP/AFASA mandate; June 30 liability-shift deadline 8 days away; no extension. Account: / company.
- Delta path: research/2026-06-22-cycle-delta.md

---

_Note: Worker API (ditto-slack-bot.dittobot.workers.dev) is blocked by the environment's network egress allowlist; skill/pillar files were not loaded from the worker. Delta written directly to GitHub. To restore full skill-file context, add `ditto-slack-bot.dittobot.workers.dev` to the environment's network egress allowlist._
