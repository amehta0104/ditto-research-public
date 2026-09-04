# Cycle Delta — 2026-09-04

Window: 2026-09-02 → 2026-09-04 (last 48 hours, Thursday cycle)

Worker unreachable this session (egress proxy blocks ditto-slack-bot.dittobot.workers.dev:443 — policy denial). Delta written directly to GitHub.

---

## Provenance and integrity notes

- **Effective window is September 2–4, 2026.** The 09-03 delta covered material through September 3 and logged 9 findings across 5 pillars. This cycle's search found that the 09-03 delta **missed one in-window item from September 2** — World's ProveKit — despite it falling inside that delta's stated window. It is counted as a new finding here since it has not appeared in any logged delta.
- **UK GOV.UK Wallet primary/derived credential split is new material.** The 09-03 delta covered the UK NAO report, the BritCard cancellation, and the DVS Trust Framework v1.0 commencement on September 1. It did NOT cover the OfDIA guidance update that confirms primary digital credentials will be exclusively available in the government-issued GOV.UK Wallet, with certified DVS providers limited to derived credentials at launch. This materially updates the UK narrative and is counted as a new finding.
- **Identity Week America (September 2–3, Washington D.C.) produced the TSA/CBP biometric expansion as the substantive post-event output.** The 09-03 delta flagged this watch item: "Keep the watch item open for 09-04." Biometric Update published the TSA/CBP expansion article in its /202609 edition. The Newark e-gate pilot is the concrete first deployment. Counted as a new finding and the watch item is now partially closed.
- **Not re-reported:** All findings from the 09-03 delta (Handwave × Visa, OMB M-26-18, Ping agentic access, Poland EAA issuer, five-country wallet rollout, Nexus 153m licence dump, UK NAO report, CAN/DGSI 120:2026, ISO/IEC free standards); and all findings from the 09-02 delta (TSA myColorado mDL, ECB SSM-2026-0301 back-fill).
- **Entrust 2026 Identity Fraud Report** surfaced in search (deepfakes in 1 in 5 biometric fraud attempts, injection attacks +40% YoY, deepfake selfies +58% in 2025). **Published November 2025 — outside the window. Do not use as a September finding.** Statistical cluster flagged again in the 09-03 delta ("$3.7bn deepfake losses / 11% of global fraud / document deepfakes +3,900% YoY") — still no primary source, still not usable.
- **Brazil ANPD / TikTok appeal** — no appeal filing or compliance acknowledgment confirmed in window. Appeal window expires approximately September 12. Watch item still open.
- **Croatia m-Gradani alcohol age check** — September 15 deadline unchanged. No new enforcement detail published in window. Watch item open.
- **Australia Digital ID Amendment (Redress Framework) Rules 2026** — consultation concluded March–April 2026; rules take effect September 30, 2026. Not a new in-window finding; background watch item.
- **PSD3/PSR OJEU** — no notice number. Fifteenth consecutive cycle. Secondary commentary places expected publication as "slipping beyond September." Still no scheduled date.

---

## Override-worthy this cycle

1. **The UK government's GOV.UK Wallet guidance has quietly created a two-tier credential market: primary credentials (including the planned digital driving licence) will be held exclusively in the government wallet, and certified private DVS providers get only derived versions — making the private-sector certification regime that "survived" the BritCard cancellation structurally dependent on government-issued primaries from day one.** Account: company /. Angle: This is the sequel to the 09-03 override item 3 ("the state programme died and the market regime lived"). The market regime lived, but it now turns out the government kept the keys. The AVPA is already calling it "a material risk of a two-tier system." The sharpest line: cancelling the mandatory national card didn't create a level playing field — it created a certified private sector whose verifiable documents depend entirely on a government source that has no obligation to share it.

2. **World open-sourced ProveKit on September 2 — the zero-knowledge proving engine already running inside World ID is now available to any developer under an MIT licence, with 128-bit post-quantum security and local proof generation that never sends personal data to a server.** Account: / company. Angle: ZKP has been the identity industry's "coming soon" for a decade. ProveKit is a production-tested ZK implementation leaving one application and becoming general-purpose infrastructure. The architecture is precisely what "prove the attribute, retain nothing" demands at the implementation layer. The post-quantum inclusion means it also closes the forward-looking cryptographic window simultaneously.

---

## New findings

### Pillar 1: Banking & Payments

