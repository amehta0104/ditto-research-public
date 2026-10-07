# Cycle Delta — 2026-10-07

Window: 2026-10-05 → 2026-10-07 (last 48 hours, Wednesday run)

## Provenance and integrity notes

- The worker API was reachable. The brand brief, competitors list and all 11 pillar guides were fetched. Deduplication was checked against the full research corpus (111 files, baseline through the 2026-10-06 delta).
- The 10-06 delta covered 10-05 items it found then. This run adds 10-05/10-06 items that delta did not log. Nothing dated 10-07 was indexed at run time.
- **GOV.UK One Login / Ecospend date:** the Contracts Finder award notice is dated 2026-09-22, but the first public coverage was 2026-10-05 (Global Government Finance) and 2026-10-06 (Biometric Update). The corpus does not mention it. It is counted as a 10-05/06 finding. Contracts Finder returned 403, so the notice text was not read directly.
- **Carried in (not counted, primary outside window):**
  1. **Treasury "Operation Economic Outcast" against the A7 Network (2026-10-01).** OFAC designated the Russia-linked A7 shadow-banking network as a significant transnational criminal organisation. FinCEN proposed restrictions on transfers involving its sub-agents and issued alert FIN-2026-Alert007. OFAC followed with a 10-05 alert warning foreign financial institutions that still deal with Iran. No prior delta logged it. It is US/Iran/Russia sanctions context, not core ICP. Source (primary): https://www.fincen.gov/system/files/2026-10/FinCEN-Alert-A7-Network.pdf. Source: http://bankingjournal.aba.com/2026/10/recent-news-from-treasurys-office-of-foreign-assets-control-oct-5/
- **Checked and rejected:**
  - IN Groupe EUDI op-ed (Euronews 10-06): opinion, no new facts.
  - Biometric Update "commercial value around the EUDI Wallet" (10-06): opinion.
  - DigiSign × Innovatrics (minor integration); HectoData passport OCR (Korea, minor); authID $2M deal (humanitarian dedup, off-lane); Cambridge police FR, UK/India airport biometrics, ICE, SSA–Carahsoft (government/border, off-lane); Bermuda digital ID RFQ (minor); Monacoeur heartbeat biometrics (early-stage).
  - HM Treasury payments-regulation consultation closed 10-06: no new output yet.
  - OFAC SDN Federal Register notices (10-06): routine.
  - Already logged: Fideuram, Treasury Dragons/nsKnox, WindRelay, Rokarolla, Shufti index, IDEMIA agentic commerce, AMLA RTS package (10-01), Japan My Number Android, Apple/Google age-check lobbying.
- **PSD3/PSR OJEU:** still no Official Journal notice surfaced. Next check is Monday 2026-10-12.

## Override-worthy this cycle

1. **GOV.UK One Login will let citizens prove identity by logging in to their bank (Ecospend, £4.7M, rollout 2027).** Account: company /. Angle: "The UK government just picked banks as an identity source for 23 million users. Every bank is now an identity provider. Most don't act like one."
2. **Apple Cash will require identity verification for every reload from 2026-11-09, with an mDL in Apple Wallet as the fast path.** Account: company. Angle: "Apple just removed the 'small amounts don't need KYC' exemption, and made a wallet credential the easiest way to clear it."

## New findings

### Pillar 1: Banking & Payments

(no new material in window. See Pillar 5 for Apple Cash / Green Dot Bank.)

### Pillar 2: Identity orchestration

