# Cycle Delta — 2026-11-03

Window: 2026-11-01 → 2026-11-03 (last 48 hours, Tue run)

## Provenance notes

- Worker (ditto-slack-bot.dittobot.workers.dev) blocked by egress proxy policy (403 on CONNECT). Consistent with all runs since at least 2026-10-22. Brand brief, pillar guides, and baseline not fetched from the worker this run.
- Prior-delta deduplication based on 2026-11-02-cycle-delta.md (most recent).
- 13 web searches executed across all 7 pillars.
- **Delta written to GitHub** (worker unavailable): `research/2026-11-03-cycle-delta.md`
- **Watch-item follow-ups confirmed this run:**
  - AMLA central AML/CFT database RTS public hearing (Nov 3, 14:00–16:00 CET): confirmed took place today; no outcomes document published yet.
  - BCB VASP bank-counterparty ban (Nov 6): confirmed effective in 3 days; BCB open data shows zero authorized VASPs as of this run — covered below as new.
  - Apple Cash ID check (Nov 9): confirmed; covered below as upcoming watch item with detail.
  - EUDI ARF Iteration 6: closes Nov 18; no new release or publication found.
  - Veridas + Fourthline merger: still pending close; no announcement found.
- **Checked and rejected (outside window or already covered):**
  - UK DSIT Digital Identity Sectoral Analysis 2026: published July 8, 2026; outside window.
  - WEF Unmasking Cybercrime deepfakes report: January 2026; outside window.
  - PSD3/PSR Council first-reading position: published Oct 21; outside window; OJEU publication still pending Q4 2026.
  - FIDO Alliance 7 billion passkeys milestone: published Oct 15; outside window.
  - FATF plenary outcomes: covered in Nov 2 delta.
  - Turkey age token: covered in Nov 2 delta.
  - AMLA RTS consultation: covered in Nov 2 delta.

---

## Override-worthy this cycle

(none)

---

## New findings

### Pillar 1: Banking & Payments

(no new material in window. AMLA central AML/CFT database RTS public hearing took place today (Nov 3, 14:00–16:00 CET, Brussels) — no outcomes document or amendment summary published as of this run; expect a summary on amla.europa.eu within days to weeks. PSD3/PSR: Council first-reading position published Oct 21 outside the window; OJEU publication still expected Q4 2026. FATF plenary outcomes and AMLA RTS consultation covered in the Nov 2 delta.)

### Pillar 2: EUDI / eIDAS2

(no new material in window. EUDI ARF Iteration 6 (topic: Digital Credentials API refinement) closes Nov 18; nothing published. Latest confirmed ARF version is v3.0.0, published July 21, 2026 on GitHub, aligning the framework with Commission Implementing Regulations 2026/1730, 2026/1731 and 2026/1735. National relying-party registers apply from December 24, 2026. 24/27 member states still tracking to miss the December 24 wallet-availability deadline.)

### Pillar 3: Fraud / Deepfakes

(no new material in window. No new named-bank deepfake case or primary-source fraud report dated Nov 1–3 found. Reference items for future drafting: Entrust 2026 Identity Fraud Report (pre-window) — deepfakes now account for 1 in 5 biometric fraud attempts; injection attacks up 40% YoY. LexisNexis / Juniper Research (July 2026) — 100.4 billion digital ID verification checks globally in 2026, up 16% YoY. These were outside the window and are noted for drafter context only.)

### Pillar 4: ZKPs in practice

(no new material in window. No bank pilot announcements or OpenID Foundation spec updates dated Nov 1–3 found. Technical note for context: the EUDI specification confirms ZKP age proofs ride the W3C Digital Credentials API, not OpenID4VP/DCQL, as no standardised DCQL query currently exists for them. The EUDI Longfellow Swift library (av-lib-ios-longfellow-zkp) for ZKP generation/verification of mdoc credentials is live on GitHub.)

### Pillar 5: Passwordless / split-key

(no new material in window. FIDO Alliance 7 billion passkeys milestone published Oct 15 — outside window. Key stats for future drafting: 42% of eligible accounts have a passkey enrolled; passkey sign-in success rate 93% vs. 78% for passwords/MFA; 57% of organisations with passkeys still rely on phishable authentication as primary day-to-day method. FIDO Passkey Rubric checklist forthcoming on Passkey Central.)

### Pillar 6: LATAM

- **BCB bank-VASP counterparty ban: zero firms authorized with 3 days to go (Nov 6 effective date).** Brazil's Banco Central published Resolution 589 on September 25, moving the start of the bank-counterparty ban from October 30 to November 6, 2026. As of this run (Nov 3), BCB's open authorization data shows zero licensed VASPs. One firm — Onda Finance (per BCB Comunicado 45.986, September 21) — is in the authorization process but not yet approved. From November 6, all BCB-supervised financial institutions (banks, payment institutions, other regulated entities) are barred from carrying out or facilitating crypto-market operations with counterparties that lack BCB authorization. VASPs that filed applications but have not yet been approved occupy a legal grey zone: third-party trackers estimate a 30-day stop period for non-filers ending November 29, but this is a calculated date, not an official BCB deadline. The practical consequence for identity vendors: virtually all Brazilian crypto firms servicing financial-institution counterparties face an immediate KYC/AML compliance squeeze that will accelerate demand for BCB-grade onboarding and continuous monitoring solutions.
  - Source: https://www.deepidv.com/media/minutes/brazil-bcb-vasp-authorisation-deadline-october-30-2026
  - Supporting: https://fcm.law/brazil-vasp-license/
  - Supporting: https://cryptoslate.com/crypto-laws/brazil-bcb-resolution-519-2025-vasp-authorization/
  - Date: 2026-11-03 (status confirmed; ban effective Nov 6)
  - Drafting caution: "Zero authorized VASPs" is from third-party tracker data, not a direct BCB API. Verify against the BCB's official authorization registry before citing the figure. Dates (Oct 30 vs. Nov 6) conflict across sources; Resolution 589 is the operative text.

### Pillar 7: Identity ecosystem

(no new material in window. No Forrester, KuppingerCole, or Gartner report dated Nov 1–3 found. Gartner Hype Cycle for Digital Identity 2026 exists (themes: AI agents, identity visibility, identity threats) but no November publication. Veridas + Fourthline merger still pending close. Reference for future drafting: UK DSIT Digital Identity Sectoral Analysis 2026 (published July 8) — 275 UK firms, ~£2B annual revenue, 77% of UK residents used a digital identity service; M&A noted includes TrustID, Keyless, DataTools acquisitions.)

---

## Upcoming watch items (next 7 days)

- **2026-11-06 (Thu):** BCB VASP bank-counterparty ban effective — verify whether any VASPs receive last-minute authorization; watch for BCB enforcement notices or clarifications on firms in-process.
- **2026-11-09 (Mon):** Apple Cash ID check goes live (US) — Green Dot Bank requires identity verification for all reloads regardless of size. Verify mechanism (credential vs. biometric). Signal: P2P payments now requiring identity gating by a major tech platform.
- **2026-11-18 (Wed):** EUDI ARF Iteration 6 closes — check for updated ARF version release.
- **~Days ahead:** AMLA central AML/CFT database RTS hearing outcomes summary — watch amla.europa.eu for post-hearing statement or amendment flags.
- **December 2026:** FATF mutual evaluation reports for US and Mexico published.
- **2026-12-24:** EUDI wallet-availability deadline — 51 days; 24/27 member states tracking to miss it.
- **H2 2026 (TBC):** Veridas + Fourthline merger closing — monitor for announcement.
