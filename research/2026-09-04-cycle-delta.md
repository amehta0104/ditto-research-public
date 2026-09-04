# Cycle Delta — 2026-09-04

Window: 2026-09-02 → 2026-09-04 (last 48 hours)

## Provenance and integrity notes

- **The effective new surface is a single day: 2026-09-03.** The 09-03 delta ran at ~10:00 UTC and captured the 09-02 print. Biometric Update and ID Tech then published **seventeen articles dated 2026-09-03**, almost all of which postdate that run. **Nothing has printed at either outlet dated 2026-09-04 as of run time.** Three business days in five have now been dense print days (08-31, 09-02, 09-03).
- **Already logged, not re-reported:** Authologic / Poland EUDI attestation-issuer registration (09-03 delta, Pillar 3), ISO/IEC free mDL and verifiable-credential standards (09-03 delta, Pillar 4), Nexus / 153m driving-licence scan dump (09-03 delta, Pillar 6), Handwave × Visa palm/token binding (09-03 delta, Pillar 1). All four re-surfaced in the 09-03 print cycle; none is new.
- **⚠️ Competitor-naming constraints this cycle are heavy — three of nine findings touch named vendors on or adjacent to `competitors.md`.**
  - **Yoti (Pillar 6/11)** — not on `competitors.md` but functionally a direct age-assurance/IDV competitor and the UK market's most visible one. The *regulatory ruling* is the story, not the vendor. Draft it as "a certified UK age-assurance provider withdrew from Spain" and let the AEPD decision carry the post. **Do not frame as a competitor stumble** — the ruling cuts against Ditto's whole category, including Ditto.
  - **Mitek (Pillar 7)** — not on `competitors.md`; adjacent IDV/liveness vendor. The LivDet-Face 2026 result is usable as *benchmark* evidence that passive liveness now works, but **do not name the top-ranked vendor**. Write it as "independent academic PAD benchmarking".
  - **Idemia (Pillar 2)** — not on `competitors.md`; the JV consolidation pattern is the finding, not the firm. **Thales/Gemalto is on the adjacent list** and Idemia sits in the same government-ID lane — treat with the same care.
- **⚠️ Yoti / AEPD — one figure needs care before drafting.** The fine is **€950,000**, levied **June 2026**; the app withdrawal is **effective 2026-09-10** (i.e. still in the future at time of writing — do not write it in the past tense). The appeal is live at the **Audiencia Nacional**. The €950k fine itself is **out of window** as an event; the withdrawal decision and its stated rationale are the in-window news.
- **⚠️ UK OfDIA guidance — the legal status of "derived credentials" is unresolved and that is the entire point.** OfDIA's updated guidance does not say private wallets are barred from primary credentials; it says DVS providers get derived credentials *"at least at first."* Do not overstate it as a ban. The AVPA's characterisation ("a material risk of a two-tier system", prior threat of action under the **Subsidy Control Act 2022**) is an interested party's reading — attribute it, don't assert it.
- **Checked and rejected — the Shufti "495% deepfake surge / +3,900% document deepfakes" cluster.** Same family as the "$3.7bn / 11% of global fraud" cluster the 09-03 delta rejected. Vendor-proprietary, projection not measurement, no methodology published. **Do not use.**
- **Checked and rejected (out of window):** OverlayPhantom (180+ apps, 10 countries, ID Austria dropper — Cyble, May 2025 onward, no in-window publication); Socure $156m raise at $5.2bn + Fravity acquisition (2026-08-27, one week out); Entrust 2026 Identity Fraud Report "injection attacks +40% YoY" (report is H1 2026).
- **Checked and rejected — PSD3/PSR OJEU publication.** Fifteenth consecutive cycle with no notice number. Secondary sources still say "June or July, potentially slipping to September". Nothing has published.
- **Noted, not counted (off-ICP):** Papua New Guinea digital IDs for ~140,000 public servants by year-end; Philippine police proposal for PhilSys biometric checks before SIM activation; Albania ALBTraceCo mandate expansion; World Bank finding 2.8bn still excluded from digital ID.
- **Noted, not counted (thin):** Biometric Update's "Asia-Pacific digital identity rollout reveals widening regional divide" — survey framing, no new primary data.

## Override-worthy this cycle

