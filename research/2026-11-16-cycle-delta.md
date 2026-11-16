# Cycle Delta — 2026-11-16

Window: 2026-11-13 → 2026-11-16 (last 72 hours — Monday, covering weekend)

## Provenance notes

- Worker (`ditto-slack-bot.dittobot.workers.dev`) blocked by egress proxy policy — consistent with all runs since 2026-10-22. Brand brief, pillar guides, and baseline not fetched. Deduplication performed against local GitHub copies of prior deltas (Nov 2–13).
- **Delta written to GitHub** (worker unavailable): `research/2026-11-16-cycle-delta.md`
- 14 web searches + 4 follow-up searches executed across all 7 pillars.
- **Watch-item follow-ups this run:**
  - Future Identity Festival London (Nov 9–10): Post-event recaps still not indexed as of this run. No trade-press writeups found. Watch next cycle.
  - 26th NextGen Payments & RegTech Forum, Austin (Nov 10): No post-event announcements found. Watch next cycle.
  - KuppingerCole Access Management Leadership Compass (November 2026): Research plan lists status as "closed" for Nov 2026 target; an analyst chat references the report as "published the previous week" covering 28 vendors, but no confirmed publication date found. Likely published this week — watch for vendor press releases.
  - EUDI ARF Iteration 6 (closes Nov 18): Not yet closed/published. Topics confirmed: Digital Credentials API refinement (Topic F) and cryptographic binding of attestations (new Topic AC). Expect updated spec on or after Nov 18.
  - AMLA central AML/CFT database RTS post-hearing summary: Still not published on amla.europa.eu.
  - PSD3/PSR Official Journal publication: Final compromise texts endorsed April 2026; OJ publication still pending — sources give Q4 2026 as expected window, not confirmed.
- **Checked and rejected (outside window or already covered):**
  - Google Wallet ZKP on mDocs (~Oct 23): Outside window.
  - Australia myID opening Dec 1 (Nov 10–11 deltas): Already covered.
  - ECOWAS biometric ID January 2027 deadline (Nov 11): Outside Nov 13–16 window.
  - Pentagon enterprise identity modernization RFP (Nov 11): Outside this window.
  - KuppingerCole Lean Identity Governance Buyer's Compass (Nov 11): Outside window; not found in prior deltas but date precedes this window.
  - Sumsub fraud-trend blog (annual stats): Outside window; figures from prior periods, not November 2026 primary finding.

---

## Override-worthy this cycle

(none)

---

## New findings

### Pillar 1: Banking & Payments

(no new material in window. PSD3/PSR OJ publication still pending — law-firm notes give Q4 2026, unconfirmed. AMLA central database RTS post-hearing summary not published. No new EBA/FCA/PSR/ECB releases found Nov 13–16.)

### Pillar 2: EUDI / eIDAS2

- **WE BUILD consortium announces next phase of digital identity and EUDI business wallet pilots** — WE BUILD, the EU-funded large-scale pilot consortium for the EUDI Wallet, announced plans for the next year covering digital identity and business wallet pilots. No specific updated timeline or new technical specification details surfaced in this run; article is dated November 2026. Significance: signals continued EU institutional momentum on EUDI wallet deployment ahead of the December 24 member-state deadline.
  - Source: https://www.biometricupdate.com/202611/we-build-plans-next-year-of-digital-identity-business-wallet-pilots
  - Date: 2026-11 (Biometric Update, exact date not confirmed from search result; in window if Nov 13–16)
  - Drafting caution: Title references "next year" plans (2027); check article scope and avoid conflating with current member-state deadline.

### Pillar 3: Fraud / Deepfakes

- **Sumsub and Constructor University (Bremen) publish adversarial face-swap AI model for stress-testing biometric defenses** — Sumsub and Constructor University released research on a faster adversarial AI model designed to generate image-based face swaps, intended as a tool for testing liveness and presentation attack detection systems. The research specifically addresses image-swap attacks (distinct from live video injection attacks, which iProov tracks separately). Practical implication: identity vendors are now expected to benchmark against adversarial AI tools, not just legacy PAD test sets. Covered by Biometric Update November 13 (missed in Nov 13 delta).
  - Source: https://www.biometricupdate.com/202611/biometric-defenses-put-to-the-test-with-faster-ai-face-swap-model
  - Date: 2026-11-13 (in window for Monday pickup; not covered in Nov 13 delta)
  - Drafting caution: Check whether full paper is published or only a press release. Distinguish image-swap from video injection in any draft.

- **New UK address verification service targets AI-enabled identity fraud; Cifas: 59% of UK National Fraud Database cases are identity fraud in H1 2026** — A UK service was launched allowing businesses to verify whether customers can physically access the address provided during registration, targeting the growing gap where AI-generated credentials produce valid-seeming but fictitious addresses. The service launch was reported in Think Digital Partners' Digital Identity Global Roundup on November 16. Cited alongside Cifas H1 2026 figures: identity fraud now constitutes 59% of cases in the UK National Fraud Database.
  - Source: https://www.thinkdigitalpartners.com/news/2026/11/16/digital-identity-global-roundup-294/
  - Date: 2026-11-16 (in window)
  - Drafting caution: Provider name not confirmed from search result; primary source is Think Digital Partners weekly roundup. Verify provider before naming in a post.

