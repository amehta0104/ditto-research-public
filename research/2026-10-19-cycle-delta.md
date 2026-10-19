# Cycle Delta -- 2026-10-19

Window: 2026-10-16 -> 2026-10-19 (last 72 hours, Monday run covering the weekend). The 10-16 delta already scanned 10-16, so this cycle focuses on 10-16 (late) to 10-19.

## Provenance and integrity notes

- Brand brief, competitors list and all 11 pillar guides were fetched from the worker. Deduplication was checked by keyword against the 2026-05-06 baseline and every delta on the worker, through 2026-10-16.
- This file is ASCII-only to avoid the double-encoding issue on the worker PUT path.
- A thin weekend. Only one in-window finding met the bar. Money20/20 USA (Las Vegas, 10-18/21) and Authenticate 2026 (Carlsbad, 10-19/21) both start in this window, so expect more vendor and FIDO news in the 10-20 and 10-21 cycles.

### Missed by prior cycles (outside this window, not counted as findings)

These fell inside the 10-15 or 10-16 windows but were not logged. They are outside today's window, so per the hard rules they are listed here and not as findings. The drafter can use them, but they are 4-5 days old.

- **Eleventh Circuit upholds Florida HB 3 (2026-10-14).** In CCIA & NetChoice v. Uthmeier, a panel (Newsom, joined by Luck and Tjoflat) vacated the preliminary injunction. It held that HB 3 likely regulates platforms in a content-neutral way, based on "addictive features" (infinite scroll, autoplay, algorithmic feeds), and likely survives intermediate scrutiny. HB 3 bars under-14s from accounts on covered platforms and requires parental consent for 14-15-year-olds. NetChoice calls it "digital ID requirements as a condition for accessing lawful speech." Pillar 11.
  - Source: https://ccianet.org/news/2026/10/appeals-court-finds-floridas-law-restricting-social-media-can-be-enforced
  - Source: https://netchoice.org/netchoice-to-explore-all-options-to-protect-floridians-rights-online-following-eleventh-circuit-court-ruling-on-hb3/
  - Source: https://reason.com/volokh/2026/10/14/florida-addictive-features-social-media-restrictions-on-minors-likely-constitutional-eleventh-circuit-holds/
- **Eleventh Circuit lets Georgia enforce SB 351 (2026-10-15).** In NetChoice v. Carr (No. 25-12436), the same panel vacated the injunction. SB 351 requires platforms to verify all users' ages with "commercially reasonable efforts", to treat anyone they cannot verify as a minor, and to obtain parental consent for under-16s. Two US age-verification laws were cleared in two days by one circuit, which together make a stronger story than either alone. Pillar 11.
  - Source (opinion, via Georgia AG): https://content.govdelivery.com/attachments/GAOAG/2026/10/15/file_attachments/3818445/10.15.26%20NetChoice%20v.%20Carr%20Opinion.pdf
  - Source: https://idtechwire.com/appeals-court-lets-georgia-enforce-social-media-age-verification-law/
  - Caution: these are preliminary-injunction rulings, not final merits decisions. NetChoice says it is "exploring all options" (en banc or certiorari).
- **Bitkom d-you survey (2026-10-15).** Bitkom ran a representative phone survey of 1,004 German residents aged 18+ in weeks 33-37 of 2026. 53% want to use d-you (20% "definitely", 33% "probably"). 46% have never heard of the EUDI wallet (down from 52% earlier in 2026), and only 8% can explain it well. Bitkom also says more than 180 companies have signed an MoU to implement it. Pillar 3.
  - Source (primary): https://www.bitkom.org/Presse/Presseinformation/Digitale-Brieftasche-d-you-Haelfte-Bevoelkerung-will-nutzen
- **Sparkassen are start partners for d-you (DSGV, 2026-09-10).** This was never logged. At launch, ten Sparkasse applications will accept d-you, including current-account, securities-account, savings and business-customer onboarding. Online-banking login, transaction authorisation, in-branch use and a Wero link are planned for later in 2027. stadt-bremerhaven.de re-reported it on 10-19. It is relevant as the clearest German bank relying-party commitment so far, set against the DK liability demands (10-14) and the DIdG (10-15/10-16).
  - Source (primary): https://www.dsgv.de/newsroom/presse/260910-pm-d-you-sparkassen-37.html
  - Caution: the later-2027 features (login, transaction authorisation, Wero) come from the secondary source and were not checked against the DSGV release.

