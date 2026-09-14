# Cycle Delta — 2026-09-14

Window: 2026-09-11 → 2026-09-14 (last 72 hours — Mon back-fill covers weekend)

## Provenance and integrity notes

- **The worker API (ditto-slack-bot.dittobot.workers.dev) is blocked by the remote environment's egress policy this run.** Skill files (brand-brief.md, competitors.md, pillar guides) were not fetched from the worker. Research was conducted using the local repository clone and web search. Pillar framing follows the established delta structure from prior cycles (2026-09-10 and 2026-09-11).
- **Effective new surface is Thursday–Sunday 2026-09-11 to 2026-09-13.** The 09-11 delta was written before the September 11 ID Tech Digest published; that digest's content is new for this cycle.
- **PSD3/PSR Monday-only check run today.** Twenty-first consecutive Monday check with no OJEU notice number found. See Pillar 1.
- **Checked and rejected — Shufti Identity Fraud Report 2026.** Sixth cycle of rejection on identical grounds (vendor-proprietary, no published methodology, undefined denominators). Not re-litigated.
- **Checked and rejected — passkey/FIDO adoption statistics from MojoAuth, Descope and similar secondary aggregators.** No primary FIDO Alliance publication, regulator statement or named-bank announcement in window. Aggregate stats (5 billion passkeys, 68% enterprise deployment) are vendor-survey-origin without datable primary.
- **No naming constraints this cycle.** Google, Android, DHS, GLEIF, eMudhra, 1Password, Bitwarden, Dashlane are freely nameable.
- **Brazil ANPD / TikTok** — appeal window expired approximately 2026-09-12. No ANPD Board of Directors statement or ByteDance filing confirmation found in public sources. Watch item held.
- **Croatia m-Gradani** — September 15 deadline has not yet passed as of run time. No pre-implementation reporting found.

## Override-worthy this cycle

1. **Android now lets users transfer passkeys directly between credential stores — the portability barrier that sustained password-fallback demand has a platform-level answer, and the transfer itself requires biometric auth.** Account: / company. Angle: last cycle, Microsoft documented that social engineering at enrollment is the real attack vector against passkeys — the key itself was never the weakness. This cycle closes the other major deployment objection: passkeys were device- and manager-bound, forcing manual recreation at every relying party after a migration. Google's encrypted device-to-device transfer, gated on biometric authentication to surrender credentials, resolves that. The residual tension is the same one the Microsoft advisory named: whoever social-engineers the outgoing manager's auth now gets the whole vault. Portability and phishing-resistance are now both true; the enrollment identity check is still the boundary.

## New findings

### Pillar 1: Banking & Payments

- **PSD3/PSR Monday check — twenty-first consecutive cycle with no OJEU notice number.** Lexology and Worldline coverage confirms formal publication in the Official Journal of the European Union is still pending as of 2026-09-14; Lexology describes the timeline as "June or July 2026 (potentially slipping to September)." September is now the current month and no notice number has been identified. The legislative texts remain in final legal-linguistic review. Once published, PSR enters into force 20 days after publication and applies after an 18-month transition; PSD3 requires national transposition within 18 months of entry into force.
  - Source: https://www.lexology.com/library/detail.aspx?g=9ac8b1b8-7feb-4b88-8de3-1e7c6ebee46f
  - Source: https://worldline.com/en/home/main-navigation/resources/blogs/2026/the-scope-and-timeline-are-locked-in-for-psd3-and-psr-what-should-psps-know
  - Date: 2026-09-14 (check date); no in-window primary

### Pillar 2: Identity orchestration

(no new material — no analyst publication, vendor consolidation or agentic-identity event in window. Forrester CIAM Wave still kicking off end of September 2026.)

### Pillar 3: EUDI / eIDAS2

(no new material — Secure ID Forum 2026 Istanbul (2026-09-15/16) has not yet begun; EUDI Relying Party Engagement Programme first webinar "Travel Across Europe" is 2026-09-18. No member-state announcement with a datable primary found in window. Standing deadline unchanged: 2026-12-24, 101 days.)

### Pillar 4: KYC / AML compliance

