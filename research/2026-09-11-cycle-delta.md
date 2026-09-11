# Cycle Delta — 2026-09-11

Window: 2026-09-09 → 2026-09-11 (last 48 hours)

## Provenance and integrity notes

- **The effective new surface is Wednesday 2026-09-10 at both outlets.** The ID Tech Digest for September 10 covers Steam Australia age checks, Philippine PhilSys social media proposals, Microsoft passkey-themed social engineering, UIDAI Aadhaar SDK, Germany d-you wallet, Delhi High Court GST biometrics, and Safetrust Aliro. **Nothing has printed at either outlet dated 2026-09-11 as of run time.** Tuesday 09-09 was captured in full by the 09-10 delta.
- **⚠️ PRIMARY-SOURCE CONFIRMATION — the Microsoft passkey social-engineering advisory was published on 2026-09-09 by the Microsoft Security Blog**, a first-party primary source. The ID Tech coverage of it is dated 09-10. Both are in-window. The Microsoft Security Blog is the citation to use; the ID Tech article is secondary.
- **✅ WATCH ITEM RESOLVED — California AB 1856 signed 2026-09-10.** Governor Newsom signed the bill as part of a child safety package. AB 1043 (the underlying Digital Age Assurance Act) remains effective 2027-01-01; AB 1856 is an amendment. Both are now signed law.
- **⚠️ Competitor-naming constraints — none hard this cycle.**
  - **Veriff** appeared in the ID Tech Sept 10 digest (Veriff / Parchment transcript integration). Veriff is on the `competitors.md` DIRECT list. Not counted.
  - **Steam/Valve** is a gaming platform, not an IDV vendor, and is not on `competitors.md`. Freely nameable.
  - **UIDAI, the Delhi High Court, PhilSys/PSA, Governor Newsom, Roblox, and Microsoft** are freely nameable.
- **Checked and rejected — IDNow EUDI Wallet Consumer Survey.** IDnow published findings from a Sapio Research survey (June 2026, 2,000 adults, France and Germany) on September 8. IDnow is a directly adjacent IDV/eIDAS vendor. The survey is vendor-commissioned with no published methodology breakdown; findings (46% abandon complex flows, 40% cite fraud protection) overlap with corpus-standing onboarding stats. Rejected on identical grounds to prior vendor surveys. Not re-litigated.
- **Checked and rejected — PSD3/PSR.** Monday-only check; today is Thursday. No check run. **Next check Monday 2026-09-14.**
- **Checked (out of window), noted — IDScan class actions.** Nine putative class actions were docketed in the Eastern District of Louisiana between 2026-09-02 and 2026-09-04 (case numbers 2:26-cv-01929 to 2:26-cv-01956, non-contiguous). All nine were filed outside this window. **No new docketings confirmed for the 09-09 to 09-11 window.** The 9-suit total is new corpus detail but the filings are not in-window findings. Watch item updated below.
- **Checked and rejected (off-ICP):** Delhi High Court order requiring biometric Aadhaar authentication for all new GST registrations in India — interesting governance action, not an ICP market. **UIDAI native Aadhaar face SDK launch (Android/iOS, on-device liveness)** — same, off-ICP.
- **Noted, not counted (EUDI background):** IDnow published a country-readiness report showing wallet deployment status per member state; Germany's d-you wallet appeared in the digest but without new dates or specs beyond the corpus anchor (January 2, 2027 launch, €79.3m allocated). No increment over what was logged on 09-03.
- **Brazil ANPD / TikTok** — appeal window expires approximately 2026-09-12 (tomorrow). No published outcome as of run time. Watch item held.
- **Croatia alcohol age check** — implementation deadline 2026-09-15 (four days). No implementation-result reporting yet. Watch item held.

## Override-worthy this cycle

