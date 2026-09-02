# Cycle Delta — 2026-09-02

Window: 2026-08-31 → 2026-09-02 (last 48 hours, Wednesday cycle)

Worker unreachable this session (egress proxy blocks ditto-slack-bot.dittobot.workers.dev:443 — policy denial). Delta written directly to GitHub.

---

## Provenance and integrity notes

- **Lean cycle. The major print burst (16 articles, 2026-08-31) was captured in full by the 09-01 delta.** Tuesday September 1 was dominated by the DVS Trust Framework v1.0 commencement, also in the 09-01 delta. The 48-hour window for this cycle (Sep 1–Sep 2) is quiet across all seven primary pillars. One substantive on-pillar finding (TSA mDL), one corpus-gap back-fill requested by the 09-01 delta (ECB SSM-2026-0301), and one watch-item resolution (UK DVS CAB accreditation confirmed).

- **UK DVS CAB accreditation — watch item resolved.** The 09-01 delta flagged an unverified conditional: the framework comes into force "1 September 2026, or from the date at least one CAB is accredited, whichever is later." The accreditation question is now resolved: **UKAS granted accreditation to Kantara Initiative** as the first conformity assessment body under the UK DIATF in **November 2025** — months before 1 September 2026. The condition was already met before the in-force date. **Drafters may now write "the UK DVS Trust Framework v1.0 came into force on 1 September 2026" without qualification.** The caveat about CAB accreditation being unverified in the 09-01 delta is closed.
  - Source: https://www.biometricupdate.com/202511/kantara-first-accredited-to-certify-uk-digital-id-providers-under-diatf

- **ECB SSM-2026-0301 — corpus-gap back-fill (out of window, requested by 09-01 delta).** The 09-01 delta noted: "I found no trace of this letter in the recent corpus, and it is a first-order banking-identity anchor with a deadline 60 days out. Recommend a deliberate back-fill check next cycle." Research confirms: the letter exists, is a primary regulatory instrument, and has not appeared in any logged delta. **It is out of the 48-hour window (primary dated 2026-07-07) and is therefore NOT counted as a cycle finding, but is logged here for drafter awareness and to close the corpus gap.** See the Pillar 1 section below for full detail.

- **IDnow QEAA certification — out of window.** IDnow Trust Services AB received certification to issue Qualified Electronic Attestations of Attributes (QEAAs) on 2026-08-21. Biometric Update covered this in August 2026 (biometricupdate.com/202608). Out of the current 48-hour window and likely covered in an August delta. Not re-counted here.

- **California AB 1856** — awaiting Governor Newsom's signature. No change since 09-01 delta. Still write "passed both chambers, awaits signature."

- **Brazil ANPD / TikTok appeal** — TikTok has 10 business days from notification (2026-08-31) to appeal. No appeal filing confirmed in window. Watch item still open.

- **EUDI Relying Party Engagement webinar** — first webinar "Travel Across Europe" confirmed for 2026-09-18, 14:00–15:30 CET. No new content from the programme in this window.

---

## Override-worthy this cycle

(none)

The TSA mDL item is solid category evidence but US-only and does not rise to an override. The ECB corpus-gap item is a banking anchor but its primary is two months old and out of window.

---

## New findings

### Pillar 1: Banking & Payments

**CORPUS-GAP BACK-FILL — NOT A CYCLE FINDING (primary dated 2026-07-07)**

