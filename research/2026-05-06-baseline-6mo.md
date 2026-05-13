# Ditto Research Baseline — 2026-05-06 (covers 2025-11-06 → 2026-05-06)

## Summary

The last six months have been the most regulation-heavy stretch in European identity and payments since PSD2 first landed. Three things define the period: (1) the **PSD3/PSR final compromise texts** dropped on 23 April 2026, locking in Verification of Payee for all credit transfers and a clearer fraud-liability cascade; (2) **DORA crossed from documentation to active enforcement**, with the first compulsion payments, the second Register of Information cycle, and the launch of the critical-third-party oversight framework; and (3) **AMLA formally took over from the EBA on 1 January 2026** and immediately opened the CDD RTS consultations that will shape KYC across the bloc through 2027.

In parallel, the **EUDI Wallet 6 December 2026 deadline** has shifted from "deadline" to "credibility test." ENISA opened the certification-scheme consultation on 2 April 2026 (closing 30 April), the ARF v2.0 went live, OpenID Foundation set February 2026 as the start of OpenID4VP/VCI self-certification, and two new Large Scale Pilots (APTITUDE, WE BUILD) launched. Most member states will hit the deadline in name only — France (already live), Germany (sandbox open, state wallet 2 January 2027), and Italy lead; the Commission itself is publicly hedging on universal readiness.

Fraud is no longer a quiet drumbeat. The **EBA-ECB joint payment-fraud report (15 December 2025)** put 2024 EEA fraud losses at €4.2bn (+17% YoY); **iProov logged a 1,151% surge in iOS injection attacks H2 2025**; **Sumsub's annual report** flagged sophisticated multi-step fraud +180% YoY and named 2026 the year of agentic-AI scams; and the **Commonwealth Bank of Australia $1bn AI-document-forgery probe (27 February 2026)** is the largest publicly disclosed AI-fraud incident at a Tier-1 bank to date. The freshest material for posting sits in the PSD3 text, AMLA CDD consultation, ENISA wallet certification consultation, the iProov/Sumsub/Veriff Q1 2026 reports, and the CBA case as a teardown anchor.

## Override-worthy this week

1. **PSD3/PSR final compromise texts published 23 April 2026 (ST-8221-2026-INIT, ST-8222-2026-INIT)** — Council moved both files to COREPER for second-reading agreement; OJEU publication expected end Q2 2026. Angle: "The 24-month VoP clock starts the day this hits the OJ — most banks aren't ready for an under-one-second name-IBAN match across non-instant rails."
2. **ENISA EUDI Wallet certification draft scheme v0.4.614 — public consultation open until 30 April 2026** — first concrete cybersecurity baseline that wallet vendors and relying parties will be measured against. Angle: "Certification, not regulation, is the real chokepoint between today and a December 2026 wallet."
3. **CBA $1bn AI-document mortgage-fraud probe (announced 27 Feb 2026)** — first Tier-1 bank to publicly disclose AI-forged income/tax docs at scale, surfaced via internal whistleblower. Angle: "Document deepfakes have moved from onboarding to underwriting. Liveness doesn't help here — provenance does."
4. **AMLA CDD RTS consultation closes 8 May 2026** — first time a single EU rulebook will define standard/simplified/enhanced CDD; final draft due to Commission 10 July 2026. Angle: "AMLA's CDD RTS is where 27 national interpretations of KYC die. Identity vendors who haven't engaged are about to be told what 'sufficient' means."
5. **iProov 2026 Threat Intelligence Report (8 April 2026)** — iOS injection attacks +741% YoY, +1,151% in H2 2025 alone; deepfakes spreading from IDV into video-call workflows. Angle: "Injection attacks just became iOS-native. Camera-based liveness is no longer the perimeter — the OS is."

---

## Pillar 1: Banking & Payments

### PSD3 / PSR

- **PSD3/PSR final compromise texts published by Council** — On 23 April 2026 the Council Secretariat circulated final compromise texts (ST-8221-2026-INIT for PSR, ST-8222-2026-INIT for PSD3) to COREPER with a recommendation to approve. Publication in the OJEU is expected by end Q2 2026, starting the 18-month transposition clock for PSD3 and the staged application of PSR.
  - Source: https://www.regulationtomorrow.com/2026/04/council-issues-i-item-note-on-psd3/
  - Source: https://www.arthurcox.com/insights/psd3-and-psr-final-compromise-texts-published/
  - Date: 2026-04-23
  - Pillar tags: banking, payments, regulation
  - Suggested angle: "Two regulation files just left Brussels with the ink still wet. The bigger story isn't what changed — it's what just became unavoidable."

- **VoP extended to all credit transfers, not just instant** — PSR mandates pre-execution payee-name/IBAN verification on every credit transfer in any currency, in-seconds response, with mismatch displayed to the payer. Application 24 months after entry into force (system changes); full liability tail at 27 months.
  - Source: https://www.nortonrosefulbright.com/en/knowledge/publications/cedd39c6/psd3-and-psr-from-provisional-agreement-to-2026-readiness
  - Date: 2026-04-23
  - Pillar tags: banking, payments, fraud
  - Suggested angle: "VoP isn't an instant-payments add-on anymore. It's the rail."

