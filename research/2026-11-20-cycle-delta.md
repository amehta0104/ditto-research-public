# Cycle Delta — 2026-11-20

Window: 2026-11-17 → 2026-11-20 (last 72 hours — Friday, covering Mon–Fri)

## Provenance notes

- Worker (`ditto-slack-bot.dittobot.workers.dev`) blocked by egress proxy policy — consistent with all runs since 2026-10-22. Brand brief, pillar guides, and baseline not fetched. Deduplication performed against local GitHub copies of prior deltas (Nov 2–19).
- **Delta written to GitHub** (worker unavailable): `research/2026-11-20-cycle-delta.md`
- 12 web searches executed across all 7 pillars.
- **Watch-item follow-ups this run:**
  - EUDI ARF Iteration 6 (closed 2026-11-18): Still no release indexed as of this run. Plan noted iteration 6 running Sep 23 – Nov 18, covering Digital Credentials API refinement. Latest tagged release on GitHub remains v3.0.0 (July 2026). Watch Monday.
  - KuppingerCole CIAM Impact Day Frankfurt (Nov 18): No post-event recap indexed two days after the event. Watch Monday.
  - KuppingerCole Access Management Leadership Compass (November 2026 target): Still not confirmed published. Alejandro Leal listed as author; planned scope includes Machine and Non-Human Identity Access and AI Readiness. Watch next cycle.
  - AMLA central AML/CFT database RTS post-hearing summary: Hearing was Nov 3; summary still not on amla.europa.eu. Watch carries forward.
  - PSD3/PSR Parliament second-reading vote: Now the final step before OJ publication per Nov 19 delta. Date not yet confirmed.
  - Australia myID private-sector opening (Dec 1): 11 days away. No early announcement found.

- **Checked and rejected:**
  - PSD3/PSR Parliament second-reading news (Nov 19): Covered in Nov 19 delta.
  - Poland EUDI wallet bill (Nov 17): Covered in Nov 19 delta.
  - youniqx EUDI sandbox / d-you confirmation (Nov 18): Covered in Nov 19 delta.
  - Entrust 2027 Identity Fraud Report (Nov 17): Covered in Nov 18 delta.
  - IDC MarketScape Augmented Identity Security (Nov 2026): Covered in Nov 18 delta.
  - Publicis Sapient + Ping Identity partnership (Nov 19): Covered in Nov 19 delta.
  - IBM / AuthMind acquisition (Nov 12): Outside window; noted in Nov 19 delta.
  - HID / inepro ID, MACO / ekey, Metalenz / PxE Imaging: All Nov 4–11, outside window.
  - USCIS IBIS $100M procurement: US federal contracting, not on-pillar for Ditto.
  - Deepfake $129M bank fraud federal indictment (unsealed Nov 5): Outside window.
  - Helix $6.2M pre-seed (voice verification): Outside window.

---

## Override-worthy this cycle

1. **Sumsub: 53% of businesses already hit by AI-agent fraud — but only 1 in 8 can revoke an agent's access** — Sumsub's Identity Fraud Report 2026-2027 (Nov 17) surfaces a new enterprise gap: agentic AI as an open fraud vector most companies cannot control. Account: / / company. Angle: "Over half of businesses are already dealing with AI-agent fraud. Only 12% can suspend an agent's access. Verification is solved — governance of what agents do next is not."

---

## New findings

### Pillar 1: Banking & Payments

(no new material in window beyond Nov 19 delta. PSD3/PSR, DORA, AMLA: all carry-forward watch items. No new EBA report, ECB SREP, or FCA/PSR ruling found Nov 17–20.)

### Pillar 2: EUDI / eIDAS2

(no new material in window. EUDI ARF Iteration 6 still not released two days after the Nov 18 close. Denmark, Germany, Poland, France remain the leading deployment signals — all covered in prior deltas. No new member-state announcement or ENISA certification update found Nov 17–20.)

### Pillar 3: Fraud / Deepfakes

- **Sumsub Identity Fraud Report 2026-2027: AI-agent fraud now affects 53% of businesses; only 12% can revoke agent access as overall fraud rate falls** — Sumsub's annual Identity Fraud Report (released 2026-11-17), based on 5.8 million fraud samples from its verification platform and surveys of 1,400 fraud/risk professionals and 1,500 consumers across 21 markets, finds a structural shift: overall identity fraud rate fell 28% YoY to 1.6% (down from 2.2% in 2025), while deepfake attacks rose 31% globally and 41% in Europe. The standout new finding: 53% of businesses report fraud involving AI agents, yet only 12% can suspend or revoke an agent's access, and 74% miss network-level fraud signals entirely. The report introduces a Fraud Complexity Index tracking manipulation techniques, automation, and coordinated network activity. The US was identified as home to the largest detected single-country fraud network. Framing: fraud reduction at the perimeter is masking an unsolved interior problem — agentic access governance — that most enterprises have not addressed.
  - Source: https://sumsub.com/identity-fraud-report-2026/
  - Source (US release): https://www.prnewswire.com/news-releases/sumsub-identity-fraud-report-us-has-worlds-largest-fraud-network-detected-as-ai-agents-open-new-gaps-302941475.html
  - Source (Europe release): https://www.prnewswire.co.uk/news-releases/europe-records-the-worlds-highest-deepfake-fraud-rate-as-ai-agents-and-cross-border-networks-rise-302941828.html
  - Source (trade coverage): https://www.biometricupdate.com/202611/sumsub-finds-deepfake-attacks-rising-as-identity-fraud-declines-in-europe
  - Date: 2026-11-17 (confirmed from PR Newswire and Biometric Update 202611 URL)
  - Drafting caution: Stats are from Sumsub's own platform data — not market-wide. The 53% AI-agent fraud figure comes from the Fraud Exposure Survey component, not verification traffic. Cross-check with Entrust's Nov 17 injection-attack data for corroboration (two independent vendors, same week, converging on AI-driven fraud). The 2026-2027 naming convention refers to the report covering 2025–2026 data with a forward-looking frame.
  - **Catch note:** This report was published Nov 17 and was searched for in both the Nov 18 and Nov 19 runs but not found. Surfaced in this run via extended search. Recommend drafter treat as fresh — it was not in prior cycle posts.

