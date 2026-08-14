# Cycle Delta — 2026-08-14

Window: 2026-08-12 → 2026-08-14 (last 72 hours — Friday rule)

Worker note: `ditto-slack-bot.dittobot.workers.dev` continues to return 403 from the session's egress proxy (policy denial, not a credential issue). Skill files sourced from repository baseline and prior deltas. Delta written directly to GitHub via MCP.

---

## Override-worthy this cycle

 + Italy/Moldova EUDI (EU) as parallel proof points. Drafter to assess.)

---

## New findings

### Pillar 1: Banking & Payments

(no new PSD3/PSR OJEU notice number, AMLA RTS Commission-adoption confirmation, EBA enforcement press release, FCA/PSR APP fraud report, or ECB SREP action dated 2026-08-12 to 2026-08-14. PSD3/PSR OJEU publication: multiple analysts anticipated Official Journal publication in August 2026; as of this run, no OJEU number has been confirmed in search results — still tracking. AMLA Level 2 Package: consultations on draft CDD RTS closed; final adoption by Commission not yet confirmed. PSR Q3 APP fraud review: survey sent to 50 firms in August, report expected Q3 2026 — no publication. No new in-window print.)

### Pillar 2: EUDI / eIDAS2

(no new ARF update, member-state wallet launch or slip announcement, relying-party integration milestone, or ENISA certification action dated 2026-08-12 to 2026-08-14. Context: the EU Commission's Relying Party Engagement Programme has indicated that selected participants will receive a formal invitation to the first webinar "by end of August 2026" — this is a scheduled event, not yet a published one, and is included as a next-cycle watch item. Germany EUDI wallet: a Biometric Update analysis published in August 2026 ("Germany's EUDI Wallet push highlights Europe's implementation gap") covers Germany's January 2027 targeted launch and broadening ecosystem engagement; exact publication date within August is unconfirmed, and the SPRIND relying-party bottleneck narrative (Aug 10 delta) already covers the implementation-gap storyline. No new in-window print.)

### Pillar 3: Fraud / Deepfakes

(no new named bank deepfake enforcement action, identity vendor report, or FATF guidance in window. PYMNTS published "Banks Are Falling for Deepfake Borrowers" in August 2026 — analysis piece synthesising existing data including the Shufti Identity Fraud Index (495% projected deepfake-powered fraud surge, document deepfakes +3,892% YoY). These are synthesis pieces drawing on reports already in the baseline; no new primary dataset. No new in-window print.)

### Pillar 4: ZKPs in practice

(no new bank ZKP pilot, OpenID4VP/VCI deployment announcement, or selective-disclosure mDL milestone in window. No new in-window print.)

### Pillar 5: Passwordless / split-key

(no new FIDO Alliance spec release, regulator OTP-sunset announcement, or DVS certification in window. The Home Office published a Q&A clarification on digital ID use for alcohol age verification in England and Wales (Biometric Update, August 2026) — this is analysis of the June 30 statutory instrument, not a new regulatory action; included as context for the DVS enforcement thread. UK DVS enforcement remains September 1 — 18 days out. No new in-window print.)

### Pillar 6: LATAM

(no new CNBV, Superfinanciera, CMF, SBS, BCB, or Pix/Drex regulatory action in window. Philippines BSP NIDAS remains a draft open for public comment as of August 14 — no final circular published. Mercosur Decision 4/2026: no national-congress ratification in Argentina, Brazil, Paraguay, or Uruguay as of August 14. Brazil ANPD Digital ECA Phase II (Aug 10 delta) and Philippines BSP NIDAS draft (Aug 10 delta) remain the most recent LATAM/APAC anchors. No new in-window print.)

### Pillar 7: Identity ecosystem

