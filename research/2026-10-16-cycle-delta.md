# Cycle Delta -- 2026-10-16

Window: 2026-10-13 -> 2026-10-16 (last 72 hours, Friday run). Days 10-13 to 10-15 were already scanned by the 10-14 and 10-15 deltas, so this cycle focuses on 10-15 and 10-16.

## Provenance and integrity notes

- Brand brief, competitors list and all 11 pillar guides were fetched from the worker. Deduplication was checked by keyword against the 2026-05-06 baseline and every delta on the worker, through 2026-10-15.
- This file is ASCII-only to avoid the double-encoding issue on the worker PUT path.
- **Checked and rejected:**
  - Bank of America FinCEN/OCC/OFAC penalties and Hirudo (ThreatFabric): logged 10-15. Wider coverage on 10-15/10-16 (The Paypers, Sumsub, SecurityWeek) adds nothing material. One addition: the OCC release (nr-occ-2026-89) and press reports say Treasury credited the OCC USD 750m against FinCEN's USD 1.2bn. That answers the 10-15 open question on the ~USD 1.21bn total. Primary: https://www.occ.gov/news-issuances/news-releases/2026/nr-occ-2026-89.html (crediting language not re-read in this cycle).
  - American Express USD 350m OCC/Fed AML penalty: dated 2026-10-09. Outside window and not previously logged. Flag for a future roundup only.
  - Fideuram / Intesa Sanpaolo EUR 95m AI-voice impersonation: logged 09-30 to 10-07. Biometric Update re-reported it on 10-15.
  - identifAI USD 40bn deepfake report: logged 10-14. Still circulating (cfotech, securitybrief).
  - Serasa Experian "golpe do sosia" (2.86m identity-fraud attempts in H1 2026, +32.9%): Serasa release dated early September 2026. CiberLATAM re-reported it on 10-15. Outside window. Worth a future post if a fresh hook appears.
  - Cifas H1 2026 (unauthorised SIM swap +402%): August. Rejected 10-05 and 10-12.
  - Finland/Bulgaria EUDI oversight: logged 10-01. Poland wallet testing: no primary found.
  - MyCheck: logged 10-14, update noted 10-15.
  - ROC joins AVPA (10-15): vendor membership news.
  - EBA chair Michaud speech at Payments Tomorrow, Paris (reported 10-15, on PSD3/PSR timing and APP fraud): only a Dutch crypto-news secondary was found and no EBA primary. Not counted. PSD3/PSR "December 2026 or January 2027" is consistent with the 10-13 delta.
  - No in-window material found for AMLA (beyond the 10-01 RTS), FATF, FCA/PSR APP fraud, NIST/iBeta, OpenID4VP/ZKP, analyst orchestration coverage, onboarding benchmarks, MiCA/Travel Rule enforcement, or LATAM regulators (CNBV, BCB, Superfinanciera).

## Override-worthy this cycle

1. **FIDO Alliance Passkey Index 2026 (2026-10-15): 36% of successful sign-ins now use a passkey, up from 26% in 2025. Passkey sign-ins succeed 93% of the time vs 78% for traditional MFA. Data comes from 15 services, including three banks: Abanca, Banesco and JPMorgan Chase.** Account: company /. Angle: "MFA fails 1 in 5 sign-ins. Passkeys fail 1 in 14. The friction argument against phishing-resistant auth just flipped. Now the hard part is recovery and the channels passkeys don't cover."
2. **Germany's Bundestag passed the Digital Identities Act (DIdG) on 2026-10-15. d-you launches 2027-01-02. No published amendment addresses the banks' liability or KYC-evidence demands from 10-13.** Account: / company. Angle: "Germany has its wallet law. German banks still don't know who pays when a wallet authentication goes wrong. 78 days to go."

## New findings

### Pillar 1: Banking & Payments

(no new material in window. See notes for American Express (out of window) and the BofA penalty-crediting clarification.)

### Pillar 2: Identity orchestration

(no new material in window. Workday / C1.ai logged 10-14.)

### Pillar 3: EUDI / eIDAS2

