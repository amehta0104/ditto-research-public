# Cycle Delta — 2026-08-13

Window: 2026-08-11 → 2026-08-13 (last 48 hours — Thursday rule)

Worker note: `ditto-slack-bot.dittobot.workers.dev` continues to return 403 from the session's egress proxy (policy denial, not a credential issue). Skill files sourced from repository baseline and prior deltas. Delta written directly to GitHub via MCP.

---

## Override-worthy this cycle

(none — two solid EUDI implementation findings, neither individually warrants override. Closest contender: Moldova EVO wallet bank integration (Aug 12) + Italy IT Wallet framework decree (Aug 12 first-capture) together form a useful counter-narrative to the SPRIND relying-party-bottleneck thread — "the wallets have places to be used in countries that have moved" — but this is an editorial angle for the drafter rather than a standalone override post.)

---

## New findings

### Pillar 1: Banking & Payments

(no new PSD3/PSR OJEU notice number, AMLA RTS Commission-adoption confirmation, EBA enforcement press release, FCA/PSR APP fraud report, or ECB SREP action dated 2026-08-11 to 2026-08-13. PSD3/PSR OJEU publication remains September 2026 tracking window; no OJEU notice number found as of August 13. AMLA Level 2 Package: 23 RTS/ITS submitted to Commission by July 10 deadline; Commission adoption not yet confirmed. PSR Q3 APP fraud post-implementation review: survey sent to 50 firms in August, report expected Q3 2026. No new in-window print.)

### Pillar 2: EUDI / eIDAS2

- **Italy IT Wallet framework decree formally approved — implementation rules for private providers and authentic-source connectivity now in force (reported August 12, 2026)** — Italy's interministerial decree, published in the Gazzetta Ufficiale on July 23 and August 3, 2026, formally approves the IT-Wallet System Guidelines and rules for experimentation. This is a distinct milestone from the December 2024 consumer launch on the IO app: the decree establishes the formal governance architecture under which private wallet providers will be tested, technical specifications will be continuously updated by the Department for Digital Transformation, and public bodies will connect as authentic sources (12-month window begins from decree entry into force). Credentials in scope for the experimental phase: ISEE income indicators, school and university qualifications, residence and electoral data, health insurance card, mobile driving licence, European Disability Card, and digital proxy certificates. Private wallet providers entered a controlled national test environment in May 2026. The decree also allows Italy to experiment with market standards ahead of full convergence with the EUDI ARF — meaning Italy can move faster than the December 24 EU-wide deadline requires. Reporting context: Biometric Update published an English-language analysis on August 12, 2026. For Ditto: Italy's framework decree is the governance layer that turns the consumer wallet into a platform relying parties can certifiably integrate. Without it, the IO app wallet is a useful consumer product; with it, it is a legally defined channel for verified-credential exchange. Identity vendors building EUDI relying-party integrations now have a documented Italian governance framework to align against — the December 24 deadline has a rulebook in Italy even if it does not have one yet in Germany or the Netherlands.
  - Source: https://www.biometricupdate.com/202608/italy-approves-it-wallet-framework-ahead-of-eidas-rollout
  - Source: https://en.ilsole24ore.com/art/it-wallet-official-gazette-whats-changing-for-businesses-and-citizens-AJpXkxe
  - Date: 2026-08-12 (Biometric Update article, first-capture in window); decree dates July 23 / August 3 in Gazzetta Ufficiale — not in prior deltas

