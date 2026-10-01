# Cycle Delta — 2026-10-01

Window: 2026-09-29 → 2026-10-01 (last 48 hours)

## Provenance and integrity notes

- The worker API was reachable. The brand brief, competitors list and pillar guides were fetched from the worker. Deduplication was checked by full-text search across all 107 files under `research/`, including the 2026-05-06 baseline and every delta through 2026-09-30.
- The effective new surface is **2026-09-30 and 2026-10-01**. Items dated 09-29 were checked against the 09-29 and 09-30 deltas.
- **Correction to the corpus:** the 2026-07-10 delta said the AMLA Art. 28(1) CDD RTS was submitted to the Commission on 07-10 as part of a "23 RTS/ITS package". In fact the AMLA final report on the CDD RTS is dated **2026-09-30** (Frankfurt). The same is true of the group-wide (Art. 16(4)/17(3)) and linked-transactions (Art. 19(9)) final reports. The July claim was wrong for at least these three instruments. Later deltas that say "submitted 2026-07-10" should be read in that light.
- **Already logged, not re-reported:**
  - Modulate $25M (09-30 delta; ID Tech re-ran it 09-30)
  - IDEMIA Agentic Commerce (09-30 delta)
  - Aylo enforcement data (09-30 delta)
  - Pindrop Deepfake Readiness Index (09-29 delta)
  - Fideuram (09-30 gap-fill; the FinTelegram / IBTimes follow-ups add no new facts)
- **Checked and rejected (out of window):**
  - Indonesia pressing Meta on under-16 deactivation under PP Tunas: the ANTARA primary is dated **2026-09-26**.
  - Visa Payment Passkey live at five Indian public-sector banks: **2026-09-18** (GFF).
  - Rokarolla Android banker: June/August 2026.
  - DHS S&T identity-verification competition: **2026-09-21**.
  - CNBV facial-biometrics rule: published 2026-07-01, with compliance due around early November. A watch item, not a finding.
- **Noted, not counted:**
  - **Ofcom:** provisional notices of contravention to Web Prime Inc. (five sites) and Porntrex for failing on highly-effective age assurance and on information requests. MLex reported 09-30, alongside First Time Videos paying its £80k fine (the fine itself dates from June). This is incremental enforcement against small operators. Useful only as a counter-data-point to Aylo's "enforcement has failed" claim (09-30 delta).
  - **Prove** extended SIM-based silent authentication to Wi-Fi and mobile web (09-30). This is an OTP-replacement move; Synchrony is quoted as interested, not as deployed. The mechanism is undisclosed and the evidence is thin.
  - **Facephi:** UAE Azure in-country deployment (09-30). Data residency, not identity news.
  - **Moca Network** mainnet (09-30). Off-ICP.
  - **Trident** $15M (09-30). Off-ICP.
  - **Noblis** continuous-biometric patent (09-30). Off-ICP.
- **PSD3/PSR OJEU:** still no Official Journal notice. Next Monday check is 2026-10-05.

## Override-worthy this cycle

1. **AMLA's final CDD rulebook makes eIDAS/EUDI identification the default for EU KYC, and turns document-plus-selfie remote onboarding into a fallback that firms must justify case by case.** AMLA's final draft RTS under AMLR Art. 28(1), dated 2026-09-30, keeps the "eIDAS-first" approach that industry lobbied against in consultation. Account: / company. Angle: "From July 2027 your remote onboarding stack needs an alibi. Every document-and-selfie check must explain why the customer couldn't use a wallet."

## New findings

### Pillar 1: Banking & Payments

(no new material in window. The AMLA CDD RTS is logged under Pillar 4 and applies to banks as obliged entities.)

### Pillar 2: Identity orchestration

(no new material. The Forrester CIAM Wave kick-off is still not seen.)

### Pillar 3: EUDI / eIDAS2