(no new material)

No in-window EBA, ECB, AMLA, FCA or PSR publication. **PSD3/PSR OJEU**: still no notice number — fifteenth consecutive cycle. **ECB SSM-2026-0301 action plan deadline 2026-10-31 (57 days)** — the strongest un-used banking hook in the corpus; drafting window is closing. Standing joint EBA-ECB reference unchanged: EU fraud losses €4.2bn in 2024.

### Pillar 2: EUDI / eIDAS2

(no new material this cycle — see Pillar 6 for the UK GOV.UK Wallet finding, which has direct EUDI structural parallels)

No new ARF version, implementing act, ENISA certification action, or member-state wallet launch confirmed in window beyond the five-country rollout wave (09-03 delta). **EUDI Relying Party Engagement Programme first webinar "Travel Across Europe", 2026-09-18, 14:00–15:30 CET — 14 days out.** Wallet-availability deadline: **2026-12-24 (111 days).**

### Pillar 3: Fraud / Deepfakes

(no new material)

No in-window primary fraud or deepfake report. Entrust 2026 Identity Fraud Report surfaced in search but was published November 2025 — out of window. The Nexus 153m licence-scan dump (09-03 delta) remains the dominant fraud story in the corpus.

### Pillar 4: ZKPs in practice

- **World open-sourced ProveKit, the zero-knowledge proving toolkit behind World ID, under an MIT licence — giving any developer access to a production-tested, offline-capable ZK engine with 128-bit post-quantum security that runs locally on a phone or browser (2026-09-02).** World released ProveKit as open-source code on September 2, 2026. The toolkit is already used in production in World ID and lets users generate cryptographic proofs on their own devices — proving claims such as age, nationality, or valid identity document ownership — without the underlying personal data ever leaving the device or reaching an external server. The implementation supports Noir, the Rust-inspired ZK language developed by Aztec, and allows developers to build new provable claims without bundling them into an application binary. Key properties: runs offline, small download size, low memory footprint, seconds-range proof generation, 128-bit post-quantum security, no trusted setup. Available on GitHub (`worldfnd/provekit`) under an MIT licence. Why it matters for Ditto: this is the cleanest in-corpus instance of ZKP moving from "embedded in one application" to "general-purpose infrastructure." The architectural argument Ditto makes — prove the attribute, not the document, retain nothing — has been theoretical at the implementation layer. **ProveKit is the production-tested version of that argument available to any relying party who wants to deploy it without building the cryptographic substrate themselves.** The post-quantum inclusion is a secondary signal worth noting: the toolkit simultaneously closes the forward-looking quantum attack window. **⚠️ Context note: World/Worldcoin conducts iris biometric collection as part of its own identity system, which has attracted regulatory attention in several jurisdictions. ProveKit is technically separable from the iris collection — it is a proving toolkit, not a biometric system — but do not present World or Worldcoin as a peer identity vendor or regulatory exemplar. The tool is the story; the provenance is background.**
  - Source: https://www.biometricupdate.com/202609/world-releases-open-source-toolkit-for-privacy-preserving-identity-proofs
  - Primary (GitHub): https://github.com/worldfnd/ProveKit
  - Corroborating: https://idtechwire.com/world-releases-mobile-first-zero-knowledge-toolkit-behind-world-id/
  - Corroborating: https://www.theblock.co/news/ecosystems/2026-09-02-world-provekit-zero-knowledge-identity-proving-toolkit-413364
  - Date: 2026-09-02

### Pillar 5: Passwordless / split-key

