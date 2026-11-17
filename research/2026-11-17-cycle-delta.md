# Cycle Delta — 2026-11-17

Window: 2026-11-14 → 2026-11-17 (last 72 hours — Monday, covering weekend)

## Provenance notes

- Worker (`ditto-slack-bot.dittobot.workers.dev`) blocked by egress proxy policy — consistent with all runs since 2026-10-22. Brand brief, pillar guides, and baseline not fetched. Deduplication performed against local GitHub copies of prior deltas (Nov 2–16).
- **Delta written to GitHub** (worker unavailable): `research/2026-11-17-cycle-delta.md`
- 13 web searches + 3 follow-up searches executed across all 7 pillars.
- **Watch-item follow-ups this run:**
  - Future Identity Festival London (Nov 9–10): Post-event recaps **still not indexed** as of this run. Promotional/event pages only. Watch next cycle.
  - 26th NextGen Payments & RegTech Forum, Austin (Nov 10): No post-event announcements found. Watch next cycle.
  - KuppingerCole Access Management Leadership Compass (November 2026): Research plan still shows November 2026 target / "closed" status but no vendor press releases or KC library listing confirmed the report. Thales confirmed Leadership positions in separate **Passwordless Authentication for Enterprises** and **B2C** compasses (2026 editions, available on Thales site) — these are distinct from the AM compass. Watch for AM compass vendor announcements.
  - EUDI ARF Iteration 6 (closes **tomorrow, 2026-11-18**): Nothing published yet. Topics confirmed: Digital Credentials API (Topic F) and cryptographic binding of attestations (new Topic AC). Check GitHub changelog at eu-digital-identity-wallet/eudi-doc-architecture-and-reference-framework on 2026-11-18.
  - AMLA central AML/CFT database RTS post-hearing summary: Still not published on amla.europa.eu.
  - PSD3/PSR Official Journal publication: Still pending — sources now give Q4 2026 / December 2026; not confirmed.

- **⚠️ Missed-in-prior-cycles alert (outside current window, requires drafter action):**
  FBI/DOJ disrupted the North Korean "FaceStealer" cryptocurrency theft scheme on **2026-11-12** (FBI.gov + DOJ press releases). The operation drained **$400 million in cryptocurrency** over 18 months via deepfake video calls and recorded webcam impersonation. DOJ simultaneously seized $1.2 billion tied to the separate TraderTraitor/Binance hack. This was not covered in the Nov 13 delta (window Nov 10–13) and correctly excluded from the Nov 16 delta (window Nov 13–16) as outside that window, but it is now also outside the current window (Nov 14–17). **Recommend drafter add this as a catch-up finding or use it as background for a Pillar 3 (Fraud/Deepfake) post.** Sources: https://www.fbi.gov/investigate/cyber/facestealer-cryptocurrency-theft-scheme · https://therecord.media/stolen-binance-crypto-recovered-doj-facestealer-disrupted · https://thehackernews.com/2026/11/fbi-says-north-korean-hackers-stole.html

- **Checked and rejected (outside window or already covered):**
  - Sumsub + Constructor University adversarial face-swap (Nov 13): Covered in Nov 16 delta.
  - UK address verification service, Cifas 59% fraud stat (Nov 16): Covered in Nov 16 delta.
  - Singapore AI agent domain registry (Nov 13): Covered in Nov 16 delta.
  - Facephi + Egypt Trust integration (Nov 13–16): Covered in Nov 16 delta.
  - WE BUILD consortium EUDI pilot update (Nov 13–16): Covered in Nov 16 delta.
  - FIDO 7B passkeys milestone (Oct 30): Outside window; noted in prior cycles.
  - Shufti on-device age verification: Borderline (Nov 13 coverage). Excluded — Nov 13 is at the edge of the previous delta's window and falls outside the current Nov 14–17 window.

---

## Override-worthy this cycle

(none)

---

## New findings

### Pillar 1: Banking & Payments

