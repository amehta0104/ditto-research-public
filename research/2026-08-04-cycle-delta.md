# Cycle Delta — 2026-08-04

Window: 2026-08-02 → 2026-08-04 (last 48 hours)

Worker note: `ditto-slack-bot.dittobot.workers.dev` continues to return 403 from the session's egress proxy (policy denial, not a credential issue). Skill files sourced from repository baseline and prior deltas. Delta written directly to GitHub via MCP.

---

## Override-worthy this cycle

1. **Cyera acquires Oasis Security for $1B — AI agent identity is now a standalone acquisition category** — The deal (announced August 3) validates the thesis that non-human identity and agentic access governance are converging into a billion-dollar security layer, separate from human IAM. Every bank accelerating AI agent deployment now has a board-level question about their NHI security posture. Account:. Angle: "The first $1B deal in AI agent identity just landed. Cyera bought Oasis Security to own the machine-identity layer. When your agents outnumber your employees, human-centric IAM is the wrong stack."

---

## New findings

### Pillar 1: Banking & Payments

(no new PSD3/PSR OJEU publication, EBA press release, ECB SREP action, or AMLA RTS update dated 2026-08-02 to 2026-08-04. PSD3/PSR OJEU publication still outstanding — anticipated September 2026. EU AI Act high-risk AI + Article 50 enforcement live from August 2 fully covered in 2026-08-03 delta. No new in-window print.)

### Pillar 2: EUDI / eIDAS2

(no new ARF release, ENISA certification update, Commission implementing act, or member-state wallet launch announcement dated 2026-08-02 to 2026-08-04. Germany targeting January 2, 2027 launch; Italy already live since December 2024; Spain (Cartera Digital) in implementation. December 24 wallet-availability deadline remains the anchor — 142 days away. No new in-window print.)

### Pillar 3: Fraud / Deepfakes

- **Biometric Update publishes 2026 Deepfake Fraud Detection Market Report — deepfake detection is a $3B market doubling by 2028** — Biometric Update and research partner Goode Intelligence published a 91-page market report in August 2026 establishing deepfake detection as a standalone, growing market category. Key figures: (i) combined voice and facial deepfake check volume is forecast at 6 billion+ in 2026, growing to 12.2 billion by 2028; (ii) annual market revenue exceeds $3 billion in 2026 and is projected to reach $6.1 billion by 2028 — a 2× growth over two years; (iii) the report frames deepfake detection as transitioning from a niche anti-spoofing add-on to a "foundational layer of digital trust" embedded across the identity stack. For Ditto: this is the first major market-sizing publication to quantify the deepfake detection category at scale, and the $3B → $6.1B trajectory positions any vendor with liveness, injection-attack detection, or provenance capabilities inside a fast-growing procurement category. Useful as a market-sizing anchor on the identity-threat-investment spectrum.
  - Source: https://www.biometricupdate.com/202608/biometric-update-publishes-2026-deepfake-fraud-detection-market-report
  - Date: 2026-08 (August 2026 publication; exact date within month unconfirmed)

### Pillar 4: ZKPs in practice

(no new bank ZKP pilot, OpenID4VP/VCI deployment announcement, or selective-disclosure mDL milestone dated 2026-08-02 to 2026-08-04. EUDI wallet ARF v3.0 Functional Conformance Assessment Framework (July 21) now formally tests ZKP selective-disclosure — already anchored in July 30 delta. No new in-window print.)

### Pillar 5: Passwordless / split-key

(no new FIDO Alliance spec release, regulator OTP-sunset announcement, or major bank passkey mandate dated 2026-08-02 to 2026-08-04. Microsoft Entra passkeys-by-default + OTP retirement and OpenAI hardware-passkey mandate both September 1 — 28 days away. France under-15 new-account age verification also September 1. No new in-window print.)

### Pillar 6: LATAM

(no new CNBV, Superfinanciera, CMF, SBS, or BCB regulatory action dated 2026-08-02 to 2026-08-04. No Pix/Drex update in window. No new in-window print.)

### Pillar 7: Identity ecosystem

- **Cyera acquires Oasis Security for $1B to own the AI agent identity layer (August 3, 2026)** — Cyera, a data security platform ($2.3B total funding, $150M+ ARR), announced the acquisition of Oasis Security — a specialist in non-human identity (NHI) and machine-identity governance — for $1 billion. The deal thesis: as autonomous AI agents proliferate across enterprises, securing the identity layer for machines, APIs, and agents is becoming as critical as human IAM. Cyera plans to integrate Oasis's technology into a unified identity and data security platform. Shared investors (Accel, Cyberstarts) supported the deal. For Ditto: this is the first $1B+ acquisition in the NHI/agentic identity category, arriving less than 48 hours after the EU AI Act GPAI enforcement powers went live. The signal is structural: regulated-industry enterprises (banks, fintechs) are actively acquiring machine-identity governance capabilities as AI agent deployment accelerates — a convergence of AI Act compliance pressure and operational security need that creates demand for identity vendors who can cover both human and non-human identity surfaces.
  - Source: https://theaiinsider.tech/2026/08/03/cyera-to-acquire-oasis-security-for-1b-to-bolster-ai-agent-security/
  - Date: 2026-08-03

