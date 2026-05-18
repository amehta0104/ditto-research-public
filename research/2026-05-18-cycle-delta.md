# Cycle Delta — 2026-05-18

Window: 2026-05-15 → 2026-05-18 (last 72 hours — Monday weekend window)

## Override-worthy this cycle

1. **FCA chief executive Nikhil Rathi: "financial crime is now a national security issue" — speech at the FCA financial crime conference, 14 May 2026 (reporting carried into 15–18 May; not captured in the 05-14 or 05-15 deltas)** — Rathi told the FCA's financial crime conference that "separating financial services from national security is outdated and dangerous," that organised crime is exploiting the gaps *between* firms, regulators and institutions, and that the response must be system-wide. The FCA confirmed it will begin sharing more intelligence with law enforcement from June 2026, including 5,000+ records via the Police National Database. Angle: pairs directly with the 05-14 ECB / Elderson AI-cyber override into a cross-Channel running theme — *both the euro-area and UK regulators have, within eight days of each other, reframed financial-crime and cyber defence as national-security infrastructure, not a compliance line item. The identity layer (verification, mobile threat defence, authentication) is exactly the "gap between firms" Rathi says criminals now exploit — and "system-wide" is the regulator's word for orchestration.*

---

## New findings

### Pillar 1: Banking & Payments

- **FCA CEO Nikhil Rathi reframes financial crime as a national-security and economic-stability threat — FCA financial crime conference, 14 May 2026** — Rathi's "Working together against financial crime" speech argues financial crime is more organised, technologically advanced and interconnected than ever; that the response must be system-wide (better information sharing, smarter technology, deeper firm/regulator/government/law-enforcement collaboration); and that criminals increasingly exploit the seams between institutions to scale fraud, money laundering and cyber-enabled crime. Concrete commitment: the FCA will expand intelligence-sharing with law enforcement from June 2026, including 5,000+ records through the Police National Database. Significance for an identity vendor: this is the UK-side bookend to the ECB Elderson AI-cyber warning (05-14 override) — the supervisory framing across both jurisdictions has moved from "compliance" to "operational resilience / national security," which is the narrative environment in which orchestration + threat-defence + verification get bought as one system rather than three procurement lanes. Dated 2026-05-14 — one day before the strict window; included as a catch-up because neither the 05-14 nor 05-15 delta captured it and the reporting/amplification ran into the window.
  - Source: https://www.fca.org.uk/news/speeches/working-together-against-financial-crime
  - Source: https://theintermediary.co.uk/2026/05/financial-crime-is-now-a-national-security-issue-says-fca-chief-executive/
  - Source: https://kyc360.com/knowledge-hub/resources/aml-roundup-15th-may-2026-fca-chief-executive-warns-that-financial-crime-is-now-a-national-security-issue
  - Date: 2026-05-14 (speech); reporting 2026-05-14 → 2026-05-15

(PSD3/PSR remains awaiting the European Parliament plenary vote following the 5 May ECON adoption — confirmed roll-call figures: PSD3 ~50–55 in favour, PSR 50 in favour; plenary still "expected later in May 2026" with no Strasbourg date confirmed and no plenary held in window. OJEU publication still anticipated June/July 2026. No new DORA enforcement actions, CTPP designations or penalty announcements in window. Next AMLA milestones fall outside this window: group-wide minimum requirements RTS hearing 20 May, business-wide risk assessment Guidelines hearing 28 May, Home-Host Supervisory Cooperation RTS hearing 28 May; next substantive output is the 10 July submission of the final CDD draft to the Commission.)

### Pillar 2: EUDI / eIDAS2

(no new material in window — no new member-state launch announcements; Romania-Mastercard MoU and France Identité ZKP age verification covered in the 05-13 delta; ENISA EUDIW certification scheme remains in post-consultation review (public review closed 30 April), Implementing Act expected end-2026. KuppingerCole EIC 2026 opens tomorrow (19 May) in Berlin — "Digital Trust Through Intelligent Identity"; EUDI Wallets and verifiable credentials are agenda centrepieces, but no pre-event announcements or vendor M&A in window. Next-cycle drafter note: EIC keynotes and any wallet-related announcements should be captured in the 19–20 May deltas.)

