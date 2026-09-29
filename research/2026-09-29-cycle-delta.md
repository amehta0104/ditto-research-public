# Cycle Delta — 2026-09-29

Window: 2026-09-27 → 2026-09-29 (last 48 hours)

## Provenance and integrity notes

- The worker API was reachable this cycle, so the brand brief, competitors list and pillar guides were fetched from the worker. Deduplication was checked against the 2026-09-24, 09-25 and 09-28 deltas and against the 2026-05-06 baseline.
- Weekend (09-26/27) was quiet. The effective new surface is **Monday 2026-09-28** (Biometric Update and ID Tech both published full Monday runs). Nothing substantive is dated 09-29 as of run time.
- **Already logged, not re-reported:** OpenID4VP/OID4VCI first HAIP self-certifiers (Biometric Update carried it again 09-28; it was logged in the 09-28 delta). Also already logged: the Ofcom NCII hash-matching deadline of 09-30, the AMLA group-wide RTS deadline of 09-30, and the Brazil Resolution 561 cutover on 10-01.
- **Checked and rejected (out of window):**
  - Alabama AG / TikTok child-safety settlement: the primary release is dated **2026-09-25**. Trade coverage on 09-28 does not bring it into the window. It is on-pillar (P11): $100M minimum, up to $300M, and "robust age assurance measures to more effectively verify the age of young users", with no method specified. A future cycle may use it only as background.
  - Utah SB73 VPN "actual-location" provision preliminarily enjoined (Judge Barlow, *Aylo v. Utah*): the ruling is dated **2026-09-24**. This resolves part of the Utah SB73 / Aylo watch item. The core age-verification mandate and the anti-circumvention prohibition remain in force.
  - IFC $700M digital-payments risk-sharing initiative: announced **2026-09-09**.
  - Ping Identity September product updates, covering agent session binding and IDV connectors: **2026-09-23**. Adjacent-list vendor.
  - Discord global age-assurance rollout (AgeKey reusable credential): **2026-09-22**.
  - RemControl Android banker: **2026-09-24**. StreamRat: disclosed early September.
  - BCRA Com. "A" 8471/8473 and CNBV Art. 319 Bis changes: **2026-08-27 / 2026-09-02**.
  - FinCEN §311 NPRM on Banque Misr UAE: published **2026-09-01**; comments close 2026-10-01.
- **Checked and rejected: recycled P5 onboarding figures.** The same numbers came back again: "1 in 5 applications abandoned", "70% abandon flows >3 min", "$3.3bn". The earlier ruling stands.
- **Noted, not counted (off-ICP):**
  - GMO passkey sign-in for Onamae.com (Japan, domain registrar, 09-28)
  - Vietnam's revised e-ID rules extending VNeID to resident foreigners (09-28)
  - NSW joining the Commonwealth face-matching scheme (law-enforcement scope, 09-28)
  - US Facial Recognition and Biometric Technology Moratorium Act reintroduced (09-28)
  - NADRA child iris capture (09-28)
  - Neurotechnology passing NIST FastCAP (09-28)
- **PSD3/PSR OJEU:** checked on the Monday cadence. Still no Official Journal notice.

## Override-worthy this cycle

(none)

## New findings

### Pillar 1: Banking & Payments

- **Deutsche Bank is taking payee verification global, building name-to-account matching, fraud scoring and compliance screening into its international payment routing *before* funds move.** On **2026-09-28**, Deutsche Bank and IPID (International Payments Identity, Singapore) announced plans for a strategic partnership. It turns Deutsche Bank's earlier, selective use of IPID fraud-prevention checks into a bank-wide deployment of "payment decision intelligence" across its global payments business. The partnership combines verification, fraud, compliance and routing signals so the bank can check recipients and assess risk before a cross-border payment is sent. **Why it matters for an identity vendor:** Verification of Payee under the EU Instant Payments Regulation is domestic and euro-only. A top-tier correspondent bank is now choosing to push the same "prove who you're paying" logic into **cross-border** flows, where no mandate requires it yet. The pattern matches the Canadian RTR and Pix cases already in this corpus: identity assurance is moving *upstream of the payment*, not being retrofitted after losses. The drafting hook is the question every bank will face: if you verify the payee on a €50 domestic instant transfer, why not on a €5m cross-border wire?
  - Source (primary): https://www.prnewswire.com/news-releases/deutsche-bank-and-ipid-announce-plans-for-strategic-partnership-to-enhance-payment-decision-intelligence-302891235.html
  - Source: https://idtechwire.com/deutsche-bank-plans-broader-payee-verification-partnership-with-ipid/
  - Date: 2026-09-28
  - **Drafting caution:** the release says "plans for" a partnership and gives no volumes, corridors or go-live date. Do not quantify, and do not describe it as deployed. The VoP/IPR contrast is our framing; the release does not mention regulation.

### Pillar 2: Identity orchestration