- **Moldova's first two banks integrate EVO digital identity wallet for in-branch KYC — first private-sector use of national digital ID (August 12, 2026)** — FinComBank and Moldindconbank have become the first commercial financial institutions in Moldova to accept the EVO digital identity wallet for in-branch customer identification. The workflow: customer scans a bank-displayed QR code, reviews the data request on their smartphone, and consents to share only the required attributes — the bank receives the verified identity data without retaining a copy of the underlying document. Michelle Iliev, State Secretary of the Ministry of Economic Development and Digitalization, confirmed this is the first time Moldova's national digital identification infrastructure has been used in the private sector. Moldova joined the WE BUILD Large-Scale Pilot consortium in September 2025, with a commitment to connect 20 relying parties to an EUDI-aligned wallet by end of 2026; EVO 2.0 launched in June 2026 with a Mastercard partnership. Context and significance for Ditto: this finding directly counters the SPRIND relying-party bottleneck finding (Aug 10 delta). The EU's implementation problem — wallets issued, but too few relying parties integrated to make them usable — is not universal. Countries that moved early on wallet issuance and private-sector engagement (Moldova, Italy) are now demonstrating production bank integrations. The commercial pattern is: wallet-to-relying-party QR-based selective disclosure, privacy-preserving (no document copy retained), consent-gated — exactly the architecture Ditto supports. For: a live bank case study from an EUDI-aligned country is a concrete counterexample to "EUDI is behind schedule" — the deadline story is about member-state issuance, not about whether the underlying identity infrastructure works. Not in prior deltas; Moldova EVO 2.0 launch (June 2026) was covered in prior months but not this first bank-integration milestone.
  - Source: https://idtechwire.com/moldovan-banks-begin-accepting-evo-digital-id-wallet/
  - Source: https://logos-pres.md/en/news/the-first-banks-have-integrated-a-digital-wallet-for-identity-verification/
  - Date: 2026-08-12

### Pillar 3: Fraud / Deepfakes

(no new named bank deepfake enforcement action, identity vendor report, or FATF guidance in window. Biometric Update Deepfake Fraud Detection Market Report ($3B→$6.1B), iProov 2026 Threat Report, and Entrust 2026 Identity Fraud Report remain the benchmark anchors from prior deltas. No new in-window print.)

### Pillar 4: ZKPs in practice

(no new bank ZKP pilot, OpenID4VP/VCI deployment announcement, or selective-disclosure mDL milestone in window. OpenID4VP 1.0 self-certification (February 2026) and EU ARF v3.0.0 (July 21) remain the benchmark anchors. No new in-window print.)

### Pillar 5: Passwordless / split-key

(no new FIDO Alliance spec release, regulator OTP-sunset announcement, or DVS certification in window. Signicat ReadID DVS cert by Kantara (Aug 11) covered in Aug 12 delta. Microsoft Entra passkeys-by-default (September 1 — 19 days) and OpenAI hardware-backed passkeys (September 1 — 19 days) remain the primary tracked anchors. No new in-window print.)

### Pillar 6: LATAM

(no new CNBV, Superfinanciera, CMF, SBS, BCB, or Pix/Drex regulatory action in window. Brazil ANPD Digital ECA Phase II guidelines (Aug 10 delta) and Philippines BSP NIDAS draft circular (Aug 10 delta, watch item — still draft as of August 13, no final circular) remain the most recent LATAM/APAC anchors. Mercosur Decision 4/2026: no national-congress ratification news as of August 13. No new in-window print.)

### Pillar 7: Identity ecosystem

(no new M&A, funding round, or analyst report in strict window. Precise Biometrics rights issue (SEK 110M) subscription period closed August 12; outcome announcement expected approximately August 13 — not yet published in search results as of this run. Cybersecurity market funding data ($1.09B in 12 deals, July 15–August 4) is consolidated market intelligence; individual rounds are outside the strict window. WISeKey WISeID AI agent + PQC positioning (Aug 11) and EU AI Act GPAI enforcement live (Aug 2, first-capture Aug 12 delta) remain the most recent anchors. No new in-window print.)

---

## Next-cycle anchors (updated)