- **PSD3 mandates dedicated APIs, kills the fallback interface** — PSD3 removes PSD2's screen-scraping fallback option; banks must hit performance benchmarks on dedicated APIs and explicitly cannot add SCA friction to TPP flows. "Premium" APIs (e.g. for VRPs) are explicitly contemplated.
  - Source: https://financialregulation.linklaters.com/post/102lw90/psd3-breakthrough-eu-legislators-agree-payments-regulation-reforms
  - Date: 2026-04-23
  - Pillar tags: banking, open banking, regulation

- **Instant Payments Regulation VoP went live across SEPA on 9 October 2025** — All SEPA PSPs were required to offer Verification of Payee with the four-state traffic-light response (match / close match / no match / other). PSD3 absorbs and extends this baseline.
  - Source: https://gurupay.eu/verification-of-payee-vop-what-changes-from-9-october-2025/
  - Date: 2025-10-09
  - Pillar tags: banking, payments, fraud

### DORA enforcement

- **DORA grace period over: first compulsion payments issued in 2026** — National competent authorities are now cross-checking Register of Information data automatically, conducting on-site reviews, and issuing the first compulsion payments to non-compliant entities. The DORA oversight framework for critical third-party providers launched 1 January 2026.
  - Source: https://www.regulation-dora.eu/blog/dora-2026-enforcement-what-changes
  - Date: 2026-01-01
  - Pillar tags: banking, regulation, third-party-risk

- **ESAs designate first 19 Critical ICT Third-Party Providers under DORA (Nov 2025)** — Designations include AWS, Google Cloud, Microsoft, Oracle, SAP, Deutsche Telekom. Penalties for CTPPs reach €5m plus 1% of average daily global turnover per day of non-compliance for up to six months.
  - Source: https://www.regulation-dora.eu/blog/dora-register-of-information-2026-guide
  - Date: 2025-11-30
  - Pillar tags: banking, third-party-risk

- **2026 Register of Information cycle: reference date 31 Dec 2025, ESA consolidation deadline 31 March 2026** — National deadlines stagger Feb–March (e.g. Luxembourg 1 March; Austria 16 Feb–13 Mar; Netherlands 20 Mar). Only ~50% of regulated entities expected full compliance by end-2025, with ~38% pushing target into 2026.
  - Source: https://www.regulation-dora.eu/blog/dora-register-of-information-2026-guide
  - Source: https://www.cssf.lu/en/2026/02/dora-submission-timeframe-for-register-of-information-edesk-portal-open-as-of-11-february-2026/
  - Date: 2026-03-31
  - Pillar tags: banking, regulation, third-party-risk

- **ECB Supervisory Priorities 2026–2028 published Nov 2025** — Two on-site inspection campaigns on cybersecurity and third-party risk; a deep-dive on bank preparedness for major cloud-provider outage; thematic reviews on maintaining critical functions during a total ICT outage; threat-led penetration testing.
  - Source: https://www.bankingsupervision.europa.eu/framework/priorities/html/ssm.supervisory_priorities202511.en.html
  - Date: 2025-11
  - Pillar tags: banking, regulation

### AMLA / AMLR

- **EBA → AMLA AML/CFT mandate handover completed 1 January 2026** — Transfers EBA's standalone AML/CFT mandate (started 2020), the EuReCa database, supervisory insights, and risk assessments. Existing EBA AML guidelines remain in force until AMLA replaces them.
  - Source: https://www.eba.europa.eu/publications-and-media/press-releases/eba-and-amla-complete-handover-amlcft-mandates
  - Source: https://www.amla.europa.eu/eba-and-amla-complete-handover-amlcft-mandates_en
  - Date: 2026-01-01
  - Pillar tags: banking, regulation, AML

- **AMLA opened three RTS consultations on 9 February 2026** — Drafts cover (i) standard/simplified/enhanced CDD under AMLR Art. 28(1); (ii) criteria for identifying business relationships and linked transactions; (iii) supervisory methodology under AMLD6 Art. 53(10). Consultation closes 8 May 2026; final drafts to Commission by 10 July 2026.
  - Source: https://www.amla.europa.eu/policy/public-consultations/consultation-draft-rts-customer-due-diligence_en
  - Source: https://www.algoodbody.com/insights-publications/amla-consults-on-draft-rts-on-cdd-measures-and-triggers-and-confirms-its-priorities-for-2026-to-2028
  - Date: 2026-02-09
  - Pillar tags: banking, regulation, AML, KYC

- **AMLA will directly supervise 40 of the most complex EU financial institutions** — Final report on RTS for the risk-assessment selection methodology already published; first round of selected entities expected 2027 with AMLR effective July 2027.
  - Source: https://www.amla.europa.eu/amla-takes-major-step-toward-harmonised-eu-supervision_en
  - Date: 2026
  - Pillar tags: banking, regulation, AML

### UK FCA / PSR