- **The Bundestag passed the Digital Identities Act (DIdG), Germany's legal basis for the d-you EUDI wallet, on 2026-10-15 (2nd/3rd reading). CDU/CSU and SPD voted for it; AfD, Greens and Die Linke voted against. d-you is due to launch on 2027-01-02.** This resolves the 10-15 watch item.
  - **Documents:** bill 21/7408; committee recommendation 21/8617. Green and Left resolution motions (21/8624, 21/8625) were rejected.
  - **Resolution passed with the law:** the government must deliver the pseudonymity function "if not at launch, then as soon as possible afterward", because it is required by directly applicable EU law. So d-you may launch with full-name identification only.
  - **Criticism (netzpolitik.org, 10-15):** there is no public register showing which relying parties may request which data, and data minimisation is left as a GDPR "appeal to companies" rather than enforced by prior authorisation. Only ID-card functions launch first; driving licence and other credentials follow later.
  - **Banks:** the Bundestag text mentions banking and payments only as a use case. None of the sources read (Bundestag, ID Tech Wire, netzpolitik) mentions the Deutsche Kreditwirtschaft demands logged 10-14 (wallet-provider liability, wallet data as sufficient KYC evidence, fraud-data access, a right to block vulnerable wallets).

  **Why it matters:** the EU's largest banking market now has a wallet law and a launch date, but the relying-party questions banks raised two days earlier (liability, evidence, fraud signals) are not visibly answered in the statute. That pushes them into implementing regulations, scheme rules and the bank's own controls, which is the orchestration layer. The pseudonymity delay and the missing relying-party register also matter for the privacy/ZKP pillar. At launch, relying parties may receive more identity data than the use case needs.
  - Source (primary): https://www.bundestag.de/dokumente/textarchiv/2026/kw42-de-digitale-identitaeten-gesetz-1223586
  - Source: https://idtechwire.com/bundestag-passes-germanys-eudi-wallet-law-adding-biometric-photo-opt-out/
  - Source: https://netzpolitik.org/2026/digitale-identitaetengesetz-verabschiedet-schwuppdiwupp-die-digitale-brieftasche-kommt/
  - Date: 2026-10-15
  - **Drafting cautions:** the committee recommendation (21/8617) and final text were not read. Say the bank demands "do not appear in the published amendments or coverage", not that they were "rejected". The Bundesrat stage is not confirmed. ID Tech Wire says the government rejected the Bundesrat's request for a consent requirement on regulations. Do not say the law is "in force". Committee-stage amendments (biometric photo opt-out, 12-month attribute deadline, age 13) were logged 10-15. Do not repeat them as new.

### Pillar 4: KYC / AML compliance

(no new material in window. BofA logged 10-15; AmEx out of window. See notes.)

### Pillar 5: Customer onboarding

(no new material in window. The only onboarding benchmarks found were the Fenergo 2025 figures, which are recycled.)

### Pillar 6: Identity verification (IDV)

- **Ping An Digital Bank (Hong Kong) completed an anti-fraud trial in the second cohort of the HKMA's GenAI Sandbox and reported deepfake detection accuracy above 96%. The system, built with OneConnect, assesses customer selfies in real time during verification to flag forged or synthetically manipulated faces.** The bank itself says this reflects test conditions, not independently certified production accuracy.
  **Why it matters:** this is a regulator-supervised deepfake-detection test inside a live bank's onboarding/verification flow, which is rare. The missing pieces matter too. There is no false-positive rate, no attack taxonomy (face swap vs injection) and no methodology. That makes it a useful hook for "a detection-accuracy number without a false-reject rate and an attack model tells a buyer nothing".
  - Source: https://technode.global/2026/10/16/pingan-ai-deepfake-sandbox/
  - Date: 2026-10-15 / 2026-10-16
  - **Drafting cautions:** Hong Kong is not an ICP market, so use it as an illustration only. The HKMA primary release was not read. Technode reports an HKMA "ART" AI framework announced the same day, which was not verified. Do not cite it. Do not compare 96% with any vendor's claims. Never name competitors.

### Pillar 7: Fraud / Deepfakes

(no new material in window. Fideuram and identifAI are re-reports; see notes.)

### Pillar 8: Mobile trust & app security

(no new material in window. Hirudo logged 10-15. A broader 10-15 write-up (SecurityWeek) adds the lure app names (Shopora, 1V1 X, ZoyaTV, KoiShort) and football-themed social ads, but nothing material.)

### Pillar 9: Passwordless / split-key