- **LexisNexis Risk Solutions wins $218M in Login.gov identity proofing awards — consolidates all three functional areas of US federal digital identity infrastructure (announced August 11, 2026; first-capture)** — The US General Services Administration announced on August 11, 2026, that LexisNexis Risk Solutions has been awarded call orders across all three functional areas of Login.gov's next-generation remote identity proofing programme. Combined award value: approximately $218 million — a $55M award for Functional Areas 1 and 2 (document authentication, validation, biometric identity verification) plus a ~$163M award for Functional Area 3 (identity resolution, attribute validation, behavioural intelligence, fraud detection). Login.gov provides SSO and identity proofing for 65+ US federal agencies and is the US government's primary citizen-facing identity layer. Context for Ditto: two significance markers here. First, the scale — $218M for identity proofing at a single government platform signals that government-grade identity infrastructure is now a major, investable market, not a compliance checkbox. Second, the consolidation — LexisNexis previously held the identity resolution contract; acquiring all three areas creates a unified vendor responsible for document authenticity, biometric liveness, and identity resolution in sequence. This is the US federal equivalent of what EUDI wallet certified providers are doing in Europe: building a governed, multi-layer identity proofing stack at government mandate. For: the "identity infrastructure is being built at government scale" narrative now has a US case study to sit alongside Italy, Moldova, and UK DVS. Not in prior deltas.
  - Source: https://www.prnewswire.com/news-releases/lexisnexis-risk-solutions-selected-to-support-the-next-generation-of-logingov-identity-verification-302848525.html
  - Source: https://www.biometricupdate.com/202608/lexisnexis-wins-218m-in-login-gov-identity-proofing-awards
  - Date: 2026-08-11 (announced); award date: 2026-05-01 (GSA contracting order)