- **TSA activated the first touchless biometric e-gates in the United States at Newark Liberty Terminal C — and CBP simultaneously expanded its own biometric exit programmes — in an early-September deployment that marks the first operational, fully touchless facial verification lane at a US airport (2026-09-03).** The Transportation Security Administration brought three biometric e-gates live at Newark Terminal C in a pilot with United Airlines, timed to the Labor Day travel surge. Unlike earlier CAT-2 biometric readers (which compare a presented document or mDL), the e-gates are **fully touchless**: eligible passengers pass through without any tap, scan or document presentation — the system compares a live facial image against enrollment and travel records already on file. Eligible passengers are TSA PreCheck holders who have opted into the **TSA PreCheck Touchless ID program** through the United Airlines app. At the same time, CBP announced expansions to its own biometric exit programmes. The Newark pilot's stated purpose is to test readiness for broader airport deployment; TSA has not committed to rollout beyond Terminal C. Why it matters for Ditto: the e-gate architecture is the same logical endpoint the passwordless pillar argues toward — **authentication against a stored assertion, without a shared secret, without a document presented.** The biometric is the authorisation event; the credential evidence stays on file. The important constraint: this is a consumer travel use case (not a named Ditto ICP), the pilot is small and United-only, and facial data is enrolled and matched against a federal travel record, not an on-device assertion. **Do not present this as equivalent to a FIDO or split-key architecture.** The structural point worth making is directional: the US federal government is operationally deploying touchless biometric lanes at its highest-security-priority checkpoint in the same week it mandated agency-wide Login.gov adoption (OMB M-26-18, 09-03 delta). The policy and the technology are moving together.
  - Source: https://www.biometricupdate.com/202609/tsa-cbp-expand-biometric-and-digital-id-programs-for-air-travel
  - Corroborating: https://hoodline.com/2026/09/newark-airport-rolls-out-nation-s-first-touchless-biometric-e-gates-in-terminal-c/
  - Date: 2026-09-03 (activation date approximate; article dated September 2026)

### Pillar 6: Identity verification (IDV)

- **OfDIA guidance updated in September 2026 confirms that primary digital credentials — including the planned digital driving licence — will be held exclusively in the government-issued GOV.UK Wallet; certified private DVS providers will have access only to derived credentials at launch, and the AVPA has publicly warned this creates a material risk of a two-tier market (2026-09 [September]).** The Office for Digital Identities and Attributes published updated guidance on using the GOV.UK Wallet that, in combination with the technical documentation, confirms the credential hierarchy: **primary credentials** (government-issued documents, beginning with the digital Veteran Card and the planned digital driving licence) live in the GOV.UK Wallet and are only accessible there. A certified **Identity Service Provider or Attribute Service Provider** can use data from the GOV.UK Wallet in a verification, but only to create a **derived credential** — a new reusable digital identity document downstream of the primary, not a direct copy of it. **Unless derived credentials are recognized in law and regulation as equivalent to primary credentials, their commercial utility is limited.** The Age Verification Providers Association has already made this argument publicly, calling the arrangement a risk of "a material risk of a two-tier system." Why this matters for Ditto: read this alongside the 09-03 override item 3 (the UK state programme was cancelled; the certified private-provider regime came into force anyway). **The sequel is now available: the certified private-provider regime came into force, but primary credential access did not come with it.** The regulatory apparatus that governs private identity providers in the UK is built on a source it does not control. Two parallel UK ecosystem signals this cycle: the NAO's diagnosis (the obstacle is never the technology — it's reconciling legacy identifiers) and now the GOV.UK Wallet architecture (the government is keeping primary credentials centrally while certifying a private verification layer). **The post the 09-03 override invites writes itself: state programme cancelled, certified market "survived" — and then you read the credential access rules and the market is downstream of the government source from day one.** ⚠️ **Do not write that DVS providers are "excluded" — the guidance says "at least at first." The constraint is structural but may evolve. Write what the current guidance says, not a permanent verdict.** ⚠️ **Note: there is a related February 2026 item (UK digital ID sector warned of legal action if mDL is limited to GOV.UK Wallet) — the September guidance update appears to have confirmed the arrangement the sector was warning against. Obtain the primary OfDIA guidance page before drafting to verify the current state.**
  - Source: https://www.biometricupdate.com/202609/uk-guidance-indicates-only-govt-digital-id-wallet-will-get-primary-credentials
  - Corroborating: https://www.ukauthority.com/articles/government-publishes-guide-for-digital-identity-providers-to-use-govuk-wallet
  - Context (February warning): https://www.biometricupdate.com/202602/uk-digital-id-sector-warns-of-legal-action-if-mdl-limited-to-gov-uk-wallet
  - Date: 2026-09 (September 2026; exact day unconfirmed — obtain primary before drafting)

### Pillar 7: LATAM

(no new material)

No -relevant regulatory instrument dated in window. Searched CNBV, Superfinanciera, CMF, SBS, BCB, Pix and Drex. **Brazil ANPD / TikTok appeal window expires approximately 2026-09-12 (8 days)** — still running, no new action confirmed. CNBV mandatory biometric banking compliance wall: November 2026.