- **FIDO Alliance published the Passkey Index 2026 on 2026-10-15.**
  - **Usage:** more than one in three successful sign-ins now use a passkey (36%), up from about one in four in 2025 (26%).
  - **Success rate:** passkey sign-ins succeed more often than traditional MFA sign-ins (93% vs 78%).
  - **Speed:** passkeys are nearly three times faster, saving an average of 27 seconds per sign-in.
  - **Outcomes:** every participant that measures phishing reported fewer successful attacks after deploying passkeys. Every participant that provided savings data reported lower SMS OTP costs.
  - **Contributors:** 15 services, up from nine in 2025: Abanca, Amazon, Banesco, JPMorgan Chase, CVS, Google, KDDI, LY Corporation, Mercari, Microsoft, NTT DOCOMO, PayPal, Shopify, TikTok and WhatsApp.
  - **Scale:** a companion FIDO post the same day estimates 7 billion passkeys in use worldwide, up from the 5 billion in the May 2026 State of Passkeys report (logged 05-07).

  **Why it matters:** the 2025 Index (baseline) showed passkeys were available. The 2026 Index shows they are used, and it includes three banks for the first time, one Spanish (Abanca) and one Venezuelan (Banesco). The 93% vs 78% figure directly answers the usual bank objection that stronger authentication costs conversion. The "lower SMS OTP costs" line ties into the OTP-sunset regulators (UAE, Philippines, India) already in the corpus. For Ditto: passkeys solve sign-in. Recovery, high-value transaction signing and device compromise (see Hirudo, 10-15) are where split-key and app-layer protection come in.
  - Source (primary): https://fidoalliance.org/passkey-index-2026/
  - Source (primary): https://fidoalliance.org/7-billion-passkeys-and-counting-the-next-chapter-of-passwordless-authentication/
  - Date: 2026-10-15
  - **Drafting cautions:** the full PDF was not read. Bank-specific figures are not broken out, so do not attribute any number to Abanca, Banesco or JPMorgan Chase individually. Some secondary sites mix up the 2025 and 2026 figures ("36% of accounts enrolled", "93% vs 63%"). Use only the 2026 figures above. The 7bn figure is FIDO's own estimate. Publication in the week before Authenticate 2026 (10-19/21) means more FIDO news is likely next cycle.

### Pillar 10: ZKPs in practice

(no new material in window. See Pillar 3: the DIdG resolution delays pseudonymity, which is relevant to selective disclosure.)

### Pillar 11: Age assurance & privacy attributes

(no new material in window. ROC/AVPA rejected. DIdG age-13 online ID logged 10-15.)

## Open watch items

- **DIdG follow-up:** read committee recommendation 21/8617 for relying-party, liability or KYC language. Confirm whether the Bundesrat must take any further step.
- **Passkey Index 2026 PDF:** check for financial-services breakouts and the methodology.
- **Bank of America:** read the consent orders (violation period, third-party-payment typologies).
- **AMLA simplified-CDD roundtables:** expressions of interest close 2026-10-18.
- **PSD3/PSR OJEU:** next check 2026-10-19. Publication expected December 2026 / January 2027.
- **2026-10-19/21:** Authenticate 2026, Carlsbad.
- **2026-10-20:** Japan My Number Card on Android (target).
- **2026-10-22:** Greek under-15 bill plenary vote; Utah SB73 / Aylo stipulation expiry.
- **2026-10-26:** BCB MED 2.0 / IN BCB 766 Pix changes take full effect.
- **2026-10-26/30:** FATF plenary, Paris.
- **2026-10-29/30:** EUDI Launchpad 2026, Brussels.
- **End-October:** Ofcom over-16 age-assurance rapid assessment.
- **2026-10-31:** ECB SSM-2026-0301 action-plan deadline.
- **2026-11-01:** Turkiye age-token regulation takes effect.
- **2026-11-03:** AMLA central AML/CFT database RTS consultation closes.
- **Early November:** CNBV Anexo 71 biometric compliance deadline.
- **2026-11-09:** Apple Cash reload ID check goes live.
- **2026-11-18:** EUDI ARF Iteration 6 closes.
- **2026-12-24:** EUDI wallet-availability deadline (69 days).
- **2027-01-02:** d-you launch.
- **Workday / C1.ai:** close expected by 2027-01-31.
- **MyCheck:** launch date and Dutch government response.