### Pillar 3: Fraud / Deepfakes

- **OCR Studio ships anti-fraud detection for AI-generated and morphed identity documents — 17 May 2026** — OCR Studio updated its document-scanning tool with a system that detects identity documents generated or edited by generative-AI tools including ChatGPT, NanoBanana, Grok and Midjourney. The approach examines low-level image structure — generation and editing artefacts invisible to the human eye — rather than checking for logical inconsistencies (dates, fonts, number formats). CTO Konstantin Bulatov: "The only traces left by deepfake images are invisible to the human eye and undetectable by traditional anti-fraud systems." No named customers disclosed. Significance for Ditto: this is squarely Ditto Verify territory (document authenticity across 16,000+ ID types) and a category-level validation that document-only / logical-check KYC is structurally broken against generative-AI forgeries — the same gap the CBA $1bn underwriting-fraud case (baseline) and FATF Horizon Scan (baseline) describe. Use as category-pattern evidence, not vendor sniping (per the hard rule — do not name OCR Studio in a post).
  - Source: https://www.biometricupdate.com/202605/ocr-studio-expands-kyc-fraud-detection-for-ai-generated-identity-documents
  - Date: 2026-05-17

(no named-bank deepfake or synthetic-ID incident disclosures in the 72h window. Surfshark deepfake-loss analysis — $2.19bn cumulative global losses, $1.65bn in 2025, US most-targeted at $712m — was released 4 May 2026, outside the window; cited here for accurate dating so the drafter can use it without re-running search. Sumsub 2025-26, Veriff 2026 and iProov 2026 reports remain the strongest aggregate anchors from the baseline.)

### Pillar 4: ZKPs in Practice

