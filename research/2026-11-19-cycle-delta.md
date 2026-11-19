# Cycle Delta — 2026-11-19

Window: 2026-11-17 → 2026-11-19 (last 48 hours — Thursday)

## Provenance notes

- Worker (`ditto-slack-bot.dittobot.workers.dev`) blocked by egress proxy policy — consistent with all runs since 2026-10-22. Brand brief, pillar guides, and baseline not fetched. Deduplication performed against local GitHub copies of prior deltas (Nov 2–18).
- **Delta written to GitHub** (worker unavailable): `research/2026-11-19-cycle-delta.md`
- 11 web searches + 3 follow-up searches executed across all 7 pillars.
- **Watch-item follow-ups this run:**
  - EUDI ARF Iteration 6 (closed Nov 18): Still no release indexed on GitHub as of this run. Latest tagged release remains v3.0.0 (July 21, 2026). Expected content: Digital Credentials API (Topic F) and cryptographic binding of attestations (new Topic AC). Watch tomorrow's run.
  - KuppingerCole CIAM Impact Day Frankfurt (Nov 18): Event confirmed occurred; no post-event recap indexed as of this run. Watch for analyst commentary.
  - KuppingerCole Access Management Leadership Compass: Still not confirmed published as of this run.
  - Future Identity Festival London (Nov 9–10): Post-event recaps still not indexed. Watch next cycle.
  - AMLA central AML/CFT database RTS post-hearing summary: Hearing was Nov 3; summary still not published on amla.europa.eu.
  - PSD3/PSR OJ publication: Parliament's second reading is now the final remaining step — see Pillar 1 finding below.

- **Checked and rejected (outside window or already covered):**
  - Entrust 2027 Identity Fraud Report (Nov 17): Covered in Nov 18 delta.
  - IDC MarketScape Augmented Identity Security 2026 (Nov 2026): Covered in Nov 18 delta.
  - IBM–AuthMind acquisition (Nov 12): Outside window; not in prior deltas — recommend drafter flag for catch-up.
  - IDC MarketScape names IBM Leader in Worldwide Digital Identity Services (Nov 10): Outside window.
  - Germany d-you wallet name/branding (Sept 2026): Already noted in prior cycles. The Jan 2 2027 launch date has been in watch items since prior cycles. The new Nov 18 finding is youniqx confirming it won the tender to supply d-you's digital infrastructure — see Pillar 2.

---

## Override-worthy this cycle

1. **Poland cabinet adopts EUDI wallet implementation bill — pilot in December 2026, 37 days before EU deadline** — Poland's Council of Ministers adopted the draft trust-services amendment on Nov 17. With Dec 24 five weeks away, every major EU member state is now formally in motion. Account: / company. Angle: "35 days to the EUDI wallet deadline — Poland just moved. Every major EU economy is now formally in motion. What does Dec 24 actually mean for relying parties who haven't started integration?"

---

## New findings

### Pillar 1: Banking & Payments

- **PSD3/PSR: Parliament has committed to adopt at second reading without amendment — OJ publication now in final stretch** — A November 19 Linklaters briefing confirms the Council adopted its first-reading position on 28 October 2026. The European Commission communicated to Parliament on 3 November that it can accept the Council's position. ECON's committee chair confirmed Parliament will adopt the text at second reading without amendment, making a formal plenary vote the only remaining step before Official Journal publication. Entry into force: 20 days after OJ publication. PSR applies 21 months after entry into force; PSD3 must be transposed in the same 21-month window. For identity vendors: verification-of-payee obligations, liability rules extending to third-party providers, and open banking re-authorisation requirements become legally enforceable on that PSR application date. The PSD3/PSR watch item moves from "pending publication" to "pending Parliament vote."
  - Source: https://financialregulation.linklaters.com/post/102mei6/payments-in-2026-3-psd3
  - Date: 2026-11-19 (article); underlying events Oct 28 (Council) / Nov 3 (Commission communication)
  - Drafting caution: Parliament's second-reading date not yet confirmed — could be weeks or one to two months away. Do not frame as "PSD3 passed" — it has not entered into force.