- **UK APP-fraud reimbursement first-year data: £173m paid Oct 2024 – Sep 2025** — Of 269,000 reported APP fraud claims, 188,000 were eligible; 88% received reimbursement under SD20. Joint FCA/PSR post-implementation review expected Q2/Q3 2026.
  - Source: https://www.lexology.com/library/detail.aspx?g=86a02274-9ff0-4c50-b3c6-5095ebd79db7
  - Source: https://bratby.law/app-fraud-reimbursement-cross-sector-liability/
  - Date: 2026-02
  - Pillar tags: banking, fraud, UK

- **FCA Year 2 Consumer Duty observations published April 2026** — Boards now formally signing off, but FCA flagged weak distribution-chain monitoring, insufficient narrative around MI dashboards, and inadequate documentation of board challenge.
  - Source: https://www.fca.org.uk/news/blogs/year-2-consumer-duty-board-reports-progress-and-what-comes-next
  - Source: https://www.regulationtomorrow.com/2026/04/fca-publishes-observations-in-relation-to-consumer-duty-board-reports/
  - Date: 2026-04
  - Pillar tags: banking, UK, regulation

- **UK money-mule account closures up 23% YoY: 226,957 closed Aug 2024 – Aug 2025** — Across 37 of the largest UK banks and PSPs. Reported by FCA August 2025; correlates with mule-recruitment surge on Instagram and TikTok.
  - Source: https://www.skopenow.com/news/money-mules-how-organized-crime-groups-recruit-via-social-media-for-money-laundering
  - Date: 2025-08
  - Pillar tags: banking, fraud, UK, AML

### Joint EU fraud baseline

- **EBA-ECB joint payment-fraud report published 15 December 2025** — EEA payment fraud reached €4.2bn in 2024, +17% YoY. Driven by credit-transfer fraud (€2.5bn, +24%) and card payments (€1.3bn, +4%). SCA still effective on remote card and credit-transfer fraud, but "manipulation of payers" (i.e. social-engineering) is the new growth vector.
  - Source: https://www.eba.europa.eu/publications-and-media/press-releases/joint-eba-ecb-report-payment-fraud-strong-authentication-remains-effective-fraudsters-are-adapting
  - Source: https://www.ecb.europa.eu/press/pr/date/2025/html/ecb.pr251215~e133d9d683.en.html
  - Date: 2025-12-15
  - Pillar tags: banking, fraud, payments
  - Suggested angle: "SCA worked. The fraud just moved upstream of it."

### Money-mule networks

- **Black Axe network used Irish teens (17–22) to launder €84m** — Pattern of recruiting students through Instagram and WhatsApp "easy-money" job posts; Netcraft and Skopenow analyses found ~24% of "quick-money" tagged Instagram posts show signs of mule recruitment.
  - Source: https://www.skopenow.com/news/money-mules-how-organized-crime-groups-recruit-via-social-media-for-money-laundering
  - Source: https://securitybrief.co.uk/story/instagram-posts-fuel-surge-in-money-mule-recruitment-schemes
  - Date: 2025-2026
  - Pillar tags: banking, fraud, AML, mule

---

## Pillar 2: EUDI / eIDAS2

- **6 December 2026 wallet deadline confirmed; Commission publicly doubting universal readiness** — Each Member State must offer at least one EUDI Wallet to its citizens by that date. Commission and ENISA both signalling that some MSes will launch with limited functionality or miss outright.
  - Source: https://www.biometricupdate.com/202604/eu-commission-doubtful-all-member-states-will-be-able-launch-eudi-wallets-this-year
  - Source: https://www.biometricupdate.com/202512/will-the-eudi-wallet-be-ready-in-2026-experts-say-probably-not
  - Date: 2026-04
  - Pillar tags: EUDI, regulation

- **ENISA opens public consultation on EUDIW Cybersecurity Certification draft scheme v0.4.614** — Published 2 April 2026, webinar 8 April, feedback closes 30 April 2026. ENISA also signed a €1.6m two-year contribution agreement with the Commission in February 2026 to support national certification rollouts.
  - Source: https://www.enisa.europa.eu/news/enisa-advances-the-certification-of-eu-digital-wallets
  - Source: https://certification.enisa.europa.eu/publications/draft-candidate-eudiw-scheme-v04614-public-review_en
  - Date: 2026-04-02
  - Pillar tags: EUDI, certification, regulation
  - Suggested angle: "The wallet deadline isn't December 2026. It's whenever ENISA's scheme says you've got an actual certified product."

- **ARF v2.0 published on the EU Digital Building Blocks repo** — Sets common architecture, protocols, formats for issuer/wallet/relying-party exchanges. Material revisions vs 1.x in response to LSP feedback.
  - Source: https://ec.europa.eu/digital-building-blocks/sites/spaces/EUDIGITALIDENTITYWALLET/pages/900014854/Version+2.0+of+the+Architecture+and+Reference+Framework+now+available
  - Source: https://github.com/eu-digital-identity-wallet/eudi-doc-architecture-and-reference-framework
  - Date: 2025–2026
  - Pillar tags: EUDI, standards

