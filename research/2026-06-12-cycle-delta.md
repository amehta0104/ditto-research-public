# Cycle Delta — 2026-06-12

Window: 2026-06-09 → 2026-06-12 (last 72 hours — Friday schedule)

## Override-worthy this cycle

(none)

## New findings

### Pillar 1: Banking & Payments

- **Sumsub partners with stablecoin-native fintech Reap to deliver Reusable KYC for cross-border payments onboarding (June 11, 2026).** — Reap, which builds stablecoin-native cards and payments infrastructure for businesses and is expanding from APAC into new markets, has embedded Sumsub's compliance platform to automate KYC/AML checks for both business customers and individual cardholders. The headline capability is Sumsub's Reusable KYC: a returning user who has already been verified through Sumsub's pipeline does not need to repeat the check at each new onboarding flow — the credential is portable across participating platforms. Regulatory context: stablecoin CASPs are among the 1,200+ VASP entities facing the MiCA July 1 mandatory-authorization deadline, and the AMLR (applying July 10, 2027) will require full CDD-compliant onboarding across the EU. Ditto significance: Sumsub's Reusable KYC is a centralised, provider-controlled model — the user's reusable credential lives in Sumsub's infrastructure. The EUDI Wallet + ZKP selective-disclosure model achieves the same reusability but with the user controlling the credential presentation layer, making portability structurally consent-first rather than platform-first. This product-market moment illustrates the design fork the identity industry is approaching in 2026.
  - Source: https://fintech.global/2026/06/11/sumsub-deal-gives-reap-compliance-edge-in-new-markets/
  - Source: https://fintechnews.sg/132839/payments/reap-sumsub/
  - Source: https://idtechwire.com/sumsub-partners-with-reap-to-power-compliance-for-stablecoin-payments-onboarding/
  - Date: 2026-06-11

(PSD3/PSR plenary vote: still unscheduled as of June 12; OJEU publication guidance unchanged at June/July 2026 with possible September slip — no new material. AMLA CDD RTS final draft to Commission July 10 — no new development in window. MiCA CASP July 1 deadline: 19 days; no named firm cease-operations announcement confirmed in window beyond what June 10 delta covered.)

### Pillar 2: EUDI / eIDAS2

(no new material — EUDI ON Community Event Berlin June 25 approaching; no new Commission, ENISA, or ARF announcement in window. Member-state readiness benchmark (fewer than one-third meeting December 24 deadline) unchanged.)

### Pillar 3: Fraud / Deepfakes

(no new material — Meta NameTag arc: UK ICO contact established June 8; no named EU DPA inquiry, EDPB coordination, or EU AI Act high-risk notification confirmed in window. Lloyds Bank 68%/£66m Meta fraud attribution data (June 9, 2026) fully covered in June 10 delta.)

### Pillar 4: ZKPs in practice

(no new material — DIF KYA-OS v1.0 vote result still pending — multi-cycle carry-forward. OpenID4VP v1.1 in active development. No new bank pilot or mDL selective-disclosure deployment in window. Note: the Sumsub/Reap Reusable KYC item in Pillar 1 is a directly adjacent development — provider-controlled reusable KYC vs. user-controlled ZKP selective-disclosure.)

### Pillar 5: Passwordless / split-key

(no new material — Philippines BSP Circular 1213 / AFASA hard deadline June 25/30: 13–18 days out; GCash (90M+ users) set June 22 as its internal user migration deadline from SMS to in-app push-notification OTPs (announced June 5, outside 72h window but noted for anchor update). No new BSP compliance-rate data or extension signal in window. Microsoft Entra passkeys on Windows GA rollout completing mid-June 2026 — ongoing, but GA announcement was from April/May; no new in-window Microsoft announcement.)

### Pillar 6: LATAM

(no new material — Brazil Drex privacy bill second committee passage not yet confirmed; BCB Phase 2 unchanged. Colombia open finance Decree 0368 technical deadline August 7 unchanged. Mexico CNBV Open Finance rules delay continues.)

### Pillar 7: Identity ecosystem

