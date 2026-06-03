# Cycle Delta — 2026-06-03

Window: 2026-06-01 → 2026-06-03 (last 48 hours)

## Override-worthy this cycle

1. **Worldline + ING + Mastercard: Europe's first live end-to-end agentic payment completed in production (2 June 2026, Money20/20 Amsterdam)** — A merchant AI agent identified concert tickets within a consumer's stated budget and executed the purchase on the ING cardholder's behalf across the Mastercard network and Worldline infrastructure spanning Belgium and the Netherlands; consumer retained final-approval authority. Account:. Angle: "Agentic commerce just went to production on European rails. The payment-auth problem is solved. The credential-delegation problem — what does the agent present, and who authorised it? — isn't."

2. **Visa executive at Money20/20 calls EUDI wallet "crucial for the financial sector" — positions it as covering payments, IBAN verification, income proof and fraud prevention, citing Visa's active participation in the EU Digital Identity Wallet Consortium (EWC) Large Scale Pilot** — first payments-network-level executive endorsement of EUDI wallet as strategic infrastructure (not merely compliance) at the year's largest fintech venue. Account: / company. Angle: "When Visa's exec team calls the EUDI wallet crucial at Money20/20, the narrative shifts from 'December 2026 deadline' to 'competitive infrastructure.' Identity vendors who aren't on the wallet layer are already behind."

## New findings

### Pillar 1: Banking & Payments

(No new dated-in-window regulatory finding. PSD3/PSR: plenary vote still unscheduled following ECON adoption on 5 May; OJEU publication anticipated June/July 2026, may slip to September — no change from prior delta. DORA: no new enforcement action in window. AMLA CDD RTS: consultations closed 8 May, final draft to Commission 10 July — calendar anchor, not new news. MiCA CASP hard deadline 1 July is 28 days out — recurring anchor.)

### Pillar 2: EUDI / eIDAS2

- **Visa executive at Money20/20 Europe (Amsterdam, 2–4 June 2026) characterises EUDI wallet as "crucial for the financial sector" — cites live Large Scale Pilot participation via the EWC consortium and positions wallet use cases spanning payments authentication, IBAN verification, income-proof attestation and fraud prevention across financial-services workflows.** — First public executive-level endorsement from a tier-1 payments network treating the wallet as strategic product infrastructure rather than regulatory checkbox. Visa's EWC participation brings the wallet into the Mastercard/Visa acceptance layer directly, which materially raises the stakes for banks that have not yet begun relying-party integration (December 2027 mandatory-acceptance deadline for regulated entities). The income-proof and fraud-prevention framing extends EUDI's narrative well beyond digital-onboarding into continuous lifecycle use cases — exactly the "wallet as identity chokepoint" theme from the baseline standing angles.
  - Source: https://www.biometricupdate.com/202506/eudi-wallet-crucial-for-the-financial-sector-visa-exec-tells-money20-20
  - Date: 2026-06-02 / 2026-06-03 (Money20/20 Days 1–2, Amsterdam)

### Pillar 3: Fraud / Deepfakes

(No new named-bank deepfake or synthetic-ID incident with a verified in-window date. "Fighting Deepfakes: A Bank's Year on the Front Line" session at Money20/20 is scheduled for 4 June (Day 3) — sweep next cycle for outputs. Standing anchors — iProov iOS injection +1,151%, Sumsub multi-step +180%, Regula 87%/26% gap — unchanged.)

### Pillar 4: ZKPs in practice

