# Cycle Delta — 2026-11-10

Window: 2026-11-08 → 2026-11-10 (last 48 hours, Tuesday)

## Provenance notes

- Worker (`ditto-slack-bot.dittobot.workers.dev`) blocked by egress proxy policy — consistent with all runs since at least 2026-10-22. Brand brief, pillar guides, and baseline not fetched. Deduplication performed against local GitHub copies of prior deltas (Nov 2–9).
- **Delta written to GitHub** (worker unavailable): `research/2026-11-10-cycle-delta.md`
- 16 web searches executed across all 7 pillars + 7 follow-up fetches.
- **Watch-item follow-ups this run:**
  - KuppingerCole Access Management Leadership Compass (scheduled Nov 2026): Not published as of this run. Watch next cycle.
  - Future Identity Festival (Nov 9–10, London): Event is live. No specific product announcements or keynote text found in this window. Watch next cycle for post-event writeups.
  - 26th NextGen Payments & RegTech Forum, Austin (Nov 10 or Nov 12 — sources conflict): No identity announcements found as of this run.
  - EUDI ARF Iteration 6 (closes Nov 18): Nothing published. Watch next cycle.
- **Checked and rejected (outside window or already covered):**
  - FIDO Alliance 7B passkeys + Passkey Index 2026 (Oct 30): confirmed covered in prior deltas.
  - Vista Equity / HID PKI acquisition (Oct 16–19): 3 weeks outside window; not in prior deltas but date too old to include today.
  - World Bank digital wallet policy notes: July 2026 — outside window.
  - Fideuram / Intesa Sanpaolo EUR 95M deepfake fraud: September 2026, logged in prior cycles.
  - DOJ $129M deepfake CEO fraud indictment (Nov 5–6): covered in Nov 9 delta.
  - Apple Cash iOS mDL verification (Nov 9): covered in Nov 9 delta.
  - Cloudflare / Tools for Humanity TAD framework (Nov 5–8): covered in Nov 9 delta.
  - WE BUILD EUDI testbed (Nov 6): covered in Nov 9 delta.
- **Near-window items included (outside strict 48h window but not covered in any prior delta):**
  - FINMA Circular 2016/7 (effective Nov 1, adopted Oct 8): 9 days outside window; missed by all prior cycles while worker was inaccessible.
  - Veriff Presence Verification (Nov 5): fell within the Nov 6 cycle window (Nov 4–6) but was not found by that run (searched for annual reports, not product launches). Included here as a gap-fill with date clearly marked.
  - hashID wallet (early Nov, ~Nov 5 inferred): date inferred as "7 weeks before Dec 24 deadline"; included with caveat.

---

## Override-worthy this cycle

1. **FINMA's mandatory liveness-detection rule is now live for Swiss online account opening** — Circular 2016/7 (partial revision) took effect November 1; every Swiss bank remote onboarding session must now include a liveness check, and the Swiss e-ID is an accepted credential for the first time. Account: company /. Angle: "Switzerland is the first major financial regulator to mandate liveness detection in its identity code — and the first to put a government e-ID on equal footing with passport MRZ. How many banks haven't patched their stacks?"

---

## New findings

### Pillar 1: Banking & Payments

- **FINMA Circular 2016/7 (partial revision) effective November 1, 2026: liveness detection is now mandatory for Swiss bank online identification** — FINMA adopted the revised circular on October 8, 2026, with effect from November 1. The three operative changes: (1) liveness detection is now a required security step for video and online identification (no longer optional); (2) the Swiss e-ID is accepted for remote account opening for the first time, alongside documents with machine-readable zones; (3) Swiss driving licences with QR codes are put on the same footing as MRZ documents. FINMA tied the liveness requirement explicitly to AI-generated deepfake risks. A one-year transition period applies to some QES-based verification paths. Direct relevance for Ditto: any identity vendor whose Swiss banking clients have not added certified liveness detection to their remote-onboarding pipeline is now non-compliant.
  - Source: https://www.pxl-vision.com/en/blog/finma-circular-2016/7-what-applies-from-november-2026 (secondary blog; check finma.ch Circular 2016/7 for authoritative text)
  - Source: https://idtechwire.com/finma-opens-swiss-remote-account-opening-to-the-e-id-and-adds-liveness-requirement/
  - Date: 2026-11-01 (effective); 2026-10-08 (adopted). Note: 9 days outside strict window; not covered in any prior delta.

### Pillar 2: EUDI / eIDAS2

- **hashID wallet launches with NFC chip reading and yes/no ZKP age checks — no name, date of birth, or photo shared with the verifier** — hashID launched a wallet app (iOS, App Store, free) approximately 7 weeks before the December 24, 2026 EUDI wallet deadline. The app reads the NFC chip in an ID card or passport and answers age verification queries with yes or no only. The relying party receives no name, date of birth, or photo. It supports OpenID4VP, OpenID4VCI, SD-JWT VC, and ISO/IEC 18013-5. No contacts directory; mutual exchange only. The hIDcap verifier is listed on the French EUDI Wallet playground (Phase 1 — protocol flow functional, cryptographic verification in progress). Significance: a production zero-disclosure age-verification wallet built on the EUDI technical stack, arriving ahead of the December deadline; validates the market for ZKP-based selective disclosure in a consumer app.
  - Source: https://idtechwire.com/hashid-launches-app-that-checks-age-from-an-id-chip-and-answers-only-yes-or-no/
  - Source: https://www.biometricupdate.com/202611/hashid-launches-digital-wallet-with-privacy-first-age-checks-and-encrypted-messaging
  - Date: early November 2026 (exact date unconfirmed; inferred from "7 weeks before Dec 24").
  - Drafting caution: exact launch date unconfirmed; hIDcap verifier still in Phase 1 on French playground — do not claim full certification.