- **Ping Identity 2026 Consumer Survey: only 5% of consumers are comfortable with AI agents taking action even with their approval, and 3% with routine transactions without final approval.**
  - **Trust in identity custodians:** 12% fully trust organisations to manage their identity data, down from 17% in 2025.
  - **Spending caps:** consumers would trust an agent with an average of US$200 for routine purchases. 42% would cap it at $100 or less; 22% would not trust it with any money.
  - **Oversight:** 71% worry an agent could misrepresent their personality, ethics or values. 56% say knowing when AI is used matters more than the fastest result.
  - **Geography:** comfort with AI autonomy is highest in India (70%) and Indonesia (61%) and lowest in Sweden (21%), the Netherlands (19%) and Australia (18%).
  - **Method:** Talker Research, 11,000 consumers in 12 countries (US 2,000; UK 2,000; FR, DE, AU, SG 1,000 each; IN, ID, NL, SE, ES, IT 500 each).
  - **Quote:** Darryl Jones, VP Consumer Segment Strategy: "Consumers are open to AI doing more, but they want a say in how far it can go."

  **Why it matters:** agentic commerce work (Mastercard Agent Pay, IDEMIA agentic tokens, logged 09-30/10-02) assumes users will delegate. This data says they will, but only with scoped, revocable, visible mandates. That is an identity and consent problem, not an AI problem. It pairs with the Fourthline finding (10-06): customers accept friction they understand.
  - Source (primary): https://www.prnewswire.com/news-releases/ping-identity-survey-finds-ai-trust-changes-when-assistance-turns-to-action-302899604.html
  - Source: https://www.biometricupdate.com/202610/consumer-trust-in-autonomous-agents-sinks-following-security-incidents
  - Date: 2026-10-06
  - **Drafting cautions:**
    - Ping Identity is an adjacent competitor. Cite the data, never the vendor in a post.
    - It is a vendor-sponsored survey of stated attitudes. A PR Newswire correction (10-06) changed only a hyperlink, not figures.
    - The "5% with approval" figure is oddly low next to "31% willing to let AI make lower-stakes decisions". Quote exactly as worded, don't paraphrase.

### Pillar 3: EUDI / eIDAS2

(no new material in window. Launchpad 2026 is 10-29/30.)

### Pillar 4: KYC / AML compliance

(no new material in window. The A7 Network action (10-01) is carried in, not counted. AMLA simplified-CDD roundtable expressions of interest close 10-18.)

### Pillar 5: Customer onboarding

- **Green Dot Bank will require identity verification for every Apple Cash reload from 2026-11-09. This removes the previous $500 threshold below which users could add, send or receive money unverified.**
  - **Fast path:** on iOS 27, users in states that support digital driver's licences can tap "Continue with ID in Wallet" to verify with the mDL already in Apple Wallet.
  - **If unverified:** users cannot send, receive or add money. Existing balances can still be spent or moved to a bank.
  - **Stated reason:** "fraud protection and regulatory reasons".
  - **Also announced:** Green Dot "may" add reloads from a bank account or merchant in future.

  **Why it matters:** one of the largest consumer P2P wallets in the US is dropping its low-value KYC exemption. It is making a reusable cryptographic credential the low-friction route through the new check. This is "verify once, reuse trust" shipped by a platform: the credential does the KYC, not a document scan. It also shows the trade-off in the Fourthline data (10-06): a mandatory check is acceptable when the friction is near zero.
  - Source (primary): https://support.apple.com/en-us/109312 (ID in Wallet flow; page updated 2026-09-14)
  - Source: https://www.macrumors.com/2026/10/05/apple-cash-reload-id-check/
  - Source: https://9to5mac.com/2026/10/05/apple-notifies-apple-cash-users-about-two-upcoming-changes/
  - Source: https://idtechwire.com/apple-cash-to-require-identity-verification-before-balance-reloads/
  - Date: 2026-10-05
  - **Drafting cautions:**
    - The 11-09 date and the removal of the $500 threshold come from Green Dot customer emails, as reported by MacRumors/9to5Mac. The Apple Support page does not state them.
    - US-only. Use it as a platform signal, not an ICP case study.
    - Green Dot Bank, not Apple, is the regulated entity.

### Pillar 6: Identity verification (IDV)

