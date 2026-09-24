# Cycle Delta — 2026-09-24

Window: 2026-09-22 → 2026-09-24 (last 48 hours)

> **Operational note:** Worker API (`ditto-slack-bot.dittobot.workers.dev`) remains blocked by environment egress policy (403 connect_rejected). Brand brief and pillar guides not fetched from worker. Research conducted via WebSearch + GitHub baseline/prior-delta context. Delta pushed directly to GitHub via MCP.

---

## Override-worthy this cycle

(none)

---

## New findings

### Pillar 1: Banking & Payments

- **EBA publishes final Guidelines on Third-Party Risk Management, aligned with DORA (Sep 24, 2026)** — The European Banking Authority today published its final Guidelines on the sound management of third-party risk, replacing the 2019 outsourcing guidelines. The new framework shifts from the concept of "outsourcing" to the broader notion of "third-party arrangements" (TPAs) and focuses supervisory attention on arrangements supporting critical or important functions (CIFs) — those whose failure would materially impair a bank's ability to operate. Scope is proportionate: non-CIF arrangements face lighter-touch requirements. The Guidelines promote a full lifecycle approach (due diligence → contracting → monitoring → exit) across both ICT and non-ICT services, and are explicitly aligned with DORA. After entry into force, financial institutions have a two-year transitional period to adapt all existing TPAs. Why it matters for an identity vendor: Ditto and any biometric/KYC third-party provider will likely be classified as supporting a CIF at banks. The two-year transition window is the time to get contractual and operational documentation in order before supervisors begin formal assessments.
  - Source: https://www.eba.europa.eu/publications-and-media/press-releases/eba-publishes-its-final-guidelines-management-third-party-risk-delivering-more-proportionate-and
  - Source: https://fintech.global/2026/09/24/eba-narrows-third-party-risk-rules-to-critical-functions/
  - Date: 2026-09-24

### Pillar 2: EUDI / eIDAS2

(no new material — EUDI ARF Iteration 6 opened Sep 23 (covered in prior delta); 15 discussion topics open through Nov 18. No new member-state launch announcement with confirmed 2026-09-22–24 date.)

### Pillar 3: Fraud / Deepfakes

(no new material in window — iProov HAPS (Sep 21) covered in Sep 23 delta. Ofcom NCII hash-matching compliance deadline Sep 30 is 6 days away; no new enforcement action with confirmed 2026-09-22–24 date.)

### Pillar 4: ZKPs in Practice

(no new material — OpenID Foundation HAIP conformance suite (Aug 7) is pre-window. No new bank ZKP pilot or specification update with confirmed 2026-09-22–24 date.)

### Pillar 5: Passwordless / Split-key

- **BIO-key receives FIDO Alliance Full Certification for Passkey:YOU — explicitly positions product for agentic AI authenticated controls (Sep 23, 2026)** — BIO-key International announced that its Passkey:YOU authenticator has achieved FIDO Alliance Full Certification (FIDO2 CTAP v2.0, Security Assurance Level L1). The product enables a user to unlock a shared passkey service by touching a shared fingerprint scanner or tapping a door-access badge — no smartphone or separate hardware token needed — and is interoperable with Entra ID, Okta, Ping, and Duo. The notable angle: BIO-key explicitly markets the certification as "unlocking new markets including Agentic AI Authenticated Controls," framing FIDO-certified biometrics as cryptographic proof that a specific named individual authorised an AI agent's action. This is the second certified product in one week (alongside iProov HAPS, Sep 21) to treat verified human presence as a precondition for high-stakes AI-agent execution, giving the Ditto "AI agents as new identity type" narrative a second concrete proof point ahead of the expected Forrester Wave CIAM kick-off.
  - Source: https://www.globenewswire.com/news-release/2026/09/23/3367405/0/en/bio-key-receives-fido-alliance-full-certification-for-passkey-you-authentication-unlocking-new-markets-including-agentic-ai-authenticated-controls.html
  - Date: 2026-09-23

### Pillar 6: LATAM

(no new material — BCB Resolução 587 (Pix fraud-marking changes, Sep 18) is pre-window and covered in prior deltas. CNBV, Superfinanciera, CMF, SBS: no primary publication with confirmed 2026-09-22–24 date.)

### Pillar 7: Identity Ecosystem

(no new material — Forrester CIAM Landscape Q3 2026 published Aug 13 (pre-window; three primary drivers: AI agents as new identity type, CIAM expanding into fraud management, reusable identity). Forrester Wave CIAM evaluation expected to kick off end-of-September; not yet launched. DHS biometric GWAC ($440.7M) awards expected late September; proposals closed Sep 18; not yet announced. No KuppingerCole, Liminal, or Gartner primary publication with confirmed 2026-09-22–24 date.)

---

## Open watch items (carried forward and updated)

- **2026-09-27** — AMLA draft RTS on risk profiling of non-financial sector obliged entities consultation closes (3 days).
- **2026-09-30** — AMLA submission to European Commission of finalised CDD RTS (first unified EU KYC baseline). Watch for AMLA press release.
- **2026-09-30** — Ofcom NCII/deepfake hash-matching compliance deadline (6 days). Platforms must demonstrate effective hash matching or equivalent. Fines up to 10% of global revenue. Consultation on 48-hour NCII removal duty (Crime and Policing Act 2026 s.100) expected by end 2026.
- **2026-09-30** — US DOL unemployment insurance Group 1 states (25) Login.gov onboarding deadline. Alabama confirmed.
- **Late September 2026** — Forrester Wave CIAM evaluation kick-off (Andras Cser; "AI agents as a new identity type" headline). Could drop any day.
- **Late September 2026** — DHS biometric capture GWAC ($440.7M) awards expected; five technology tracks.
- **2026-10-22** — Utah SB73 / Aylo ruling.
- **2026-10-31** — ECB SSM-2026-0301 action plan deadline (AI-enabled cyberattacks; strong phishing-resistant MFA priority area).
- **2026-11-18** — EUDI ARF Iteration 6 closes (15 topics, 4 new including Topics AB, AC, AD, AE).
- **2026-12-24** — EUDI wallet availability deadline (91 days). Germany 2027-01-02 ("d-you", 40 launch partners).
- **Open** — Coimisiún na Meán v X: X's promised ID verification "within weeks."
- **Open** — Brazil ANPD Board of Directors ruling on TikTok.

---

## Run summary

- **Findings count by pillar:** P1 Banking: 1 (EBA final third-party risk guidelines, Sep 24). P5 Passwordless: 1 (BIO-key FIDO certification + agentic AI, Sep 23). All other pillars: no new primary material in window.
- **Override-worthy:** (none this cycle)
- **Delta path:** `research/2026-09-24-cycle-delta.md` — worker API blocked (egress policy); delta pushed directly to GitHub via MCP.
