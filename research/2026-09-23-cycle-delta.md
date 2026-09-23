# Cycle Delta — 2026-09-23

Window: 2026-09-21 → 2026-09-23 (last 48 hours)

> **Operational note:** Worker API (`ditto-slack-bot.dittobot.workers.dev`) remains blocked by environment egress policy (403 connect_rejected). Brand brief and pillar guides not fetched from worker. Research conducted via WebSearch + GitHub baseline/prior-delta context. Delta pushed directly to GitHub via MCP.

---

## Override-worthy this cycle

1. **iProov publishes HAPS — Human Approval and Presence Specification for AI agent governance (Sep 21)** — experimental open spec requiring cryptographic proof of genuine human presence and intent before an AI agent executes a sensitive action. Angle: "Permission ≠ Intent. HAPS is the technical answer to the question regulators haven't asked yet: how do you audit that a human actually meant what their AI agent did?"

---

## New findings

### Pillar 1: Banking & Payments

(no new material — PSD3/PSR: still no OJEU publication; secondary sources continue to describe expectation as "H2 2026" with no confirmed date; twenty-sixth Monday check. AMLA CDD RTS September 30 submission to Commission remains a watch item with no press release yet in window. EBA, DORA, ECB: no primary publication with confirmed 2026-09-21–23 date.)

### Pillar 2: EUDI / eIDAS2

- **EUDI ARF Iteration 6 opens September 23, 2026 (today)** — The sixth Architecture and Reference Framework consultation cycle runs from September 23 to November 18, 2026 (57 days). 15 discussion topics are active: 11 reopened from earlier iterations requiring further refinement, plus 4 newly introduced topics: **Topic AB** (Digital Signature using the EUDI Wallet), **Topic AC** (Cryptographic Binding of Attestations), **Topic AD** (User Binding in Proximity Flows), and **Topic AE** (Liveness Tests in Remote Flows). Topics AC (attestation cryptographic binding) and AE (liveness in remote flows) sit directly on Ditto's product surface — outcomes will shape ARF 2.x and the minimum technical bar for wallet certification before the December 24, 2026 deadline. The GitHub discussions forum is now open for public comment on all 15 topics.
  - Source: https://github.com/eu-digital-identity-wallet/eudi-doc-architecture-and-reference-framework/discussions/categories/arf-discussion-topics
  - Source: https://eudi.dev/latest/discussion-topics/
  - Date: 2026-09-23

### Pillar 3: Fraud / Deepfakes

- **iProov publishes HAPS (Human Approval and Presence Specification) — experimental open protocol for binding genuine human intent to AI agent actions (Sep 21)** — iProov released an experimental open specification on GitHub under the Apache 2.0 licence. HAPS addresses the "authorization ≠ intent" gap in agentic AI workflows: an AI agent holding access credentials can execute actions without a human having specifically intended that action (e.g. via prompt injection, scope creep, or misused tokens). The protocol intercepts a proposed sensitive action, pauses the agent, and requires the user to generate a signed consent credential — containing cryptographic challenges, audience restrictions, expiration timestamps, and single-use nonces — before execution proceeds. HAPS is proof-agnostic (it does not prescribe biometrics, passkey, or any specific mechanism) and is designed to work across OAuth, OpenID Connect, and WebAuthn. A partial Rust reference implementation and test vectors are included; iProov explicitly invites independent review and implementations. Why it matters for an identity vendor: this is the first publicly scoped technical specification that makes human biometric/liveness presence a precondition for high-stakes AI-agent execution — directly on-pillar for Ditto's split-key and strong-authentication narrative, and a natural hook into the "AI agents as a new identity type" thesis that Forrester has flagged as the headline of its forthcoming CIAM Wave evaluation. Also relevant to EUDI Pillar 2: Topic AE (Liveness Tests in Remote Flows, just opened in ARF Iteration 6) could reference protocols like HAPS as candidate implementations.
  - Source: https://mb.com.ph/article/10936891/technews/iproov-publishes-haps-an-experimental-specification-for-verifying-human-approval-of-ai-agent-actions
  - Source: https://context.ph/2026/09/21/iproov-releases-open-haps-framework-verifying-genuine-human-approval-behind-ai-agent-actions/
  - Source: https://idtechwire.com/iproov-publishes-experimental-protocol-for-human-approval-of-ai-agent-actions/
  - Date: 2026-09-21

