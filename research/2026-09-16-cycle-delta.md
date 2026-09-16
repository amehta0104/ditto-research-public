# Cycle Delta — 2026-09-16

Window: 2026-09-14 → 2026-09-16 (last 48 hours)

> **Operational note:** Worker API (`ditto-slack-bot.dittobot.workers.dev`) blocked by environment egress policy for the second consecutive day. Brand brief and pillar guides not fetched from worker; research conducted via web search and GitHub baseline/prior-delta context. Brand context inferred from baseline (2026-05-06) and pillar definitions in the researcher prompt.

---

## Override-worthy this cycle

1. **Revolut social-engineering identity breach exposes passports, selfies, and transaction histories** — An unauthorized party extracted passport scans, driving licences, selfies, and transaction histories from Revolut on 2026-09-14 by sending fraudulent requests using a spoofed legitimate government-agency email domain; the data exposed is the exact kit fraudsters need for synthetic identity attacks and targeted phishing. Account:. Angle: Centralized identity document storage doesn't just create compliance risk — it creates a high-value target. Every KYC that stores a selfie + passport is one breach away from arming the next synthetic-ID wave.

---

## New findings

### Pillar 1: Banking & Payments

(no new material)

### Pillar 2: EUDI / eIDAS 2

(no new material)

### Pillar 3: Fraud / Deepfakes

- **Revolut discloses identity data breach via spoofed government-agency email (2026-09-14)** — Revolut confirmed that an unauthorized party obtained sensitive customer identity data — passports, driving licences, selfies, and transaction histories — after internal staff disclosed it in response to fraudulent requests sent from what appeared to be a legitimate government-agency email domain. This is not a deepfake attack on customers directly, but the data exposed directly enables downstream deepfake onboarding fraud and targeted phishing campaigns. The breach illustrates that liveness and document checks at onboarding do not protect against breaches of the stored artefacts produced by those checks. For Ditto: KYC architectures that centralise biometric + document data create systemic risk long after the onboarding event; selective-disclosure / reusable-identity models that verify attributes without retaining raw credentials eliminate this attack surface entirely.
  - Source: https://hipther.com/news/2026/09/14/133624/fintech-pulse-your-daily-industry-brief-september-14-2026-revolut-ascentai-tabby-nu-finastra-and-kom
  - Date: 2026-09-14

### Pillar 4: ZKPs in Practice

(no new material)

### Pillar 5: Passwordless / Split-key

(no new material)

### Pillar 6: LATAM

(no new material)

### Pillar 7: Identity Ecosystem

- **DHS launches $440.7M government-wide biometric capture device GWAC (2026-09-10; questions closed 2026-09-14)** — DHS posted a solicitation on SAM.gov on 2026-09-10 for a government-wide multiple-award contract (GWAC) with a $440.7M ceiling covering fingerprint, facial, iris, palmprint, and multimodal biometric capture hardware; questions closed 2026-09-14 (in window); proposals due 2026-09-18. Other federal agencies (State Dept., Justice Dept.) can place orders through the vehicle, which DHS frames as ending years of fragmented biometric procurement. At least three awards planned per five technology tracks, no maximum number of contractors. Signal for Ditto: the US federal government is standardising the biometric capture layer at scale — commoditising the sensor hardware tier — while pushing differentiation up the stack to liveness algorithms, matching software, and identity orchestration. Identity vendors who compete on hardware will be squeezed; those who compete on software/orchestration are insulated.
  - Source: https://www.biometricupdate.com/202609/dhs-launches-440m-government-wide-biometric-capture-procurement | https://www.washingtontechnology.com/contracts/2026/09/dhs-starts-bidding-441m-biometric-tech-contract/415937/ | https://fedscoop.com/dhs-biometric-technologies-federal-government-procurement/
  - Date: 2026-09-10 (questions deadline 2026-09-14; proposals due 2026-09-18)

---

## Upcoming watch items (next 2 weeks)

- **2026-09-18** — EUDI Relying Party Engagement Programme first webinar (travel use case focus)
- **2026-09-18** — DHS biometric capture GWAC proposals deadline
- **2026-09-19** — CIMB SecureTAC: password verification sunsetted; all transactions require biometric or OCTO App passcode only
- **2026-09-30** — Ofcom NCII/deepfake compliance deadline
- **Late September** — Forrester Wave™ CIAM expected to publish (Andras Cser lead analyst; "AI agents as a new identity type" is the headline thesis)
- **2026-12-24** — EUDI wallet availability deadline (99 days)
