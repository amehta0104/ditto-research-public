# Cycle Delta -- 2026-10-13

Window: 2026-10-11 -> 2026-10-13 (last 48 hours; the 10-10 Turkish Official Gazette item is included because it surfaced in coverage on 10-12 and no prior delta logged it)

## Provenance and integrity notes

- The worker API was reachable. The brand brief, competitors list and all 11 pillar guides were fetched. Deduplication was checked by keyword against the full research corpus (115 files, through the 2026-10-12 delta).
- **Encoding bug on the worker:** stored deltas (at least 10-09 and 10-12) have double-encoded UTF-8. An em dash is stored as `c3 a2 c2 80 c2 94`, so the GitHub mirror shows mojibake in place of dashes and accented letters. The PUT path appears to decode the body as Latin-1. This file is written in ASCII only to avoid it. The worker needs a fix.
- **Checked and rejected:**
  - Japan FSA IC-chip request: no exchange or bank has announced an image-upload end date since 10-09 (TokenPost, CoinPost, JinaCoin checked). It stays a watch item.
  - Intercede MyID Authenticate (FIDO passkey platform, 10-12) and SecuGen FIDO2 key certification: vendor product news. SecuGen was already logged 10-06.
  - Moldova EVO wallet at four banks: Sept 24, outside window (two-bank stage logged 08-12, four-bank stage 09-17).
  - ID.me + Plaid benefit-payment verification: September, outside window.
  - Malaysia MyDigital ID 18-bank sandbox: January 2026.
  - AMLA central-database RTS consultation (10-07, comments due 11-03) and AMLA dropping group-wide rules for non-financial firms (10-01): outside window. The central-database consultation is not in any prior delta and is logged under watch items.
  - FCA "AML controls on paper" speech (10-07): outside window.
  - Brazil Quod/Rufra H1 fraud data (+10.26%, 9M occurrences): published July, already logged.
  - Mexico Condusef H1 follow-ups (Diario Marca, CiberLATAM): these re-report the Expansion piece logged 10-12.
  - South Africa biometric asylum platform, Bangladesh border screening, Samoa digital ID tender, Sindh/NADRA education records, South Wales police facial recognition evaluation: off-ICP.
  - No new material found for PSD3/PSR OJEU, EUDI ARF/implementing acts, FATF, NIST/iBeta, mobile malware, or SIM swap in window.

## Override-worthy this cycle

1. **Turkiye will require social platforms to check age with a government-issued token that tells the platform only "15+" or "18+": no name, no username, no document.** The rule was published in the Official Gazette on 2026-10-10 and takes effect 2026-11-01. Account: company /. Angle: "A national government just mandated selective disclosure for age checks. The platform learns one bit, not who you are. That's the model, and it's arriving through regulation before the EUDI wallets ship."

## New findings

### Pillar 1: Banking & Payments

(no new material in window. PSD3/PSR still not in the Official Journal. Publication is expected December 2026.)

### Pillar 2: Identity orchestration

(no new material in window)

### Pillar 3: EUDI / eIDAS2

(no new material in window. For the national-wallet age-check angle, see the Greece Gov.gr Wallet / Kids Wallet finding in Pillar 11.)

### Pillar 4: KYC / AML compliance

(no new material in window)

### Pillar 5: Customer onboarding

- **KakaoBank (South Korea) opened fully remote mobile account opening to foreign residents on 2026-10-12. It combines a selfie check designed for foreign customers with Korea's public MyData identity confirmation, and the bank says onboarding takes about five minutes.** Applicants must be 19+ with a foreign-resident ID and a phone registered in their name. AI translation covers English, Chinese and Vietnamese, with seven languages planned. An international debit card is planned for early December.
  **Why it matters:** foreign residents are the classic thin-file, document-heavy onboarding segment. A large digital bank is replacing branch visits with selfie plus government data-source checks, a small data point for "verify against authoritative sources, not uploaded images" (the same logic as the Japan FSA request, 10-12 delta). Korea is not an ICP market, so use it as an illustration only.
  - Source: https://idtechwire.com/kakaobank-opens-selfie-based-mobile-onboarding-to-foreign-residents/
  - Date: 2026-10-12
  - **Drafting cautions:** the secondary source cites Electronic Times and Aju Press. The bank's own announcement was not read directly. "About five minutes" is the bank's claim.

### Pillar 6: Identity verification (IDV)

(no new material in window)

### Pillar 7: Fraud / Deepfakes

- **Denmark's culture minister presented a proposed Copyright Act amendment on 2026-10-12. It would ban sharing realistic deepfakes of a person's face or voice without consent and require major platforms to take such content down quickly.** It frames the protection as a "right to one's own body and voice" (minister Zenia Stampe). There are exceptions for parody, satire and criticism, but these do not apply where the content is misinformation posing serious danger to life or property. It also protects performers from unauthorised AI imitation.
  **Why it matters:** this treats likeness as an asset the person owns, the legal counterpart to the technical problem identity vendors fight at onboarding (face and voice cloning to pass liveness and voice checks). It is useful as context for deepfake posts. It does not change any KYC or authentication obligation.
  - Source: https://www.biometricupdate.com/202610/denmark-moves-to-give-people-legal-control-over-deepfake-likenesses
  - Date: 2026-10-12
  - **Drafting cautions:** this is a legislative proposal. No effective date or penalties are reported. Denmark first floated this approach in 2025, so frame it as "Denmark is moving the bill forward", not "Denmark just invented this".