- **Two new Large Scale Pilots launched: APTITUDE and WE BUILD (Sep 2025)** — APTITUDE (117 partners, 11 MSes, France-coordinated) covers travel, mobile vehicle registration, interoperability. WE BUILD (~200 partners, 13 EU business registers) covers B2B, B2G and B2C payments and identity.
  - Source: https://www.biometricupdate.com/202509/new-eu-large-scale-pilots-launch-to-develop-the-digital-identity-wallet-ecosystem
  - Source: https://aptitude.digital-identity-wallet.eu/
  - Date: 2025-09
  - Pillar tags: EUDI, pilot

- **First-wave LSPs (POTENTIAL, NOBID, EWC, DC4EU) wrap with €46m EU funding, 550+ orgs, 27 countries, 11 use cases** — Validated functionality for governmental services, banking, telecoms, mDL, e-signature, health, payments (NOBID), travel credentials (EWC), and education/social security (DC4EU).
  - Source: https://digital-strategy.ec.europa.eu/en/policies/eudi-wallet-implementation
  - Source: https://media.meeco.me/public-assets/reports/Meeco_Report_EUDI_Large_Scale_Pilots.pdf
  - Date: 2025
  - Pillar tags: EUDI, pilot

- **Country readiness snapshot Feb 2026** — France (France Identité in production with first relying-party tests), Italy (building on SPID), Germany (sandbox open, state wallet 2 January 2027 for citizens, market opens to private wallets 2028), Netherlands (delays/limited functionality at launch), Bulgaria (no serious work yet).
  - Source: https://www.eideasy.com/blog/eu-digital-identity-wallets-february-2026-status
  - Source: https://www.namirial.com/en/blog/stories/status-check-eudi-wallet/
  - Date: 2026-02
  - Pillar tags: EUDI, country-status

- **Germany launched EUDI sandbox January 2026; state wallet to launch 2 January 2027** — Initial focus on PID; EAA support including driver's licence expected Q1 2026; private market wallets to open 2028.
  - Source: https://www.lissi.id/blog/germanys-eudi-wallet-sandbox-is-coming-your-guide-to-getting-ready
  - Date: 2026-01
  - Pillar tags: EUDI, Germany

- **Relying-party deadline confirmed: regulated sectors must accept all recognised EUDI Wallets from December 2027** — Banks, PSPs, electronic money institutions explicitly named. Tier-1 banks should be testing now; Tier-2 should be building.
  - Source: https://www.eideasy.com/blog/eu-digital-identity-wallet-acceptance-2027
  - Source: https://www.stibbe.com/publications-and-insights/eidas-20-key-implications-for-financial-institutions-in-the-dutch-market
  - Date: 2026
  - Pillar tags: EUDI, banking

- **Baker McKenzie (3 March 2026): EUDI Wallet positioned as harmonised age-gating instrument** — Will sit alongside DSA, AVMSD, GDPR — first cross-EU consistent way to prove "over 18" with selective disclosure.
  - Source: https://www.bakermckenzie.com/en/insight/publications/2026/03/european-union-eudi-wallet-harmonizes-identification-and-age-gating
  - Date: 2026-03-03
  - Pillar tags: EUDI, age-assurance, privacy

---

## Pillar 3: Fraud, Deepfakes, Synthetic ID

- **iProov 2026 Threat Intelligence Report (8 April 2026): iOS injection attacks +741% YoY** — H2 2025 alone +1,151% vs H2 2024. Industrialised attack kits now lower the bar from state-sponsored to repeatable playbooks. Image-to-video tools (Kling AI, Nano Banana) collapse cost of synthetic-identity creation.
  - Source: https://www.iproov.com/reports/threat-intelligence-report-2026
  - Source: https://www.businesswire.com/news/home/20260408812610/en/iProov-Issues-Annual-Threat-Intelligence-Report
  - Date: 2026-04-08
  - Pillar tags: fraud, deepfake, biometrics
  - Suggested angle: "Mobile used to be the safe channel. iProov just torched that assumption."

- **Sumsub 2025-2026 Identity Fraud Report: sophisticated multi-step fraud +180% YoY; deepfakes = 11% of all fraud** — Multi-step attacks rose from 10% (2024) to 28% (2025); UK deepfake attempts +94%; Maldives +2,100%, Malaysia +408%, Thailand +199%. Sumsub's framing: agentic-AI scams are 2026's main threat.
  - Source: https://sumsub.com/fraud-report-2025/
  - Source: https://sumsub.com/newsroom/sumsubs-annual-report-fraud-shifts-to-complex-multi-step-schemes-in-2025-agentic-ai-scams-poised-to-surge-in-2026/
  - Date: 2025-12
  - Pillar tags: fraud, deepfake

- **Veriff Identity Fraud Report 2026: adversary-in-the-middle attacks +46% YoY** — Many real-time deepfakes; e-commerce and financial services the most affected verticals. Global fraud attempts +21% YoY; deepfake attacks now drive 1 in every 20 IDV failures.
  - Source: https://www.veriff.com/pr-news/veriff-identity-fraud-report-2026
  - Date: 2026
  - Pillar tags: fraud, deepfake