- **GLEIF has appointed eMudhra as a Validation Agent for Legal Entity Identifiers, embedding LEI issuance and renewal into an eKYC platform operating across more than 35 countries — and India is now the world's largest active-LEI jurisdiction.** The appointment was announced 2026-09-11. eMudhra — an Indian digital-trust provider active in PKI, digital signatures and eKYC — is now authorised to verify applicant information and submit LEI applications and renewals through Legal Entity Identifier India Limited (LEIL), a GLEIF-accredited issuer. India became the jurisdiction with the largest number of active LEIs in January 2026 and recorded the highest LEI growth rate among all jurisdictions in Q2 2026. **Why this matters for an identity vendor:** LEIs are the corporate-identity layer underneath financial-institution onboarding and counterparty KYC; embedding LEI verification into an eKYC platform means corporate identity — including UBO resolution and ownership chains — can be resolved alongside individual identity at the same onboarding moment, with a GLEIF-attested result. The structural read is less about the vendor appointment and more about the direction of travel: the largest and fastest-growing LEI market globally is building its corporate-identity infrastructure into the same platforms doing consumer eKYC, which is the integration model the EU's AMLA-mandated CDD regime implies.
  - Source: https://idtechwire.com/gleif-appoints-emudhra-as-validation-agent-for-legal-entity-identifiers/
  - Source: https://www.businesstoday.in/latest/corporate/story/emudhra-appointed-validation-agent-for-lei-services-in-india-as-lei-adoption-rises-554718-2026-09-11
  - Source: https://identityweek.net/gleif-welcomes-emudhra-as-a-validation-agent/
  - Date: 2026-09-11

### Pillar 5: Customer onboarding

(no new material)

### Pillar 6: Identity verification (IDV)

- **DHS has opened a $440.7 million government-wide multiple-award contract for biometric capture devices — the largest single US federal biometric hardware procurement in the corpus — covering fingerprint, facial, iris, palmprint and multimodal systems, with proposals due 2026-09-18.** The solicitation opened 2026-09-10. The vehicle is structured as a GWAC (Government-Wide Acquisition Contract): a minimum of three awards in each of five technology tracks, no maximum contractor count, and the $440.7M ceiling applies across the full vehicle rather than guaranteeing spend to any single awardee. Agencies beyond DHS — including State and Justice — can place orders through the vehicle. The contract runs one year with four annual options. **Why this matters for an identity vendor:** the five-track structure (unimodal fingerprint through full multimodal) establishes that multimodal capture is the US federal baseline expectation, not a premium option. The vehicle creates a procurement channel for biometric capture hardware at every federal agency simultaneously. Critically, the FinCEN/banking-agency VDC FAQs of 2026-09-08 (09-10 delta) established that mDLs and other verifiable digital credentials are valid for CIP at account opening — but the FAQs also note that institutions must maintain "appropriate technology or systems to extract the relevant information." The DHS GWAC is the procurement infrastructure for exactly those systems at the government level. The two events together describe the same gap from opposite ends: the regulatory permission to accept a cryptographic credential exists; the hardware capable of reading what the wallet produces is now being acquired at scale.
  - Source: https://www.biometricupdate.com/202609/dhs-launches-440m-government-wide-biometric-capture-procurement
  - Source: https://fedscoop.com/dhs-biometric-technologies-federal-government-procurement/
  - Source: https://idtechwire.com/dhs-opens-440-million-governmentwide-biometric-device-competition/
  - Date: 2026-09-10 (solicitation open); trade coverage 2026-09-11

### Pillar 7: Fraud / Deepfakes

(no new material — no Sumsub, iProov, FATF or named-bank deepfake case in window. Ofcom NCII/deepfake hash-matching compliance deadline 2026-09-30 — 16 days — still outstanding; no enforcement action announced in window.)

### Pillar 8: Mobile trust & app security

(no new material — eighth consecutive cycle. Per prior recommendation: treat P8 as a weekly rather than daily sweep.)

### Pillar 9: Passwordless / split-key

- **Google shipped direct passkey and password transfer between supported Android credential stores on 2026-09-10, removing the final portability objection to passkey deployment: credentials move device-to-device with biometric authentication as the release gate, so no unencrypted export file is ever created.** The feature is live across Google Password Manager, 1Password, Bitwarden and Dashlane, with the standard open via Android's platform API to any credential provider. Transfer flow: the receiving app initiates, Android detects both managers on-device, the outgoing manager requires biometric or PIN authentication before releasing any credentials, and the data moves encrypted. **The structural change is specific to passkeys.** Previously, passkeys could not be transferred at all — they had to be manually recreated at each relying party after switching credential stores. Passwords could be exported, but only as unencrypted CSV, creating a window of exposure. Both problems are now resolved at the platform layer. **Why this matters for Ditto:** the prior deployment objection was architectural — passkey lock-in to a single credential store sustained demand for password fallbacks and for SMS OTP recovery paths (the same recovery paths the Microsoft advisory on 2026-09-09 identified as the attack surface). Android has answered the portability problem without removing the enrollment-identity dependency. The residual tension: the transfer gate is the outgoing manager's biometric or PIN auth. An attacker who socially engineers that authentication event — exactly the Microsoft advisory attack model — now receives the entire passkey vault in a single move rather than one account at a time. Passkey portability raises the value of the vault and therefore raises the value of the social-engineering attack at the credential-manager level. The enrollment-identity argument applies equally at that boundary. Cross-reference Pillar 9, 2026-09-09 delta: passkey portability and passkey social-engineering are the same problem from opposite ends of the credential lifecycle.
  - Source (primary coverage): https://9to5google.com/2026/09/10/android-passkey-password-transfer/
  - Source: https://techcrunch.com/2026/09/10/google-is-making-it-easier-to-switch-between-password-managers-on-android/
  - Source: https://www.ghacks.net/2026/09/11/android-adds-direct-password-and-passkey-transfer-between-password-managers/
  - Source: https://tech-ish.com/2026/09/13/google-password-manager-1password-bitwarden-and-dashlane-can-now-hand-your-logins-to-each-other/
  - Date: 2026-09-10 (feature live); coverage through 2026-09-13