- **Two more member states put their EUDI wallet legal frameworks in place this week.**
  - **Finland:** the national EUDI wallet legislation **entered into force 2026-10-01**; the Ministry of Finance release is dated 09-30. Roles under the law:
    - DVV must provide at least one public wallet, issuing the initial identification credential against a valid passport or ID card.
    - Private companies may offer wallets if they meet the provider requirements.
    - Traficom supervises wallet providers and keeps the register.
    - From **2027-01-01**, providers must verify the validity of the identity document used for initial issuance.
    - The wallets themselves are expected **during 2027**, after the 2026-12-24 availability deadline.
  - **Bulgaria:** the Council of Ministers approved the steps to build and provide an EUDI wallet on **2026-09-29**. The wallet will cover e-services, data/certificate submission and qualified e-signatures, and will integrate with national eID and the horizontal e-authentication system. The Minister of Innovation and Digital Transformation is named supervisory authority and single point of contact. No provider or timeline is named.

  **Why it matters:** the corpus tracker has listed Bulgaria as "not started" since August. That status should move to "legal basis approved; no date". Finland is a clean example of the pattern the corpus keeps seeing: the law is on time, the wallet is late. With 84 days to the deadline, the gap between *legal readiness* and *wallet in citizens' hands* is now the story. Read it together with the AMLA CDD RTS below: relying parties will be legally pointed at wallets before most citizens hold one.
  - Source (primary): https://vm.fi/en/-/legislation-on-european-digital-identity-wallets-enters-into-force-in-october
  - Source (primary): https://www.bta.bg/en/news/bulgaria/1214098-government-approves-steps-to-introduce-european-digital-identity-wallet
  - Source: https://idtechwire.com/finlands-digital-wallet-legislation-takes-effect-ahead-of-2027-launch/
  - Source: https://idtechwire.com/bulgaria-assigns-oversight-roles-for-european-digital-identity-wallet/
  - Date: 2026-09-29 (Bulgaria); 2026-09-30 / 2026-10-01 (Finland release / in force)
  - **Drafting caution:** do not say Finland "launched" a wallet. The law is in force; the wallet comes in 2027. The 2027-01-01 document-validity rule is from ID Tech's summary and is not in the vm.fi English release; verify against the Finnish text before quoting.

### Pillar 4: KYC / AML compliance

- **AMLA published its final draft RTS on customer due diligence (AMLR Art. 28(1)), dated 2026-09-30, and kept the eIDAS-first model.** This is the instrument the corpus has flagged since August as "the one that matters".
  - **The default.** Identity verification is by ID document/passport, or by electronic identification means at eIDAS **"substantial" or "high"** assurance, whether notified or not. Recital 11 says this "includes European Digital Identity Wallets", plus relevant qualified trust services.
  - **The fallback (Art. 7, "Alternative verification measures in non-face-to-face circumstances").** Other remote tools may be used only where the customer cannot reasonably present documents in person **and** has no access to qualifying eID. Those tools must ensure the person presenting the document is its holder. They must also protect the integrity and confidentiality of the communication and capture images, video, sound and data in identifiable quality. The process must stop on "technical shortcomings or unexpected connection interruptions" or on any doubt about the integrity of the process. Records must be time-stamped and allow ex post verification.
  - **Justification duty.** Under Art. 7(3), firms must "justify why the customer could not be verified" by the default methods and demonstrate compliance to their supervisor.
  - **Consultation feedback.** AMLA records that respondents feared an "eIDAS-first" approach. Its response is that the Art. 22(6) methods "are still the default option", and that existing remote onboarding tools may continue if they meet the Art. 7 minimums, "necessary especially in the face of emerging technological threats". Firms may show compliance through recognised international or European technical standards. eID may also be used face to face.
  - **Timing.** The RTS goes to the Commission for adoption and will **apply six months after entry into force** (recital 27). AMLR itself applies 2027-07-10.
  - **The rest of the package.** AMLA's regulatory-instruments page (last updated 09-30) also carries the final reports on group-wide requirements (Art. 16(4)/17(3)) and on linked-transaction criteria (Art. 19(9)). MLex (10-01) reports seven documents in total.

  **Why it matters for an identity vendor:** this is the single most consequential identity-verification text for EU regulated onboarding. It splits the market in two:
  - **Wallet/eID acceptance**, the default path, which needs orchestration of EUDI wallets plus national eIDs at substantial/high.
  - **Remote document-and-biometric IDV**, now a *justified exception* with explicit anti-injection and integrity expectations.

  Firms that built remote KYC around document-plus-selfie will need wallet/eID acceptance in front of it, and an audit trail explaining every fallback. This is the strongest regulatory hook for Ditto's EUDI orchestration plus Verify positioning this quarter.
  - Source (primary): https://www.amla.europa.eu/document/download/e15ab2e5-4074-4de8-bb9d-613dd8b7fdd1_en?filename=Final%20Report%20-%20draft%20RTS%2028%281%29%20AMLR.pdf
  - Source (primary, index): https://www.amla.europa.eu/policy/regulatory-instruments_en
  - Source: https://www.mlex.com/mlex/financial-crime/articles/2532501
  - Date: 2026-09-30 (final report); 2026-10-01 (reported)
  - **Drafting cautions:**
    - This is a *draft* RTS until the Commission adopts it. Say "AMLA's final draft" or "AMLA has sent the Commission".
    - Do not claim remote video/selfie onboarding is "banned". It is permitted as a justified fallback.
    - "Six months after entry into force" is the RTS's own application rule. Do not state a calendar date until the OJ publication.
    - Quotes above are verbatim from the PDF; keep them exact.
    - No AMLA press release was indexed at run time (the AMLA news page returned empty).

