# Cycle Delta — 2026-05-26

Window: 2026-05-24 → 2026-05-26 (last 48 hours — Tuesday cycle)

## Override-worthy this cycle

1. **Microsoft Entra Face Check (government ID + biometric face match) for account recovery reaches GA — named IDV partner ecosystem now published** — The "What's New in Microsoft Entra May 2026" blog (cited in the 05-25 delta for Entra External ID passkeys GA and Agent ID) also confirmed that **Microsoft Entra ID account recovery with government-issued ID and biometric face check** is now generally available — a distinct finding the 05-25 delta did not capture. Users who lose all authentication methods can now recover access via a liveness-matched government ID document, guided through an IDV provider from Microsoft's named ecosystem. At GA, Microsoft published its partner list for the first time: **1Kosmos** and **CLEAR** join existing partners **Au10tix**, **IDEMIA**, and **TrueCredential** in the Microsoft Security Store. Angle: Microsoft just declared what the auth-recovery stack looks like — government ID + face check, not SMS. For identity vendors, this is the signal that IDV is no longer a one-time onboarding checkpoint: it is now the backstop when a phishing-resistant passkey is lost. The named partner list (Au10tix, IDEMIA, CLEAR, 1Kosmos, TrueCredential) is also the first public, hyperscaler-endorsed IDV vendor shortlist for the account-recovery use case.

## New findings

### Pillar 1: Banking & Payments

(no new material in window — PSD3/PSR: EP ECON vote was 5 May (PSD3 50-3-5; PSR 50-2-2); plenary vote now expected at the June 2026 Strasbourg session; OJEU publication anticipated June–September 2026. DORA: 19 CTPPs designated 18 November 2025; 2026 is active-enforcement phase but no new designations or penalty-payment actions in window. AMLA: two public hearings on 28 May 2026 — business-wide risk assessment Guidelines (10:00–12:00 CET) and home-host supervisory cooperation RTS (14:00–16:00 CET) — are the next substantive AMLA outputs; sweep immediately after. Consultation papers: business-wide risk assessment published 16 April 2026 (consultation deadline 15 July); home-host supervisory cooperation RTS published 11 May 2026. EBA Reporting Framework 4.3 final publication expected June 2026; draft technical package published 16 April.)

### Pillar 2: EUDI / eIDAS2

(no new material in window — ARF remains at v2.8.0 (EU Digital Identity Wallet GitHub); no new Implementing Acts or member-state launch announcements in window. ENISA EUDIW cybersecurity certification scheme post-consultation review (public review closed 30 April; Implementing Act expected end-2026) unchanged. Upcoming: German EUDI Hackathon 4–5 June Berlin; EUDI Wallet Community Event 25 June Berlin. Estonia RIA €21.65M procurement (05-22 override) remains the freshest single procurement anchor.)

### Pillar 3: Fraud / Deepfakes

- **ACFE Fraud Magazine May/June 2026 cover: "A Blueprint for Beating Synthetic IDs" — US lenders face $3.3 billion direct exposure to synthetic identity fraud in new accounts, all-time high, +7% from 2024** — The Association of Certified Fraud Examiners (ACFE) dedicated its May/June 2026 cover story to synthetic identity theft, which it describes as "now the fastest-growing fraud threat across the globe." The cover story presents a three-part blueprint: (1) **Credit bureau reform** — bureaus disclose scant information about how credit profiles are created, matched, and maintained, the gaps synthetic-ID fraudsters routinely exploit; (2) **Vulnerability assessment** — generative AI accelerates synthetic identity creation by enabling near-instant fabrication of supporting documents alongside CPNs (credit privacy numbers); (3) **Recommended solutions** — reform credit reporting, expand access to the SSA's Electronic Consent-Based SSN Verification (eCBSV) service, and adopt digital identity credentials to shift the assurance layer from document-procedural to cryptographic. Significance for Ditto: the ACFE cover story is the highest-profile trade-association framing of the synthetic-ID problem in 2026. The $3.3 billion stat is primary-source, specific to new-account exposure (the onboarding moment), and is the first figure directly tied to the KYC gap rather than aggregate fraud losses. The eCBSV + digital identity prescription aligns directly with orchestrated onboarding as the architectural answer. **Note:** ACFE Fraud Magazine publishes bi-monthly; the May/June 2026 issue circulation date is not confirmed as within the strict 48h window — treat as first-capture if not previously tracked.
  - Source: https://www.acfe.com/fraud-magazine/all-issues/issue/article?s=2026-mayjun-cover-blueprint-for-synthetic-id-theft
  - Date: May/June 2026 issue (exact circulation date within May not confirmed)

### Pillar 4: ZKPs in practice

