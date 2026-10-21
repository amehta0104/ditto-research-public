# Cycle Delta -- 2026-10-21

Window: 2026-10-19 -> 2026-10-21 (last 48 hours, Wednesday run). The 10-20 delta already scanned 10-19 and early 10-20, so this cycle focuses on 10-20 and 10-21.

## Provenance and integrity notes

- Brand brief, competitors list and all 11 pillar guides were fetched from the worker. Deduplication was checked by keyword against the 2026-05-06 baseline and every delta on the worker, through 2026-10-20.
- This file is ASCII-only to avoid the double-encoding issue on the worker PUT path.
- Authenticate 2026 day 2 (10-20) produced the FIDO digital-credentials news that the 10-20 cycle expected. The EPC SCARLET release (dated 10-19, Brussels) was missed by the 10-20 cycle. It is still inside today's window, so it is counted here.
- **Checked and rejected:**
  - FIDO "7 billion passkeys" and Passkey Index 2026: logged 10-16. Biometric Update re-reported them on 10-20 alongside a "FIDO Passkey Rubric" tool. No new financial-services breakout.
  - GhostBat Android malware (Cyble, 60 Indian banking/UPI apps, "Ghost Overlay" PIN capture): published 2026-10-16. Outside window and not logged earlier. Noted for the drafter as an older item only. Primary: https://cyble.com/blog/ghostx-forged-in-transit-licensed-to-deceive/
  - Mexico "despojo biometrico" ring (fake bank-prize deliveries used to photograph victims' faces and register their banking apps on other devices; about MXN 18m, 67 complaints; FGJ CDMX): dated 2026-08-17. Outside window. Strong material if a fresh hook appears.
  - Condusef Edomex "identity and phone theft up 20%" (El Independiente, 10-20): the figure could not be traced to a Condusef primary. Not counted.
  - Expansion (10-09) Mexico bank-fraud claims, MXN 11,213m in H1 2026: outside window.
  - Hopae adds d-you and AltID to its EUDI sandbox (fintech.global, 10-20): vendor product news. Not counted.
  - IDENTOS PolicyArc (agent authorisation), Visa/BILL/Billtrust agent invoice-payment pilot, DirectTrust/GLEIF vLEI, Ethiopia Fayda bank fees: these surfaced in the ID Tech digest (10-20). They are off-ICP, or their dates could not be confirmed. Not counted.
  - ISO/IEC PWI 27566-4 age-assurance interoperability and Google age inference in Malaysia: both dated 10-14. Outside window.
  - Greek under-15 bill: TechTimes (10-20) previews the 10-22 plenary vote. It is already a watch item.
  - GSMA Open Gateway Portugal launch (10-20; MEO, NOS, Vodafone, SIM-swap APIs): an event page only, with no published operator details. Not counted.
  - OFAC Federal Register notices (10-20): routine narcotics designations. Off-pillar.
  - No in-window material found for PSD3/PSR OJEU, EBA/ECB/DORA, AMLA, FATF, FCA/PSR APP fraud, NIST/iBeta, onboarding benchmarks, MiCA/Travel Rule enforcement, EU age-verification app, Ofcom, Biometrics Institute Congress outputs, or LATAM regulators (CNBV, BCB, Superfinanciera, CMF).

## Override-worthy this cycle

1. **The European Payments Council launched SCARLET ("Strong Customer Authentication Acceptance Rulebook and Liability Framework for EUDIW Transactions") on 2026-10-19. It will set common rules, including liability, for 3,000+ PSPs accepting EUDI wallets for SCA. The first rulebook is not due until December 2027, the same month private-sector wallet acceptance becomes mandatory.** Account: / company. Angle: "Europe's banks will get their EUDI wallet liability rulebook in the same month they're legally required to accept the wallet. If you're waiting for the rules before you design the integration, you'll be designing it under deadline."

## New findings

### Pillar 1: Banking & Payments

(See Pillar 3 for EPC SCARLET, which is as much a payments item as an EUDI one.)

### Pillar 2: Identity orchestration

- **Transmit Security changed CEO and launched "Agentic Trust" (2026-10-19).** Founder Mickey Boodaei steps down after 12 years and becomes chairman, focusing on product and AI-agent security. Matt Thompson replaces him. Thompson is a former Socure president and CCO and an ID.me co-founder, and has also worked at Capital One and IDEMIA. Agentic Trust detects agent traffic, classifies the agent software, investigates what it can do, and then governs it. Enterprises can allow an agent, limit it, hold risky actions for the customer's approval, or stop it, using scoped, time-limited permissions. The pitch is that agents now open accounts, move funds and complete purchases with valid credentials, which gets them past traditional controls. Boodaei: "AI assistants are changing how people interact with banks, retailers, insurers and other businesses."

  **Why it matters:** this is the third major identity vendor in a week to package "agent governance" for banks, after World AgentKit (10-18) and the Mastercard Know-Your-Agent sessions. The category is settling on a pattern: detect the agent, bind it to a verified human, and gate high-risk actions with step-up approval. That is an orchestration-layer problem, not a point-product one. The leadership hire also matters. A Socure/ID.me IDV operator now runs a CIAM/fraud vendor, which points to more convergence between verification and authentication.
  - Source: https://www.calcalistech.com/ctechnews/article/bkb1s1e3ze
  - Source: https://runtimewire.com/article/boodaei-transmit-security-ceo-transition-thompson
  - Date: 2026-10-19
  - **Drafting cautions:** this is a competitor (Transmit Security is on the adjacent watch list). Never name it in a post. Use it only as evidence of the category pattern. No customers or funding were announced with the launch. The USD 543m / USD 2.2bn figures refer to the 2021 round, not to this news.

### Pillar 3: EUDI / eIDAS2

- **EPC launches SCARLET: a rulebook and liability framework for EUDI wallets used in payment SCA (press release, Brussels, 2026-10-19).** SCARLET stands for "Strong Customer Authentication Acceptance Rulebook and Liability Framework for EUDIW Transactions". It will define contractual responsibilities, operating rules and technical requirements for PSPs and wallet providers when customers use an EUDI wallet for strong customer authentication, covering payment-account access and payment initiation. It will also set a liability framework for disputed wallet-authenticated transactions. The EPC board approved development on 2026-09-24. An open consultation is planned for summer 2027, and the first rulebook is targeted for December 2027. It is intended for "the more than 3,000 payment service providers and 27 or more EU Digital Identity Wallet providers expected to operate across the EU and EEA". The stated aim is to stop participants developing incompatible approaches to wallet acceptance under eIDAS 2 (Regulation (EU) 2024/1183).

  **Why it matters:** this is the first scheme-level body to say openly that EUDI wallet SCA needs a liability allocation between banks and wallet providers. That is the same gap the German DK raised over DIdG liability (logged 10-14). The timing is the story. The rulebook lands in December 2027, the same month the eIDAS 2 private-sector acceptance obligation applies (2027-12-24). Banks that wait for SCARLET will have no runway. Those building now will need an orchestration layer that can absorb rule changes after the consultation. Wallet acceptance for SCA also puts EUDI directly into the authentication stack, not just onboarding.
  - Source (primary): https://www.europeanpaymentscouncil.eu/document-library/press-releases/press-release-epc-launches-scarlet-initiative-supporting-eu-digital
  - Source (primary, PDF): https://www.europeanpaymentscouncil.eu/sites/default/files/kb/file/2026-10/EPC267-26%20v1.0%20SCARLET%20press%20release.pdf
  - Source: https://idtechwire.com/epc-launches-scarlet-work-on-digital-wallet-payment-authentication/
  - Source: https://www.finextra.com/newsarticle/48606/epc-to-create-eu-digital-identity-wallet-framework-for-psps
  - Date: 2026-10-19
  - **Drafting cautions:** the EPC primary pages returned 403 and the PDF could not be parsed. Details come from ID Tech Wire and fintech.garden, which agree with each other and with the search snippets of the EPC page. Re-check the primary before quoting it verbatim. SCARLET is a scheme rulebook, not law, and participation terms are not yet known. The 2027-12-24 acceptance date comes from secondary coverage of eIDAS 2. Present it as "end of 2027" unless it is checked against the regulation text.

### Pillar 4: KYC / AML compliance

(no new material in window.)

### Pillar 5: Customer onboarding

(no new material in window.)

### Pillar 6: Identity verification (IDV)

(no new material in window.)

### Pillar 7: Fraud / Deepfakes

(no new material in window. INTERPOL deepfake campaign logged 10-20.)

### Pillar 8: Mobile trust & app security

(no new material in window. GhostBat (10-16) and the Mexico biometric-capture ring (08-17) are outside the window; see notes.)

### Pillar 9: Passwordless / split-key

- **FIDO Alliance opens its digital-wallet certification documents and launches an External Advisory Forum (2026-10-20, Authenticate 2026 day 2).** FIDO will make two working documents public "in coming weeks". The first is the **Credential Manager Reference Architecture (CMRA)**: functional, security and interoperability requirements for digital wallets holding national ID, payment, workforce and travel credentials. It is the foundation of FIDO's Credential Manager Certification Program. The second is the **Verifier Identification Framework**, which lets a wallet show the user verified information about the website or service requesting their data. The new External Advisory Forum is a non-binding channel for issuers, governments, regulators and industry associations to feed into the digital-credentials work and the certification program. FIDO describes the program as four workstreams: wallet certification, scalable verifier identification, credential schemes and specifications, and usability and verifier enablement. Day-2 sessions included Mastercard, PayPal and Microsoft on identity wallets in payment authentication. Andrew Shikiar, FIDO Executive Director and CEO: "The vast potential of digital credentials will only be realized if people, organizations and governments can trust them wherever they're used."

  **Why it matters:** FIDO is moving beyond passkeys into wallet certification and verifier (relying-party) identification. That overlaps with the EUDI certification and relying-party registration regime, but sits outside it. On the same two days, the EPC (SCARLET) and FIDO both moved on "wallet as authenticator for payments". Banks may end up under two overlapping trust frameworks, one regulatory (eIDAS 2 / EUDI) and one industry (FIDO certification). Mapping one onto the other is an orchestration job. Verifier identification also reframes the anti-phishing argument: the wallet authenticates the relying party to the user, not only the user to the bank.
  - Source (primary): https://fidoalliance.org/fido-alliance-moves-to-accelerate-digital-credentials-adoption-at-scale/
  - Source (primary): https://fidoalliance.org/authenticate-2026-day-2-building-the-foundation-of-trust-for-digital-credentials/
  - Source: https://www.morningstar.com/news/business-wire/20261020339447/fido-alliance-moves-to-accelerate-digital-credentials-adoption-at-scale
  - Date: 2026-10-20
  - **Drafting cautions:** the documents are not yet published ("in coming weeks"), so do not describe their contents beyond the summary above. No governments, banks or members are named as Forum participants. The announcement does not mention EUDI or eIDAS. Any EUDI link is our analysis, not FIDO's claim.

### Pillar 10: ZKPs in practice

(no new material in window. FIDO Verifier Identification Framework (Pillar 9) is adjacent to selective-disclosure and relying-party trust.)

### Pillar 11: Age assurance & privacy attributes

(no new material in window. Greek under-15 bill plenary vote is on 10-22.)

## Open watch items

- **FIDO CMRA and Verifier Identification Framework:** publication expected "in coming weeks". Read them for EUDI/ARF alignment and any bank or wallet participants.
- **EPC SCARLET:** read the EPC primary (403 today) for verbatim text and participation terms.
- **2026-10-21:** Authenticate 2026 day 3, Money20/20 USA close, Biometrics Institute Congress day 2. Re-check in the 10-22 cycle.
- **YuanKong RAT:** Star Labs primary still not found.
- **NetChoice/CCIA:** en banc or certiorari filings on Florida HB 3 and Georgia SB 351.
- **DIdG follow-up:** committee recommendation 21/8617 (relying-party, liability, KYC language). Link it to SCARLET liability.
- **Passkey Index 2026 PDF:** financial-services breakouts.
- **Bank of America:** consent orders.
- **AMLA simplified-CDD roundtables:** watch for the participant list or roundtable dates.
- **2026-10-22:** Greek under-15 bill plenary vote; Utah SB73 / Aylo stipulation expiry.
- **PSD3/PSR OJEU:** next check 10-26.
- **2026-10-26:** BCB MED 2.0 / IN BCB 766 Pix changes take full effect.
- **2026-10-26/30:** FATF plenary, Paris.
- **2026-10-29/30:** EUDI Launchpad 2026, Brussels.
- **End-October:** Ofcom over-16 age-assurance rapid assessment; Romania EUDI sandbox target (10-31).
- **2026-10-31:** ECB SSM-2026-0301 action-plan deadline.
- **2026-11-01:** Turkiye age-token regulation takes effect.
- **2026-11-03:** AMLA central AML/CFT database RTS consultation closes.
- **Early November:** CNBV Anexo 71 biometric compliance deadline; BCB "Circuito Pix" session on Resolution 587 operations.
- **2026-11-09:** Apple Cash reload ID check goes live.
- **2026-11-16:** ACCS-IEEE event on New York age-assurance regulations.
- **2026-11-18:** EUDI ARF Iteration 6 closes.
- **2026-12-24:** EUDI wallet-availability deadline (64 days).
- **2027-01-02:** d-you launch.
- **Workday / C1.ai:** close expected by 2027-01-31.
- **Summer 2027:** EPC SCARLET open consultation. **December 2027:** first SCARLET rulebook.
- **MyCheck:** launch date and Dutch government response.
