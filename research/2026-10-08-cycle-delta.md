# Cycle Delta — 2026-10-08

Window: 2026-10-06 → 2026-10-08 (last 48 hours, Thursday run)

## Provenance and integrity notes

- The worker API was **unreachable** this run (egress proxy blocked `ditto-slack-bot.dittobot.workers.dev`). Skill files and deduplication corpus were read directly from the GitHub repository (`amehta0104/ditto-linkedin-content`). Deduplication checked against the most recent deltas (2026-10-06, 2026-10-07). Pillar guidance inferred from prior delta structure; content and biases held consistent.
- The 10-07 delta covered Oct 5–7 material; its rejected-items list did **not** mention the South Korea bank hack story (published Oct 6 in Korean press, picked up in English Oct 6–7). It is not in any prior delta and is counted as a new finding.
- The Regula Crypto KYC Snapshot press release was published **2026-10-08** (today); no prior delta could have covered it.
- **PSD3/PSR OJEU:** A source (published ~35 days before today, so ~early September) puts the European Parliament plenary date at December 14, 2026 (indicative). This is outside the 48 h window but updates the open watch item. Logged below under watch items only; not counted as a new finding.
- **Checked and rejected (in-window, not new or off-lane):**
  - Indonesia government market consultation for facial liveness for national digital ID (Oct 7): off-ICP, minor.
  - CBP 1 billion facial biometric verifications milestone (Oct 6): US border, off-lane.
  - Biometric Update accessibility opinion piece (Oct 7): no new facts.
  - EUDI ARF: no new ARF version or October implementing act found; ARF remains at v2.8, next milestone Launchpad 2026 (Oct 29–30).
  - Incognia AI-agent detection tool (Finextra, Oct 6): single-source trade press, could not verify with primary. Held over pending primary confirmation.
  - Fourthline, IDEMIA WebCapture, Apple/Google MERA, Apple Cash, GOV.UK One Login/Ecospend, Bron FaceScan, Ping Identity survey, AMLA RTS, OFAC A7 Network: all in prior deltas.
  - Visa/BioCatch ($2.4 B): August 2026, outside window, likely in earlier delta.
  - Socure/Fravity $156 M: August 2026, outside window.

---

## Override-worthy this cycle

1. **An open-source Chinese AI agent (Artex) is suspected of breaching seven South Korean financial institutions, exposing ~68,000 customers' income data, loan limits, and resident registration numbers.** Account: company / /. Angle: "An AI agent just walked into seven banks. It didn't phish anyone. It guessed its way to valid account numbers and pulled the rest. No funds taken—just the data that makes synthetic-identity fraud downstream."

---

## New findings

### Pillar 1: Banking & Payments

- **South Korea's financial regulator (FSC/FSS) ordered all financial firms to immediately tighten fraud monitoring and stand up help desks for the ~68,000 customers whose data was exposed in an AI-assisted breach campaign spanning seven institutions.** Banks have agreed to heighten scrutiny of new loan applications, new account openings, and large transfers tied to breach victims. Authorities also urged firms to move toward AI-based anti-phishing defences and have flagged the need for more thorough auditing requirements.

  **Why it matters:** The regulator's response frames the breach as an authentication and onboarding risk, not just a security one. Exposed income and loan-limit data is the raw material for synthetic-identity credit fraud. Institutions are being told to treat their own onboarding flows as the next attack surface.
  - Source: see Pillar 7 for full sourcing on the breach itself
  - Date: 2026-10-06

### Pillar 2: Identity orchestration

(no new material in window)

### Pillar 3: EUDI / eIDAS2

(no new material in window. Launchpad 2026 remains 2026-10-29/30, Brussels. ARF at v2.8; no new iteration found. Under-one-third of member states reportedly on track for the December 24 deadline per a June 2026 source.)

### Pillar 4: KYC / AML compliance

(no new material in window. AMLA simplified-CDD roundtable expressions of interest still close 2026-10-18. AMLA RTS package logged 2026-10-01.)

### Pillar 5: Customer onboarding

(no new material in window)

### Pillar 6: Identity verification (IDV)

(no new material in window)

### Pillar 7: Fraud / Deepfakes