- **Entrust/Onfido report: deepfake attempts every 5 minutes; digital document forgeries +244% YoY** — Digital document forgeries now 57% of all document fraud cases. Digitally presented media is 300% more likely to be AI-generated than the prior year.
  - Source: https://www.entrust.com/company/newsroom/deepfake-attacks-strike-every-five-minutes-amid-244-surge-in-digital-document-forgeries
  - Date: 2024-11 (still the canonical citation; Entrust has not yet released its 2026 update)
  - Pillar tags: fraud, deepfake, document-fraud

- **Commonwealth Bank of Australia: ~$1bn AI-document mortgage-fraud probe (27 Feb 2026)** — Whistleblower-flagged; lender and broker in private banking accused of forging income statements and tax returns using AI; involved shell companies, draft tax returns through accountants, and overseas-sourced deposits. First Tier-1 bank publicly disclosing AI-forged docs at scale in underwriting.
  - Source: https://ia.acs.org.au/article/2026/ai-heist--cba-calls-police-over--1b-loan-fraud.html
  - Source: https://www.unsw.edu.au/newsroom/news/2026/03/commonwealth-bank-one-billion-dollars-suspected-loan-fraud-change-AI
  - Date: 2026-02-27
  - Pillar tags: fraud, deepfake, document-fraud, banking
  - Suggested angle: "Onboarding fraud got the headlines for three years. CBA shows the deeper hole: AI-forged docs now flow through the underwriting tunnel where nobody is looking."

- **Swiss businessman defrauded of "several million CHF" via voice-cloned business partner (Jan 2026)** — Canton of Schwyz; transfer to Asia. Adds to the Arup ($25.6m, 2024) reference case.
  - Source: https://www.biometricupdate.com/202601/deepfake-voice-fraud-dupes-swiss-businessman-into-transferring-millions
  - Date: 2026-01
  - Pillar tags: fraud, deepfake, voice-clone, BEC

- **AI-powered BEC = $2.77bn losses, 21,442 incidents in 2024 (FBI IC3)** — Deepfake fraud drained $1.1bn from US corporate accounts in 2025, ~3x the $360m of 2024. 41% of orgs (Ponemon) have experienced deepfake attacks targeting executives; 37% of cyber leaders (Gartner Sep 2025) encountered deepfake incidents in video calls.
  - Source: https://www.iproov.com/reports/threat-intelligence-report-2026
  - Source: https://cybelangel.com/blog/deepfake-ceo-fraud-how-voice-cloning-targets-us-executives/
  - Date: 2025-2026
  - Pillar tags: fraud, deepfake, BEC

- **Synthetic identity fraud: $30–35bn annual US loss estimate; reported identity-related losses $12.5bn in 2024 (+25%)** — 67% of banks/fintechs saw fraud rates climb in 2025. Boston Fed: GenAI is materially expanding synthetic-ID fraud risk.
  - Source: https://www.biia.com/synthetic-identity-fraud-statistics-2026-hard-numbers-big-threats/
  - Source: https://www.bostonfed.org/news-and-events/news/2025/04/synthetic-identity-fraud-financial-fraud-expanding-because-of-generative-artificial-intelligence.aspx
  - Date: 2025-04 / 2026
  - Pillar tags: fraud, synthetic-id, banking

- **FATF Horizon Scan: AI & Deepfakes published 22 Dec 2025** — Synthetic audio/video/image content defeats KYC, remote onboarding, biometric verification and liveness; FATF expects supervisors to scrutinise AI-specific AML/CFT controls and AI-risk governance frameworks.
  - Source: https://www.fatf-gafi.org/en/publications/Methodsandtrends/horizon-scan-ai-deepfake.html
  - Source: https://www.tlt.com/insights-and-events/insight/fatf-horizon-scan-ai-deepfakes----impacts-on-aml-cft-cpf
  - Date: 2025-12-22
  - Pillar tags: fraud, deepfake, AML, regulation
  - Suggested angle: "FATF just told supervisors what 'good' looks like for AI risk. The vendors who haven't built that map are about to be on the wrong side of every ARR conversation."

- **Equifax: synthetic-identity fraud "slipping past every lender" (April 2026 alert)** — New pattern of AI-stitched personas opening credit lines and aging accounts before bust-out.
  - Source: https://www.thestreet.com/personal-finance/equifax-flagged-synthetic-identity-fraud-thats-slipping-past-every-lender
  - Date: 2026-04
  - Pillar tags: fraud, synthetic-id, banking

---

## Pillar 4: ZKPs in Practice

