# Cycle Delta — 2026-08-18

Window: 2026-08-16 → 2026-08-18 (last 48 hours — Tuesday)

Worker note: `ditto-slack-bot.dittobot.workers.dev` returns 403 this session (egress-proxy policy denial — same class as the 2026-08-10→08-14 runs). Delta written to GitHub directly via MCP. Skill files read via GitHub MCP. This is a tooling regression, not a content gap; all research steps completed normally.

This is a **quiet regulatory cycle** — no new EBA, AMLA, EUDI, or FIDO print in window. The single discrete finding is a **correction to the September 1 cluster**: France's Constitutional Council struck down the under-15 social media ban on August 14, voiding the September 1 France age-verification implementation date carried as a positive cluster item in the 08-17 delta. The only other in-window item is a directional LATAM note (Mexico CURP-SIM enforcement phase begun Aug 17). PSD3 OJEU remains absent for a ninth consecutive cycle.

---

## Override-worthy this cycle

1. **France's Constitutional Council struck down the under-15 social media ban on 2026-08-14 — killing the September 1 implementation date named in the 08-17 cluster.** Account: / company. Angle: this is not a policy-wonk footnote — it is the clearest signal yet that mandatory age verification at platform level is constitutionally fragile when the verification method is unspecified. The Council censured Article 1 on two grounds that map directly to Ditto's product thesis: (i) the law was disproportionate because it was too broad, and (ii) it did not sufficiently protect users' privacy in relation to age verification. ZKP-backed wallet credentials — the EUDI Wallet Age Verification App's Longfellow ZK track, selective-disclosure attribute release — are the only available mechanism that resolves both constitutional objections simultaneously. The DSA is now the only remaining EU-level tool in France for platform child-safety enforcement, and it does not mandate age verification. Contrast with Ofcom's approach: binding rules under the Online Safety Act rather than standalone age legislation, with Ofcom's "highly effective" definition due October — which now becomes the European de facto benchmark. Correction for the drafter: **do not publish any post that references France September 1 age verification as an upcoming milestone; it is void.**

---

## New findings

### Pillar 1: Banking & Payments

(No new EBA / ECB / FCA / PSR publication dated 16–18 Aug. **PSD3/PSR OJEU**: no OJEU notice number — ninth consecutive cycle. Final compromise texts 23 Apr; ECON second-reading recommendation 18 May; publication anticipated summer/Q3 2026; entry into force 2027. **AMLA Level 2**: 23 RTS/ITS submitted to Commission by 10 Jul; Commission adoption typically 3–6 months after submission; no adoption confirmed; Article 28(1) CDD RTS remains the highest-value watch item; AMLR applies 10 Jul 2027. **PSR APP-fraud post-implementation review**: survey out to 50 firms, report expected Q3 2026, formal consultation December 2026. No new discrete print 16–18 Aug.)

### Pillar 2: Identity orchestration

(No new Forrester / KuppingerCole / Gartner / Liminal publication or identity M&A announcement dated 16–18 Aug. Standing watch items unchanged: KuppingerCole NHI Management Leadership Compass pending 2026; Okta x Permiso ~$200M close expected Okta Q3 FY2027 (Aug–Oct 2026); Cyera x Oasis $1B (3 Aug close). No new in-window print.)

### Pillar 3: EUDI / eIDAS2

(No new ARF update, ENISA certification action, member-state wallet launch or slip, or relying-party integration milestone dated 16–18 Aug. **Relying Party Engagement Programme first webinar**: Commission committed to invitations by end of August (~13 days); still pending as of 18 Aug — unchanged. **Wallet-availability deadline**: 24 Dec 2026 (128 days) — Italy live, Spain pilot, Germany 2 Jan 2027, Netherlands likely miss, Malta partial, Bulgaria not started. No new in-window print.)

### Pillar 4: KYC / AML compliance

(No new FATF, AMLA, AMLR, or national-AML-supervisor print dated 16–18 Aug. Status unchanged from 08-17 delta.)

### Pillar 5: Customer onboarding

(No new onboarding-KPI study or benchmark dated 16–18 Aug. No new in-window print.)

### Pillar 6: Identity verification (IDV)

(No new iBeta certification, FIDO Document Authenticity output, or NIST IAL/SP 800-63 release confirmed 16–18 Aug. No new in-window print.)

### Pillar 7: Fraud / Deepfakes

(No new named-bank deepfake incident, primary vendor report, or FATF typology in window. WindRelay (P8 primary in 08-17 delta) is the live fraud anchor — no follow-up Group-IB attribution, new geographic expansion beyond CEE, or card-scheme response confirmed as of 18 Aug. **EU AI Act Article 50 GPAI enforcement**: retroactive fines possible on GPAI providers since 2 Aug 2026; no named first enforcement action against an identity or deepfake deployment confirmed 16–18 Aug — still the highest-value watch item in this pillar. No new discrete print 16–18 Aug.)

