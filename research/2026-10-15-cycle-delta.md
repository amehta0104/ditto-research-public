# Cycle Delta -- 2026-10-15

Window: 2026-10-13 -> 2026-10-15 (last 48 hours)

## Provenance and integrity notes

- Brand brief, competitors list and all 11 pillar guides were fetched from the worker. Deduplication was checked by keyword against the 2026-05-06 baseline and every delta from 2026-09-08 to 2026-10-14.
- **Correction to the 2026-10-14 delta.** That delta said "no in-window material found for... FinCEN". FinCEN, the OCC and OFAC announced penalties against Bank of America on 2026-10-13 (headline: USD 1.2bn from FinCEN). That is inside both windows. It is logged below (Pillar 4).
- This file is ASCII-only to avoid the double-encoding issue on the worker PUT path.
- **Checked and rejected:**
  - FinCEN/agency mDL-VDC CIP FAQs: logged 09-10 (primary dated 2026-09-08). Fintech.global re-reported them on 10-14 as if they were new. They are not.
  - Socure mDL verification (Google/Samsung Wallet): primary dated 2026-09-30, rejected 10-05 as out of window. Resurfaced in search this cycle.
  - MyCheck (Dutch bank/insurer wallet): logged 10-14. Biometric Update (10-14) adds only that the coalition has offered it to the Dutch government at no cost and frames it as a sovereignty play. It is still not operational and has no launch date. Not counted.
  - Bank Negara Malaysia / Securities Commission warning on deepfake videos impersonating their senior officers (2026-10-13): in window, but a generic consumer scam alert in a non-ICP market. No new data.
  - BioCatch "84% of bank leaders see AI agents as the greatest vulnerability": press release dated 2026-06-10. Out of window.
  - identifAI USD 40bn deepfake report: logged 10-14.
  - HID FIDO board, Hopae FIDO membership, Dashlane Passkey Power 20, Intercede, SecuGen: logged or rejected 10-13/10-14.
  - SEON + Yuno checkout integration, Zumigo SIM-swap-aware silent authentication: vendor product news with no market data.
  - No in-window material found for PSD3/PSR OJEU, EBA, AMLA (beyond the 10-01 RTS), FATF, FCA/PSR APP fraud, NIST/iBeta, OpenID4VP/ZKP, or LATAM regulators (CNBV, BCB, Superfinanciera).

## Override-worthy this cycle

1. **US Treasury hit Bank of America with a USD 1.2bn FinCEN AML penalty, plus OCC (USD 750m) and OFAC (USD 11.6m) actions. Press puts the combined total at about USD 1.21bn. Regulators say its customer due diligence "failed to account for customers' extensive reliance on payments from unknown third parties", and more than USD 5bn in suspicious activity went unreported or was reported late.** Account: company /. Angle: "The biggest bank AML fine since TD wasn't about a customer the bank failed to identify. It was about who was paying them. KYC that stops at the account holder misses the third party who's actually moving the money."
2. **Hirudo, a new Android banking trojan, swaps real banking apps for patched copies that relay Google Play Integrity checks to the attacker's server and return a passing verdict (ThreatFabric, 2026-10-14). Mexico is among the coded targets.** Account: company /. Angle: "Your app asked Google if the device was trustworthy. The attacker answered. Attestation you don't verify server-side is a checkbox, not a control."

## New findings

### Pillar 1: Banking & Payments

(no new material in window. For the Bank of America enforcement action, see Pillar 4.)

### Pillar 2: Identity orchestration

(no new material in window. Workday / C1.ai was logged 10-14.)

### Pillar 3: EUDI / eIDAS2