- **OpenID Foundation: self-certification for OpenID4VP 1.0, OpenID4VCI 1.0, HAIP 1.0 launched 26 Feb 2026** — First conformance regime for the protocols underpinning EUDI Wallet and most production verifiable-credential stacks. Credential-format agnostic: SD-JWT VC, ISO mdoc, W3C VCDM all in scope.
  - Source: https://openid.net/openid-for-verifiable-credential-self-certification-to-launch-feb-2026/
  - Source: https://mobileidworld.com/openid-sets-feb-2026-self-certification-launch-for-wallet-and-verifiable-credential-conformance-tests/
  - Date: 2026-02-26
  - Pillar tags: ZKP, standards, EUDI

- **Privado ID Release 7: Identity Verification for Apps cuts user steps from 9 → 4 (50% faster)** — Spun off from Polygon Labs as Privado ID in 2024; built on the iden3 protocol with on-device ZK proofs, EVM-compatible. Now positioning Web3-native UX at Web2 latencies.
  - Source: https://www.privado.id/blog/introducing-privado-id-moving-beyond-polygon-to-deliver-independent-privacy-preserving-identity-solutions
  - Source: https://docs.privado.id/docs/introduction/
  - Date: 2026
  - Pillar tags: ZKP, decentralised-identity

- **GLEIF + Chainlink Sibos 2025 strategic partnership** — Brings vLEI-anchored institutional identity onto blockchain rails for cross-border digital-asset settlement; first credible "compliance-grade" identity primitive in DeFi-adjacent infrastructure.
  - Source: https://blog.chain.link/sibos-2025-recap/
  - Date: 2025-09
  - Pillar tags: ZKP, identity, capital-markets

- **Selective disclosure in EUDI is a ZK use case in production by default** — ARF v2.0 mandates support for selective disclosure of attributes; OpenID4VP carries SD-JWT VC and ISO mdoc, both designed to expose only required attributes.
  - Source: https://eu-digital-identity-wallet.github.io/eudi-doc-architecture-and-reference-framework/1.1.0/arf/
  - Date: 2026
  - Pillar tags: ZKP, EUDI, privacy

---

## Pillar 5: Passwordless & Split-key

- **FIDO Alliance Passkey Index (Oct 2025): 15bn+ accounts now passkey-capable, 48% of top-100 sites support passkeys** — 75% global consumer awareness (up from 39% two years prior); 69% of users have at least one passkey; 36% have a passkey enrolled on a given account; 26% of sign-ins on enabling sites use passkeys; passkey sign-in averages 8.5s (-73% vs other methods).
  - Source: https://fidoalliance.org/wp-content/uploads/2025/10/FIDO-Passkey-Index-October-2025.pdf
  - Source: https://fidoalliance.org/fido-alliance-launches-passkey-index-revealing-significant-passkey-uptake-and-business-benefits/
  - Date: 2025-10
  - Pillar tags: passwordless, FIDO, authentication

- **Banking lags: hardware-bound passkey activation in consumer banking <5%** — Most financial-services institutions still in planning or early pilot. Synced passkeys higher but still well below web-platform averages.
  - Source: https://www.useideem.com/post/passwordless-progress-report-2026-banks-leading
  - Date: 2026
  - Pillar tags: passwordless, banking

- **Central Bank of UAE mandate: all licensed FIs must eliminate SMS/email OTPs by March 2026** — First major regulator to set a hard sunset on shared-secret OTPs; precedent that EU and UK regulators are watching.
  - Source: https://www.useideem.com/post/passwordless-progress-report-2026-banks-leading
  - Date: 2026-03
  - Pillar tags: passwordless, regulation, banking

- **PSD3 reasserts SCA harmonisation with explicit anti-friction stance for TPP flows** — Banks may not stack additional auth steps on TPP requests; SCA must not be applied "more times than necessary." Sets the stage for passkeys (and EUDI Wallet) to be the canonical SCA factor.
  - Source: https://financialregulation.linklaters.com/post/102lw90/psd3-breakthrough-eu-legislators-agree-payments-regulation-reforms
  - Date: 2026-04-23
  - Pillar tags: passwordless, regulation, SCA

---

## LATAM landscape

- **Banco Central do Brasil: Drex confirmed for 2026 launch, but pivoted away from blockchain** — First phase restricted to FIs, notaries, brokers, focused on credit-guarantee reconciliation (preventing the same asset being pledged twice). BC went technology-agnostic after data-privacy / LGPD / banking-secrecy compatibility issues with the original DLT design.
  - Source: https://www.spacemoney.com.br/investimentos/criptomoeda/drex-2026-fases-mitos/
  - Source: https://www.ainvest.com/news/brazil-fast-tracks-drex-cbdc-launch-2026-global-trends-2508/
  - Date: 2025-2026
  - Pillar tags: LATAM, CBDC, Brazil

- **Brazil Pix MED 2.0 mandatory from February 2026** — New version of the Special Return Mechanism for Pix-fraud reversal; BC tightened oversight of instant-payment fraud after first year of Pix limits and the R$5,000 threshold debate. Brazilian financial-sector fraud losses reached R$10.1bn in 2024 (+17% YoY); ~70% from social engineering.
  - Source: https://br.cointelegraph.com/news/central-bank-of-brazil-will-go-for-it-and-try-to-save-drex-from-the-r5-000-pix-fiasco
  - Source: https://ironvest.com/blog/brazilian-banks-can-reduce-social-engineering-fraud-heres-how/
  - Date: 2026-02
  - Pillar tags: LATAM, Brazil, fraud, payments
  - Suggested angle: "MED 2.0 makes Brazil the first major market with a regulator-mandated Pix-fraud reversal mechanism. The identity question: who's accountable for the credential that authorised the original transfer?"