(no new material in window. PSD3/PSR OJ publication still pending — law-firm notes and trade press give December 2026; no confirmed OJEU notice found. AMLA central database RTS post-hearing summary not published. No new EBA/FCA/PSR/ECB releases found Nov 14–17.)

### Pillar 2: EUDI / eIDAS2

- **European Commission and French authorities authorize Getlink (Eurotunnel) to trial drive-in biometric kiosks for EU Entry/Exit System checks at Folkestone and Calais** — The EC granted Getlink permission to run a two-year trial of camera-supervised biometric kiosks at the Eurotunnel terminals in Folkestone and Calais. Kiosks capture face and fingerprint biometrics without drivers leaving their vehicles; border police supervise remotely via "eagle eye" cameras. The system is not yet operational — integration with French border authority systems is still pending. This is the first authorized use of EES-compliant in-vehicle biometric processing at a major cross-border land terminal. Significance for identity vendors: EES rollout has slipped since 2021; this authorization signals that the EU/UK entry/exit biometric infrastructure is moving toward operational phase, expanding the addressable market for biometric capture and liveness products beyond airports.
  - Source: https://www.biometricupdate.com/202611/eurotunnel-to-trial-camera-supervised-biometrics-for-in-car-ees-checks
  - Source: https://idtechwire.com/eu-clears-eurotunnel-to-trial-drive-in-biometric-kiosks-for-entry-exit-system-checks/
  - Date: 2026-11-14 (confirmed from multiple outlets in window)
  - Drafting caution: System not yet operational (French integration pending); avoid framing as a live deployment. This is a tier-2 ecosystem signal, not a Ditto-specific angle, unless linked to the broader EES/biometric infrastructure narrative.

### Pillar 3: Fraud / Deepfakes

(no new primary material in window Nov 14–17. See ⚠️ Missed-in-prior-cycles alert above for the FBI FaceStealer $400M disruption (Nov 12) — high-quality Pillar 3 finding available for drafter use despite being outside the formal window.)

### Pillar 4: ZKPs in practice