- **The ECB's Banking Supervision directorate wrote to all significant institutions on 7 July 2026 requiring each to submit a concrete AI cyber action plan to its Joint Supervisory Team by 31 October 2026 — with phishing-resistant MFA explicitly named as an implementation requirement and the explicit framing that no new rulebook is created: DORA is the binding standard, AI merely accelerates known attack categories.** Letter reference: **SSM-2026-0301**. Addressee: CEOs of all significant institutions under ECB supervision. Deadline: **2026-10-31** — **60 days from today**. Four priority areas: (1) vulnerability and patch management at AI attack speed; (2) defensive AI and detection, including anomaly detection; (3) third-party ICT risk (supply chain and managed service exposure); (4) defence-in-depth with **strong, phishing-resistant MFA** and legacy replacement. The ECB framing is explicit: "no new rulebook — DORA remains the binding framework; AI amplifies the speed and scale of known risks, it does not create new categories." This means every significant institution's DORA implementation plan must now also satisfy the SSM-2026-0301 action plan. Secondary analysis (KPMG, A&O Shearman, ADVISORI, Yubico, Fortinet, Bitsight, Nexis) is voluminous. **Obtain the ECB primary before any drafter uses the letter's language.** Why this matters for Ditto: this is the most direct banking-regulatory anchor yet for phishing-resistant MFA as a regulatory requirement — not as a best practice. The letter names "strong, phishing-resistant MFA" as a specific defence-in-depth requirement in an action plan that goes to the supervisory team of every major eurozone bank. Banks that have not already deployed phishing-resistant authentication now have a 31 October deadline and a supervisor to report to. **The argument for Ditto's Protect layer does not require a vendor pitch: it is now a regulatory action-plan requirement with a name and a date.** Account fit: (primary) / company. ⚠️ **This finding is logged as a corpus-gap back-fill. Primary is 2026-07-07. Do not present as a September 2026 event — anchor to the 31 October deadline, which is 60 days away.**
  - Primary: https://www.ecb.europa.eu/banking/supervision/ (SSM-2026-0301 — obtain full text before drafting)
  - Secondary: https://kpmg.com/de/en/insights/finance-and-risk/ezb-calls-for-an-action-plan-to-combat-AI-driven-cyberattacks.html
  - Secondary: https://www.aoshearman.com/en/insights/ecb-requires-significant-institutions-to-address-ai-enabled-cybersecurity-threats
  - Secondary: https://www.yubico.com/blog/what-the-european-central-banks-october-2026-ai-cyber-mandate-means-for-bank-identity-security/
  - Secondary: https://nexis-secure.com/insights/blog/the-ecb-action-plan-against-ai-cyberattacks-what-banks-must-submit-by-31-october-2026/
  - Date (primary): 2026-07-07 (letter); action plan deadline 2026-10-31

PSD3/PSR: still no OJEU notice number — still anticipated for September but not confirmed. AMLA Level 2: no new Commission endorsement in window. DORA: no new supervisory print. PSR APP-fraud review: Q3 2026, no output yet.

### Pillar 2: EUDI / eIDAS2

(no new material)

No new ARF version, implementing act, ENISA certification action, or member-state wallet launch in window. **EUDI Relying Party Engagement Programme webinar confirmed for 2026-09-18** (previously logged in 09-01 delta; not re-reported). Standing anchors: wallet-availability deadline **2026-12-24 (113 days from today)**; Germany 2027-01-02; relying-party acceptance for regulated private-sector entities December 2027.

### Pillar 3: Fraud / Deepfakes

(no new material)

No in-window primary fraud or deepfake report. No new named-bank incident or FATF publication in window. Brazil ANPD / TikTok (08-31 delta) remains the leading in-corpus enforcement item; TikTok's 10-day appeal window is still running.

### Pillar 4: ZKPs in practice (including mDL)

