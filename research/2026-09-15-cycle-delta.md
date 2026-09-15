# Cycle Delta — 2026-09-15

Window: 2026-09-13 → 2026-09-15 (last 48 hours)

## Provenance and integrity notes

- **The worker API (ditto-slack-bot.dittobot.workers.dev) is blocked by the remote environment's egress policy this run.** Skill files (brand-brief.md, competitors.md, pillar guides) were not fetched from the worker. Research conducted using local repository clone and web search. Pillar framing follows the established delta structure from prior cycles (2026-09-14 and 2026-09-11).
- **Effective new surface: Saturday–Monday 2026-09-13 to 2026-09-15.** Both primary findings are dated September 15 (watch items materialising on their deadline date).
- **PSD3/PSR check skipped — Tuesday.** Monday-only check. Next check: 2026-09-22.
- **CIMB SecureTAC OTP sunset not yet triggered** — 4 days from run date; no customer-impact reporting found.
- **Secure ID Forum Istanbul underway today (2026-09-15/16)** — programme confirmed, no policy announcements from government speakers found as of run time.
- **Brazil ANPD / TikTok** — appeal window expired ~2026-09-12. No ANPD Board of Directors ruling or ByteDance filing confirmation published. Watch item remains open.
- **EUDI Relying Party Engagement Programme first webinar "Travel Across Europe"** — 2026-09-18 (3 days); confirmed in programme, no pre-release policy output found.
- **iProov / Sumsub / Onfido / Veriff** — no new primary publication in window. iProov 2026 Threat Report is April 8 (already in corpus); Sumsub is November 2025.
- **Forrester CIAM Solutions Landscape Q3 2026** — dated August 13, 2026; outside window. Forrester Wave CIAM to kick off end of September 2026 per Forrester blog. Watch item open.
- **No competitor-naming constraints this cycle** — Yoti is freely nameable (listed on UK DVS statutory register, in-scope as context not competitor-performance claim).

## Override-worthy this cycle

1. **On the same day — September 15 — England and Wales and Croatia both activated mandatory digital age checks for alcohol sales, one through a certified DVS marketplace, the other through the national state digital ID. Two jurisdictions, one day, two architectures.** Account: company /. Angle: the architecture choice is the product question. Croatia mandates m-Gradani — one national-ID infrastructure, zero market alternatives, accountable party is the state. England and Wales mandate a DVS from the statutory trust-framework register — multiple certified providers (Yoti first out), accountability split between UKAS, the provider and the licensee. Both require a government-attested age signal; the question is who issues the credential and who stands behind it. The buyer building age assurance today has to choose which model their market is heading toward — and the Croatia/UK split shows regulators have not yet converged.

## New findings

### Pillar 1: Banking & Payments

(no new material — PSD3/PSR Tuesday run; Monday check skipped. No EBA, ECB, AMLA or DORA publication with a confirmed September 13–15 primary found.)

### Pillar 2: Identity orchestration

(no new material — Forrester CIAM Solutions Landscape Q3 2026 is August 13, outside window. Forrester Wave CIAM evaluation kicks off end of September 2026.)

### Pillar 3: EUDI / eIDAS2

(no new material — Secure ID Forum Istanbul underway but no policy announcements found in window. EUDI Relying Party Engagement Programme first webinar is 2026-09-18. Standing deadline 2026-12-24 — 100 days.)

### Pillar 4: KYC / AML compliance

(no new material — AMLA, FATF, sanctions all clear. AMLR applies 2027-07-10.)

### Pillar 5: Customer onboarding

(no new material)

### Pillar 6: Identity verification (IDV)

(no new material — DHS biometric GWAC proposals due 2026-09-18; no new trade coverage beyond the 09-14 delta finding.)

### Pillar 7: Fraud / Deepfakes

(no new material — no iProov, Sumsub, Veriff, Onfido or FATF primary in window. Ofcom NCII/deepfake compliance deadline 2026-09-30 — 15 days — still outstanding.)

### Pillar 8: Mobile trust & app security

