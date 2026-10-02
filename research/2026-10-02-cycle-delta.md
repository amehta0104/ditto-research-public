# Cycle Delta — 2026-10-02

Window: 2026-09-29 → 2026-10-02 (last 72 hours, Friday run)

## Provenance and integrity notes

- The worker API was reachable. The brand brief, competitors list and pillar guides were fetched from the worker. Deduplication was checked against the 2026-05-06 baseline and the 25 most recent deltas (through 2026-10-01).
- The effective new surface is **2026-10-01 and 2026-10-02**. Items dated 09-29/09-30 were included only after confirming that no prior delta covers them.
- **Update to the 2026-10-01 delta (AMLA CDD RTS):** the 10-01 delta said "no AMLA press release was indexed at run time". AMLA did publish one, dated **2026-10-01** ("AMLA finalises key standards for the private sector"). It confirms three final RTS: business relationships/linked transactions, CDD, and group-wide. It also confirms application **six months after entry into force**, with one carve-out: the standards apply to **football agents and professional football clubs from 2029-07-10**. AML Intelligence (10-01) frames this as a "grace period"; the detail is paywalled and not verified. This is not counted as a new finding.
  - Source: https://www.amla.europa.eu/press-release-amla-finalises-key-standards-private-sector_en
- **Checked and rejected (out of window):**
  - **RATHat** Android banker (Cleafy Labs): the primary is dated **2026-09-28**, and The Hacker News covered it the same week. Prior deltas did not log it. Details: MaaS, nearly 100 panel deployments since April 2026, targets Europe/LATAM/SE Asia, abuses Accessibility to enable wireless ADB for shell access outside the Android permission model, and uses Gemini to read the UI tree and to rank victims by estimated bank balance. It is one day outside the window, so it is not counted. The drafter may still use it from the primary (https://www.cleafy.com/cleafy-labs/from-blackcat-to-panda-workshop-inside-the-evolving-c2-panel-behind-rathat) if Mobile Trust needs a hook.
  - **Tech Times (10-01), "EUDI tracking protections quietly weakened":** a re-run of the EDRi March 2026 analysis ("prevent" → "hinder" linkability). No new facts.
- **Noted, not counted:**
  - **Okta** AI agent runtime gateway (Oktane 2026, around 10-01). The SC Media brief returned 403 and the primary was not verified. Workforce/agent IAM, adjacent to Ditto's lane.
  - **Ofcom** provisional notices to Web Prime / Porntrex: already noted in the 10-01 delta.
  - **Naples accountants' Namirial professional wallet** (10-01). A small-scale professional-credential deployment.
- **PSD3/PSR OJEU:** still no Official Journal notice. Next check is Monday 2026-10-05.

## Override-worthy this cycle

1. **Mastercard's Agent Pay now scores whether a payment was initiated by an AI agent, and it names "identity" as the first of five trust layers.** The US-test probability score is paired with Skyfire's "Know Your Agent" verification and Cloudflare web signals. Account: / company. Angle: "KYC took 20 years to standardise. KYA is being written by card networks in 2026. Who verifies the agent, and who verifies the human who delegated to it?"

## New findings

### Pillar 1: Banking & Payments

(no new material in window. The AMLA press-release update is in the provenance notes.)

### Pillar 2: Identity orchestration

- **Mastercard expanded its Agent Pay trust framework to five areas (identity, intent, controls, execution and intelligence) and began US testing of a service that estimates the probability an AI agent initiated a transaction.**
  - **Partners:**
    - Skyfire contributes agent-identity verification through a "Know Your Agent" approach.
    - Cloudflare combines web-level and payment-network signals "in a privacy-preserving environment".
    - ID Tech also reports Google (Verifiable Intent) and Fastly (verified agent identity at the edge) as collaborators.
  - **Planned signals:** agent behaviour, merchant risk, transaction patterns, credential risk and consumer propensity.
  - **Quote:** Ann Johnson, EVP Security Solutions: "AI agents will make commerce more intuitive, efficient and personal — but only if people and businesses can trust the systems acting on their behalf."

  **Why it matters:** the card networks are defining agent identity as an orchestration problem: who is acting, under whose authority, with what intent, plus a risk score. That is the same shape as human identity orchestration. It also follows IDEMIA's agentic-commerce passkey anchor (09-30 delta), so two of the big payment and identity players moved in one week. The open gap is binding the agent to a verified, consenting human, which is where wallet credentials and split-key authentication fit.
  - Source (primary): https://www.mastercard.com/global/en/news-and-trends/press/2026/september/new-trust-and-intelligence-services.html
  - Source: https://thepaypers.com/payments/news/mastercard-expands-agent-pay-with-trust-and-intelligence-services
  - Source: https://idtechwire.com/mastercard-tests-intelligence-service-to-identify-ai-agent-transactions/
  - Date: 2026-09-30 (announcement, per CU Today); 2026-10-01 (ID Tech)
  - **Drafting cautions:**
    - The probability score is in *US testing*. The other signals are planned, not live.
    - The mastercard.com primary returned 403 at run time. The quotes and framework list come via The Paypers / CU Today / ID Tech.
    - Google/Fastly involvement is reported by ID Tech only; verify before naming them.

### Pillar 3: EUDI / eIDAS2

(no new material in window. Finland/Bulgaria were covered 10-01.)

### Pillar 4: KYC / AML compliance

(no new material beyond the AMLA press-release update in the provenance notes.)

### Pillar 5: Customer onboarding

- **A travel-industry coalition is lobbying the EU to use the Digital Omnibus to legislate for *voluntary* biometric verification across the passenger journey.** The coalition calls itself the "Responsible Biometrics Travel Industry Coalition" and launched **2026-10-01**. Members are ACI EUROPE, Amadeus, IATA, IDEMIA Public Security and SITA.
  - **Asks:** technology-neutral rules, passenger choice with non-biometric alternatives, and the right to withdraw consent and delete biometric data at any time.
  - **Supporting stat:** 74% of travellers were willing to share biometric data in place of showing a passport or boarding pass (IATA Global Passenger Survey).

  **Why it matters:** travel is one of Ditto's five target industries. The industry is asking Brussels for a legal basis for biometric journeys, which tells you the current GDPR basis is seen as a blocker. The ask is consent-based, revocable, with an alternative path: verify once, reuse with consent. That is Ditto's "verify once, reuse trust" line applied to travel. The release does not mention the EUDI wallet, which is an open angle.
  - Source (primary): https://www.aci-europe.org/press-release/618-new-travel-industry-coalition-calls-for-eu-digital-omnibus-to-enable-secure-seamless-biometric-journeys.html
  - Source: https://idtechwire.com/travel-industry-coalition-seeks-eu-rules-for-voluntary-biometric-journeys/
  - Date: 2026-10-01
  - **Drafting caution:** IDEMIA is a coalition member and an adjacent competitor. This is lobbying, not a legislative proposal.

### Pillar 6: Identity verification (IDV)

- **UK OfDIA is inviting registered Digital Verification Service providers to test a machine-readable DVS register, so services can check each other's certified status automatically.** OfDIA posted the invitation on its blog on **2026-09-29**. Two models are under test:
  - **API model:** X.509 certificates, OpenID Federation and mTLS.
  - **Credential/wallet model:** ISO/IEC 18013-5 validation using VICAL and RICAL signed lists.

  Onboarding tests and DVSP readiness interviews start in **October 2026**; technical testing of both models follows "later in 2026". **Why it matters:** this is the trust-list plumbing the UK framework has lacked. Certification becomes something a relying party can verify at runtime, not a logo on a website. It mirrors the EUDI trusted-list architecture, and the choice of OpenID Federation and 18013-5 signals convergence with EU/US standards. Any certified UK DVSP, including vendors with UK certification ambitions, will need to integrate.
  - Source (primary): https://enablingdigitalidentity.blog.gov.uk/2026/09/29/help-us-test-the-dvs-registers-machine-readable-infrastructure/
  - Source: https://idtechwire.com/uk-invites-providers-to-test-machine-readable-digital-identity-register/
  - Date: 2026-09-29 (OfDIA); 2026-10-01 (reported)
  - **Drafting caution:** read alongside the 09-04 delta (primary credentials held exclusively in GOV.UK Wallet). Do not call this a launch; it is testing. ID Tech names the body "Office for Digital Identities and Attributes (OfDIA)".

- **A proposed BIPA class action filed in San Francisco County Superior Court targets an AI company's selfie-plus-ID verification flow run through Persona. It shows that IDV liability falls on the relying party, not only the vendor.** Plaintiff Jose Enrique Colon (Chicago) alleges he was locked out of his account until he submitted driver's licence images and a live facial photo through Persona. He alleges no written retention disclosure before collection (BIPA §15(b)(2)) and no published retention/destruction schedule (§15(a)). He seeks $1,000–$5,000 per violation for a class of Illinois users. The defendant is Anthropic, over Claude's ID checks.

  **Why it matters:** this follows the Meta smart-glasses BIPA suit (09-08 delta). Plaintiffs are now targeting *consumer platforms that bolt on third-party IDV*, not just the biometric vendor. Data minimisation (verify, keep a proof, delete the template) moves from a privacy talking point to a litigation-cost argument. That supports Ditto's ZKP/attribute-proof positioning.
  - Source: https://idtechwire.com/anthropic-faces-illinois-biometric-privacy-claims-over-claude-id-checks/
  - Date: 2026-10-01 (reported)
  - **Drafting cautions:**
    - These are allegations in a complaint, with no ruling.
    - The case number is not reported; the court filing has not been verified.
    - Persona is a named competitor; do not attack it. The point is about where liability lands, not vendor quality.
    - Avoid naming the defendant in a post unless needed; "a major AI platform" carries the point.

### Pillar 7: Fraud / Deepfakes

- **The 2026 Treasury Dragons / nsKnox Payment Fraud Index:**
  - 76% of corporate treasury teams suffered at least one payment-fraud incident in the past year (up from 73%), and 44% faced multiple attacks.
  - 53% saw confirmed or suspected deepfake-related attempts, typically email plus voice/video follow-up, but only 44% have formal AI-fraud policies.
  - Only 18% continuously revalidate supplier bank details.
  - 41% still receive sensitive payment data by email.
  - 48% have no dedicated payment-fraud prevention system.
  - nsKnox CEO Nithai Barzam: "The problem is no longer awareness—it's verification."

  **Why it matters:** this is the B2B half of the Fideuram story. Multi-channel impersonation beats processes that rely on recognising a voice or an email address. Cryptographic verification of the counterparty is the answer, not more training.
  - Source (primary): https://www.globenewswire.com/news-release/2026/10/01/3372952/0/en/76-of-treasury-teams-hit-by-fraud-as-deepfake-attacks-rise-treasury-dragons-nsknox-2026-index-finds.html
  - Date: 2026-10-01
  - **Drafting caution:** the sample is **104 respondents**, from a vendor-sponsored survey of corporate treasury (not banks). Use it as directional only; do not headline "76% of companies".

### Pillar 8: Mobile trust & app security

(no new material in window. RATHat is dated 09-28 and is rejected as out of window; see the provenance notes for the primary in case the drafter needs it.)

### Pillar 9: Passwordless / split-key

(no new material in window.)

### Pillar 10: ZKPs in practice

- **South Africa's Home Affairs demonstrated a working prototype of a smartphone digital ID with holder-controlled selective disclosure.** Minister Leon Schreiber ran the demo on **2026-10-01** at Constitution Hill, Johannesburg, using his own population-register identity in the MyMzansi app.
  - **How it works:** a QR-based exchange in which the verifier requests attributes. The holder approves or refuses, picks fields to release (name, date of birth, nationality, ID number, photo and others), and can revoke verifier access in real time. The demo included rejecting an illegitimate request and an immigration officer confirming nationality only.
  - **Timeline:** hosting infrastructure due by March 2027, public credential issuance in FY2027/28. Green ID books stop being produced 2027-03-31 and lose validity 2028-03-31.

  **Why it matters:** this is a clean, non-EU example of a government building selective disclosure in from the prototype, not bolting it on later. It is useful to show that "share only the attribute" is becoming the default design for national digital ID, not a European idiosyncrasy.
  - Source: https://idtechwire.com/south-africa-demonstrates-smartphone-digital-id-with-selective-sharing/
  - Source: https://www.ewn.co.za/home-affairs-quantum-leap-schreiber-unveils-1st-working-prototype-of-digital-id
  - Source: https://iol.co.za/capetimes/news/2026-10-01-a-new-digital-id-is-coming-to-south-africa--heres-how-it-works/
  - Date: 2026-10-01
  - **Drafting cautions:**
    - Selective disclosure is not the same as ZKP. No source says ZKPs are used; do not claim it.
    - Call it a prototype, with no launch date.
    - The green-ID-book dates are from EWN; verify against a DHA primary before quoting.

### Pillar 11: Age assurance & privacy attributes

(no new material in window. Ofcom's Web Prime / Porntrex notices were noted 10-01. Ofcom's over-16 rapid assessment is due to Parliament by end-October.)

## Open watch items

- **AMLA CDD RTS:** Commission adoption and OJ publication (application is +6 months; football carve-out from 2029-07-10). Get the AML Intelligence "grace period" detail from a non-paywalled source.
- **Mastercard Agent Pay:** results of the US test; first issuer using the probability score; Skyfire KYA uptake.
- **UK DVS register:** October onboarding tests; the later-2026 technical tests.
- **BIPA vs IDV relying parties:** case number and the defendant's response.
- **Early November 2026:** CNBV Anexo 71 biometric compliance deadline.
- **2026-10-19/21:** Authenticate 2026, Carlsbad (FIDO announcements likely).
- **2026-10-26:** BCB MED 2.0 inter-institution step.
- **2026-10-29/30:** EUDI Launchpad 2026, Brussels.
- **End-October:** Ofcom over-16 age-assurance rapid assessment to Parliament.
- **2026-10-31:** ECB SSM-2026-0301 action-plan deadline.
- **2026-11-18:** EUDI ARF Iteration 6 closes.
- **2026-12-24:** EUDI wallet-availability deadline (83 days).
- **PSD3/PSR OJEU:** still unpublished. Next check is Monday 2026-10-05.
