# Cycle Delta — 2026-08-20

Window: 2026-08-18 → 2026-08-20 (last 48 hours — Thursday)

Worker note: `ditto-slack-bot.dittobot.workers.dev` returns 403 this session (egress-proxy policy denial — same class as the 2026-08-10→08-19 runs). Delta written to GitHub directly via MCP. Skill files could not be read from the worker; research conducted using prior delta context and web searches. This is a tooling regression, not a content gap; all research steps completed normally.

**Quiet cycle.** The September 1 cluster (UK DVS Trust Framework 1.0, Microsoft Entra passkeys-by-default, OpenAI Daybreak Red) is now 12 days out and all cluster items remain on track — no new OfDIA or Microsoft announcement, no UKAS DVS recognition notice in window. PSD3/PSR OJEU is absent for an **eleventh consecutive cycle**. WindRelay has no follow-through (no attribution, no new geography, no card-scheme response). EUDI Relying Party Programme webinar invitations are still pending (committed by end of August — 11 days remain). The single in-window new finding is a US vendor research report published August 20.

---

## Override-worthy this cycle

(none)

---

## New findings

### Pillar 1: Banking & Payments

(No new EBA / ECB / FCA / PSR / AMLA publication dated 18–20 Aug. **PSD3/PSR OJEU**: no OJEU notice number — **eleventh consecutive cycle**. Final compromise texts 2026-04-23; ECON second-reading recommendation 2026-05-18; OJEU publication anticipated summer/Q3 2026; entry into force 2027 with 18-month transitional period. **AMLA Level 2**: 23 RTS/ITS submitted to Commission by 2026-07-10; Commission adoption of first major package now reported as expected **Q4 2026**; Article 28(1) CDD RTS remains the single most consequential instrument for identity vendors — defines "compliant" identity verification across 27 member states; AMLR applies 2027-07-10. No new discrete in-window print.)

### Pillar 2: Identity orchestration