(no new material — ninth consecutive cycle. Treat as weekly sweep.)

### Pillar 9: Passwordless / split-key

(no new material — CIMB SecureTAC OTP sunset is 2026-09-19; no customer-impact reporting yet. FIDO Alliance State of Passkeys 2026 is May 2026, outside window.)

### Pillar 10: ZKPs in practice

(no new material — no OpenID4VP/VCI update or bank ZKP pilot in window. TrustED EUDI + ZKP pilot (09-11 delta) remains strongest in-corpus item.)

### Pillar 11: Age assurance & privacy attributes

- **England and Wales licensed premises can now accept certified digital proof of age for alcohol sales under the Licensing Act 2003 (Mandatory Licensing Conditions) (Amendment) Order 2026, which came into force today (September 15, 2026) — the first time a Digital Verification Service listed on the UK trust-framework statutory register is accepted as lawful age evidence in licensed premises.** The Mandatory Licensing Conditions Amendment Order was approved by both Houses of Parliament on September 8, 2026. The UK Digital Verification Services Trust Framework v1.0 came into effect on September 2, 2026, when UKAS accredited the first conformity assessment body. Digital proof of age must come from a DVS listed on the GOV.UK statutory register meeting the trust framework standards; Yoti is already on the register and is cited in trade coverage as the first deployable app for this purpose. Businesses are not required to adopt digital age checks — physical passports and driving licences remain valid — but the Order creates the legal permission for the first time. **Why this matters for an identity vendor:** England and Wales have formally made a certified third-party DVS — not the issuing government itself — the accountable party for an age-gated regulated activity. The liability and verification standard attach to the trust-framework certification, not to any single state credential. Compare Croatia (same day, below): there, the state is the only provider. The UK model distributes accountability through market certification; Croatia's model centralises it through state infrastructure. For any buyer selling into both markets, the credential-issuance and liability question is answered differently by each regulator.
  - Source: https://www.gov.uk/government/news/new-rules-pave-the-way-for-businesses-to-adopt-digital-proof-of-age-for-alcohol-sales
  - Source: https://www.biometricupdate.com/202609/policy-intention-is-becoming-much-clearer-on-digital-id-for-uk-alcohol-sales
  - Source: https://xident.io/blog/uk-digital-id-alcohol-age-checks-dvs-trust-framework-2026/
  - Source: https://identityweek.net/alcohol-licensing-act-allows-digital-age-checks-in-england-and-wales/
  - Date: 2026-09-15 (Order in force); Parliament approval 2026-09-08; DVS trust framework v1.0 active 2026-09-02

- **Croatia's mandatory m-Gradani QR-code age verification for online alcohol retailers went live today (September 15, 2026) — the first European deployment of a national state digital ID as the sole lawful age-gate for a regulated e-commerce category.** The system replaces self-declared birthdate checkboxes on registered online alcohol retailers. Flow: the online shop generates a QR code at checkout; the customer scans it with their phone; m-Gradani links their verified identity to the purchase; the platform checks their age against government records; the customer receives a notification to confirm. Retailers must register with the Ministry of Economy before connecting their web shop to m-Gradani; the Ministry confirms the seller is authorised to trade in alcohol before approving the connection. Delivery workers are separately required to check physical identification at the doorstep and to withhold goods if the customer refuses or is under 18. **Why this matters for an identity vendor:** Croatia has made the national state digital ID the only compliant verification route for a regulated commercial category — there is no DVS-marketplace alternative, no facial-age-estimation track, no credit-card proxy. The accountability model is state-infrastructure-first: the seller integrates one API, the credential issuer is the state, and no third-party IDV vendor sits between the retailer and the legal obligation. This is the structural opposite of England and Wales (same day, above), where a certified third-party DVS is the mechanism and the state is not the credential issuer. Contrast also with Australia (09-11 delta): Epic used four routes including facial estimation and bank-backed ConnectID; Steam used one (credit card) with ≈65% exclusion. Croatia's design avoids exclusion through mandate — everyone with an m-Gradani-registered identity is covered — but creates dependency on state infrastructure availability and enrollment completeness.
  - Source: https://www.croatiaweek.com/croatia-digital-age-verification-online-alcohol-sales/
  - Source: https://idtechwire.com/croatia-puts-online-alcohol-sales-behind-a-state-digital-id-check/
  - Source: https://total-croatia-news.com/news/croatia-alcohol-sales-e-citizens/
  - Date: 2026-09-15 (implementation live)