### Pillar 8: Identity ecosystem

(no new material)

No in-window analyst report (Forrester, KuppingerCole, Liminal, Gartner) or significant M&A / funding announcement confirmed dated September 3–4. **Identity Week America (September 2–3) produced the TSA/CBP biometric expansion (Pillar 5 above) as its most substantive on-pillar output.** Government keynote speakers included Diane Sabatino (CBP) and Ha Nguyen McNeill (TSA).

---

## Watch items carried forward

- **Krebs on Security primary on the Nexus dump** — obtain before drafting; FBI New Orleans investigation ongoing. Highest-value drafting item in corpus.
- **NAO digital identity report** — obtain primary from nao.org.uk (title discrepancy unresolved). Watch for Public Accounts Committee session.
- **UK GOV.UK Wallet credential architecture** — obtain OfDIA primary guidance page to confirm primary/derived split. Watch for legal challenge (the sector warned of this in February 2026). Watch for first DVS-issued derived credential.
- **UK DVS register** — SQR liquidation (2026-07-31) still the only certified-provider failure on record. Watch for further exits and first 1.0 register entries.
- **ECB SSM-2026-0301 action plan deadline — 2026-10-31 (57 days).** Obtain ECB primary. Drafting window is closing.
- **PSD3/PSR OJEU publication** — no notice number, fifteenth consecutive cycle.
- **AMLA Level 2 package** — Commission endorsement expected Q4 2026; Article 28(1) CDD RTS is the item that matters. AMLR applies 2027-07-10.
- **EUDI wallet-availability deadline 2026-12-24 (111 days)** — Germany 2027-01-02; relying-party acceptance December 2027.
- **EUDI Relying Party Engagement Programme** — first webinar "Travel Across Europe", 2026-09-18, 14:00–15:30 CET (14 days).
- **EUDI attestation-issuer registrations** — Poland registered (09-03 delta). Count of registered EAA issuers per member state is now a trackable metric.
- **Romania ROWallet** — phased rollout October 2026, full launch January 2027.
- **Croatia m-Gradani alcohol age check — implementation deadline 2026-09-15 (11 days).** Watch for penalty detail and tourist/OIB exclusion coverage.
- **Australia IDLock — privacy consultation closes 2026-09-18 (14 days).**
- **Brazil ANPD / TikTok appeal** — expires approximately 2026-09-12 (8 days).
- **California AB 1856** — awaiting Governor Newsom's signature.
- **GSA PQC Summit 2026-09-16 (12 days).**
- **Biometric Update × Goode Intelligence age-assurance webinar 2026-09-15 (11 days)** — 2026 Age Assurance & Digital Age Credentials Market Report is the item to obtain.
- **OMB Memo M-26-18 agency inventory deadline** — approximately 2026-11-01. Watch for inventory count.
- **TSA PreCheck Touchless ID Newark pilot** — watch for expansion decision and any CBP biometric exit announcement at other airports.
- **ISO/IEC free standards portal** — watch for download volumes and additional standards added.
- **FIDO wallet certification programme** — no published spec or date.
- **Meta consent judgment** — $17bn vs $18bn resolution pending.
- **DNP / Austriacard** — Austrian FDI clearance last gate; completion targeted September 2026 quarter-end.
- **ToxicPanda, OverlayPhantom, Manic, WindRelay, Quick Heal 232-app trojan** — all out of window; strong candidates on any follow-up publication.

---

## Run summary

- **Findings count by pillar:** 3 findings across 3 pillars — P4 ZKPs/mDL (1: World ProveKit open-source ZK toolkit, MIT licence, post-quantum, production-grade); P5 Passwordless (1: TSA/CBP Newark biometric e-gates, first touchless facial lane in US); P6 IDV (1: UK GOV.UK Wallet primary/derived credential split confirmed by OfDIA guidance, AVPA warning). P1, P2, P3, P7, P8, LATAM: no new material.
- **Override-worthy:** (1) UK GOV.UK Wallet primary/derived credential split — the sequel to the BritCard cancellation story: the certified private-sector regime "survived" but is structurally downstream of government primary credentials from day one; (2) World ProveKit — ZKP moving from "inside World ID" to MIT-licensed general-purpose infrastructure, post-quantum-secure.
- **Delta path:** research/2026-09-04-cycle-delta.md (written to GitHub — worker egress blocked).