(No new analyst publication, funding round or M&A announcement dated 18–20 Aug. Standing consolidation anchors unchanged from 08-19 delta: Veridas × Fourthline expected H2 2026; Okta × Permiso ~$200M expected Okta Q3 FY2027; Visa × BioCatch $2.4bn; Cyera × Oasis $1B; Oak $60M seed. **Directional note — "Know Your Agent" framing**: Experian's 2026 U.S. Identity & Fraud Report (P7 below, first-capture) flags that 91% of businesses express confidence in "Know Your Agent" capabilities for AI-powered commerce — the same KYA framing surfacing in the NHI/agentic identity cluster anchored in the 08-17 delta (InterSAGE, Socure, Okta × Permiso, Ping Identity). This is a data point for the KYA narrative, not a new standalone finding; cross-reference for the drafter building the September agentic identity cluster.)

### Pillar 3: EUDI / eIDAS2

(No new ARF update, ENISA certification action, member-state wallet launch or slip dated 18–20 Aug. **EUDI Relying Party Engagement Programme**: Commission committed to sending formal invitations to selected participants by end of August 2026 — **11 days remaining** as of today; still pending, unchanged. Standing wallet-availability countdown: **24 Dec 2026 (126 days)** — Italy live, Spain pilot, Germany 2 Jan 2027, Netherlands likely miss, Malta partial, Bulgaria not started. Worldline × Lissi EUDI hub (first-captured 08-19) and SPRIND relying-party bottleneck unchanged. No new in-window print.)

### Pillar 4: KYC / AML compliance

(No new FATF, AMLA, AMLR, or national-AML-supervisor print dated 18–20 Aug. Status unchanged from 08-19 delta.)

### Pillar 5: Customer onboarding

(No new onboarding-KPI study or benchmark dated 18–20 Aug. Standing benchmarks unchanged.)

### Pillar 6: Identity verification (IDV)

(No new iBeta certification, FIDO Document Authenticity output, NIST IAL/SP 800-63 release, or UKGC follow-through confirmed 18–20 Aug. **UKGC watch**: the 08-19 delta's first-capture (UKGC warns operators on fuzzy matching and deferred verification as LC17 breach) is now published in the corpus — watch for any Commission follow-through from a reminder blog to formal guidance or enforcement casework. **UK DVS Trust Framework 1.0**: no UKAS recognition notice in window; certification against 1.0 is still stated to begin no earlier than 1 September 2026. No new discrete in-window print.)

### Pillar 7: Fraud / Deepfakes

- **NEW STANDING ANCHOR — Experian 2026 U.S. Identity & Fraud Report: 60% of consumers aware of AI-generated fakes in scams; 80% of businesses using ML/GenAI in fraud management; 91% expressing confidence in "Know Your Agent" capabilities for AI-powered commerce (published 2026-08-20)** — Experian's annual U.S. Identity & Fraud Report describes a fraud landscape in which "scams extend across messages, websites, documents, voices, images and account activity." Key findings: 60% of consumers have heard of AI-generated fake images or videos being used in scams, with more than half saying they are very or extremely concerned about AI-enabled scams; consumers express willingness to verify their identity but only when the request is contextually justified; 80% of businesses already use machine learning or generative AI in fraud management; 93% express confidence in adaptive risk-based authentication; and 91% express confidence in emerging **"Know Your Agent" (KYA) capabilities** as AI-powered commerce evolves — the first consumer-research-backed data point for the KYA framing that has to date rested on vendor and analyst commentary only. Why this matters for Ditto: (a) the 60% consumer awareness / >50% concern figures are the first 2026 primary-survey anchor on AI fraud awareness at the consumer level — adds to the corpus alongside Shufti (deepfake fraud +495% over 2025), Sumsub (+2,100% globally), and iProov (+741% iOS injection YoY); (b) the KYA figure (91%) is materially useful for the September agentic identity cluster — it shows that enterprise buyers are already expressing confidence in KYA tooling rather than treating it as speculative. **Constraint**: this is a US-only report; do not present statistics as global; cite with "in a US study" framing. Vendor-published research — attribute carefully; combine with primary sources (FATF typology, Sumsub, iProov) to anchor any post rather than leading with Experian alone.
  - Source: https://www.experian.com/blogs/insights/2026-identity-fraud-report/
  - Source: https://www.helpnetsecurity.com/2026/08/20/experian-digital-identity-fraud-risks-report/
  - Date: 2026-08-20 (report published; Help Net Security coverage same date)

(No new named-bank deepfake incident, primary vendor report from a non-US regulator, or FATF typology in window. **WindRelay**: no follow-through — no Group-IB attribution to a named crew, no loss figures, no spread beyond Czechia/Slovakia/Slovenia, no card-scheme or supervisor response as of 20 Aug — unchanged from 08-19. **EU AI Act Article 50**: enforcement began 2026-08-02; interpretive guidelines remain in draft as of 20 Aug; no named first enforcement action against an identity or deepfake deployment confirmed in window. Standing fraud anchor context unchanged from 08-19 delta.)

### Pillar 8: Mobile trust & app security

(No new named mobile malware family, banking-trojan campaign, or CVE dated 18–20 Aug. WindRelay/SpyNote unchanged. Zimperium 2026 Mobile Banking Heist Report (2026-03-19) logged as standing uncaptured anchor from 08-19. No new in-window print.)

### Pillar 9: Passwordless / split-key

(No new FIDO Alliance specification, regulator OTP-sunset, or major bank passkey deployment confirmed 18–20 Aug. **Microsoft Entra passkeys-by-default September 1** remains on track — 12 days out; opt-out API live from 2026-08-01; users enabled for SMS/voice auto-enabled for passkeys 2026-09-01; Security Store opens 2026-09-18; full SMS/voice blocking 2027-02-01. No new Microsoft announcement in window. Standing FIDO adoption anchors unchanged: ~5 billion passkeys in use, 90% consumer awareness, 75% enrolled, 49% using regularly, 68% of organisations deployed/deploying for employee sign-in.)

### Pillar 10: ZKPs in practice

(No new bank ZKP pilot, OpenID4VP/VCI deployment, or selective-disclosure/mDL milestone confirmed 18–20 Aug. **OpenID4VP/VCI conformance testing (2026-08-10)** logged as standing uncaptured anchor from 08-19 delta — HAIP-profiled self-certification suites now open; watch for first certified implementations. No new in-window print.)

### Pillar 11: Age assurance & privacy attributes

(No new Ofcom enforcement action or age-assurance regulatory publication dated 18–20 Aug. **OfDIA alcohol age-check guidance** (08-18, captured 08-19): operationally the most consequential age-assurance publication of the quarter — excludes age estimation from DVS certification; requires programmatic checking, medium confidence and biometric binding to the presenter. Awaiting Parliamentary approval of the Licensing Act Order (autumn 2026 intended). **Ofcom October rapid assessment**: still incoming — the surviving European reference standard for platform age verification since France's ban was struck down (08-14, captured 08-18). No new in-window print.)

### Pillar 12: LATAM

(No new CNBV / Banxico / BCB / CMF / SBS / IFT publication confirmed 18–20 Aug. **Philippines BSP NIDAS draft circular**: draft published 2026-08-06, comment period ongoing as of 20 Aug — no final circular confirmed in window (3-month compliance timeline for large banks starts on issuance). **Mexico CNBV CUB biometric reform**: compliance wall early-to-mid November 2026 unchanged; no CNBV or Banxico response to the Congreso CDMX punto de acuerdo (captured 08-19) confirmed in window. **Mexico IFT CURP-SIM enforcement** (captured 08-18) unchanged. **Mercosur Decision 4/2026**: still awaiting national-congress ratification in Argentina, Brazil, Paraguay, Uruguay as of 20 Aug. No new in-window print.)

---

## Next-cycle anchors (updated)

- **September 1 cluster — 12 days out.** All three items on track, none with new announcements in window: (1) **UK DVS Trust Framework 1.0** — certification against 1.0 begins no earlier than 1 Sep; UKAS recognition still awaited; UK CertifID trust mark launches; OfDIA 6-week security review completes ~mid-September; supplemental age-assurance code still pending consultation. Pairs with two strong content items: OfDIA alcohol guidance (08-19) and SQR liquidation (08-19). (2) **Microsoft Entra passkeys-by-default** — 1 Sep auto-enablement; Security Store 18 Sep; full SMS/voice blocking 2027-02-01. (3) **OpenAI Daybreak Red** — assurance-gated capability access (08-17).
- **EUDI Relying Party Engagement Programme — first webinar invitations by end of August (11 days)** — still the highest-value near-term EUDI watch item. Commission confirmed invitations by end of August covering transport, hospitality, tourism, payments and border management. An invitation sent is an immediate content trigger.
- **UKGC follow-through** — watch for Commission moving from reminder blog to formal enforcement casework or guidance on matching quality standards. Also watch whether GAMSTOP publishes match-rate data.
- **SQR aftermath** — watch whether OfDIA addresses provider continuity / credential portability in DVS 1.0 or the supplemental code. No published answer exists.
- **PSD3/PSR OJEU** — no OJEU notice number (eleventh consecutive cycle). Publication still anticipated; any notice number is an immediate content trigger.
- **AMLA Level 2 package → Commission adoption** — first major package expected Q4 2026. Article 28(1) CDD RTS is the one that matters.
- **Philippines BSP NIDAS final circular** — still draft as of 20 Aug; 3-month compliance clock for large banks starts on issuance.
- **WindRelay follow-through** — WATCH: Group-IB attribution, loss figures, LATAM spread, card-scheme response.
- **EU AI Act Article 50 — first named enforcement action** — fines live from 2 Aug; no named identity/deepfake action in window. Interpretive guidelines still in draft. Highest-value watch item in P7.
- **CNBV CUB biometric compliance wall — early-to-mid November 2026** — strongest unbuilt thread; now with political pressure from CDMX punto de acuerdo.
- **Ofcom October rapid assessment to Parliament** — "highly effective" age assurance for under-16 social media; the surviving European reference standard.
- **Precise Biometrics new shares trade on Nasdaq Stockholm ~24 Aug (4 days)** — rights issue 91% subscribed (~SEK 100M).
- **Brazil Digital ECA Phase II** — Google Play Brazil age-verification changes Sep 2026 as first visible signal; administrative sanctions Nov 2026.
- **KuppingerCole NHI Management Leadership Compass** — pending 2026; watch.
- **FATF guidance on consistent implementation of the 2025 Travel Rule Revisions** — flagged for late 2026.
- **iBeta CEN/TS 18099:2025 Level 3 results** — first vendor publications will become an RFP line item.
- All other standing anchors from 08-19 delta unchanged.

---

## Run summary

- Findings count by pillar: P1 Banking: 0 | P2 Identity orchestration: 0 (cross-ref) | P3 EUDI: 0 | P4 KYC/AML: 0 | P5 Onboarding: 0 | P6 IDV: 0 | P7 Fraud/Deepfakes: **1 new standing anchor** (Experian 2026 U.S. Identity & Fraud Report, 2026-08-20) | P8 Mobile trust: 0 | P9 Passwordless: 0 | P10 ZKP: 0 | P11 Age assurance: 0 | P12 LATAM: 0 — **Total: 1 item across 1 pillar.**
- Override-worthy: **none.** This is the first zero-override cycle since August 5. No primary regulatory publication, no named incident, no M&A announcement in window.
- Delta path: research/2026-08-20-cycle-delta.md
- Note: worker 403 (egress-proxy policy denial); delta pushed to GitHub directly via MCP. Slack heartbeat posted to C0B2XF2KYKS.
