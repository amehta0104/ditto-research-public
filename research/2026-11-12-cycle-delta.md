# Cycle Delta — 2026-11-12

Window: 2026-11-10 → 2026-11-12 (last 48 hours, Thursday)

## Provenance notes

- Worker (`ditto-slack-bot.dittobot.workers.dev`) blocked by egress proxy policy — consistent with all runs since at least 2026-10-22. Brand brief, pillar guides, and baseline not fetched. Deduplication performed against local GitHub copies of prior deltas (Nov 2–11).
- **Delta written to GitHub** (worker unavailable): `research/2026-11-12-cycle-delta.md`
- 17 web searches executed across all 7 pillars + 5 follow-up searches.
- **Watch-item follow-ups this run:**
  - KuppingerCole Access Management Leadership Compass (November 2026): Still not confirmed published as of this run. Research plan page still shows "Estimated publication: November 2026." Watch next cycle.
  - Future Identity Festival London (Nov 9–10): Post-event recaps not yet indexed. Watch next cycle for trade-press writeups.
  - 26th NextGen Payments & RegTech Forum, Austin (Nov 10): Event confirmed as November 10 at W Hotel Austin. Agenda included "Digital Identity & Wallets — Authentication, Passkeys and Tokenised Credentials" panel. No post-event speaker remarks or announcements found as of this run.
  - EUDI ARF Iteration 6 (closes Nov 18): Nothing published. Watch next cycle.
  - AMLA central AML/CFT database RTS: Public hearing concluded November 3; written comments deadline also November 3. No post-hearing summary or revised draft published as of this run.
- **Checked and rejected (outside window or already covered):**
  - DOJ $129M deepfake CEO indictment: covered in Nov 9 delta.
  - Veriff Presence Verification: covered in Nov 10 delta.
  - FINMA Circular 2016/7 (eff. Nov 1): covered in Nov 10 delta.
  - hashID wallet launch: covered in Nov 10 delta.
  - Israel draft national digital ID strategy (Nov 8): covered in Nov 10 delta.
  - Australia myID / Accenture AU$36.2M contract (Nov 10): covered in Nov 11 delta.
  - AMLA SDD sectoral roundtables (Nov 9–Dec 2): covered in Nov 11 delta.
  - FIDO 7B passkeys (Oct 30): outside window; noted in prior cycles.
  - DORA enforcement fines: no specific November 2026 fine confirmed in any source; general compliance commentary only.

---

## Override-worthy this cycle

1. **BioCatch: 80% of banks have already faced agentic AI attacks — nearly half occur at account opening, with no regulated identity layer for agents in the US** — BioCatch's 2026 agentic AI survey finds 80% of banks have already encountered agentic AI attacks; nearly half of the agentic interactions BioCatch detected occurred during account opening; fund transfers and beneficiary changes are the highest-risk moments. Meanwhile the CFPB's open-banking rule (the only US framework that would govern agent access to bank accounts) remains enjoined by a federal court, leaving no regulated route for AI agents into bank accounts. Biometric Update framed this on November 11 as "the identity layer nobody built." Account: / company. Angle: "80% of banks have already faced agentic AI attacks — mostly at account opening — and there's still no regulated identity standard for who (or what) is allowed in. The gap Ditto closes isn't theoretical."

---

## New findings

### Pillar 1: Banking & Payments

(no new material in window. AMLA central database RTS hearing concluded Nov 3 — no post-hearing summary published yet. PSD3/PSR ratification expected Nov–Dec 2026 per one law-firm note; no official OJEU publication confirmed as of this run.)

### Pillar 2: EUDI / eIDAS2

(no new material in window. EUDI ARF Iteration 6 closes November 18 — watch for updated ZKP/Digital Credentials API specification. Future Identity Festival London recaps not yet published.)

### Pillar 3: Fraud / Deepfakes

- **Digidentity survey: 80% of UK adults expect banks to catch deepfakes during selfie checks — 69% doubt their bank can** — Digidentity commissioned Censuswide to survey 1,000 UK adults (fielded early October 2026). Key findings: 80% expect their bank to detect AI-generated video deepfakes during selfie verification; 69% are not confident their bank can differentiate them from an impersonator; 81% say banks should be held responsible if their identity verification provider fails to stop fraud; 53% believe a text or email OTP is sufficient to prove identity; 62% will accept no more than two additional minutes of additional checks to reduce impersonation risk. The gap between consumer expectation (deepfake detection expected) and consumer practice (OTP accepted as sufficient) is the core tension the data surfaces. Covered by Biometric Update, The Paypers, SC World, CFO Tech, TechRadar.
  - Source: https://www.biometricupdate.com/202611/uk-consumers-expect-banks-to-answer-for-failed-identity-checks-digidentity-finds
  - Source: https://thepaypers.com/fraud-and-fincrime/news/digidentity-most-surveyed-uk-adults-unsure-banks-can-spot-imposters
  - Date: 2026-11-11 (IN WINDOW). Survey fielded October 2026.
  - Drafting caution: Digidentity is a commercial identity vendor with a direct interest in this finding. Stats are from their commissioned survey; treat as market-sentiment data, not independent research.

