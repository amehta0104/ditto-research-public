# Cycle Delta — 2026-09-28

Window: 2026-09-25 → 2026-09-28 (last 72 hours; Mon run covers Fri–Mon)

> **Operational note:** Worker API (`ditto-slack-bot.dittobot.workers.dev`) remains blocked by environment egress proxy (403 connect_rejected). Brand brief and pillar guides not fetched from worker. Deduplication performed against GitHub copies of prior deltas and baseline. Delta pushed directly to GitHub via MCP.

---

## Override-worthy this cycle

1. **OpenID Foundation: first 14 organisations certify to OpenID4VP + OpenID4VCI with HAIP — the EUDI protocol stack has its first production certifiers** — Sep 24, 2026; missed by the Sep 25 delta's crawl. This is the first concrete proof that the credential-presentation and issuance protocols underpinning every EUDI wallet are now certifiable in production, covering wallet providers, issuers, verifiers, and government agencies. Angle: "EUDI gets a lot of 'member states will launch in December.' This week the actual protocol stack — OpenID4VP, OID4VCI, HAIP — got its first 14 certified implementations. December just became measurably more real."

---

## New findings

### Pillar 1: Banking & Payments

- **AMLA group-wide requirements RTS due to European Commission Sep 30, 2026 — second major AMLA RTS package completing this year** — The AMLA draft RTS on group-wide minimum requirements and additional measures for subsidiaries and branches in third countries (Articles 16(4) and 17(3) of AMLR 2024/1624) is due for submission to the Commission by 30 September 2026. This is a distinct instrument from the CDD RTS (submitted July 10, 2026); together the two packages mean AMLA will have delivered its two most consequential first-year mandates by end of Q3. The group-wide RTS harmonises how EU banking groups apply AML/CFT controls across international structures and in third-country subsidiaries, replacing fragmented national interpretations. Over 650 stakeholders participated in the May 2026 public hearing. Application date: 10 July 2027.
  - Source: https://www.amla.europa.eu/amla-concludes-public-hearing-draft-rts-group-wide-requirements_en
  - Source: https://simontbraun.eu/amlr-draft-rts-amla-closes-consultations/2026/05/28/
  - Date: 2026-09-30 (submission deadline)
  - **Note:** Prior delta watch item "2026-09-30 — AMLA CDD RTS" was imprecise; the Sep 30 deadline is for group-wide requirements, not CDD (that was July 10). Updating the watch list accordingly.

### Pillar 2: EUDI / eIDAS2

- **EUDI September 2026 status: Croatia, Hungary, Portugal and Liechtenstein reach Category 4 implementation readiness** — eIDasy's monthly member-state tracking (Sep 2026 update) moves Croatia (Certilia Wallet confirmed), Hungary (DÁP / Digitális Adattárca path clear), Portugal (gov.pt EUDI path confirmed), and Liechtenstein (eID.li confirmed) into Category 4 (clear implementation path with confirmed wallet solution). France (France Identité), Austria (eAusweise), and Italy (IT-Wallet) remain leading implementations. The baseline finding that fewer than 1/3 of member states were readiness-benchmark-compliant as of June now requires updating upward; the December 24 deadline is closing fast and the gap is narrowing — though certification under the ENISA scheme remains the harder chokepoint.
  - Source: https://www.eideasy.com/blog/eu-digital-identity-wallets-september-2026
  - Date: 2026-09 (monthly update)

### Pillar 3: Fraud / Deepfakes

- **UK Crime and Policing Act 2026, section 100: Ofcom to mandate NCII removal within 48 hours — consultation before year-end** — The existing Sep 30 compliance deadline (hash-matching to detect NCII/deepfakes, fines up to 10% of global revenue) is the first enforcement stage. Section 100 of the Crime and Policing Act 2026 — new primary legislation — goes further: once Ofcom consults (planned before Dec 31, 2026) and updates the Illegal Harms Codes of Practice, platforms will be legally required to remove any reported non-consensual intimate image, including AI-generated deepfakes, within 48 hours. This is a materially higher bar than hash-matching — it introduces a reactive takedown duty alongside the proactive detection requirement. Identity vendors need to position around the "detection ≠ takedown" gap this creates for biometric identity recovery post-compromise.
  - Source: https://www.grcreport.com/post/ofcom-opens-enforcement-push-on-illegal-intimate-images-ai-deepfakes
  - Source: https://www.thinkbroadband.com/news/tech-firms-face-ofcom-enforcement-over-intimate-image-and-deepfake-protections
  - Date: 2026-09-28 (reported alongside Sep 30 enforcement opening)

### Pillar 4: ZKPs in Practice

