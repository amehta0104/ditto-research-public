# Cycle Delta -- 2026-10-20

Window: 2026-10-18 -> 2026-10-20 (last 48 hours, Tuesday run). The 10-19 delta already scanned 10-18 and 10-19, so this cycle focuses on late 10-19 and 10-20.

## Provenance and integrity notes

- Brand brief, competitors list and all 11 pillar guides were fetched from the worker. Deduplication was checked by keyword against the 2026-05-06 baseline and every delta on the worker, through 2026-10-19.
- This file is ASCII-only to avoid the double-encoding issue on the worker PUT path.
- Another thin cycle. Money20/20 USA, Authenticate 2026 and the Biometrics Institute Congress (London, 10-20/21) are all running, but no FIDO press release or bank-side identity announcement with substance had been published by the time of this scan.
- **Checked and rejected:**
  - World ID for banking and finance: logged 10-19. Still circulating (Yahoo Finance, Winbuzzer 10-20, The Paypers, CoinCentral). Nothing new.
  - Hirudo (10-15), YuanKong RAT (rejected 10-19; Star Labs primary still not found), identifAI USD 40bn (10-14), Fideuram (09-30 to 10-07): all re-surfaced. Not counted.
  - Mastercard at Money20/20: panel sessions only ("Who Let the Bots Pay?", "The Trust Layer for Agentic Commerce"). No new product or data. Agent Pay trust services were logged earlier.
  - Banesco passkey case study (2.2m users, about 92% of active users on passkeys): FIDO case study dated May/June 2026. Outside window. A "65% fall in identity-theft fraud reports" figure appears only in a search-engine summary and was not found in the case study. Do not cite it.
  - Condusef: 11 legitimate financial institutions impersonated in August 2026 (alert dated around 2026-09-11). Outside window. El Heraldo de Mexico (10-19) re-reported it alongside vendor claims from Silent4Business (deepfake cost "from USD 1,000 to USD 1" in six years, "about 18 seconds" to make one). These are vendor claims and the article could not be loaded. Not counted.
  - Colombia "63 identity-impersonation cases a day" (ACIS, Incode-sourced): competitor-sourced and undated. Not counted.
  - BCB Resolution 587 (Pix DICT fraud-marking accountability): resolution dated 2026-09-18, logged 09-23/09-25. Mundocoop (10-16) re-reported it. One detail is new: BCB plans a "Circuito Pix" session in early November on the operational side. Noted under watch items.
  - FinCEN BOI final rule for US entities: dated 2026-08-11. Outside window.
  - OFAC actions on 10-19 (PAIPA GL 1/2, Venezuela GL 60A): routine, off-pillar.
  - Keycloak 26.8 experimental OpenID4VP verifier: an open-source release, with no exact date confirmed and no relying-party adoption. Not counted.
  - Tech Transparency Project "nudify apps" report: dated April 2026. Outside window.
  - No in-window material found for PSD3/PSR OJEU, EBA/ECB/DORA, AMLA (SDD roundtable call closed 10-18, no output yet), FATF, FCA/PSR APP fraud, NIST/iBeta, analyst orchestration coverage, onboarding benchmarks, SIM-swap/SS7, MiCA/Travel Rule enforcement, EU age-verification app, Ofcom, or LATAM regulators (CNBV, BCB, Superfinanciera, CMF).

## Override-worthy this cycle

1. **INTERPOL launched a global deepfake-scam awareness campaign on 2026-10-19 (Singapore). Its Innovation Centre director says: "AI is erasing the tell-tale signs of a scam. Spelling mistakes, branding inconsistencies, clumsy formatting: these red flags are fast becoming a thing of the past."** Account: company /. Angle: "When INTERPOL says the red flags are gone, 'train your customers to spot the scam' stops being a control. If people can't see the fake, verification has to happen in the channel, not in the customer's head."

## New findings

### Pillar 1: Banking & Payments

(no new material in window.)

### Pillar 2: Identity orchestration

(no new material in window. World ID for banking logged 10-19. Mastercard Money20/20 agentic-commerce sessions rejected; see notes.)

### Pillar 3: EUDI / eIDAS2

(no new material in window.)

### Pillar 4: KYC / AML compliance

(no new material in window.)

### Pillar 5: Customer onboarding

(no new material in window. Only recycled abandonment statistics surfaced: Signicat 2022, Fenergo, HooYu.)

### Pillar 6: Identity verification (IDV)

(no new material in window.)

### Pillar 7: Fraud / Deepfakes