- **Daon patents AI agent authorization "three-layer trust stack" — third patent in governance series (first capture)** — Daon's third US patent in its AI agent governance series ("Methods and Systems for Authorizing Invocation of a Tool by an Autonomous Artificial Intelligence Agent") was issued July 21, 2026 and publicly announced July 28; featured in the Think Digital Partners Global Roundup on August 3, 2026 (first capture — not in prior deltas). The patent describes a three-layer authorization check triggered each time an AI agent attempts to invoke a tool or API: (1) is the agent still linked to the authorised human identity; (2) is the agent behaving within expected parameters; (3) does the runtime context (action, resource, scope, session, execution environment) match the permitted operation. The system issues per-action authorisations rather than session-level permission grants — treating each agent API call as a distinct identity event. For Ditto: the Daon pattern illustrates the emerging demand for identity verification that is continuous, context-aware, and machine-readable rather than point-in-time and human-readable. This is the Ditto split-key/distributed verification model applied to the agent layer — an angle can own before competitors frame it as "agent IAM."
  - Source: https://www.biometricupdate.com/202607/daon-expands-ai-agent-governance-patent-portfolio
  - Source: https://www.daon.com/resource/daon-secures-third-patent-advancing-ai-agent-governance-in-regulated-industries/
  - Source: https://www.thinkdigitalpartners.com/news/2026/08/03/digital-identity-global-roundup-279/
  - Date: 2026-07-28 (announcement); 2026-08-03 (first-capture via Think Digital roundup; not in prior deltas)

---

## Next-cycle anchors (updated)

- **Ofcom post-July-31 enforcement watch** — Deadline passed July 31. No named enforcement action found as of August 4. Watch for Ofcom press release or investigation opening. Any named enforcement is a UK identity-verification demand signal and company page.
- **AUSTRAC Tranche 2 post-July-1 enforcement watch** — Three full weeks since enforcement began (July 1). Still no Federal Court filing or civil penalty notice found. Watch each cycle.
- **PSD3/PSR OJEU publication** — Still outstanding; anticipated September 2026. European Parliament ECON urged adoption by September at latest. Search each cycle.
- **UK DVS Trust Framework 1.0 enforcement (September 1 — 28 days)** — Kantara Initiative is first accredited CAB. Watch for second CAB accreditation or UK CertifID trust mark publication.
- **Microsoft Entra passkeys-by-default + SMS/voice OTP retirement (September 1 — 28 days)** — Hard date now <30 days. Active /company posting window. Posting opportunity opening.
- **France under-15 social-media new-account age verification (September 1 — 28 days)** — Note: the mandatory platform age verification mechanism was removed from the final law text (July 21) — enforcement now delegated entirely to CNIL/DSA framework. Angle: the September 1 deadline is real, but the verification mandate has no teeth without platform compulsion. UK DVS Trust Framework and Online Safety Act are the stronger enforcement models.
- **EUDI wallet-availability deadline (December 24, 2026 — 142 days)** — Watch for any member-state launch announcement or Commission deadline-risk statement.
- **EU AI Act Article 50 machine-readable content marking deadline for pre-August 2 GPAI systems (December 2, 2026)** — Transitional relief ends; watch for EU AI Office implementation guidance.
- **Mercosur cross-border digital ID (Decision 4/2026)** — Awaiting national-congress ratification in Argentina, Brazil, Paraguay, Uruguay.
- **September NHI/agentic identity watch** — Cyera × Oasis $1B deal (Aug 3) and Daon's three-patent governance series signal that AI agent identity is emerging as a distinct market category. Watch for additional M&A, analyst coverage (KuppingerCole NHI/ITDR), or EU AI Act GPAI compliance guidance that names agent identity as a control requirement.

---

## Run summary

- Findings by pillar: P1 Banking: 0 | P2 EUDI: 0 | P3 Fraud/Deepfakes: **1** (Biometric Update 2026 Deepfake Fraud Detection Market Report — $3B→$6.1B) | P4 ZKP: 0 | P5 Passwordless: 0 | P6 LATAM: 0 | P7 Identity ecosystem: **2** (Cyera×Oasis $1B + Daon AI agent patent #3 first-capture) — **Total: 3 findings across 2 pillars**
- Override-worthy: **1** — Cyera × Oasis Security $1B acquisition (August 3, 2026); validates AI agent/NHI identity as a standalone billion-dollar acquisition category, arriving <48h after EU AI Act GPAI enforcement went live.
- Delta path: research/2026-08-04-cycle-delta.md