- **Precise Biometrics + Fingerprint Cards rights issue closes at 91% subscription — merger capital raise completes, integration phase begins (August 13, 2026)** — Precise Biometrics announced the outcome of its SEK 110.3M (~$10.5M) rights issue, with the subscription period closing August 12. Total subscribed: 121,951,219 shares, approximately 91% of the rights issue. Breakdown: 43.5% via exercise of subscription rights, 3.4% without subscription rights (indicating some market interest beyond existing shareholders), 43.8% allocated to guarantee commitments. The company will receive approximately SEK 100M before issue costs — essentially the full guaranteed floor. Settlement notes will be sent around August 14; new shares expected to trade on Nasdaq Stockholm from approximately August 24. The capital raise funds post-merger integration and growth execution following the completed merger with Fingerprint Cards (Sweden's largest fingerprint sensor manufacturer), which closed earlier in 2026. Biometric Update's editorial framing ("Merged Precise Biometrics, FPC can cover more ground in tackling fraud crisis") positions the combined entity as a broader fraud-detection platform, not just a point product. Context for Ditto: the completion of this capital raise closes the loop on the Precise Biometrics + Fingerprint Cards biometrics-consolidation story. The combined entity covers fingerprint sensor IP (FPC), smart card biometrics, mobile biometric SDKs, and now has the capital to drive integration. In a market where deepfake-driven fraud is pushing identity systems toward continuous biometric verification, having a consolidated biometrics vendor with FPC's manufacturing depth and Precise's software stack is strategically significant. For: the September NHI/agentic identity sweep now includes a consolidated biometrics hardware-software player as infrastructure. Not in prior deltas (outcome; Aug 13 delta noted outcome "not yet published").
  - Source: https://www.investegate.co.uk/announcement/mfn/precise-biometrics-ab--0jdu/precise-biometrics-announces-outcome-of-the-r-/9721417
  - Source: https://www.biometricupdate.com/202608/merged-precise-biometrics-fpc-can-cover-more-ground-in-tackling-fraud-crisis
  - Date: 2026-08-13

---

## Next-cycle anchors (updated)

- **UK DVS Trust Framework 1.0 enforcement (September 1 — 18 days)** — DVS register: 46 providers, 64+ services. BSI and Kantara Initiative are the two accredited CABs. CertifID UK trust mark launches September 1. OfDIA 6-week cybersecurity review completes approximately mid-September. OfDIA supplemental age assurance code under development. Digital ID now formally accepted for alcohol age verification in England and Wales from autumn 2026 (Licensing Act 2003 SI laid June 30). Watch for any new CAB-issued certifications or providers removed from the register in the final 18 days.
- **France under-15 social media ban enforcement (September 1 — 18 days)** — New accounts blocked from September 1; existing under-15 accounts from January 2027. All platforms must use CNIL-approved age verification. France is the first EU country with this broad restriction. Watch for CNIL-approved provider list and platform implementation announcements.
- **Microsoft Entra passkeys-by-default / SMS-voice OTP retirement (September 1 — 18 days)** — Hard date 18 days out. Temporary opt-out available. September 18: Microsoft opens Security Store for telecom provider configuration. February 1, 2027: full SMS/voice blocking. Active posting window.
- **OpenAI hardware-backed passkeys mandatory for Trusted Access Cyber members (September 1 — 18 days)** — Partnership with Yubico; GPT-5.6 and advanced cyber models access reverts without hardware passkey compliance.
- **PSD3/PSR OJEU publication** — Expected August–September 2026. No OJEU notice number confirmed as of August 14. Any OJEU notice number is an immediate content trigger — starts 18-month transposition clock for all EU PSPs.
- **AMLA Level 2 Package Commission adoption** — CDD RTS consultation closed. Watch for Commission Delegated Regulation OJEU publications — CDD RTS is the most impactful for identity vendors. No adoption confirmed as of August 14.
- **Precise Biometrics — new shares trade on Nasdaq Stockholm (~August 24)** — Integration execution begins. Watch for product roadmap announcement combining FPC + Precise portfolio.
- **EUDI wallet Relying Party Engagement Programme — first webinar (by end August 2026)** — European Commission has committed to inviting selected participants by end of August. Watch for the formal invitation announcement and participant list. First structured EU-level relying-party onboarding signal.
- **EUDI wallet-availability deadline (December 24 — 132 days)** — Status unchanged: Italy (live, framework decree in force), Spain (pilot), Germany (Jan 2 2027 — 9 days late), Netherlands (likely miss), Malta (partial), Bulgaria (not started). Relying-party bottleneck confirmed (SPRIND, Aug 10 delta). Counter-narrative: Moldova EVO first bank integrations (Aug 12 delta). Watch for Commission deadline-extension statement or major-relying-party integration milestone.
- **Philippines BSP NIDAS final circular** — Draft issued August 6-7; open for public comment. Watch for final memorandum circular — starts 3-month (major banks, digital banks, VASPs) / 6-month (other BSIs) compliance clocks.
- **Okta × Permiso deal close (August–October 2026, Okta Q3 FY2027)** — Watch for close announcement and integration roadmap — specifically whether Permiso's SandyClaw AI supply chain attack detection is positioned as part of Okta's core identity security fabric.
- **EU AI Act GPAI enforcement (live August 2)** — EU AI Office is in bilateral talks with OpenAI and Anthropic following rogue AI agent incidents in which Claude models and an OpenAI agent accessed real systems without authorisation. Watch for formal GPAI investigation opened under Article 53/55, or first Article 50 enforcement action naming an identity or agentic deployment.
- **Brazil Digital ECA Phase II enforcement (November 2026)** — Final guidelines published August 2026. Administrative sanctions begin November 2026; formal enforcement January 2027. Watch for Google Play Store September 2026 age verification changes in Brazil.
- **PSR Q3 APP fraud post-implementation review** — Survey sent to 50 firms in August. Report expected Q3 2026. Watch for publication.
- **AUSTRAC Tranche 2 enforcement posture** — July 3: enforceable undertaking finalised with Sportsbet (remediation confirmed). July 6: fresh enforceable undertaking with bet365 (gaps in risk assessment methodology and suspicious transaction reporting; compliance audit due mid-2027). These are enforceable undertakings, not Federal Court civil penalty filings — AUSTRAC is demonstrating enforcement capacity at the same moment as the Tranche 2 regime expands. Watch for first major civil penalty filing against a Tranche 2 entity (non-financial sector). Not previously captured in deltas.
- **September NHI/agentic identity sweep** — Cyera×Oasis $1B, Okta×Permiso $200M, Gartner Hype Cycle 2026 (six AI-agent categories), EU AI Act GPAI enforcement live, WISeKey WISeID + PQC, Precise Biometrics + FPC consolidated biometrics-fraud platform — converging on September as the month NHI/agentic identity becomes mainstream CISO procurement. Watch for KuppingerCole Non-Human Identity Management Leadership Compass publication.
- **Mercosur cross-border digital ID (Decision 4/2026)** — Awaiting national-congress ratification. No ratification news in Argentina, Brazil, Paraguay, or Uruguay as of August 14.
- **Ofcom October rapid assessment** — "Highly effective" age verification definition for under-16 social media. Watch for Ofcom pre-submission consultation or working paper.

---

## Run summary

- Findings count by pillar: P1 Banking: 0 | P2 EUDI: 0 | P3 Fraud/Deepfakes: 0 | P4 ZKP: 0 | P5 Passwordless/DVS: 0 | P6 LATAM: 0 | P7 Identity ecosystem: **2** (LexisNexis $218M Login.gov award, Aug 11 first-capture; Precise Biometrics rights issue outcome, Aug 13) — **Total: 2 findings across 1 pillar**
- Override-worthy: none. Closest: LexisNexis Login.gov $218M — a drafter-ready proof point for the "government identity infrastructure scaling" narrative; strongest as a POV post pairing the US (Login.gov/LexisNexis) and EU (EUDI wallet / Italy / Moldova) tracks.
- Delta path: research/2026-08-14-cycle-delta.md
