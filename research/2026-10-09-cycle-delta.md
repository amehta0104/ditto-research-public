# Cycle Delta — 2026-10-09

Window: 2026-10-06 → 2026-10-09 (last 72 hours, weekend included)

> **⚠ Operational note:** The worker at `ditto-slack-bot.dittobot.workers.dev` was unreachable from this cloud environment (egress proxy policy blocked the Cloudflare Workers domain). Skill files and prior deltas could not be read to check for duplication. This delta was pushed directly to GitHub as a fallback. Deduplication against prior baseline/deltas was not possible this cycle — the drafter should check before using findings.

---

## Override-worthy this cycle

1. **AMLA final draft CDD regulatory technical standards submitted to the European Commission** — AMLA published and sent its final draft RTS on customer due diligence (Article 22) to the Commission on 30 September 2026; the standards place EUDI Wallet and eID at "substantial/high" assurance at the top of the identity-verification compliance hierarchy, and explicitly require liveness detection and anti-spoofing in document-based checks. Account: / company. Angle: Ditto's wallet-native verification stack is positioned precisely at the tier AMLA now codifies as the gold standard.

2. **Germany's d-you EUDI wallet draws heavy Bundestag criticism ahead of January 2, 2027 launch** — A formal hearing produced strong pushback on the design of Germany's planned national EUDI wallet, raising questions about privacy, vendor lock-in, and timeline realism. Account:. Angle: Germany is the EU's largest relying-party market; implementation slippage or redesign directly affects the eIDAS2 rollout velocity every identity vendor has been pricing in.

---

## New findings

### Pillar 1: Banking & Payments

- **AMLA final draft CDD RTS: eID/EUDI Wallet codified as top-tier identity compliance method** — AMLA sent its final draft customer due diligence technical standards to the European Commission on 30 September 2026 (date is 6 days before this window; industry analysis and vendor reaction appeared in-window). Article 22 creates a three-tier identity-verification hierarchy: (1) eID/EUDI Wallet at "substantial" or "high" assurance, (2) qualified electronic signature, (3) document-based checks. Liveness detection and anti-spoofing are expected to be mandatory in the document-based tier. AMLR applies from 10 July 2027; AMLA is reported to have delivered only 24 of its 40 mandates in 2026, signalling implementation pressure. The standard is still a draft pending Commission adoption.
  - Source: https://joinble.io/blog/amla-cdd-rts-identity-verification-2026
  - Date: 2026-09-30 (analysis week of 2026-10-06)

- **EU AMLR sets new remote identity verification standards** — Industry coverage in the week of October 6 highlighted the AMLR's Article 22(6) as explicitly recognising eID, EUDI Wallet, and QES as equivalent to face-to-face verification; document-based remote checks are permitted but must meet ETSI TS 119 461. This is the first clear EU AML-level endorsement of wallet-based KYC.
  - Source: https://www.biometricupdate.com/202610/ (AMLR item in October feed)
  - Date: 2026-10-06 (approx.)

---

### Pillar 2: EUDI / eIDAS2

- **Germany d-you EUDI wallet: Bundestag hearing draws heavy criticism** — A parliamentary hearing brought strong criticism of the design and privacy architecture of Germany's planned national EUDI wallet (d-you), scheduled to launch to the public on 2 January 2027. Germany, alongside Denmark and Italy, is one of the most-watched national implementations because of market size. Criticism centred on data centralisation and vendor dependency. The hearing outcome could force a redesign before launch.
  - Source: https://heise.de/en/news/EUDI-Wallet-Hearing-with-heavy-criticism-of-the-planned-d-you-wallet-11478144.html
  - Date: 2026-10 (within window)