- **OpenID Foundation: first 14 organisations self-certify to OpenID4VP + OpenID4VCI with HAIP (Sep 24, 2026)** — The OpenID Foundation announced the first fourteen organisations to complete self-certification for OpenID for Verifiable Presentations (OpenID4VP 1.0) and OpenID for Verifiable Credential Issuance (OpenID4VCI 1.0) under the High Assurance Interoperability Profile (HAIP). The cohort spans wallet providers, credential issuers, verifiers, and government agencies. This closes the loop on the self-certification framework that launched in February 2026 and is the mandatory conformance layer for EUDI Wallet relying parties and issuers under the ARF v2.0. The credential formats covered — SD-JWT VC and ISO mdoc — are the two production formats eIDAS2 mandates. For identity vendors: any issuer or relying party touching EUDI wallets will need to certify against these profiles; fourteen have already done it.
  - Source: https://openid.net/first-implementers-certify-to-openid4vp-and-openid4vci-with-haip/
  - Source: https://openid.net/openid4vp-and-openid4vci-conformance-tests-are-complete-and-open-for-self-certification/
  - Date: 2026-09-24

### Pillar 5: Passwordless / Split-key

(no new material in window — BIO-key FIDO full certification (Sep 23) covered in Sep 25 delta. FIDO passkey adoption now exceeds 5 billion users globally and 90% consumer awareness, but these figures are from the Sep 2026 FIDO industry report rather than a specific Sep 26–28 announcement.)

### Pillar 6: LATAM

- **Brazil Resolution 561 FX/VASP migration cutover: Oct 1, 2026 — 3 days away** — Confirmed from BCB: effective October 1, eFX providers must settle international payments exclusively through traditional FX operations or non-resident BRL accounts; stablecoin settlement in the eFX channel is prohibited. Separately, a 270-day VASP authorisation transition deadline falls October 30, 2026. Neither item is new material — both were in prior delta watch items — but both are now in the 72-hour decision horizon for affected LATAM fintechs. Watch for BCB enforcement bulletin and VASP licence status announcements this week.
  - Source: https://www.ledgerinsights.com/brazil-imposes-partial-ban-on-stablecoins-crypto-for-cross-border-payments-and-fx/
  - Date: 2026-10-01 (cutover date)

### Pillar 7: Identity Ecosystem

- **Ping Identity acquires Keyless — biometric authentication embedded into enterprise IAM (2026)** — Ping Identity completed its acquisition of Keyless, the UK-based privacy-preserving biometric authentication startup known for its zero-knowledge biometric architecture. The deal expands Ping's portfolio with on-device biometric authentication using ZK proofs, addressing the growing requirement from banks and regulated entities for phishing-resistant MFA that satisfies PSD3's SCA bar without centralised biometric storage. Exact date and financial terms not disclosed in search results; confirmed as completed in 2026.
  - Source: https://tech-insider.org/cybersecurity-ma-consolidation-2026/
  - Date: 2026 (Q1–Q2; exact date unconfirmed)
  - **Note:** Include only if date can be confirmed closer to Ditto's pitch cycle; ZK + biometric + enterprise IAM convergence is directly on-pillar.

---

## Corrected watch items (updated from Sep 25 delta)

- **2026-09-30** — AMLA group-wide requirements RTS (third-country branches/subsidiaries) submitted to Commission. (Prior watch item listed this as "CDD RTS" — correction: CDD RTS was July 10. This is the group-wide requirements package.)
- **2026-09-30** — Ofcom NCII/deepfake hash-matching enforcement opens formally. Watch for first enforcement notices.
- **2026-10-01** — Brazil Resolution 561 eFX channel migration cutover (confirmed, 3 days away).
- **2026-10-30** — Brazil VASP authorisation transition deadline (270-day window closes).
- **2026-12-24** — EUDI wallet availability deadline. Progress: Croatia, Hungary, Portugal, Liechtenstein now Category 4; fewer than 1/3 → more than 1/3 of member states benchmark-ready.
- **Before 2026-12-31** — Ofcom consults on Crime and Policing Act 2026 s.100 NCII 48h takedown requirement.
- **Open** — AMLA risk-profiling RTS (non-financial obliged entities) consultation closed Sep 27; final draft expected H1 2027.
- **Open** — PSD3/PSR OJEU publication — anticipated June/July 2026 (slipped); possibly September. Watch for Official Journal notice.
- **Open** — Forrester Wave CIAM evaluation kick-off (Andras Cser); Landscape Q3 2026 published Aug 10. Wave itself expected Q4 2026.
- **Open** — DHS biometric capture GWAC ($440.7M, 5 tracks, ≥15 awards): proposals due Sep 18; awards expected late September/October.

---

## Run summary

- **Findings count by pillar:** P1 Banking: 1 (AMLA group-wide RTS Sep 30). P2 EUDI: 1 (Croatia/Hungary/Portugal/Liechtenstein Category 4). P3 Fraud: 1 (UK Crime and Policing Act 2026 s.100 NCII 48h takedown). P4 ZKPs: 1 (OpenID4VP + OID4VCI first 14 HAIP certifiers, Sep 24). P5 Passwordless: 0. P6 LATAM: 1 (BCB Resolution 561 cutover watch, Oct 1). P7 Ecosystem: 1 (Ping/Keyless, date unconfirmed). Weekend (Sep 26–27) was quiet; no primary regulatory releases found.
- **Override-worthy:** OpenID4VP/OID4VCI first 14 certifiers (Sep 24) — first proof the EUDI protocol stack is production-certifiable; directly strengthens 's December-deadline narrative.
- **Delta path:** `research/2026-09-28-cycle-delta.md` — worker API blocked (egress policy); delta pushed directly to GitHub via MCP.