- **Colombia mandates open finance: Decree 0368 issued 7 April 2026; technical deadline 8 August 2026** — SFC will administer the participant directory; standardised APIs with prior, express, informed consent; standards to be published within six months. Non-supervised fintechs concerned about being shut out.
  - Source: https://www.superfinanciera.gov.co/publicaciones/10116081/finanzas-abiertas-obligatorias-impulsaran-el-desarrollo-del-sistema-y-la-inclusion-financiera-en-el-pais/
  - Source: https://iupana.com/2026/04/28/fintechs-no-vigiladas-fuera-del-open-finance-en-colombia/
  - Date: 2026-04-07
  - Pillar tags: LATAM, Colombia, open finance, regulation

- **Chile Law 21,719 (data protection) fully in force December 2026** — Modernises Chile's data-protection regime to OECD/EU baseline; new Data Protection Agency operational. Chile's open-finance regime requires SCA and links identity/auth to state-of-the-art tech.
  - Source: https://practiceguides.chambers.com/practice-guides/data-protection-privacy-2026/chile
  - Source: https://www.konsentus.com/unlocking-the-fintech-law-open-finance-in-chile/
  - Date: 2026-12
  - Pillar tags: LATAM, Chile, regulation, privacy

- **Mexico CNBV: digital onboarding requires biometrics + liveness + cross-checking against official registries** — Sumsub's 2026 CNBV AML audit guide reaffirms: institutions must demonstrate identity was verified "in a robust and properly documented manner" — tooling neutral but evidence-bar high. Synthetic identities and account-as-mule patterns growing.
  - Source: https://sumsub.com/blog/cnbv-aml-audit-mexico-compliance-guide/
  - Source: https://facephi.com/en/aml-compliance-in-mexico-digital-identity-cnbv-and-fraud-prevention-in-onboarding/
  - Date: 2026
  - Pillar tags: LATAM, Mexico, KYC, CNBV

- **LATAM deepfake incidents +255%; Mexico +500%; Argentina highest deepfake-related search interest** — One Argentine case: woman defrauded of £10,000 by AI-generated "George Clooney." Brazilian banking fraud-detection systems generally not designed for deepfake.
  - Source: https://www.ventasdeseguridad.com/en/news/latest-news/431-enterprises/24355-a-marked-increase-in-deepfakes-is-reported-throughout-latin-america.html
  - Source: https://ironvest.com/blog/what-will-stop-banking-fraud-in-argentina-in-2026/
  - Date: 2026
  - Pillar tags: LATAM, fraud, deepfake

- **Meta sued Brazil/China advertisers over celebrity-deepfake healthcare scams (Feb 2026)** — Operation used deepfakes of a prominent physician; first major platform-level enforcement action against deepfake ad fraud in LATAM.
  - Source: https://hongkongfp.com/2026/02/27/us-tech-giant-meta-sues-brazil-china-advertisers-over-celebrity-deepfake-scams/
  - Date: 2026-02-27
  - Pillar tags: LATAM, Brazil, deepfake, fraud

- **Nubank, Mercado Pago, Ualá all ramping in 2026** — Mercado Pago requesting full banking licences in Argentina and pending in Mexico; Nubank Colombia weathered a third-party data-breach scare (denied own systems compromised) Q1 2026; Ualá pushing into card competition with Nubank/Mercado Pago.
  - Source: https://www.valoraanalitik.com/nubank-niega-filtraciones-de-datos-2026/
  - Source: https://www.iproup.com/finanzas/65468-uala-vs-mercado-pago-y-nubank-el-plan-para-quedarse-con-el-trono-de-la-banca-digital
  - Date: 2026-01–04
  - Pillar tags: LATAM, neobanks

---

## Category / Founder POV signals

- **KuppingerCole Research Compass IAM 2026 published** — Forward-looking framing of market consolidation and tech shifts through 2027; CIAM Leadership Compass scheduled in 2026 cycle. Microsoft named top overall IDaaS leader; Ping named Overall Leader in 2026 KC CIAM Leadership Compass.
  - Source: https://www.kuppingercole.com/research/an82012/research-compass-identity-and-access-management-2026
  - Source: https://hub.pingidentity.com/analyst-reports/kuppingercole-leadership-compass-ciam
  - Date: 2026
  - Pillar tags: analyst, CIAM

- **Liminal 2026 Predictions: continuous identity becomes default; synthetic identities become "model-generated personas"** — 99% of CIAM eCommerce practitioners now consider IDV a critical capability; 99% expect to deploy passkeys/hardware tokens within 2 years; 84% cite integration challenges.
  - Source: https://liminal.co/articles/2026-predictions-whats-next-fraud-identity/
  - Source: https://liminal.co/reports/link-index-reports/customer-identity-access-management-in-ecommerce/
  - Date: 2026
  - Pillar tags: analyst, identity, fraud