(carry-forward, not a new finding — OpenID Connect Advanced Syntax for Claims (ASC) 1.0: the member vote to advance to Implementer's Draft ran 1–15 May and concluded on 15 May; the OpenID Foundation has **not yet published an official "approved" result page** as of this scan (2026-05-18). The "Notice of Vote" and the eKYC&IDA recommendation remain the latest primary artifacts. Drafter note: treat ASC 1.0 as "vote concluded, recommended for approval, formal Implementer's Draft confirmation pending" — do not state it has been formally approved until the OpenID Foundation result page is live. The substantive content — "Transformed Claims" deriving an over-18 boolean from a birthdate without exposing the DOB — is unchanged and remains the production-grade protocol-level expression of the privacy-preserving disclosure pattern. No new ZKP bank pilots or OpenID4VP/VCI events in window.)
  - Source: https://openid.net/notice-of-vote-to-approve-the-proposed-implementers-draft-of-openid-connect-advanced-syntax-for-claims-asc-1-0/
  - Date: vote concluded 2026-05-15; formal result not yet posted as of 2026-05-18

### Pillar 5: Passwordless / Split-key

(no new material in window — Microsoft Entra passkeys on Windows (device-bound, Windows Hello) and Entra External ID passkeys (consumer-facing) both flagged as "late May 2026" GA windows; no specific dated announcement landed in this 72h window. Confirmation expected in the 05-19–05-22 cycle alongside EIC output. World Passkey Day 2026 data (5bn passkeys, 75% enabled, 68% enterprise), the FIDO Agentic Authentication TWG, OpenAI joining the FIDO board, and Google AP2 / Mastercard Verifiable Intent contributions were all announced late April / early May — captured in earlier deltas and outside this window. FIDO Authenticate APAC 2026 is 2–3 June Singapore.)

### Pillar 6: LATAM

(no new material in window — Unico Brazil digital age verification launch (05-14) and Trinsic Digital ID Opportunity Zones Brazil green-zone status (05-14) covered in the 05-15 delta. No fresh CNBV, Superfinanciera, CMF, SBS or BCB regulatory announcements in the 72h window. No new Nubank, Mercado Pago or Ualá news in window.)

### Pillar 7: Identity Ecosystem

- **IATA and Trip.com announce digital ID wallet pilot for airline booking flows — 12–13 May 2026 (catch-up; not captured in any prior delta; Biometric Update coverage 2026-05-15, in window)** — At the IATA Airline Global Conference (AGC) in Amsterdam, Trip.com Group announced a pilot with IATA to test wallet-based digital credentials in airline booking flows. Architecture: travellers store secure identity credentials in Apple Wallet or Google Wallet and use them to autofill booking information with selective disclosure — travellers control what data is shared. Participating airlines: Air Canada, Turkish Airlines, Qatar Airways; technology partner: Hopae (which has prior EUDI Wallet integration experience). Roll-out scope: optional Customer ID functionality tested with a subset of users in the UK and US in the first phase. IATA is separately discussing a new multi-airline, multi-border-authority digital ID PoC in China. Significance for an identity-orchestration vendor: this is the first major IATA-endorsed consumer-facing pilot of wallet credentials as airline booking infrastructure — extending the "wallet as credential layer" story from banking KYC into travel, and validating that selective disclosure (give only what the relying party needs) is the architecture the market is converging on across sectors.
  - Source: https://www.biometricupdate.com/202605/iata-trip-com-to-pilot-digital-id-wallets-for-airline-booking-flows
  - Source: https://www.phocuswire.com/news/technology/trip-com-digital-id-google-apple-wallets
  - Source: https://www.prnewswire.com/news-releases/ai-and-digital-identity-drive-aviations-next-chapter-trip-com-group-at-airline-global-conference-302770340.html
  - Date: 2026-05-12 (press release); 2026-05-13–05-15 (reporting)

- **World Bank and African DPAs outline trust governance formula for DPI at ID4Africa 2026 closing — 15–16 May 2026** — On the Friday–Saturday closing segment, a World Bank-led presentation put trust governance at the centre of the DPI/identity conversation, and data-protection-authority leaders from multiple African countries discussed regional collaboration on DPI oversight, cross-border data sharing, incident response and systemic accountability. The World Bank also released a DPI procurement guide. Useful as evidence that "trust and governance, not deployment" is now the global identity consensus — reinforcing the EUDI "certification is the real deadline" standing theme. Outside Ditto's ICP geography; soft signal / analogy material only.
  - Source: https://www.biometricupdate.com/202605/world-bank-african-dpas-outline-formula-for-trusted-digital-identity-dpi
  - Source: https://www.biometricupdate.com/202605/world-bank-unveils-dpi-procurement-guide-for-more-integrated-digital-services
  - Date: 2026-05-15 / 2026-05-16

(KuppingerCole EIC 2026 opens 19 May Berlin — no pre-event vendor announcements or category M&A landed in window. Next-cycle drafter note: EIC opens tomorrow; the 19–20 May deltas should capture keynote/vendor output.)

---

## Run summary

- Findings count by pillar: P1 (Banking): 1 (FCA Rathi catch-up) | P2 (EUDI): 0 | P3 (Fraud/Deepfakes): 1 (OCR Studio) | P4 (ZKPs): 0 (carry-forward note) | P5 (Passwordless): 0 | P6 (LATAM): 0 | P7 (Identity ecosystem): 2 (IATA/Trip.com catch-up + World Bank ID4Africa soft signal) → Total: **3 hard findings + 1 soft signal** (quiet weekend window)
- Override-worthy: FCA / Nikhil Rathi "financial crime is national security" speech — pairs with the 05-14 ECB Elderson AI-cyber override into a cross-Channel "defence is national-security infrastructure, not compliance" theme
- Delta path: research/2026-05-18-cycle-delta.md
