# Cycle Delta — 2026-10-06

Window: 2026-10-04 → 2026-10-06 (last 48 hours, Tuesday run)

## Provenance and integrity notes

- The worker API was reachable. The brand brief, competitors list and all 11 pillar guides were fetched. Deduplication was checked against the full research corpus (111 files, baseline through the 2026-10-05 delta).
- The 10-05 delta ran on Monday morning, so the effective new surface is **2026-10-05 (afternoon) and 2026-10-06**. Nothing dated 10-06 was indexed at run time.
- **Fourthline report date:** the release page carries an editorial date of 2026-10-01, but page metadata shows it went live on **2026-10-05**. The newsroom lists it as Oct 5, and Biometric Update covered it on 10-05. No prior delta logged it. It is counted as a 10-05 finding.
- **Carried in (not counted, primary outside window):**
  1. **Harborside breach notice (IDScan.net / VeriScan), dated 2026-10-03.** This is the first downstream relying-party notice found for the IDScan.net breach logged 09-03/09-08/09-10. New details:
     - Access window: **2026-04-04 → 2026-09-02**.
     - Exposed data: name, address, DOB, sex, licence number and dates, an "image of the front of your ID", and scan metadata including "the approximate location (GPS coordinates) of the scanning device".
     - Harborside says it is reviewing data retention and vendor oversight "to minimize information collection and sharing". The number affected was not stated.
     - Source (primary): https://shopharborside.com/notice-of-data-breach
     - Source: https://idtechwire.com/harborside-discloses-customer-id-exposure-in-veriscan-breach/ (2026-10-05)
     - Use: the retention argument now has a named relying party saying it will collect less. Do not frame IDScan.net as a competitor stumble (see 09-10 caution).
  2. **DHS S&T RIVR-2 (Remote Identity Validation Rally 2).** It was announced in a 2026-09-30 webinar and covered by Biometric Update on 10-05. There are three core tracks (document validation, selfie-to-document match, PAD), plus an experimental **Biometric Deepfake Detection** track.
     - RIVR-1 medians as reported: PAD impostor detection **53%**, IDV legitimate-user success **79%**, IDV impostor detection **87%**.
     - Key dates: IDV/SMTD applications due **2026-10-16**; PAD and deepfake applications open December 2026.
     - Source: https://www.biometricupdate.com/202610/dhs-puts-numbers-behind-rivr-2-details-new-deepfake-testing
     - Source (primary): https://mdtf.org/Images/RemoteIdentity/RIVR-2%20Announcement_final.pdf
     - Caution: the RIVR-1 figures come via Biometric Update. Check them against the MdTF PDF before quoting.
  3. **OFAC Sinaloa Cartel designations (2026-09-29):** 21 individuals and 25 entities, including currency-exchange operators using "mirror transactions" with exchanges in Southern California. No Mexican bank or fintech is named. Possible context only. Source: https://www.steptoe.com/en/news-publications/stepwise-risk-outlook/sanctions-update-october-5-2026.html
- **Checked and rejected:** RATHat / RemControl (already logged), Shufti deepfake index (not in window), Ofcom age-assurance report (July), EU Reg 2026/2099 (09-22), Finland/Bulgaria EUDI oversight (10-01), Think Digital Partners 10-05 roundup (items all already logged or off-lane), Sumsub × FOMO Pay (minor customer win), SecuGen FIDO2 key (minor), UK eGates / Brazil palm biometrics (border, off-lane).
- **PSD3/PSR OJEU:** still no Official Journal notice surfaced in search. Next check is Monday 2026-10-12.

## Override-worthy this cycle

1. **78% of Europeans would accept slower bank verification for less fraud risk (Fourthline / Opinium, n=6,000, six countries).** Account: company /. Angle: "The industry spent a decade removing friction. Customers are now asking for it back, as long as you explain why."
2. **Apple and Google are lobbying US states to adopt app-store age-verification laws with no private right of action ("MERA").** Account: company. Angle: "The age-assurance fight in the US is no longer about whether to verify. It's about who carries the liability when it fails."

## New findings

### Pillar 1: Banking & Payments

(no new material in window. See Pillar 5 for the Fourthline bank-customer survey.)

### Pillar 2: Identity orchestration

(no new material in window)

### Pillar 3: EUDI / eIDAS2

(no new material in window. The Fourthline coverage includes an EUDI-awareness stat; see the Pillar 5 cautions.)

### Pillar 4: KYC / AML compliance

(no new material in window. OFAC Sinaloa designations (09-29) are carried in, not counted.)

### Pillar 5: Customer onboarding

- **Fourthline's second annual Fraud & Authentication Report: 78% of European consumers would accept slower bank verification checks in exchange for significantly less fraud risk.**
  - **Range:** UK 72% to Netherlands 80%.
  - **By age:** 74% of 18–24s and 79% of over-55s would accept slower checks.
  - **Trust:** 83% of UK respondents trust their bank to handle money securely, versus 64% in the Netherlands.
  - **Explanation matters:** 71% of Germans say they need to know why extra steps are needed, and 15% refuse slower processes. 53% of UK respondents want banks to explain why extra security is needed.
  - **Fraud exposure:** 22% of 18–24s have experienced financial fraud and 30% have been exposed to AI-generated scams, versus 13% and 8% for over-55s.
  - **Method:** Opinium, 6,000 nationally representative adults (1,000 each in UK, FR, DE, ES, IT, NL), fieldwork 2026-08-24 to 08-31.
  - **Quote:** Fleur de Roos, COO: "European customers say when it comes to security and identity verification, they want a meaningful process they understand."

  **Why it matters:** this cuts against the "every extra step loses customers" orthodoxy in onboarding. Consumers will tolerate friction when it is visibly about protecting them and explained. The real gap is explaining it, not speed. That fits Ditto's line: strong verification once, then reuse, with the reason made clear.
  - Source (primary): https://www.fourthline.com/news/european-consumers-choose-safety-over-speed-new-fourthline-research-reveals
  - Source: https://www.biometricupdate.com/202610/elevated-fraud-risk-brings-friction-back-into-fashion-for-european-bank-customers
  - Date: 2026-10-05 (went live; editorial date on page 2026-10-01)
  - **Drafting cautions:**
    - This is a vendor-sponsored survey of stated preferences, not behaviour. Say "would accept", not "prefer".
    - Fourthline is an IDV/KYC vendor (merging with Veridas). Cite the data; do not promote the vendor.
    - Biometric Update also reports "only 3% know about the EUDI Wallet" and "35% have never heard of it". These were not found in the primary release; verify before using.

