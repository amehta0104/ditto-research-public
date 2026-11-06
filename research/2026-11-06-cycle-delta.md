# Cycle Delta — 2026-11-06

Window: 2026-11-04 → 2026-11-06 (last 72 hours, Fri run)

## Provenance notes

- Worker (ditto-slack-bot.dittobot.workers.dev) blocked by egress proxy policy (host not in allowed network domains). Consistent with all runs since at least 2026-10-22. Brand brief, pillar guides, and baseline not fetched from the worker this run.
- Prior-delta deduplication based on 2026-11-05-cycle-delta.md (most recent).
- 13 web searches executed across all 7 pillars.
- **Delta written to GitHub** (worker unavailable): `research/2026-11-06-cycle-delta.md`
- **Watch-item follow-ups confirmed this run:**
  - BCB VASP bank-counterparty ban (Nov 6): **EFFECTIVE TODAY.** Article 91 of BCB Resolution 520/2025, as amended by Resolution 589/2026, is now operative. BCB-supervised banks and payment institutions may no longer carry out or facilitate crypto-market operations with unauthorized VASPs. No BCB press releases, enforcement orders, or last-minute authorizations found as of this run. See Pillar 6 below.
  - Apple Cash ID check (Nov 9): 3 days away. No new primary source this window; watch item intact.
  - AMLA central AML/CFT database RTS consultation (closed Nov 3): No post-hearing summary or amendment flag published as of this run. Watch amla.europa.eu.
  - EUDI ARF Iteration 6: Closes Nov 18; nothing published.
  - KuppingerCole Access Management Leadership Compass: Scheduled for November 2026 (calendar lists Nov 9); not yet confirmed as published.
- **Checked and rejected (outside window or already covered):**
  - ABN AMRO deepfake case (46 fraudulent accounts): First reported March 2026; outside window.
  - Utah adult site age verification enforcement (Nov 2): Outside window.
  - Papua New Guinea / Ethiopia biometric digital ID (Nov 3): Outside window.
  - PSD3/PSR Council text: OJEU publication still pending Q4 2026; no new development.
  - FIDO 7 billion passkeys (Oct 2026) + Passkey Index data: Outside window; already covered in prior deltas.
  - Veriff, Sumsub, iProov annual reports: All pre-window; no November 2026 edition found.

---

## Override-worthy this cycle

(none)

---

## New findings

### Pillar 1: Banking & Payments

(no new material in window. No new EBA, ECB, FCA, or PSR guidance dated Nov 4–6 found. PSD3/PSR: OJEU publication still expected Q4 2026; no confirmation. AMLA central AML/CFT database RTS public hearing concluded November 3 — no outcomes document published as of this run. DORA: no new enforcement actions found.)

### Pillar 2: EUDI / eIDAS2

- **Kosovo launches national eID wallet with EUDI alignment intent, enrollment opening November 9.** Kosovo's Ministry of Digitalization and Public Administration launched a national eID, digital wallet, and e-signature framework in early November 2026. Enrollment opens November 9. EU interoperability is not yet confirmed; Kosovo is an EU accession candidate and the launch is framed explicitly as a step toward EUDI alignment. Significance for the wallet ecosystem: candidate-state launches ahead of full EU membership show the ARF/eIDAS2 architecture spreading beyond the 27-member bloc; validates the portability of the EUDI technical stack. Limited direct relevance to Ditto's regulated-banking audience but useful context's ecosystem angle.
  - Source: https://www.biometricupdate.com/202611/kosovo-launches-national-digital-id-wallet-e-signatures-ahead-of-eudi-alignment
  - Date: 2026-11 (early November)
  - Drafting caution: Limited detail on technical specification; EU interoperability not confirmed. Source is Biometric Update reporting on a ministerial announcement; verify against Kosovo MDPA official site before citing technical claims.

### Pillar 3: Fraud / Deepfakes

- **ID-Pal integrates biometric identity and business verification into ThirdEye's AML platform for Australian and New Zealand financial institutions.** Published November 5, 2026. ID-Pal's biometric KYC module (document capture + selfie biometric) is now embedded into ThirdEye's AML-screening platform, enabling AUS/NZ regulated financial institutions to run identity verification and AML screening from a single workflow without switching tools. This follows a pattern seen across the EU market: identity vendors being absorbed as infrastructure layers inside compliance platforms, rather than deployed standalone. Significance: illustrates the "identity as AML plumbing" consolidation thesis — the same dynamic driving EU demand for interoperable KYC outputs that can feed directly into AMLA-compliant workflows.
  - Source: https://www.biometricupdate.com/202611/id-pal-brings-biometric-identity-verification-to-thirdeyes-aml-platform
  - Date: 2026-11-05
  - Drafting caution: AUS/NZ market focus; direct EU regulatory applicability is indirect. Useful as a market consolidation data point, not as a primary EU regulatory signal.

### Pillar 4: ZKPs in practice

(no new material in window. No bank pilot announcements or OpenID Foundation spec updates dated Nov 4–6 found. EUDI ARF Iteration 6 (covering Digital Credentials API refinement and ZKP age-proof pathway) closes Nov 18 — nothing published yet. Status unchanged from Nov 5 delta.)

