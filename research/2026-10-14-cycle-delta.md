# Cycle Delta -- 2026-10-14

Window: 2026-10-12 -> 2026-10-14 (last 48 hours)

## Provenance and integrity notes

- Brand brief, competitors list and all 11 pillar guides were fetched from the worker. Deduplication was checked by keyword against the baseline and every delta from 2026-08-01 to 2026-10-13.
- **The 2026-10-13 delta on the worker is a thin version.** It was written straight to GitHub while the worker was blocked and has no source URLs for most items. A fuller local draft of the same cycle (Turkiye, Greece, KakaoBank, Denmark, with sources) existed but was not the one stored. Nothing from 10-13 is repeated here.
- This file is ASCII-only to avoid the double-encoding issue on the worker PUT path (see the 10-13 notes).
- **Checked and rejected:**
  - FIDO Credential Exchange Protocol (CXP/CXF) "published 10-14": search engines mis-date the original 2024 draft. Not new.
  - Intercede MyID Authenticate and SecuGen FIDO2 key (10-12): logged and rejected 10-13.
  - Ofcom Use of Age Assurance Report 2026: already in the corpus.
  - Aylo backing Apple's device-based age model (Biometric Update, 10-07): outside window.
  - Twyn iBeta Level 2 PAD (early October): date not confirmed in window, and it is vendor news.
  - Brivas v. Match Group liveness patent suit: date not confirmed, off-ICP.
  - OFAC SDN designation of the International Criminal Court (10-12): sanctions politics, not identity or KYC process.
  - AMLA final CDD RTS: logged 10-01.
  - CNBV Anexo 71: no new circular. The deadline is already a watch item.
  - Hopae joins FIDO Alliance (10-13), BIO-key Middle East deal, Apple HomeView, Police Scotland LFR, Philippines PSA offline eKYC: vendor membership news or off-ICP.
  - No in-window material found for PSD3/PSR OJEU, EBA, FATF, FinCEN, UK APP fraud, mobile malware, SIM swap or LATAM regulators.

## Override-worthy this cycle

1. **Germany's banks say they will not take the EUDI wallet on trust. Ahead of the Bundestag's final vote on the wallet law (DIdG, 2nd/3rd reading 2026-10-15), the Deutsche Kreditwirtschaft demanded liability rules that make wallet providers prove each authentication ran correctly, plus a right to block wallets with known vulnerabilities.** Account: / company. Angle: "Banks aren't asking whether the wallet works. They're asking who pays when it doesn't. That liability gap is an orchestration problem, and it has to close before 2 January."
2. **Dutch banks and insurers are building their own eIDAS2-aligned identity wallet, MyCheck (ABN AMRO, Rabobank, ASN Bank, Achmea, KPN, Deloitte).** Account: company /. Angle: "The EU expected banks to accept wallets. In the Netherlands, they decided to issue one."
3. **Workday is buying C1.ai, an identity-governance platform for "people and agents".** Account:. Angle: "Identity governance just moved into the HR system of record. Agents now get onboarded, promoted and offboarded like staff."

## New findings

### Pillar 1: Banking & Payments