### Pillar 4: ZKPs in Practice

(no new material — OpenID4VP 1.0 final (July 2025) remains the current specification baseline; no new bank ZKP pilot or specification update with confirmed 2026-09-21–23 date.)

### Pillar 5: Passwordless / Split-key

(no new material — CIMB SecureTAC password sunset (Sep 19) covered in Sep 21 delta; Microsoft Entra ID passkeys-as-default rollout ongoing; FIDO Alliance State of Passkeys 2026 (5 billion active passkeys) is a background data point with no new Sep 21–23 publication. No FIDO Alliance announcement or regulator OTP sunset update with confirmed 2026-09-21–23 date.)

### Pillar 6: LATAM

(no new material in window — Banco Central do Brasil published Resolução BCB nº 587 (Pix fraud-marking and 500k-account exemption changes) on September 18, 2026 — date is pre-window and likely covered in Sep 18 delta. CNBV, Superfinanciera, CMF, SBS, BCB: no primary publication with confirmed 2026-09-21–23 date. Brazil ANPD TikTok ruling still outstanding.)

### Pillar 7: Identity Ecosystem

(no new material — Forrester Wave CIAM evaluation: "kickoff at end of September 2026" remains imminent but not yet launched (Andras Cser lead; "AI agents as a new identity type" headline); cross-reference iProov HAPS (P3 above) as on-pillar for this thesis. DHS biometric GWAC ($440.7M): awards expected late September — not yet announced. No Liminal, KuppingerCole, or Gartner primary publication with confirmed 2026-09-21–23 date.)

---

## Open watch items (carried forward and updated)

- **2026-09-27** — AMLA draft RTS on risk profiling of non-financial sector obliged entities consultation closes.
- **2026-09-30** — AMLA submission to European Commission of finalised CDD RTS (first unified EU KYC baseline). Watch for AMLA press release.
- **2026-09-30** — Ofcom NCII/deepfake hash-matching compliance deadline. Platforms must demonstrate effective hash matching or equivalent. Fines up to 10% of global revenue. After this date, Ofcom can issue enforcement notices. Consultation on 48-hour NCII removal duty (Crime and Policing Act 2026 s.100) expected by end 2026.
- **2026-09-30** — US DOL unemployment insurance Group 1 states (25) Login.gov onboarding deadline. Alabama confirmed. Watch for state-specific go-live announcements this week.
- **Late September 2026** — Forrester Wave CIAM evaluation kick-off (Andras Cser; "AI agents as a new identity type" headline). Could publish any day.
- **Late September 2026** — DHS biometric capture GWAC ($440.7M) awards expected across five tracks (fingerprint, facial, iris, palmprint, multimodal).
- **2026-11-18** — EUDI ARF Iteration 6 closes (15 topics; 4 new including Topics AB, AC, AD, AE). Watch for consensus-driven outputs that will feed ARF 2.x.
- **2026-10-22** — Utah SB73 / Aylo ruling.
- **2026-10-31** — ECB SSM-2026-0301 action plan deadline (AI-enabled cyberattacks; strong phishing-resistant MFA priority area).
- **2026-12-24** — EUDI wallet availability deadline (92 days). Germany 2027-01-02 ("d-you", 40 launch partners).
- **Open** — Coimisiún na Meán v X: X's promised ID verification "within weeks."
- **Open** — Brazil ANPD Board of Directors ruling on TikTok.

---

## Run summary

- **Findings count by pillar:** P2 EUDI: 1 (ARF Iteration 6 opens today). P3 Fraud/Deepfakes: 1 (iProov HAPS Sep 21). All other pillars: no new primary material in window.
- **Override-worthy:** iProov HAPS (Sep 21) — "Permission ≠ Intent" hook, directly bridges P3 fraud and P7 "AI agents as identity type" thesis.
- **Delta path:** `research/2026-09-23-cycle-delta.md` — worker API blocked (egress policy); delta pushed directly to GitHub via MCP.