1. **Microsoft's own security team has published that the primary attack on enterprise passkey deployments is not cryptographic — it is social engineering the enrollment process itself, and it is active across multiple sectors.** Account: / company. Angle: the advisory does not say passkeys failed. It says they never got the chance. An attacker who poses as IT support and tricks an employee into completing device-code authorization or "setting up" their passkey has bypassed the cryptography before it could engage. The phishing-resistance of a passkey begins at the identity check performed during enrollment, and that check is the gap. Pairs directly with the Singpass finding from 09-10 (passkeys don't retire the OTP because recovery paths remain phishable) — both say the same thing from opposite directions: the weakest point in a phishing-resistant credential is always the human and the enrollment layer, never the cryptographic object itself.

2. **California has now defined in law which operating systems are responsible for surfacing age signals to apps — and the answer is the commercial ones.** Governor Newsom signed AB 1856 on 2026-09-10. Open-source operating systems (Debian, Fedora, Ubuntu, Arch and equivalents) are explicitly exempt; Windows, macOS, iOS and Android remain fully in scope. Account: company /. Angle: the legislature did not exempt open-source because Linux cannot do age verification — it can. The exemption exists because the law requires an accountable, commercial operator. This is the same logic that regulators in France, the UK and Australia are landing on: the person responsible for the age gate is the party who can be fined for not having one. The question for every B2B buyer is whether their identity infrastructure is built to be that accountable party or to depend on one.

3. **Australia set a September 9 deadline for gaming platforms to verify adult users, and two platforms that met it chose opposite architectures.** Epic built four routes — facial age estimation, payment card, government ID, and bank confirmation — none of which retains biometric data at the platform. Steam built one: a valid Australian credit card, which reportedly excludes roughly 65% of Australians using debit cards or PayPal, and which keeps the card on file to maintain verification. Account: company. Angle: one mandate, one deadline, two implementations — one designed for breadth and one for operational simplicity. The exclusion rate is the real story. Age assurance that does not cover 65% of the addressable population is not assurance; it is a compliance artefact. And every buyer who asks "what percentage of our users can you verify?" is asking the same question.

## New findings

### Pillar 1: Banking & Payments

(no new material — PSD3/PSR Monday-only check skipped; no EBA, ECB or AMLA publication dated in window. The FinCEN/mDL watch item (09-10 delta) remains open: no US bank has announced mDL acceptance at account opening yet, and NIST SP 1800-42 has not published. ECB SSM-2026-0301 action plan deadline 2026-10-31 — 50 days. Still the strongest un-used banking hook in the corpus.)

### Pillar 2: Identity orchestration

(no new material — searched analyst coverage, orchestration platform moves and agentic identity. Forrester CIAM Wave still kicking off end of September 2026; nothing published. The Microsoft passkey-social-engineering advisory is counted under Pillar 9 and cross-referenced here: the attack succeeds precisely because the orchestration layer — who is allowed to enroll what credential on which account — has no strong identity check at the time of enrollment.)

### Pillar 3: EUDI / eIDAS2

- **An EU-funded research consortium has published its first assessment of whether the EUDI Wallet's privacy model can hold in the real world when combined with zero-knowledge proofs, homomorphic encryption and differential privacy (September 2026).** The **TrustED** project — a 37-month EU-funded consortium — is testing **EUDI Wallet** implementations alongside privacy-enhancing technologies including **zero-knowledge proofs** (attribute proof without underlying data disclosure), **homomorphic encryption** (computation on encrypted data without decryption) and **differential privacy** (aggregate-level inference resistance). The project is explicitly structured to test real-world deployability, not just technical feasibility: "TrustED tests whether Europe's digital identity model can preserve privacy in the real world." Key design claim: a user can prove a requirement (e.g. age above a threshold) without revealing the underlying data attribute (e.g. date of birth), and can share verified claims from the EUDI Wallet without disclosing the full credential. The project aligns with the EUDI Wallet ecosystem, eIDAS2 and the GDPR. **Why this matters for Ditto:** the EUDI corpus to date has been about deadlines, ARF versions and member-state rollout. TrustED is the first in-corpus assessment of whether the *privacy architecture* the ARF specifies can actually be deployed and used. The wallet's design promises selective disclosure; the question TrustED is answering is whether that promise is operational. If ZKPs in EUDI can produce regulator-accepted attribute proofs without exposing full credentials, the market changes: every relying party that currently demands a full document scan to verify one attribute will have a privacy-preserving alternative mandated into the infrastructure they must connect to by December 2027. **Constraint: this is a research project publishing findings, not a regulator action or market deployment. Do not write that ZKPs are in EUDI Wallets now — they are being tested for integration.**
  - Source: https://www.biometricupdate.com/202609/trusted-tests-whether-europes-digital-identity-model-can-preserve-privacy-in-the-real-world
  - Date: 2026-09-10 (Biometric Update coverage)
  - **Verification note: obtain the TrustED project primary at trustedproject.eu before quoting findings directly. The Biometric Update coverage is the trade source; the project's own published results are the citation.**

