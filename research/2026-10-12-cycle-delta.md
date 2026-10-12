# Cycle Delta — 2026-10-12

Window: 2026-10-09 → 2026-10-12 (last 72 hours, Monday run covering the weekend)

## Provenance and integrity notes

- The worker API was reachable. The brand brief, competitors list and all 11 pillar guides were fetched. Deduplication was checked by keyword against the full research corpus (114 files, from the 6-month baseline through the 2026-10-09 delta).
- **The 2026-10-09 delta skipped deduplication.** It ran without worker access, so several of its items repeat earlier deltas (GOV.UK One Login open banking, the EUDI commercial-value op-ed, the Euronews op-ed, AMLA CDD RTS). The drafter should treat that file with care.
- **Carried in (not counted, primary date outside window, not logged by any prior delta):**
  1. **Reusable KYC gateway for a 20M-wallet stablecoin network (2026-10-07).** Sumsub launched a "Reusable KYC Gateway" at Token2049 Singapore, with MiniPay (Opera's stablecoin wallet, 70+ countries, 20M+ wallets) as first integrator. Users verify once and reuse the result at every regulated partner, and MiniPay does not store the documents. Early partner results: verification conversion up from ~70% to ~95%, and KYC completion time cut by "up to 50%". This is strong "verify once, reuse trust" data. Sumsub is a direct competitor: cite the numbers as "a stablecoin wallet network", never name the vendor. These are vendor-reported early results. Source (primary): https://sumsub.com/newsroom/sumsub-launches-reusable-kyc-gateway-cutting-repeat-verification-for-minipays-network/ Source: https://idtechwire.com/sumsub-launches-reusable-kyc-gateway-with-minipay-as-first-integrator/
  2. **Brazil: 3.6 million facial-biometric records linked to identity-fraud attempts as of September 2026 (published 2026-10-08).** This is up 20% since May 2026, about 5,000 new records a day. The base is a 140-million-face database, and financial institutions are the main target (fraudulent account opening using real faces and AI-manipulated images). The data comes from CertiFace, a Brazilian vendor shared-database. It is useful as a anchor. Source: https://olhardigital.com.br/2026/10/08/seguranca/brasil-tem-36-milhoes-de-registros-biometricos-ligados-a-fraudes-de-identidade
  3. **Ditto's own news (2026-10-01): Ditto was named a Product Leader in the KuppingerCole Leadership Compass for Identity Verification 2026 (26 vendors evaluated).** It is not a research finding. It is logged because no delta recorded it and the drafter should know it exists for company-page content. Source: https://finance.yahoo.com/technology/ai/articles/ditto-named-product-leader-kuppingercole-183400262.html (PR Newswire)
- **Checked and rejected:**
  - Biometric Update roundups dated 10-09: voice and meeting deepfake detection launches (Netarx, Onecom, Pindrop BotStopper) are vendor product news. The crypto roundup repeats Regula (logged 10-08).
  - Anatsa via a Google Play PDF reader (Zscaler, 10-09): the same distribution pattern is already a standing anchor (08-19). RemControl: logged 09-29/10-05. RedWing Stealer (Uzbekistan/Kazakhstan): off-region.
  - Next Biometrics bankruptcy, TECH5 CEO change, Ethiopia Fayda sandbox, Nigeria PVC, America.gov/Login.gov, Google Wallet state-ID list update (10-10): off-lane or minor.
  - Philippines Senate SMART KIDS Act (10-08): outside window, off-ICP. Note it if age-assurance volume is thin.
  - IDScan.net 153M–160M licence leak: September, outside window.
  - Cifas H1 2026: August, outside window. FATF plenary is 10-26/30, so no outcomes yet.
- **PSD3/PSR OJEU:** still no Official Journal notice found on 2026-10-12. The indicative EP plenary date of 2026-12-14 (logged 10-08) stands. Next check: Monday 2026-10-19.

## Override-worthy this cycle

1. **Japan's financial regulator told banks and crypto exchanges to stop accepting ID-document photos for remote KYC now, without waiting for the legal ban on 2027-04-01, and to read the ID chip instead. The trigger was a run of breaches that leaked licence images.** Account: company /. Angle: "Japan just concluded that a photo of an ID is no longer evidence of anything. Once the images leak, they become the attack kit. Chip reads and cryptographic credentials are where remote KYC goes next."
2. **Mexico: bank-fraud claims hit MXN 11.2bn in H1 2026, and identity-theft claims rose 18.8% year on year.** Account:. Angle: "Mexican customers claimed MXN 11.2bn in bank fraud in six months, about 7.5% of the sector's profits. Identity theft is the fastest-growing category, and the onboarding check is where it starts."

## New findings

### Pillar 1: Banking & Payments

(no new material in window. See Pillar 7 for Mexico bank-fraud data and Pillar 6 for the Japan FSA request.)

### Pillar 2: Identity orchestration

(no new material in window. A KuppingerCole "Identity Orchestration Beyond User Journeys" webinar ran 10-08. It is an event, not research output.)

### Pillar 3: EUDI / eIDAS2

(no new material in window. Launchpad 2026 is 10-29/30. No new ARF version or implementing act found.)

### Pillar 4: KYC / AML compliance

(no new material in window. The Japan FSA request (Pillar 6) is also an AML/KYC instrument under the Act on Prevention of Transfer of Criminal Proceeds. AMLA simplified-CDD roundtable expressions of interest close 10-18.)

### Pillar 5: Customer onboarding

(no new material in window. See the carried-in reusable-KYC conversion data in the notes above.)

### Pillar 6: Identity verification (IDV)

- **Japan's Financial Services Agency (FSA) asked financial institutions on 2026-10-09 to move remote identity verification to IC-chip reading immediately. It also asked them to stop accepting ID-document images "without waiting for" the 2027-04-01 date when the amended Act on Prevention of Transfer of Criminal Proceeds enforcement rules ban them.**
  - **The three requests:** (1) review cybersecurity, including third-party risk and incident response, in light of recent unauthorised-access incidents; (2) in remote verification, "thoroughly reconfirm" ID-document images and face photos for unnatural elements; (3) bring forward the switch to IC-chip reading.
  - **Trigger:** a run of unauthorised-access breaches at customer-facing services that leaked customer data including driver's-licence images. Press coverage cites the Times Car breach (a car-sharing service, disclosed 2026-09-28) and a Nippon Rent-A-Car incident.
  - **Crypto exposure:** a JinaCoin survey of 9 major Japanese crypto exchanges found 8 still accept image upload (Coincheck, bitFlyer, bitbank, GMO Coin, SBI VC Trade, Mercoin, Binance Japan, BitTrade). Only Rakuten Wallet has dropped it.
  - **Precedent:** Japanese mobile carriers already stopped image-based verification on 2026-04-01.

  **Why it matters:** a G7 financial regulator is officially treating document-image KYC as compromised. Once licence images leak at scale, they become reusable fraud material, so "upload a photo of your ID" stops proving possession. The regulator's answer is cryptographic proof: read the chip and verify its signature. That is the logic behind wallet credentials and EUDI-style attestations. It also links to the IDScan.net licence leak (September) and the Korean bank breach (10-08 delta). Leaked identity data is now the input to the next onboarding attack.
  - Source (primary): https://www.fsa.go.jp/news/r8/sonota/20261009/20261009.html
  - Source: https://www.itmedia.co.jp/news/article/2610/09/2000002166/
  - Source: https://www.watch.impress.co.jp/docs/news/2147233.html
  - Source: https://jinacoin.ne.jp/fsa-identity-verification-20261010/
  - Date: 2026-10-09
  - **Drafting cautions:**
    - It is a request (要請), not a new legal deadline. The binding date is still 2027-04-01.
    - The Times Car figures conflict across outlets (~1.6M licence-verification records in ITmedia vs 6.6M total records in Impress Watch). Do not quote a number without saying which.
    - The FSA notice itself does not name Times Car. The incident attribution comes from press coverage.
    - Japan is not an ICP market. Frame it as a regulator signal, not a customer story.

### Pillar 7: Fraud / Deepfakes

- **Mexico: bank customers claimed MXN 11,213m (~11.2bn) for possible fraud in H1 2026, up 4.64% year on year. Identity-theft claims were the fastest-growing category: 18,663 cases (+18.8%) totalling MXN 691m (+8.9%).**
  - **Volume:** 2.52 million fraud claims (vs 2.48m in H1 2025, +1.4%), with an average loss of about MXN 4,300 per victim.
  - **Scale vs profits:** claims equal about 7.5% of the banking sector's H1 2026 profits (MXN 149,120m).
  - **AI-assisted fraud (vendor data):** AI-assisted fraud sessions rose from 2% (Q1 2023) to 32% (early 2026), projected at 65% by end-2026.
  - **Other:** Mexico accounted for ~70% of LATAM QR-phishing ("QRishing") activity in H1 2026.

  **Why it matters:** fraud claims are growing slowly, but identity theft is growing four times faster. In Mexico's biggest banking market, the losses are shifting from payment fraud to impersonation at account opening and recovery. That matches the CNBV Anexo 71 biometric requirement due in early November. It gives a current, local figure to anchor posts on.
  - Source: https://expansion.mx/economia/2026/10/09/fraude-bancario-imparable-en-mexico-clientes-reclaman-11-213-mdp-en-el-primer-semestre-de-2026
  - Date: 2026-10-09
  - **Drafting cautions:**
    - The underlying data is Condusef (Buró de Entidades Financieras) with CNBV profit data, compiled by Expansión. Cite "Condusef data" for the claims figures. The primary Condusef table was not read directly.
    - "Claimed" (reclamado) is not "lost". Do not call MXN 11.2bn fraud losses.
    - The AI-session stat comes from Incode, a LATAM IDV competitor. Use it only as "industry data", never name the vendor, and treat it as vendor-sourced.
    - Supersedes the standing "Condusef +18% Jan–May" anchor for H1 figures. Do not mix the two periods.

### Pillar 8: Mobile trust & app security

(no new material in window. An Anatsa Google Play PDF-reader campaign (Zscaler, 10-09) repeats a pattern already logged as standing context.)

### Pillar 9: Passwordless / split-key

(no new material in window. Authenticate 2026 is 10-19/21.)

### Pillar 10: ZKPs in practice

(no new material in window)

### Pillar 11: Age assurance & privacy attributes

(no new material in window. The Ofcom over-16 rapid assessment is still due end-October.)

## Open watch items

- **Japan FSA:** whether the major crypto exchanges announce dates to drop image upload; any FSA follow-up or Times Car figure confirmation.
- **DHS RIVR-2:** IDV/SMTD applications close 2026-10-16.
- **AMLA simplified-CDD roundtables:** expressions of interest close 2026-10-18; sessions 11-09 and 12-02.
- **PSD3/PSR OJEU:** next check 2026-10-19; indicative EP plenary 2026-12-14.
- **2026-10-19/21:** Authenticate 2026, Carlsbad.
- **2026-10-20:** Japan My Number Card on Android (target).
- **2026-10-26:** BCB MED 2.0 / IN BCB 766 Pix changes take full effect.
- **2026-10-26/30:** FATF plenary, Paris. Outcomes expected about 10-30.
- **2026-10-29/30:** EUDI Launchpad 2026, Brussels.
- **End-October:** Ofcom over-16 age-assurance rapid assessment.
- **2026-10-31:** ECB SSM-2026-0301 action-plan deadline.
- **Early November:** CNBV Anexo 71 biometric compliance deadline. Pairs with today's Condusef identity-theft data.
- **2026-11-09:** Apple Cash reload ID check goes live.
- **2026-11-18:** EUDI ARF Iteration 6 closes.
- **2026-12-24:** EUDI wallet-availability deadline (73 days).
- **South Korea AI-agent bank breach:** police forensic confirmation of the Artex attribution; FSC guidance.