(carry-forward, status unchanged — OpenID Connect ASC 1.0: vote concluded 15 May 2026; formal Implementer's Draft result page still not published by OpenID Foundation as of 26 May. DIF KYA-OS: 14-day Trusted Agentic AI Working Group review period concluded approximately 22–25 May; as of DIF Newsletter #61 (May 2026), the specification is in review ahead of the vote — no vote result published on blog.identity.foundation or DIF newsletter as of this scan. Sweep again after FIDO Authenticate APAC June 2–3 and Money20/20 Europe June 2–4 for any standards announcements in either event.)

### Pillar 5: Passwordless / Split-key

- **Microsoft Entra Face Check for account recovery reaches GA — government ID + biometric face match replaces SMS as the recovery backstop; named IDV partner ecosystem published** — See override item. Additional specifics: the Biometric Update synthesis article ("Microsoft expands passkey support, phases out weaker authentication methods," published May 2026) confirms the Entra recovery flow: a user who loses all phishing-resistant authentication factors is guided through an IDV provider — driver's licence or other government-issued document — with a liveness face check to confirm the physical owner matches the document photo. Once verified, the user is prompted to register a synced passkey to prevent future lockout. Separately, the same Microsoft blog confirmed that **security questions will be removed as a password-reset option in Microsoft Entra ID from January 2027**, citing susceptibility to guessing and social engineering — closing the last procedural fallback in the Entra authentication stack. The January 2027 removal date gives regulated firms a concrete deadline for eliminating security-question-based resets from their own Entra-integrated applications.
  - Source: https://techcommunity.microsoft.com/blog/microsoft-entra-blog/whats-new-in-microsoft-entra-may-2026/4517884
  - Source: https://www.biometricupdate.com/202605/microsoft-expands-passkey-support-phases-out-weaker-authentication-methods
  - Date: 2026-05-25 (What's New in Entra May 2026 blog); Biometric Update synthesis ~2026-05-25 to 2026-05-26

### Pillar 6: LATAM

(no new material in window — Colombia Bre-B: 103.38 million keys registered (April 13, 2026 data; outside window); 34 million registered users / 638.69 million transactions processed as of April 5, 2026. Bre-B is in a "Pix moment" watch phase for P2P card displacement. No new CNBV, Superfinanciera, BCB, CMF, SBS publications in window. Standing carry-forwards: Colombia open-finance technical standards (August 2026); Brazil Pix MED 2.0 / BCB device-limit rules in force; Mexico Fintech Law 2.0 expected October 2026; Chile Law 21,719 data-protection regime fully in force December 2026. Upcoming: FIDO Authenticate APAC 2–3 June Singapore (Cyber Security Agency of Singapore as government sponsor) — fintech SCA and passkey trajectories in Singapore are the closest leading indicator for the LATAM regulatory arc.)

### Pillar 7: Identity ecosystem

(no new M&A, funding, or analyst report publications confirmed in window — KuppingerCole 2026 Research Compass for IAM remains the most recent analyst-cadence output; the EIC 2026 AuthZEN award (05-22 override) was the last analyst-event endorsement. Upcoming event cluster June 2–5 will generate significant Pillar 7 material: Money20/20 Europe 2–4 June Amsterdam (identity, decentralised identity, agentic commerce all on agenda); FIDO Authenticate APAC 2–3 June Singapore; German EUDI Hackathon 4–5 June Berlin. DIF KYA-OS vote and ASC 1.0 formal publication are also expected before or during that window. MetaComp StableX KYA Framework for regulated financial services (announced Money20/20 Asia, 21 April 2026) is a category-pattern signal for the "agentic identity governance" sub-theme but is outside the window; has been absorbed into the DIF KYA-OS context by prior deltas.)

---

## Run summary

- Findings by pillar: P1: 0 | P2: 0 | P3: 1 (ACFE $3.3B synthetic ID cover story — primary source, not in prior deltas) | P4: 0 (carry-forward: ASC 1.0 + KYA-OS) | P5: 1 (Microsoft Entra Face Check account recovery GA + January 2027 security-question removal — missed from 05-25 delta's read of same source) | P6: 0 | P7: 0 → Total: **2 hard findings** (lean Tuesday-after-weekend cycle)
- Override-worthy: **1** — Microsoft Entra Face Check (gov ID + biometric) for account recovery GA with named IDV partner ecosystem (1Kosmos, CLEAR, Au10tix, IDEMIA, TrueCredential); account: / company; angle: IDV is now the backstop for every lost passkey, not just onboarding KYC
- Delta path: research/2026-05-26-cycle-delta.md
- Note: worker at ditto-slack-bot.dittobot.workers.dev returned HTTP 403 host-not-allowed under this session's sandbox network policy; delta written directly to GitHub repo (amehta0104/ditto-linkedin-content) instead; mirror-research workflow will sync to public mirror on push to main
- Next-cycle anchors: AMLA May 28 double-hearing (sweep same day); Money20/20 Europe + FIDO Authenticate APAC + German EUDI Hackathon all June 2–5 (heavy next Friday/weekend cycle); DIF KYA-OS vote result and ASC 1.0 formal publication both imminent