Standing EUDI anchors unchanged: wallet-availability deadline **2026-12-24 (103 days)**; relying-party acceptance December 2027; Germany 2027-01-02. **EUDI Relying Party Engagement Programme first webinar "Travel Across Europe" 2026-09-18 (7 days).**

### Pillar 4: KYC / AML compliance

(no new material — AMLA, FATF, sanctions all clear. AMLA Article 28(1) CDD RTS Commission endorsement still expected Q4 2026. AMLR applies 2027-07-10.)

### Pillar 5: Customer onboarding

(no new material)

### Pillar 6: Identity verification (IDV)

(no new in-window primary material — IDScan class action update is out-of-window (suits filed Sept 2-4); see provenance notes. Watch items updated below.)

### Pillar 7: Fraud / Deepfakes

(no new material — no Sumsub, iProov, Veriff or FATF primary in window. The Microsoft passkey-social-engineering finding is counted under Pillar 9; see cross-reference there.)

### Pillar 8: Mobile trust & app security

(no new material — seventh consecutive cycle. Pillar 8 sweeps are producing no datable material on a daily cadence. Per prior recommendation: move to a weekly sweep.)

### Pillar 9: Passwordless / split-key

- **Microsoft's Security team published an advisory on 2026-09-09 documenting a social engineering campaign that targets passkey enrollment rather than passkey cryptography — attackers pose as IT support staff, create urgency around an authentication setup requirement, and use the resulting trust to capture session tokens or enroll an attacker-controlled device.** The Microsoft Security Blog primary is dated **2026-09-09**. The campaign has been observed **since May** across multiple organisations. Attack flow: a target receives an urgent call or message claiming a security configuration is required; they are directed to a fraudulent sign-in page or persuaded to complete a **device-code authorization flow**; the attacker captures a session token via an **adversary-in-the-middle phishing proxy**, or tricks the user into completing an **OAuth device-code consent** that grants the attacker access. Post-compromise persistence: the attacker **registers an additional authentication method** (biometric passkey, software TOTP, or enrolled device) on the compromised account, so that changing the password does not restore exclusive access. Data extraction then proceeds via **Microsoft Graph, SharePoint and OneDrive APIs**. Microsoft's statement that requires quoting exactly: **"the campaign generally does not break passkey cryptography or interfere with a genuine passkey enrollment — the threat lies in the social engineering tactics used to deceive users rather than in compromising the passkey technology itself."** **Why this matters for Ditto:** this is the clearest primary-source documentation in the corpus of the identity-before-authentication dependency. The cryptographic strength of the passkey is not the attack surface — the identity check that should have run *before* the passkey was enrolled is. If the enrollment event is social-engineered, the relying party has bound a cryptographic key to the wrong person, and the phishing-resistance property of the passkey protects the attacker's continued access, not the legitimate user's. **The two-line argument for an identity vendor: a passkey is only as phishing-resistant as the identity verification that happened at enrollment. A stolen-enrollment passkey is more durable than a stolen password, because it survives a password reset.** Pairs directly with the Singpass finding from 09-10 (passkeys don't retire SMS OTP because account recovery remains phishable); pairs with the agentic access-control finding from 09-03 (delegation without strong identity at the human end creates the seam). Cross-pillar with Pillar 7 (adversary-in-the-middle phishing remains the delivery mechanism).
  - Source (primary): https://www.microsoft.com/en-us/security/blog/2026/09/09/passkey-themed-social-engineering-leads-identity-cloud-compromise/
  - Source (trade): https://idtechwire.com/microsoft-tracks-passkey-themed-social-engineering-behind-cloud-data-theft/
  - Date: 2026-09-09 (primary); trade coverage 2026-09-10

### Pillar 10: ZKPs in practice

(no new material standalone — see Pillar 3 for the TrustED EUDI + ZKP pilot, which is the most significant ZKP-in-practice development in this cycle. The corpus of ISO/IEC free standard access (09-03) and the FinCEN VDC definition (09-10) both remain the strongest prior-cycle items for ZKP framing.)

### Pillar 11: Age assurance & privacy attributes

- **Governor Newsom signed California AB 1856 on 2026-09-10, amending the Digital Age Assurance Act to exempt open-source operating systems from the age-signal mandate — defining the commercial platform as the legal accountable party for surfacing age data to apps.** The bill was enrolled and sent to the Governor on 2026-09-04. The amendment modifies the definition of "operating system provider" under the **California Digital Age Assurance Act (DAAA)**, explicitly excluding open-source systems — **Debian, Fedora, Ubuntu, Arch and equivalents** are named in coverage as out of scope. **Windows, macOS, iOS and Android remain fully in scope** under the DAAA for the 2027-01-01 effective date. The signed bill was part of a package Newsom described as "the strongest child safety chatbot and social media laws in the nation." **The structural read is not that California has weakened age verification.** It has done the opposite: it has defined the accountability perimeter. Open-source is out not because it lacks technical capability — Linux distributions ship FIDO2, passkeys and secure enclaves — but because the DAAA requires an **accountable commercial entity** that can be regulated, audited and penalised. **For an identity vendor this resolves an ambiguity the bill introduced**: any buyer building on or distributing through a major commercial OS now operates within a state law that requires an age-signal API to be available to their apps — and that signal must be provided by the OS, not engineered around it. The question becomes which stack they are building on and whether their own service sits above or below the OS-level signal layer.
  - Source: https://www.gov.ca.gov/2026/09/10/governor-newsom-signs-the-strongest-child-safety-chatbot-and-social-media-laws-in-the-nation/
  - Source: https://calmatters.digitaldemocracy.org/bills/ca_202520260ab1856
  - Date: 2026-09-10 (signed)
  - **Verification note: obtain the enrolled bill text to confirm the exact definition of "operating system provider" and the open-source exclusion clause. Coverage is consistent across sources but the statutory language is the citation.**

- **Steam implemented Australia's R18+ age-verification requirement with a single route — a valid Australian credit card that must remain on the account — and the exclusion rate is roughly 65% of Australians.** Valve's **Steam** introduced mandatory credit-card age verification for Australian users seeking to view, search or purchase **R18+-rated titles** on or around **2026-09-09**, the statutory deadline under Australia's **Age-Restricted Material App Distribution Services Code**. The check requires users to add a **valid Australian credit card** (not a debit card, not PayPal, not an international card) and to **keep it on the account** — removing the card returns the account to under-18 status. Existing purchases of R18+ titles are unaffected. **The exclusion figure:** multiple outlets cite approximately 65% of Australians as not meeting the single-route check because they do not hold, or do not choose to register, a qualifying credit card. **The structural contrast this cycle:** Epic Games Store met the same deadline one week earlier with four parallel routes — facial age estimation, payment card, government ID document, and bank-backed age confirmation via ConnectID (logged 09-09 delta as "a global games storefront"). Steam met the same deadline with one. **Neither response is necessarily non-compliant with the Code as written.** The Code requires "robust age assurance" — it does not prescribe routes. The question for a regulator is whether a check that cannot verify the majority of the addressable user base qualifies. **For an identity vendor this is the clearest real-world demonstration of the tradeoff buyers face:** a multi-route approach reaches more users, costs more to build and operate, and gives regulators less to object to; a single route costs less, excludes more, and shifts the compliance risk onto the platform. **Do not imply Steam is non-compliant — the eSafety Commissioner has not made that determination.**
  - Source: https://www.ghacks.net/2026/09/10/steams-age-verification-in-australia-only-accepts-credit-cards-excluding-half-of-consumers/
  - Source: https://idtechwire.com/steam-uses-credit-cards-for-australias-new-r18-age-checks/
  - Source: https://www.gamingonlinux.com/2026/09/age-verification-for-steam-rolls-out-in-australia-requiring-a-credit-card/
  - Date: 2026-09-09 (rollout); 2026-09-10 (coverage)
  - **Do not imply eSafety has found Steam non-compliant. Write "excludes users who do not hold an Australian credit card" — the exact exclusion figure varies by source, use ≈65% only if attributed.**

- **Philippine agencies opened a public consultation on using PhilSys — the national ID backed by biometric enrollment — as the authentication layer for social media age checks, and Roblox has already agreed to integrate it.** The **Department of Information and Communications Technology (DICT)** and the **Cybercrime Investigation and Coordinating Center (CICC)** convened a town hall on **2026-09-10** to develop proposals for legislation on children's social-media access. The proposed framework: **prohibit children under 13** from social media, and require **parental consent and oversight tools for users 13 to 17**. The **Philippine Statistics Authority (PSA)** confirmed that **PhilSys** — which issues a unique identity number backed by demographic and biometric enrollment — could establish the age and identity of the person opening or managing an account. **Roblox** has already agreed to integrate the Philippine national ID for age checks. The **DICT** is also formally requesting **Meta** to integrate PhilSys across Facebook, Instagram, Messenger, WhatsApp and Threads. **Two structural reads.** First, **PhilSys is being proposed as a national government-run identity layer that sits above the platform and resolves the account-ownership ambiguity the Irish investigation into X identified** — if the ID is the authentication source, self-declaration goes away as a defence. Second, **this is the fourth jurisdiction in four cycles to use age assurance as the forcing function for biometric national-ID integration into commercial platforms** — after the UK (device-level legislation, 09-10), Ireland (Coimisiún na Meán, 09-10) and Australia (eSafety codes). The Philippines is not in the EU and not subject to eIDAS, but the pattern is the same. **Constraint: this is a consultation and proposed legislation, not enacted law. Roblox agreement is announced but not verified as a live integration.**
  - Source: https://idtechwire.com/philippine-agencies-discuss-philsys-based-age-checks-for-social-media/
  - Date: 2026-09-10

## LATAM

(no new material — CNBV, Superfinanciera, CMF, SBS, BCB, Pix all clear. The Brazil ANPD TikTok appeal window expires approximately 2026-09-12 (tomorrow); no published outcome as of run time. Watch item held.)

## Open watch items

- **Brazil ANPD / TikTok — URGENT, expires ~2026-09-12 (tomorrow).** Appeal window closes. Watch for (a) whether ByteDance has filed, (b) ANPD confirmation of receipt, (c) whether the 22-platform audit produces any parallel action. **This is the nearest trigger in the corpus.**
- **Croatia alcohol age check — 2026-09-15 (4 days).** September 15 deadline for retailers to implement m-Gradani QR-code age checks online. Watch for (a) penalty detail, (b) whether the tourist/OIB exclusion is published in guidance, (c) implementation reporting.
- **Secure ID Forum 2026 — Istanbul, 2026-09-15/16 (4 days).** Government-and-industry forum. Watch for substantive policy announcements from government speakers.
- **Biometric Update × Goode Intelligence age-assurance webinar 2026-09-15 (4 days).** The 2026 Age Assurance & Digital Age Credentials Market Report is the item to obtain.
- **GSA PQC Summit 2026-09-16 (5 days).** Post-quantum cryptography policy outputs.
- **CIMB SecureTAC OTP sunset — 2026-09-19 (8 days).** All web transfers and online card payments must use biometric or passcode app approval from this date; password approval ends. Watch for customer-impact reporting. Pairs with Singpass Android expansion (09-10 delta): same week, two opposite postures on OTP.
- **EUDI Relying Party Engagement Programme — first webinar "Travel Across Europe", 2026-09-18 (7 days), 14:00–15:30 CET.**
- **UK device-level child safety legislation — NEW last cycle, highest near-term UK watch.** Watch for (a) bill introduction and title, (b) whether the obligation lands on the OS vendor or the app, (c) whether it references the Windows/Apple/Google age APIs as the compliance mechanism.
- **Australia IDLock privacy consultation — closes 2026-09-18 (7 days).** National rollout 2027.
- **Ofcom NCII/deepfake enforcement — compliance deadline 2026-09-30 (19 days).** Hash-matching must be operational for covered services.
- **US DOL / unemployment insurance — Group 1 states (25) must onboard to enhanced federal ID verification by 2026-09-30 (19 days).**
- **California AB 1856 — RESOLVED (signed 2026-09-10).** AB 1043 effective 2027-01-01.
- **Utah SB73 / Aylo — stipulation expires 2026-10-22 (41 days)** or on Judge Barlow's ruling.
- **ECB SSM-2026-0301 action plan deadline — 2026-10-31 (50 days).** Obtain the ECB primary. Still the strongest un-used EU banking hook; the drafting window is closing.
- **DNP / Austriacard — Austrian FDI clearance.** Quarter ending September 2026 closes in 19 days.
- **FinCEN mDL/VDC FAQs follow-up (09-10 delta).** Watch for (a) first US bank to announce mDL acceptance, (b) NIST SP 1800-42 final publication, (c) EBA or FCA equivalent guidance.
- **Coimisiún na Meán v X (09-10 delta).** Watch for X's promised ID verification "within weeks" and the investigation outcome.
- **Australia digital duty of care (09-10 delta).** Watch for bill text and eSafety enforcement posture shift.
- **IDScan.net breach — 9 class actions filed Sept 2-4.** Watch for (a) FTC or state AG action, (b) formal breach notification and affected-individual count, (c) any regulator using this to question IDV retention practices generally.
- **Forrester CIAM Wave — kicks off end of September 2026.** First orchestration-relevant analyst event on the calendar.
- **AEPD / Yoti appeal (09-10 delta) — Audiencia Nacional.** Watch for appeal outcome and whether any other DPA adopts the Article 9 biometric-consent reading.
- **RAND Europe "Novel Technologies" report — obtain PDF.** Pairs with EUDI wallet data-sovereignty question.
- **PSD3/PSR — twentieth cycle, no OJEU notice. Monday-only check: 2026-09-14.**
- **AMLA Level 2** — Commission endorsement Q4 2026; AMLR applies 2027-07-10.
- **EUDI wallet-availability deadline 2026-12-24 (103 days).** Germany 2027-01-02; relying-party acceptance December 2027.
- **EUDI attestation-issuer registrations** — Poland remains the only logged registration.
- **Biometrics Institute "On the Pulse" on watchlists — 2026-09-30 (19 days).**
- **FIDO wallet certification programme** — no published spec or date.
- **Meta consent judgment** — still unresolved $17bn vs $18bn. Use California AG figure.
- **EES operational failure** — safeguard expired 2026-09-06, IATA refused extension. Watch for Commission action.
- **ToxicPanda, OverlayPhantom, TsarBot, CopyBara, PixBankBot** — all out of window; strong P8 candidates on any follow-up.

## Run summary

- **Findings count by pillar:** 4 findings across 3 pillars — P9 Passwordless (1: Microsoft passkey social-engineering advisory — primary, dated 09-09); P3 EUDI (1: TrustED ZKP-EUDI real-world pilot, dated 09-10); P11 Age assurance (3: California AB 1856 signed 09-10; Steam Australia credit-card-only R18+ check 09-09/10; Philippines PhilSys social media consultation 09-10). P1, P2, P4, P5, P6, P7, P8, P10 and LATAM: no new material.
- **Override-worthy:** (1) Microsoft Security Blog on passkey social-engineering enrollment attacks — phishing-resistance begins at identity verification, before the passkey is issued; (2) California AB 1856 signed — commercial OS platforms are in, open-source is out, accountability perimeter now defined by law; (3) Steam vs Epic Australia — same mandate, same deadline, two architectures, 65% exclusion rate illustrates what minimum-viable compliance costs in reach.
- **Delta path:** research/2026-09-11-cycle-delta.md