### Pillar 6: Identity verification (IDV)

(no new material counted. Harborside/IDScan.net notice and DHS RIVR-2 are carried in; see the provenance notes.)

### Pillar 7: Fraud / Deepfakes

- **IDEMIA Public Security's WebCapture SDK (v3.38) passed a BixeLab injection-attack evaluation at CEN/TS 18099:2024 Level 2 (Substantial).**
  - **Attacks:** 0 successful out of **900** injection attempts across **10** attack instrument species (deepfakes, face swaps, replay, morphing, avatar reenactment).
  - **Genuine users:** 2 errors in 300 transactions, a BPCER of **0.67%**.
  - **Quote:** Ted Dunstone, BixeLab CEO: "As deepfakes and injection attacks become more sophisticated and accessible, independent testing is increasingly important to ensure biometric systems can withstand real-world threats."

  **Why it matters:** injection-attack certification under CEN/TS 18099 is becoming a checkbox that vendors publish, alongside PAD (ISO 30107-3). Buyers will start asking for both. Note the test level: Substantial, not High.
  - Source (primary): https://www.idemia.com/press-release/idemia-public-securitys-webcapture-sdk-earns-independent-validation-against-deepfake-and-biometric-fraud-attacks-2026-10-05
  - Source: https://idtechwire.com/idemia-webcapture-blocks-all-900-injection-attempts-in-bixelab-assessment/
  - Date: 2026-10-05
  - **Drafting cautions:**
    - IDEMIA is an adjacent competitor. Use this as a market-signal point ("injection testing is now table stakes"), not a vendor shout-out.
    - The sample is 900 attacks and 300 genuine transactions, a lab test at Substantial level. Do not call it "deepfake-proof".

### Pillar 8: Mobile trust & app security

(no new material in window)

### Pillar 9: Passwordless / split-key

(no new material in window. Authenticate 2026 (10-19/21) is the next likely source.)

### Pillar 10: ZKPs in practice

(no new material in window)

### Pillar 11: Age assurance & privacy attributes

- **Politico (2026-10-04): Apple and Google lobbyists are pressing US state lawmakers to adopt kids' online safety laws that bar private lawsuits over age verification and leave enforcement to state attorneys general.**
  - **MERA:** a Google lobbyist has circulated alternative bill text, the "Mobile Ecosystem Responsibility Act". It is modelled on California's Digital Age Assurance Act approach.
  - **Meta's position:** Meta backs the rival App Store Accountability Act (ASAA), which puts verification and liability on the app stores.
  - **Where ASAA stands:** it has passed in Utah, Texas, Louisiana and Alabama, and failed this year in Arizona, Georgia and Kansas.
  - **Quotes:**
    - A child-safety advocate called the Apple/Google drafts "phantom child safety legislation bills that have no real teeth".
    - Google: "Certain other platforms are more focused on putting forward proposals that shift responsibility away from themselves."

  **Why it matters:** the US age-assurance debate has moved from whether to verify to who holds the liability. Whichever model wins decides who buys age assurance: app stores/OS, or every app and platform. That decides where an age-attribute credential has to be accepted.
  - Source (original reporting): Politico, 2026-10-04 (syndicated): https://www.yahoo.com/news/politics/articles/apple-google-push-states-shield-174500685.html
  - Source: https://www.biometricupdate.com/202610/apple-google-lobby-lawmakers-to-remove-liability-from-draft-online-safety-bills
  - Date: 2026-10-04
  - **Drafting cautions:**
    - This is based on draft text, emails and anonymous sources. MERA is not introduced legislation.
    - The source is US-only; Ditto's ICP is EU/UK/LATAM, so use it as a contrast to the EU age-verification app approach.

## Open watch items

- **DHS RIVR-2:** IDV/SMTD applications close 2026-10-16; deepfake-detection track opens December.
- **IDScan.net breach:** more relying-party notices; affected count.
- **MERA vs ASAA:** whether any state introduces the MERA text in the 2027 sessions.
- **Fourthline report:** obtain the full report to verify the EUDI-awareness figures.
- **2026-10-19/21:** Authenticate 2026, Carlsbad.
- **2026-10-20:** Japan My Number Card on Android (target).
- **2026-10-26:** BCB MED 2.0 inter-institution step.
- **2026-10-29/30:** EUDI Launchpad 2026, Brussels.
- **End-October:** Ofcom over-16 age-assurance rapid assessment.
- **2026-10-31:** ECB SSM-2026-0301 action-plan deadline.
- **Early November:** CNBV Anexo 71 biometric compliance deadline.
- **2026-11-18:** EUDI ARF Iteration 6 closes.
- **2026-12-24:** EUDI wallet-availability deadline (79 days).
- **PSD3/PSR OJEU:** still unpublished. Next check is 2026-10-12.
