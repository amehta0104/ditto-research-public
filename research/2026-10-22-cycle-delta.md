# Cycle Delta -- 2026-10-22

Window: 2026-10-20 -> 2026-10-22 (last 48 hours, Thursday run). The 10-21 delta already covered 10-19 and 10-20, so this cycle focuses on 10-21 and early 10-22.

## Provenance and integrity notes

- Brand brief, competitors list and all 11 pillar guides were fetched from the worker. Deduplication was checked by keyword against the 2026-05-06 baseline and every delta on the worker, through 2026-10-21.
- This file is ASCII-only to avoid the double-encoding issue on the worker PUT path.
- This is a thin cycle. Money20/20 USA closed 10-21 and Authenticate 2026 day 3 produced no new FIDO release. Two findings are counted.
- **Checked and rejected:**
  - World ID for banking and finance (logged 10-19), Transmit Security CEO / Agentic Trust (logged 10-21), identifAI USD 40bn (logged 10-14), Fideuram (logged 09-30 to 10-07), Shufti Identity Fraud Report (logged 10-07), Hirudo (logged 10-15), YuanKong (rejected 10-19): all re-surfaced. Not counted.
  - Proof x401 agent-authorisation protocol: Biometric Update (10-20) covered its Money20/20 demo, but x401 launched on 2026-06-26 (Help Net Security). Outside window.
  - FinCEN mDL CIP FAQ: dated 2026-09-08. Outside window.
  - French authorities' (Treasury, AMF, Banque de France, ACPR) joint answer to the Commission's MiCA review consultation, reportedly published 10-21: the AMF primary could not be found. Not counted. Re-check in the 10-23 cycle.
  - ID Tech Digest 10-21: First Advantage + ID.me FCRA identity check (hiring), Kforce + 1Kosmos (consultant verification; 1Kosmos is a direct competitor), VA / Deloitte USD 199.9m identity task order, South Africa grant biometrics, FaceTec law-enforcement ID barcodes, GCheck worker wallet. All off-ICP (employment screening, US government, welfare). Not counted.
  - Intellicheck + Agility Credit (ID checks for dealership credit pulls) and COOP Jednota + Innovatrics (57,000 shoppers age-verified for unstaffed stores): vendor announcements, and no primary was read. Not counted.
  - FCA AI supervision tools for the 60,000 professional-services AML firms coming in 2028: no in-window date could be confirmed. Not counted.
  - Brazil Civil Police operation against a bank-fraud ring (BRL 1.27m, 114 reports, about 2,700 phone lines; Prensa Latina 10-20): a single police operation with no identity-control angle in the coverage. Not counted.
  - Greek under-15 bill: the plenary vote is today (10-22) and no result had been reported at scan time. The figure of up to EUR 48bn in fines (iefimerida) could not be dated. Watch item.
  - No in-window material found for PSD3/PSR OJEU, EBA/ECB/DORA, FATF, FCA/PSR APP fraud, NIST/iBeta, onboarding benchmarks, MiCA/Travel Rule enforcement, EU age-verification app, Ofcom (the October industry bulletin page returned 403 and its items could not be dated), OpenID4VP/mDL bank pilots, or LATAM regulators (CNBV, BCB, Superfinanciera, CMF). The BCB Pix MED 80-day change is already a watch item (10-26).

## Override-worthy this cycle

(none)

## New findings

### Pillar 1: Banking & Payments

(no new material in window.)

### Pillar 2: Identity orchestration

(no new material in window. Transmit Security / Agentic Trust was logged 10-21.)

### Pillar 3: EUDI / eIDAS2

(no new material in window. EPC SCARLET was logged 10-21. Hopae sandbox additions (10-20) are vendor news; see the 10-21 notes.)

### Pillar 4: KYC / AML compliance

- **AMLA and OLAF signed a Working Arrangement on 2026-10-21 to cooperate and exchange information against money laundering, terrorist financing, fraud and corruption.** The framework covers operational and strategic information: criminal patterns, emerging trends, risk indicators and crime-prevention methods. OLAF will contribute anti-fraud expertise to joint analyses coordinated by AMLA. Information from those analyses can be cross-checked against OLAF data, including financial intelligence on banking and cash transactions relevant to fraud against EU funds. The legal bases are Article 94 of the AMLA Regulation and OLAF's own regulation. AMLA Chair Bruna Szego: "Criminals do not respect institutional boundaries, and neither can our response." OLAF Director-General Petr Klement called it "an important step towards stronger day-to-day cooperation between AMLA, OLAF and the Financial Intelligence Units of Member States."

  **Why it matters:** AMLA is building its intelligence plumbing before direct supervision starts. Joint analyses that combine FIU and OLAF data mean that red flags spotted at one obliged entity can be matched against patterns across the EU. Banks' onboarding and monitoring records become inputs to EU-level analysis, so the quality and traceability of identity evidence ("who exactly was verified, how, and when") matters beyond the bank's own file. This is a modest, institutional item: useful as supporting evidence in an AMLA-readiness post, not as a headline.
  - Source (primary): https://anti-fraud.ec.europa.eu/media-corner/news/amla-and-olaf-strengthen-cooperation-fight-against-financial-crime-2026-10-21_en
  - Date: 2026-10-21
  - **Drafting cautions:** this is a cooperation arrangement, not a new obligation on banks. Do not imply that it changes CDD requirements or that OLAF supervises obliged entities.