1. **The UK just told the certified private identity industry it can have copies of the government's credentials, not the credentials themselves — and opened a sandbox on the same day.** OfDIA's updated guidance gives DVS-certified providers access only to *derived* credentials built from GOV.UK Wallet data, while primary credentials like the mDL appear to stay exclusive to the state wallet. Account: / company. Angle: the UK spent a year building a statutory certification regime for private identity providers, and the first thing it certified them for was second-hand data. The question every regulated buyer should now ask their identity vendor is *which* credential you are actually receiving.

2. **A European regulator has ruled that estimating someone's age from their face is special-category biometric data — and a certified provider is leaving the market rather than comply.** The AEPD's reading of GDPR pulls facial age estimation into Article 9 and requires a non-biometric alternative; the provider's answer is that PINs, passwords and SMS OTPs "can be easily shared, stolen or compromised." Account: company /. Angle: this is the sharpest statement yet of the privacy-versus-security trap in age assurance — and it is the exact trap zero-knowledge proofs exist to escape. You cannot be ordered to offer a weaker alternative to a check that never retained the data in the first place.

3. **The zero-knowledge proving stack that runs on a phone, offline, with post-quantum security, is now open source.** World released ProveKit — client-side ZK proofs for claims like legal age or nationality, built in Noir, 128-bit post-quantum, seconds to generate, runs on constrained devices. Account: / company. Angle: the standard objection to ZKPs in banking has always been "too slow, too heavy, not on a handset, not quantum-safe." That objection just became checkable against published code.

## New findings

### Pillar 1: Banking & Payments

- **A major Southeast Asian bank is switching off password approval for online transactions entirely and routing every web and merchant-site payment through an app-based biometric approval on the customer's phone.** CIMB will require SecureTAC approval — Face ID, fingerprint or device passcode inside the CIMB OCTO app — for all transactions initiated via CIMB Clicks Web and merchant websites from **2026-09-19**. Passwords will no longer be accepted as an authentication method; customers with neither biometrics nor a device passcode enabled will simply be unable to approve. The bank frames it as anti-fraud, not compliance — there is no cited regulatory mandate. **For an identity vendor this is the cleanest available example of a bank-initiated (not regulator-forced) credential sunset with a hard public date**, and it puts the authentication decision on the phone, which is where mobile threat defence becomes load-bearing rather than optional.
  - Source: https://www.thestar.com.my/tech/tech-news/2026/09/03/cimb-online-transactions-to-require-securetac-approval-via-biometrics-or-passcode-from-sept-19
  - Source: https://idtechwire.com/cimb-makes-app-based-authentication-mandatory-for-online-transactions/
  - Date: 2026-09-03 (effective 2026-09-19)

### Pillar 2: Identity orchestration

- **An immigration-services giant, a Swiss secure-identification firm and a government biometrics supplier are assembling a single end-to-end identity platform out of three separate companies in under two months.** Fragomen (6,000+ professionals, 70+ offices) and SICPA announced their joint venture in **July 2026**; on 2026-09-03 they added **Idemia Public Security** (600+ government agency customers), bringing biometrics into a stack that already spans identity verification, document authentication, verifiable credentials, digital wallets and credential lifecycle management. Target use cases: workforce mobility, travel, hospitality, education, IAM, document digitalisation, humanitarian programmes. No financial terms disclosed. **This is the consolidation thesis playing out in public — three vendors bolting together the exact functional stack Ditto ships as one platform**, and doing it because buyers have stopped wanting to integrate five vendors themselves.
  - Source: https://www.biometricupdate.com/202609/fragomen-sicpa-jv-adds-idemia-biometrics-to-assemble-end-to-end-identity-platform
  - Date: 2026-09-03 (JV announced July 2026)

- **A dedicated home computer for autonomous AI agents will require a biometric approval before the agent is allowed to take a higher-risk action — agentic identity is now shipping in consumer hardware, not just enterprise PAM.** PamirAI selected Precise Biometrics' FPC AllKey Pro to gate sensitive actions on its Linux-based "Agent Computer", which keeps long-running agent tasks alive when the user closes their laptop, with the agent operating other machines via PamirAI's AKVM. Consumer launch targeted **fall 2026**; manufacturing by Seeed Studio. **Second agentic-identity finding in two cycles** — the 09-03 delta logged an access-management vendor shipping privileged access controls for AI agents on employee machines. The pattern across both: the industry has converged on *human biometric approval as the checkpoint an agent cannot cross by itself*. That is a step-up authentication problem, and step-up is orchestration.
  - Source: https://idtechwire.com/pamirai-selects-precise-biometrics-for-agent-computer-approval-checks/
  - Date: 2026-09-03

