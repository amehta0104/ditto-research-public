# Cycle Delta -- 2026-10-23

Window: 2026-10-20 -> 2026-10-23 (72 hours, Friday run). The 10-20 and 10-21 deltas cover 10-18 to 10-21, so this cycle focuses on 10-21 to early 10-23.

## Provenance and integrity notes

- Brand brief and competitors list were fetched from the worker. Deduplication was checked by keyword against every delta on the worker from 2026-09-28 to 2026-10-22.
- **Carry-over:** the 2026-10-22 delta on the worker is a thin "no new material" file written while the worker was unreachable. A fuller 10-22 scan (AMLA-OLAF, KDDI NVv2) was never uploaded. Both items are dated 10-21, are inside this window, are not in any worker delta, and were re-verified against their primaries today. They are included below.
- This file is ASCII-only to avoid the double-encoding issue on the worker PUT path.
- **Checked and rejected:**
  - iProov "human approval service" for AI agents (ID Tech Digest 10-22): only the HAPS specification (September 2026, logged 09-24/25) could be found. No separate in-window launch was confirmed.
  - EU mDL Implementing Regulation 2026/2266: published 10-14. Outside window. (Enters into force 11-03; added as a watch item.)
  - TransUnion Synthetic Fraud and Credit Washing Scores (10-20): US credit-bureau lending product, off-ICP. Not counted.
  - Login.gov + CLEAR, eMudhra root CA distrust, Smart Africa pilot, Switzerland biometric ID, Somalia ID: US government, PKI or public-sector items with no bank-identity angle. Not counted.
  - Persona academic research grants (up to USD 100,000): competitor PR with no market signal. Not counted.
  - BCB Pix MED 2.0 / IN BCB 767: already a watch item (10-26). No new material.
  - No in-window material found for PSD3/PSR OJEU, EBA/ECB/DORA, FATF, FCA/PSR APP fraud, NIST, onboarding benchmarks, OpenID4VP/ZKP bank pilots, Ofcom enforcement, or CNBV/Superfinanciera/CMF.

## Override-worthy this cycle

1. **Mexico's Senate passed the Digital Economy Law: financial entities must accept CURP Digital as a trust mechanism for remote contracting of financial services.** Account:. Angle: Mexico just made a state digital identity a mandatory-acceptance onboarding rail. Pair it with CNBV Anexo 71 biometrics (due early November) for a "Mexico's identity stack is being written this quarter" post.
2. **Greece passed its under-15 social media ban (vote 10-22). Platforms must verify age from 2027-01-01, using Kids Wallet / gov.gr Wallet attestations that disclose only above/below 15.** Account: company. Angle: a national law in force that asks for one bit, not a birthdate. Selective disclosure moves from pilot to legal requirement.
3. **UK laid the draft "information gateway" code letting public authorities share data and credentials with certified DVS providers (10-21).** Account: company /. Angle: the UK is opening authoritative government data to private verifiers. That changes what "verified" means for UK onboarding.

## New findings

### Pillar 1: Banking & Payments