### Pillar 5: Customer onboarding

(no new material. See Pillar 4: the AMLA CDD RTS is the onboarding story of the cycle. The cross-reference for onboarding owners is that a fallback-justification step is coming into every EU remote funnel.)

### Pillar 6: Identity verification (IDV)

(no separate new material. See Pillar 4: AMLA RTS Art. 7 sets the EU minimum bar for remote IDV tools: holder-binding, channel integrity, stop-on-anomaly, ex post verifiable records, and compliance through recognised standards. It is not double-counted.)

### Pillar 7: Fraud / Deepfakes

(no new material in window beyond the BioCatch report, logged under Pillar 8. Fideuram follow-ups added no new facts.)

### Pillar 8: Mobile trust & app security

- **BioCatch's 2026 Global Scams Report: attempted banking scams rose 35% year on year, and 90% of scam attempts now happen on mobile devices** (up from 85%). The report was released **2026-09-30**. It covers data from **370+ financial institutions serving 760M+ users in 21 countries** over 12 months. Other figures:
  - Growth slowed from 65% the prior year.
  - Employment scams were up **258%** and romance-scam attempts **23%**.
  - Purchase scams make up a third of attempts.
  - Investment scams average **$6,600** per case, about 5x the average.

  The report points to on-device signals banks can use: "active calls during transactions, remote access applications installed on devices" and new-beneficiary behaviour. Quote: "artificial intelligence has lowered the barrier to entry for aspiring scammers." (Thomas Peacock, Director of Global Fraud Intelligence). **Why it matters:** this is a large-sample confirmation that the authorised-push-payment fight is happening on the phone, during a live call, inside the genuine banking app. Login-time authentication can't catch that alone. It supports the in-session device-integrity and coercion-signal argument (Ditto Protect) over more checks at the door.
  - Source (primary): https://www.biocatch.com/press-release/global-banking-scams-increase-by-35
  - Source: https://www.amlintelligence.com/2026/09/latest-90-of-banking-scam-attempts-now-originate-on-mobile-devices-report/
  - Date: 2026-09-30
  - **Drafting cautions:**
    - BioCatch is being acquired by Visa (08-05 delta). Cite it as "BioCatch (being acquired by Visa)" and do not frame it as an independent study.
    - "Scam attempts" are detections across BioCatch customers, not losses.
    - The 155% LATAM figure some outlets carry is from an April 2026 BioCatch release, not this report. Do not use it here.