(no new material in window. For the German banking lobby's position on the EUDI wallet, see Pillar 3.)

### Pillar 2: Identity orchestration

- **Workday signed a definitive agreement on 2026-10-13 to acquire C1.ai, which describes itself as an agentic identity platform for people and agents. C1.ai governs access for employees and AI agents across email, CRM, code repositories, finance tools and cloud infrastructure.** Workday plans to connect it to its "Agent System of Record", so that access is granted, changed and revoked automatically when people join, change roles or leave, and the same lifecycle applies to agents. Closing is expected in Workday's fiscal Q4 2027 (ending 2027-01-31). No price was disclosed.
  **Why it matters:** this is another identity-platform consolidation, and this time the buyer is an HR/ERP system of record, not a security vendor. The pitch is one lifecycle for humans and agents. That is the same "orchestrate, don't bolt on" argument Ditto makes, applied to workforce identity. Use it as a market signal. It is not Ditto's CIAM lane.
  - Source (primary): https://newsroom.workday.com/2026-10-13-Workday-to-Acquire-C1-ai%2C-a-Leading-Agentic-Identity-Platform-for-People-and-Agents
  - Source: https://idtechwire.com/workday-agrees-to-acquire-c1-ai-for-human-and-ai-agent-identity-governance/
  - Date: 2026-10-13
  - **Drafting cautions:** this is workforce IGA, not customer identity. Do not frame it as an IDV or CIAM deal. The deal has not closed.

- **SBI Holdings (Japan) and KB Kookmin Card (South Korea), with SBI Everspin and Everspin, announced cross-border trials of AI-agent identity on 2026-10-13. They use a "KYA (Know Your Agent) Trust Gateway" that validates an agent's credentials before connecting it to another organisation's services.** Phase 1 lets Japanese AI agents access Korean services. Later phases add user-delegated authority and then cross-border stablecoin payments.
  **Why it matters:** this is the first bank-group KYA trial in the corpus that crosses a border. Earlier KYA items (Mastercard Agent Pay/Skyfire, 10-02 delta) were single-network. Agent identity is becoming an inter-institution trust problem, which means credential exchange and orchestration, not a single vendor's score.
  - Source: https://idtechwire.com/sbi-and-kb-kookmin-card-plan-cross-border-ai-agent-identity-trials/
  - Date: 2026-10-13
  - **Drafting cautions:** this is an announced trial with no live results. The SBI press release was not read directly.

### Pillar 3: EUDI / eIDAS2

- **German banking associations (Deutsche Kreditwirtschaft, DK) set out their demands on the d-you EUDI wallet on 2026-10-13, as the Bundestag prepares to pass the Digital Identities Act (DIdG). Second and third readings are scheduled for 2026-10-15.**
  - **Liability:** the wallet provider must be able to prove that an authentication ran properly, was correctly logged and was not affected by wallet errors.
  - **KYC evidence:** the law should state that storing the data the wallet provides is enough, and that "a copy of an ID is neither required nor technically feasible".
  - **Fraud data:** banks want a legal right to standardised protocols, transaction data, wallet-provider details and risk signals for fraud investigations.
  - **No forced acceptance:** they reject any obligation to accept third-party wallets or put payment cards into them without a contract.
  - **Security veto:** banks want to be able to reject or temporarily block wallets with known vulnerabilities.

  **Why it matters:** this is the relying-party view from the EU's largest banking market, 71 days before the 12-24 wallet deadline and ahead of d-you's 2027-01-02 launch. Banks are not resisting the wallet. They are asking for evidence, liability allocation and risk signals, which is exactly the layer between wallet and bank that orchestration covers. It also follows the critical Bundestag hearing logged on 10-09.
  - Source: https://t3n.de/news/digitaler-ausweis-auf-dem-smartphone-was-banken-an-der-d-you-wallet-kritisieren-1767990/
  - Source (legislative status): https://www.bundestag.de/dokumente/textarchiv/2026/kw42-de-digitale-identitaeten-gesetz-1223586
  - Date: 2026-10-13
  - **Drafting cautions:** the DK position paper itself was not read. Quotes are via t3n (German, translated). Check the outcome of the 10-15 vote before posting. The law may pass with or without these changes.

- **A Dutch coalition of ABN AMRO, Rabobank, ASN Bank, insurer Achmea, telco KPN and Deloitte is developing MyCheck, a free digital identity wallet aligned with eIDAS2. Insurers A.S.R. and Nationale-Nederlanden are named as intended partners.** It covers login, contract signing, sharing verified data to cut form-filling, and age checks that do not reveal name, address or date of birth. No launch date has been given.
  **Why it matters:** banks are moving from relying party to issuer and operator. This is a private, bank-led wallet in the same market where itsme is replacing iDIN, which is due to complete by end-2027. For EUDI positioning, the Netherlands now has competing bank-led schemes alongside the state wallet, and relying parties will have to accept several. That is the multi-wallet orchestration case in one country.
  - Source: https://idtechwire.com/dutch-banks-and-insurers-develop-mycheck-digital-identity-wallet/
  - Date: 2026-10-13
  - **Drafting cautions:** the underlying ABN AMRO press release was not found or read. "Free" and the partner list come from the secondary source. Do not say MyCheck is a certified EUDI wallet. It is "aligned with" eIDAS2.

### Pillar 4: KYC / AML compliance

(no new material in window)

### Pillar 5: Customer onboarding

(no new material in window. See Pillar 6 for South Korea's state mobile ID moving into four major bank apps.)

### Pillar 6: Identity verification (IDV)

- **From 2026-10-14, South Korea's government mobile ID is available inside the apps of four major banks: Shinhan, Woori, Hana and IBK. Six private providers already offered it, including Samsung and Naver.** It covers five credential types: resident registration card, driver's licence, foreign resident card, veterans card and disability card. Credentials are issued by NFC tap of the physical card or in a branch. The Ministry of the Interior and Safety says it will keep adding channels.
  **Why it matters:** a state-issued, chip-anchored credential becomes something a bank app can present and verify, instead of a photo of a card. This follows Japan's FSA push to IC-chip verification (10-12 delta) as a second Asian G20 example of "verify the credential, not the image". Korea is not an ICP market, so use it as an illustration only.
  - Source: https://idtechwire.com/south-korea-opens-government-mobile-ids-to-four-more-bank-apps/
  - Date: 2026-10-13 (announced); effective 2026-10-14
  - **Drafting cautions:** the ministry statement was not read directly. Shinhan was in the 10-08 breach story. Do not link the two.

### Pillar 7: Fraud / Deepfakes

- **identifAI published its first deepfake fraud report on 2026-10-13. It estimates deepfake-enabled financial fraud at USD 40bn a year.** Video synthesis accounts for 42.7% of observed cases and voice cloning for 21.9%. The US accounts for 34.1% of incidents. It says synthetic media causes about 1 in 100 identity-verification check failures globally, and that X (42.1%) and LinkedIn (14.5%) are the main sources of executive video and audio used to train the fakes. It cites a case of deepfakes plus face morphing being used to open 46 fraudulent accounts at ABN AMRO.
  **Why it matters:** "1 in 100 IDV failures" and "morphing used to open 46 accounts at a named EU bank" are onboarding-layer data points, not CEO-fraud anecdotes. The LinkedIn share is a ready-made hook for a LinkedIn post.
  - Source: https://securityboulevard.com/2026/10/report-deepfakes-are-driving-40b-of-fraudulent-transactions/
  - Date: 2026-10-13
  - **Drafting cautions:** this is a vendor report with undisclosed methodology. Attribute every number to identifAI. The ABN AMRO case has no date or primary source in the coverage. Do not use it until it is independently confirmed. The Hong Kong USD 25.6m case is from 2024. Do not present it as new.

### Pillar 8: Mobile trust & app security

(no new material in window. The Anatsa PDF-reader dropper on Google Play was reported 10-09, outside the window.)

### Pillar 9: Passwordless / split-key

- **HID joined the FIDO Alliance Board of Directors on 2026-10-14. Sean Dyon (VP, Authentication Business Unit) is the board delegate.** The announcement cites research saying 93% of organisations are at some stage of passkey adoption and 65% report high or expert familiarity. It frames the next phase as lifecycle management, recovery and physical-plus-digital integration.
  **Why it matters:** a minor governance item, but the stated board priority, recovery and lifecycle, is the "last 40%" this pillar argues FIDO left unsolved. It can support a recovery-flow post ahead of Authenticate 2026 (10-19/21).
  - Source: https://securitybrief.com.au/story/hid-joins-fido-alliance-board-as-passkey-use-grows
  - Date: 2026-10-14
  - **Drafting cautions:** the source of the 93%/65% stats is not named in the coverage. Do not use them without finding the underlying survey.

### Pillar 10: ZKPs in practice

(no new material in window. The Yoti/ConnectID threshold-only age check (Pillar 11) is attribute minimisation by data-source design, not ZKP.)

### Pillar 11: Age assurance & privacy attributes

- **On 2026-10-13, Yoti added ConnectID (bank-backed identity exchange run by Australian Payments Plus) as an age-check route in Australia. Users are redirected to their banking app, and the platform receives only an over-16 or over-18 result, with no name and no date of birth.** It is aimed at Australia's Age-Restricted Material Codes for R18+ games and apps. ConnectID already supports age checks for Snapchat and Reddit, and through Epic Games' Kids Web Services.
  **Why it matters:** this is the third age-assurance design in a week where the relying party gets one bit (Turkiye's state token, Greece's Kids Wallet, now bank-backed in Australia). The source of the attribute differs (state, wallet, bank), but the disclosure model is the same. That supports Ditto's "prove the fact, not the identity" line, and shows banks acting as attribute issuers outside banking.
  - Source: https://www.biometricupdate.com/202610/yoti-adds-connectid-bank-verification-to-its-age-assurance-product-in-australia
  - Date: 2026-10-13
  - **Drafting cautions:** ConnectID's Epic/Steam context was logged 09-09/09-11. The new part is the Yoti integration. "No personal data shared" is the company's claim.

- **The Philippine House of Representatives approved House Bill 11566 (Children's Digital Safety, Protection and Well-Being Act) on third and final reading on 2026-10-13. It restricts under-13s from social media and adds parental-consent and duty-of-care rules for ages 13-17.** The Senate's SMART KIDS Act would go further, to under-18. The government plans to use the PhilSys national ID for automated age checks.
  **Why it matters:** this moves the PhilSys-based age-check idea (logged as a discussion item 09-11) into passed lower-house legislation. It is non-ICP, so count it only toward the global age-assurance pattern.
  - Source: https://idtechwire.com/philippine-house-approves-under-13-social-media-restrictions/
  - Date: 2026-10-13
  - **Drafting cautions:** this is not law yet. The bill still needs the Senate and the two versions must be reconciled.

## Open watch items

- **2026-10-15:** Bundestag 2nd/3rd reading of DIdG (German EUDI wallet law). Check whether the DK's liability and KYC-evidence asks made it into the text.
- **DHS RIVR-2:** IDV/SMTD applications close 2026-10-16.
- **AMLA simplified-CDD roundtables:** expressions of interest close 2026-10-18.
- **PSD3/PSR OJEU:** next check 2026-10-19. Publication is expected December.
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
- **2026-12-24:** EUDI wallet-availability deadline (71 days).
- **Workday / C1.ai:** close expected by 2027-01-31.
- **MyCheck:** launch date and ABN AMRO primary release.
