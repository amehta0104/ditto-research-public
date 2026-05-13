# Cycle Delta — 2026-05-07

Window: 2026-05-05 → 2026-05-07 (last 48 hours)

## Override-worthy this cycle

1. **World Passkey Day 2026: FIDO Alliance reports 5 billion passkeys in use (7 May 2026)** — Big jump in actual usage metrics: 49% of consumers now use passkeys regularly, 68% of organizations have deployed or are actively deploying. Source data is two parallel Sapio Research studies (Apr 2026, 11,000 consumers across 10 countries). Angle: "Passwords didn't die, passkeys finally went mainstream — 5bn in use, 49% use them regularly, 68% of orgs deploying. The fight is no longer adoption. It's where banks land in the lag."

2. **Microsoft Entra passkeys for Windows: GA late May 2026; security questions retired Jan 2027 (announced 7 May 2026)** — Device-bound passkeys via Windows Hello container, supports corporate, personal, and shared devices, with admin controls via Conditional Access. Microsoft signed the Passkey Pledge on the same day. Angle: "When Microsoft kills security questions on Entra in January 2027, it stops being a compliance discussion. Knowledge factors are leaving the building. Banks that still send OTPs as their fallback are next."

3. **Pix MED 2.0 enforcement penalties begin May 2026 (Brazil)** — BCB enforcement of multi-hop Pix fraud-recovery mandate is now live; supervisory penalties for non-compliant institutions started this month, completing the phased rollout that began Feb 2 with mandatory adoption. R$6.5bn in 2025 Pix fraud losses; 7% prior fund-recovery rate is the baseline this is meant to fix. Angle: "Brazil just became the first major market to enforce a multi-hop fraud-tracing mandate on instant payments. The identity question this surfaces: if the credential authorising the original Pix was strong, who is liable downstream?"

---

## New findings

### Pillar 1: Banking & Payments

- **Pix MED 2.0 enforcement penalty phase begins May 2026** — BCB's upgraded refund mechanism (live and mandatory since 2 Feb 2026) traces stolen funds across multiple intermediary accounts with automatic preventive blocks at each hop. Supervisory penalties for non-compliant institutions begin this month, completing the phased rollout. Driven by R$6.5bn in 2025 Pix-fraud losses and a 7% recovery rate under the prior single-hop mechanism. Resolution BCB No. 491 and Resolution CMN No. 5,193 (Nov 2025) layer additional cybersecurity duties on top. Together this is the largest tightening of Pix's security framework since launch in Nov 2020. Baseline noted MED 2.0 mandatory adoption; this is the new enforcement teeth.
  - Source: https://clearingpost.com/insights/bcb-pix-med-2-fraud-recovery-mandatory-2026/
  - Date: 2026-05 (penalty phase begin)

### Pillar 2: EUDI / eIDAS2

(no new material in window — ENISA consultation closed 30 April; next-step certification milestones not yet public this cycle)

### Pillar 3: Fraud / Deepfakes

(no new material in window — no fresh primary-source vendor reports or named bank incidents in the 48h window)

### Pillar 4: ZKPs in practice

(no new material in window — OpenID4VP/VCI self-certification continues from Feb 2026; no fresh announcements this cycle)

### Pillar 5: Passwordless / Split-key

- **FIDO Alliance State of Passkeys 2026 report — released 7 May 2026 (World Passkey Day)** — Estimates 5 billion passkeys now in use globally. Headline numbers: 90% consumer awareness (up from 75% at Oct 2025 Passkey Index); 75% have a passkey enabled on at least one account; 49% use passkeys regularly when available (up materially from 26% of sign-ins on enabling sites in Oct 2025); 68% of organizations have deployed or are actively deploying passkeys for employee sign-ins; 82% say fully passwordless authentication is the ultimate goal, with 28% having reached it. Methodology: two parallel Sapio Research studies in April 2026 — a Consumer Study (11,000 consumers across US, UK, France, Germany, Australia, Singapore, Japan, South Korea, China, India) and a separate enterprise study. Compared to the baseline (Oct 2025 Passkey Index: 15bn capable accounts, 36% with a passkey enrolled, 26% sign-ins via passkey on enabling sites), this is a materially stronger usage picture, not just capability.
  - Source: https://finance.yahoo.com/sectors/technology/articles/fido-alliance-reports-accelerating-global-130000169.html
  - Source: https://www.corbado.com/blog/world-passkey-day-passkey-benchmark-2026
  - Date: 2026-05-07

- **Microsoft: Entra passkeys for Windows GA in late May 2026; security questions removed as Entra ID password-reset option from January 2027 — announced 7 May 2026** — Microsoft Security blog post on World Passkey Day confirms general availability of device-bound passkeys stored in the Windows Hello container, authenticated via face, fingerprint, or PIN. Supports corporate, personal, and shared Windows devices, with admin controls via Conditional Access and Authentication Methods policies. Microsoft also signed the FIDO Passkey Pledge. The dual-message — passkeys land, security questions die — is the more interesting signal for an identity-vendor narrative: it codifies that knowledge-based recovery is being phased out at the IdP layer, not just the front-door auth step.
  - Source: https://www.microsoft.com/en-us/security/blog/2026/05/07/world-passkey-day-advancing-passwordless-authentication/
  - Date: 2026-05-07

- **Sumitomo Mitsui Trust Bank deploys OneSpan FIDO authentication for mobile banking (announced via World Passkey Day coverage, 7 May 2026)** — One of Japan's largest trust banks adopts cloud-based FIDO authentication for mobile banking. Driver: phishing-related fraud losses in the hundreds of millions of yen; alignment with Japan FSA's proposed requirement that financial institutions use phishing-resistant authentication methods. Notable as a Tier-1 Asian bank-level FIDO deployment, not just a tech-platform metric.
  - Source: https://finance.yahoo.com/sectors/technology/articles/fido-alliance-reports-accelerating-global-130000169.html
  - Date: 2026-05-07

### Pillar 6: LATAM

- **Pix MED 2.0 supervisory penalty phase begins May 2026** The angle is the regulatory-firstness — Brazil is the first major market to operationalise multi-hop fraud reversal as a mandate with teeth, and it makes credential strength + onboarding integrity the auditable spine of Pix. Identity vendors who tie their pitch to "preventing the original credential abuse" rather than "scoring transactions after the fact" should have a sharper Brazilian story this quarter.
  - Source: https://clearingpost.com/insights/bcb-pix-med-2-fraud-recovery-mandatory-2026/
  - Date: 2026-05

### Pillar 7: Identity ecosystem

(no new material in window — no fresh analyst publications, M&A, or category funding announcements specific to identity vendors in the 48h window. Money 20/20 Europe (2-4 June) and KuppingerCole EIC (19-22 May) are upcoming inflection points but not yet news.)

---

## Run summary

- Findings by pillar: P1: 1 | P2: 0 | P3: 0 | P4: 0 | P5: 3 | P6: 1 (cross-listed) | P7: 0 — Total: 4 distinct findings
- Override-worthy: FIDO 5bn passkeys / State of Passkeys 2026; Microsoft Entra passkeys GA + security-question retirement; Pix MED 2.0 enforcement phase
- Delta path: research/2026-05-07-cycle-delta.md
