# Cycle Delta -- 2026-10-26

Window: 2026-10-23 -> 2026-10-26 (72 hours, Monday run, weekend coverage)

## Provenance and integrity notes

- Brand brief and competitors list were fetched from the worker. Deduplication was checked by keyword against every worker delta from 2026-10-05 to 2026-10-23.
- **Carry-over:** a fuller 10-23 scan was written locally but never uploaded. The 10-23 delta on the worker is a thinner run that covers only Greece and BCB. Seven items from the fuller scan (dated 10-20/10-21) are not in any worker delta. They fall outside this window, so they are NOT counted as new findings. They are listed separately at the end under "Carry-over (outside window)" so the drafter does not lose them. Each one was verified against its sources on 10-23.
- This file is ASCII-only to avoid the double-encoding issue on the worker PUT path.
- **Checked and rejected:**
  - Germany DIdG Bundestag vote (10-16), FIDO CMRA / Verifier ID framework (10-20/21), Hirudo (10-14), Bank of America (10-13), identifAI (10-13): already logged.
  - American Express USD 350m OCC/Fed AML penalty: dated 10-09. Outside window (already flagged 10-16).
  - Pakistan NCCIA arrests in an AI-forged-identity Canadian bank account ring (raids 10-19, reported 10-21): outside window, single secondary source, banks not named. Not counted.
  - iProov 2026 Threat Intelligence Report: published April 2026. Not new.
  - ACMA Medion SIM-swap fine: January 2024. Not new.
  - Ofcom TikTok age-inference investigation: opened 07-16. The promised October status update was not found. Watch item.
  - ESA Joint Committee 2027 work programme (10-23): generic, no identity angle. Not counted.
  - Ondato + Trinsic EUDI integration: rejected 10-23 (vendor integration). Kforce + 1Kosmos (hiring fraud), Checkr + Workday, Oleria, London City Airport biometrics: off-ICP. Not counted.
  - BCB IN 766/767 Pix tracking-graph and MED 2.0 changes take effect today (10-26): known watch item. No new rule.
  - No in-window material found for PSD3/PSR OJEU, EBA/ECB/DORA, AMLA, FATF (plenary 10-28/30), FCA/PSR APP fraud, NIST, onboarding benchmarks, OpenID4VP/ZKP bank pilots, EU age-verification app, US state age laws, CNBV/Superfinanciera/CMF, or identity M&A.

## Override-worthy this cycle

1. **PayPay (44m+ verified users) is dropping photo-based eKYC from early November. It will accept only IC-chip reads of My Number cards and driver's licences, and it gives leaked ID-document images as the reason.** Account: company /. Angle: Japan's largest wallet says a photo of an ID is no longer evidence, because breaches have put those photos in criminals' hands. The document image is now a compromised credential. Cryptographic, chip-read or wallet-based proofs replace it.

## New findings

### Pillar 1: Banking & Payments

(no new material in window. BCB MED 2.0 / Pix tracking changes take effect 10-26; already a watch item.)

### Pillar 2: Identity orchestration

(no new material in window.)

### Pillar 3: EUDI / eIDAS2

(no new material in window. EUDI Wallet Launchpad, Brussels, 10-29/30.)

### Pillar 4: KYC / AML compliance

(no new material in window. FATF plenary runs 10-28/30; outcomes are expected 10-30/31.)

### Pillar 5: Customer onboarding

- **PayPay announced on 2026-10-23 that it will stop accepting photo-based identity verification from early November 2026. It will standardise on methods that read the IC chip in the ID document.** For My Number cards there are two routes: chip read with an electronic-signature password (about 2 minutes), or printed information plus facial recognition plus a chip read for users who have forgotten their password. Driver's licences are read by chip using two 4-digit PINs. PayPay's stated reasons: "personal information, including images of driver's licenses, was leaked due to cyberattacks", which raises the risk of "impersonation and other misuse of images of identity verification documents". It also cites alignment with the amendment to Japan's AML ordinance (Act on Prevention of Transfer of Criminal Proceeds), which takes effect on 2027-04-01. More than 44 million users had completed PayPay identity verification as of September 2026. IDTechWire reports that Kyoto Bank makes a similar change on 2026-11-02.

  **Why it matters:** this is a mass-market operator retiring the "photo of ID plus selfie" flow five months before the regulatory deadline, because document images have leaked so widely that they no longer prove anything. It is a clean real-world example of the shift from "check the picture" to "check the cryptography". For banks and fintechs, a document scan alone is becoming weak evidence, and chip reads, wallet credentials and liveness bound to the chip photo are where onboarding is heading. The same pattern links to UK DVS (government-source checks) and the EUDI wallet.
  - Source (primary): https://about.paypay.ne.jp/en/pr/20261023/01/
  - Source: https://idtechwire.com/paypay-to-replace-photo-based-ekyc-with-chip-reading/
  - Date: 2026-10-23
  - **Drafting cautions:** Japan-specific. The April 2027 rule is the ordinance amendment PayPay cites; do not describe its full scope without reading the ordinance. The Kyoto Bank date comes from IDTechWire only. Do not say Japan has "banned" photo eKYC.

