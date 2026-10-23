# Cycle Delta -- 2026-10-23

Window: 2026-10-20 -> 2026-10-23 (last 72 hours, Friday run, weekend coverage)

## Provenance notes

- Worker (ditto-slack-bot.dittobot.workers.dev) blocked by egress proxy policy (403 on CONNECT). Brand brief, pillar guides and baseline not fetched from the worker this run.
- Prior-delta deduplication performed by reading the two most recent GitHub deltas directly: 2026-10-21-cycle-delta.md and 2026-10-22-cycle-delta.md. Those cover 2026-10-18 through 2026-10-22 and are the basis for exclusions.
- World ID Suite for Banks (announced 2026-10-18 at Money20/20): covered in the 2026-10-21 cycle (referenced as "World AgentKit (10-18)" in context of agentic-trust category; Money20/20 announcements described as captured). Not re-logged.
- Fideuram / Intesa Sanpaolo AI fraud loss (~EUR 95m): event dated 2026-02-23. Outside window. Secondary reports surfaced in October but the incident itself is months old. Not counted.
- identifAI deepfake fraud report (USD 40B market size): published 2026-10-13. Outside window. Not counted.
- **Checked and rejected:**
  - Ondato + Trinsic EUDI wallet partnership (fintech.global, 2026-10-21): vendor product integration news. Same category as Hopae/d-you rejected in the 10-21 cycle. Not counted.
  - FIDO CMRA and Verifier Identification Framework: documents not yet published ("in coming weeks" per 10-20 announcement). Watch item carried forward.
  - EPC SCARLET, FIDO Authenticate 2026, Transmit Security Agentic Trust, Money20/20 / Biometrics Institute Congress outputs: all logged in 10-21 delta.
  - BCB virtual-asset unauthorized-provider ban (effective 2026-10-30): rule announced earlier; the 2026-10-30 effective date is a compliance trigger, not a new rule. Watch item.
  - No in-window material found for PSD3/PSR OJEU, EBA/ECB/DORA, AMLA, FATF plenary (starts 2026-10-26), FCA/PSR APP fraud, ZKPs, CNBV, Superfinanciera, CMF, SBS, or identity M&A/funding.

---

## Override-worthy this cycle

1. **Greek parliament passed the under-15 social media ban on 2026-10-22/23, imposing mandatory age verification on platforms with a 2027-01-01 enforcement date.** Account: / company. Angle: "The first EU member-state law that writes 'age verification' directly into the enforcement trigger -- not a regulator's guidance, an actual statute with fines. The identity layer just became a legal dependency for every platform targeting European users."

---

## New findings

### Pillar 1: Banking & Payments

(no new material in window.)

### Pillar 2: EUDI / eIDAS2

(no new material in window. EUDI Launchpad 2026, Brussels, starts 2026-10-29; expect ARF or readiness announcements next cycle.)

### Pillar 3: Fraud / Deepfakes

(no new material in window. World ID Suite for Banks covered in 10-21 cycle; Fideuram incident pre-dates window.)

### Pillar 4: ZKPs in practice

(no new material in window.)

### Pillar 5: Passwordless / split-key

(no new material in window. FIDO CMRA and Verifier Identification Framework publication pending.)

### Pillar 6: LATAM

- **Banco Central do Brasil published a press release on 2026-10-20 confirming that Normative Instruction BCB 766 and the updated DICT Operational Manual (v8.5) expand Pix functionality and improve transaction-security controls, with the MED 2.0 changes taking full effect on 2026-10-26.** The update raises the MED (Special Return Mechanism) response deadline from 30 to 80 days and introduces new fraud-flow information layers for infraction notifications. The BCB also confirmed active work to strengthen DICT (the Pix identifier database) access controls and AML/CFT risk mitigations tied to identity data.
  - Source: https://www.bcb.gov.br/en (press release 2026-10-20, "Regulatory updates expand Pix functionality and improve transaction security")
  - Supporting: https://ciberlatam.com/en/investigations/brazil-s-bcb-766-updates
  - Date: 2026-10-20
  - Drafting caution: primary BCB URL requires direct access for verbatim text; confirm exact wording before quoting. The 2026-10-26 MED 2.0 effective date has been stable across multiple prior deltas. Lead with the identity-data / DICT angle, not the payment-ops angle.

### Pillar 7: Identity ecosystem

- **Greek parliament passed Law on Age Verification for Social Media (vote 2026-10-22/23; effective 2027-01-01).** The law bans social media platform access for users under 15 and requires platforms (Facebook, TikTok, X, and any algorithm-driven content service) to implement "reliable age-verification mechanisms that comply with personal data protection requirements." Non-compliant platforms face financial penalties. The ruling New Democracy party supported it; PASOK abstained; remaining opposition parties voted against. Critics raised privacy and enforcement questions; the government framed it as child-safety legislation.
  - Source: https://greekreporter.com/2026/10/23/greece-children-under-15-social-media-ban/
  - Source: https://www.bta.bg/en/news/balkans/1230865-greece-approves-social-media-ban-for-children-under-15-from-2027
  - Source: https://en.tempo.co/read/2122209/greece-passes-social-media-ban-for-kids-under-15
  - Date: 2026-10-22 (vote); 2027-01-01 (effective)
  - Drafting caution: the law names no specific technical standard; "reliable age-verification mechanisms" is the full statutory phrase. The enforcement regime (which regulator, what penalty scale) is not confirmed in available sources. Distinguish from Australia's Online Safety Amendment (social media) which set a similar ban. Both converge on the same identity-infrastructure gap: platforms need a privacy-preserving age signal that does not require storing a birth certificate.

---

## Upcoming watch items (next 7 days)

- **2026-10-26:** BCB MED 2.0 / IN BCB 766 Pix changes take full effect. Check BCB for any implementation notices.
- **2026-10-26/30:** FATF plenary, Paris. Watch for guidance on AI, deepfakes, and digital identity.
- **2026-10-29/30:** EUDI Launchpad 2026, Brussels. High priority -- likely to produce EUDI ARF or readiness announcements.
- **2026-10-30:** BCB virtual-asset unauthorized-provider ban takes effect.
- **2026-10-31:** ECB SSM-2026-0301 action-plan deadline.
- **End-October:** Ofcom over-16 age-assurance rapid assessment; Romania EUDI sandbox target.
- **2026-11-01:** Turkiye age-token regulation takes effect.
- **2026-11-03:** AMLA central AML/CFT database RTS consultation closes.
- **Early November:** CNBV Anexo 71 biometric compliance deadline; BCB "Circuito Pix" session.
- **2026-11-09:** Apple Cash reload ID check goes live.
- **2026-11-18:** EUDI ARF Iteration 6 closes.
- **2026-12-24:** EUDI wallet-availability deadline (62 days).
