# Cycle Delta — 2026-05-25

Window: 2026-05-22 → 2026-05-25 (last 72 hours — Friday/weekend/Monday)

## Override-worthy this cycle

(none — weekend cycle; no major primary-source regulatory or primary vendor publications on Saturday/Sunday. Top carry-forward for next cycle: AMLA May 28 double-hearing (business-wide risk assessment + home-host supervisory cooperation RTS); EP PSD3/PSR plenary vote expected June 2026.)

## New findings

### Pillar 1: Banking & Payments

(no new material in window — PSD3/PSR: the European Parliament plenary session of 18–21 May 2026 did not include PSD3/PSR; the ECON vote (50-3-5 / 50-2-2, 5 May) moves next to the June plenary; OJEU publication still anticipated June–September 2026. DORA: no new compulsion payments, CTPP designations or on-site inspection outcomes in window. AMLA: the May 20 public hearing on group-wide minimum requirements RTS published no outcome in window; the two May 28 hearings — business-wide risk-assessment Guidelines and Home-Host Supervisory Cooperation RTS — are upcoming; sweep immediately after. EBA Reporting Framework 4.3 final publication expected June 2026 — not yet landed. The 05-14 ECB / Elderson AI-cyber override, 05-18 FCA / Rathi "financial crime is national security" override, and the 05-21 Microsoft SMS-sunset override remain the live cross-channel banking-supervision anchors for the drafter.)

### Pillar 2: EUDI / eIDAS2