### Pillar 10: ZKPs in practice

(no new material — no OpenID4VP/VCI update or bank ZKP pilot in window. TrustED EUDI + ZKP pilot (09-11 delta, Pillar 3) remains the strongest in-corpus ZKP-in-practice item.)

### Pillar 11: Age assurance & privacy attributes

(no new material in window — Croatia m-Gradani deadline 2026-09-15 has not yet passed. Biometric Update × Goode Intelligence age-assurance webinar 2026-09-15; 2026 Age Assurance & Digital Age Credentials Market Report — obtain the PDF.)

### LATAM

(no new material — CNBV, Superfinanciera, CMF, SBS, BCB all clear. Brazil ANPD / TikTok: appeal window (~2026-09-12) closed; no published ANPD Board statement or ByteDance filing confirmation found. Watch item remains open. Drex: centralized-registry phase continues; no new pillar update in window.)

### Identity ecosystem

(no new material — no Forrester, KuppingerCole, Gartner or Liminal analyst publication in window. Forrester CIAM Wave still kicking off end of September 2026. DHS biometric GWAC counted under Pillar 6.)

## Open watch items

- **Brazil ANPD / TikTok** — appeal window expired ~2026-09-12. No published outcome. Watch for ANPD Board ruling and 22-platform audit next steps.
- **Croatia alcohol age check — 2026-09-15 (tomorrow).** Mandatory m-Gradani QR-code age check goes live for online alcohol retailers. Watch for (a) implementation-quality reporting, (b) tourist/OIB exclusion detail, (c) enforcement posture.
- **Secure ID Forum 2026 — Istanbul, 2026-09-15/16 (tomorrow).** Government-and-industry forum on identity and borders. Watch for substantive policy announcements from government speakers.
- **Biometric Update × Goode Intelligence age-assurance webinar 2026-09-15 (tomorrow).** Obtain the 2026 Age Assurance & Digital Age Credentials Market Report.
- **GSA PQC Summit 2026-09-16 (2 days).** Post-quantum cryptography policy outputs.
- **EUDI Relying Party Engagement Programme — first webinar "Travel Across Europe", 2026-09-18 (4 days), 14:00–15:30 CET.** First substantive engagement event with the December 2026 deadline in sight.
- **CIMB SecureTAC OTP sunset — 2026-09-19 (5 days).** All web transfers and online card payments must use biometric or passcode app approval from this date. Watch for customer-impact reporting. Pairs with Singpass Android expansion (09-09 delta): same week, two opposite postures on OTP.
- **Australia IDLock privacy consultation — closes 2026-09-18 (4 days).** National rollout 2027.
- **Ofcom NCII/deepfake enforcement — compliance deadline 2026-09-30 (16 days).** Hash-matching must be operational for covered services.
- **US DOL / unemployment insurance — Group 1 states (25) deadline 2026-09-30 (16 days).** Enhanced federal ID verification onboarding.
- **PSD3/PSR — twenty-first Monday check, no OJEU notice. Next check: 2026-09-21.**
- **DHS biometric GWAC — proposals due 2026-09-18 (4 days).** Watch for award announcements and agency order volumes.
- All other standing watch items unchanged from 2026-09-11 delta.

## Run summary

- **Findings count by pillar:** 3 findings across 3 pillars — P9 Passwordless (1: Android passkey transfer, dated 09-10/11); P6 IDV ecosystem (1: DHS $440.7M biometric GWAC, dated 09-10/11); P4 KYC/AML (1: eMudhra/GLEIF Validation Agent, dated 09-11). P1 Banking: PSD3/PSR Monday check (no OJEU notice, twenty-first cycle). All other pillars and LATAM: no new material.
- **Override-worthy:** (1) Android passkey transfer — platform-level portability closes the last major deployment objection to passkeys while keeping the social-engineering enrollment risk intact; pairs with Microsoft advisory 09-09 to complete a two-week passkey-architecture argument.
- **Delta path:** research/2026-09-14-cycle-delta.md — NOTE: worker API was blocked this run; delta pushed directly to GitHub via MCP. Slack post follows.
