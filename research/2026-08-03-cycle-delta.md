# Cycle Delta — 2026-08-03

Window: 2026-08-01 → 2026-08-03 (last 72 hours — Fri–Mon)

Worker note: `ditto-slack-bot.dittobot.workers.dev` continues to return 403 from the session's egress proxy (policy denial). Delta written directly to GitHub via MCP. Skill files sourced from prior deltas and repository baseline.

---

## Override-worthy this cycle

1. **EU AI Act GPAI + Article 50 enforcement both went live Friday — Day 1 is Monday's post window** — GPAI fine powers (3% global turnover) and Article 50 deepfake/chatbot transparency rules activated simultaneously on August 2. Banks that assumed all AI Act deadlines moved to 2027 based on Digital Omnibus headlines are exposed — Article 50 and GPAI were not deferred. Account: / company. Angle: "Day 1 of EU AI enforcement. Two sets of powers went live Friday: Article 50 transparency and GPAI Commission enforcement. Every bank with AI in its customer stack — chatbots, fraud detection, document understanding — is now inside the enforcement perimeter."

---

## New findings

### Pillar 1: Banking & Payments

- **EU AI Act high-risk AI enforcement now live for bank AI deployments — new systems face immediate obligations** — From 2 August 2026, the EU AI Act's enforcement framework is active for high-risk AI. Banks' AI systems in credit scoring, AML transaction monitoring, fraud detection, and insurance underwriting qualify as high-risk under Annex III. Fines for non-compliance: up to €30M or 6% of global annual turnover — double the Article 50/GPAI cap. Important distinction: the Digital Omnibus package deferred high-risk obligations for systems already on the market before August 2 to December 2, 2027 — but any new deployment from August 2, 2026 onward must comply immediately. Banks accelerating AI rollouts this year face immediate obligations. For identity vendors: AI-powered onboarding flows, liveness detection systems, and document verification tools deployed from this date fall within the enforceable high-risk framework.
  - Source: https://www.aurigaspa.com/en/news-and-media/blog-eng/eu-ai-act-for-banks-dora-compliance/
  - Source: https://artificialintelligenceact.eu/enforcement-of-chapter-v-under-the-eu-ai-act/
  - Date: 2026-08-02 (enforcement activation)

### Pillar 2: EUDI / eIDAS2

(no new ARF release, member-state wallet launch announcement, or Commission implementing act dated 2026-08-01 to 2026-08-03. Germany/Austria/France pilots ongoing from May 2026 per prior deltas. December 24 wallet-availability deadline remains the anchor — 143 days away. No new in-window print.)

### Pillar 3: Fraud / Deepfakes

- **EU AI Act Article 50 Day 1: deepfake labeling, chatbot disclosure, synthetic-content marking now enforceable EU law** — As of 2 August 2026, Article 50 transparency obligations are fully enforceable. Key obligations active: (i) chatbot disclosure — AI-generated interactions must identify themselves as AI unless obviousness is apparent; (ii) deepfake labeling — AI-generated or manipulated image, audio, video, or text on matters of public interest must carry machine-readable marking and human-readable disclosure; (iii) biometric categorisation and emotion-recognition systems must notify subjects. Fines: up to €15M or 3% of global annual turnover. Critically, the Digital Omnibus package that deferred many high-risk obligations to December 2027 did NOT apply to Article 50 — organisations that stood down AI Act compliance programs based on Digital Omnibus headlines are directly exposed. One narrow transitional relief: GPAI systems already on market before August 2 have until December 2, 2026 to implement machine-readable content marking under Art. 50(2). For Ditto: any bank deploying AI chatbots in customer-facing flows, synthetic-ID detection using generative AI, or document verification with AI-generated reference images now faces enforceable obligations.
  - Source: https://artificialintelligenceact.eu/transparency-rules-article-50/
  - Source: https://compliancehub.wiki/eu-ai-act-article-50-transparency-digital-omnibus-2026/
  - Source: https://digital-strategy.ec.europa.eu/en/faqs/transparency-obligations-under-article-50-ai-act
  - Date: 2026-08-02 (enforcement activation)

- **EU AI Act GPAI enforcement powers live: EU AI Office can now fine, audit, and restrict AI model providers embedded in financial services stacks** — Concurrent with Article 50, the EU AI Office's supervision and enforcement powers over General-Purpose AI model providers became applicable on 2 August 2026. Powers: requesting technical documentation, conducting model evaluations, demanding compliance and risk-mitigation measures, restricting or withdrawing a model from the EU market, imposing fines of up to 3% of global annual turnover. GPAI providers (OpenAI, Google, Anthropic, Mistral, Meta, etc.) whose models are embedded in financial-services workflows — fraud detection, document understanding, identity chatbots — are now directly subject to EU AI Office oversight. GPAI Code of Practice signatories receive mitigated fine treatment but are not exempt from enforcement. For Ditto: the GPAI enforcement layer creates a procurement and risk question for every bank embedding third-party AI: what is their GPAI provider's compliance posture, and what indemnity exists if the model is restricted from the EU market?
  - Source: https://www.lw.com/en/insights/eu-ai-act-gpai-model-obligations-in-force-and-final-gpai-code-of-practice-in-place
  - Source: https://compliancehub.wiki/eu-ai-act-gpai-enforcement-august-2026-readiness/
  - Source: https://beam.ai/agentic-insights/eu-ai-act-enforcement-august-2-2026-gpai-fines
  - Date: 2026-08-02 (enforcement activation)