(no new material in window — no new member-state launch announcements, ARF updates, or Commission Implementing Acts published. ARF version 2.8.0 is the current published version (EU Digital Identity Wallet GitHub), up from v2.0 in the May-06 baseline — but the incremental release history did not generate a discrete in-window news event. ENISA's EUDIW cybersecurity certification scheme remains in post-consultation review (public review closed 30 April; Implementing Act expected end-2026). Next EUDI inflection points: German EUDI Hackathon 4–5 June Berlin; EUDI Community Event 25 June Berlin. Estonia RIA €21.65M procurement (05-21/22 override) remains the freshest single artifact for converting the "EUDI deadline" argument into a procurement-budget number a CRO can cite.)

### Pillar 3: Fraud / Deepfakes

(no new named-bank deepfake or synthetic-ID incident disclosures with verified in-window primary-source dates. GetReal Security's "Deepfake penetration outpacing security preparedness" Biometric Update article (May 2026, likely published 21–22 May) introduced Deepfake Readiness Benchmark Report headline data — 8/10 organisations encounter AI deepfakes at least occasionally; 45% frequently; 41% of organisations with 1,000+ employees report having hired or onboarded a fake job candidate or imposter — but this publication sits at the edge of or just outside this window. Drafter: treat these stats as fresh category-pattern support for the 05-21 iProov Verified Meetings / Veriff Deepfakes Report cluster, not as a separate standalone finding. Carry-forward: UK legislation banning nudification tools (autumn 2026 expected) is the next statutory anchor following the 05-20 Ofcom hash-matching codes-of-practice override.
  - Source: https://www.biometricupdate.com/202605/deepfake-penetration-outpacing-security-preparedness-getreal-security
  - Date: 2026-05-21 or 2026-05-22 (edge-of-window; treat as carry-forward)

### Pillar 4: ZKPs in practice

(no new material — dual carry-forward:
1. **OpenID Connect ASC 1.0 formal result still pending** — the member vote to advance to Implementer's Draft concluded 15 May 2026; as of this scan (25 May) the OpenID Foundation has still not published an official Implementer's Draft result page. Drafter: continue to treat as "vote concluded, recommended for approval, formal confirmation pending" — do not state it has been approved until the OpenID Foundation result page is live. The "Transformed Claims" mechanism — deriving an over-18 boolean from a birthdate without exposing the DOB — remains the production-grade ZKP-in-practice reference for the eKYC selective-disclosure narrative.
   - Source: https://openid.net/notice-of-vote-to-approve-the-proposed-implementers-draft-of-openid-connect-advanced-syntax-for-claims-asc-1-0/
   - Date: vote concluded 2026-05-15; formal result still not posted as of 2026-05-25
2. **DIF KYA-OS vote outcome still not confirmed** — the 14-day Trusted Agentic AI Working Group review period for KYA-OS 1.0 (formerly MCP-I) concluded approximately 22–25 May 2026; no vote result was published on the DIF blog (blog.identity.foundation) or via DIF newsletter as of this scan. Sweep again in the next cycle.
   - Source: https://blog.identity.foundation/kya-os/
   - Date: 14-day review ended ~2026-05-22 to 2026-05-25; vote result pending)

### Pillar 5: Passwordless / Split-key

- **Microsoft Entra External ID passkeys reach general availability — late May 2026** — Microsoft's "What's New in Entra May 2026" blog (Tech Community, published late May 2026) confirmed two GA milestones: (1) Entra passkeys on Windows (rolling out since late April, completion by mid-June 2026); (2) **Microsoft Entra External ID passkeys** — GA in late May 2026. External ID is Microsoft's CIAM platform for customer-facing B2C applications, making this the first GA of a major hyperscaler's customer-identity layer with native passkey support — not a preview, not enterprise-only. For financial-services firms building consumer-facing apps on Microsoft identity infrastructure, passkeys are now the default authentication path rather than an enterprise configuration opt-in. This closes the enterprise-to-consumer gap that kept the 05-07 Entra Windows GA and 05-21 Microsoft SMS-sunset override as enterprise-only stories. The 05-21 and 05-22 deltas both noted "no specific GA-declaration landed" for Entra External ID; this is that declaration. Additional note: the same blog introduces "Agent ID" — Microsoft Entra's identity foundation for AI agents (non-human principals), positioned as the authentication layer for agentic workloads. Pairs with the 05-22 AuthZEN override (the authorisation-decision layer for agents) to complete the authn + authz architecture for agentic identity.
  - Source: https://techcommunity.microsoft.com/blog/microsoft-entra-blog/whats-new-in-microsoft-entra-may-2026/4517884
  - Source: https://entra.news/p/whats-new-in-microsoft-entra-may
  - Date: 2026-05-25 (approx late May 2026; first confirmed post-05-22 GA declaration)

- **Fintech leads all industries in passkey adoption at ~60% active-use rate — sector benchmark, May 2026** — Cross-industry passkey adoption benchmarks (FIDO Alliance State of Passkeys 2026 synthesis + MojoAuth / Corbado analysis, published May 2026) show fintech and banking at approximately 60% of eligible users actively signing in with a passkey in the last 30 days — the highest of any sector. Ecommerce: 35%; B2B SaaS: 28%; media/entertainment: 18%; cross-industry average: 33–38%. Drivers cited: regulatory pressure (PSD2 SCA, FFIEC guidance, UAE OTP mandate), ATO fraud cost ($200–$4,500 per incident), and aggressive default-on passkey prompting at sign-in. Separately, a Corbado / ID Tech Wire benchmark (May 2026) flagged a key operational friction point: Windows 10/11 desktop passkey login success rates remain 45–60%, far below mobile. Significance for Ditto: this is the first public sector-level breakdown showing fintech ahead of the cross-industry average, providing a concrete stat to anchor the "passkeys in banking are not aspirational — they are the leading sector" argument — and the Windows desktop friction point gives the counterweight (adoption rate ≠ frictionless experience everywhere).
  - Source: https://securityboulevard.com/2026/05/passkey-adoption-rates-by-industry-in-2026-ecommerce-fintech-saas-and-media-benchmarks/
  - Source: https://idtechwire.com/benchmark-report-highlights-operational-hurdles-as-passkey-adoption-matures/
  - Source: https://www.corbado.com/passkey-benchmark-2026
  - Date: 2026-05 (exact date within May unclear; circulating in late May 2026 window)

### Pillar 6: LATAM

(no new material in window — no new CNBV, Superfinanciera, BCB, CMF or SBS publications in window. Standing carry-forwards: Colombia open-finance technical standards to be published by August 2026 (Decree 0368, 7 April 2026); Brazil Pix MED 2.0 and BCB device-limit rules in force; Mexico Fintech Law 2.0 expected October 2026; Chile Law 21,719 data-protection regime fully in force December 2026. The LATAM deepfake incidents +255% / Mexico +500% stat from the 05-06 baseline remains the region's primary fraud anchor. Note: FIDO Authenticate APAC 2–3 June Singapore (Cyber Security Agency of Singapore as government sponsor) is the closest regional event — APAC SCA and passkey-adoption trajectory is a proxy leading indicator for the LATAM regulatory arc.)

### Pillar 7: Identity ecosystem

(no new M&A, funding rounds, or analyst report publications in window. Upcoming June 2–5 events will generate significant pillar-relevant material: Money20/20 Europe 2–4 June Amsterdam (identity, deepfake prevention, decentralised identity, agentic commerce all on agenda); FIDO Authenticate APAC 2–3 June Singapore; German EUDI Hackathon 4–5 June Berlin. These three events fall in the same 96-hour window — next Friday/weekend cycle will be heavy. DIF KYA-OS vote result and ASC 1.0 formal publication are also due before or during that window. Palo Alto Networks / CyberArk $25B acquisition closed 11 February 2026 — already well outside all deltas; confirm with drafter whether this has been used before surfacing.)

---

## Run summary

- Findings by pillar: P1: 0 | P2: 0 | P3: 0 (edge-of-window carry-forward note) | P4: 0 (dual carry-forward: ASC 1.0 + KYA-OS) | P5: 2 (Entra External ID passkeys GA + fintech passkey sector benchmark) | P6: 0 | P7: 0 → Total: **2 hard findings** (lean weekend cycle; no major regulatory / primary-source publications Sat/Sun)
- Override-worthy: none — Entra External ID passkeys GA is meaningful but anticipated since May 7; OTP-sunset narrative already used as override in 05-21. Top candidates for next cycle: AMLA May 28 double-hearing (both business-wide risk-assessment and home-host supervisory cooperation on same day — uncommon); PSD3/PSR EP plenary vote date (watch for June confirmation); DIF KYA-OS vote result (imminent); ASC 1.0 formal publication (imminent); Money20/20 Europe / FIDO Authenticate APAC / EUDI Hackathon cluster (June 2–5)
- Delta path: research/2026-05-25-cycle-delta.md
- Note: worker at ditto-slack-bot.dittobot.workers.dev returned HTTP 403 host-not-allowed under this session's sandbox network policy; delta written directly to GitHub repo (amehta0104/ditto-linkedin-content) instead; mirror-research workflow will sync to public mirror on push to main
