# Cycle Delta — 2026-07-07

Window: 2026-07-04 → 2026-07-07 (last 72 hours — Monday run, Fri–Mon weekend window)

## Override-worthy this cycle

1. **European Commission formally upgrades eIDAS Dashboard into operational trust hub for EUDI Wallet ecosystem** — The centralized, machine-readable registry of certified relying parties, PID providers, wallet providers, and attribute providers is now live, giving the December 24, 2026 member-state deadline a visible infrastructure backbone. Account:. Angle: "The plumbing is real — Europe's digital identity trust layer went from concept to a live registry this week. Every relying party, every PID provider, every certified wallet now has a public address in the EU's trust framework."

2. **CaixaBank and Visa complete first AI agent payment on card rails in Europe** — Live pilot using Visa's Agentic Ready programme executed a real card transaction initiated by an AI agent on behalf of a human cardholder, with the same tokenization, identity verification, and fraud monitoring applied to conventional payments. Account: / company. Angle: The AI agent identity problem just became concrete — if an agent can spend your money, who verifies the agent is who it says it is?

## New findings

### Pillar 1: Banking & Payments
- **CaixaBank and Visa complete first AI-agent-initiated payment on card rails in Europe** — CaixaBank (Valencia; ~12M cardholders; €5B 2025–2027 AI strategy) announced on July 6 that it completed a live transaction initiated by an AI agent, using Visa's Intelligent Commerce framework and its Agentic Ready programme. The pilot ran on real card data against standard merchant systems, with tokenization, identity verification, and fraud monitoring applied identically to conventional card transactions. Visa's Agentic Ready programme launched in Europe in March 2026; current participating FIs include Barclays, BBVA, CaixaBank, Commerzbank, HSBC UK, ING, Klarna, Lloyds Banking Group, NatWest, Nexi, and Revolut. For Ditto: the moment AI agents can initiate real payments, the identity and authorization layer for agents becomes a financial-services-grade compliance problem — who verified the agent's identity, under whose delegation, and with what audit trail? The split-key and selective-disclosure problems extend to non-human principals.
  - Source: https://www.caixabank.com/en/headlines/news/caixabank-completes-its-first-transaction-initiated-by-an-artificial-intelligence-agent-in-collaboration-with-visa
  - Source: https://idtechwire.com/caixabank-and-visa-complete-an-ai-agent-payment-on-card-rails/
  - Source: https://paymentexpert.com/2026/07/02/visa-agentic-payments-merchants-eu/
  - Date: 2026-07-06

### Pillar 2: EUDI / eIDAS2
- **European Commission expands eIDAS Dashboard into live trust hub for EUDI Wallet ecosystem** — Reported July 6, 2026 (ID Tech Digest; Biometric Update). The EC has formally upgraded the eIDAS Dashboard, operated by DG DIGIT and DG CNECT, into the operational trust infrastructure for the EUDI Wallet: a centralized, machine-readable registry of certified relying parties, PID providers, wallet providers (WRPAC providers), registrars, and registers. Functionalities for the Catalogue of Attributes and Schemes and PuB-EAA providers are in active development. The upgrade provides the cryptographic interoperability and public verification layer that member states need before the December 24, 2026 deadline — each member state must publish its trust information to the Dashboard for the wallet ecosystem to be interoperable. This is the first time the trust-layer plumbing for EUDI is visibly operational, not just planned. For Ditto: every certified relying party and PID provider now has a public address in the EU's trust framework; identity vendors seeking to operate as attribute providers or relying parties in the EUDI ecosystem need to be listed here.
  - Source: https://idtechwire.com/eu-expands-eidas-dashboard-into-trust-hub-for-digital-identity-wallet/
  - Source: https://www.biometricupdate.com/202607/eidas-dashboard-evolving-to-meet-europes-broad-digital-id-ambitions
  - Source: https://ec.europa.eu/digital-building-blocks/sites/spaces/DIGITAL/pages/973932461/eIDAS+Dashboard+expands+its+role+in+Europe+s+Digital+Identity+Trust+Framework
  - Date: 2026-07-06 (reported; Dashboard upgrade ongoing)