- **INTERPOL launched a public awareness campaign on AI deepfake scams on 2026-10-19 (dateline Singapore).** It consists of three short videos, themselves AI-generated, showing how fabricated voices and images are used to impersonate trusted people and to get victims to pay or disclose sensitive information across borders. The tagline is "Wait. Validate. Don't take the bait." It is part of Project SynthWave PLUS, funded by the Government of Japan and focused on Southeast Asia "and beyond".
  - **Quote (Toshinobu Yasuhira, Director, INTERPOL Innovation Centre):** "AI is erasing the tell-tale signs of a scam. Spelling mistakes, branding inconsistencies, clumsy formatting: these red flags are fast becoming a thing of the past."
  - **Advice to businesses (INTERPOL):** mandatory training on deepfake scams and social engineering; "multi-step verification for financial transactions and data transfers"; regular software updates against malware and spyware.
  - **Scam types named:** investment, impersonation, romance, sextortion, deepfake pornography and disinformation. The payment methods it flags are wire transfers, cryptocurrency and gift cards.

  **Why it matters:** the world's largest police organisation is now saying on the record that the visual and linguistic cues consumer-education campaigns rely on no longer work. That supports the argument that fraud controls have to sit with the institution: out-of-band verification for high-risk requests, bound to a cryptographically verified device or identity, rather than the customer's judgement. INTERPOL's own business advice ("multi-step verification for financial transactions") is a neutral, citable line for that argument. The quote also works well as a post opener.
  - Source (primary): https://www.interpol.int/en/News-and-Events/News/2026/INTERPOL-launches-public-awareness-campaign-highlighting-risk-of-AI-deepfake-scams
  - Date: 2026-10-19
  - **Drafting cautions:** this is an awareness campaign, not a threat report. It contains no new statistics, case counts or loss figures, so do not attach numbers to it. Some secondary coverage mixes it up with Operation HAECHI and earlier INTERPOL seizure figures (USD 300m, 3,500 arrests). Those are different, older operations. Do not combine them. Some aggregators date the campaign 10-18; the INTERPOL primary says 19 October 2026. INTERPOL's public advice includes 2FA and safe words. Do not overstate it as endorsing any specific technology.

### Pillar 8: Mobile trust & app security

- **Japan's "Android My Number Card" went live on 2026-10-20.** The national ID credential is added to Google Wallet, and the service adds a new attribute-certification function (zokusei shomei) for in-person identity, age and residence checks, authenticated with on-device biometrics. On 2026-10-19 the Digital Agency published the supported-device list. Coverage (ITmedia Mobile, k-tai Watch) says the new attribute-certification function works only on a subset of handsets with a qualifying secure chip, mostly recent flagships. The other listed devices support only the basic functions. Devices must run Android 12+ with current security patches, and models bought overseas may not work even if they are on the list.
  This resolves the 10-20 watch item. The original announcement was logged 10-05 to 10-08.

  **Why it matters:** this is a live example of a state credential whose availability depends on handset hardware. The same national ID gets different capabilities depending on the phone's secure element. Any relying party designing around a wallet credential, including EUDI wallets under the December 2026 deadline, has to plan for a mixed population. Some customers will have the high-assurance credential and some won't, so fallback paths and device-integrity signals are still needed. That is the mobile-trust and orchestration argument.
  - Source: https://www.itmedia.co.jp/mobile/articles/2610/19/news071.html
  - Source: https://k-tai.watch.impress.co.jp/docs/news/2149346.html
  - Source (primary, service page): https://services.digital.go.jp/mynumbercard-android/
  - Date: 2026-10-19 (device list) / 2026-10-20 (launch)
  - **Drafting cautions:** Japan is not an ICP market, so use it as an illustration only. The model counts conflict across secondary sources (one summary says 40+ models, another says 400+ with about 120 supporting attribute certification), and the Digital Agency list was not read directly. Do not cite any count. Say "only a subset of devices". The launch is confirmed by Digital Agency communications as summarised in search, but the primary page body could not be loaded. If precision matters, re-check before posting.

### Pillar 9: Passwordless / split-key

(no new material in window. No FIDO Authenticate 2026 press release found yet. Banesco case study rejected as out of window; see notes.)

### Pillar 10: ZKPs in practice

(no new material in window.)

### Pillar 11: Age assurance & privacy attributes

(no new material in window. Japan's attribute-certification function covers in-person age checks; see Pillar 8. The Greek under-15 bill goes to a vote 10-22.)

## Open watch items

- **2026-10-20/21:** Authenticate 2026 (FIDO), Money20/20 USA, Biometrics Institute Congress (London). Re-check for FIDO announcements and congress outputs in the 10-21 and 10-22 cycles.
- **Japan My Number Android:** read the Digital Agency device list directly for an authoritative attribute-certification model count.
- **YuanKong RAT:** Star Labs primary still not found.
- **NetChoice/CCIA:** en banc or certiorari filings on Florida HB 3 and Georgia SB 351.
- **DIdG follow-up:** committee recommendation 21/8617 (relying-party, liability, KYC language).
- **Passkey Index 2026 PDF:** financial-services breakouts.
- **Bank of America:** consent orders.
- **AMLA simplified-CDD roundtables:** call closed 10-18. Watch for the participant list or roundtable dates.
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
- **2026-11-18:** EUDI ARF Iteration 6 closes.
- **2026-12-24:** EUDI wallet-availability deadline (65 days).
- **2027-01-02:** d-you launch.
- **Workday / C1.ai:** close expected by 2027-01-31.
- **MyCheck:** launch date and Dutch government response.