- **The Bundestag's Digital Affairs Committee approved Germany's Digital Identities Act (DIdG), the national legal basis for the d-you EUDI wallet, in amended form on 2026-10-14. The coalition (CDU/CSU, SPD) voted for it and AfD, Greens and Die Linke voted against.** Plenary 2nd/3rd reading is today, 2026-10-15. d-you is due to launch on 2027-01-02.
  - **Amendments published so far:** users may refuse to have their biometric photo included in wallet identity data; pseudonymous use is emphasised; the deadline for providing attribute certificates is cut from 24 to 12 months; German/EU digital sovereignty is weighted in procurement; the federal citizen account stays as a voluntary alternative; the online ID function can be used from age 13; evaluation is brought forward.
  - **What is missing:** neither the Bundestag summary nor beck-aktuell mentions any of the banking associations' (DK) demands logged 10-14 (provider liability for faulty authentications, wallet data counting as sufficient KYC evidence, fraud-data access, a right to block vulnerable wallets).

  **Why it matters:** if the law passes in this form, German banks get a state wallet with no statutory answer on who carries liability when a wallet authentication fails. That gap moves into contracts, scheme rules and the relying party's own controls, which is the orchestration and risk-signal layer. It also follows the DK position paper by one day, which makes for a clean "banks asked, lawmakers didn't answer (yet)" story.
  - Source (primary, committee): https://www.bundestag.de/dokumente/textarchiv/2026/kw42-pa-digitales-identitaeten-1224678
  - Source (plenary agenda): https://www.bundestag.de/dokumente/textarchiv/2026/kw42-de-digitale-identitaeten-gesetz-1223586
  - Source: https://www.beck-aktuell.de/heute-im-recht/rechtspolitik-gesetzgebung/gesetzentwurf-digitale-identitaet-eudi-wallet-d-you-datenschutz-eu-2026-10-14
  - Date: 2026-10-14
  - **Drafting cautions:** "not addressed" is based on summaries, not the amended bill text or committee report (Beschlussempfehlung), which were not read. Do not say the bank demands were rejected. Say they do not appear in the published amendments. Check the plenary result (10-15) before posting. The Bundesrat stage still follows.

### Pillar 4: KYC / AML compliance

