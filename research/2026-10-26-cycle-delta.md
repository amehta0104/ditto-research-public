# Cycle Delta — 2026-10-26

Window: 2026-10-23 → 2026-10-26 (last 72 hours, Monday run, weekend coverage)

## Provenance notes

- Worker (ditto-slack-bot.dittobot.workers.dev) blocked by egress proxy policy (403 on CONNECT). Brand brief, pillar guides and baseline not fetched from the worker this run. This is consistent with every run since at least 2026-10-22.
- Prior-delta deduplication performed by reading the two most recent GitHub deltas: 2026-10-22-cycle-delta.md and 2026-10-23-cycle-delta.md. Those cover 2026-10-20 through 2026-10-23 and are the basis for exclusions.
- Window is narrow (Fri close → Mon morning). No industry conferences ran; no major regulator publications fall on weekends. One genuine in-window finding identified.
- **Checked and rejected:**
  - Feedzai Fraud Readiness Index 2026 (Inc.com, Oct 23): **included** — the Oct 23 Friday delta did not capture it; it falls in window.
  - Germany Digital Identities Act / Bundestag vote (Oct 15): outside window; covered in earlier cycle delta.
  - FATF plenary outcomes: plenary sessions are Oct 28–30; no outcomes published as of Oct 26.
  - Socure $156M / Fravity acquisition (Aug 27): outside window.
  - Fideuram/Intesa AI voice fraud €95M (incident Feb 2026; Reuters wire ~Sept 26): outside window; flagged in prior deltas.
  - FIDO Passkey Index 2026 (Oct 15): outside window; covered in earlier cycle delta.
  - Ofcom over-16 age-assurance rapid assessment: committed by end of October 2026; not yet published as of Oct 26. Watch item.
  - BCB MED 2.0 / IN BCB 766 Pix effective Oct 26: effective date confirmed arrived; covered as LATAM finding + watch item in Oct 23 delta. No new BCB press release found. Not re-logged.
  - EUDI Launchpad Brussels (Oct 29–30): begins in 3 days; no pre-event announcement found in window.
  - CNBV, Superfinanciera, CMF, SBS, ZKPs, EBA/ECB, DORA, PSD3 OJEU: no in-window material found.

---

## Override-worthy this cycle

(none)

---

## New findings

### Pillar 1: Banking & Payments

(no new material in window.)

### Pillar 2: EUDI / eIDAS2

(no new material in window. EUDI Launchpad 2026, Brussels, runs 2026-10-29/30 — expect ARF updates, member-state readiness announcements, and cross-border use-case outputs in the next delta.)

### Pillar 3: Fraud / Deepfakes

- **Feedzai's Fraud Readiness Index 2026 found that 96% of banks and fintechs plan to increase AI fraud-detection budgets over the next two years, while 9 in 10 want cross-industry collaboration on fraud risk — yet the survey also found widespread gaps between declared intent and deployed capability.** The Index, based on responses from institutions globally, frames AI-powered fraud (including deepfake impersonation and synthetic-ID attacks) as the primary driver of budget pressure. A separate FedScoop piece published the same day quotes US Treasury officials describing the current environment as making it "easier than ever to spin up fake identities."
  - Source: https://www.inc.com/ray-fernandez/banks-fraud-feedzai-socure-capabilities-score/91424621
  - Supporting: https://fedscoop.com/financial-agencies-fighting-fraud-treasury
  - Date: 2026-10-23
  - Drafting caution: the Inc. piece is secondary; verify the specific figures against Feedzai's own report before quoting. The FedScoop quote is useful colour but is an official's spoken remark, not a published guidance document.

### Pillar 4: ZKPs in practice

(no new material in window.)

### Pillar 5: Passwordless / split-key

(no new material in window. FIDO CMRA and Verifier Identification Framework publication still pending.)

### Pillar 6: LATAM

(no new material in window. BCB MED 2.0 effective date (2026-10-26) arrived; covered in Oct 23 delta. No new BCB press release confirming implementation status found via search.)

### Pillar 7: Identity ecosystem

(no new material in window.)

---

## Upcoming watch items (next 7 days)

- **2026-10-26 (today):** FATF Week opens in Paris. Plenary sessions run 2026-10-28/30 under UK President Giles Thomson. Agenda includes: progress on the FATF Fraud Roadmap (launched July 2026, evidence-gathering phase closes this month), mutual evaluation reports for Mexico and the US, and the first FSRB Guest Initiative countries (Barbados, Namibia, Thailand). Communiqué and press conference expected Friday Oct 30. Watch for any mention of digital identity, deepfakes, or AI in the fraud context.
- **2026-10-26 (today):** BCB MED 2.0 / IN BCB 766 Pix changes effective. Monitor BCB site for implementation notices.
- **2026-10-29/30:** EUDI Launchpad 2026, Brussels (The Egg). Second edition; invitation-only. Focus: national wallet implementations, cross-border use cases, joint credential development. High probability of ARF or readiness announcements. **Priority for next delta.**
- **2026-10-30:** BCB virtual-asset unauthorized-provider ban takes effect.
- **2026-10-31:** ECB SSM-2026-0301 action-plan deadline.
- **End-October:** Ofcom over-16 highly-effective age-assurance rapid assessment due to Parliament (confirmed commitment; not yet published as of Oct 26). **Priority for next delta.**
- **2026-11-01:** Turkiye age-token regulation takes effect.
- **2026-11-03:** AMLA central AML/CFT database RTS consultation closes.
- **Early November:** CNBV Anexo 71 biometric compliance deadline.
- **2026-11-09:** Apple Cash reload ID check goes live.
- **2026-11-18:** EUDI ARF Iteration 6 closes.
- **2026-12-24:** EUDI wallet-availability deadline (59 days).