### Pillar 6: Identity verification (IDV)

- **HyperVerge reported on 2026-10-23 that its HyperKYC face-liveness stack passed two BixeLab evaluations.** PAD: ISO/IEC 30107-3:2023 at BixeLab Level 3 (September 2026); 150 presentation attacks with zero accepted; a 4% genuine-user rejection rate per transaction and 0% per user (Samsung Galaxy S25 and iPhone 13). Injection: CEN/TS 18099 at the Substantial level (2026-07-01 to 09-10); 630 injected transactions using face swaps, deepfakes and avatar reenactment, all rejected; 1.33% genuine error rate, across Android, iOS and Web SDKs. BixeLab notes the evaluation is not NIST-accredited and is not a certification or government endorsement.

  **Why it matters:** together with Sumsub's iBeta Level 3 claim (10-21, see carry-over) and IDEMIA's BixeLab CEN/TS 18099 result (logged earlier in October), this is the third vendor in a month to publish independent injection or PAD results. RFP language is moving from "has liveness" to "show me the CEN/TS 18099 and 30107-3 Level 3 letters". The fact that HyperVerge disclosed genuine-user error rates is useful: it shows buyers should ask about false rejects, not just attacks stopped.
  - Source: https://idtechwire.com/hyperverge-passes-bixelab-presentation-and-injection-attack-tests/
  - Date: 2026-10-23
  - **Drafting cautions:** vendor-reported; the BixeLab letters were not read directly. The sample sizes are small (150 PAD attacks). Never name the vendor in a post. Use it as evidence for a category point ("independent injection testing is becoming table stakes").

### Pillar 7: Fraud / Deepfakes

(no new material in window.)

### Pillar 8: Mobile trust & app security

(no new material in window.)

### Pillar 9: Passwordless / split-key

- **Huntress disclosed a "token spraying" campaign on 2026-10-23. Stolen Microsoft 365 session tokens were replayed at scale against 79 organisations between 2026-07-14 and 2026-09-22.** There were 497 successful sign-ins and more than 200,000 failed attempts. The tokens were captured by adversary-in-the-middle relays, device-code phishing and social engineering, then replayed from separate infrastructure. Six IPs were traced to a German host, and one incident showed a 12-minute gap between the victim authenticating and the hijacked session appearing. After getting in, attackers registered 48 rogue "DESKTOP-" devices, created hidden inbox rules, and at 19 organisations deleted the victims' MFA methods and registered their own within 3 hours.

  **Why it matters:** a large, well-documented example of MFA being satisfied and then made irrelevant. The user completes a genuine MFA challenge and the attacker walks off with the session. Once in, the attacker's first move is to rewrite the authenticator list. That supports two Ditto arguments: phishing-resistant, origin-bound authentication (passkeys or split-key) stops the relay, and authenticator registration or recovery is itself a high-risk event that needs strong re-verification. It fits with Broadcom's "fraud after successful 3DS" point (carry-over).
  - Source (primary): https://www.huntress.com/blog/token-replay-spray
  - Source: https://idtechwire.com/huntress-finds-stolen-microsoft-365-sessions-used-across-79-organizations/
  - Date: 2026-10-23
  - **Drafting cautions:** this is a workforce (Microsoft 365) attack, and no banks are named. Do not present it as a banking-customer attack. Use it to illustrate the pattern. The figures are Huntress's own telemetry. Passkeys stop AiTM relays at sign-in, but they do not protect a session token that has already been issued if the device itself is compromised; do not overclaim.

### Pillar 10: ZKPs in practice

(no new material in window.)

### Pillar 11: Age assurance & privacy attributes