### Pillar 8: Mobile trust & app security

(no new material in window)

### Pillar 9: Passwordless / split-key

(no new material in window. Authenticate 2026 is 10-19/21.)

### Pillar 10: ZKPs in practice

(no new material in window. The Turkiye and Greece age-assurance findings in Pillar 11 are threshold-only disclosure, the practical selective-disclosure story. They are not ZKP deployments.)

### Pillar 11: Age assurance & privacy attributes

- **Turkiye: a regulation published in the Official Gazette on 2026-10-10 requires social platforms to verify age with a token issued through e-Devlet (the government portal). The token tells the platform only whether the user is 15+ or 18+, and does not pass on name, username or other identifiers.**
  - **Dates:** effective 2026-11-01. Existing accounts must be checked by 2027-03-31.
  - **Restrictions:** minimum age 15. Users aged 15-17 get a separate age-appropriate service with mandatory private accounts, restricted livestreaming, limited personalised ads and Turkish-language parental controls.
  - **Oversight:** technical guidance comes from the Cybersecurity Directorate. Enforcement starts with warnings and a compliance period before penalties.

  **Why it matters:** this is a national mandate built on attribute-only disclosure. Platforms get a verifiable yes/no signed by the state, not a document scan or a date of birth. It is the clearest live example of the "prove the fact, not the identity" model Ditto argues for, and it is arriving through social-media regulation rather than banking. It also gives the age-assurance pillar a non-EU, non-UK reference point.
  - Source (primary): https://www.resmigazete.gov.tr/eskiler/2026/10/20261010-15.pdf
  - Source: https://idtechwire.com/turkiye-sets-government-age-token-checks-for-social-media/
  - Date: 2026-10-10 (published); coverage 2026-10-12
  - **Drafting cautions:** the token mechanics come from the secondary summary. The Gazette PDF (Turkish) was confirmed to exist but was not read in full. Turkiye is not an ICP market, so frame it as a regulatory design signal. Do not imply it uses EUDI or ZKP technology.

- **Greece submitted its under-15 social-media ban bill to parliament on 2026-10-11. Age checks would run through Gov.gr Wallet and Kids Wallet, which give the platform only an above/below-threshold flag, not a date of birth. Committee review is 10-13, the plenary vote is expected 10-22, and the target effective date is 2027-01-01.**
  - **Scope:** applies to new and existing accounts. Parental consent cannot override the ban, and there is no restricted 13-15 tier. Eligibility is by birth year (born 2013 or later is blocked).
  - **Method:** a QR-code flow scanned with Kids Wallet, reusing Greece's existing alcohol/tobacco age-check system. The bill also allows "other equivalent age-assurance solutions".
  - **Oversight:** the National Council for Radio and Television and the Hellenic Data Protection Authority, under Greece's DSA framework.

  **Why it matters:** this is the first legislative step on the Greek ban. The 10-05 delta noted that no legislative step had been taken since the April announcement. Greece is one of the seven EU age-verification-app pilot countries, so this is the first time a pilot state has written wallet-based threshold checks into law. It is the bridge between the EU age-verification blueprint and the EUDI wallet. The "other equivalent solutions" clause leaves room for private providers.
  - Source: https://idtechwire.com/greece-submits-social-media-age-verification-bill-to-parliament/
  - Date: 2026-10-11
  - **Drafting cautions:** the underlying reporting is Naftemporiki and ProtoThema. The bill text was not read. Penalties and platform obligations are not yet reported. The vote has not happened, so say "proposed" until 10-22.

## Open watch items

- **2026-10-13:** Greek parliamentary committee review of the under-15 bill. Plenary vote expected 10-22.
- **Japan FSA:** watch for the first crypto exchange or bank to announce an end date for image upload.
- **DHS RIVR-2:** IDV/SMTD applications close 2026-10-16.
- **AMLA simplified-CDD roundtables:** expressions of interest close 2026-10-18.
- **PSD3/PSR OJEU:** next check 2026-10-19. Publication is expected December.
- **2026-10-19/21:** Authenticate 2026, Carlsbad.
- **2026-10-20:** Japan My Number Card on Android (target).
- **2026-10-26:** BCB MED 2.0 / IN BCB 766 Pix changes take full effect.
- **2026-10-26/30:** FATF plenary, Paris.
- **2026-10-29/30:** EUDI Launchpad 2026, Brussels.
- **End-October:** Ofcom over-16 age-assurance rapid assessment.
- **2026-10-31:** ECB SSM-2026-0301 action-plan deadline.
- **2026-11-01:** Turkiye age-token regulation takes effect.
- **2026-11-03:** AMLA central AML/CFT database RTS consultation closes (public hearing the same day). Published 10-07, not previously logged.
- **Early November:** CNBV Anexo 71 biometric compliance deadline.
- **2026-11-09:** Apple Cash reload ID check goes live.
- **2026-11-18:** EUDI ARF Iteration 6 closes.
- **2026-12-24:** EUDI wallet-availability deadline (72 days).
