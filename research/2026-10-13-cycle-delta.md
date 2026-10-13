# Cycle Delta -- 2026-10-13

Window: 2026-10-11 --> 2026-10-13 (last 48 hours)

Note: Worker API (ditto-slack-bot.dittobot.workers.dev) blocked by org egress policy in this session.
Delta written directly to GitHub. All findings verified against prior delta contents.

---

## Override-worthy this cycle

1. **Turkiye age-token mandate live Nov 1** -- Published Official Gazette 2026-10-10, effective 2026-11-01.
   Social platforms must verify age via e-Devlet government token that returns only "15+" or "18+": no name,
   no username, no document number. Existing accounts must comply by 2027-03-31.
   Account: company /. Angle: "A national government just mandated selective disclosure for age checks.
   The platform learns one bit, not who you are."

---

## New findings

### Pillar 1: Banking & Payments

- **PSD3/PSR OJEU publication now expected December 2026 (timeline slipped).** The political agreement was
  locked November 2025 but formal adoption and Official Journal publication have slipped to December 2026.
  The PSR then applies 21 months after publication (~Q3/Q4 2028); Verification of Payee obligation follows
  at 27 months. Earlier PSP guidance had anticipated mid-2026 publication. This is a material shift for
  compliance planning.
  - Source: https://www.adyen.com/knowledge-hub/psd3 (updated 2026-10-12)
  - Date: 2026-10-12

### Pillar 2: EUDI / eIDAS2

(no new material in window)

### Pillar 3: Fraud / Deepfakes

- **Denmark proposes deepfake likeness ban (legislative, no effective date yet).** Denmark's culture minister
  presented a Copyright Act amendment on 2026-10-12 that would ban sharing realistic deepfakes of a person's
  face or voice without consent. Major platforms would face takedown obligations. Frames individual likeness
  as a personal digital asset rather than purely a copyright instrument. Status: proposal only, committee
  review pending.
  - Source: (reported via secondary coverage; primary: Danish Ministry of Culture)
  - Date: 2026-10-12

### Pillar 4: ZKPs in Practice

(no new material in window)

### Pillar 5: Passwordless / Split-key

(no new material in window -- Authenticate U.S. 2026 conference runs Oct 19-21 in Carlsbad; watch for
FIDO Alliance announcements next cycle)

### Pillar 6: LATAM

- **Brazil Pix IN BCB 766 changes take full effect 2026-10-26.** Layered fund-tracing (in force Aug 10) and
  the extended 80-day MED contestation window (in force Sept 1) come together with further UI changes
  effective Oct 26. Institutions must present clearer contestation flows and permit document attachments for
  disputed transfers. Not a new rule in window, but the Oct 26 go-live is an actionable watch date.
  - Source: https://camposthomaz.com/en/?p=35664 (newsletter dated Sept 2026)
  - Date: watch date 2026-10-26

### Pillar 7: Identity ecosystem

- **IonQ acquires Elisity for up to $1.3bn -- quantum + Zero Trust M&A.** IonQ signed a definitive
  all-stock agreement on 2026-10-12 to acquire Elisity, a Zero Trust network security company. Strategic
  rationale: pair IonQ post-quantum cryptography (PQC) and quantum key distribution (QKD) with Elisity's
  identity-based access controls and enterprise customer base. Tied to the White House EO on quantum
  security dated 2026-06-22. Primary source is an SEC 8-K filing. Note: this is identity-adjacent
  (enterprise Zero Trust) rather than a pure digital-identity / KYC vendor deal, but signals that
  PQC + identity is now M&A territory at $1.3bn valuations.
  - Source: https://www.sec.gov/Archives/edgar/data/0001824920/000119312526419609/ionq-ex99_1.htm
  - Date: 2026-10-12

---

## Age assurance

- **Greece under-15 social-media ban bill.** Submitted to parliament 2026-10-11. Age checks via Gov.gr
  Wallet / Kids Wallet returning only an above/below-threshold flag. Committee review 2026-10-13; plenary
  vote expected 2026-10-22; target effective date 2027-01-01. First EU member state to write EUDI
  wallet-based threshold checks into law.
  - Source: secondary coverage of Greek parliamentary record
  - Date: 2026-10-11

- **Turkiye age-token regulation (full detail).** Threshold-only disclosure (15+ / 18+). Minimum age 15,
  separate restricted tier for 15-17. Enforcement via Cybersecurity Directorate. Existing accounts grace
  period to 2027-03-31.
  - Source: Official Gazette 2026-10-10
  - Date: 2026-10-10

---

## Customer onboarding

- **KakaoBank (South Korea) opens fully remote mobile account to foreign residents.** Launched 2026-10-12.
  Selfie check + Korea's public MyData identity confirmation, ~5 minutes. AI translation covers
  English/Chinese/Vietnamese. International debit card planned December 2026. Illustration of reusable
  government identity enabling private-sector account opening, not an ICP market for Ditto.
  - Source: secondary coverage; primary: KakaoBank press release
  - Date: 2026-10-12

---

## Open watch items

- 2026-10-16: DHS RIVR-2 applications close
- 2026-10-18: AMLA simplified-CDD roundtable expressions of interest close
- 2026-10-19/21: Authenticate 2026, Carlsbad (FIDO Alliance -- expect passkey/credential announcements)
- 2026-10-20: Japan My Number Card on Android (target)
- 2026-10-22: Greece under-15 bill plenary vote
- 2026-10-26: BCB MED 2.0 / IN BCB 766 Pix changes full effect
- 2026-10-26/30: FATF plenary, Paris
- 2026-10-29/30: EUDI Launchpad 2026, Brussels (72 days to Dec 24 deadline)
- 2026-11-01: Turkiye age-token regulation takes effect
- 2026-11-03: AMLA central AML/CFT database RTS consultation closes
- 2026-12-24: EUDI wallet-availability deadline (member states must offer at least one wallet)

---

## Session note

Worker API (ditto-slack-bot.dittobot.workers.dev:443) returned 403 at proxy CONNECT stage -- org egress
policy denial, not a credential error. Delta written to GitHub as fallback. Skill files (brand-brief,
competitors, pillars) could not be read; pillar framing based on task prompt constants. Drafter should
verify pillar alignment against brand-brief.md.