- **Money 20/20 Europe (Amsterdam, 2–4 June 2026) — content pillars include "AI and the Agentic Age" and "Regulation in the Fast Lane"** — Decentralised identity, asset tokenisation, deepfake prevention all on agenda; relevant in-person window positioning around PSD3/EUDI/AMLA narrative.
  - Source: https://europe.money2020.com/agenda/content-pillars
  - Date: 2026-06-02
  - Pillar tags: events

- **Eastnets + FacePhi Sibos 2025 alliance: "world's first end-to-end anti-fraud ecosystem"** — Combines AML/CFT, biometric auth, mule-account detection. Notable as a banking-channel partnership rather than another standalone vendor.
  - Source: https://www.eastnets.com/blog/7-key-takeaways-from-sibos-2025
  - Date: 2025-09
  - Pillar tags: identity, banking, partnership

---

## Competitor pulse

- **2026-02-05** — Veriff acquired Estonian KYB firm Vespia (M&A). [Tracxn](https://tracxn.com/d/companies/veriff/__wn13cIFrjSk3QHJ4L8aq05jHHYlceDZb1YhBD25qmGc/funding-and-investors)
- **2026-01** — Socure announced acquisition of Qlarifi, expanding into safer BNPL. [HostMerchantServices](https://hostmerchantservices.com/2026/01/socure-acquires-qlarifi/)
- **2026-03** — BioCatch unveiled DeviceIQ for device-risk evaluation in digital banking. [Biometric Update reference](https://www.biometricupdate.com/companies/biocatch)
- **2026-04-08** — iProov published 2026 Threat Intelligence Report (iOS injection +741%). [iProov](https://www.iproov.com/reports/threat-intelligence-report-2026)
- **2025-11** — Veriff, Sumsub, Veridas issued joint warning on sophistication of attacks. [Biometric Update](https://www.biometricupdate.com/202511/veriff-sumsub-veridas-warn-of-sophisticated-fraud-attacks)
- **2025-12** — Sumsub published Identity Fraud Report 2025-2026; flagged agentic-AI scams as 2026 threat. [Sumsub](https://sumsub.com/fraud-report-2025/)
- **2026** — Veriff published Identity Fraud Report 2026. [Veriff](https://www.veriff.com/pr-news/veriff-identity-fraud-report-2026)
- **2026** — Entrust/Onfido published 2026 Identity Fraud Report. [Onfido](https://onfido.com/landing/identity-fraud-report/)
- **2026** — Privado ID shipped Release 7 with Identity Verification for Apps. [Privado ID](https://www.privado.id/)
- Persona's last public funding: $200m Series D (Apr 2025); total $418m. [CB Insights](https://www.cbinsights.com/company/persona-1/financials)
- Yoti: last funding $9.49m Dec 2023; total $210m. [Tracxn](https://tracxn.com/d/companies/yoti/__r0-NLomAs8ISqr75av9_8aMF-nTxBkXo6ri-3MXnDG4/funding-and-investors)
- AU10TIX: most recent $80m TPG/Oak HC/FT round; ~198 employees Feb 2026. [CB Insights](https://www.cbinsights.com/company/au10tix/financials)
- Jumio: last funding $150m March 2021; ~611 employees March 2026. [Tracxn](https://tracxn.com/d/companies/jumio/__n_v3Ht0SWd-Yl-76hYL_8HHaij8GvNxHSXOTsZWKnT8)
- Onfido (under Entrust since 8 April 2024); Signicat (Nordic Capital portfolio since 2019) — both quiet on net-new equity in 2026.

---

## Standing themes worth recurring on

1. **"SCA worked. The fraud moved upstream of it."** — EBA/ECB Dec 2025 data is the canonical citation. Strong auth still effective on the credential; fraudsters now manipulate the human or the document. Reusable across PSD3, deepfake, voice-clone, mule, CBA-style underwriting fraud posts.

2. **"December 2026 is the political deadline. ENISA certification is the real one."** — Wallet ≠ certified product. Useful framing every time another country claims they'll "launch" — separates marketing-launch from production-grade.

3. **"AMLA replaces 27 interpretations of KYC with one rulebook."** — Entire 2026–2027 narrative arc as RTS package lands and direct supervision of 40 FIs builds out. Identity vendors who haven't engaged with the consultation are about to be told what "sufficient" means.

4. **"Liveness was built for cameras. Injection attacks bypass the camera."** — iProov's iOS data is the proof point. Reusable when defending the case for cryptographic device binding, network signals, behavioural and provenance over pure biometric liveness.

5. **"The wallet isn't a feature. It's a chokepoint between identity vendors and the bank."** — December 2027 relying-party deadline means the bank either accepts the wallet (and the wallet's IDV outcome) or explains why not. Identity vendors who aren't on the issuer/wallet side become a step the bank can skip.