(no new material in window. Ping Identity's September product update, which binds agent sessions to user and device and adds IDV connectors in DaVinci, is dated 09-23. It is out of window and from an adjacent-list vendor. The agentic-identity cluster (Omada/EmpowerID, BIO-key, iProov HAPS) is logged in the 09-24 and 09-25 deltas. The Forrester CIAM Wave kick-off had still not been announced as of run time.)

### Pillar 3: EUDI / eIDAS2

(no new material. Biometric Update's 09-28 items were a sponsored EUDI opinion piece and a re-report of the OpenID HAIP certifications already logged 09-28. The rollout-status piece of 09-24 is out of window. Its datapoints may be useful background once verified against primaries: Sweden's earliest release is 2028, epicenter.works puts standards at "50-to-60 percent complete", and IN Groupe says "We will not see this massive big bang by the end of the year".)

### Pillar 4: KYC / AML compliance

(no new material. The AMLA group-wide RTS submission is due **2026-09-30**, with no press release yet. The FinCEN Banque Misr UAE §311 comment period closes **2026-10-01**. Both are watch items, not findings.)

### Pillar 5: Customer onboarding

(no new material. Only the recycled vendor abandonment figures came back; they were rejected again. See the provenance notes.)

### Pillar 6: Identity verification (IDV)

(no new material that meets the ICP filter. Neurotechnology passing NIST FastCAP qualification on 09-28 is contactless-fingerprint for government and law enforcement; noted, not counted.)

### Pillar 7: Fraud / Deepfakes

- **Only 1 in 10 large US enterprises has deployed deepfake detection, while 3 in 4 security leaders say deepfakes are already a problem. Among organisations hit by a deepfake attack, 1 in 4 lost $1M+ in a single incident.** This is Pindrop's *Deepfake Readiness Index 2026*, released **2026-09-28**. The survey was fielded by **Wakefield Research** among **250 US security leaders at organisations with 1,000+ employees**, **2026-06-11 to 06-22**, with a margin of error of **±6.2pp**. Further figures:
  - **93%** are concerned about their preparedness.
  - **37%** believe one successful attack could end the business.
  - **74%** believe defences will improve faster than attacks.
  - **75%** say it would take an executive-level compromise to make deepfakes a board priority.

  The report names the attack surfaces as **helpdesk calls, remote job interviews and sensitive virtual meetings**. That is the same enrolment and recovery surface as the Microsoft Storm-3121/3032 finding (09-11 delta). **Why it matters:** this is one of the few deepfake surveys in the corpus with a disclosed sample and fieldwork window. The useful angle is the gap between concern and deployment (93% worried vs 10% deploying), not the scale of the threat. The "74% think defences will outpace attacks" figure is a ready-made contrarian hook.
  - Source (primary): https://www.pindrop.com/resources/report/deepfake-readiness-index
  - Source: https://www.biometricupdate.com/202609/deepfakes-are-overwhelming-businesses-unprepared-to-deal-with-ai-threat-pindrop
  - Date: 2026-09-28
  - **Verification notes:**
    - Biometric Update also attributes a **"1,680% increase in AI-driven attacks, Q4 2024–June 2026"** to Pindrop. **That figure does not appear in the report primary.** Do not use it.
    - The sample is US-only and cross-sector, with no financial-services breakdown. Do not describe these as bank figures.
    - Pindrop is not on the `competitors.md` lists and is nameable, but it is a vendor survey: cite it as "a Wakefield Research survey for Pindrop" with n=250.

### Pillar 8: Mobile trust & app security

(no new material in window. RemControl (09-24) and StreamRat (early September) are out of window. The recommendation to move P8 to a weekly sweep stands.)

### Pillar 9: Passwordless / split-key

(no new material that meets the ICP filter. GMO's passkey sign-in for Onamae.com (Japan, 09-28) is a domain registrar and off-ICP; noted, not counted.)

### Pillar 10: ZKPs in practice

(no new material. The OpenID HAIP certifications were already logged 09-28. No bank ZKP pilot or OpenID4VP/SD-JWT VC spec change is dated in window.)

### Pillar 11: Age assurance & privacy attributes

(no new material in window. The Alabama–TikTok settlement (09-25) and the Utah SB73 VPN-provision injunction (09-24) are both on-pillar but out of window; see the provenance notes.)

## Open watch items

- **2026-09-30:** AMLA group-wide requirements RTS submitted to the Commission. Watch for the AMLA press release.
- **2026-09-30:** Ofcom NCII/deepfake hash-matching compliance deadline. Watch for first enforcement notices.
- **2026-09-30:** US DOL UI Group 1 states' Login.gov onboarding deadline.
- **2026-10-01:** FinCEN Banque Misr UAE §311 comment period closes.
- **2026-10-01:** Brazil Resolution 561 eFX cutover. **2026-10-30:** VASP authorisation transition closes.
- **Deutsche Bank / IPID (NEW):** watch for go-live, corridors covered, and whether other correspondent banks follow with cross-border payee verification.
- **Utah SB73 / Aylo:** the actual-location provision is enjoined (09-24). Watch for an appeal and for the 2026-10-22 stipulation expiry.
- **Forrester CIAM Wave:** kick-off expected end of September and still not seen.
- **DHS biometric capture GWAC ($440.7M):** awards expected late September or October.
- **2026-10-31:** ECB SSM-2026-0301 action-plan deadline.
- **2026-11-18:** EUDI ARF Iteration 6 closes.
- **2026-12-24:** EUDI wallet-availability deadline (86 days). Germany's d-you launches 2027-01-02.
- **Before 2026-12-31:** Ofcom consultation on the Crime and Policing Act 2026 s.100 48-hour NCII takedown duty.
- **PSD3/PSR OJEU:** still unpublished. Next Monday check is 2026-10-05.
