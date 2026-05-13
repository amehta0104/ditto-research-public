# Cycle Delta — 2026-05-13

Window: 2026-05-11 → 2026-05-13 (last 48 hours)

## Override-worthy this cycle

1. **Romania signs MoU with Mastercard to deliver EU-aligned national digital identity wallet — 11 May 2026** — Government memorandum adopted Monday under a five-year Digital Partnership programme. The Romanian state retains ownership and administration of the wallet ecosystem; Belgian-incorporated Mastercard Europe SA is "limited to serving as a technical service provider." The arrangement carries no cost to the public budget. Angle: "EUDI delivery doesn't have to mean public-builds-everything. Romania just put a card scheme inside its national wallet stack — owned by the state, operated by the private sector — six months before the December deadline. That's the shape every member state running behind schedule is going to study."

2. **France Identité iOS sandbox ships ZKP-based unlinkable age verification — articles 12–13 May 2026** — France's national digital ID app now supports OID4VP 1.0 on iOS and Android; its privacy-preserving age-check uses Zero-Knowledge Proof cryptography so a relying party learns only "user is over 18" — no identity, date of birth, or issuer reference is revealed — and responses are cryptographically unlinkable across verifiers. First EU member-state national wallet with live ZK age-verification coverage across both mobile ecosystems. Angle: "France just shipped the ZKP-based age check privacy advocates said was too hard to deploy in practice. A national government app proves over-18 with no data residue and no cross-site tracking. That's not a pilot; that's a live government sandbox."

---

## New findings

### Pillar 1: Banking & Payments

(no new material in window — PSD3/PSR remains awaiting Parliament plenary vote following 5 May ECON adoption; OJEU publication still anticipated June/July 2026 with possible slip to September. FCA/PSR APP-fraud framework review still expected Q2 2026 with no fresh announcement this cycle. No new DORA enforcement actions disclosed in window — ECB/ESA oversight activity continues but no formal CTPP designation events or penalty announcements.)

### Pillar 2: Identity orchestration

- **UK King's Speech (13 May 2026): Digital Identity and Authentication Bill formally confirmed on UK legislative agenda** — The State Opening of Parliament confirmed the Digital Identity and Authentication Bill among 12 priority bills for the 2026–27 session. The bill will be introduced "later this year"; voluntary digital ID intended to be available to those who want it by 2029. Police Biometrics Bill also confirmed in the same Speech. Context: the 05-08 delta flagged this as override-worthy at announcement (7 May); today's delivery moves the bill from "planned" to "formally tabled" — now an active piece of UK primary legislation, not a government consultation commitment. The government's stated position remains unchanged: voluntary, anti-scope-creep protections on the face of the bill, no service conditioning.
  - Source: https://www.parliament.uk/business/news/2026/may-2026/state-opening-of-parliament-2026/
  - Source: https://lordslibrary.parliament.uk/research-briefings/lln-2026-0020/
  - Date: 2026-05-13

- **ID4Africa 2026 AGM opens in Abidjan (12–15 May 2026)** — Africa's premier annual digital-identity conference convened 2,300+ delegates from 100+ countries (80% senior government officials) at Parc des Expositions d'Abidjan, Côte d'Ivoire. Theme: "Digital Identity: From DPI to Digital Public Ecosystems." The conference marks a deliberate conceptual shift: from deploying identity infrastructure (Digital Public Infrastructure) to sustaining identity governance ecosystems (Digital Public Ecosystems), with governance, interoperability, and long-term legitimacy as the 2026 priorities. Country playbooks from 13 African identity authorities shared live on 12 May. 70% of speakers are African — highest proportion in the event's 12-year history. Not a regulatory finding; useful as ecosystem signal that the global identity community has moved from "can we build it?" to "how do we make it last?"
  - Source: https://www.biometricupdate.com/202605/building-digital-id-systems-that-last-african-countries-share-experiences-as-id4africa-2026-opens
  - Source: https://www.biometricupdate.com/202605/id4africa-2026-shifts-focus-to-digital-identity-ecosystems-and-sustainability
  - Date: 2026-05-12