- **Toppan and BitGo complete proof-of-concept combining vLEI corporate identity checks with 3-party distributed key management for digital asset transfers** — Toppan (via its TOPPAN Edge subsidiary, Japan's first GLEIF-qualified vLEI issuer) and BitGo completed a trial that splits signing authority across three HSM-based keys and runs automated vLEI identity checks at each transaction and counterparty registration. The system executes "automated digital verification of corporate identities and representative authority" during transfers and when adding to approved counterparty whitelists. Tests confirmed secure asset transfers when one of three keys was unavailable. TOPPAN Edge is simultaneously launching vLEI-Gateway™ in November 2026 to commercialise the identity check layer. Commercial-platform launch targeting banks, municipalities and corporations is planned for 2028.
  - Source: https://www.biometricupdate.com/202611/toppan-bitgo-test-vlei-identity-checks-for-secure-digital-asset-transfers
  - Source: https://thepaypers.com/crypto-web3-and-cbdc/news/toppan-and-bitgo-complete-poc-for-decentralised-key-management
  - Date: ~2026-11-12 to 2026-11-14 (Biometric Update "202611"; exact date not confirmed from search result — in or near window boundary)
  - Drafting caution: vLEI is a verifiable credential standard for legal entities (not a ZKP scheme), but it uses cryptographic attestations and selective disclosure in a ZKP-adjacent way. Confirm exact article date before citing. PoC, not a commercial product — 2028 target. Niche audience (crypto/digital assets, not retail banking); secondary to Pillar 7 if the verifiable credentials angle is preferred.

### Pillar 5: Passwordless / split-key

(no new confirmed material in window. KuppingerCole Access Management Leadership Compass still not confirmed published as of this run. Thales confirmed as Leader in KuppingerCole's separately published Passwordless Authentication for Enterprises 2026 and Passwordless Authentication for B2C 2026 compasses — these are relevant background for a passwordless post but are not the AM compass and were not published this week.)

### Pillar 6: LATAM

(no new primary-source material in window. No Drex Phase 2 report, no new CNBV/Superfinanciera/CMF/SBS/BCB identity announcements found. Sumsub/Jelou WhatsApp integration (Nov 11 delta) remains most recent LATAM-relevant finding. ASEAN DEFA signed this week (see Pillar 7) includes payments and digital identity — not LATAM but a comparable regional DPI signal for context.)

### Pillar 7: Identity ecosystem

- **ASEAN DEFA signed: 11-country binding digital economy pact names cross-border digital identity as a priority** — All 11 ASEAN member states signed the Digital Economy Framework Agreement (DEFA) in Manila on 2026-11-14. DEFA is ASEAN's first standalone, legally binding digital economy agreement, covering digital trade, e-commerce, electronic payments, and digital identity. Singapore's Deputy PM Gan Kim Yong specifically cited digital identities as helping businesses verify whom they are trading with. Early priority projects will include payments, digital identities and electronic trade documents; first rollouts targeted for early 2027. Vietnam is already piloting cross-border identity linkage between VNeID, Singapore's Singpass and Laos' LAeID — DEFA gives that initiative a formal interoperability mandate. Significance for identity vendors: ASEAN's $3.6 trillion combined GDP and 680 million population with highly mobile workforces make this the second-largest regional digital identity binding framework signed in 2026, after the EU eIDAS2 implementing acts.
  - Source: https://www.biometricupdate.com/202611/asean-digital-economy-pact-puts-cross-border-identity-on-the-agenda
  - Source: https://www.manilatimes.net/2026/11/16/business/top-business/asean-ministers-sign-landmark-digital-economy-pact/2470381
  - Source: https://www.thestar.com.my/aseanplus/aseanplus-news/2026/11/14/asean-states-sign-digital-economy-framework-agreement-which-kicks-in-from-early-2027
  - Date: 2026-11-14 (IN WINDOW — confirmed by multiple primary and secondary sources)
  - Drafting caution: DEFA covers a wide remit; digital identity is one of several named areas, not the centrepiece. Singapore-led; implementation varies widely by member state. /LATAM angle: ASEAN DEFA and Vietnam's VNeID pilot are good counterparts to Drex/Pix momentum for a "regional DPI acceleration" narrative.

---

## Upcoming watch items (next 7 days)

- **2026-11-18 (Wed) ← HIGHEST PRIORITY:** EUDI ARF Iteration 6 closes — expect updated specification covering Digital Credentials API (Topic F) and cryptographic binding of attestations (Topic AC). Check: https://github.com/eu-digital-identity-wallet/eudi-doc-architecture-and-reference-framework/blob/main/CHANGELOG.md
- **2026-11-18 (Wed):** KuppingerCole Customer Identity & Access Management Impact Day, Hilton Frankfurt Airport — analyst commentary on passwordless and EUDI wallet may surface.
- **This week:** KuppingerCole Access Management Leadership Compass — confirm publication via vendor press releases (Ping Identity, Thales, CyberArk, Okta) or KC library at kuppingercole.com/research.
- **This week:** Future Identity Festival London (Nov 9–10) post-event recaps — still not indexed; watch thefutureidentity.com and biometricupdate.com.
- **2026-11-30:** Israel draft national digital ID strategy comment period closes.
- **2026-12-01:** Australia myID opens to private-sector providers — first approved provider list expected.
- **2026-12-02:** AMLA SDD roundtables conclude — formal public consultation on simplified CDD guidelines expected to follow.
- **2026-12-24:** EUDI wallet-availability deadline — 37 days. Germany confirmed Jan 2, 2027; multiple states still slipping.
- **~Days ahead:** AMLA central AML/CFT database RTS post-hearing summary — watch amla.europa.eu.
- **Q4 2026:** PSD3/PSR Official Journal publication — December 2026 expected per law-firm briefings.
- **Q4 2026:** Vista Equity / HID PKI deal expected to close.
- **Drafter action:** FBI FaceStealer $400M deepfake crypto-theft disruption (Nov 12) — missed in prior cycles. Recommend catch-up post or fold into next Pillar 3 draft. Sources in provenance notes above.