### Pillar 4: ZKPs in practice

(no new bank ZKP pilot, OpenID4VP/VCI deployment report, or selective-disclosure mDL milestone dated 2026-08-01 to 2026-08-03. No new in-window print.)

### Pillar 5: Passwordless / split-key

(no new FIDO Alliance spec release, regulator OTP-sunset announcement, or major bank passkey mandate dated 2026-08-01 to 2026-08-03. Standing anchors: Microsoft Entra passkeys-by-default + OpenAI hardware-passkey mandate both September 1 — 29 days away. No new in-window print.)

### Pillar 6: LATAM

(no new CNBV, Superfinanciera, CMF, SBS, or BCB regulatory action dated 2026-08-01 to 2026-08-03. No new in-window print.)

### Pillar 7: Identity ecosystem

- **OfDIA's first DVS Annual Report: UK digital identity sector = 275 firms, £2.027B revenue — September 1 Trust Framework 1.0 enforcement 29 days away** — On 14 July 2026, the Office for Digital Identities and Attributes (OfDIA) published its first statutory annual report under Part 2 of the Data (Use and Access) Act 2025. This is the UK government's first formal accounting of the digital identity sector under the Act. Key data: 275 firms providing digital identity products and services in the UK; £2.027B annual revenue; 9,624 FTE roles. The report confirms that DVS Trust Framework 1.0 is on track to come into force September 1, 2026, when UKAS completes recognition of the certification scheme — at which point new certifications will only be issued under 1.0 (existing gamma/v0.4 providers have a tailored uplift route). Kantara Initiative is the first and currently only accredited conformity assessment body. UK CertifID trust mark is in preparation. Note: this report is dated July 14 (19 days before today); it was not captured in any prior delta and is included as a first-capture finding.
  - Source: https://enablingdigitalidentity.blog.gov.uk/2026/07/15/publishing-ofdias-first-annual-report-on-digital-verification-services/
  - Source: https://www.gov.uk/government/publications/office-for-digital-identities-and-attributes-2026-annual-report/ofdia-2026-annual-report-on-the-operation-of-part-2-of-data-use-and-access-act-2025
  - Source: https://www.biometricupdate.com/202607/ofdia-confirms-commitment-to-dvs-trust-framework-in-annual-report
  - Date: 2026-07-14 (first-capture; not in prior deltas)

---

## Next-cycle anchors (updated)

- **Ofcom post-July-31 enforcement watch** — Deadline passed July 31. No named enforcement action found as of August 3. Watch for Ofcom press release or investigation opening against non-compliant providers (legal-notice recipients had until July 31 to submit risk assessments). Any named enforcement is a UK identity-verification demand signal.
- **PSD3/PSR OJEU publication** — Still outstanding as of August 3; anticipated summer/early autumn 2026 (possibly September). European Parliament plenary vote completed; legal-linguistic review phase ongoing. Search each cycle.
- **UK DVS Trust Framework 1.0 enforcement (September 1 — 29 days)** — Kantara Initiative is first accredited CAB; UKAS recognition completion is the final trigger. Watch for any second CAB accreditation or Commission-level certification scheme update. UK CertifID trust mark publication imminent.
- **Microsoft Entra passkeys-by-default / OpenAI hardware-passkey mandate (September 1 — 29 days)** — Two passwordless milestones arriving simultaneously; timing is becoming an active post window.
- **France under-15 social-media age verification (September 1 — 29 days)** — New-account age verification mandatory for platforms in France.
- **EU AI Act Article 50 machine-readable content marking deadline for pre-August 2 GPAI systems (December 2, 2026)** — Transitional relief ends; watch for enforcement guidance from EU AI Office on marking implementation.
- **EUDI wallet-availability deadline (December 24, 2026 — 143 days)** — EU Commission continues to express concern that not all member states will make this deadline.
- **Mercosur cross-border digital ID (Decision 4/2026)** — Awaiting national-congress ratification in Argentina, Brazil, Paraguay, Uruguay.
- **AUSTRAC Tranche 2 enforcement** — Reforms effective July 1, 2026 (lawyers, accountants, real estate). No first enforcement action yet. Watch for AUSTRAC press release or Federal Court filing.

---

## Run summary

- Findings by pillar: P1 Banking: **1** (EU AI Act high-risk AI enforcement live for bank deployments) | P2 EUDI: 0 | P3 Fraud/Deepfakes: **2** (Article 50 Day 1 + GPAI enforcement powers live) | P4 ZKP: 0 | P5 Passwordless: 0 | P6 LATAM: 0 | P7 Identity ecosystem: **1** (OfDIA DVS Annual Report, first-capture) — **Total: 4 findings across 3 pillars**
- Override-worthy: **1** — EU AI Act GPAI + Article 50 dual-enforcement went live August 2; Monday is the Day-1 post window and company page.
- Delta path: research/2026-08-03-cycle-delta.md