### Pillar 8: Mobile trust & app security

(No new named mobile malware campaign or CVE dated 16–18 Aug. WindRelay/SpyNote carried as primary finding in 08-17 delta; no follow-up attribution or geographic expansion in window. Standing context unchanged.)

### Pillar 9: Passwordless / split-key

(No new FIDO Alliance specification, regulator OTP-sunset, or major bank passkey deployment confirmed 16–18 Aug. **Microsoft Entra passkeys-by-default September 1** is a standing watch item — no new announcement in window; September 1 date has been known. **OpenAI Daybreak Red** (08-17 delta, P9) is the live assurance-gated-capability anchor. No new in-window print.)

### Pillar 10: ZKPs in practice

(No new bank ZKP pilot, OpenID4VP/VCI deployment, or selective-disclosure/mDL milestone confirmed 16–18 Aug. Note: the France Constitutional Council ruling (P11 below) makes ZKP-based age proofs strategically more urgent — the Council's two censure grounds (over-breadth + verification privacy) are exactly what selective-disclosure wallet credentials address. No new in-window ZKP print.)

### Pillar 11: Age assurance & privacy attributes

- **FIRST-CAPTURE — France's Constitutional Council struck down the under-15 social media ban on 2026-08-14, nullifying the September 1 new-account age-verification implementation date listed as a cluster item in the 08-17 delta.** The Constitutional Council censured Article 1 of France's Act to Protect Minors from Social Media Risks on the grounds that: (i) the ban constitutes a **disproportionate interference with freedom of expression and communication**; (ii) the law is too broad, covering services where risks to minors have not been proven; and (iii) the law does not sufficiently protect users' **privacy in relation to the age verification checks required to enforce it**. Separately, Parliament had already stripped the age-verification mechanism from the final bill before passage (July 21, 2026) — meaning even before the Constitutional Council ruling, the law carried no designated verification method. The ruling removes Article 1 entirely; **new legislation would be required to revive the ban**, and no timeline for re-submission has been announced. Practical effect: the **September 1 France cluster item is void** — no French mandatory new-account age verification begins on 1 September 2026. The DSA (which does not mandate age verification) is the only remaining EU-level enforcement tool in France for platform child-safety.

  Integrity note: this item was dated **2026-08-14** — within the 08-17 delta's window — and was **not captured** by that delta, which continued to list France September 1 as a positive cluster item. Carried here as a first-capture and a direct correction to the prior cluster anchors.

  Two productive angles for the drafter. (A) **Regulatory fragmentation is the real age-assurance risk**: France's constitutional defeat shows that standalone age-verification mandates face a harder bar than OSA-style embedding. The UK's approach — Ofcom binding rules under the Online Safety Act, "highly effective" age assurance definition due October, fines of up to 10% of global turnover — is now the European model that survives constitutional scrutiny. The DSA leaves age verification to platforms' discretion in France. (B) **Privacy-preserving verification is now the constitutional answer**: the Council cited privacy of verification as a core failure. ZKP-backed age proofs and wallet-based selective-disclosure attribute release are the only technically available mechanism that resolves both the "over-breadth" and "verification privacy" objections simultaneously — and no other currently-deployed age verification method does both. This directly connects to the EUDI Wallet Age Verification App's Longfellow ZK experimental track and to Sub-theme B (ZKP selective disclosure in `zkp-in-practice.md`).

  - Source: https://www.france24.com/en/france/20260814-france-s-constitutional-authority-strikes-down-social-media-ban-for-under-15s
  - Source: https://www.anews.com.tr/world/2026/08/14/frances-constitutional-council-strikes-down-child-social-media-ban
  - Source: https://thenextweb.com/news/france-social-media-ban-under-15s-constitutional-council
  - Source: https://www.insideglobaltech.com/2026/08/14/french-constitutional-council-strikes-down-under-15-social-media-ban/
  - Date: 2026-08-14 (first-capture; missed by 08-17 delta)

(Standing age-assurance context: Ofcom statutory age-assurance report 27 Jul 2026 — child exposure to highly effective age checks rose 25%→43% Jan 2026, 69M+ age checks completed; Ofcom October rapid assessment to Parliament on "highly effective" for under-16 social media; UK social media ban for under-16s announced 15 Jun 2026, secondary legislation before Christmas, enforcement Spring 2027; Brazil ANPD Digital ECA Phase II administrative sanctions Nov 2026; US Senate Commerce Committee advanced age-verification legislation 5 Aug 2026 — out of window but noted.)

### Pillar 12: LATAM

- **Directional — Mexico's telecoms regulator enters active enforcement phase of biometric CURP-SIM registration mandate; unlinked lines face 72-hour service suspension (2026-08-17)** — Mexico's telecommunications regulator (IFT) commenced the active enforcement phase of the national mobile SIM registration mandate, with phone lines not linked to a CURP (biometric national identity record) facing service suspension within 72 hours — retaining access only to emergency services and carrier customer care until subscribers complete registration. Reported in ID Tech Wire's 17 Aug digest (direct fetch blocked; item extracted from search snippet). Directional: this is an IFT (telecoms) mandate, operating on a different track from the **CNBV CUB biometric reform** (DOF July 1, 90 business-day compliance wall landing early-to-mid November 2026). The relevance is convergence: the same national identity record (CURP) underpins both mandates, so a consumer who has not biometrically registered their SIM is increasingly the same consumer who cannot complete CNBV-compliant digital onboarding. For identity vendors in Mexico, this is a structural tailwind — biometric identity infrastructure is being enforced simultaneously from two regulatory angles (telecom + banking). Do not conflate the two mandates in a post — state clearly whether the context is SIM registration (IFT) or banking identity verification (CNBV CUB). The CNBV CUB angle remains the stronger anchor since it is directly in-ICP and no post has yet been built around it.
  - Source: ID Tech Wire August 17, 2026 digest (idtechwire.com — egress-blocked from direct fetch; item from search snippet)
  - Date: 2026-08-17

(No new Nubank / Mercado Pago / Ualá / BCB / CNBV print confirmed 16–18 Aug. Mercosur Decision 4/2026: still awaiting national-congress ratification in Argentina, Brazil, Paraguay, Uruguay — no ratification notice in window.)

---

## Next-cycle anchors (updated)

- **September 1 cluster — 14 days out — REVISED.** France under-15 item is **void** (Constitutional Council Aug 14). Surviving cluster items: (1) **UK DVS Trust Framework 1.0** — UKAS recognition of the certification scheme pending; no OfDIA enforcement-live date announced as of 18 Aug; supplemental age-assurance code still pending consultation. (2) **Microsoft Entra passkeys-by-default** — September 1 effective; Security Store opens 18 Sep for telecom-provider config; full SMS/voice blocking 1 Feb 2027. (3) **OpenAI Daybreak Red** — assurance-gated capability access (08-17 delta, P9). **Correct any draft that referenced France September 1 as an upcoming implementation date.**
- **Ofcom October rapid assessment to Parliament — now the European benchmark for age assurance.** With France's ban struck down and the DSA silent on method, Ofcom's "highly effective" definition is the highest-credibility reference standard available in Europe for platform age verification. Watch for a pre-submission consultation or working paper from Ofcom ahead of October.
- **EUDI Relying Party Engagement Programme — first webinar invitations by end of August (~13 days)** — still pending, unchanged. Highest-value near-term EUDI signal.
- **CNBV CUB compliance wall — early-to-mid November 2026** — first post opportunity; now reinforced by simultaneous IFT CURP-SIM enforcement (this delta).
- **EU AI Act Article 50 — first named enforcement action** — fines live from 2 Aug; no named identity/deepfake action in window. Highest-value watch item in P7.
- **WindRelay follow-through** — No new attribution, geographic expansion, or card-scheme response as of 18 Aug.
- **PSD3/PSR OJEU** — no OJEU notice number; ninth consecutive cycle.
- All other standing anchors from 08-17 delta unchanged.

---

## Run summary

- Findings count by pillar: P1 Banking: 0 | P2 Identity orchestration: 0 | P3 EUDI: 0 | P4 KYC/AML: 0 | P5 Onboarding: 0 | P6 IDV: 0 | P7 Fraud/Deepfakes: 0 | P8 Mobile trust: 0 | P9 Passwordless: 0 | P10 ZKP: 0 | P11 Age assurance: **1 first-capture** (France Constitutional Council, 2026-08-14, missed by 08-17 delta) | P12 LATAM: **1 directional** (Mexico IFT CURP-SIM enforcement, 2026-08-17) — **Total: 2 items across 2 pillars.**
- Override-worthy: **1** — France Constitutional Council struck down under-15 social media ban (Aug 14), voiding the September 1 cluster item. Constitutional grounds: disproportionate freedom-of-expression interference + insufficient age-verification privacy protection. Strategic angle: ZKP wallet selective-disclosure is the constitutional solution path; Ofcom's OSA-embedded approach is now the surviving European model. Correct any draft referencing France September 1 implementation.
- Delta path: research/2026-08-18-cycle-delta.md
- Note: worker 403 (egress-proxy policy denial); delta pushed to GitHub directly. Slack heartbeat posted to C0B2XF2KYKS.