### Pillar 3: Fraud / Deepfakes

- **Veriff launches Presence Verification: passive liveness + video analysis + device/network signals, with optional coercion detection** — Announced November 5, 2026 (GlobeNewswire). Veriff's Presence Verification combines passive liveness detection with video analysis and device-and-network signals to flag manipulated media (deepfake video feeds), automated attacks, and coached sessions. Coercion detection is an optional add-on for privacy-sensitive deployments. Available via iOS and Android SDKs and REST API with webhook callbacks. Veriff reports: >98% coercion-detection accuracy; 84% improvement in social engineering fraud detection (vendor figures, methodology not disclosed). Veriff also positions this for agentic commerce — confirming the genuine human behind an AI agent at account setup or high-value transaction moments. Note: fell within the Nov 6 cycle window but was not captured by that run.
  - Source: https://www.globenewswire.com/news-release/2026/11/05/3396390/0/en/veriff-introduces-presence-verification-to-detect-deepfakes-and-coercion.html
  - Source: https://www.biometricupdate.com/202611/veriff-adds-contextual-fraud-detection-to-biometric-verification
  - Date: 2026-11-05. Note: 5 days outside today's strict window; missed by the Nov 6 cycle.

### Pillar 4: ZKPs in practice

- *(See Pillar 2: hashID wallet — directly relevant to ZKP-based selective disclosure in production.)*

(No additional new material in window. EUDI ARF Iteration 6 closes November 18 — watch for updated ZKP/Digital Credentials API specification.)

### Pillar 5: Passwordless / split-key

(no new material in window. KuppingerCole Access Management Leadership Compass still not published as of November 10. Next expected finding: compass publication — check kuppingercole.com/researchplan/leadership-compass-access-management-2026.)

### Pillar 6: LATAM

(no new material in window. BCB VASP ban (Nov 6 effective) remains in force with no enforcement orders found. Drex Phase 2 report still not published.)

### Pillar 7: Identity ecosystem

- **Israel's National Cyber Directorate publishes draft national digital identity strategy for public comment** — Published November 8, 2026 (IN WINDOW). The draft consolidates Israel's identity infrastructure around a national digital identity wallet, based on the national ID card. Banks, insurers, health providers, and telecoms would be able to verify customers against the government system without collecting copies of physical ID documents. The strategy was prepared with the National Digital Agency, Population and Immigration Authority, Finance Ministry, and Bank of Israel. Key limits: (1) the plan does not replace KYC procedures; (2) digital cards gain legal equivalence with physical ones only gradually, requiring legislative amendments; (3) physical ID issuance continues. Public comment period: open until November 30, 2026. Plans for mutual digital ID recognition with other countries are stated in principle. Significance: the "government as identity layer for the private sector" model is now a draft policy in a third country (alongside the EU's EUDI wallet and India's DigiLocker pattern) — useful anchor's identity infrastructure framing.
  - Source: https://www.biometricupdate.com/202611/israel-unveils-plan-to-unite-identity-assets-around-national-digital-id-wallet
  - Source: https://idtechwire.com/israels-draft-digital-id-strategy-would-open-the-government-login-to-banks-and-add-a-national-wallet/
  - Source: https://www.israeldefense.co.il/en/node/72561
  - Date: 2026-11-08 (IN WINDOW)

---

## Upcoming watch items (next 7 days)

- **2026-11-12 (Thu, TBC):** 26th NextGen Payments & RegTech Forum, Austin — authentication / passkeys / tokenised credentials session; Proof/Enigma Business Certificates possibly referenced.
- **2026-11-18 (Wed):** EUDI ARF Iteration 6 closes — expect updated specification covering Digital Credentials API, ZKP age-proof pathway; check eu-digital-identity-wallet/eudi-doc-architecture-and-reference-framework on GitHub.
- **November 2026 (ongoing):** KuppingerCole Access Management Leadership Compass — scheduled but not yet published. Check kuppingercole.com.
- **November 30:** Israel draft national digital ID strategy comment period closes — watch for banking-sector responses.
- **2026-12-24:** EUDI wallet-availability deadline — 44 days. Germany confirmed Jan 2, 2027; multiple states still slipping.
- **~Days ahead:** AMLA central AML/CFT database RTS consultation outcomes — watch amla.europa.eu.
- **Vista Equity / HID PKI deal (Oct 16 announcement):** Expected to close Q4 2026. Watch for closing announcement — first major PKI infrastructure M&A since DigiCert consolidation.