### Pillar 2: EUDI / eIDAS2

- **Poland cabinet adopts EUDI wallet bill tied to mObywatel — pilot December 2026** — Poland's Council of Ministers adopted a draft amendment to the act on trust services and electronic identification on 2026-11-17. The bill integrates the EUDI wallet into mObywatel, Poland's existing government app used by ~38 million citizens. A pilot is planned for December 2026, with permanent integration after pilot review. PM Tusk noted cross-border use depends on other member states also adopting the wallet. The EU deadline (at least one wallet available to every citizen) is 24 December 2026, now 37 days from adoption. Poland is Europe's fifth-largest economy; this confirms that the dominant EUDI deployment pattern is wallet-as-extension of existing national digital government apps (mObywatel in Poland, France Identité in France, Bundesdruckerei/youniqx infrastructure in Germany).
  - Source: https://www.intellinews.com/poland-to-link-eu-digital-identity-wallet-with-mobywatel-app-486248
  - Source: https://ceo.com.pl/en/poland-eu-digital-identity-wallet-mobywatel-2026/
  - Source: https://idtechwire.com/id-tech-digest-november-17-2026/
  - Date: 2026-11-17 (confirmed from multiple sources)
  - Drafting caution: Bill is a draft amendment — still needs parliamentary passage in Poland. December pilot may slip depending on parliamentary calendar. Cross-border use explicitly noted as dependent on other member states' readiness.

- **youniqx Identity launches public EUDI Wallet sandbox — confirms it built Germany's d-you wallet infrastructure** — youniqx Identity, the digital identity arm of Austria's state printing company (Oesterreichische Staatsdruckerei), launched a fully public EUDI Wallet sandbox and developer playground at playground.youniqx.com on 2026-11-18. The relaunch includes MIA ("My Identity App"), a test wallet that runs on-device, stores and presents EUDI-spec credentials, and allows developers to test relying-party scenarios (hotel check-in, age verification, SIM card registration, cross-border travel) using pre-built fictional personas, with no personal data required. iOS available now; Android to follow. The announcement also confirmed that youniqx won the international tender to supply the digital infrastructure behind Germany's d-you EUDI wallet, which is scheduled to launch January 2, 2027 with ~40 partners. For relying parties: youniqx's sandbox is now the most openly accessible EUDI conformance test environment for vendors without large enterprise pilot access.
  - Source: https://www.globenewswire.com/news-release/2026/11/18/3405399/0/en/youniqx-identity-launches-fully-public-eudi-sandbox.html
  - Source: https://idtechwire.com/youniqx-identity-opens-public-eudi-wallet-sandbox-and-relaunches-mia-as-a-test-wallet/
  - Date: 2026-11-18 (confirmed)

### Pillar 3: Fraud / Deepfakes

(no new material in window. No iProov/Sumsub/Veriff/Onfido report released Nov 17–19. John Erik Setsaas KuppingerCole CIAM Impact Day preview — "1 in 5 Norwegians used someone else's BankID" — is a compelling angle but is a pre-event speaker preview, not a published report. Watch for post-event content and primary source.)

### Pillar 4: ZKPs in practice

(no new material in window. EUDI ARF Iteration 6 (expected to cover Digital Credentials API and cryptographic binding) still not released. No OpenID4VP or mDL deployment announcement found Nov 17–19.)

### Pillar 5: Passwordless / split-key

(no new confirmed material in window. KuppingerCole Access Management Leadership Compass still not confirmed published as of this run.)

### Pillar 6: LATAM

(no new primary-source material in window. No Drex Phase 2, CNBV, Superfinanciera, CMF, SBS, or BCB identity announcements found Nov 17–19. Prior most-recent LATAM finding: Sumsub/Jelou WhatsApp integration (Nov 11 delta).)