### Checked and rejected

- YuanKong Android RAT (cybersecuritynews.com, 2026-10-16, attributed to Star Labs): it abuses Wireless Debugging for shell access, shows fake PIN keypads and runs as malware-as-a-service (42 operator accounts, 110 droppers). The Star Labs primary could not be found or verified, and no target countries or banks are named. Not counted. Re-check if the primary surfaces.
- Socure Q3 2026 results (10-15): competitor-adjacent vendor results, outside window.
- Central Bank of Ireland Deputy Governor Kincaid on scam reporting and liability: dated 10-09 and paywalled.
- eIDeasy EUDI wallet tracker for October (10-15): a vendor tracker, outside window. Poland's EPTC sandbox opened 09-16.
- Mastercard "Know Your Agent: How banks are updating identity verification" panel at Money20/20 (10-19): a conference session with no published output. Mastercard Agent Pay agent-identity signals (10-01) are outside window.
- GAO quantum-readiness audit and the Paravision State Department award (Biometric Update): the pages could not be loaded and dates could not be confirmed. Not counted.
- Bank of America, Hirudo, FIDO Passkey Index 2026, DIdG, Fideuram, identifAI, Ping An/HKMA: logged 10-14 to 10-16. They are still circulating.
- No in-window material found for PSD3/PSR OJEU, EBA/ECB/DORA, AMLA, FATF, FCA/PSR APP fraud, OFAC/Travel Rule, NIST/iBeta, OpenID4VP/ZKP pilots, EU age-verification app, analyst orchestration coverage, onboarding benchmarks, SIM-swap/SS7, or LATAM regulators (CNBV, BCB, Superfinanciera).

## Override-worthy this cycle

1. **World launched "World ID for banking and finance" at Money20/20 (2026-10-18). The suite has three parts: a proof wallet app, deepfake-resistant identity checks for Zoom calls, and AgentKit, which lets a verified human delegate proofs to an AI agent. The named design partners are investment firms. No bank is named.** Account: company /. Angle: "The pitch to banks now is 'prove there's a human behind the agent'. That's a delegation problem, not a liveness problem. Who is accountable when the agent acts, and can the bank verify that link without collecting more personal data?" (Critique the category pattern. Do not name World in the post.)

## New findings

### Pillar 1: Banking & Payments

(no new material in window.)

### Pillar 2: Identity orchestration

- **World (the Tools for Humanity / Sam Altman-backed identity project) launched "World ID for banking and finance" on 2026-10-18. Co-founder Alex Blania unveiled it at Money20/20 USA in Las Vegas.** It packages three products around three cryptographic proofs: Proof of Human (Orb enrolment), Proof of Presence (phone-based liveness at the moment of interaction) and Proof of Attributes (selective disclosure from government credentials, such as age or nationality).
  - **World ID app (generally available):** a wallet for holding and presenting proofs, available in 150+ countries.
  - **World ID for Zoom (generally available):** confirms meeting participants are verified humans, not deepfakes. World says hosts will "soon" be able to require Proof of Presence in waiting rooms. Press reports say the feature had been in testing since April.
  - **World ID for Agents / AgentKit (beta):** a person delegates proofs to an AI agent, which presents a "delegated Proof of Human" to a third-party platform without exposing the underlying personal data.
  - **Partners and scale:** the design partners are Bain Capital, OpenExchange, Outtake, Pantera Capital and VanEck Funds. No bank is named as a customer or partner. World says more than 18 million people hold a Proof of Human.
  - **Fraud framing:** World cites Deloitte's projection of US AI-enabled fraud losses reaching USD 40bn by 2027 (from USD 12.3bn in 2023), and the 2024 Arup USD 25.6m deepfake video-call case.

  **Why it matters:** this is the first proof-of-personhood vendor to pitch a packaged product directly at banks. It puts "know your agent" (agent delegation) and deepfake-resistant video verification next to classic KYC attributes. It overlaps with three Ditto pillars: agentic identity (orchestration), deepfake defence for high-risk interactions (fraud), and selective disclosure (ZKP). The gap is just as useful. There are no bank partners yet, enrolment depends on proprietary Orb hardware, and the relying bank still has to decide how a delegated agent proof maps to liability and to its existing KYC record. That decision layer is orchestration territory.
  - Source (primary): https://world.org/blog/announcements/world-id-banking-finance-ai-safe
  - Source: https://www.biometricupdate.com/202610/world-brings-biometric-proof-of-human-to-banking-and-ai-agents
  - Source: https://www.finextra.com/newsarticle/48602/world-takes-on-ai-driven-impersonations-with-new-suite-for-banking-and-finance
  - Date: 2026-10-18
  - **Drafting cautions:** do not name World in a post. Under the competitor rule, critique the pattern ("proof-of-human for agents"), not the vendor. Do not say any bank has adopted it. The USD 40bn figure is Deloitte's 2027 projection as cited by World. Do not confuse it with identifAI's USD 40bn "deepfake fraud market" estimate (logged 10-14). The "testing since April" claim for Zoom comes from press, not the World primary. Related corpus: World ProveKit open-sourcing (09-04), USD 52.5m raise (07-27).

