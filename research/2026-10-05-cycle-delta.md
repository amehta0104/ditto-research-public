# Cycle Delta — 2026-10-05

Window: 2026-10-02 → 2026-10-05 (last 72 hours, Monday run covering the weekend)

## Provenance and integrity notes

- The worker API was reachable. The brand brief, competitors list and all 11 pillar guides were fetched. Deduplication was checked against the full research corpus (109 files, baseline through the 2026-10-02 delta).
- This was a thin window: Friday afternoon plus a weekend. Most "new" items surfaced by search were re-reports of material dated 09-22 to 10-01. Only one finding is counted.
- **Carried in from 2026-10-01 (missed by the 10-02 delta, not counted).** These three items have primaries dated 10-01, one day before today's window. The 10-02 delta did not log them, and none appears anywhere in the corpus. They are listed here with full sourcing because each is stronger than anything inside the window. The drafter may use them.
  1. **Google: Android 17 Advanced Protection now restricts AccessibilityService to verified Accessibility Tools.** With Advanced Protection on, only apps flagged as accessibility tools (`isAccessibilityTool="true"`: screen readers, switch/voice input, Braille) can use the API. Per Security Affairs (March), existing grants to other apps are revoked when the mode is switched on. Antivirus, automation tools and password managers are excluded. The same release adds Intrusion Logging (separate opt-in), USB Protection, Failed Authentication Lock (select devices), WebGPU disabled, and "View Supporting Apps". Apps can detect the mode through `AdvancedProtectionManager` and harden themselves.
     - **Why it matters:** Accessibility abuse is the core mechanism of every banking trojan logged this quarter (RATHat, RemControl, Anatsa, ToxicPanda). Google has now shipped an OS-level kill switch for it, but only for users who opt in to Advanced Protection. Most banking customers won't. That leaves app-side runtime protection as the default line of defence. Banks can read the Advanced Protection signal and treat it as a risk input.
     - Source (primary): https://blog.google/security/android-advanced-protection-updates/ (Il-Sung Lee, 2026-10-01)
     - Source: https://thehackernews.com/2026/10/android-17-advanced-protection-locks.html (2026-10-02/03)
     - Source (background): https://securityaffairs.com/189497/security/advanced-protection-mode-in-android-17-prevents-apps-from-misusing-accessibility-services.html (Beta 2 preview, March 2026)
     - **Drafting cautions:**
       - Advanced Protection is **opt-in**; do not say "Android 17 blocks accessibility malware".
       - The feature was previewed in Android 17 Beta 2 in March. The 10-01 post is the GA feature announcement.
     - Pillar: Mobile trust. Account fit: company / 
  2. **NAB is the first Australian bank to accept ISO/IEC 18013-5 mobile driver licences in branch.** Customers in selected Queensland branches approve a request and share their Queensland mDL device-to-device, with no manual data entry. A physical-document path remains. NAB will extend the service state by state "as compatible technology… become[s] available".
     - **Quotes:**
       - Claire Righetti (Executive, Onboarding & Identity): "We're making it easier and safer for our customers and harder for would-be criminals."
       - Si Phan (Head of Identity Management): "The threat environment is constantly changing which means we need to continually innovate."
     - **Why it matters:** this is a named tier-1 bank using a cryptographic credential for onboarding/servicing instead of a document scan. It is the in-branch analogue of the US CIP guidance (09-08 delta) and the Socure mDL launch (09-30, below).
     - Source (primary): https://www.nab.com.au/news/technology-ai/nab-first-australian-bank-to-announce-tamper-proof-encrypted-ide (2026-10-01)
     - Source: https://idtechwire.com/id-tech-digest-october-2-2026/
     - Pillar: Customer onboarding / IDV. Account fit: company / 
  3. **Service NSW upgraded its Digital Driver Licence with face verification (identity proofing) and consent-based QR sharing.** An over-18 proof that does not reveal date of birth or address is announced as a coming feature. Proofing requires three identity documents plus a face check; NSW Digital ID holders skip the documents. The pilot is limited to Western Sydney and the Blue Mountains, with statewide rollout "later in 2026". The only accepting venue so far is Panthers Penrith Rugby Leagues Club.
     - Source (primary): https://www.service.nsw.gov.au/nsw-digital-driver-licence-upgrade (2026-10-01)
     - Source: https://idtechwire.com/nsw-begins-digital-driver-licence-upgrade-with-face-verification-and-consent-based-sharing/ (2026-10-02)
     - **Drafting caution:** the over-18 proof is a future feature, not live. No source says ZKPs are used.
     - Pillar: ZKP / selective disclosure, age assurance. Account fit: 