- **UK DVS Trust Framework 1.0 enforcement (September 1 — 19 days)** — DVS register: 46 providers, 64+ services. BSI and Kantara confirmed as the two accredited CABs. CertifID UK trust mark launches September 1. OfDIA 6-week security review completes approximately mid-September. OfDIA supplemental age assurance code: watch for formal consultation launch. Watch for any new CAB accreditation or provider removed from register.
- **Microsoft Entra passkeys-by-default / SMS-voice OTP retirement (September 1 — 19 days)** — Hard date 19 days out. September 18: Microsoft opens Security Store for customer-managed telecom provider configuration. February 1, 2027: full SMS/voice blocking. Active posting window.
- **OpenAI hardware-backed passkeys mandatory for Trusted Access Cyber members (September 1 — 19 days)** — Partnership with Yubico; GPT-5.6 and advanced cyber models access reverts without hardware passkey compliance.
- **France under-15 social media age verification (September 1 — 19 days)** — New-account age verification mandatory for platforms in France.
- **PSD3/PSR OJEU publication** — September 2026 tracking window. No OJEU notice number as of August 13. Any OJEU notice number is an immediate content trigger.
- **AMLA Level 2 Package Commission adoption** — 23 RTS/ITS submitted July 10. Watch for Commission Delegated Regulation OJEU publications — CDD RTS is the most impactful for identity vendors. No publication confirmed as of August 13.
- **Precise Biometrics rights issue outcome (expected August 13 — today)** — Watch for allotment announcement and any named strategic investor or over/undersubscription signal. An oversubscribed outcome with named institutional investor would be a content trigger for the biometrics-consolidation thread.
- **Philippines BSP NIDAS final circular** — Draft issued August 6-7, open for public comment. Watch for final memorandum circular — starts 3-month (major banks, digital banks, VASPs) / 6-month (other BSIs) compliance clocks.
- **EUDI wallet-availability deadline (December 24 — 133 days)** — Status unchanged: Italy (live, framework decree in force), Spain (pilot), Germany (Jan 2 2027 — 9 days late), Netherlands (likely miss), Malta (partial), Bulgaria (not started). Relying-party onboarding is the systemic bottleneck (SPRIND, Aug 10 delta). Watch for Commission deadline-extension statement or major relying-party integration announcement. New angle: Moldova (EUDI-adjacent) achieving first bank integrations while EU member states lag.
- **Brazil Digital ECA Phase II enforcement (November 2026)** — Final guidelines published August 2026. Administrative sanctions begin November 2026; formal enforcement January 2027. Watch for Google Play Store September 2026 age verification changes in Brazil.
- **EU AI Act GPAI enforcement (live August 2)** — Article 50 transparency obligations and GPAI fine powers now active. Watch for first GPAI enforcement action naming an agentic use case or first named AI agent provider audited under Article 53/55.
- **September NHI/agentic identity sweep** — Cyera×Oasis $1B, Okta×Permiso $200M, Gartner Hype Cycle 2026 (six AI-agent categories), EU AI Act GPAI enforcement live, WISeKey WISeID + PQC — all converging on September as the month NHI/agentic identity becomes mainstream CISO procurement. Watch for KuppingerCole Non-Human Identity Management Leadership Compass (December 2025 version confirmed; watch for 2026 update).
- **PSR Q3 APP fraud post-implementation review** — Survey sent to 50 firms in August. Report expected Q3 2026. Watch for publication.
- **Okta × Permiso deal close (August–October 2026)** — Watch for close announcement and integration roadmap.
- **Mercosur cross-border digital ID (Decision 4/2026)** — Awaiting national-congress ratification. No ratification news as of August 13.
- **AUSTRAC Tranche 2 enforcement** — Reforms effective July 1 (lawyers, accountants, real estate). No major Federal Court civil penalty filing confirmed as of August 13. Watch for first significant post-enrollment enforcement action.
- **Ofcom October rapid assessment to Parliament** — "Highly effective" age verification definition for under-16 social media. Watch for Ofcom pre-submission consultation or working paper.

---

## Run summary

- Findings count by pillar: P1 Banking: 0 | P2 EUDI: **2** (Italy IT Wallet framework decree first-capture Aug 12; Moldova EVO wallet first bank integrations Aug 12) | P3 Fraud/Deepfakes: 0 | P4 ZKP: 0 | P5 Passwordless/DVS: 0 | P6 LATAM: 0 | P7 Identity ecosystem: 0 — **Total: 2 findings across 1 pillar**
- Override-worthy: none. Strongest combined signal: Italy IT Wallet framework decree + Moldova EVO bank integrations — together support an editorial angle of "the wallets are operational and relying parties are onboarding, in the countries that moved." Drafter may use as a paired proof-point for the EUDI implementation-gap thread. Account:.
- Delta path: research/2026-08-13-cycle-delta.md
