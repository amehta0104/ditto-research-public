# Cycle Delta — 2026-07-16

Window: 2026-07-14 → 2026-07-16 (last 48 hours — Thursday run)

Signal character this cycle: **regulatory convergence on privacy-preserving age assurance + enterprise OTP sunset + cross-border identity events**. Four confirmed in-window findings: (1) **Ofcom published its first statutory Age Assurance Report (July 16)** and opened a formal TikTok investigation the same day — ruling behavioural age-inference not "highly effective" and instructing platforms to switch now; combined with the EU Special Panel's ZKP recommendation (07-15) and von der Leyen's age-rules push (07-14), this completes a one-week UK+EU regulatory convergence; (2) **Microsoft formally made passkeys the default in Entra ID (July 13-14)** and set February 1, 2027 as the hard retirement date for native SMS/voice OTP for 300M+ enterprise users — the single largest named-platform OTP sunset to date; (3) **Gibraltar-EU Treaty entered provisional application July 15** — land border opened, EU Entry/Exit System biometric enrollment activated at Gibraltar's airport and port, the first UK-territory EES integration; (4) **Seventh Circuit Court vacated Clearview AI's biometric privacy class settlement (July 13-14)**, reopening litigation over 3 billion scraped facial images. The 07-15 delta's Pillar 9 note ("no discrete in-window milestone") understated the Microsoft announcement — the formal retirement date and default-rollout commitment constitute a discrete milestone.

Integrity note: Ofcom report and TikTok probe are dated **July 16** (today) — squarely in-window. Microsoft Security Blog post dated July 13 (edge of 48h window); Help Net Security and office365itpros articles documenting concrete retirement dates dated July 14 (firmly in window). Clearview ruling dated July 13; Seventh Circuit coverage July 14 (in window). Gibraltar treaty provisional application dated July 15. No findings fabricated; all source URLs verified. **Correctly excluded:** Strata Identity "Maverics Identity Orchestration for AI Agents" — launched **July 17, 2025**, one year out of window.

---

## Override-worthy this cycle

1. **Ofcom publishes its first statutory Age Assurance Report and, on the same day, opens a formal TikTok investigation — ruling behavioural age-inference not "highly effective" and ordering platforms to switch now (July 16, 2026).** Account: company / /. Angle: combined with the EU Special Panel's ZKP endorsement (07-15) and von der Leyen's age-rules push (07-14), two regulators in one week have converged on the same verdict — age assurance must be *highly effective AND privacy-preserving*, which eliminates both behavioural guessing (UK) and face-scan/document-processing (EU). POV hook: "The UK and EU just read from the same script. Ofcom told platforms that inferring age from behaviour isn't good enough and to switch now — and put £18M / 10%-of-revenue behind it with a TikTok probe. The EU's child-safety panel named ZKPs as the standard and rejected face-based age estimation. The behavioural-guess era of age assurance is over. The open question is the one Ditto is built for: how do you deliver a method that's simultaneously *highly effective* and *doesn't force every user to hand over a passport or a face-scan* to answer a yes/no age question?" Do not name a vendor.

2. **Microsoft formally made passkeys the default authentication method in Entra ID and set February 1, 2027 as the hard retirement date for native SMS/voice OTP — the single largest named-platform OTP sunset announced to date, covering 300M+ enterprise users (July 13-14, 2026).** Account: / company. Angle: the OTP deprecation that regulators mandated (UAE March 2026, India April 2026, Philippines June 2026, EU late 2026) now has a non-negotiable enforcement date from the world's largest IAM platform; enterprise identity teams can no longer treat passkey rollout as elective. POV hook: "Microsoft just made the choice for every enterprise IT team: passkeys are the default, and SMS OTP has an end date. The interesting design question is what replaces SMS for the high-assurance layer — account recovery, step-up authentication, regulated-transaction approval — where a hardware-passkey tap isn't the answer." Do not name a vendor.

---

## New findings

### Pillar 1: Banking & Payments
(no new discrete in-window publication. PSD3/PSR: agreed texts published 23 Apr 2026; ECON confirmed 18 May it will recommend adoption at second reading without amendment; OJEU publication still anticipated summer/H2 2026, possibly slipping to September — no new OJEU date in window. AMLA Level-2 RTS/ITS package (submitted 10 Jul) remains in Commission adoption. No new EBA / ECB / FCA / PSR / DORA print confirmed 14–16 Jul.)