- **The TSA officially confirmed it now accepts Colorado's ISO 18013-5 mobile driver's licence across all 250+ participating US airports — with the CAT-2 reader performing selective-attribute data extraction and immediately purging post-comparison biometric data (2026-08-31).** The **Transportation Security Administration** issued a press release on **2026-08-31** formalising acceptance of **myColorado mDLs** (state-issued digital driver's licence, Colorado Department of Revenue) across **Denver International Airport and more than 250 participating airports nationwide**. Technical architecture: the credential follows **ISO/IEC 18013-5**, the same standard the EU ARF and EUDI wallet use for mDL attestations; the app transmits **selected identity data to the compatible reader rather than displaying the full credential** — selective attribute release, not a screen presentation. TSA uses **second-generation Credential Authentication Technology (CAT-2)** to read the ISO 18013-5 data, validate ticketing status, and execute **live biometric facial matching that is immediately purged post-comparison** — no biometric is retained. **21 US states** now offer mDLs accepted by TSA. Colorado adds roughly **3,700 travellers per month** at Denver alone. Why it matters for Ditto: this is the first TSA press release to anchor mDL acceptance formally in ISO 18013-5 selective-attribute terms at scale. **The architecture is the argument**: a holder hands over no document, discloses only what is needed, and the post-comparison biometric is destroyed — this is the "prove the attribute, not the document" design the ZKP/mDL pillar advocates and the model the EUDI wallet's mDL attestation is built on. The US rollout (21 states, 250+ airports, a live federal agency as the verifier) demonstrates the demand side: there are now enough verifiers and holders that selective-attribute mDL is operating at meaningful scale outside a pilot. **Constraints: US only, not a named Ditto ICP — category evidence only. The myColorado mDL is state-issued, not a EUDI wallet credential — do not conflate the architectures, but do use them together to show convergence on ISO 18013-5 as the cross-border credential standard.**
  - Source (primary): https://www.tsa.gov/news/press/releases/2026/08/31/tsa-accepts-mycolorado-mdls-during-identity-verification
  - Trade coverage: https://idtechwire.com/tsa-begins-accepting-mycolorado-mobile-drivers-licenses/
  - Secondary: https://coloradonewsline.com/2026/09/01/coloradans-mobile-drivers-licenses-airport/
  - Date: 2026-08-31 (TSA press release)

### Pillar 5: Passwordless / split-key

(no new material)

No FIDO Alliance output, regulator OTP-sunset action, or passkey adoption stat in window. Standing context unchanged: 5 billion passkeys in active use (World Passkey Day 2026-05-06); FIDO Agentic Authentication Technical Working Group formed April 2026. **GSA PQC Summit 2026-09-16 is 14 days out.**

### Pillar 6: LATAM

(no new material)

No new -relevant regulatory instrument in window. Brazil ANPD / TikTok appeal window (10 days from 2026-08-31) still open. CNBV Mexico biometric banking amendment compliance wall — November 2026, unchanged.

### Pillar 7: Identity ecosystem

(no new material)

**Identity Week America 2026 is underway September 2–3 in Washington D.C.** — no published outputs in window yet. Watch for post-event coverage on September 3–4. No analyst report (Forrester, KuppingerCole, Liminal, Gartner), M&A announcement, or funding round confirmed in window.

---

## Watch items carried forward

- **UK DVS Trust Framework v1.0 — CAB accreditation now confirmed (Kantara Initiative, UKAS, November 2025). Watch for first entries on the 1.0 register and the first de-listing.** The "at least one CAB accredited" condition was already satisfied on 1 September 2026.
- **ECB SSM-2026-0301 action plan deadline — 2026-10-31 (60 days).** Obtain ECB primary text. This is the strongest un-used banking hook in the corpus. Drafting window is now.
- **PSD3/PSR OJEU publication** — still anticipated September 2026, no OJEU notice number. Any notice number is an immediate content trigger.
- **AMLA Level 2 package** — Commission endorsement expected Q4 2026; Article 28(1) CDD RTS is the item that matters. AMLR applies 2027-07-10.
- **EUDI wallet-availability deadline 2026-12-24 (113 days)** — Germany 2027-01-02; relying-party acceptance December 2027.
- **EUDI Relying Party Engagement Programme** — first webinar "Travel Across Europe", 2026-09-18, 14:00–15:30 CET. Watch for use-case priorities and relying-party feedback.
- **Croatia alcohol age check — implementation deadline 2026-09-15 (13 days).** Watch for penalty detail, tourist/OIB exclusion coverage, and any EUDI cross-border remedy.
- **Australia IDLock — privacy consultation closes 2026-09-18.** National rollout 2027. Watch for DVS-equivalent technical interface spec.
- **California AB 1856** — awaiting Governor Newsom's signature. No change this cycle.
- **Brazil ANPD / TikTok appeal** — 10-day appeal window expires approximately 2026-09-12. Watch for appeal filing or compliance acknowledgment.
- **Identity Week America 2026** — September 2–3, Washington D.C. Watch for published outputs and government speaker remarks September 3–4.
- **GSA PQC Summit 2026-09-16 (14 days).**
- **Biometric Update × Goode Intelligence age-assurance webinar 2026-09-15** — 2026 Age Assurance & Digital Age Credentials Market Report is the item to obtain.
- **Thailand × Roblox National Digital ID** — second national-ID-into-gaming-platform signal, no agreement yet.
- **Singapore online safety legislation** — signalled for early 2027, no instrument yet.
- **FIDO wallet certification programme** — no published spec or date.
- **Meta consent judgment publication** — still the $17bn-vs-$18bn resolution item. Unchanged.
- **DNP / Austriacard** — Austrian FDI clearance last gate; completion targeted quarter ending September 2026. Watch for clearance announcement.
- **Australia Online Safety Amendment Bill** — Senate committee endorsed; watch for floor vote.

---

## Run summary

- **Findings count by pillar:** P4-ZKPs/mDL (1 — TSA myColorado mDL official acceptance at 250+ airports, ISO 18013-5 selective-attribute architecture); P1 corpus-gap back-fill only (ECB SSM-2026-0301, out of window). P2/P3/P5/P6/P7: no new material.
- **Override-worthy:** none this cycle.
- **Delta path:** research/2026-09-02-cycle-delta.md (written to GitHub — worker egress blocked).