- **On 2026-10-13, FinCEN assessed a USD 1.2bn civil money penalty against Bank of America, N.A., alongside a USD 750m OCC penalty (the OCC's largest ever) and an USD 11.6m OFAC settlement.** Treasury cites failures to mitigate and report "priority national security risks", including Chinese money laundering networks, fraud, potential trade-based money laundering and illicit finance along the US southwest border.
  - **CDD failure, in Treasury's words:** the bank's "CDD processes failed to account for customers' extensive reliance on payments from unknown third parties", and it "failed to timely and meaningfully respond to mounting red flags involving these customers -- including potential ties to narcotics trafficking proceeds".
  - **Reporting:** more than USD 5bn in suspicious transactions not reported on time, over USD 1bn of it tied to national-security and other priority risks. Treasury says the bank "outsourced to third parties a substantial portion of its proactive detection and reporting obligations".
  - **Amounts:** press (CNBC, SCMP, Al Jazeera) reports the combined total as about USD 1.21bn, which implies the OCC's USD 750m is credited against FinCEN's USD 1.2bn. This is not confirmed in the releases read. Do not add the three figures together.
  - **Context:** an earlier (December 2024) OCC cease-and-desist order did not fix the problems. Press coverage ranks the FinCEN penalty third-largest in Treasury history, behind Binance (2023) and TD Bank (2024).

  **Why it matters:** this is a CDD case, not an onboarding-ID case. The customers were identified, but the bank did not understand who was funding them. That gives a concrete, named, regulator-sourced line for "KYC is continuous, not a point-in-time check" and for perpetual or event-driven re-verification. The "outsourced detection" finding is also a warning for any bank relying on vendors without owning the decision layer.
  - Source (primary): https://www.fincen.gov/news/news-releases/fincen-assesses-12-billion-penalty-against-bank-america
  - Source (primary, Treasury): https://home.treasury.gov/news/press-releases/sb0657
  - Source: https://www.cnbc.com/2026/10/13/bank-of-america-treasury-money-laundering.html
  - Date: 2026-10-13
  - **Drafting cautions:** the consent orders were not read. Use Treasury's quotes, not paraphrased "BofA ignored..." claims. The violation period was not stated in the releases read. The "third-largest" ranking comes from press, not Treasury. Do not link the "southwest border" language to Mexico or to named cartels unless the consent order says so.

### Pillar 5: Customer onboarding

(no new material in window. Search turned up only undated or recycled abandonment statistics.)

### Pillar 6: Identity verification (IDV)

(no new material in window. FinCEN mDL FAQs and Socure mDL resurfaced but are logged/out of window; see notes.)

### Pillar 7: Fraud / Deepfakes

(no new material in window. Malaysia BNM/SC deepfake-impersonation alert rejected; see notes.)

### Pillar 8: Mobile trust & app security

- **ThreatFabric disclosed Hirudo, a new Android banking trojan, on 2026-10-14. It replaces genuine banking apps with patched copies signed with public test keys, then hooks the apps from inside to defeat their own security checks.**
  - **How it bypasses checks:** one line injected into the app's Application class loads a hooking engine (built on YAHFA and Dobby). The engine spoofs signature checks and hides its Accessibility services. It relays Google Play Integrity requests "over plain HTTP to an operator-controlled server, which returns a verdict for the app to accept."
  - **Capabilities:** theft of passwords, PINs and unlock patterns (read via Accessibility); localised fake checkout overlays; live screen and camera streaming via WebRTC; SMS interception.
  - **Targets and distribution:** primarily 8 apps from 7 banks in Indonesia. Code also targets China, India, Mexico, Morocco, Thailand and Malaysia. Lures (shopping, adult video, short-drama apps) are served from Amazon CloudFront, with OpenInstall attribution and shared Meta Pixel IDs.

  **Why it matters:** this attacks the assumption that an app's own runtime checks and a Play Integrity call prove the device is clean. If the attestation verdict is consumed on-device rather than verified server-side, a patched app can just be told "pass". That is the argument for app-layer threat defence plus server-side attestation validation and device binding, which is Ditto Protect's territory. Mexico on the target list gives a LATAM hook.
  - Source (primary): https://www.threatfabric.com/blogs/hirudo-from-fake-updates-to-patched-banking-apps
  - Source: https://www.bleepingcomputer.com/news/security/hirudo-android-malware-replaces-banking-apps-to-evade-security-checks/
  - Date: 2026-10-14
  - **Drafting cautions:** no Mexican bank is named, and Mexico is a coded target, not a confirmed active campaign. Say "Mexico is among the targeted countries in the code". Do not claim Play Integrity itself is broken. The bypass works where the app trusts a verdict it did not verify with Google server-side. ThreatFabric is a mobile-security vendor, but this is primary threat research, not a product claim.

### Pillar 9: Passwordless / split-key

(no new material in window. HID / FIDO board logged 10-14.)

### Pillar 10: ZKPs in practice

(no new material in window.)

### Pillar 11: Age assurance & privacy attributes

(no new material in window. Note from Pillar 3: Germany's amended DIdG lets the online ID function be used from age 13.)

## Open watch items

- **2026-10-15 (today):** Bundestag plenary vote on DIdG. Check the result and whether the committee report (Beschlussempfehlung) adds any relying-party or liability language.
- **Bank of America:** read the FinCEN and OCC consent orders for the violation period and the third-party-payment typologies.
- **DHS RIVR-2:** IDV/SMTD applications close 2026-10-16.
- **AMLA simplified-CDD roundtables:** expressions of interest close 2026-10-18.
- **PSD3/PSR OJEU:** next check 2026-10-19. Publication expected December.
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
- **2026-12-24:** EUDI wallet-availability deadline (70 days).
- **Workday / C1.ai:** close expected by 2027-01-31.
- **MyCheck:** launch date and Dutch government response.
