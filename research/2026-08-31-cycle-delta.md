# Cycle Delta — 2026-08-31

Window: 2026-08-28 → 2026-08-31 (last 72 hours — Monday cycle, weekend coverage)

Worker unreachable this session (egress proxy blocks ditto-slack-bot.dittobot.workers.dev:443 — policy denial). Delta written directly to GitHub.

This is the Monday morning cycle covering the weekend. Two in-window findings confirmed: a NIST positioning statement on agentic AI identity that directly extends the Aug 26-27 GSA/Login.gov RFI thread; and the EUDI Relying Party Engagement Programme's first webinar slipping past its own stated "end of August 2026" deadline. No new EU/UK banking regulatory publication, ZKP pilot, FIDO/passkey regulatory action, or LATAM regulatory instrument in window. Australia Senate has not yet voted on the Online Safety Amendment (Strengthening Enforcement) Bill; OMB Login.gov draft memo has not been finalized as an OMB Circular.

---

## Override-worthy this cycle

1. **NIST's NCCoE has published an explicit positioning statement — "Back to the Future: Why Agentic AI Needs a Strong Identity Foundation" — arguing that the identity challenges of agentic AI are not new and the answer is to implement foundational standards that already exist, not wait for new ones; the post was published 2026-08-27 and covered by Biometric Update alongside a Deutsche Telekom + Vodafone TM Forum Catalyst PoC that demonstrated an AI agent completing in one day what would take an engineer weeks.** Account: / company. Angle: the most authoritative standards body in identity has called the bluff — the hard problem in agentic identity is not that new standards are needed, it is that implementers are not using the ones that exist. One week after GSA's Login.gov RFI asked vendors how to detect and classify AI agents, NIST published a blog that says the governance answer is already on the shelf.

---

## New findings

### Pillar 1: Banking & Payments

(No new EU/UK banking-regulatory publication in window. PSD3/PSR OJEU publication still anticipated H2 2026 — no OJEU notice number confirmed, sixteenth consecutive cycle. AMLA Level 2 package awaiting Commission endorsement Q4 2026. DORA enforcement: no new supervisory print. EBA/ECB: no new joint publication. PSR Q3 APP-fraud review: no new output. FinCEN stablecoin CIP NPRM comment period closed 2026-08-21 — no comment summary, extension or final rule in window.)

### Pillar 2: EUDI / eIDAS2

- **The EUDI Relying Party Engagement Programme's first webinar has slipped past its own stated deadline of "by end of August 2026" — as of 2026-08-31, no invitation has been published and no announcement is visible in any trade source.** The programme's own published language committed to selected participants receiving a formal invitation "by end of August 2026." Today is the last day of August. No invitation notice, no webinar registration page, and no programme update have appeared in trade sources. Why this matters for Ditto: this is the first hard evidence that the relying-party engagement calendar is running behind schedule, 116 days before the December 24 wallet-availability deadline. The SPRIND sandbox bottleneck (captured 08-10) was a structural diagnosis; the webinar slip is a concrete calendar data point — the Commission's own front-door event for onboarding relying parties has already missed its first self-imposed milestone. Relying parties who applied and are waiting for their first structured engagement are now 4+ weeks further from the December deadline without a first touchpoint. **Constraint: the slip is confirmed by absence of evidence, not by a Commission announcement — this may resolve in the next 24-48 hours. Watch for an updated programme page or trade coverage before treating this as a confirmed delay.**
  - Source: https://ec.europa.eu/digital-building-blocks/sites/spaces/EUDIGITALIDENTITYWALLET/pages/978681884/Relying+Party+Engagement+Programme
  - Date: 2026-08-31 (confirmed by absence of announcement, as of run time)

### Pillar 3: Fraud / Deepfakes

(No new named-bank deepfake incident, primary IDV vendor fraud report, or FATF guidance in window.)

### Pillar 4: ZKPs in practice

(No new bank pilot, OpenID4VP/VCI update, selective disclosure, or mDL announcement in window.)

### Pillar 5: Passwordless / split-key

(No new FIDO Alliance output, regulator OTP-sunset announcement, or passkey adoption stat in window. OMB Login.gov draft memo: still in draft, no finalization as OMB Circular as of 2026-08-31. GSA Login.gov RFI for device fingerprinting and AI agent detection: responses still due 2026-09-11; no shortlisting or award in window.)

### Pillar 6: LATAM



### Pillar 7: Identity ecosystem

