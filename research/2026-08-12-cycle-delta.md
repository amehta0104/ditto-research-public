# Cycle Delta — 2026-08-12

Window: 2026-08-10 → 2026-08-12 (last 48 hours — Wednesday rule)

Worker note: `ditto-slack-bot.dittobot.workers.dev` continues to return 403 from the session's egress proxy (policy denial, not a credential issue). Skill files sourced from repository baseline and prior deltas. Delta written directly to GitHub via MCP.

---

## Override-worthy this cycle

(none — August 10–12 window is thin; no single event warrants override. Closest contender: Signicat ReadID certified under UK DVS Trust Framework 20 days before enforcement — confirms the DVS register is actively being populated ahead of September 1. Drafter may use as a named proof-point supporting the DVS/age verification thread rather than a standalone post.)

---

## New findings

### Pillar 1: Banking & Payments

(no new PSD3/PSR OJEU notice number, AMLA RTS Commission-adoption confirmation, EBA enforcement press release, FCA/PSR APP fraud report, or ECB SREP action dated 2026-08-10 to 2026-08-12. PSD3/PSR OJEU publication remains the September 2026 tracking window — no OJEU notice number found as of August 12. AMLA Level 2 Package: 23 RTS/ITS submitted to Commission by July 10 deadline; Commission adoption not yet confirmed. No new in-window print.)

### Pillar 2: EUDI / eIDAS2

(no new ARF update, member-state wallet launch or slip announcement, relying-party integration milestone, or ENISA certification action dated 2026-08-10 to 2026-08-12. SPRIND relying-party bottleneck finding (Aug 10 delta) and EUDI ARF as AI agent infrastructure non-paper (Aug 11 delta, first-capture Aug 5) remain the most recent anchors. December 24 deadline: Italy live, Spain pilot, Germany Jan 2, Netherlands likely miss, Malta partial, Bulgaria not started — status unchanged. No new in-window print.)

### Pillar 3: Fraud / Deepfakes

(no new bank deepfake enforcement action, named identity vendor report, or FATF guidance in window. Biometric Update 2026 Deepfake Fraud Detection Market Report ($3B→$6.1B CAGR), iProov 2026 Threat Report, and Entrust 2026 Identity Fraud Report (injection attacks +40% YoY) remain the benchmark anchors from prior deltas. No new in-window print.)

### Pillar 4: ZKPs in practice

(no new bank ZKP pilot, OpenID4VP/VCI deployment announcement, or selective-disclosure mDL milestone in window. OpenID4VP 1.0 self-certification (February 2026) and EU ARF v3.0.0 (July 21) remain the benchmark anchors. No new in-window print.)

### Pillar 5: Passwordless / split-key

- **Signicat ReadID earns UK DVS Trust Framework certification via Kantara Initiative — 20 days before September 1 enforcement (August 11, 2026)** — Signicat's ReadID service has been independently audited by the Kantara Initiative (one of the two accredited Conformity Assessment Bodies under the DVS trust framework) and has secured a three-year listing on the government's official DVS register through June 2029. Certification covers two roles: identity verification component (NFC-based e-passport and identity document chip reading, cryptographic document authentication, issuer facial image retrieval) and identity orchestration. Approved use cases: Right to Work, Right to Rent, and Disclosure and Barring Service (DBS) checks. Timing context: the DVS ecosystem now stands at 46 providers with 64+ certified services; BSI and Kantara Initiative are the only two accredited CABs; the DVS register is the sole legal basis for organisations to rely on certified digital identity checks from September 1. With OfDIA also considering a supplemental age assurance code (Aug 10 delta), the certification pipeline is bifurcating — DVS baseline certification (required before the supplemental age code) plus a second track for age assurance. Vendors that hold only the baseline are excluded from the age channel. For Ditto: named, in-production DVS certifications arriving 20 days before enforcement confirm the market is operationalising — not watching. Identity vendors integrated with DVS-certified providers own a compliant channel at enforcement; those still building one do not. Not in prior deltas.
  - Source: https://www.biometricupdate.com/202608/signicat-certified-for-idv-digital-identity-orchestration-in-uk-by-kantara
  - Source: https://theintermediary.co.uk/2026/08/signicat-secures-uk-digital-identity-certification/
  - Date: 2026-08-11

### Pillar 6: LATAM