- **The UK Government Digital Service has contracted Ecospend (Trustly-owned, FCA-authorised) for £4.7M to add open banking as an identity-verification route in GOV.UK One Login.** Users will prove identity by signing in to their online bank and sharing account information (AIS, not payment initiation).
  - **Scope:** "identity verification, identity validation and fraud risk assessment".
  - **Contract:** awarded via the Open Banking DPS (RM6301), notice dated 2026-09-22, work running to February 2029. Rollout is expected in 2027.
  - **Scale:** One Login serves about 23 million people across 250+ government services.
  - **Context:** Ecospend is already the sole open banking provider to HMRC and NS&I (payments).

  **Why it matters:** the UK's main government identity service is treating the customer's bank as an identity evidence source. Bank-held KYC becomes reusable outside the bank. This supports "verify once, reuse trust". It also raises the question for banks of whether they are passive data sources or identity providers with their own liability and commercial terms. It is the UK counterpart to the EUDI model where banks are both relying parties and attestation issuers. Cross-ref Pillar 2 (orchestration: another verification route to orchestrate) and Pillar 1.
  - Source: https://www.globalgovernmentfinance.com/gds-gov-uk-one-login-ecospend-verification/ (2026-10-05)
  - Source: https://www.biometricupdate.com/202610/uk-adds-open-banking-to-gov-uk-one-login-identity-verification (2026-10-06)
  - Source (primary, not directly read, 403): https://www.contractsfinder.service.gov.uk/notice/a7d36d89-8d8f-4ce3-bea0-8b960e01270e
  - Date: 2026-10-05 (first coverage; contract notice 2026-09-22)
  - **Drafting cautions:**
    - Rollout is 2027. Say "will let", not "lets".
    - No GPG45 confidence level is stated for the open banking route. Do not claim it reaches medium confidence on its own.
    - Use "a UK government identity service partnered with an open banking provider". Ecospend/Trustly are not competitors, but keep the post about the model.

### Pillar 7: Fraud / Deepfakes

(no new material in window. Fideuram and Treasury Dragons/nsKnox remain the standing anchors, already logged.)

### Pillar 8: Mobile trust & app security

(no new material in window. No new named banking-malware family or vendor report dated 10-05 to 10-07.)

### Pillar 9: Passwordless / split-key

- **Bron, a self-custody crypto wallet, launched FaceScan: biometric account recovery for users who lose their passkeys or device, with no ID document or seed phrase required.**
  - **How it works:** it uses iProov Dynamic Liveness and stores an encrypted template only, with no photos or video.
  - **Safeguards:** a mandatory 30-day hold after enrolment before recovery can be used, and an extra two-day delay for accounts whose workspaces have moved at least $100.
  - **Alternative:** "Guardian" recovery via two trusted contacts.
  - **Quote:** founder Dmitry Tokarev: users can "establish that they are the account owner without supplying an identity document or seed phrase".

  **Why it matters:** this is a concrete production example of the pillar's core claim that recovery is where passwordless breaks. A passkey-first product had to bolt on a biometric-plus-time-lock recovery path to stay usable. The time locks admit that biometric recovery alone is an attack surface.
  - Source: https://idtechwire.com/bron-adds-iproov-facescan-recovery-for-self-custody-wallets/
  - Date: 2026-10-06
  - **Drafting cautions:**
    - iProov is a direct competitor. Never name it; describe it as "a liveness-based recovery flow".
    - The only source is trade press; no Bron primary release was found. Treat it as a small-company example, not market evidence.

### Pillar 10: ZKPs in practice

(no new material in window)

### Pillar 11: Age assurance & privacy attributes

(no new material in window. The Apple/Google state-bill lobbying covered by ID Tech on 10-06 is the same story logged 10-06.)

## Open watch items

- **GOV.UK One Login open banking:** GDS roadmap detail; GPG45 scoring of the bank route; whether banks are paid.
- **Apple Cash:** 2026-11-09 go-live; whether bank/merchant reloads follow.
- **AMLA simplified-CDD roundtables:** expressions of interest close 2026-10-18; sessions 11-09 and 12-02.
- **DHS RIVR-2:** IDV/SMTD applications close 2026-10-16.
- **2026-10-19/21:** Authenticate 2026, Carlsbad.
- **2026-10-20:** Japan My Number Card on Android (target).
- **2026-10-26:** BCB MED 2.0 inter-institution step.
- **2026-10-29/30:** EUDI Launchpad 2026, Brussels.
- **End-October:** Ofcom over-16 age-assurance rapid assessment.
- **2026-10-31:** ECB SSM-2026-0301 action-plan deadline.
- **Early November:** CNBV Anexo 71 biometric compliance deadline.
- **2026-11-18:** EUDI ARF Iteration 6 closes.
- **2026-12-24:** EUDI wallet-availability deadline (78 days).
- **PSD3/PSR OJEU:** still unpublished. Next check is 2026-10-12.