### Pillar 4: ZKPs in practice

(no new material in window. EUDI ARF Iteration 6 closes Nov 18 — expect updated specification covering Digital Credentials API refinement and new Topic AC on cryptographic binding of attestations. That is the next expected ZKP/mDL signal.)

### Pillar 5: Passwordless / split-key

- **KuppingerCole Access Management Leadership Compass likely published — covers 28 vendors; passwordless and FIDO analysis included** — KuppingerCole's research plan shows report 80987 (Access Management, analyst Alejandro Leal) with a November 2026 target; plan status reads "closed." A KC analyst chat references the report as "published the previous week" covering 28 vendors. No vendor press release or KC library listing found as of this run to confirm the date. Classified here as highly probable this week — watch for vendor press releases (Ping Identity, Thales, CyberArk) for confirmation. If confirmed, this is the principal analyst benchmark for the access management market through H1 2027.
  - Source: https://www.kuppingercole.com/researchplan/leadership-compass-access-management-2026
  - Date: Expected November 2026 (target); **not yet confirmed published** as of this run
  - Drafting caution: Do not draft post citing this report until confirmed published. Use watch-item in next cycle to verify.

### Pillar 6: LATAM

(no new primary-source material in window. No Drex Phase 2 report, no new CNBV/Superfinanciera/CMF/SBS/BCB identity announcements found. Sumsub/Jelou WhatsApp integration (Nov 11 delta) remains most recent LATAM-relevant finding.)

### Pillar 7: Identity ecosystem

- **Singapore evaluates national AI agent domain registry to verify and track AI agent identities** — Singapore officials announced they are assessing whether the country's internet domain infrastructure could form the backbone of a national registry for AI agents, assigning verifiable identities and audit trails to agents operating across digital services. The proposal would extend Singapore's existing national digital identity infrastructure into an "agent identity layer." Covered by Biometric Update November 13 (missed in Nov 13 delta). Significance: follows Singapore IMDA's January 2026 requirement that AI agents carry verifiable digital identities; this is the next concrete step toward an enforcement mechanism.
  - Source: https://www.biometricupdate.com/202611/singapore-explores-internet-domain-system-to-identify-and-track-ai-agents
  - Date: 2026-11-13 (in window for Monday pickup; not covered in Nov 13 delta)
  - Note: Directly extends the agentic-AI identity thread from Nov 12 (BioCatch 80% survey + CFPB void). Singapore taking concrete infrastructure action while the US has no regulated route.

- **Facephi integrates identity verification and fraud detection into Egypt Trust's hosted e-signature platform** — Facephi, the Spanish biometric identity vendor, agreed to build its identity verification and fraud detection technology into Egypt Trust's locally hosted platform for electronic signatures and seals. The integration embeds biometric verification and fraud signals directly into the trust-services workflow.
  - Source: https://www.biometricupdate.com/202611/facephi-and-egypttrust-partner-on-digital-identity-and-fraud-prevention
  - Date: 2026-11 (Biometric Update; exact date not confirmed from search result, in window if Nov 13–16)
  - Drafting caution: Regional partnership (Spain/Egypt); primarily an ecosystem-consolidation signal rather than a tier-1 market event.

---

## Upcoming watch items (next 7 days)

- **2026-11-18 (Wed) ← HIGHEST PRIORITY:** EUDI ARF Iteration 6 closes — expect updated ARF spec covering Digital Credentials API (Topic F) and cryptographic binding of attestations (Topic AC); check https://github.com/eu-digital-identity-wallet/eudi-doc-architecture-and-reference-framework
- **2026-11-18 (Wed):** KuppingerCole Customer Identity & Access Management Impact Day, Hilton Frankfurt Airport — watch for analyst commentary on passwordless and EUDI wallet.
- **This week:** KuppingerCole Access Management Leadership Compass — confirm publication via vendor press releases or KC library listing.
- **This week:** Future Identity Festival London (Nov 9–10) post-event recaps — still not indexed; watch thefutureidentity.com and biometricupdate.com.
- **2026-11-30:** Israel draft national digital ID strategy comment period closes.
- **2026-12-01:** Australia myID opens to private-sector providers — first approved provider list expected.
- **2026-12-02:** AMLA SDD roundtables conclude — formal public consultation on simplified CDD guidelines expected to follow.
- **2026-12-24:** EUDI wallet-availability deadline — 38 days. Germany confirmed Jan 2, 2027; multiple states slipping.
- **~Days ahead:** AMLA central AML/CFT database RTS post-hearing summary — watch amla.europa.eu.
- **Q4 2026:** PSD3/PSR Official Journal publication — still expected before year-end.
- **Q4 2026:** Vista Equity / HID PKI deal expected to close.
