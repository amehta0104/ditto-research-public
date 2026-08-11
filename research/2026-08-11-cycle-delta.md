# Cycle Delta — 2026-08-11

Window: 2026-08-09 → 2026-08-11 (last 48 hours — Tuesday rule)

Worker note: `ditto-slack-bot.dittobot.workers.dev` continues to return 403 from the session's egress proxy (policy denial, not a credential issue). Skill files sourced from repository baseline and prior deltas. Delta written directly to GitHub via MCP.

---

## Override-worthy this cycle

(none — strict Aug 9–11 window sparse for Ditto's core pillars; first-capture findings below)

---

## New findings

### Pillar 1: Banking & Payments

(no new PSD3/PSR OJEU notice number, AMLA RTS Commission-adoption confirmation, EBA enforcement press release, FCA/PSR APP fraud reimbursement report publication, or ECB SREP action dated 2026-08-09 to 2026-08-11. The AMLA Level 2 Package — 23 RTS/ITS/guidelines — carried a July 10 statutory deadline; submission to the Commission is presumed complete but no Commission press release or AMLA confirmation notice has been found as of August 11. PSR APP fraud: the PSR published its independent third-party evaluation on July 1, 2026, finding APP fraud losses fell by an estimated £73M/year and APP scam volumes fell by ~35,000 following mandatory reimbursement; the formal Q3 post-implementation consultation is scheduled for December 2026. These events are outside the strict window and carry earlier first-capture dates; flagged here as watch items. No new in-window print.)

### Pillar 2: EUDI / eIDAS2

- **Non-paper calls for EUDI ARF to become the trust infrastructure for autonomous AI agent commerce (August 5, 2026)** — Biometric Update published analysis of a non-paper titled "Trusted Identities for AI Agents: An Opportunity for Europe" (August 5, 2026), proposing that the EUDI Wallet Architecture and Reference Framework should be the baseline for authenticating and authorising AI agents operating across EU borders by 2030. The non-paper argues that the same relying-party registration, selective disclosure, and PID verification infrastructure being built for human EUDI Wallets can be extended to machine identities — making the December 2026 wallet rollout not just a citizen-identity play but the foundation layer for the EU AI agent economy. Framing: billions of AI agents will operate cross-border by 2030; without a common identity layer they will either be untrusted or operate on Big Tech proprietary auth, which contradicts the EU's digital sovereignty objective. For Ditto: this is the first policy-adjacent document framing EUDI ARF as AI agent infrastructure rather than exclusively citizen identity — it bridges the EUDI pillar directly to the September NHI/agentic identity theme. Not in prior deltas (the Aug 5 date falls within the Aug 4–7 cycle window but was not captured in the Aug 7 delta; included here as a first-capture).
  - Source: https://www.biometricupdate.com/202608/eudi-wallet-provides-baseline-target-for-standards-to-enable-agentic-commerce
  - Date: 2026-08-05 (first-capture; not in Aug 7 delta)

### Pillar 3: Fraud / Deepfakes

(no new bank deepfake enforcement action, named identity vendor report, or FATF guidance in strict window. The Aug 4/10 deltas cover the Biometric Update 2026 Deepfake Fraud Detection Market Report ($3B→$6.1B), iProov 2026 Threat Report, and continuous-verification banking pattern. No new in-window print.)

### Pillar 4: ZKPs in practice

(no new bank ZKP pilot, OpenID4VP/VCI deployment announcement, or selective-disclosure mDL milestone in window. No new in-window print.)

### Pillar 5: Passwordless / split-key

(no new FIDO Alliance spec release or standalone regulator OTP-sunset announcement in window. Microsoft Entra passkeys-by-default (September 1 — 21 days) and OpenAI hardware-backed passkeys (September 1 — 21 days) remain the immediate tracked anchors. No new in-window print.

Context note — New Zealand liveness detection thresholds mandated (effective June 29, 2026 / grace period ended August 3): NZ Digital Identity Services Trust Framework Amendment Rules 2026 formally define four levels of biometric assurance (basic, standard, strong, very strong) and mandate that any liveness detection system must comply with ISO/IEC 30107-3 and demonstrate effectiveness against ≥90% of presentation attacks. Separately, the NZ Biometric Processing Privacy Code's 9-month grace period expired August 3, 2026, meaning all organisations using biometric identity verification in New Zealand are now fully subject to its rules. This is outside the strict window and was not in prior deltas; flagged as a regulatory-maturity data point for the liveness/passwordless pillar.)

### Pillar 6: LATAM

(no new CNBV, Superfinanciera, CMF, SBS, BCB, or Pix/Drex action in window. Brazil ANPD Digital ECA Phase II enforcement (November 2026) covered in Aug 10 delta. No new in-window print.)

### Pillar 7: Identity ecosystem

- **Okta acquires Permiso Security for ~$200M to own AI agent identity threat detection — second major NHI acquisition in 12 days (July 30, 2026)** — On July 30, 2026, Okta signed a definitive agreement to acquire Permiso Security for approximately $200 million (almost entirely cash). Permiso brings: 2,500+ identity risk signals; coverage across 70+ identity partners; and SandyClaw, a dynamic sandbox for testing AI agent skills and prompts for malicious behaviour. Post-acquisition, Okta will offer unified ITDR (identity threat detection and response) across human, machine, and AI agent identities in a single platform — the first major identity provider to do so. Strategic context: the deal is the second significant NHI/AI agent identity acquisition in 12 days, following Cyera × Oasis Security ($1B, August 3). The pattern signals that the world's largest identity vendors are in an active land-grab for AI agent identity governance capabilities. The CSA machine-to-human identity ratio is now reported at 144:1; only 21% of organisations have NHI governance programs. Deal close: expected Okta Q3 FY2027 (August–October 2026). For Ditto: the Okta + Cyera pattern confirms that NHI/agentic identity has transitioned from a "watch" theme to a "closing" theme — enterprise procurement decisions are being made now. Identity vendors that can articulate an AI agent identity posture (continuous authorisation, split-key for non-human actors, per-action credential issuance) are differentiated; vendors that only do human onboarding are watching their adjacent category be acquired at scale. Not in any prior delta (July 30 falls within the July 29–31 cycle window but was not captured in the July 31 delta; included here as a first-capture).
  - Source: https://techcrunch.com/2026/07/30/okta-buys-ai-security-startup-permiso-source-says-for-about-200m/
  - Source: https://www.okta.com/newsroom/press-releases/okta-signs-definitive-agreement-to-acquire-permiso-security/
  - Source: https://cyberscoop.com/okta-acquires-permiso-security-ai-identity-threat-detection/
  - Date: 2026-07-30 (first-capture; not in any prior delta)

- **Gartner Hype Cycle for Digital Identity 2026: six new AI-agent-centric categories added — "AI Agent Identity" in Innovation Trigger (July 6, 2026)** — Gartner published its annual Hype Cycle for Digital Identity on July 6, 2026, adding six entirely new entrants, all driven by AI agents and workloads: AI Agent Identity, CIAM for AI Agents, Workload Access Management, Intent-Based Access Control, Identity Security Posture Management, and Authorization Management Platforms. Gartner places AI Agent Identity in the Innovation Trigger phase (2–5 years to mainstream adoption) and frames the 2026 landscape as being "transformed by AI agents, identity visibility and identity threats." Key finding for identity vendors: 94% of organizations report increased machine identities driven by AI/agent deployments; AI agents and machine identities now outnumber human accounts and most tools cannot see or govern them fast enough. The report signals that identity security is consolidating into a single "see → harden → detect and stop" lifecycle that spans human and non-human surfaces. For Ditto: the Gartner framing legitimises the NHI/AI agent narrative as an enterprise procurement theme — CISOs reading this report are now looking for vendors with multi-surface identity governance. Not in prior deltas (publication date July 6 falls well outside recent cycle windows; included here as a first-capture analyst anchor for the September NHI theme).
  - Source: https://www.silverfort.com/blog/3-takeaways-from-the-2026-gartner-hype-cycle-for-digital-identity/
  - Source: https://securityboulevard.com/2026/07/our-3-takeaways-from-the-2026-gartner-hype-cycle-for-digital-identity/
  - Source: https://www.gartner.com/en/documents/8100597
  - Date: 2026-07-06 (first-capture; not in prior deltas)

---

## Next-cycle anchors (updated)

- **UK DVS Trust Framework 1.0 enforcement (September 1 — 21 days)** — BSI and Kantara Initiative confirmed as the two accredited CABs. CertifID UK trust mark launches September 1. OfDIA 6-week DVS security review completes approximately mid-September. **Active**: OfDIA considering supplemental DVS code for age assurance — watch for formal consultation launch date. New-in-cycle: 21 days from enforcement.
- **Microsoft Entra passkeys-by-default / SMS-voice OTP retirement (September 1 — 21 days)** — Full SMS/voice retirement February 1, 2027. September 18: Microsoft opens Security Store for customer-managed telecom provider configuration. Active posting window.
- **OpenAI hardware-backed passkeys mandatory for Trusted Access Cyber members (September 1 — 21 days)** — Partnership with Yubico; access to GPT-5.6 and advanced cyber models reverts to default without compliance.
- **Okta × Permiso deal close (August–October 2026)** — Watch for close announcement and Okta product integration roadmap. Any named bank customer or SI partnership announced post-close is a market signal.
- **PSD3/PSR OJEU publication** — September 2026 tracking window. Still no OJEU notice number as of August 11. Any OJEU notice number is an immediate content trigger.
- **AMLA Level 2 Package Commission adoption** — 23 RTS/ITS/guidelines submitted to Commission by July 10 deadline. Watch for Commission Delegated Regulation publications in the OJEU — the CDD RTS in particular is the most impactful for identity vendors. No publication confirmed as of August 11.
- **EUDI wallet-availability deadline (December 24 — 135 days)** — Status unchanged from Aug 10: Italy (live), Spain (pilot), Germany (Jan 2, 2027), Netherlands (likely miss), Malta (partial), Bulgaria (not started). Systemic relying-party onboarding bottleneck confirmed by SPRIND sandbox (Aug 10 delta). Watch for Commission deadline-extension statement or major relying-party integration.
- **Brazil Digital ECA Phase II enforcement (November 2026)** — Administrative sanctions begin November; formal enforcement January 2027. Watch for Google Play Store September 2026 Brazil age verification changes as first major signal.
- **PSR/FCA consolidation** — Financial Services and Markets Bill 2026-27 in Parliament. PSR Q3 APP fraud post-implementation review: formal consultation December 2026. Independent third-party evaluation (July 1): £73M/year fraud reduction confirmed.
- **September NHI/agentic identity sweep** — Cyera×Oasis $1B (Aug 3), Okta×Permiso $200M (July 30), Gartner Hype Cycle 2026 (six new AI-agent categories, July 6), SailPoint unified human/NHI/AI agent platform launch (Aug 4), Daon three-patent governance series — all converging on September as the month NHI/agentic identity becomes a mainstream CISO procurement topic. Watch for KuppingerCole Non-Human Identity Management Leadership Compass or EU AI Act GPAI guidance naming agent identity as a control requirement.
- **Precise Biometrics rights issue closed August 12 (yesterday)** — Watch for post-close company positioning update and commercial partnership announcements.
- **Mercosur cross-border digital ID (Decision 4/2026)** — Awaiting national-congress ratification. No ratification news as of August 11.
- **AUSTRAC Tranche 2 enforcement** — Reforms effective July 1 (lawyers, accountants, real estate). No Federal Court filing or civil penalty notice as of August 11. Watch for first significant enforcement action.
- **Ofcom October rapid assessment to Parliament** — What constitutes "highly effective age verification" for under-16 social media. Watch for pre-submission Ofcom consultation or working paper.

---

## Run summary

- Findings count by pillar: P1 Banking: 0 (watch items noted) | P2 EUDI: **1** (EUDI ARF as AI agent identity baseline, first-capture Aug 5) | P3 Fraud/Deepfakes: 0 | P4 ZKP: 0 | P5 Passwordless: 0 (NZ liveness mandate noted as non-window context) | P6 LATAM: 0 | P7 Identity ecosystem: **2** (Okta×Permiso first-capture July 30; Gartner Hype Cycle 2026 first-capture July 6) — **Total: 3 findings across 2 pillars**
- Override-worthy: none from strict window. Strongest first-capture: Okta×Permiso $200M — confirms NHI/AI agent identity as the active M&A category (second deal in 12 days with Cyera×Oasis). Account:.
- Delta path: research/2026-08-11-cycle-delta.md
