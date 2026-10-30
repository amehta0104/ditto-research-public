# Cycle Delta — 2026-10-30

Window: 2026-10-28 → 2026-10-30 (last 72 hours, Friday run)

## Provenance notes

- Worker (ditto-slack-bot.dittobot.workers.dev) blocked by egress proxy policy (403 on CONNECT). Consistent with all runs since at least 2026-10-22. Brand brief, pillar guides, and baseline not fetched from the worker this run.
- Prior-delta deduplication based on 2026-10-29-cycle-delta.md and 2026-10-28-cycle-delta.md.
- 13 web searches executed across all 7 pillars.
- **Delta written to GitHub** (worker unavailable): `research/2026-10-30-cycle-delta.md`
- **FATF plenary Paris (Oct 28–30):** President's press conference scheduled 17:00 CEST today. Outcomes not indexed before this run fired (06:00 ET). **Priority for Nov 3 delta.**
- **EUDI Launchpad Brussels (Oct 29–30):** Day 2 concluded today. No public Commission announcements or ARF updates found as of this run.
- **BCB bank-VASP counterparty ban:** In effect from today (Oct 30). Covered in Oct 29 delta as "taking effect tomorrow" — status note included under Pillar 6, not a new independent finding.
- **Checked and rejected (outside window or already covered):**
  - identifAI $40B deepfake fraud estimate (Oct 14): outside window.
  - Ofcom facial age estimation endorsement (Oct 29): covered in Oct 29 delta.
  - EUDI 24/27 member states missing deadline: covered in Oct 28 delta.
  - TransUnion $2.4B synthetic identity: covered in Oct 28 delta.
  - Veridas + Fourthline merger announcement (Jul 16): outside window; likely in July delta.
  - PSD3/PSR OJEU publication: not confirmed as of searches today.

---

## Override-worthy this cycle

(none)

---

## New findings

### Pillar 1: Banking & Payments

(no new material in window. FATF plenary press conference scheduled Oct 30 at 17:00 CEST — outcomes not indexed before this run fired; priority for Nov 3 delta. PSD3/PSR OJEU publication still unconfirmed; last known status: ECON committee adoption May 2026, OJEU expected H2 2026.)

### Pillar 2: EUDI / eIDAS2

(no new material in window. EUDI Launchpad 2026 Day 2 concluded today in Brussels — no public Commission announcements, press releases, or ARF updates found as of this run. France Identité has 5M users per tracker dated Oct 5; Italy IT-Wallet and Denmark AltID remain the most advanced national implementations. **Priority for Nov 3 delta:** any ARF or Commission materials from the Launchpad.)

### Pillar 3: Fraud / Deepfakes

(no new material in window. All deepfake reports found dated outside the 72h window. identifAI $40B estimate (Oct 14) already rejected in Oct 29 delta.)

### Pillar 4: ZKPs in practice

(no new material in window. OpenID4VP 1.0 migration from Presentation Definitions to DCQL (Digital Credential Query Language) confirmed in March 2026 — outside window. No new bank pilots or OpenID Foundation spec updates found for this period.)

### Pillar 5: Passwordless / split-key

(no new material in window. No new FIDO Alliance announcements found. Ofcom facial age estimation endorsement covered in Oct 29 delta.)

### Pillar 6: LATAM

- **CNBV Anexo 71 facial biometrics compliance deadline confirmed as today / early next week — Mexican banks must now meet new facial biometric requirements.** The 90-business-day transition window from the July 2, 2026 Diario Oficial publication of CNBV's amended Anexo 71 (CUB Biometrics reform) expires around October 30 – November 1, 2026. Multiple sources confirm the deadline as "finales de octubre / inicios de noviembre." Key requirements: (1) facial biometrics added alongside fingerprints for in-person customer identity verification — fingerprint-only compliance is no longer sufficient; (2) 1:1 matching against INE or SRE biometric records with a ≥90% match rate; (3) presentation attack detection (PAD) compliant with ISO/IEC 30107-3; (4) biometric databases prohibited from being sold, shared, or made interoperable with third parties. Iris and voice remain excluded. This is the first time facial biometrics are formally mandated for Mexican banking KYC at the branch level.
  - Source: https://facephi.com/observatory/en/cnbv-facial-biometrics-regulation/
  - Supporting: https://kyc-systems.com/blog/reforma-cub-biometricos-cnbv-2026
  - Supporting: https://www.mobiletime.com.br/noticias/03/07/2026/mexico-obliga-biometria-facial-servicos-bancarios/
  - Supporting: https://basham.com.mx/en/resolution-amending-the-general-provisions-applicable-to-credit-institutions/
  - Date: 2026-10-30 (deadline window; regulation published 2026-07-02)
  - Drafting caution: Deadline and technical specs sourced primarily from Facephi (a biometrics vendor with a commercial interest) and law-firm commentary. Verify against official CNBV text and the Diario Oficial de la Federación before publishing.

- **BCB bank-VASP counterparty ban now in effect (status follow-up).** As of today (October 30), BCB-supervised financial institutions are prohibited from conducting virtual-asset operations with counterparties lacking BCB authorization or a pending application. This is the enforcement consequence of the October 29 VASP filing deadline covered in the Oct 29 delta. No BCB enforcement notices or authorization announcements found as of this run. Verify effective date — October 30 vs. November 6 per Res. 589 — against official BCB text.
  - Date: 2026-10-30 (per BCB Res. 519/520; Nov 6 alternative per Res. 589)

### Pillar 7: Identity ecosystem

(no new material in window. Note: Veridas + Fourthline merger announced July 16, 2026 — outside window; likely covered in July delta. Closing expected H2 2026 — monitor for completion announcement, which would be new material when it lands.)

---

## Upcoming watch items (next 7 days)

- **2026-10-30 (today, 17:00 CEST):** FATF President press conference — grey-list changes (Mexico/US mutual evaluation discussion). **Priority for Nov 3 delta.**
- **~2026-11-01:** CNBV Anexo 71 — verify whether all banks met the deadline or whether the CNBV issued an extension notice.
- **2026-11-01:** Turkiye age-token regulation takes effect.
- **~2026-11-06:** BCB VASP bank-counterparty ban alternate effective date per Res. 589 — verify against official BCB text.
- **2026-11-03:** AMLA central AML/CFT database RTS consultation closes.
- **2026-11-09:** Apple Cash reload ID check goes live (US).
- **2026-11-18:** EUDI ARF Iteration 6 closes.
- **2026-12-24:** EUDI wallet-availability deadline (55 days). 24/27 member states still tracking to miss it.
- **H2 2026 (TBC):** Veridas + Fourthline merger closing expected — monitor for announcement.