### Pillar 4: ZKPs in practice

(no new material in window. EUDI ARF Iteration 6, expected to cover Digital Credentials API and cryptographic binding of attestations, still not released. No OpenID4VP or mDL deployment announcement found Nov 17–20.)

### Pillar 5: Passwordless / split-key

- **IPQS: passkeys stop credential theft but 66% of passkey systems allow silent re-enrollment — recovery flows are the new attack surface** — IPQS published a security advisory on 2026-11-19 arguing that passkeys alone cannot prevent account takeover. The key citation is a USENIX Security 2026 audit finding that 66% of passkey-supporting services allowed new passkey registration without additional confirmation from the account holder, leaving recovery and re-enrollment as exploitable paths. IPQS's framing: passkey adoption removes password-based credential stuffing but shifts the ATO vector to enrollment and recovery — areas where most implementations currently have no step-up. For identity vendors: reinforces the "passkeys + continuous identity assurance" message over "passkeys = problem solved."
  - Source: https://www.globenewswire.com/news-release/2026/11/19/3406645/0/en/ipqs-warns-passkeys-alone-cannot-prevent-account-takeover-and-payment-fraud.html
  - Date: 2026-11-19 (confirmed from GlobeNewswire URL and date)
  - Drafting caution: IPQS is a fraud-detection vendor with a commercial interest in positioning passkeys as incomplete. The USENIX 2026 audit citation should be treated as directional until the primary paper is verified. FIDO Alliance has previously acknowledged re-enrollment as a known risk and published guidance on it; check FIDO's response before drafting a post that frames passkeys as broken.

### Pillar 6: LATAM

(no new primary-source material in window. No Drex Phase 2 report, no CNBV/Superfinanciera/CMF/SBS/BCB identity announcements found Nov 17–20. Prior most-recent LATAM finding: Sumsub/Jelou WhatsApp integration (Nov 11 delta).)

### Pillar 7: Identity ecosystem

- **Trulioo + Bureau partnership: device intelligence and behavioral biometrics join Trulioo's orchestration layer** — Trulioo announced a go-to-market partnership with Bureau (device intelligence, behavioral biometrics, and account intelligence) on 2026-11-17, adding Bureau's signals to Trulioo's global identity verification orchestration platform. The pairing addresses the gap between point-in-time document verification and continuous session-aware fraud signals — the same gap the Entrust and Sumsub reports this week identify as the primary open problem. For the identity market: this is the third major identity-vendor pairing in November to signal that standalone document/biometric verification is no longer sufficient; vendors are now leading with layered-signal architectures.
  - Source: idtechwire.com/id-tech-digest-november-17-2026/
  - Date: 2026-11-17 (IDTechWire digest; original announcement not separately confirmed)
  - Drafting caution: Partnership announcement is marketing. Confirm Trulioo primary release before citing in a post.

---

## Upcoming watch items (next 7 days)

- **HIGHEST PRIORITY — EUDI ARF Iteration 6:** Still not released 2 days after close. Check https://github.com/eu-digital-identity-wallet/eudi-doc-architecture-and-reference-framework/releases Monday.
- **This week:** KuppingerCole CIAM Impact Day Frankfurt (Nov 18) post-event writeups — passkeys in production, deepfake-resistant identity, EUDI wallet. Watch kuppingercole.com/blog and #CIAMID2026.
- **This week:** KuppingerCole Access Management Leadership Compass — still not confirmed published (November 2026 target). Watch for Ping Identity, Thales, CyberArk, Okta vendor press releases citing placement.
- **~Days ahead:** AMLA central AML/CFT database RTS post-hearing summary — watch amla.europa.eu.
- **Weeks ahead:** PSD3/PSR Parliament second-reading vote — now the last formal step before OJ publication.
- **2026-11-30:** Israel draft national digital ID strategy comment period closes.
- **2026-12-01:** Australia myID opens to private-sector providers — 11 days out.
- **2026-12-02:** AMLA SDD roundtables conclude.
- **2026-12-24:** EUDI wallet-availability deadline — 34 days. Germany confirmed Jan 2 (d-you/youniqx); Poland pilot December; multiple member states slipping.
- **Q4 2026:** PSD3/PSR OJ publication — Parliament vote now the remaining step.
- **Q4 2026:** Vista Equity / HID PKI deal expected to close.
- **Drafter backlog:**
  - FBI FaceStealer $400M deepfake crypto-theft (Nov 12) — still not posted. Recommend catch-up Pillar 3.
  - IBM–AuthMind acquisition (Nov 12) — not in any prior delta post; recommend catch-up Pillar 7.
  - John Erik Setsaas "1 in 5 Norwegians used someone else's BankID" — await KuppingerCole CIAM Impact Day post-event recap for confirmable quote.

---

## Summary

- **Findings by pillar:** Banking & Payments: 0 | EUDI/eIDAS2: 0 | Fraud/Deepfakes: 1 | ZKP: 0 | Passwordless: 1 | LATAM: 0 | Identity ecosystem: 1 | Total: 3
- **Override-worthy:** Sumsub AI-agent fraud governance gap (53% hit, 12% can revoke) — Pillar 3 / company angle
- **Delta path:** `research/2026-11-20-cycle-delta.md`