- **NIST's National Cybersecurity Center of Excellence published a blog post titled "Back to the Future: Why Agentic AI Needs a Strong Identity Foundation" (2026-08-27), authored by Bill Fisher and Ryan Galluzzo, arguing that agentic AI deployments are repeating the same identity management mistakes of the past and that existing foundational standards — not new ones — are the answer; Biometric Update covered this 2026-08-28 alongside a Deutsche Telekom + Vodafone TM Forum Catalyst proof-of-concept (C26.0.921) that operationalises exactly that argument in a live network environment.** The NCCoE blog states: "Early agentic deployments are repeating a familiar pattern — prioritizing feature development and immediate value over security" and "many of the challenges are not new — the same issues that have plagued identity management systems for decades." The NCCoE's stated goal is to "accelerate the adoption of agentic AI by demonstrating how cybersecurity standards and best practices can reduce risk and realize agentic AI value." The Deutsche Telekom/Vodafone Catalyst PoC (C26.0.921, presented DTW Ignite Copenhagen, June 25) demonstrates an AI agent completing network access management — continuously interpreting contractual obligations and translating them into enforceable access policies — in one day versus multiple weeks for an engineer; it anchors on TM Forum's Digital Identity API (TMF720) and incorporates four zero-trust safeguards: initial policy dry-run, human-in-the-loop approval for high-risk identity changes, controlled rollout, and deliberate negative testing with conflicting or incomplete data. The Biometric Update article frames both as evidence that the agentic-identity market is converging: standards bodies say "use what exists," and two competing telcos have already demonstrated it. Why this matters for Ditto: this is the highest-authority signal yet that the agentic identity architecture debate is settling — existing IAM and identity standards are the foundation, integration is the hard problem, new credential types are not. This directly supports the orchestration thesis: if the answer to agentic identity is "use TMF720, use FIDO, use OpenID," then the implementation gap that an orchestration layer closes is exactly the one NIST is naming. The corpus now holds a complete two-week arc: Experian Agent OS (June) → InterSAGE four-layer model → Ping NHI argument → GSA Login.gov RFI ("detect agents at the front door," Aug 26) → NIST NCCoE ("govern them with existing standards," Aug 27) → OMB Login.gov mandate ("scale the platform," Aug 27). The arc runs from product to detection to governance to mandated reach in eight weeks. **Constraints: the NIST blog is a cybersecurity-insights post, not a standard, an RFI, or a regulatory instrument — do not write "NIST requires" or "NIST mandates"; the TM Forum Catalyst PoC was presented in June, not August — the BU article is the in-window event; do not name Deutsche Telekom or Vodafone as Ditto customers or prospects; the US is not a named Ditto ICP.** Not in any prior delta (no "Fisher," "Galluzzo," "NCCoE blog," or "Back to the Future" corpus-wide).
  - Source: https://www.nist.gov/blogs/cybersecurity-insights/back-future-why-agentic-ai-needs-strong-identity-foundation
  - Secondary: https://www.biometricupdate.com/202608/nist-european-telcos-converge-on-identity-as-foundation-for-agentic-ai; https://www.tmforum.org/catalysts/projects/C26.0.921/trusted-agentic-ai-for-access-management
  - Date: 2026-08-27 (NIST blog) / 2026-08-28 (BU in-window coverage)

---

## Next-cycle watch items

- **EUDI Relying Party Engagement Programme webinar** — "end of August" deadline has now lapsed. Watch for Commission update or invitation publishing in the first week of September; if nothing by 2026-09-05, the slip has extended to six weeks from the December deadline.
- **OMB Login.gov draft memo** — still in draft; watch for finalization as OMB Circular. GSA Login.gov RFI responses due 2026-09-11.
- **GSA PQC Summit** — 2026-09-16; watch for published outputs and FICAM draft update the following week.
- **Australia Online Safety Amendment (Strengthening Enforcement) Bill** — Senate committee recommended passage (Aug 25, captured 08-28); watch for Senate floor vote.
- **FinCEN stablecoin CIP NPRM** — comment period closed 2026-08-21; watch for comment summary, agency extension, or law-firm roundup.

---

## Run summary

- **Findings count by pillar:** P2-EUDI (1 — Relying Party webinar slip confirmed past "end of August" deadline); P7-Identity ecosystem (1 — NIST NCCoE "Back to the Future" blog + BU/telco coverage). P1/P3/P4/P5/P6: no new material.
- **Override-worthy:** NIST NCCoE blog positioning agentic AI identity as an existing-standards implementation problem — directly extends the Aug 26-27 GSA Login.gov RFI thread and frames the orchestration argument at its strongest. Account: / company.
- **Delta path:** research/2026-08-31-cycle-delta.md (written to GitHub — worker egress blocked).