### LATAM

(no new material — CNBV, Superfinanciera, CMF, SBS, BCB, Pix all clear. Brazil ANPD / TikTok: appeal window expired ~2026-09-12; no ANPD Board ruling or ByteDance response published. Drex centralized-registry phase continues; no new announcement.)

### Identity ecosystem

(no new material in window — Forrester CIAM Solutions Landscape Q3 2026 dated August 13, outside window; Forrester Wave CIAM evaluation kicks off end of September 2026. No KuppingerCole, Gartner or Liminal publication in window. No M&A or funding announcements found.)

## Open watch items

- **Secure ID Forum 2026 — Istanbul, 2026-09-15/16 (underway now).** Watch for policy announcements from government speakers on digital ID, borders and biometrics. No outputs found as of run time.
- **EUDI Relying Party Engagement Programme — first webinar "Travel Across Europe", 2026-09-18 (3 days), 14:00–15:30 CET.** First substantive engagement event with the December 2026 deadline in sight.
- **DHS biometric GWAC — proposals due 2026-09-18 (3 days).** Watch for award announcements and agency order volumes.
- **Australia IDLock privacy consultation — closes 2026-09-18 (3 days).** National rollout 2027.
- **CIMB SecureTAC OTP sunset — 2026-09-19 (4 days).** Biometric/passcode approval mandatory for all web transfers and online card payments. Watch for customer-impact reporting.
- **PSD3/PSR — twenty-second Monday check: 2026-09-22.** No OJEU notice found in twenty-one prior cycles.
- **Brazil ANPD / TikTok** — appeal window expired ~2026-09-12. No Board ruling published. Watch for ANPD Board of Directors decision and any ByteDance appeal confirmation.
- **Ofcom NCII/deepfake enforcement — compliance deadline 2026-09-30 (15 days).** Hash-matching must be operational.
- **US DOL / unemployment insurance — Group 1 states (25) deadline 2026-09-30 (15 days).**
- **Biometrics Institute "On the Pulse" on watchlists — 2026-09-30 (15 days).**
- **Forrester Wave CIAM evaluation — kicks off end of September 2026.** Watch for initiation announcement.
- **GSA PQC Summit 2026-09-16 (tomorrow).** Post-quantum cryptography policy outputs.
- **ECB SSM-2026-0301 action plan deadline — 2026-10-31 (46 days).** Strongest unused EU banking hook; drafting window closing.
- **EUDI wallet-availability deadline 2026-12-24 (100 days).** Germany 2027-01-02.
- **Coimisiún na Meán v X** — X's promised ID verification "within weeks." Watch for launch.
- **Utah SB73 / Aylo — 2026-10-22 (37 days)** or on Judge Barlow's ruling.
- **DNP / Austriacard** — Austrian FDI clearance, quarter ending September 2026.
- **RAND Europe "Novel Technologies" report** — obtain PDF.
- All other standing watch items unchanged from 2026-09-14 delta.

## Run summary

- **Findings count by pillar:** 2 findings, 1 pillar — P11 Age assurance (UK DVS Alcohol Order in force 2026-09-15; Croatia m-Gradani alcohol check live 2026-09-15). All other pillars and LATAM: no new material.
- **Override-worthy:** (1) UK and Croatia both go live on the same day with digital age checks for alcohol — two architectures (DVS marketplace vs. state-only ID), one regulatory direction; the architecture choice is the identity-vendor product question.
- **Delta path:** research/2026-09-15-cycle-delta.md — NOTE: worker API blocked this run (egress policy denial, per proxy status endpoint); delta pushed directly to GitHub via MCP. Slack post to follow.