(No new dated-in-window finding. DIF KYA-OS (Trusted Agentic AI WG) v1.0 vote result still not published as of this scan — carry-forward again. OpenID ASC 1.0 Implementer's Draft formally approved 27 May is the standing selective-disclosure anchor from the 06-01 delta.)

### Pillar 5: Passwordless / split-key

(No new dated-in-window finding. FIDO Authenticate APAC 2026 opens 4 June in Singapore — sweep next cycle for any spec announcements. Philippines BSP OTP sunset: 25–30 June 2026, now 22–27 days out. No extension confirmed. Recurring calendar anchor.)

### Pillar 6: LATAM

(No new dated-in-window finding. Colombia open finance Decree 0368 implementation unchanged — 7 August 2026 technical deadline. Standing Drex / Pix MED 2.0 / CNBV / deepfake anchors unchanged.)

### Pillar 7: Identity ecosystem

- **Worldline + ING + Mastercard complete Europe's first live end-to-end agentic payment in production — announced 2 June 2026 at Money20/20 Europe (Amsterdam).** — An ING cardholder browsed for a wedding-anniversary gift; a merchant AI agent identified concert tickets within the stated budget and completed the transaction across the Mastercard network, using Worldline infrastructure spanning Belgium and the Netherlands; the consumer granted explicit final approval before settlement. This is distinct from the Mastercard × Santander × PayOS pilot (March 2026, also in prior context) — this is a Worldline-led production deployment with a Dutch retail ING cardholder rather than a controlled sandbox. Identity/authentication significance: the transaction demonstrates that the "agentic payment" model — AI agent acts on behalf of a credentialed consumer — is now in production on live European rails. The unsolved adjacent problem is credential delegation: what cryptographic claim does the merchant agent present to prove it is authorised by that cardholder? The FIDO Agentic Authentication TWG ("Verifiable User Instructions / Agent Authentication / Trusted Delegation") is exactly the standards gap this production proof point exposes. Ditto's ZKP/split-key/selective-disclosure stack sits at precisely the credential-delegation layer the market now needs.
  - Source: https://www.globenewswire.com/news-release/2026/06/02/3305397/0/en/WORLDLINE-Worldline-and-ING-complete-a-live-end-to-end-European-agentic-payment-in-production-Press-release.html
  - Source: https://worldline.com/en/home/top-navigation/media-relations/press-release/pr-2026_06_02_01
  - Source: https://www.finextra.com/newsarticle/47844/ing-completes-live-end-to-end-european-agentic-payment-transaction
  - Date: 2026-06-02

---

## Next-cycle anchors

- **Money20/20 Europe Day 3 (4 June, Amsterdam)** — "Fighting Deepfakes: A Bank's Year on the Front Line" (Horizon Stage, 13:45–14:15); closing keynotes; any final EUDI/eIDAS-2 session outputs
- **EUDI ON Hackathon remote (4–5 June 2026)** — first community-driven EUDI Wallet build event; EAA (professional qualifications, driving licence, academic degrees) as focus; winning teams present at Berlin Community Event 25 June
- **FIDO Authenticate APAC 2026 (4–5 June, Singapore)** — watch for any new spec announcements from the Agentic Authentication TWG or passkey regional-deployment data
- **DIF KYA-OS WG vote result** — still unposted; multi-cycle carry-forward; next check: 4 June
- **PSD3/PSR plenary vote** — still unscheduled; OJEU publication June/July 2026 (may slip to September)
- **UK People's Panel on digital ID workshop 2 (20–21 June)**
- **FATF Best Practices on Travel Rule Supervision (26 June)**
- **Philippines BSP Circular 1213 OTP sunset (25–30 June)** — hard deadline for phasing out SMS/email OTPs at all BSP-supervised FIs; no extension confirmed
- **MiCA CASP hard deadline (1 July)** — CASPs without authorisation must cease EU services; Travel Rule zero-threshold applies
- **AMLA CDD RTS final draft → European Commission (10 July)**
- **EUDI Wallet Community Event "EUDI ON" (25 June, Berlin)** — government/ecosystem status update; hackathon winning-team presentations

---

## Run summary

- Findings count by pillar: P1: 0 | P2: 1 (Visa exec / EUDI wallet "crucial for financial sector" — Money20/20) | P3: 0 | P4: 0 | P5: 0 | P6: 0 | P7: 1 (Worldline + ING + Mastercard first production agentic payment in Europe) → **Total: 2 unique findings**
- Override-worthy: **2** — (1) Worldline/ING/Mastercard Europe's first production agentic payment (credential-delegation problem is now live on real rails); (2) Visa exec calls EUDI wallet "crucial" at Money20/20 (tier-1 payments network treats wallet as strategic, not just compliance)
- Delta path: research/2026-06-03-cycle-delta.md