- **South Korea: open-source AI agent Artex suspected of breaching seven financial firms, exposing ~68,000 customers' personal and financial data.** Korean police opened a 28-investigator task force on 2026-10-06. President Lee Jae Myung said AI agents were "highly likely" used; officials told AFP the attribution to Artex is "highly likely" but unconfirmed.
  - **Affected institutions:** Shinhan Bank, KB Kookmin Bank, Hana Bank, BNK Busan Bank, Yegaram Savings Bank, Welcome Savings Bank, Hyundai Capital.
  - **Exposed data:** names, phone numbers, resident registration numbers, annual income, loan limits. In the Shinhan case, investigators found attackers fed random values to discover valid customer numbers and then extracted associated records. No funds were stolen.
  - **The tool:** Artex is an open-source AI agent written by Li Puhua (alias "Autumn"), a Chinese cybersecurity engineer. It draws on commercial models including Claude Opus, ChatGPT, and DeepSeek to automate vulnerability discovery. Officials said use of a Chinese-built tool does not itself imply Chinese state attribution; attack IPs spanned 20+ addresses across ~12 countries including the US, Japan, and Germany.
  - **Figures:** precise counts vary by outlet and institution. Shinhan: ~25,000 accounts cited in most reports; Yegaram Savings Bank: ~40,000. Aggregate cited as 66,000–68,000. Treat as provisional pending police confirmation.

  **Why it matters for an identity vendor:** this is the first widely confirmed case of AI-agent-automated enumeration attacks on live bank authentication endpoints at scale. The attack vector was not a deepfake credential or injection attack—it was brute-force enumeration of valid account numbers, a step that normally requires human effort and is limited by it. AI removes that limit. The stolen data (income, loan cap, registration number) is a synthetic-identity fraud kit. Cross-ref Pillar 1: the regulatory response is explicitly linking this to onboarding risk.
  - Source: https://bankinfosecurity.com/south-korea-suspects-ai-tool-helped-steal-bank-customer-data-a-33031
  - Source: https://www.sofx.com/south-korea-says-ai-agents-likely-breached-seven-financial-firms-68000-customers-exposed/
  - Source: https://www.koreaherald.com/article/10894542
  - Source: https://qz.com/south-korea-president-ai-bank-hacks-68000-customers-100726
  - Date: 2026-10-06 (police opened probe; story broke in Korean press same day)
  - **Drafting cautions:**
    - Artex attribution is "highly likely" per Korean officials, not yet forensically confirmed. Say "suspected" or "authorities believe", never "confirmed".
    - Figures differ across outlets. Do not combine figures from different institutions into a single precise number.
    - No funds stolen—this is a data-harvest, not a financial theft. Do not imply monetary loss.

- **Regula Crypto KYC Snapshot (Oct 8, 2026): 44% of surveyed crypto firms report confirmed AI-assisted or automated activity on the user side of identity checks, versus 31% in other sectors.**
  - **Secondary stat:** 48% of crypto respondents associate incorrect identity verification results with financial loss, vs 38% in other sectors.
  - **Method:** Sapio Research, March 2026, 850 fraud-prevention/financial-crime decision-makers across six sectors, 102 of whom are in crypto. Small crypto sample; treat sector gap as directional.
  - **Parent study context:** an earlier release from the same study series (May 2026) found 87% of companies globally report signs of AI-assisted or automated activity within identity verification processes, with only 26% classifying it as a major risk.

  **Why it matters:** published the same day as the South Korea story, the Regula figure gives a market-data frame for the incident. If 44% of crypto firms are already seeing AI/automation on the user side of their IDV flows, the South Korea case is not an outlier—it is the high-water mark of a known trend reaching banking infrastructure.
  - Source (primary): https://www.globenewswire.com/news-release/2026/10/08/3376956/0/en/nearly-half-of-crypto-firms-confirm-ai-or-automation-on-the-user-side-of-identity-checks-survey-finds.html
  - Source: https://www.lelezard.com/en/news-nearly-half-of-crypto-firms-confirm-ai-or-automation-on-the-user-side-of-identity-checks-22394745.html
  - Date: 2026-10-08
  - **Drafting cautions:**
    - Regula is an IDV vendor (document verification). Cite the data, do not promote the vendor.
    - "Confirmed" in the headline means respondents self-reported it; it is not an independent audit. Use "surveyed firms report" or "respondents confirmed", not "44% of firms use AI fraud."
    - The 44% vs 87% gap (crypto vs all-industry) and the May vs October timeframes are from different sample cuts of the same study; do not directly compare them as a trend.

### Pillar 8: Mobile trust & app security

(no new material in window)

### Pillar 9: Passwordless / split-key

(no new material in window. Authenticate 2026 is 2026-10-19/21.)

### Pillar 10: ZKPs in practice

(no new material in window)

### Pillar 11: Age assurance & privacy attributes

(no new material in window)

---

## Open watch items (updated)

- **PSD3/PSR OJEU:** European Parliament Legislative Observatory now lists **December 14, 2026** as the indicative plenary date (source ~35 days old). If plenary is in December, entry into force likely 2027 and main PSR application date ~mid-2028. Next check: 2026-10-12.
- **DHS RIVR-2:** IDV/SMTD applications close **2026-10-16**.
- **AMLA simplified-CDD roundtables:** expressions of interest close **2026-10-18**; sessions 2026-11-09 and 2026-12-02.
- **2026-10-19/21:** Authenticate 2026, Carlsbad — expected passkey/FIDO content.
- **2026-10-20:** Japan My Number Card on Android (target date).
- **2026-10-26:** BCB MED 2.0 infraction-notification changes take effect.
- **2026-10-29/30:** EUDI Launchpad 2026, Brussels (invitation-only). ARF update expected around this date.
- **End-October:** Ofcom over-16 age-assurance rapid assessment.
- **2026-10-31:** ECB SSM-2026-0301 action-plan deadline.
- **Early November:** CNBV Anexo 71 biometric compliance deadline (~90 business days from July 1 rule, banks must have facial recognition for Level 3/4 accounts). Watch for FSS/FSC follow-on guidance on AI-enumeration attack defences in South Korean banking.
- **2026-11-18:** EUDI ARF Iteration 6 closes.
- **2026-12-24:** EUDI wallet-availability deadline for member states.
- **South Korea AI breach:** watch for police forensic confirmation of Artex attribution; affected-customer count updates; and whether FSC issues formal guidance on AI-agent attack defences for financial institutions.