(no new material in window. For Mexico's Digital Economy Law, see Pillar 5.)

### Pillar 2: Identity orchestration

(no new material in window.)

### Pillar 3: EUDI / eIDAS2

(no new material in window. EU mDL Implementing Regulation 2026/2266 was published 10-14, outside window; see watch items.)

### Pillar 4: KYC / AML compliance

- **AMLA and OLAF signed a Working Arrangement on 2026-10-21 to cooperate and exchange information against money laundering, terrorist financing, fraud and corruption.** It covers operational and strategic information: criminal patterns, emerging trends, risk indicators and crime-prevention methods. OLAF will contribute anti-fraud expertise to joint analyses coordinated by AMLA, and information from those analyses can be cross-checked against OLAF data. AMLA Chair Bruna Szego: "Criminals do not respect institutional boundaries, and neither can our response." OLAF Director-General Petr Klement called it "an important step towards stronger day-to-day cooperation between AMLA, OLAF and the Financial Intelligence Units".

  **Why it matters:** AMLA is building its intelligence plumbing before direct supervision starts in 2028. When FIU and OLAF data are analysed together, a red flag at one obliged entity can be matched against patterns across the EU. A bank's onboarding records then feed EU-level analysis, so it matters more that the bank can show who was verified, how and when. Treat this as supporting evidence in an AMLA-readiness post, not a headline.
  - Source (primary): https://anti-fraud.ec.europa.eu/media-corner/news/amla-and-olaf-strengthen-cooperation-fight-against-financial-crime-2026-10-21_en
  - Date: 2026-10-21
  - **Drafting cautions:** this is a cooperation arrangement, not a new obligation on banks. Do not imply that it changes CDD requirements or that OLAF supervises obliged entities.

- **French authorities (Treasury, AMF, Banque de France, ACPR) published joint proposals for the MiCA review on 2026-10-21.** They propose to "strengthen ESMA's role in supervising significant crypto-asset service providers" and crypto conglomerates. They also want a framework for multi-issuance stablecoins (equivalence assessments, supervisory cooperation, stronger reserve protection) and a "secure and proportionate" DeFi framework with "adapted due diligence obligations" and protocol certification. They back euro stablecoins and tokenised deposits. Crypto and traditional finance should converge but keep distinct legal regimes.

  **Why it matters:** France is pushing for EU-level supervision of the largest CASPs and for due-diligence duties in DeFi. If that holds, crypto-fintech KYC will be judged against one ESMA standard, not 27 national readings. This resolves the 10-22 watch item. It is low priority: the press release does not address the Travel Rule or onboarding procedures directly.
  - Source (primary): https://www.banque-france.fr/fr/communiques-de-presse/revision-du-reglement-mica-les-autorites-francaises-publient-leurs-propositions-conjointes
  - Date: 2026-10-21
  - **Drafting cautions:** these are national proposals to a Commission consultation, not adopted law. Do not say ESMA "will" supervise CASPs.

### Pillar 5: Customer onboarding

- **Mexico's Senate approved the Digital Economy Law for Digital and Electronic Payments on 2026-10-20 (72-37 in the particular vote; 73-34 in general).** The law recognises CURP Digital, alongside the Citizen Digital File, as a "mecanismo de confianza" that financial entities must accept when customers contract financial services digitally. Users can still choose other official ID. The Chamber of Deputies had approved the bill on 10-06, so it now goes to publication. It takes effect on publication in the DOF. SHCP then has 15 business days to designate sectors where digital-only payment becomes mandatory, and sectoral regulators have 15 more to set transition timelines.

  **Why it matters:** Mexican banks and fintechs will have to accept a state digital credential as an onboarding input. Accepting CURP Digital does not replace document checks, biometrics or fraud controls. Institutions now have to combine a state credential with CNBV Anexo 71 facial biometrics (due early November) and their own risk checks. That is an orchestration problem. It is also a -ready story: in one quarter, Mexico has mandated biometrics in branches and a digital ID rail for remote onboarding.
  - Source: https://www.infobae.com/mexico/2026/10/20/el-senado-aprueba-la-nueva-ley-que-obliga-al-pago-digital-y-electronico-a-partir-de-2027/
  - Source: https://www.informador.mx/mexico/Senado-aprueba-Ley-de-Economia-Digitalpretenden-reducir-los-pagos-en-efectivo-20261021-0019.html
  - Source: https://www.bloomberglinea.com/latinoamerica/mexico/senado-aprueba-pagos-digitales-en-mexico-a-la-espera-de-que-gobierno-decida-sectores-de-aplicacion/
  - Date: 2026-10-20
  - **Drafting cautions:** no DOF publication was found at scan time, so say "approved by Congress" or "pending publication", not "in force". The coverage is mostly about cash and digital payments; the CURP Digital provision is one part of it. Media reports differ on the vote count (72-34 vs 72-37 in the particular vote), so cite 73-34 in general or omit the count. Do not claim CURP Digital is biometric unless a primary says so.

### Pillar 6: Identity verification (IDV)

- **UK government laid the draft Code of Practice for Public Authorities Sharing Information with Digital Verification Services in Parliament (2026-10-21).** The code sets out how public authorities can use the section 45 power in the Data (Use and Access) Act 2025. That power lets an authority disclose information about a person to a DVS provider that is certified and on the government DVS register, when the person has asked that provider to verify them. The OfDIA blog says the code covers "both direct issuance of government-issued credentials to be stored in registered private sector wallets, and sharing specific attributes or status checks." Both Houses must approve it. Government aims to publish the final code "by the end of the year", and section 45 commences when the code is published. HMRC, the Welsh Revenue Authority and Revenue Scotland are excluded from the initial commencement. Where special-category data (including biometrics) is shared, authorities need both an Article 6 basis and an Article 9 condition under UK GDPR.

  **Why it matters:** this is the switch that lets certified private-sector verifiers check against government records and issue government credentials into private wallets. UK onboarding moves from "check the document" towards "check the authoritative source". Certification and register status become a commercial requirement for any IDV vendor selling into UK banking and age assurance.
  - Source (primary): https://enablingdigitalidentity.blog.gov.uk/2026/10/21/the-draft-code-of-practice-for-the-information-gateway-has-been-laid-in-parliament/
  - Source: https://www.biometricupdate.com/202610/uk-publishes-draft-data-sharing-code-for-digital-verification-services
  - Date: 2026-10-21
  - **Drafting cautions:** this is a draft, and the gateway is not live until Parliament approves and the code is published. Do not name which datasets (HMPO, DVLA) will flow first; the blog does not say. Do not say or imply that Ditto is on the DVS register unless verified.

- **Sumsub says its Liveness product passed iBeta Level 3 Presentation Attack Detection testing (ISO/IEC 30107-3), announced 2026-10-21.** Testers ran 900 presentation attacks across Android and iOS, including hyper-realistic masks, and recorded 0% APCER. Sumsub calls Level 3 iBeta's most rigorous tier. Competitor (direct list).

  **Why it matters:** Level 3 is becoming the new PAD bar for competitors to claim. Buyers will start asking for it in RFPs, which raises the proof threshold for any liveness claim, including Ditto Verify's.
  - Source: https://sumsub.com/newsroom/sumsub-liveness-achieves-ibeta-level-3-compliance-in-independent-biometric-testing
  - Date: 2026-10-21
  - **Drafting cautions:** this is vendor-reported. The iBeta confirmation letter was not read, and no BPCER was disclosed. PAD testing covers physical presentation attacks, not injection or deepfake-stream attacks; do not equate it with deepfake resistance. Never draft a post attacking a competitor.

### Pillar 7: Fraud / Deepfakes

- **Broadcom launched Arcot Scam Defense (2026-10-21). It is a second layer inside its 3-D Secure service that flags likely social-engineering fraud even after the cardholder has passed the authentication challenge.** It looks at transaction data, device intelligence, historical behaviour and the challenge interaction itself. Examples include a location mismatch between devices, delayed password entry, a switch to an alternative authentication method, and a large distance between the checkout device and the authenticating device. Broadcom reports USD 500m of fraud on successfully authenticated challenges over 12 months. At one pilot issuer, reviewing the top 1% of successful challenges was estimated to stop USD 4m of fraud in one month, at a cost of 0.38 points of authentication success rate. Matt Cooke (VP/GM, Payment Security): "financial institutions are recording broad increases in fraud attempts linked to AI-assisted social engineering."

  **Why it matters:** a major 3DS provider is saying that passing SCA no longer means the payment is genuine. When the real customer is manipulated into approving, authentication alone cannot catch it. Device and behaviour signals around the authentication step become the control. This supports the "authentication is not authorisation" argument and links to the UK APP-reimbursement debate.
  - Source: https://thepaypers.com/fraud-and-fincrime/news/broadcom-launches-arcot-scam-defense-against-social-engineering-fraud
  - Date: 2026-10-21
  - **Drafting cautions:** all figures are Broadcom's own (the investor-relations primary returned 403). Attribute them to Broadcom. The pilot figure is an estimate for one unnamed issuer. Card-not-present only.

### Pillar 8: Mobile trust & app security

(no new material in window. For SIM-based number verification, see Pillar 9.)

### Pillar 9: Passwordless / split-key

- **KDDI commercially launched "Number Verification v2" (NVv2) on 2026-10-21, integrated into Google Firebase Phone Number Verification.** NVv2 checks a user's phone number against the carrier's SIM and contract records in one step, with no SMS one-time passcode sent or typed. KDDI says this closes the routes used to steal SMS codes, such as real-time phishing, and reduces drop-off at authentication. The API follows the GSMA Open Gateway and Linux Foundation CAMARA specifications. KDDI also names AI agents registering accounts and making payments as a use case. Firebase Senior Product Manager Micah Baker: "Our collaboration with KDDI allows Firebase to guide developers to better security, better end user experience".

  **Why it matters:** with a major carrier and Google's developer platform behind it, "SMS OTP without the SMS" becomes an option any app developer can switch on, not a bespoke telco integration. It also puts more trust in the SIM record, so SIM-swap and port-out controls matter more. A carrier number check proves control of a SIM. It does not prove who the person is or that the device is clean. For banks, it is a better possession factor, not a replacement for phishing-resistant, device-bound authentication.
  - Source (primary): https://newsroom.kddi.com/english/news/detail/kddi_nr-1204_4771.html
  - Source: https://idtechwire.com/kddi-launches-sim-based-number-verification-on-google-firebase/
  - Date: 2026-10-21
  - **Drafting cautions:** KDDI (au) subscribers in Japan only. Do not imply global carrier coverage through Firebase. No pricing or adoption figures. Do not call it phishing-proof.

### Pillar 10: ZKPs in practice

(no new material in window. For a selective-disclosure law in force, see the Greek age-assurance item in Pillar 11.)

### Pillar 11: Age assurance & privacy attributes

- **The Greek Parliament passed the bill banning social media for under-15s on 2026-10-22 (reported 10-23). It applies from 2027-01-01.** New Democracy voted in favour, PASOK voted "present", and the other parties voted against. Platforms are responsible for verifying age, and self-declaration in terms of service is not enough. The government will use the Kids Wallet app alongside gov.gr Wallet and an EU-standard age-verification system. Digital Governance Minister Dimitris Papastathopoulos said the system shares "only the information if they are above or below the age limit, without disclosing their birthdate." Reports cite fines of up to 6% of global annual turnover. Private messaging and educational uses are excluded. Greece is working with Cyprus, Denmark, France, Ireland, Italy and Spain on a European age-verification solution.

  **Why it matters:** this is a national law, already passed, that requires an age check to return a single attribute and nothing else. It confirms the 10-14 pattern (Turkiye state token, Kids Wallet, bank-backed checks in Australia) as law, not pilot. Gambling and gaming relying parties should expect the same design: verify the attribute, do not collect the document.
  - Source: https://www.protothema.gr/politics/article/1899210/perase-apo-ti-vouli-i-apagoreusi-ton-social-media-gia-paidia-kato-ton-15-eton-sugrousi-skertsou-me-tin-adipoliteusi/
  - Source: https://www.newsit.gr/politikh/yperpsifistike-sti-vouli-to-nomosxedio-gia-tin-apagoreysi-ton-social-media-se-paidia-kato-ton-15-eton-pos-tha-leitourgei/4805299/
  - Date: 2026-10-22
  - **Drafting cautions:** the 6% fine figure comes from Greek media summaries, not the bill text; attribute it or omit it. The law does not mandate one technology, and Kids Wallet is one available tool. Do not call it a ZKP system; the government describes attribute-only disclosure, not a specific cryptographic method.

## Open watch items

- **Mexico Digital Economy Law:** watch for DOF publication and the SHCP sector list (15 business days after publication). Look for CNBV or SHCP rules on how CURP Digital acceptance works in onboarding.
- **UK DVS information gateway code:** parliamentary approval votes; final publication "by the end of the year".
- **Greek under-15 law:** Government Gazette publication; platform compliance announcements before 2027-01-01.
- **Ofcom October 2026 industry bulletin / TikTok age-assurance update:** still unread.
- **FIDO CMRA and Verifier Identification Framework:** publication expected "in coming weeks".
- **EPC SCARLET:** read the EPC primary for verbatim text and participation terms.
- **YuanKong RAT:** Star Labs primary still not found.
- **NetChoice/CCIA:** en banc or certiorari filings on Florida HB 3 and Georgia SB 351.
- **DIdG follow-up:** committee recommendation 21/8617. Link it to SCARLET liability.
- **Passkey Index 2026 PDF:** financial-services breakouts.
- **Bank of America:** consent orders.
- **AMLA simplified-CDD roundtables:** participant list or dates.
- **PSD3/PSR OJEU:** next check 10-26.
- **2026-10-26:** BCB MED 2.0 / IN BCB 767 Pix changes take full effect.
- **2026-10-26/30:** FATF plenary, Paris.
- **2026-10-29/30:** EUDI Wallet Launchpad 2026, Brussels.
- **2026-10-30:** Microsoft Entra telephony-provider option for SMS/voice MFA (Microsoft-provided SMS ends 2027-02-01).
- **End-October:** Ofcom over-16 age-assurance rapid assessment; Romania EUDI sandbox target (10-31).
- **2026-10-31:** ECB SSM-2026-0301 action-plan deadline.
- **2026-11-01:** Turkiye age-token regulation takes effect.
- **2026-11-03:** AMLA central AML/CFT database RTS consultation closes; EU mDL Implementing Regulation 2026/2266 enters into force.
- **Early November:** CNBV Anexo 71 biometric compliance deadline; BCB "Circuito Pix" session on Resolution 587 operations.
- **2026-11-09:** Apple Cash reload ID check goes live.
- **2026-11-16:** ACCS-IEEE event on New York age-assurance regulations.
- **2026-11-18:** EUDI ARF Iteration 6 closes.
- **2026-12-24:** EUDI wallet-availability deadline (62 days).
- **2027-01-01:** Greek under-15 ban applies.
- **2027-01-02:** d-you launch.
- **Workday / C1.ai:** close expected by 2027-01-31.
- **Summer 2027:** EPC SCARLET open consultation. **December 2027:** first SCARLET rulebook.
- **MyCheck:** launch date and Dutch government response.