### Pillar 5: Passwordless / split-key

- **FIDO Passkey Rubric now live on Passkey Central — bronze-to-platinum deployment self-assessment tool.** The Passkey Rubric, previewed at FIDO's Authenticate conference (October 2026) alongside the 7-billion-passkey milestone announcement, is now live at passkeycentral.org/launch-and-grow/passkey-rubric. Prior deltas flagged it as "forthcoming"; it is now confirmed published. The rubric covers three phases — creating a passkey, signing in with it day-to-day, and passkey management — and uses bronze/silver/gold/platinum tiers to give product and engineering teams a progressive self-assessment framework. It flags common pitfalls (allowing only one passkey per account) and overlooked capabilities (automatic passkey upgrades). Supporting material on Passkey Central also covers employee deployments with case studies from Cloudflare, Target, Semperis and RSA. Significance: the rubric operationalizes FIDO's research and UX guidance into an actionable checklist for deployers — useful signal for identity vendors positioning around FIDO-based passwordless as a capability baseline.
  - Source: https://www.passkeycentral.org/launch-and-grow/passkey-rubric
  - Supporting: https://fidoalliance.org/7-billion-passkeys-and-counting-the-next-chapter-of-passwordless-authentication/
  - Supporting: https://napapay.ai/payment-radar/fido-reports-rising-passkey-use-and-previews-a-deployment-checklist
  - Date: 2026-11 (confirmed live by Nov 6, 2026)

### Pillar 6: LATAM

- **BCB VASP bank-counterparty ban effective today (November 6, 2026): no authorized VASPs confirmed, no enforcement notices found.** Article 91 of BCB Resolution 520/2025, as amended by Resolution 589/2026, is now operative. BCB-supervised banks, payment institutions, and other regulated entities are barred from carrying out or facilitating virtual asset operations — including custody, FX, payment accounts, and payment transactions — with counterparties that have not received BCB authorization. As of September 2026 data, no VASP had been granted SPSAV authorization. Firms that filed applications by the October 30 deadline may occupy a legal grey zone pending their reviews; sources conflict on whether "in process of authorization" language was preserved after the Resolution 589 amendment. No BCB press releases, enforcement orders, or last-minute authorization announcements were found as of this run. The practical consequence for identity vendors: virtually all Brazilian crypto firms servicing bank counterparties now face an immediate KYC/AML compliance crisis — demand for BCB-grade onboarding and continuous-monitoring solutions is likely to spike. The ban also strengthens Brazil's existing Pix-linked identity infrastructure as the dominant channel for financial-services identity flows, reinforcing Drex as the settlement layer.
  - Source: https://fcm.law/brazil-vasp-license/
  - Supporting: https://www.deepidv.com/media/minutes/brazil-bcb-vasp-authorisation-deadline-october-30-2026
  - Supporting: https://lumx.io/blog-posts/bank-account-for-vasp
  - Date: 2026-11-06 (effective date)
  - Drafting caution: "No authorized VASPs" derives from September 2026 BCB data via secondary trackers — not a direct BCB API read. Verify against bcb.gov.br authorization registry before citing. Date discrepancy (Oct 30 vs Nov 6) across sources; Resolution 589 is the operative text for Nov 6.

### Pillar 7: Identity ecosystem

(no new material meeting the bar this cycle. KuppingerCole Access Management Leadership Compass is on the November 2026 calendar (est. November 9); not yet confirmed published as of this run — check kuppingercole.com/researchplan/leadership-compass-access-management-2026. No M&A or funding announcements found in window. Future Identity Festival London runs November 9–10 — may generate analyst/vendor announcements next run. 26th NextGen Payments and RegTech Forum, Austin, runs November 10.)

---

## Upcoming watch items (next 7 days)

- **2026-11-09 (Mon):** Apple Cash ID check goes live (US) — verify user experience; iOS 27 Wallet ID credential pathway is likely mechanism for Green Dot Bank-required identity gating on P2P reloads. Watch for any Apple or Green Dot press release.
- **2026-11-09 (Mon):** KuppingerCole Access Management Leadership Compass — check kuppingercole.com for publication; scheduled November 2026 (calendar ref: Alejandro Leal). Will cover FIDO2/WebAuthn, passkeys, device-bound credentials, non-human identity access, AI governance.
- **2026-11-09–10 (Mon–Tue):** Future Identity Festival, London — watch for vendor announcements, analyst keynotes, M&A signals.
- **2026-11-10 (Tue):** 26th NextGen Payments and RegTech Forum, Austin — watch for payments-identity convergence announcements.
- **2026-11-18 (Wed):** EUDI ARF Iteration 6 closes — check for updated ARF version on GitHub (eu-digital-identity-wallet/eudi-doc-architecture-and-reference-framework).
- **~Days ahead:** AMLA central AML/CFT database RTS consultation outcomes — watch amla.europa.eu for post-hearing summary or amendment flags.
- **2026-12-24:** EUDI wallet-availability deadline — 48 days; 24/27 member states tracking to miss it. Germany confirmed Jan 2, 2027; Finland and others slip to 2027.
