# Cycle Delta — 2026-09-21

Window: 2026-09-19 → 2026-09-21 (last 72 hours, Fri–Mon weekend window)

> **Operational note:** Worker API (`ditto-slack-bot.dittobot.workers.dev`) remains blocked by environment egress policy (403 connect_rejected). Brand brief and pillar guides not fetched from worker. Research conducted via WebSearch + GitHub baseline/prior-delta context. Brand context inferred from prior deltas and pillar framing established in the researcher prompt. Delta pushed directly to GitHub via MCP.

---

## Override-worthy this cycle

(none)

---

## New findings

### Pillar 1: Banking & Payments

(no new material — EBA, AMLA, DORA, ECB, PSD3/PSR: no primary publication with confirmed 2026-09-19–21 date found. PSD3/PSR OJ publication still pending, not confirmed in window. Next PSD3/PSR check: 2026-09-22.)

### Pillar 2: EUDI / eIDAS 2

(no new material in window — ARF Iteration 6 begins 2026-09-23, 2 days away; no pre-iteration policy output confirmed in window. No member-state launch announcement with confirmed 2026-09-19–21 date. Note: Germany "d-you" wallet naming/40-partner announcement was 2026-09-09; UK digital ID for alcohol venues came into force 2026-09-15; Euronews 24-of-27 member-state miss article dated 2026-09-16 — all just pre-window, likely covered in prior cycle deltas.)

### Pillar 3: Fraud / Deepfakes

(no new material in window — Ofcom NCII/deepfake hash-matching compliance deadline approaches 2026-09-30 (9 days). No new deepfake case, regulator enforcement action, or vendor report with confirmed 2026-09-19–21 date found.)

### Pillar 4: ZKPs in Practice

(no new material)

### Pillar 5: Passwordless / Split-key

- **CIMB SecureTAC password sunset confirmed executed — Malaysia's CIMB Bank eliminates password-based transaction approval for all online banking, effective 19 September 2026** — As of September 19, all CIMB Clicks Web transfers and merchant card payments require authentication via the CIMB OCTO mobile app using biometrics (Face ID / fingerprint) or a custom 6-digit OCTO App passcode; password-based SecureTAC approvals now fail with an error, and funds are not deducted. This is the first confirmed go-live of a full hard password sunset at a major SE Asian retail bank covering ALL transaction approvals — not just high-value or privileged operations. Customers who have not enrolled biometric/passcode cannot approve transactions until they do. CIMB has ~9 million retail customers across Malaysia. Why this matters for an identity vendor: this is the first live proof point of a major bank hard-removing shared-secret authentication for transaction approval and replacing it entirely with device-bound biometrics/passcode — the architecture Ditto advocates. It is a deployable case study demonstrating the security and UX argument: the bank absorbs the friction of migrating millions of customers off passwords because the fraud-prevention benefit outweighs the onboarding cost. and can both use this.
  - Source: https://www.cimb.com/en/newsroom/2026/cimb-boosts-customer-protection-with-new-biometric-authentication-on-the-cimb-octo-app.html
  - Source: https://soyacincau.com/2026/09/07/passwords-no-longer-supported-cimb-bank-only-accepts-biometrics-or-passcode-for-securetac-approvals-from-19-september/
  - Source: https://www.thestar.com.my/tech/tech-news/2026/09/03/cimb-online-transactions-to-require-securetac-approval-via-biometrics-or-passcode-from-sept-19
  - Date: 2026-09-19 (execution date; pre-launch announcement 2026-09-03/07)

### Pillar 6: LATAM

(no new material — CNBV, Superfinanciera, CMF, SBS, BCB, Pix, Drex: no primary publication with confirmed 2026-09-19–21 date. Brazil ANPD Board of Directors ruling on TikTok still outstanding.)

### Pillar 7: Identity Ecosystem

(no new material in window — Forrester Wave CIAM evaluation expected to kick off "end of September 2026"; no report published yet. Forrester CIAM Landscape Q3 2026 published August 2026, outside window. No Liminal, KuppingerCole, or Gartner primary publication with confirmed 2026-09-19–21 date. DHS biometric capture GWAC ($440.7M): proposals closed 2026-09-18, awards expected later in September — not yet announced.)

---

## Open watch items (carried forward and updated)

- **2026-09-22 (tomorrow)** — PSD3/PSR Monday check (twenty-fifth cycle).
- **2026-09-23** — EUDI ARF Iteration 6 begins (runs to 2026-11-18); watch for opening topic papers and new discussion topics.
- **2026-09-30** — Ofcom NCII/deepfake hash-matching compliance deadline (9 days). Platforms that are not using hash matching must prove their systems are equally effective; fines up to 10% of global revenue for non-compliance. Ofcom plans separate consultation on Crime and Policing Act 2026 s.100 requirement for 48-hour NCII removal.
- **2026-09-30** — US DOL unemployment insurance Group 1 states (25) Login.gov onboarding deadline. Alabama confirmed: beginning September 30, initial UI claimants verify via Login.gov. Watch for other state announcements this week.
- **Late September 2026** — Forrester Wave CIAM evaluation launch (Andras Cser; "AI agents as a new identity type" headline thesis). Could drop any day now.
- **Late September 2026** — DHS biometric capture GWAC ($440.7M) awards expected; proposals closed 2026-09-18 across 5 technology tracks (fingerprint, facial, iris, palmprint, multimodal).
- **2026-10-22** — Utah SB73 / Aylo ruling.
- **2026-10-31** — ECB SSM-2026-0301 action plan deadline.
- **2026-12-24** — EUDI wallet availability deadline (94 days). Germany 2027-01-02 ("d-you", 40 launch partners announced).
- **Open** — Brazil ANPD Board of Directors ruling on TikTok.
- **Open** — Coimisiún na Meán v X: X's promised ID verification "within weeks."
- **Open** — EUDI RP Engagement Programme: first webinar ran 2026-09-18; watch for published outputs/summary.

---

## Run summary

- **Findings count by pillar:** 1 finding — P5 Passwordless (CIMB SecureTAC password sunset executed, 2026-09-19). Pillars 1–4, 6–7: no new primary material in window.
- **Override-worthy:** (none this cycle)
- **Delta path:** `research/2026-09-21-cycle-delta.md` — worker API blocked (egress policy); delta pushed directly to GitHub via MCP.