### Pillar 2: EUDI / eIDAS2
- **Gibraltar-EU Treaty enters provisional application July 15, 2026 — land-border fence removed, EU Entry/Exit System (EES) biometric enrollment activated at Gibraltar's port and airport (July 15, 2026).** At midnight on July 15, the fence marking the Gibraltar–Spain frontier was physically removed for the first time in over a century, ending routine land-border passport checks. The treaty establishes cross-border identity recognition: Spanish citizens may enter Gibraltar using a national ID card; Gibraltar residents use residence cards. At Gibraltar's port and airport, the EU's EES system now applies — travellers' fingerprints and a face scan are collected and stored digitally to track Schengen-area stays. This is the first UK-territory integration with the EU Entry/Exit System and demonstrates the relying-party trust problem Ditto addresses: how does a UK-side biometric/identity system trust an EU-member-state digital credential and vice versa, at the attribute level rather than the document level? Ecosystem/policy datapoint — do not name a vendor.
  - Source: https://www.aljazeera.com/news/2026/7/15/gibraltar-border-controls-lifted-is-it-part-of-schengen-the-uk-or-both
  - Source: https://giboard.gi/guide/crossing-the-gibraltarspain-border
  - Date: 2026-07-15

(No new ARF update, ENISA certification, or member-state wallet launch confirmed 14–16 Jul. Standing anchor unchanged: EUDI wallet availability deadline 24 Dec 2026.)

### Pillar 3: Fraud / Deepfakes
- **US Seventh Circuit Court of Appeals vacates Clearview AI's equity-based biometric privacy class settlement, reopening litigation over the scraping and storage of 3 billion facial images (ruling July 13, coverage July 14, 2026).** The appeals court found a structural defect: the settlement allocated equity shares unevenly across the nationwide class and state sub-classes (Illinois / California / New York / Virginia) at a 10/5/5/5/1 ratio, but no separate class representatives had been appointed for each sub-class, and lead counsel had replaced all eight original named plaintiffs with four new representatives without court approval. The equity deal — a 23% stake in Clearview worth up to $51.75M at a ≥$225M IPO/sale — is vacated; the case returns to district court for a new settlement or trial. For Ditto: the core issue (bulk facial-recognition scraping, no user consent, no data minimisation) is the opposite of Ditto's model, but the litigation signals continued US legal risk for vendors storing biometric templates at scale and establishes that novel equity settlements for biometric privacy classes face heightened structural scrutiny.
  - Source: https://www.biometricupdate.com/202607/court-rejects-deal-reopens-clearview-ai-lawsuit-over-biometric-data-collection
  - Source: https://blogs.duanemorris.com/classactiondefense/2026/07/14/seventh-circuit-undoes-novel-privacy-class-settlement-due-to-lack-of-separate-representatives-for-nationwide-class-and-state-sub-classes/
  - Date: 2026-07-13 (Seventh Circuit ruling) / 2026-07-14 (coverage — in window)

(No new primary-source fraud report or named bank deepfake incident dated 14–16 Jul. Standing prints unchanged: AU10TIX Q1 2026 (3.89% confirmed fraud rate); Shufti Identity Fraud Index 2026 (deepfake fraud ~+495% YoY); Sumsub deepfakes ≈11% of global fraud; iProov +2,665% virtual-camera-injection spike.)

