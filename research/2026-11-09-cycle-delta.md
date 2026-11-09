# Cycle Delta — 2026-11-09

Window: 2026-11-06 → 2026-11-09 (last 72 hours — Mon covering weekend)

## Provenance notes

- Worker (`ditto-slack-bot.dittobot.workers.dev`) blocked by egress proxy policy — consistent with all runs since at least 2026-10-22. Baseline and brand brief not fetched. Deduplication performed against local GitHub copies of prior deltas (Nov 2–6).
- **Delta written to GitHub** (worker unavailable): `research/2026-11-09-cycle-delta.md`
- 12 web searches executed across 7 pillars + 5 follow-up searches.
- **Watch-item follow-ups this run:**
  - Apple Cash ID check (Nov 9): **CONFIRMED LIVE TODAY.** Apple Cash now requires identity verification for every reload starting November 9; iOS 27 enables the "Continue with ID in Wallet" pathway using government-issued mDL credentials. See Pillar 5 below.
  - KuppingerCole Access Management Leadership Compass (scheduled Nov 9): Not found as published as of this run. Watch for next cycle.
  - BCB VASP bank-counterparty ban (Nov 6): Previously confirmed effective. No new enforcement orders or authorization notices found this window.
  - AMLA central AML/CFT database RTS: No post-hearing summary published.
  - EUDI ARF Iteration 6: Closes Nov 18; nothing published.
- **Checked and rejected (outside window or already covered):**
  - Kosovo wallet launch (Nov early): Covered in Nov 6 delta.
  - Fideuram/Intesa Sanpaolo €95M deepfake fraud: September 2026 — outside window, already in prior cycles.
  - FIDO 7 billion passkeys (October 2026): Outside window; covered in prior deltas.
  - Germany d-you wallet launch (Jan 2, 2027): Announced Sept 9, 2026 — outside window; previously covered.
  - WE BUILD general EUDI context: Background only; Nov 6 specific roadmap article is new (included below).
  - UK Digital Identity Sectoral Analysis 2026: July 2026 publication — outside window.
  - PSD3/PSR formal adoption: December 2026 expected; no new development in window.

---

## Override-worthy this cycle

1. **DOJ unseals $129M AI deepfake CEO fraud indictment against three foreign nationals** — Three defendants charged Nov 5 with wire fraud + aggravated identity theft for using AI-cloned CEO voices and video to defraud companies globally; named victims include a Rhode Island bank, two hospital systems and a UK fintech. First US federal prosecution explicitly charging both CEO and lawyer identity theft via generative AI. Account: company / /. Angle: "The FBI case that rewrites every bank's fraud response playbook — and the identity stack that could have stopped it."

---

## New findings

### Pillar 1: Banking & Payments

- **DOJ deepfake indictment names a Rhode Island bank as a named victim** — The $129M AI fraud case (see Pillar 3) includes a RI-headquartered bank as a named victim; wire transfer authorised via AI-voice CEO impersonation. This is the first US federal prosecution in which a regulated bank is a named victim of AI-generated executive impersonation. Signals that AI-voice fraud against banks is now a DOJ priority, not just a cyber-insurance problem.
  - Source: https://abcnews.com/Technology/wireStory/3-charged-scheme-ai-impersonate-ceos-attorneys-steal-137899167
  - Date: 2026-11-05 (indictment); reported 2026-11-06–08

### Pillar 2: EUDI / eIDAS2

- **WE BUILD consortium confirms 2027 digital identity and business wallet pilots are on schedule; testbed ready** — Announced November 6. WE BUILD (180+ organisations across 27 EU countries) published its next-year roadmap; testbed environment is now live. KuppingerCole speaker projects Q3 2027 for first live business wallets. Business wallet regulation expected to be finalised and published late 2026, with implementing acts to follow during the pilot window. Mandatory acceptance for banking by end-2027 confirmed.
  - Source: https://www.biometricupdate.com/202611/we-build-plans-next-year-of-digital-identity-business-wallet-pilots
  - Date: 2026-11-06

### Pillar 3: Fraud / Deepfakes

- **DOJ indicts three in $129M AI CEO voice-clone fraud ring targeting companies worldwide** — Jacob Soall (Spain/UK), Sharon Hazan (Israel), and Guy Sheetrit (Israel/UAE) charged in SDNY on seven counts: conspiracy to commit wire fraud, wire fraud, two counts of aggravated identity theft, three counts of money laundering. Method: spear-phishing email purporting to be from the CEO, then a follow-up call using AI-cloned CEO voice and in some cases AI video, to authorize wire transfers. Victims include: Missouri hospital system ($4.9M), California hospital system ($3M), Rhode Island bank, UK fintech, Massachusetts mutual fund. Max sentence 20 years on fraud counts. First US federal prosecution explicitly charging both CEO and lawyer identity theft using generative AI tools.
  - Source: https://www.biometricupdate.com/202611/deepfake-ceos-stolen-lawyer-identities-fuel-alleged-129m-fraud; https://abcnews.com/Technology/wireStory/3-charged-scheme-ai-impersonate-ceos-attorneys-steal-137899167; https://www.cbsnews.com/news/3-ai-steal-129-million-companies-impersonating-executives-lawyers/
  - Date: 2026-11-05 (indictment unsealed); reported widely 2026-11-06–08

### Pillar 4: ZKPs in practice

(no new material in window)

### Pillar 5: Passwordless / split-key

- **Apple Cash now requires identity verification for every reload effective November 9; iOS 27 enables government mDL as the KYC pathway** — Apple Cash now mandates ID verification before any balance reload, effective today. Under iOS 27, users can tap "Continue with ID in Wallet" to satisfy the check using a state-issued driver's license or ID stored in Apple Wallet. This is the first time a major US consumer payments platform has made government-issued mobile credentials (mDL) a standard KYC pathway rather than a fallback. Significance: government mDL is now a production KYC instrument for 100M+ Apple Cash users; sets a precedent for EU regulated entities considering EUDI wallet-based ID as a KYC input.
  - Source: https://iphonewired.com/news/1200054/; https://idtechwire.com/apple-cash-to-require-identity-verification-before-balance-reloads/
  - Date: 2026-11-09 (effective today)

### Pillar 6: LATAM

(no new material in window)

### Pillar 7: Identity ecosystem

- **Cloudflare + Tools for Humanity propose "Trusted Agent Delegation" (TAD) framework for AI agent identity** — Published November 5; covered November 8. The proposal defines four tiers of AI-agent identity verification: Nothing → Session → Account → Unique, with World ID (iris-based proof-of-human, 15M+ enrolled) as the top-tier option. Cloudflare's preferred authentication method is Web Bot Auth (cryptographic request signing). A working group of agent builders, KYC providers and payment providers is forming. This frames identity infrastructure as the control plane for agentic commerce — directly adjacent to Ditto's split-key and selective-disclosure positioning.
  - Source: https://www.biometricupdate.com/202611/cloudflare-tools-for-humanity-propose-identity-framework-for-ai-agent-access
  - Date: 2026-11-05 (published); 2026-11-08 (Biometric Update)

---

## Upcoming signal (not yet a finding)

- **Future Identity Festival** runs 2026-11-09 to 2026-11-10 at The Brewery, London (2,500+ attendees). Watch for announcements; may generate findings for the next cycle.
- **KuppingerCole Access Management Leadership Compass**: Scheduled for November 2026 (calendar lists Nov 9); not yet confirmed as published. Check next cycle.
- **EUDI ARF Iteration 6** closes November 18. Watch for publication.