### Pillar 7: Identity ecosystem

- **Publicis Sapient + Ping Identity announce global partnership to modernise enterprise identity for AI adoption** — Publicis Sapient (global digital transformation integrator) and Ping Identity announced a global partnership on 2026-11-19 to help organisations upgrade legacy identity and access management systems for AI-era adoption. The partnership targets enterprises running infrastructure that cannot handle AI agent access patterns, agentic workflows, or machine-to-machine identity. For the identity market: a large systems integrator explicitly pairing with an IAM vendor to position identity modernisation as a precondition for AI deployment is a new commercial motion — it validates the "AI forces identity rearchitecture" narrative that analyst firms (Gartner, IDC) have been building in 2026.
  - Source: https://consultancy.uk/news/amp/46258/publicis-sapient-and-ping-identity-partner-to-upgrade-identity-identity-systems-for-ai
  - Date: 2026-11-19 (confirmed)
  - Drafting caution: Partnership announcement is marketing — no named customer or project dollar amount. Use as ecosystem-signal post ("SIs are now leading with identity modernisation as an AI precondition") rather than a product news post.

---

## Upcoming watch items (next 7 days)

- **HIGHEST PRIORITY — EUDI ARF Iteration 6:** Still not released. Check https://github.com/eu-digital-identity-wallet/eudi-doc-architecture-and-reference-framework/releases daily. Expected content: Digital Credentials API (Topic F), cryptographic binding of attestations (Topic AC).
- **This week:** KuppingerCole CIAM Impact Day Frankfurt (Nov 18) post-event writeups — passkeys in production, deepfake-resistant identity, EUDI wallet. Watch kuppingercole.com/blog and #CIAMID2026.
- **This week:** KuppingerCole Access Management Leadership Compass — still not confirmed published. Watch for Ping Identity, Thales, CyberArk, Okta vendor press releases.
- **~Days ahead:** AMLA central AML/CFT database RTS post-hearing summary — watch amla.europa.eu.
- **Weeks ahead:** PSD3/PSR Parliament second-reading vote — now the last formal step before OJ publication.
- **2026-11-30:** Israel draft national digital ID strategy comment period closes.
- **2026-12-01:** Australia myID opens to private-sector providers — first approved provider list expected.
- **2026-12-02:** AMLA SDD roundtables conclude.
- **2026-12-24:** EUDI wallet-availability deadline — 35 days. Germany confirmed Jan 2 (d-you/youniqx); Poland pilot December; multiple other member states still slipping.
- **Q4 2026:** PSD3/PSR OJ publication — Parliament second reading now the remaining step.
- **Q4 2026:** Vista Equity / HID PKI deal expected to close.
- **Drafter actions:**
  - FBI FaceStealer $400M deepfake crypto-theft (Nov 12) — still not posted. Recommend catch-up Pillar 3 post.
  - IBM–AuthMind acquisition (Nov 12) — outside current window, not in prior deltas. Recommend drafter flag: IBM acquiring identity security company AuthMind to extend governance over human, machine, and AI agent credentials. Source: idtechwire.com/id-tech-digest-november-12-2026
  - John Erik Setsaas (eID misuse, BankID sharing) — compelling stat in CIAM Impact Day preview: "1 in 5 Norwegians used someone else's BankID." If confirmed in post-event content, strong Pillar 2 or company-POV angle on eID-sharing as the unaddressed fraud vector.

---

## Summary

- **Findings by pillar:** Banking & Payments: 1 | EUDI/eIDAS2: 2 | Fraud: 0 | ZKP: 0 | Passwordless: 0 | LATAM: 0 | Identity ecosystem: 1 | Total: 4
- **Override-worthy:** Poland cabinet adopts EUDI wallet bill (Nov 17); "35 days to deadline — every major EU economy now formally in motion"
- **Delta path:** `research/2026-11-19-cycle-delta.md`
