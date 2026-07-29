# Cycle Delta — 2026-07-29

Window: 2026-07-27 → 2026-07-29 (last 48 hours)

Worker note: `ditto-slack-bot.dittobot.workers.dev` returned 403 from the session's egress proxy (policy denial, not a credential issue). Skill files sourced from the repository baseline and prior deltas. Delta written directly to GitHub via MCP.

---

## Override-worthy this cycle

(none)

The single confirmed in-window finding (Keyfactor/Cofide) is a machine-identity acquisition — adjacent to Ditto's thesis but upstream of human identity verification. Not override-worthy on its own. The strongest posting anchor this week remains EU AI Act Article 50 enforcement (August 2 — 4 days), which has been standing in prior deltas and is now imminent: deepfake labelling, chatbot disclosure, and AI-content marking become binding Friday. That is the priority posting window and the company page.

---

## New findings

### Pillar 1: Banking & Payments

(no new EBA / ECB / FCA / PSR / DORA primary print in window. PSD3/PSR OJEU still not published — anticipated summer/autumn 2026. AUSTRAC Tranche 2 compliance officer notification deadline materialised TODAY, July 29. ~90,000 newly in-scope Australian entities — accountants, lawyers, real estate agents, precious metals dealers — subject to criminal liability for non-enrolment; daily compounding civil penalties begin (up to A$18,780/day for corporations). No new AUSTRAC enforcement print found as of this run; watch for regulatory statement or first-mover action.)

### Pillar 2: EUDI / eIDAS2

(no new ENISA certification, ARF update, implementing act, or member-state wallet announcement in window. EU Commission expressed concern in April 2026 that not all member states will make the December 24, 2026 wallet-availability deadline — no update on that assessment in window. ARF v2.8 current. No new in-window news.)

### Pillar 3: Fraud / Deepfakes

(no new named bank deepfake case, Sumsub/iProov/Veriff/Onfido primary report, or FATF guidance dated 27–29 Jul. Standing context unchanged: AU10TIX Q1 2026 FS Fraud Intelligence Report (Jul 9) — 3.89% confirmed fraud rate across financial services, AI-generated identity fraud dominant across all three sub-sectors; Shufti Identity Fraud Index 2026 — document deepfakes +3,892% YoY. EU AI Act Article 50 deepfake-labelling enforcement August 2 — 4 days away.)

### Pillar 4: ZKPs in practice

(no new EU-bank ZKP pilot, OpenID4VP/VCI deployment, or discrete mDL ZKP milestone dated 27–29 Jul. Standing context unchanged.)

### Pillar 5: Passwordless / split-key

(no new FIDO Alliance spec, regulator OTP-sunset announcement, or major bank passkey mandate dated 27–29 Jul. Standing anchors: Microsoft Entra passkeys-by-default + OpenAI hardware-passkey mandate both effective September 1. Visa payment passkeys for AI agent commerce active with 30 European issuers — primary announcement July 2, outside window; Biometric Update coverage 202607 prefix but exact date unconfirmed in window.)

### Pillar 6: LATAM

(no new discrete in-window LATAM regulatory print 27–29 Jul. Mercosur Decision 4/2026 cross-border digital ID accord — covered in Jul 27 delta; awaiting national-congress ratification in Argentina, Brazil, Paraguay, Uruguay. Bolivia and Chile moving to join. CNBV, Superfinanciera, CMF, SBS, BCB produced no new in-window release. Standing LATAM anchors unchanged.)

### Pillar 7: Identity ecosystem