### Pillar 5: Customer onboarding

(no new material in window.)

### Pillar 6: Identity verification (IDV)

(no new material in window. The ID Tech Digest 10-21 IDV deals are off-ICP; see notes.)

### Pillar 7: Fraud / Deepfakes

(no new material in window. Everything that surfaced was a re-report; see notes.)

### Pillar 8: Mobile trust & app security

(no new material in window. For SIM-based number verification as an SMS-OTP replacement, see Pillar 9.)

### Pillar 9: Passwordless / split-key

- **KDDI commercially launched "Number Verification v2" (NVv2) on 2026-10-21. It is integrated into Google Firebase Phone Number Verification.** NVv2 verifies a user's phone number against the carrier's SIM and contract records in one step. No SMS one-time passcode is sent or typed. KDDI says this removes the attack routes used to steal SMS codes, such as real-time phishing, and reduces drop-off at authentication. The API follows the GSMA Open Gateway and Linux Foundation CAMARA specifications; KDDI has taken part in that standardisation since 2022. KDDI also names AI agents registering accounts and making payments as a use case. Firebase Senior Product Manager Micah Baker said the collaboration "allows Firebase to guide developers to better security, better end user experience, and more use cases for phone number verification."

  **Why it matters:** a major carrier plus Google's developer platform makes "SMS OTP without the SMS" a default option for any app developer, not a bespoke telco integration. That shifts the baseline for possession checks. It also concentrates trust in the SIM record, which makes SIM-swap and port-out controls more important, not less. A carrier number check proves control of a SIM, not who the person is or whether the device is clean. For banks, it is a better possession factor, not a replacement for phishing-resistant, device-bound authentication or identity proofing. This is useful for the "OTP is dying, what replaces it" argument.
  - Source (primary): https://newsroom.kddi.com/english/news/detail/kddi_nr-1204_4771.html
  - Source: https://idtechwire.com/kddi-launches-sim-based-number-verification-on-google-firebase/
  - Date: 2026-10-21
  - **Drafting cautions:** the launch is for KDDI (au) subscribers in Japan. Do not imply global carrier coverage through Firebase from this release. Pricing and adoption figures were not disclosed. Do not call it phishing-proof: it removes the SMS-code interception route only.

### Pillar 10: ZKPs in practice

(no new material in window.)

### Pillar 11: Age assurance & privacy attributes

(no new material in window. The Greek under-15 plenary vote is today; the result had not been reported at scan time.)

## Open watch items

- **2026-10-22:** Greek under-15 bill plenary vote (KidsWallet over-15 attestation for adults); Utah SB73 / Aylo stipulation expiry. Check results in the 10-23 cycle.
- **French MiCA review answer (AMF / Treasury / BdF / ACPR, reportedly 10-21):** find the primary and check it for AML/Travel Rule or CASP onboarding positions.
- **Ofcom October 2026 industry bulletin:** the page returned 403. Read it for dated enforcement actions and age-assurance guidance updates.
- **FIDO CMRA and Verifier Identification Framework:** publication expected "in coming weeks".
- **EPC SCARLET:** read the EPC primary for verbatim text and participation terms.
- **YuanKong RAT:** Star Labs primary still not found.
- **NetChoice/CCIA:** en banc or certiorari filings on Florida HB 3 and Georgia SB 351.
- **DIdG follow-up:** committee recommendation 21/8617. Link it to SCARLET liability.
- **Passkey Index 2026 PDF:** financial-services breakouts.
- **Bank of America:** consent orders.
- **AMLA simplified-CDD roundtables:** watch for the participant list or roundtable dates.
- **PSD3/PSR OJEU:** next check 10-26.
- **2026-10-26:** BCB MED 2.0 / IN BCB 766 Pix changes take full effect.
- **2026-10-26/30:** FATF plenary, Paris.
- **2026-10-29/30:** EUDI Launchpad 2026, Brussels.
- **2026-10-30:** Microsoft Entra telephony-provider option for SMS/voice MFA (Microsoft-provided SMS ends 2027-02-01).
- **End-October:** Ofcom over-16 age-assurance rapid assessment; Romania EUDI sandbox target (10-31).
- **2026-10-31:** ECB SSM-2026-0301 action-plan deadline.
- **2026-11-01:** Turkiye age-token regulation takes effect.
- **2026-11-03:** AMLA central AML/CFT database RTS consultation closes.
- **Early November:** CNBV Anexo 71 biometric compliance deadline; BCB "Circuito Pix" session on Resolution 587 operations.
- **2026-11-09:** Apple Cash reload ID check goes live.
- **2026-11-16:** ACCS-IEEE event on New York age-assurance regulations.
- **2026-11-18:** EUDI ARF Iteration 6 closes.
- **2026-12-24:** EUDI wallet-availability deadline (63 days).
- **2027-01-02:** d-you launch.
- **Workday / C1.ai:** close expected by 2027-01-31.
- **Summer 2027:** EPC SCARLET open consultation. **December 2027:** first SCARLET rulebook.
- **MyCheck:** launch date and Dutch government response.