### Pillar 3: EUDI / eIDAS2

(no new material — Poland/Authologic attestation-issuer registration and the five-country rollout cluster were both logged in the 09-03 delta)

### Pillar 4: KYC / AML compliance

(no new material)

### Pillar 5: Customer onboarding

(no new material)

### Pillar 6: Identity verification (IDV)

- **OfDIA's updated guidance indicates certified private providers will get only derived credentials from GOV.UK Wallet, while primary credentials such as the mobile driving licence stay with the state wallet — and OfDIA opened a developer sandbox the same day.** The guidance states that a DVS provider "also certified as a holder service... could use information from GOV.UK Wallet to create a new reusable digital identity document" — i.e. a secondary artefact derived from the government credential. The sandbox (test wallet app, document builder, credential issuer, certificate authority, test mDL) is open to providers already registered and certified against the trust framework; it explicitly cannot be used for penetration testing or performance evaluation. The **Age Verification Providers Association** warns of "a material risk of a two-tier system" and has previously threatened action under the **Subsidy Control Act 2022** on market-distortion grounds. **This lands three days after the DVS Trust Framework v1.0 came into force (2026-09-01) and six weeks after the national digital ID scheme was cancelled (2026-07-21)** — the certified private regime survived the scheme's death, and has now been handed a materially narrower role than the industry expected. Unless derived credentials are recognised in law as equivalent to primary ones, their utility is limited.
  - Source: https://www.biometricupdate.com/202609/uk-guidance-indicates-only-govt-digital-id-wallet-will-get-primary-credentials
  - Source (primary, sandbox): https://www.gov.uk/guidance/how-to-access-the-govuk-wallet-sandbox
  - Source (primary, technical): https://docs.wallet.service.gov.uk/verify-credentials/credentials-in-wallet
  - Date: 2026-09-03

- **A UK age-assurance provider is pulling its ID app out of Spain rather than comply with a data protection ruling that facial age estimation is special-category biometric data requiring a non-biometric alternative.** The AEPD fined Yoti **€950,000 (~$1.1m)** in **June 2026**, reading GDPR's biometric-data definition to cover facial age estimation and therefore requiring the provider to offer users a non-biometric route. Yoti's stated objection is that the mandated alternatives — "PINs, passwords and SMS or email OTPs" — "can be easily shared, stolen or compromised", so the remedy degrades security for minors. The app comes out of the Apple and Android stores in Spain on **2026-09-10**; Yoti is appealing at the **Audiencia Nacional** and hopes to return on a favourable decision. **This is a European DPA ordering an identity provider to make its product weaker on privacy grounds, and it is the strongest live argument in the corpus for architectures that prove an attribute without processing or retaining the biometric at all.**
  - Source: https://www.biometricupdate.com/202609/yoti-withdrawing-id-app-from-spain-to-avoid-undermining-biometric-security
  - Source: https://idtechwire.com/yoti-pulls-digital-id-app-from-spanish-stores-during-biometric-appeal/
  - Date: 2026-09-03 (fine June 2026; withdrawal effective 2026-09-10)

### Pillar 7: Fraud / Deepfakes

- **Independent academic presentation-attack benchmarking now shows passive liveness holding up against attacks it was never trained on — including 3D masks — with a leading algorithm recording zero successful attacks in a separate US government assessment.** LivDet-Face 2026, run by **CITeR** with **Clarkson University** and **UNC Charlotte**, tested PAD algorithms against undisclosed collections of genuine and attack images — printed faces, screen replays and 3D masks — specifically to measure generalisation beyond training data. One vendor took the top three places in the image category; the same vendor's algorithm recorded an **APCER of zero** in a separate US government evaluation, meaning no attack in that evaluation passed its liveness check. For comparison, the 2024 iteration's winner posted 4.93% average classification error. **The significance for an identity vendor is not the leaderboard — it is that "passive liveness can't stop determined attackers" is no longer defensible as a blanket claim, and that the independent benchmark, not the vendor datasheet, is now the citable authority.** Note that LivDet-Face measures *presentation* attacks; it does not measure injection attacks, which is where the harder deepfake problem sits.
  - Source: https://www.biometricupdate.com/202609/miteks-passive-liveness-impresses-in-biometric-image-benchmark
  - Date: 2026-09-03
  - **Naming rule: do not name the top-ranked vendor. Write it as independent academic PAD benchmarking.**