(no new material in window. Greek under-15 law logged 10-23. Ofcom's over-16 rapid assessment to Parliament is due by end-October.)

## Carry-over (outside window; verified 10-23; not in any worker delta)

Full write-ups, including drafting cautions, are in the unuploaded 10-23 scan. Summaries:

- **Mexico Digital Economy Law (Senate 2026-10-20).** Financial entities must accept CURP Digital as a "mecanismo de confianza" for remote contracting of financial services. Pending DOF publication.. Sources: https://www.infobae.com/mexico/2026/10/20/el-senado-aprueba-la-nueva-ley-que-obliga-al-pago-digital-y-electronico-a-partir-de-2027/; https://www.bloomberglinea.com/latinoamerica/mexico/senado-aprueba-pagos-digitales-en-mexico-a-la-espera-de-que-gobierno-decida-sectores-de-aplicacion/. Caution: say "approved by Congress", not "in force"; vote counts differ between reports.
- **UK DVS information-gateway draft code laid in Parliament (2026-10-21).** Lets public authorities share data and credentials with certified, registered DVS providers under s.45 of the Data (Use and Access) Act 2025. Company /. Source: https://enablingdigitalidentity.blog.gov.uk/2026/10/21/the-draft-code-of-practice-for-the-information-gateway-has-been-laid-in-parliament/. Caution: draft only; the final code is due "by the end of the year".
- **AMLA-OLAF Working Arrangement (2026-10-21).** Information exchange and joint analyses. Company /. Source: https://anti-fraud.ec.europa.eu/media-corner/news/amla-and-olaf-strengthen-cooperation-fight-against-financial-crime-2026-10-21_en. Caution: no new obligations on banks.
- **French authorities' joint MiCA-review proposals (2026-10-21).** ESMA supervision of significant CASPs, and DeFi due-diligence duties. Company. Source: https://www.banque-france.fr/fr/communiques-de-presse/revision-du-reglement-mica-les-autorites-francaises-publient-leurs-propositions-conjointes. Caution: proposals, not law.
- **Broadcom Arcot Scam Defense (2026-10-21).** Flags social-engineering fraud after a successful 3DS challenge. Broadcom cites USD 500m of fraud on authenticated challenges over 12 months. / company. Source: https://thepaypers.com/fraud-and-fincrime/news/broadcom-launches-arcot-scam-defense-against-social-engineering-fraud. Caution: all figures are Broadcom's.
- **KDDI Number Verification v2 on Google Firebase (2026-10-21).** SIM and contract number check with no SMS OTP; follows CAMARA / Open Gateway. Company /. Source: https://newsroom.kddi.com/english/news/detail/kddi_nr-1204_4771.html. Caution: KDDI subscribers in Japan only; do not call it phishing-proof.
- **Sumsub Liveness iBeta Level 3 PAD (2026-10-21).** 900 attacks, 0% APCER (vendor-reported). Competitive intel only. Source: https://sumsub.com/newsroom/sumsub-liveness-achieves-ibeta-level-3-compliance-in-independent-biometric-testing. Caution: PAD is not injection or deepfake resistance; never name it in a post.

## Open watch items

- **2026-10-26 (today):** BCB IN 766/767 Pix tracking-graph / MED 2.0 changes take effect.
- **2026-10-28/30:** FATF plenary, Paris (first under UK President Giles Thomson). Outcomes expected 10-30/31.
- **2026-10-29/30:** EUDI Wallet Launchpad 2026, Brussels.
- **2026-10-30:** BCB unauthorised virtual-asset provider ban takes effect; Microsoft Entra telephony-provider option for SMS/voice MFA.
- **End-October:** Ofcom over-16 age-assurance rapid assessment; Ofcom TikTok investigation status update; Romania EUDI sandbox target (10-31); ECB SSM-2026-0301 action-plan deadline (10-31).
- **2026-11-01:** Turkiye age-token regulation takes effect.
- **2026-11-02:** Kyoto Bank chip-only eKYC (per IDTechWire). **Early November:** PayPay chip-only eKYC goes live; CNBV Anexo 71 biometric deadline.
- **2026-11-03:** AMLA central AML/CFT database RTS consultation closes; EU mDL Implementing Regulation 2026/2266 enters into force.
- **Mexico Digital Economy Law:** DOF publication, then the SHCP sector list (15 business days later).
- **UK DVS gateway code:** parliamentary approval; final code "by end of year".
- **FIDO CMRA and Verifier ID Framework:** public documents "in coming weeks".
- **PSD3/PSR OJEU:** still unpublished. Recheck weekly.
- **2026-11-09:** Apple Cash reload ID check. **2026-11-18:** EUDI ARF Iteration 6 closes. **2026-12-24:** EUDI wallet-availability deadline. **2027-01-01:** Greek under-15 ban applies. **2027-01-02:** d-you launch. **2027-04-01:** Japan AML ordinance amendment (non-face-to-face verification).