- **Sumsub + Jelou AI embed iBeta Level 3-certified liveness into WhatsApp onboarding for payments and remittances** — Sumsub and Jelou AI announced November 11 that they have integrated identity verification directly into WhatsApp-based financial-services onboarding. The AI agent in the chat triggers a Sumsub liveness check and decides the next step in the flow based on the result — no redirect away from the WhatsApp interface. Use cases cover cross-border remittance eligibility, money-transfer KYC, and digital-payment-platform onboarding. Sumsub's liveness detection passed iBeta Level 3 presentation attack detection testing. Technical options: Conversational (video selfie in chat), WebView (photo selfie), or WhatsApp Flows. Significance: first confirmed integration of an iBeta Level 3-certified liveness check inside a chat interface for live financial KYC flows; directly relevant to LATAM markets where WhatsApp dominates consumer financial interaction.
  - Source: https://idtechwire.com/sumsub-and-jelou-ai-to-put-identity-checks-inside-whatsapp-onboarding/
  - Source: https://fintech.global/2026/11/11/sumsub-and-jelou-ai-bring-id-checks-into-whatsapp/
  - Date: 2026-11-11 (IN WINDOW)
  - Drafting caution: No pricing, geographic availability, or technical integration details confirmed. No primary press release found — coverage is trade press only.

### Pillar 4: ZKPs in practice

(no new material in window. EUDI ARF Iteration 6 closes November 18 — expected to include updated ZKP/Digital Credentials API specification.)

### Pillar 5: Passwordless / split-key

(no new material in window. KuppingerCole Access Management Leadership Compass still not confirmed published — scheduled for November 2026, check kuppingercole.com/researchplan/leadership-compass-access-management-2026.)

### Pillar 6: LATAM

(no new primary-source material in window. Sumsub/Jelou WhatsApp integration above is directly LATAM-relevant — WhatsApp is the dominant messaging and financial-services channel in Brazil, Colombia, Mexico, and Peru. Drex Phase 2 report still not published. BCB VASP ban remains in force.)

### Pillar 7: Identity ecosystem

- **BioCatch: 80% of banks have already faced agentic AI attacks; regulatory void as CFPB rule enjoined** — Biometric Update published "AI agent identity takes shape across fraud detection and access controls" on November 11. The article synthesises BioCatch's 2026 agentic AI survey (80% of banks have encountered agentic AI attacks; nearly half of agentic sessions occurred at account opening; fund transfers and beneficiary changes are the highest-risk moments) with the unresolved US regulatory gap: the CFPB's Personal Financial Data Rights rule — the only framework that would create a regulated channel for AI agents into bank accounts — remains enjoined by a federal court (Eastern District of Kentucky), and as of August 2026 a revised proposal had not been published. Result: no regulated route exists for AI agents into bank accounts in the US. Governance frameworks do exist in Singapore (IMDA January 2026: agents must carry verifiable digital identities and audit trails) and NIST's AI Agent Standards Initiative (February 2026), but both are non-binding. ACAMS also published "Know your agent: Fraud's next frontier has no fingerprints," treating agentic identity as a formal AML/KYC gap. The Cloud Security Alliance notes that Regulation E's "unauthorized transfer" definition may leave agent misuse outside consumer protections, depending on how courts treat prompt-injection hijack of an agent.
  - Source: https://www.biometricupdate.com/202611/ai-agent-identity-takes-shape-across-fraud-detection-and-access-controls
  - Source: https://financemagnates.com/forex/80-of-banks-have-already-faced-agentic-ai-attacks-according-to-biocatch-survey
  - Source: https://www.acams.org/en/opinion/know-your-agent-frauds-next-frontier-has-no-fingerprints
  - Source: https://labs.cloudsecurityalliance.org/research/csa-research-note-banks-block-personal-ai-agents-20261102-cs/
  - Date: 2026-11-11 (IN WINDOW)

---

## Upcoming watch items (next 7 days)

- **2026-11-13+:** Future Identity Festival London (Nov 9–10) post-event recaps — check thefutureidentity.com and biometricupdate.com.
- **2026-11-13+:** 26th NextGen Payments & RegTech Forum (Nov 10, Austin) post-event writeups — check Biometric Update, Payments Dive.
- **2026-11-18 (Wed):** EUDI ARF Iteration 6 closes — expect updated specification covering Digital Credentials API, ZKP age-proof pathway; check eu-digital-identity-wallet/eudi-doc-architecture-and-reference-framework on GitHub.
- **November 2026 (ongoing):** KuppingerCole Access Management Leadership Compass — scheduled for November but not yet confirmed published. Check kuppingercole.com/researchplan/leadership-compass-access-management-2026.
- **2026-11-30:** Israel draft national digital ID strategy comment period closes — watch for banking-sector responses.
- **2026-12-01:** Australia myID opens to private-sector providers. First wave of approved providers to watch.
- **2026-12-02:** AMLA SDD roundtables conclude — formal public consultation on simplified CDD guidelines expected to follow.
- **2026-12-24:** EUDI wallet-availability deadline — 42 days. Germany confirmed Jan 2, 2027; multiple states still slipping.
- **~Days ahead:** AMLA central AML/CFT database RTS post-hearing summary — watch amla.europa.eu.
- **Q4 2026:** Vista Equity / HID PKI deal (Oct 16 announcement) expected to close — watch for closing announcement.
- **Ongoing:** BioCatch agentic AI survey follow-on coverage — watch for CFPB revised rule publication and Singapore IMDA framework adoption elsewhere.