- **Fastly + Skyfire: first CDN-level deployment of verified AI agent identity — "Know Your Agent" architecture goes live at the edge (June 10, 2026).** — Fastly (NYSE: FSLY) and Skyfire announced a partnership that embeds Skyfire's KYC-backed agent identity credentials directly into Fastly's global edge cloud platform. The mechanism: AI agents making requests through Fastly's infrastructure can carry Skyfire's tokenised, KYC-verified identity credentials, allowing enterprise targets to distinguish verified revenue-generating agents from malicious automation in real time, at scale, without re-architecting their infrastructure. As AI agents increasingly browse, negotiate, and transact autonomously — Fastly's own research shows AI traffic grew 6.5x faster than human traffic over the last year — the "Know Your Agent" (KYA) identity problem has become a production-grade infrastructure challenge, not a whitepaper concept. Ditto significance: agent identity is structurally the same problem as human identity at higher velocity. The consent-first, selective-disclosure model Ditto advocates for human credentials applies equally to agent credentials — the question is whether the agent identity layer being built in 2026 embeds a privacy-first ZKP architecture or creates a new centralised surveillance layer for autonomous systems. The Fastly/Skyfire stack uses tokenised KYC credentials (provider-custodied) rather than zero-knowledge proofs, representing the same design fork as Sumsub/Reap in Pillar 1. Together these two June 10–11 announcements signal that 2026 is the year the centralised vs. decentralised identity architecture choice is being made at the infrastructure layer, not just the policy layer.
  - Source: https://www.businesswire.com/news/home/20260610660439/en/Fastly-and-Skyfire-Partner-to-Enable-Trusted-Agentic-Commerce-with-Verified-Identity-at-the-Edge
  - Source: https://idtechwire.com/fastly-and-skyfire-partner-to-bring-verified-identity-to-agentic-commerce-at-the-edge/
  - Date: 2026-06-10

---

## Next-cycle anchors (updated)

- **GCash internal SMS OTP sunset: June 22** — 90M+ users have until June 22 to migrate from SMS to in-app push-notification OTPs; failure means account access loss. First large-scale, consumer-visible passphrase migration event under BSP Circular 1213.
- **Philippines BSP Circular 1213 / AFASA deadline (June 25/30)** — 13–18 days; any last-minute compliance-rate data or BSP extension signal.
- **UK People's Panel on digital ID — Workshop 2 (June 20–21, Birmingham)** — second in-person session; interim recommendations on public acceptance of EUDI-style wallets; final session June 21 closes formal consultation.
- **EUDI Wallet Community Event "EUDI ON" (June 25, Berlin)** — hackathon winning-team presentations; Germany, France, Italy member-state status updates.
- **FATF Best Practices on Travel Rule Supervision (June 26)** — confirmed publication date; supervisory approaches for VASP Travel Rule compliance.
- **MiCA CASP hard deadline (July 1)** — 19 days; watch for named firm cease-operations announcements or NCA enforcement orders, especially France AMF June 30 hard stop for 90 unlicensed firms.
- **Meta NameTag regulatory response** — UK ICO engaged June 8; watch for named EU DPA inquiry, EDPB coordination, or EU AI Act high-risk notification.
- **AMLA CDD RTS final draft → Commission (July 10)** — calendar anchor.
- **PSD3/PSR plenary vote** — still unscheduled; OJEU publication June/July 2026 (may slip to September).
- **Brazil Drex privacy bill** — watch for second committee approval or amendment to anti-surveillance provisions.
- **DIF KYA-OS v1.0 vote result** — multi-cycle carry-forward.
- **Japan JSDA phishing-resistant MFA mandatory deadline** — "summer 2026"; watch for JSDA formal finalization.
- **AI agent identity standards** — FIDO Alliance Agentic Authentication TWG (formed April 27) in active spec development; Fastly/Skyfire commercial deployment (June 10) is the first production milestone to benchmark the spec work against.

---

## Run summary

- Findings count by pillar: P1: 1 (Sumsub/Reap Reusable KYC for stablecoin payments, June 11) | P2: 0 | P3: 0 | P4: 0 | P5: 0 | P6: 0 | P7: 1 (Fastly/Skyfire AI agent identity at edge, June 10) → **Total: 2 unique findings**
- Override-worthy: **none**
- Delta path: research/2026-06-12-cycle-delta.md