- **Analysis: where commercial value is actually created around the EUDI Wallet** — Biometric Update published a market analysis arguing that the commercial opportunity around the EUDI Wallet concentrates in identity attribute attestation (Qualified Electronic Attribute Attestation providers) and identity verification underpinning those attestations — not in building wallets themselves. Argues that relying parties will need a verification layer behind the wallet, not just a wallet reader.
  - Source: https://www.biometricupdate.com/202610/where-commercial-value-can-actually-be-created-around-the-eudi-wallet
  - Date: 2026-10 (within window)

- **FINMA formalises Swiss E-ID for remote account opening; liveness detection required** — FINMA's revised Circular 2016/7 on video and online identification (finalised 2026, following December 2025 consultation) now permits banks to open accounts fully digitally using the Swiss E-ID and mandates liveness and presentation-attack detection controls. Switzerland is outside the EU but tracks eIDAS2 closely; this is an early example of a national regulator mandating liveness as a condition of accepting a government-issued digital ID.
  - Source: https://fidentity.ch/en/news/finma-circular-2016-7-revision-2026-digital-onboarding
  - Date: 2026-10 (industry coverage within window)

- **Euronews, October 6: "The EUDI wallet: building trust, unlocking growth in Europe"** — Op-ed/analysis piece in Euronews (dated October 6) framing the EUDI Wallet as a trust and growth enabler, citing relying-party obligations and the December 2026 wallet availability deadline. Signals mainstream-media visibility of the wallet narrative.
  - Source: https://www.euronews.com/2026/10/06/the-eudi-wallet-building-trust-unlocking-growth-in-europe
  - Date: 2026-10-06

---

### Pillar 3: Fraud / Deepfakes

- **Biometric Update: data breaches make the case for minimising identity data in KYC** — Article published in the week of October 6 argues that repeated large-scale KYC data breaches (storing full document images, selfies, biometric templates) are driving a regulatory and industry shift toward data-minimisation approaches — selective disclosure, attribute attestation rather than raw document storage, and ZKP-based age/identity proofs. Directly supportive of the "verify, don't store" positioning.
  - Source: https://www.biometricupdate.com/202610/data-breaches-make-the-case-for-minimizing-identity-data-in-kyc
  - Date: 2026-10 (within window)

---

### Pillar 4: ZKPs in practice

(no new material)

---

### Pillar 5: Passwordless / split-key

- **GOV.UK One Login adds open banking as an alternative identity-proof method** — The UK's national government sign-in service (227 services, 15M+ proven identities) added bank account information as a route for identity proofing alongside photo ID, per guidance updated January 2026 and confirmed in March 2026 parliamentary answer. Industry coverage in October 2026 frames this as a significant step: a government service treating bank-held identity data as equivalent to document-based proof. Relevant to passwordless/split-key pillar because it demonstrates account-held credentials as a first-class identity anchor.
  - Source: https://sign-in.service.gov.uk/about/roadmap; https://www.gov.uk/guidance/proving-your-identity-with-govuk-one-login-by-answering-security-questions
  - Date: confirmed in force January 2026; in-window industry commentary

---

### Pillar 6: LATAM

- **Brazil: Receita Federal pilots palm-vein biometrics for pedestrian border crossing at Brazil-Paraguay bridge** — The Brazilian Federal Revenue Service launched a palm biometrics pilot for the most-used pedestrian border crossing between Brazil and Paraguay, using palm-vein recognition for traveller identification. First use of palm biometrics in a Brazilian government border context; signals BCB/government appetite for biometric layering.
  - Source: https://www.biometricupdate.com/202610/ (mentioned in October 2026 digest)
  - Date: 2026-10 (within window)

---

### Pillar 7: Identity ecosystem

- **Identis launches North American subsidiary combining biometrics, payments, and digital ID** — Identis, a digital identity and payments firm, announced the launch of a dedicated North American subsidiary, positioning itself as a single stack covering biometric verification, payment-identity binding, and digital credentials. M&A/expansion signal in the identity space.
  - Source: https://www.biometricupdate.com/202610/identis-launches-north-american-subsidiary-combining-biometrics-payments-and-digital-id
  - Date: 2026-10 (within window)