### Pillar 3: Fraud / Deepfakes
- **Biometric Update synthesis on global fraud escalation: Liminal + Unico data shows injection attacks now 45.8% of biometric fraud; banks deploying continuous verification as structural response** — A Biometric Update feature published early July 2026 synthesizes a joint intelligence report from Liminal and Unico showing that coordinated, networked fraud is now the dominant attack pattern. Key data: one institution logged 8,065 deepfake attempts in eight months tied to $347 million in verified losses; global fraud losses exceed $400 billion annually; injection attacks (malicious synthetic media injected directly into the video stream before verification occurs, bypassing the camera entirely) represent 45.8% of classified fraud cases; advanced deepfake/manipulated-monitor attacks 23.3%; physical presentation attacks 30.9%. Unico identified a single fraud entity linked to 949 identity documents, targeting 30 different businesses — confirming fraud operates as coordinated B2B-scale campaigns. Deepfake-as-a-service access costs as little as $5. Industry response: banks are moving toward continuous, on-device biometric checks rather than point-in-time verification (YEO Messaging, ReconIQ deploying in U.S. banks; Czechia's Air Bank adding Innovatrics face verification for mobile-app pairing). Synthetic identity fraud now accounts for 11% of global fraud — an eightfold year-over-year increase; projected U.S. unsecured credit losses from synthetic identity exceed $3.1 billion in 2026.
  - Source: https://www.biometricupdate.com/202607/global-fraud-escalation-drives-new-wave-of-biometric-and-continuous-verification-in-banking
  - Source: https://idtechwire.com/unico-network-data-shows-injection-attacks-now-dominate-classified-fraud-report/
  - Source: https://liminal.co/reports/identity-fraud-intelligence-2026
  - Date: 2026-07-04 to 2026-07-06 (featured in ID Tech Digest July 6, 2026)

### Pillar 4: ZKPs in practice
(no new bank ZKP pilot, OpenID4VP/VCI update, or mDL deployment confirmed in window — ZKP-based selective disclosure under eIDAS 2 ARF is operational context but no fresh primary-source announcement July 4–7.)

### Pillar 5: Passwordless / split-key
- **Incode deploys biometric face verification for password resets on the Auth0 Marketplace** — Announced July 6, 2026. Incode released two integrations on Auth0's marketplace that embed biometric identity checks into enterprise authentication flows: (1) **Incode ID Verification** — redirects new first-login users to a government-ID + live-selfie capture flow; liveness-checked and face-matched before account is confirmed; (2) **Incode Face Auth Reset** — interrupts the Auth0 password-reset flow and requires a live face scan matched 1:1 against the verified identity captured at enrollment; attackers with stolen credentials and email access cannot pass this check. Both integrations are live in the Auth0 Marketplace. For Ditto: this is the biometric-replaces-knowledge-factor pattern applied to the highest-risk moment in passwordless flows — account recovery. The integration path (biometric vendor → IAM marketplace → enterprise app) is the deployment model for zero-trust, phishing-resistant credential resets at scale.
  - Source: https://www.biometricupdate.com/202607/incode-adds-biometric-verification-to-auth0-password-resets
  - Source: https://idtechwire.com/incode-brings-biometric-verification-and-face-based-resets-to-auth0/
  - Source: https://auth0.com/blog/auth0-incode-bringing-biometric-identity-to-logins/
  - Date: 2026-07-06

### Pillar 6: LATAM
(no new material confirmed in window July 4–7 — Colombia Open Finance Decree 368 signed April 7, outside window; Brazil DeCripto/Pix/Drex updates covered in prior deltas; no new CNBV, Superfinanciera, CMF, SBS publication confirmed this weekend.)

### Pillar 7: Identity ecosystem
- **FSB AI Sound Practices outreach event held July 7 (today)** — The Financial Stability Board hosted its virtual outreach event on "Sound Practices for Responsible Adoption of AI" on July 7, 2026 (13:00–15:00 CEST), as part of its consultation on 12 sound practices covering organisation-wide AI governance, risk management across AI development and deployment stages, and management of AI-related cyber/ICT/third-party risks. Consultation responses due July 22, 2026; final report to G20 Finance Ministers in October 2026. The 12 practices apply to financial institutions globally and directly address AI use in KYC, fraud detection, and identity verification workflows. For Ditto: the FSB sound practices will become the G20 baseline for what "responsible AI in financial services" means, and AI-driven identity verification sits squarely in scope — financial institutions citing these practices when procuring IDV tools will expect vendors to document AI governance, bias testing, model explainability, and third-party risk controls.
  - Source: https://www.fsb.org/2026/06/sound-practices-for-responsible-adoption-of-artificial-intelligence-ai-consultation-report/
  - Source: https://www.fsb.org/2026/06/virtual-outreach-event-on-fsb-sound-practices-for-financial-institutions-responsible-adoption-of-artificial-intelligence/
  - Date: 2026-07-07 (event held today; no outcomes published yet — publication October 2026)

---

## Next-cycle anchors (updated)

- **AMLA 23 RTS/ITS → Commission (July 10)** — 3 DAYS. CDD standards, business-relationship standards, harmonised supervision ITS, and sanctions/breaches RTS all legally due to the EC. The most important KYC/identity regulatory submission of July 2026. Watch amla.europa.eu for post-submission publication.
- **Ofcom Categorisation Register publication (July 2026)** — Expected this month; identifies Category 1/2A/2B services under the Online Safety Act, triggering age-verification and user-empowerment duties on the largest platforms.
- **Ofcom statutory age-assurance effectiveness report (by July 17)** — 10 days. First-year statutory assessment of how UK platforms are implementing age-assurance under the Online Safety Act.
- **EU AI Act Code of Practice signatory deadline (July 22, 18:00 CEST)** — 15 days. Sign for presumption of conformity with Article 50 deepfake/AI-content disclosure obligations. Voluntary but functions as the compliance safe harbour.
- **FSB AI Sound Practices consultation deadline (July 22)** — 15 days.
- **EU AI Act Article 50 enforcement (August 2)** — 26 days. Deepfake labelling, chatbot disclosure, AI-content marking become binding; €15M or 3% global turnover fines.
- **AUSTRAC Tranche 2 enrolment deadline (July 29)** — 22 days. ~100,000 newly in-scope professional-service entities must enrol.
- **UK DVS Trust Framework 1.0 enforcement (September 1)** — 56 days.
- **EUDI Wallet hard deadline (December 24, 2026)** — All EU member states must make wallet available. eIDAS Dashboard Trust Hub now operational as the enabling infrastructure.
- **PSD3/PSR OJEU publication** — H2 2026; no confirmed date.
- **FATF seventh targeted update on VA/VASP Standards** — Approved June plenary; not yet published.

---

## Run summary

- Findings count by pillar: **P1 Banking & Payments: 1** (CaixaBank + Visa first AI-agent payment on card rails, July 6) | **P2 EUDI/eIDAS2: 1** (eIDAS Dashboard → EUDI Trust Hub live, July 6) | **P3 Fraud/Deepfakes: 1** (Liminal + Unico synthesis — injection attacks 45.8% of biometric fraud, banks moving to continuous verification) | **P4 ZKPs: 0** | **P5 Passwordless: 1** (Incode + Auth0 biometric face-reset, July 6) | **P6 LATAM: 0** | **P7 Identity ecosystem: 1** (FSB AI Sound Practices outreach event held today July 7) → **Total: 5 findings across 5 pillars**
- Override-worthy: **2** — (1) eIDAS Dashboard → EUDI Trust Hub: centralized, machine-readable relying-party/PID/wallet registry now live; the infrastructure layer for December 24, 2026 becomes visible. Account:. (2) CaixaBank + Visa first AI-agent payment on card rails: identity/auth problem for AI agents in financial services becomes concrete and real. Account: / company.
- Delta path: `research/2026-07-07-cycle-delta.md`

---

_Note: Worker API (ditto-slack-bot.dittobot.workers.dev) is blocked by the environment's network egress allowlist (403 policy denial on CONNECT); skill/pillar files were not loaded from the worker. Delta written directly to GitHub via MCP. To restore full skill-file context, add `ditto-slack-bot.dittobot.workers.dev` to the environment's network egress allowlist._