### Pillar 8: Mobile trust & app security

- **South Korea's three mobile carriers have jointly launched a month-long public campaign to move identity checks onto a QR credential with dynamic images, screen-capture prevention and time-limited validity — because forged and altered digital IDs are rising.** SK Telecom, KT and LG Uplus are pushing the QR feature in the **PASS** mobile ID app (10m+ subscribers, driving licences and resident identity cards) across **3,600+ community service centres**, with the campaign running to **2026-10-05**. The driver is stated as fraud, not regulation: "rising cases of forged or altered digital IDs". The countermeasures are all anti-screenshot / anti-replay — dynamic imagery, capture prevention, activation checks, time-limited verification. **This is the failure mode of first-generation "show a picture of your ID on your phone" schemes arriving at national scale, and the fix is cryptographic freshness — which is what a properly bound credential gives you for free.**
  - Source: https://www.biometricupdate.com/202609/koreas-telecom-giants-launch-qr-id-verification-campaign
  - Date: 2026-09-03 (campaign to 2026-10-05)

### Pillar 9: Passwordless / split-key

- **See Pillar 1 (CIMB SecureTAC).** A named bank retiring password approval for all web-initiated transactions on a public date (2026-09-19), by its own choice rather than regulatory compulsion, is the strongest passwordless data point in the corpus this quarter. No separate finding.

### Pillar 10: ZKPs in practice

- **World open-sourced ProveKit, an audited zero-knowledge proving toolkit that generates identity proofs on the user's own device — offline, on constrained hardware, in seconds, with 128-bit post-quantum security.** Built on **Noir** (developed by Aztec), it produces privacy-preserving proofs of selective claims — legal age, nationality, NFC-based passport possession — without the device contacting a server. World's own framing: "to our knowledge, no existing solution meets all these requirements" of post-quantum security plus a developer-friendly language plus mobile-first client-side proving. Small download, low memory, works offline. **Every standard objection to ZKPs in regulated onboarding — latency, handset feasibility, quantum durability, developer accessibility — is now answerable against published, audited code rather than a whitepaper.** For a vendor whose differentiators are "zero-knowledge proofs for privacy-by-design" and "quantum-ready", this is the year's most useful third-party validation.
  - Source: https://www.biometricupdate.com/202609/world-releases-open-source-toolkit-for-privacy-preserving-identity-proofs
  - Source: https://idtechwire.com/world-releases-mobile-first-zero-knowledge-toolkit-behind-world-id/
  - Date: 2026-09-03

### Pillar 11: Age assurance & privacy attributes

- **See Pillar 6 (Yoti / AEPD).** The AEPD's classification of facial age estimation as Article 9 special-category data, and the requirement to offer a non-biometric alternative, is the most consequential age-assurance regulatory development in the window. Counted once, under Pillar 6.

- **The FDA's first authorisations of flavoured e-cigarettes carry device-level age-verification conditions — the nicotine device stays locked until the user's age is confirmed on the device itself.** This moves age assurance from point-of-sale to point-of-use, with continuous re-checking on the hardware rather than a one-time gate at purchase. The FDA acknowledged in the same breath that "device restrictions are unlikely to be sufficient on their own for the most youth-appealing flavors." No enforcement deadline or numerical target published. **Thin on specifics but structurally interesting: a US federal regulator has now written repeated on-device age proof into a product authorisation**, which is the physical-goods analogue of the continuous-assurance argument, and a use case where a reusable privacy-preserving age credential is obviously superior to re-scanning a licence.
  - Source: https://www.biometricupdate.com/202609/age-verification-brings-the-privacy-debate-to-vaping
  - Date: 2026-09-03

## Open watch items