### Pillar 9: Passwordless / split-key

(no new material that meets the bar. Prove's Wi-Fi silent authentication is noted, not counted; see the provenance notes.)

### Pillar 10: ZKPs in practice

- **A Commission study ranks decentralised identity, wallets, verifiable credentials and zero-knowledge technology as R&I priorities for the next Horizon Europe. It also shows the area got under 1% of the digital research money examined for 2021–2025.** DG CNECT's *Study on the EU's Strategic Digital Technologies for the Next EU Research and Innovation Programme* was published **2026-09-29** and reported by Biometric Update on 09-30.
  - The cybersecurity roadmap calls "decentralized identity and digital wallets" "mature, high-impact trends to prioritize".
  - The blockchain roadmap lists "self-sovereign identity, verifiable credentials and zero-knowledge technology" among priorities.
  - Funding to date: "blockchain, distributed ledgers and digital identity received about €23 million" in 2021–2025, the smallest allocation of the areas examined.
  - The next framework programme (2028–2034) is proposed at €175bn.

  **Why it matters:** this is a usable contrast for a POV post. The EU is mandating wallets for every citizen by end-2026 and pointing AML onboarding at them (Pillar 4), while its own study says identity got the smallest share of research funding. Privacy-preserving identity has been treated as a deployment problem, not a research one. The study now says that should change.
  - Source (primary): https://digital-strategy.ec.europa.eu/en/library/study-eus-strategic-digital-technologies-next-eu-research-innovation-programme
  - Source: https://www.biometricupdate.com/202609/eu-study-puts-digital-identity-on-research-roadmap-for-next-horizon-europe
  - Date: 2026-09-29 (study); 2026-09-30 (reported)
  - **Drafting caution:** this is a contractor study for DG CNECT, not Commission policy; say "a Commission-commissioned study". The €23M figure and the quotes come via Biometric Update; verify them against the study PDF before quoting. The €175bn is the *proposed* budget.

### Pillar 11: Age assurance & privacy attributes

(no new material that meets the bar. The Ofcom provisional notices to Web Prime and Porntrex are noted in the provenance notes. Indonesia/Meta is dated 09-26, out of window.)

## Open watch items

- **AMLA CDD RTS (NEW):**
  - watch for Commission adoption and OJ publication (the application date is +6 months)
  - pull the Art. 19(9) linked-transactions and Art. 16/17 group-wide final reports for any identity-relevant clauses
  - watch for an AMLA press release and for national supervisors' reaction to the "justify every fallback" duty
- **2026-10-01 (today):**
  - FinCEN Banque Misr UAE §311 comment period closes.
  - Brazil Resolution 561 eFX cutover.
- **2026-10-26:** BCB MED 2.0 inter-institution notification step.
- **Early November 2026:** CNBV facial-biometrics compliance deadline (90 business days from 2026-07-01). angle.
- **2026-10-29/30:** EUDI Launchpad 2026, Brussels (invitation-only). Watch for member-state readiness statements.
- **October 2026:**
  - FATF plenary (first under the UK Presidency).
  - PSR APP-reimbursement policy review.
- **UK under-16 restrictions:** Ofcom rapid age-verification study; regulations to be laid by year-end.
- **IDEMIA Agentic Commerce:** first named scheme or issuer.
- **Fideuram:** Bank of Italy / ECB comment; Milan prosecutor disclosures.
- **Forrester CIAM Wave:** kick-off still not seen.
- **DHS biometric capture GWAC ($440.7M):** awards expected in October.
- **2026-10-31:** ECB SSM-2026-0301 action-plan deadline.
- **2026-11-18:** EUDI ARF Iteration 6 closes.
- **2026-12-24:** EUDI wallet-availability deadline (84 days). Finland: law in force, wallet 2027. Bulgaria: legal basis approved, no date.
- **PSD3/PSR OJEU:** still unpublished. Next check is Monday 2026-10-05.