### Pillar 3: EUDI / eIDAS2

(no new material in window. See the notes for the Bitkom survey (10-15) and the Sparkasse start-partner release (09-10), both missed by prior cycles.)

### Pillar 4: KYC / AML compliance

(no new material in window.)

### Pillar 5: Customer onboarding

(no new material in window.)

### Pillar 6: Identity verification (IDV)

(no new material in window.)

### Pillar 7: Fraud / Deepfakes

(no new material in window. For World ID for Zoom (deepfake-resistant meeting verification), see Pillar 2.)

### Pillar 8: Mobile trust & app security

(no new material in window. YuanKong RAT rejected: primary not verified; see notes.)

### Pillar 9: Passwordless / split-key

(no new material in window. Authenticate 2026 starts today; FIDO news likely in the next cycle.)

### Pillar 10: ZKPs in practice

(no new material in window. For World's Proof of Attributes (selective disclosure), see Pillar 2.)

### Pillar 11: Age assurance & privacy attributes

(no new material in window. See the notes for the Eleventh Circuit Florida HB 3 (10-14) and Georgia SB 351 (10-15) rulings, both missed by prior cycles.)

## Open watch items

- **2026-10-19/21:** Authenticate 2026 (Carlsbad) and Money20/20 USA (Las Vegas). Check for FIDO announcements (agentic auth, digital credentials, payments) and bank-side identity news.
- **2026-10-20/21:** Biometrics Institute Congress, London.
- **YuanKong RAT:** look for the Star Labs primary and any named targets.
- **NetChoice/CCIA:** watch for en banc or certiorari filings on Florida HB 3 and Georgia SB 351.
- **DIdG follow-up:** read committee recommendation 21/8617 for relying-party, liability or KYC language.
- **Passkey Index 2026 PDF:** check for financial-services breakouts.
- **Bank of America:** read the consent orders.
- **PSD3/PSR OJEU:** checked 10-19, not published. Next check 10-26.
- **2026-10-20:** Japan My Number Card on Android (target).
- **2026-10-22:** Greek under-15 bill plenary vote; Utah SB73 / Aylo stipulation expiry.
- **2026-10-26:** BCB MED 2.0 / IN BCB 766 Pix changes take full effect.
- **2026-10-26/30:** FATF plenary, Paris.
- **2026-10-29/30:** EUDI Launchpad 2026, Brussels.
- **End-October:** Ofcom over-16 age-assurance rapid assessment; Romania EUDI sandbox target (10-31).
- **2026-10-31:** ECB SSM-2026-0301 action-plan deadline.
- **2026-11-01:** Turkiye age-token regulation takes effect.
- **2026-11-03:** AMLA central AML/CFT database RTS consultation closes.
- **Early November:** CNBV Anexo 71 biometric compliance deadline.
- **2026-11-09:** Apple Cash reload ID check goes live.
- **2026-11-18:** EUDI ARF Iteration 6 closes.
- **2026-12-24:** EUDI wallet-availability deadline (66 days).
- **2027-01-02:** d-you launch.
- **Workday / C1.ai:** close expected by 2027-01-31.
- **MyCheck:** launch date and Dutch government response.
