# Cycle Delta — 2026-09-25

Window: 2026-09-23 → 2026-09-25 (last 48 hours)

> **Operational note:** Worker API (`ditto-slack-bot.dittobot.workers.dev`) remains blocked by environment egress proxy (403 connect_rejected). Brand brief and pillar guides not fetched from worker. Deduplication performed against local GitHub copies of prior deltas (2026-09-23, 2026-09-24). Delta pushed directly to GitHub via MCP.

---

## Override-worthy this cycle

1. **Omada acquires EmpowerID to govern AI-agent identities in real time** — Sep 24, 2026; third identity-ecosystem signal in 48 hours that human governance of AI agents is the market's next mandatory layer (iProov HAPS Sep 21; BIO-key "Agentic AI Authenticated Controls" Sep 23; now a full IGA acquisition Sep 24). Angle: "Three signals, one week: the 'AI agents as identity type' moment isn't coming — it landed."

---

## New findings

### Pillar 1: Banking & Payments

(no new material — EBA final third-party risk guidelines (Sep 24) covered in yesterday's delta. AMLA CDD RTS Sep 30 deadline now 5 days away; no press release yet. PSD3/PSR OJEU publication still pending H2 2026.)

### Pillar 2: EUDI / eIDAS2

(no new material — EUDI ARF Iteration 6 opened Sep 23 (covered in Sep 23 delta); 15 discussion topics run through Nov 18. No member-state launch announcement with confirmed 2026-09-23–25 date.)

### Pillar 3: Fraud / Deepfakes

(no new material in window — iProov HAPS (Sep 21) covered in Sep 23 delta. Ofcom NCII deepfake hash-matching compliance deadline remains Sep 30; no enforcement action confirmed within window.)

### Pillar 4: ZKPs in Practice

(no new material — no new bank ZKP pilot or OpenID4VP/VCI spec update with confirmed 2026-09-23–25 date.)

### Pillar 5: Passwordless / Split-key

- **GSA's Login.gov begins accepting mobile driver's licenses stored in Google Wallet and Samsung Wallet for identity proofing (2026-09-23)** — The US General Services Administration expanded Login.gov's public-facing identity platform to accept ISO 18013-5 mDLs held in Google Wallet and Samsung Wallet as a primary identity-proofing option. Crucially, GSA framed the launch around selective disclosure: users "can preview and share only the specific attributes required for verification rather than their entire document." As of March 2026, 20 US states and one territory offer mDLs, covering approximately 71.5 million drivers. The integration is scoped to identity proofing for government-service access and is one option alongside existing methods — not mandatory. Why it matters for an identity vendor: this is the most significant US-government validation yet that attribute-selective, wallet-held credentials are production-ready for regulated-sector access; it directly pre-figures what EU relying parties will face under eIDAS2 by late 2027, and gives Ditto a US–EU parallel in any government-sector pitch.
  - Source: https://www.govexec.com/technology/2026/09/logingov-now-accepting-mobile-drivers-licenses/416166/
  - Source: https://fedscoop.com/mobile-drivers-licenses-login-dot-gov-identity-verification/
  - Date: 2026-09-23

### Pillar 6: LATAM

(no new material in window — BCB Resolução 587 (Pix fraud-marking, Sep 18) pre-window and covered in prior deltas. Note: Brazil Resolution 561 FX/VASP channel migration cutover is 2026-10-01 — 6 days away; watch for BCB enforcement bulletin.)

### Pillar 7: Identity Ecosystem

- **Omada acquires EmpowerID to close the AI-agent identity gap (2026-09-24)** — Omada A/S (backed by GRO Capital) announced the acquisition of EmpowerID, a Dublin, Ohio-based identity-governance software company, on September 24, 2026. EmpowerID brings runtime agent-governance capabilities: the combined platform allows organisations to define, in real time, what each AI agent is permitted to do and to revoke that permission the moment the agent steps outside those boundaries — replacing post-hoc audit with inline enforcement. Patrick Parker (EmpowerID founder) becomes Omada's Chief Innovation Officer. Financial terms were not disclosed. Why it matters: this is the first IGA acquisition explicitly framed around AI-agent runtime governance rather than human-identity provisioning — confirming that IGA vendors are treating autonomous agents as a distinct identity class requiring dedicated controls. It is the third AI-agent-identity signal in 48 hours alongside iProov HAPS (Sep 21) and BIO-key's "Agentic AI Authenticated Controls" FIDO cert (Sep 23), representing a material clustering of market signals.
  - Source: https://www.prnewswire.com/news-releases/omada-acquires-empowerid-to-close-the-ai-agent-security-gap-302888544.html
  - Source: https://martechseries.com/predictive-ai/ai-platforms-machine-learning/omada-acquires-empowerid-to-close-the-ai-agent-security-gap/
  - Date: 2026-09-24

- **Bangladesh announces $748M budget for One-ID digital identity gateway at UN side event (2026-09-23)** — ICT Adviser Rehan Asif Asad announced at a UN General Assembly side event in New York on September 23, 2026 that Bangladesh has budgeted US$748M for an 18–24 month programme to establish a single unified digital identity system as the primary gateway to all public-sector services. The system will incorporate AI-driven DPI, Estonia's X-Road data-exchange framework, and will consolidate multiple sectoral credentials (NID, tax, health, education) into a single lifelong digital identity. Biometric Update confirmed the $748M figure and describes the plan as a "One-ID" platform. Why it matters for an identity vendor: a $748M national identity platform procurement in South Asia (population ~175M) is a tier-1 emerging-market opportunity signal; the explicit X-Road interoperability requirement favours vendors with standards-based credential frameworks.
  - Source: https://www.biometricupdate.com/202609/bangladesh-budgets-us748-million-for-one-id-digital-identity-project
  - Source: https://www.newagebd.net/post/telecom/315090/ai-driven-digital-public-infrastructure-in-2yrs-ict-adviser
  - Date: 2026-09-23

---

## Open watch items (carried forward and updated)

- **2026-09-27** — AMLA draft RTS on risk profiling of non-financial sector obliged entities consultation closes (2 days).
- **2026-09-30** — AMLA submission to European Commission of finalised CDD RTS (first unified EU KYC baseline). Watch for AMLA press release.
- **2026-09-30** — Ofcom NCII/deepfake hash-matching compliance deadline (5 days). Fines up to 10% of global revenue.
- **2026-09-30** — US DOL unemployment insurance Group 1 states (25) Login.gov onboarding deadline. Watch for state go-live confirmations.
- **2026-10-01** — Brazil Resolution 561 FX/VASP channel migration cutover (6 days).
- **Late September 2026** — Forrester Wave CIAM evaluation kick-off (Andras Cser; "AI agents as a new identity type" headline). Could drop any day.
- **Late September 2026** — DHS biometric capture GWAC ($440.7M) awards expected across five tracks.
- **2026-10-22** — Utah SB73 / Aylo ruling.
- **2026-10-31** — ECB SSM-2026-0301 action plan deadline (AI-enabled cyberattacks; strong phishing-resistant MFA priority area).
- **2026-11-18** — EUDI ARF Iteration 6 closes (15 topics; 4 new including Topics AB, AC, AD, AE).
- **2026-12-24** — EUDI wallet availability deadline (90 days). Germany 2027-01-02 ("d-you", 40 launch partners); fewer than 1/3 of member states meet readiness benchmark.
- **Open** — Coimisiún na Meán v X: X's promised ID verification "within weeks."
- **Open** — Brazil ANPD Board of Directors ruling on TikTok.

---

## Run summary

- **Findings count by pillar:** P5 Passwordless: 1 (GSA Login.gov mDL acceptance, Sep 23). P7 Identity Ecosystem: 2 (Omada/EmpowerID acquisition Sep 24; Bangladesh $748M One-ID DPI Sep 23). All other pillars: no new primary material in window.
- **Override-worthy:** Omada/EmpowerID — third AI-agent-identity signal in 48 hours (after iProov HAPS and BIO-key FIDO cert); strongest market-validation cluster's "AI agents as new identity type" thesis.
- **Delta path:** `research/2026-09-25-cycle-delta.md` — worker API blocked (egress policy); delta pushed directly to GitHub via MCP.