- **Keyfactor announces intent to acquire UK-based Cofide to bring cryptographic verified identity to AI agents and cloud workloads (July 27, 2026)** — Keyfactor, a machine identity management platform, announced its intent to acquire Cofide, a UK startup (founded 2024) that issues cryptographic, short-lived verified identities to AI agents and software workloads using open standards — SPIFFE, OAuth, and OIDC — replacing static, stealable credentials across hybrid and multi-cloud environments. The acquisition extends Keyfactor's Trust Control Plane to every workload and AI agent, giving security teams one system to govern both human and non-human identity at enterprise scale. The stated driver: AI-era enterprises now have automated systems (AI agents, microservices, cloud workloads) that far outnumber employees, yet most still run on static credentials that can be copied or stolen. Cofide's model — every workload gets its own cryptographic, short-lived identity — applies zero-trust principles to the machine layer. For Ditto: this is the first confirmed in-window M&A move explicitly targeting the AI agent identity frontier. It reinforces the same zero-trust, cryptographic-identity argument makes for human authentication, now extended to machines. The consolidation signal: identity vendors that want to serve a bank's complete identity surface must now cover AI agent authentication, not only customer onboarding. Adjacent to, not substitutive for, Ditto's human-biometric product — but the same customer (bank CISO) now buys both.
  - Source: https://www.keyfactor.com/press-releases/keyfactor-announces-intent-to-acquire-cofide-to-bring-verified-identity-to-ai-agents-and-cloud-workloads/
  - Source: https://www.prnewswire.com/news-releases/keyfactor-announces-intent-to-acquire-cofide-to-bring-verified-identity-to-ai-agents-and-cloud-workloads-302834309.html
  - Source: https://www.biometricupdate.com/202607/keyfactor-to-acquire-cofide-as-ai-agents-drive-identity-shift
  - Source: https://www.bankinfosecurity.com/keyfactor-expands-into-ai-agent-identity-cofide-deal-a-32331
  - Date: 2026-07-27

---

## Next-cycle anchors (updated)

- **EU AI Act Article 50 enforcement (August 2 — 4 days)** — Deepfake labelling, chatbot disclosure, AI-content marking become binding. Fines up to €15M / 3% global turnover. CoP Transparency signatory list (deadline July 22) to be published before August 2 enforcement. Highest-urgency posting window of the week — and company page.
- **Ofcom child safety risk assessment records due (July 31 — 2 days)** — Deadline for supervised platforms to submit records; enforcement acceleration against non-compliant platforms expected to follow.
- **AUSTRAC Tranche 2 deadline NOW PASSED (July 29)** — Enrolment cut-off date reached today. Watch for AUSTRAC enforcement action or statement against late-registering entities in coming days.
- **Microsoft Entra passkeys-by-default / OpenAI hardware-passkey mandate (September 1)** — Two passwordless milestones arriving simultaneously; posting opportunity as the hard date nears.
- **UK DVS Trust Framework 1.0 enforcement (September 1)** — Certified private-sector IDV becomes the only permissible route for regulated-sector identity in the UK post-BritCard.
- **France under-15 social-media ban mechanism (September 1)** — New-account age verification requirement; existing-account verification/suspension from January 1, 2027.
- **EUDI wallet-availability deadline (December 24, 2026)** — EU Commission expressed concern in April 2026 that not all member states will make this deadline. Watch for any member-state launch announcement or Commission risk assessment.
- **PSD3/PSR OJEU publication** — Still outstanding; anticipated summer/autumn 2026.
- **Mercosur cross-border digital ID (Decision 4/2026)** — awaiting national-congress ratification. Watch for Argentina and Brazil legislative calendars.
- **Consolidation wave watch** — Keyfactor × Cofide (Jul 27) continues the identity M&A wave: Fourthline × Veridas (Jul 16), SwiftConnect × HID SAFE (Jul 22), OneSpan DigipassONE (Jul 22), World ID $52.5M raise (Jul 24), BIO-key × Central Bank of Jordan (Jul 28).

---

## Run summary

- Findings by pillar: P1 Banking: 0 | P2 EUDI: 0 | P3 Fraud: 0 | P4 ZKP: 0 | P5 Passwordless: 0 | P6 LATAM: 0 | P7 Identity ecosystem: **1** (Keyfactor/Cofide AI agent identity acquisition Jul 27) — **Total: 1 confirmed in-window finding**
- Override-worthy: **none** — EU AI Act Article 50 enforcement (August 2) is the week's highest-urgency posting anchor; use it now
- Delta path: research/2026-07-29-cycle-delta.md