- **UK OfDIA derived-vs-primary credentials — the live one.** Watch for (a) any OfDIA or DSIT statement on whether derived credentials will be recognised in law as equivalent to primary, (b) whether the AVPA converts its Subsidy Control Act 2022 threat into an actual claim, (c) the first DVS provider admitted to the GOV.UK Wallet sandbox. Obtain the full OfDIA guidance primary from gov.uk before drafting.
- **Yoti / AEPD appeal at the Audiencia Nacional** — no hearing date published. Watch for the written AEPD decision text (the Article 9 reasoning on facial age estimation is the citable asset), for whether other DPAs adopt the same reading, and for the actual 2026-09-10 delisting. **If another EU DPA follows, this becomes a category-level event.**
- **ProveKit** — watch for the audit report, for adoption outside World's own stack, and for any OpenID4VP / ISO 18013-5 binding. Cross-check against the ISO/IEC free-standards release logged 09-03: cheap standards plus open ZK tooling is a genuine barrier-to-entry collapse.
- **LivDet-Face 2026** — obtain the CITeR results paper for the actual APCER/BPCER figures; the trade write-up does not publish the table. Watch for whether an injection-attack track is added.
- **ECB SSM-2026-0301 action plan deadline — 2026-10-31 (57 days).** Obtain the ECB primary. Still the strongest un-used banking hook in the corpus.
- **PSD3/PSR OJEU publication** — no notice number, fifteenth consecutive cycle. Any notice number is an immediate content trigger.
- **AMLA Level 2 package** — Commission endorsement expected Q4 2026; Article 28(1) CDD RTS is the item that matters. AMLR applies 2027-07-10.
- **FATF Travel Rule implementation guidance** — signalled for late 2026, no date.
- **EUDI wallet-availability deadline 2026-12-24 (111 days)** — Germany 2027-01-02; relying-party acceptance December 2027.
- **EUDI Relying Party Engagement Programme** — first webinar "Travel Across Europe", 2026-09-18, 14:00–15:30 CET.
- **EUDI attestation-issuer registrations** — Poland is the first logged. Watch the count of registered EAA issuers per member state.
- **Romania ROWallet** — phased rollout October 2026, full launch January 2027.
- **Croatia alcohol age check — implementation deadline 2026-09-15 (11 days).** Penalty detail and the tourist/OIB exclusion still unreported.
- **Australia IDLock — privacy consultation closes 2026-09-18 (14 days).** National rollout 2027.
- **California AB 1856** — passed both chambers unanimously (Senate 39–0 on 2026-08-26; Assembly concurrence 69–0 on 2026-08-27), **still awaiting Governor Newsom's signature, deadline 2026-09-30 (26 days)**. Exempts GPL/MIT/BSD/Apache-licensed operating systems; Windows, macOS, iOS and Android remain in scope. AB 1043 effective 2027-01-01.
- **Brazil ANPD** — TikTok appeal window expires approximately 2026-09-12; 22 platforms under audit; Discord suit running.
- **Identity Week America** — ran 2–3 September, Washington D.C. Keynotes included CBP (Diane Sabatino, "The Unseen Shield"), California DMV (Ajay Gupta) and the US Government Publishing Office (Hugh Halpern). **No substantive published output as of 09-04.** Watch next week for session write-ups.
- **OMB Memo M-26-18** — agency authentication-website inventories due ~2026-11-01. The inventory count is the content trigger.
- **GSA PQC Summit 2026-09-16 (12 days).**
- **Biometric Update × Goode Intelligence age-assurance webinar 2026-09-15 (11 days)** — the 2026 Age Assurance & Digital Age Credentials Market Report is the item to obtain.
- **CAN/DGSI 120:2026** — watch for Canadian regulator adoption by reference.
- **UK DVS register attrition** — SQR's liquidation (2026-07-31) remains the only certified-provider failure. The derived-credentials guidance makes further exits more likely, not less.
- **FIDO wallet certification programme** — no published spec or date.
- **Meta consent judgment publication** — still resolves $17bn vs $18bn. Use the California AG figure ("up to $17 billion over ten years").
- **DNP / Austriacard** — Austrian FDI clearance the last gate; completion targeted for the quarter ending September 2026.
- **Socure / Fravity ($156m raise, $5.2bn valuation, 2026-08-27)** — out of window, but the agentic-AI-into-fraud-decisioning acquisition pattern is worth a follow-up if further detail publishes.
- **ToxicPanda, OverlayPhantom, Manic, WindRelay, Quick Heal 232-app trojan** — all out of window; strong candidates on any follow-up publication.
- **Thailand × Roblox National Digital ID**; **Singapore online safety legislation** (early 2027); **Australia Online Safety Amendment Bill** — all unchanged.