(KuppingerCole EIC 2026 opens 19 May Berlin; agenda confirms Identity Fabrics as Martin Kuppinger's opening-keynote theme and a dedicated "Orchestrating Non-Human Identity at Scale" session, but no pre-event vendor announcements landed in window. No fresh analyst publications or category M&A in window.)

### Pillar 3: EUDI / eIDAS2

- **Romania signs MoU with Mastercard for EU-aligned national digital identity wallet — 11 May 2026** — The Romanian government adopted a memorandum on Monday establishing a five-year Digital Partnership programme with Mastercard. Mastercard Europe SA serves as technical service provider only; the Romanian state retains ownership and administration of the ecosystem. The solution will be interoperable across the EU, in line with the EUDI Wallet framework. No cost to the public budget. The signing lands six months before the December 2026 member-state deadline and follows Romania's earlier September 2025 risk of a €310M EU fine for cutting e-ID plans — context the new partnership is designed to unwind. Practical significance for an identity-orchestration vendor: the "public ownership, private operation" split is now an explicit member-state pattern for EUDI delivery, not a hypothetical.
  - Source: https://www.biometricupdate.com/202605/romania-signs-mastercard-deal-for-eu-aligned-digital-identity-wallet
  - Source: https://identityweek.net/romania-signs-mou-with-mastercard-deploying-the-eudi-wallet/
  - Source: https://actmedia.eu/financial-and-banking/romania-to-conclude-memorandum-with-mastercard-implementing-european-digital-identity-wallet/119503
  - Date: 2026-05-11

- **France Identité iOS sandbox launched with OID4VP 1.0 and ZKP unlinkable age verification (articles 12–13 May 2026; sandbox launched 7 May; not captured in prior deltas)** — France Identité's sandbox build is now available on iOS and Android, supporting OID4VP 1.0 for interoperability testing with relying parties preparing for the EUDI Wallet. France is one of seven front-runner member states piloting the EU Age Verification Solution. The sandbox implements ZKP-based selective disclosure: a relying party asks for proof of an age threshold; the app presents only that attribute with no date of birth, no issuer reference, and cryptographically unlinkable responses across verifiers (no cross-service tracking by design). EUDI relevance: demonstrates that relying-party integration with a government-issued wallet is testable end-to-end today, not a 2027 aspiration; and the ZKP age-check is a live demonstration that privacy-preserving selective disclosure is deployable in a national government app.
  - Source: https://www.biometricupdate.com/202605/france-identite-app-launches-sandbox-for-ios-proves-age-check-privacy-bona-fides
  - Source: https://idtechwire.com/france-identite-adds-ios-sandbox-and-tests-privacy-preserving-age-verification/
  - Source: https://mobileidworld.com/france-identite-brings-ios-users-into-eudi-wallet-age-verification-testing/
  - Date: 2026-05-12 (reporting); iOS sandbox available from 2026-05-07

- **Jordan grants full legal status to Sanad digital ID under amended Civil Status Law — reported 11 May 2026** — Sanad now legally equivalent to physical national ID cards under Article 39 amendment, with both public bodies and private sector entities (banking, telecoms, regulated services) required to accept it. 2.6M citizens activated, 600K of those since January 2026. House of Representatives passed the amendment by majority vote on 13 April; publication and operationalisation hit the wires in window. Not in Ditto's geographic ICP, but a clean comparator point: "digital ID becomes legal ID" is now a multi-jurisdiction reality, which is the substantive backdrop for EUDI's December deadline. Best used as analogy material for an EUDI/eIDAS2 post, not as a primary cite.
  - Source: https://www.biometricupdate.com/202605/jordan-grants-legal-status-to-sanad-digital-id-as-users-pass-2-6m
  - Source: https://idtechwire.com/jordans-sanad-digital-id-gains-full-legal-status-under-amended-civil-status-law/
  - Date: 2026-05-11

### Pillar 4: KYC / AML compliance

(no new material in window — AMLA Home-Host Supervisory Cooperation RTS consultation opened 11 May (covered in yesterday's delta), public hearing scheduled 28 May. ISDA filed its response to the AMLA CDD RTS on 11 May (also covered yesterday). Next AMLA milestone is the 10 July submission of final CDD draft to the Commission.)

### Pillar 5: Customer onboarding

(no new material in window)

### Pillar 6: Identity verification (IDV)

(no new material in window — Veriff FIDO DocAuth certification reported April 2026 (outside window); no fresh iBeta PAD certifications, NIST IAL updates, or vendor M&A in window.)

### Pillar 7: Fraud / Deepfakes

- **Biometric Update guest editorial: "From identity to intent: Reimagining biometrics for real-time fraud prevention" — 12 May 2026, by Lenny Gusel (Head of Fraud Solutions, North America, Feedzai)** — Argues that instant payments and open banking have made transaction speed the new fraud surface, and that one-time biometric authentication is no longer sufficient against AI-powered scams. Proposes a shift to continuous, behaviour-driven, adaptive intent monitoring — intervening only when risk truly increases. Not a hard finding, but a useful commentary anchor for any Ditto post arguing that identity needs to be continuous, not a one-time onboarding event. Sub-theme A under banking ("identity orchestration across the lifecycle") is the closest fit.
  - Source: https://www.biometricupdate.com/202605/from-identity-to-intent-reimagining-biometrics-for-real-time-fraud-prevention
  - Date: 2026-05-12

### Pillar 8: Mobile trust & app security

(no new material in window — Anatsa Google Play campaign (10k installs via fake document-reader app) was April 2026, outside window; no fresh named-bank mobile-malware disclosures or ThreatLabz/Zimperium publications in window.)

### Pillar 9: Passwordless / Split-key

(no new material in window — FIDO World Passkey Day data (5bn passkeys, 68% enterprise deployment), Microsoft Entra GA, SMTB FIDO deployment, and Biometric Update enterprise-fallback commentary all covered in 7 May / 11 May deltas. OpenID Connect ASC 1.0 implementer's-draft vote (1–15 May) continues — primarily a Pillar 10 signal, see below.)

### Pillar 10: ZKPs in practice

- **France Identité deploys ZKP unlinkable age verification in live government sandbox** — See full finding under Pillar 3. The ZKP mechanism: a relying party requests an age-threshold assertion; the France Identité app generates a Zero-Knowledge Proof confirming the threshold is met, exposing no underlying date of birth and no linkable identifier. Responses to different relying parties cannot be correlated. Architecture complies with OID4VP 1.0 and the EUDI ARF. This is a production-environment government implementation of selective disclosure with ZKPs — the "can it work in practice?" question now has a government-issued answer. Cross-cite P3 for the EUDI context.
  - Source: https://www.biometricupdate.com/202605/france-identite-app-launches-sandbox-for-ios-proves-age-check-privacy-bona-fides
  - Date: 2026-05-12

(soft signal also in window — OpenID Connect Advanced Syntax for Claims (ASC) 1.0 implementer's-draft vote runs through 15 May, recommended for approval by the eKYC & IDA working group following the public review that opened in March. The two components — "Selective Abort and Omit" and "Transformed Claims" — include deriving an age verification result from a birthdate without exposing the full date of birth, which is the canonical privacy-preserving claim transformation. Reporting cycle opened around 1 May, so this is *in-flight* rather than *new this window*, but the vote concludes 15 May and the drafter should know the spec is about to advance to implementer's-draft status. Useful for any post drawing the line between "ZKP-style privacy" and "production-grade claim-level disclosure controls.")

### Pillar 11: Age assurance & privacy attributes

(no new material in window — Ofcom's anticipated May report on platform responses to its April age-assurance demands (Facebook, Instagram, Roblox, Snapchat, TikTok, YouTube; 30 April deadline) has not yet published; the 2026 Global Age Assurance Standards Summit Final Communiqué commentary (Biometric Update, 11 May) was covered in yesterday's delta.)

---

## Run summary

- Findings by pillar: P1: 0 | P2: 2 | P3: 3 | P4: 0 | P5: 0 | P6: 0 | P7: 1 (commentary) | P8: 0 | P9: 0 | P10: 1 (cross-pillar P3) | P11: 0 → Total: **5 hard findings + 1 commentary** (France Identité counted once across P3/P10)
- Override-worthy: Romania-Mastercard EUDI Wallet MoU; France Identité ZKP unlinkable age verification
- Delta path: research/2026-05-13-cycle-delta.md