(no new CNBV, Superfinanciera, CMF, SBS, BCB, or Pix/Drex action in window. Brazil ANPD Digital ECA Phase II guidelines (Aug 10 delta) and Philippines BSP NIDAS draft circular (Aug 10 delta, watch item) remain the most recent APAC/LATAM anchors. Philippines BSP NIDAS remains a draft open for public comment as of August 12 — no final circular published, no compliance clocks started. Mercosur Decision 4/2026: no national-congress ratification news in Argentina, Brazil, Paraguay, or Uruguay as of August 12. No new in-window print.)

### Pillar 7: Identity ecosystem

- **WISeKey positions WISeID as the trusted identity layer for autonomous AI agents and post-quantum security (August 11, 2026)** — WISeKey issued a positioning statement on August 11 framing its WISeID platform as critical infrastructure for the emerging AI agent economy. The core argument: generative AI is commoditising synthetic identity creation while billions of autonomous AI agents will need verified identities for cross-border transactions — a governance gap that WISeKey intends to fill by combining WISeID (digital identity), its Root of Trust (hardware-backed PKI), and SEALSQ's post-quantum semiconductor technology. The framing explicitly covers people, connected devices, industrial systems, robots, and autonomous AI agents as identity subjects — not just humans. Context: this is a vendor positioning statement, not an M&A or product-launch announcement. WISeKey/SEALSQ is a niche PKI and post-quantum hardware player; its strategic significance for Ditto is the signal it adds to the broader September NHI/AI agent identity sweep (Cyera×Oasis $1B, Okta×Permiso $200M, Gartner Hype Cycle 2026, Daon patents). Multiple independent actors — large identity acquirers, analyst firms, post-quantum chip vendors — are now simultaneously framing AI agent identity governance as the next infrastructure layer. For Ditto: the convergence of post-quantum + AI agent identity in a single vendor announcement is a new framing worth tracking; it previews a procurement conversation where enterprise security teams will want AI agent identity to be quantum-resistant from the outset. Not in prior deltas.
  - Source: https://www.globenewswire.com/news-release/2026/08/11/3342393/0/en/wisekey-positions-wiseid-at-the-center-of-trusted-ai-digital-identity-and-post-quantum-security.html
  - Source: https://www.wisekey.com/press/wisekey-positions-wiseid-at-the-center-of-trusted-ai-digital-identity-and-post-quantum-security/
  - Date: 2026-08-11

- **EU AI Act GPAI enforcement powers live as of August 2, 2026 — 3% fines and vendor compliance obligations now active (first-capture; outside strict window)** — On August 2, 2026, the EU AI Act's enforcement provisions over General-Purpose AI (GPAI) providers went live, including 3% fines, mandatory capability evaluations, and vendor compliance obligations under Articles 53 and 55. Article 50 transparency requirements now apply to any AI agent intended to interact with natural persons or generate content: providers must disclose the AI nature of interactions and, for systemic-risk models (>10^25 FLOPs), maintain risk management obligations that explicitly address agentic use and autonomous capabilities. The General-Purpose AI Code of Practice operationalises these via a Safety and Security Chapter covering AI agents. Identity governance implication: any AI agent operating on behalf of a user in an EU context must meet Article 50 disclosure requirements — meaning agent identity (who the agent is, what it is authorised to do, who it acts for) is now a compliance requirement, not just a best practice. For Ditto: this closes the loop between the EUDI ARF as AI agent identity infrastructure (Aug 5 non-paper, Aug 11 delta) and EU regulatory enforcement. The architecture being built for EUDI wallets (selective disclosure, relying-party verification, PID-backed identity) is precisely the layer needed for GPAI Article 50 compliance in agentic deployments. This is the first EU enforcement mechanism that makes AI agent identity a legal obligation. Not in prior deltas.
  - Source: https://beam.ai/agentic-insights/eu-ai-act-enforcement-august-2-2026-gpai-fines
  - Source: https://www.digitalapplied.com/blog/eu-ai-act-august-2026-transparency-obligations-agency-checklist
  - Date: 2026-08-02 (first-capture; not in prior deltas; Aug 10 and Aug 11 deltas listed as watch item only)

---

## Next-cycle anchors (updated)