- **Checked and rejected (out of window or already covered):**
  - **Socure** mDL verification in DocV (Google/Samsung Wallet): primary dated 2026-09-30. It was not logged in prior deltas, but it is out of window. Primary: https://www.socure.com/news-and-press/mdl-verification-remote-onboarding. Socure is an adjacent competitor.
  - **RemControl** Android banker (Group-IB): primary dated 2026-09-23. It targets 30+ banks in IT/FR/ES/PL/PT/GCC/CA, and its C2 and overlays were partly built with an AI assistant that was deceived into helping. Out of window.
  - **XConnect** fuzzy matching on UK CAMARA KYC Match (EE/Vodafone/VMO2): dated 2026-09-30. Out of window.
  - **Ping Identity** agents for Gemini Enterprise: dated 2026-10-01. Workforce IAM, off-lane.
  - **OpenID4VP/VCI HAIP first 14 certifiers** (09-24): already logged 09-28.
  - **Implementing Reg (EU) 2026/2099** (MyHealth@EU + EUDI): OJ 2026-09-22. Out of window.
  - **Greece under-15 social media ban from 2027-01-01 via Kids Wallet:** the GreekReporter 10-04 piece re-reports the April 2026 announcement. No new legislative step was found.
  - Cifas H1 2026 (August), Tandem deepfake survey (09-14), Ocrolus/Resistant AI (10-01), Jumio selfie.DONE EMEA (09-29), Sardine AI Labs (10-01): all out of window.
- **PSD3/PSR OJEU:** web searches surfaced no Official Journal notice. This was not confirmed directly on EUR-Lex. Next check is Monday 2026-10-12.

## Override-worthy this cycle

(none inside the window. If the drafter needs a Mobile Trust hook, use carried-in item 1, Android 17 Advanced Protection: "Google just shipped a kill switch for the #1 banking-malware technique. It's off by default.")

## New findings

### Pillar 1: Banking & Payments

(no new material in window)

### Pillar 2: Identity orchestration

(no new material in window. Ping Identity's Gemini agents (10-01) are workforce IAM and out of window.)

### Pillar 3: EUDI / eIDAS2

(no new material in window. The Finland/Bulgaria legal steps were covered 10-01; Reg 2026/2099 dates from 09-22.)

### Pillar 4: KYC / AML compliance

(no new material in window)

### Pillar 5: Customer onboarding

(no new material in window. See carried-in item 2, NAB, in the provenance notes.)

### Pillar 6: Identity verification (IDV)

(no new material in window. Socure mDL (09-30) is out of window; see the provenance notes.)

### Pillar 7: Fraud / Deepfakes

(no new material in window)

### Pillar 8: Mobile trust & app security

(no new material counted. See carried-in item 1, Android 17 Advanced Protection, in the provenance notes.)

### Pillar 9: Passwordless / split-key

(no new material in window. Authenticate 2026, 10-19/21, is the next likely source.)

### Pillar 10: ZKPs in practice

- **Japan's Digital Agency set 2026-10-20 as the target launch date for the My Number Card in Google Wallet on Android.** It adds "attribute certification" for in-person checks of identity, age and residency across government and private-sector services. Relying parties read the phone credential with a free Digital Agency verifier app. It needs Android devices with approved security chips. The 08-27 delta logged only "autumn 2026"; this is the first firm date, and it follows the iPhone version (June 2025).
  - **Why it matters:** with this, both mobile OS platforms carry a national ID with attribute-level presentation. The relying-party side (a free government verifier app) is the piece the EUDI rollout has not yet made cheap.
  - Source (primary): https://services.digital.go.jp/mynumbercard-android/news/fec690c52f9ffeb35d30f/
  - Source: https://idtechwire.com/japan-sets-october-20-launch-target-for-my-number-card-in-google-wallet/
  - Date: 2026-10-02 (reported)
  - **Drafting cautions:**
    - The 10-20 date is provisional, pending final testing.
    - The Digital Agency page does not show a clear publication date.
    - Do not claim ZKP or selective disclosure; the sources say only "attribute certification".
    - Japan is outside Ditto's ICP geographies, so use it only as a comparison point.

### Pillar 11: Age assurance & privacy attributes

(no new material in window. Ofcom's over-16 rapid assessment is still due to Parliament by end-October.)

## Open watch items

- **Android 17 Advanced Protection:** any bank or regulator guidance telling customers to enable it; Play policy follow-through on `isAccessibilityTool`.
- **NAB mDL:** next state after Queensland; whether CBA/Westpac/ANZ follow.
- **Japan My Number on Android:** confirm the 10-20 go-live.
- **AMLA CDD RTS:** Commission adoption and OJ publication.
- **Mastercard Agent Pay:** US test results; first issuer.
- **UK DVS register:** October onboarding tests.
- **2026-10-19/21:** Authenticate 2026, Carlsbad.
- **2026-10-22:** Ocrolus/Resistant AI document-fraud webinar (low priority).
- **2026-10-26:** BCB MED 2.0 inter-institution step.
- **2026-10-29/30:** EUDI Launchpad 2026, Brussels.
- **End-October:** Ofcom over-16 age-assurance rapid assessment.
- **2026-10-31:** ECB SSM-2026-0301 action-plan deadline.
- **Early November:** CNBV Anexo 71 biometric compliance deadline.
- **2026-11-18:** EUDI ARF Iteration 6 closes.
- **2026-12-24:** EUDI wallet-availability deadline (80 days).
- **PSD3/PSR OJEU:** still unpublished. Next check is 2026-10-12.