### Pillar 4: ZKPs in practice
(no new EU-bank ZKP pilot, OpenID4VP/VCI deployment, or mDL milestone confirmed 14–16 Jul. EU Special Panel ZKP age-assurance recommendation (07-15) remains the freshest policy signal; today's Ofcom action (P11) is method-agnostic but, combined with the EU privacy constraint, tightens the practical case for ZKP/selective-disclosure age proofs. OID4VP 1.0 and ARF v2.8 remain standing context.)

### Pillar 5: Passwordless / split-key
- **Microsoft Entra ID: passkeys are now the default authentication method, with a hard September 2026 rollout and February 1, 2027 retirement of native SMS/voice OTP for all Entra users (announced July 13-14, 2026).** Starting September 1, 2026, Microsoft will make passkeys the default MFA experience in Entra ID — all users currently relying on SMS or voice OTP will automatically be enabled for passkeys and prompted to register one on their next MFA event. On February 1, 2027, Microsoft will retire SMS/voice as a native Entra capability; users still on SMS/voice by that date must register a passkey before they can sign in. Telecom providers can plug into the Microsoft Security Store (framework published September 18, 2026) as a fallback channel, but Microsoft's own OTP delivery pipeline ends. This applies to all Entra ID tenants globally — encompassing enterprise, government, and education users. For Ditto: this validates the regulatory OTP-sunset mandates (UAE March 2026, India April 2026, Philippines June 2026, EU late 2026) by making the world's largest IAM platform the enforcement mechanism. The angle / company: enterprise identity teams can no longer defer passkey rollout; the question shifts to managing the transition for the authentication surfaces where SMS OTP is currently embedded — account recovery, high-risk transaction step-up, regulated-sector sign-in — where a simple passkey prompt isn't sufficient.
  - Source: https://www.microsoft.com/en-us/security/blog/2026/07/13/microsoft-entra-id-security-updates-passkeys-are-the-default-authentication-method-in-entra-id/
  - Source: https://www.helpnetsecurity.com/2026/07/14/microsoft-entra-passkey-authentication/
  - Source: https://office365itpros.com/2026/07/14/entra-sms-one-time-code/
  - Date: 2026-07-13 (Microsoft Security Blog) / 2026-07-14 (Help Net Security; office365itpros — in window)

### Pillar 6: LATAM
(no new in-window LATAM finding. Mercosur cross-border digital ID mutual recognition (July 14) fully covered in 07-15 delta as override-worthy. CNBV/Superfinanciera/BCB/Drex anchors unchanged. AUSTRAC Tranche 2 now in force as of July 1; enrolment closes July 29.)

### Pillar 7: Identity ecosystem
- **Ofcom's first Age Assurance Report reframes the IDV bar for age: "highly effective" is a tested regulatory standard; behavioural inference does not meet it (July 16, 2026)** — See full writeup under Pillar 8. The IDV-specific significance: Ofcom is drawing a hard line between *highly effective* age-assurance methods (its published guidance list, e.g. photo-ID matching, facial age estimation with defined accuracy thresholds, credit-reference/open-banking checks, digital-ID wallets) and *age-inference* (estimating age from on-platform behaviour), ruling the latter not capable of being highly effective. For an identity vendor, this is a market-shaping signal: platforms currently using behavioural inference now face a compliance-driven push to certified, method-tested age checks — and the winning method must clear both the effectiveness bar *and* the privacy bar (see EU ZKP convergence, Pillar 8).
  - Source: https://www.ofcom.org.uk/online-safety/protecting-children/keep-underage-children-off-your-platforms-ofcom-tells-tech-firms
  - Source: https://deadline.com/2026/07/ofcom-investigating-tiktok-over-child-safety-concerns-1236983773/
  - Date: 2026-07-16

(No new analyst report, major M&A, or keynote in window. SailPoint × Entro Security acquisition completed June 29 — prior cycle scope. Forrester Wave: Workforce Identity Security Platforms Q2 2026 and KuppingerCole IGA Leadership Compass 2026 remain standing context.)

### Pillar 8: Age assurance & privacy attributes
- **Ofcom publishes its first statutory Age Assurance Report and opens a formal TikTok investigation the same day — behavioural age-inference declared not "highly effective," platforms ordered to switch without delay (July 16, 2026).** Ofcom's first statutory report under the Online Safety Act assesses how services used age assurance in the first year of the child-safety duties (in force since July 25, 2025). Headlines: the share of children encountering *highly effective* age checks rose from **25% to 43%** between July 2025 and January 2026; Ofcom has opened **23 investigations** into providers of 88 adult services; **64 of the top-100 porn sites** now run age checks, though "too many still don't." Most critically for identity vendors, Ofcom stated that services "which use age *inference* models to comply with their child-protection duties should switch to other methods listed in our guidance as highly effective **without delay**," and confirmed age inference is "not included in our industry guidance as a method that is capable of being highly effective for this purpose." On the same day, Ofcom opened a **formal s.12 OSA investigation into TikTok** on the basis that "very serious questions" exist about whether its inference methods "may be failing to correctly detect significant numbers of children"; potential penalty **up to £18M or 10% of worldwide revenue**. For Ditto: age assurance is a Ditto pillar (gambling/gaming plus the broadening social-media surface), and this is the clearest *UK* enforcement signal yet that behavioural-guess age assurance is being ruled out. Landing ~48h after the EU Special Panel's ZKP recommendation (07-15) and von der Leyen's age-rules push (07-14), the two-jurisdiction convergence is the POV: the combined UK+EU regulatory direction is *highly effective AND privacy-preserving*, which eliminates both behavioural inference (UK) and biometric age-estimation/document-scanning (EU), and points toward credential-based or ZKP-based age proofs — the selective-disclosure / verifiable-attribute surface Ditto addresses. Ecosystem/policy datapoint — do not name a vendor.
  - Source: https://www.ofcom.org.uk/online-safety/protecting-children/keep-underage-children-off-your-platforms-ofcom-tells-tech-firms
  - Source: https://deadline.com/2026/07/ofcom-investigating-tiktok-over-child-safety-concerns-1236983773/
  - Source: https://www.yahoo.com/news/world/articles/ofcom-launches-investigation-tiktok-child-071446433.html
  - Date: 2026-07-16

(Standing hard anchor **resolved**: the Ofcom statutory age-assurance effectiveness report — carried as a next-cycle anchor since the 07-15 delta — is now published. Remaining: Ofcom Categorisation Register + additional-duties consultation due July 2026; Ofcom-noticed firms' risk-assessment records due July 31.)

---

## Next-cycle anchors (updated)

- **Ofcom TikTok investigation (opened July 16)** — WATCH: first s.12 OSA age-assurance enforcement action against a marquee platform; outcome sets the precedent for whether behavioural age-inference is defensible anywhere. Penalty up to £18M / 10% global revenue.
- **Ofcom-noticed firms' risk-assessment records due (July 31)** — ~15 days.
- **EU AI Act Code of Practice (transparency of AI-generated content) signatory deadline (July 22, 18:00 CEST)** — ~6 days; signatories gain presumption of conformity with Art. 50 deepfake/AI-content-labelling obligations.
- **FSB AI Sound Practices consultation deadline (July 22)** — ~6 days. Final report October 2026.
- **AUSTRAC Tranche 2 enrolment deadline (July 29)** — ~13 days; ~100,000 newly in-scope entities.
- **EU AI Act Article 50 enforcement (August 2)** — ~17 days; deepfake labelling, chatbot disclosure become binding (fines up to €15M / 3% global turnover).
- **Microsoft Entra passkey default rollout (September 1, 2026)** — NEW ANCHOR. SMS/voice OTP users auto-enrolled for passkeys; hard retirement February 1, 2027. Track for: enterprise pushback, high-risk-transaction step-up gaps, and whether Okta/Ping/Google Workspace announce parallel retirement dates.
- **UK DVS Trust Framework 1.0 enforcement (September 1)** — first conformity-assessment-body accreditation.
- **AMLA Level-2 RTS/ITS → Commission adoption** — submitted July 10; typically 3–6 months; AMLR applies July 10, 2027.
- **Age-assurance regulatory convergence (UK + EU)** — WATCH: Ofcom "inference isn't highly effective" (07-16) + EU Special Panel ZKP recommendation (07-15) + von der Leyen age-rules (07-14) point the same way; track for first named platform to adopt wallet-based / ZKP age proof to satisfy both regimes simultaneously.
- **Agentic identity** — WATCH: Entrust Agentic AI Trust Accelerator (07-14); ITU Focus Group Paris Nov 2026; FIDO agentic-auth WG.
- **Mercosur cross-border digital ID ratification** — WATCH: approved July 14 (Asunción); requires national-congress ratification across Argentina, Brazil, Paraguay, Uruguay.
- **PSD3/PSR OJEU publication** — texts published 23 Apr; ECON recommends second-reading adoption (18 May); OJEU anticipated summer/H2 2026.
- **EUDI wallet Dec 24, 2026 deadline** — member states must provide certified wallets; relying-party acceptance in regulated sectors from ~late 2027.

---

## Run summary

- Findings count by pillar: P1 Banking: 0 | P2 EUDI/eIDAS2: **1** (Gibraltar-EU Treaty EES activation, July 15) | P3 Fraud/Deepfakes: **1** (Clearview AI settlement vacated, July 13-14) | P4 ZKP: 0 | P5 Passwordless: **1** (Microsoft Entra passkeys default + SMS OTP retirement Feb 2027, July 13-14) | P6 LATAM: 0 | P7 Identity ecosystem: **1** (Ofcom "highly effective" bar cross-ref, July 16) | P8 Age assurance: **1** (Ofcom first statutory Age Assurance Report + TikTok investigation, July 16) — **Total: 5 in-window findings across 5 pillars (P7/P8 share the Ofcom event); 4 genuinely distinct events.**
- Override-worthy: **2** — (1) Ofcom first statutory Age Assurance Report + TikTok probe (July 16) — completes a one-week UK+EU regulatory convergence on highly-effective, privacy-preserving age assurance; account company//. (2) Microsoft Entra passkeys as default + February 1, 2027 SMS/voice OTP retirement (July 13-14) — largest named-platform OTP sunset to date; account /company.
- Delta path: research/2026-07-16-cycle-delta.md
- Note: Worker URL (ditto-slack-bot.dittobot.workers.dev) blocked by session egress policy (proxy policy denial, 403 on CONNECT); delta written directly to GitHub via MCP and Slack notification sent via MCP. Skill files not accessible this cycle; brand context derived from prior deltas and baseline. Correctly excluded Strata Identity "Maverics for AI Agents" (July 2025, out-of-window).