- **UK DVS Trust Framework 1.0 enforcement (September 1 — 20 days)** — BSI and Kantara confirmed as the two accredited CABs. DVS register: 46 providers, 64+ services. CertifID UK trust mark launches September 1. OfDIA 6-week security review completes approximately mid-September. OfDIA supplemental age assurance code: watch for consultation launch date. Named recent certification: Signicat ReadID (Aug 11). Watch for additional Kantara-audited certifications in the remaining 20 days and any provider refused certification or removed from the register.
- **Microsoft Entra passkeys-by-default / SMS-voice OTP retirement (September 1 — 20 days)** — Hard date 20 days out. September 18: Microsoft opens Security Store for customer-managed telecom provider configuration. February 1, 2027: full SMS/voice blocking. Active posting window.
- **OpenAI hardware-backed passkeys mandatory for Trusted Access Cyber members (September 1 — 20 days)** — Partnership with Yubico; GPT-5.6 and advanced cyber models access reverts without hardware passkey compliance.
- **Precise Biometrics rights issue outcome (August 13 — tomorrow)** — Subscription period closed August 12. Outcome announcement expected around August 13. Watch for oversubscription/undersubscription signal and any named strategic investor disclosure.
- **PSD3/PSR OJEU publication** — September 2026 tracking window. No OJEU notice number as of August 12. Any OJEU notice number is an immediate content trigger.
- **AMLA Level 2 Package Commission adoption** — 23 RTS/ITS submitted July 10. Watch for Commission Delegated Regulation publications in the OJEU — CDD RTS is the most impactful for identity vendors. No publication confirmed as of August 12.
- **Philippines BSP NIDAS final circular** — Draft issued August 6-7, open for public comment. Watch for final memorandum circular publication — that starts the 3-month (major banks, digital banks, VASPs) / 6-month (other BSIs) compliance clocks.
- **EU AI Act GPAI enforcement (live August 2)** — Article 50 transparency obligations on AI agents now legally enforceable. Watch for first GPAI enforcement action naming an agentic use case or first named AI agent provider audited under Article 53/55. KuppingerCole or Forrester analyst note linking GPAI Article 50 to identity vendor requirements would be a content trigger.
- **EUDI wallet-availability deadline (December 24 — 134 days)** — Status unchanged: Italy live, Spain pilot, Germany Jan 2 2027, Netherlands likely miss, Malta partial, Bulgaria not started. SPRIND relying-party bottleneck identified (Aug 10 delta). Watch for Commission deadline-extension statement.
- **Brazil Digital ECA Phase II enforcement (November 2026)** — Final guidelines published August 2026. Administrative sanctions begin November 2026; formal enforcement January 2027. Watch for Google Play Store September 2026 age verification changes in Brazil.
- **PSR/FCA consolidation** — Financial Services and Markets Bill 2026-27 in Parliament. PSR Q3 APP fraud post-implementation review: survey sent to 50 firms in August, report expected Q3 2026.
- **Okta × Permiso deal close (August–October 2026)** — Watch for close announcement and integration roadmap.
- **September NHI/agentic identity sweep** — Cyera×Oasis $1B, Okta×Permiso $200M, Gartner Hype Cycle 2026 (six AI-agent categories), SailPoint unified platform, Daon patents, WISeKey WISeID + PQC, EU AI Act GPAI enforcement live — convergence on September as the month NHI/agentic identity becomes mainstream CISO procurement. Watch for KuppingerCole Non-Human Identity Management Leadership Compass publication.
- **Mercosur cross-border digital ID (Decision 4/2026)** — Awaiting national-congress ratification. No ratification news as of August 12.
- **AUSTRAC Tranche 2 enforcement** — Reforms effective July 1 (lawyers, accountants, real estate). Enrollment deadline was July 29. No major Federal Court civil penalty filing confirmed as of August 12. Watch for first significant post-enrollment enforcement action.
- **Ofcom October rapid assessment to Parliament** — "Highly effective" age verification definition for under-16 social media. Watch for Ofcom pre-submission consultation or working paper.

---

## Run summary

- Findings count by pillar: P1 Banking: 0 | P2 EUDI: 0 | P3 Fraud/Deepfakes: 0 | P4 ZKP: 0 | P5 Passwordless/DVS: **1** (Signicat ReadID DVS cert by Kantara, Aug 11) | P6 LATAM: 0 | P7 Identity ecosystem: **2** (WISeKey WISeID + PQC AI agent positioning, Aug 11; EU AI Act GPAI enforcement live Aug 2, first-capture) — **Total: 3 findings across 2 pillars**
- Override-worthy: none. Strongest timely finding: Signicat ReadID DVS certification (Aug 11, 20 days before enforcement) — use as a named proof-point for the DVS market operationalising thread. Strongest strategic finding: EU AI Act GPAI Article 50 now legally enforceable for AI agents (Aug 2, first-capture) — bridges EUDI ARF as AI agent infrastructure (Aug 11 delta) to EU enforcement reality.
- Delta path: research/2026-08-12-cycle-delta.md
