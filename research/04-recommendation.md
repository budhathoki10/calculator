# 04 — Recommendation

## The answer: none of these ideas is good enough to build

Eighteen ideas went through five validation rounds. **None survived.** The last three (the local review-and-referral engine, the freelancer "client garden", and the independent-tutor growth kit) were eliminated in Round 5. For each, the independent reviewer's strongest failure case could not be answered with evidence. The best final score was **5.05 / 10** (tutor kit). That is below the 6.0 "test before building" bar and the 7.0 "build" bar, both fixed *before* any scoring (`03-validation.md`).

This is the outcome your rule 7 allows: "'None of these is good enough' is an acceptable answer." A small idea that clearly makes users money was the goal. None of the candidates could show *clearly* that users would make money, and the shared reason is below.

**The one finding that matters most.** Every idea that reached the final round relied on the same claim: *prompting* a person to ask past customers for referrals, reviews or repeat work produces extra paid work that the person can see. The research found:

- strong evidence that referrals are the main way individuals get work. Word of mouth is 62–75% of freelance work in surveys, and repeat buyers are 68% of Fiverr's marketplace revenue (`01`);
- **no evidence that a prompted ask adds to that**, rather than taking credit for referrals that would have happened anyway. The adversarial review also found that referral coupons underperform ordinary coupons (Iyengar, Wharton) and that a funded referral tool for small businesses (Spreadable) shut down months after launch (`03a`, both old);
- strong evidence that incumbents already ship this feature in tools the users already have. HoneyBook (August 2025) has reactivation and referral requests. Jobber sells a Referrals add-on at $29/mo. Google gives a free review link and QR code (`03`, Round 5, re-checked).

Until the ask mechanism is shown to work, any product built on it is a guess.

---

## Why each of the top candidates lost

Ranked by highest score reached.

| Rank | Idea | Best score (round) | Final | Why it lost |
|---|---|---|---|---|
| 1 | **#6 Independent-tutor growth kit** | 6.10 (R2) | 5.05 | "Full or empty" paradox: established tutors fill up through word of mouth and then don't need it; new tutors have no parents to ask. The paying middle group has unknown size. The only quantified evidence for the mechanism is one vendor anecdote. Seasonal and capacity churn. It must refuse the most motivated users (those escaping Preply's 18–33% or Wyzant's 25%), because moving marketplace students off-platform breaks those platforms' terms. |
| 2 | **#1 Upwork Job Radar** | 5.70 (R1) | killed R2 | Real, recent demand: Upwork removed RSS feeds in August 2024, and paid tools appeared. But Vollna sells alerts from $4/mo, Upwork has free saved-search notifications and its own Uma assistant, and Upwork API access is manually approved. No defensible difference, and it depends on Upwork's goodwill. |
| 3 | **#5 Client garden (freelancers)** | 5.70 (R2) | 4.55 | HoneyBook shipped the core features in August 2025. Personal-CRM history is poor: Dex, YC-backed, took about 2.5 years to reach 1,000 customers at an LTV of about $231. And 70% of freelancers get most work from marketplaces, whose clients can't be reactivated off-platform, which excludes the founder's own community. |
| 4 | **#4 Local review-and-referral engine** | 5.55 (R1) | 4.85 | Google's free review link plus WhatsApp quick replies cover the review half free. Jobber and Housecall Pro trigger asks automatically on job completion. Only 11% of sole proprietors use CRM software (2022). No low-cost route from Nepal to US, UK or Australian local providers was found. |

---

## Pricing reference (for any revival; every price is sourced)

All [SE]: search excerpt, page not opened.

| Product | Price | Source |
|---|---|---|
| TutorBird | $14.95/mo (one listing now shows $16.95) + $4.95 per extra tutor | toolradar.com; capterra listings |
| Teachworks | $16.49/mo + $0.32 per lesson | teachngo.com |
| NiceJob | $75/mo (up to 2,500 customers a year) | get.nicejob.com/pricing |
| ReviewNudger | $29/mo | getapp listings |
| Jobber Referrals / Reviews / Marketing Suite | $29 / $39 / $79 per month | help.getjobber.com/hc/en-us/articles/20959257809815 |
| Podium | $399–$599/mo, 12-month contracts | pabau.com (competitor) |
| Dex / folk | $12/mo / $24–30 per user per month | happenstance.ai; capterra |
| HoneyBook Starter | about $29–36/mo after the February 2025 increase | prospeo.io; agiled.app (competitor blogs) |
| Vollna | $4–$49/mo (or $24/$62, disputed) | softwaresuggest.com; uphunt.io |
| BNI | about $699/yr (self-reported); $998–$1,398 in year one (independent) | growwithbni.bni.com; diymarketers.com |

[I] Dodo's fees (4% + $0.40, plus 1.5% for non-US customers, plus 0.5% for subscriptions) take 7.8–9.3% of a $12 charge and 14–16% of a $4 charge. Any revived idea should be priced at **$10/mo or more**, or sold annually, to keep the fixed $0.40 from eating the margin.

---

## Would users profit? The worked example for the closest candidate, and why it is unproven

Tutor kit at $12/mo:

| Input | Value | Label |
|---|---|---|
| Subscription | $12/mo | [A] proposed price |
| One extra weekly student, low case | $16/hr × 4 = $64/mo | [SE] Preply: adult English lessons average $16/hr (preply.com/en/blog/english-tutor-rates) |
| One extra weekly student, high case | $35–60/hr × 4 = $140–240/mo | [SE] Wyzant marketing: "$35 - 60 per hour on average" (wyzant.com/getstarted) |
| Nepal home tutor, per student | NPR 5,000–30,000/mo | [SE] necojobs.com.np (jobs blog, undated) |
| Extra students produced by the kit | **unknown** | [A] the untested mechanism |

**Arithmetic.** [I] One extra student who stays one month at the low case ($64) pays for about 5 months of subscription. The user profits in the first few months **if** the kit produces at least one extra student in its first ~5 months.

**Why this is not proof.** The last row is the whole question, and no evidence answers it (A4 in `03a`). The test below answers it before any code is written.

---

## First 100 paying users

**Not applicable.** No idea passed. Planning user acquisition for an unvalidated product would be guessing.

The tests below use only legal, free channels: personal network, opt-in sign-up forms, posting in communities **within their rules**, and no bulk DMs.

---

## Biggest risks and the cheapest test for each

These tests are what "starting the best project" honestly means now. They cost no code and very little money, and each has a pass/fail line fixed in advance.

| # | Risk | Cheapest test | Pass line (set now) | Cost |
|---|---|---|---|---|
| 1 | **The founder can't be paid from Nepal** (gates everything) | Email Dodo support and Paddle sales: "I am an individual with a Nepal-issued passport/citizenship and a Nepali bank account in my name. Can I onboard as an Individual merchant selling a SaaS subscription, and receive payouts to my Nepali bank?" Ask for the answer in writing, with the payout fee. Also check Paddle's `/countries` API. | A written "yes" from at least one | $0, about 1 week |
| 2 | **Prompted asks don't create extra paid work** (the A4 gap that killed all three) | Concierge experiment, no software. Recruit 20 independent tutors who have 5+ non-marketplace students and are *not* full. Give them a script for a personal WhatsApp referral ask to parents, sent from their own phone, and log the enquiries and enrolments for 6 weeks. Run a parallel group of 10–15 local in-person providers (beauty, cleaning, fitness) if reachable. | At least 1 in 4 tutors gains a paying student they attribute to the ask | $0, 6 weeks |
| 3 | **The paying segment can't be reached from Nepal** | During test 2, log the hours spent and channels used to find each willing participant | Under about 2 hours per participant through a channel that could repeat | $0 |
| 4 | **They won't pay even if it works** | At the end of test 2, offer the participants who gained a student a $12/mo pre-sale (14-day refund), billed through whichever processor passed test 1 | At least 5 paying | Processor fees only |
| 5 | **Incumbents copy it** | Not testable cheaply. Watch TutorBird's and Teachworks' changelogs during the 6 weeks. | Note only | $0 |

**If tests 1, 2 and 4 all pass,** re-score the tutor kit with the new evidence (E, D and R would rise on measured data) and only then consider building. **If test 2 fails,** the whole "referral engine" family is dead and should not be revived in a new form.

---

## What you must do personally (only the parts that are worth doing now)

1. **Payments (now):** send the written questions in test 1 to Dodo and Paddle. Do not rely on country lists. Dodo's list was cut off in every excerpt, and its own feedback board shows users "blocked at onboarding" in under-served countries.
2. **Identity and bank (when a processor says yes):** Dodo needs KYC through Persona (government ID plus selfie). The bank-account name must match the ID. An individual account needs "KYC + Bank Form" and no company [SE docs.dodopayments.com/miscellaneous/verification-process].
3. **Tax (before the first revenue):** foreign-currency receipts for software services face a 5% advance tax under Finance Act 2080 [SE samriddhi.org]. Get a PAN and confirm treatment with a Nepali tax adviser.
4. **Legal review (before storing anyone's client data):** one session with a Nepali lawyer on the Individual Privacy Act 2075 and Regulation 2077. One firm reads the Act as requiring consent, notice and, for collection, "approval of the Competent Authority", with penalties up to 3 years or NPR 30,000 [SE pioneerlaw.com; consentstack.io; dlapiperdataprotection.com]. Ask also about GDPR data-processor duties for EU/UK users and data about minors (tutoring).
5. **Domain and landing page:** not yet. They are only needed if tests 1 and 2 pass.
6. **Local wallets (only if you ever bill in NPR):** Khalti and eSewa won't release funds to a bank without business registration, PAN/VAT and a tax clearance certificate [SE khalti.com/info/terms/merchant; blog.esewa.com.np]. Fees are set by contract, roughly 2–3.5% according to a third party [SE websnp.com].

---

## What to research next instead

1. **Open the sources.** Widen this environment's network access (cloud environment settings → Network access) and re-run the key checks with pages actually opened: Dodo's accepted-countries list, Paddle's `/countries`, Upwork's fee page, Google's review policy and the BrightLocal 2026 survey. This turns the decisive [SE] items into Verified ones.
2. **Answer the mechanism question** (test 2 above). It is cheap and decisive, and it decides an entire family of ideas.
3. **Start a fresh problem-discovery round in the group where you have an unfair advantage: Nepali and South Asian freelancers.** The evidence shows their top problem is finding clients (73–86%), that they depend on marketplaces partly because marketplaces solve payment, and that they face the $500 card cap and 5% tax. Interview 20 of them about *the last time they lost money or a client*, not about features. This research did not have their own words (Reddit was unreachable, and Nepali forums were not searched), and that gap is the most likely place a better idea is hiding.
4. **Re-examine problem #1 (paid leads that don't convert)** for an angle that doesn't require Thumbtack, Jobber or Housecall integrations. That problem had the strongest independent pain evidence (an FTC order, Bark at about €40 per lead with zero hires, Google Local Services Ads at $53–63 per lead), but every idea for it here died on integrations and reach.

---

## The ledger

### Verified (a source I opened says it)

**None.** The environment blocked every page fetch, and you declined to widen access. Every factual claim in this research is a **search excerpt [SE]**: text the search tool attributed to a named URL, page not opened.

### Search-excerpt facts that the decision rests on (open these first)

| Fact | Source |
|---|---|
| Dodo supports individual merchant accounts (KYC + bank form); Nepal's accepted status was not visible | docs.dodopayments.com/miscellaneous/verification-process; /accepted-countries-and-territories |
| Dodo and Paddle exclude coaching and done-for-you services; Dodo excludes escrow | docs.dodopayments.com/miscellaneous/merchant-acceptance; paddle.com/support/aup |
| Dodo fees 4% + 40¢, +1.5% international, +0.5% subscription; payout-fee wording conflicts | dodopayments.com/pricing; docs pricing page |
| Fiverr: active buyers 3.1M vs 3.6M; repeat buyers = 68% of marketplace revenue | Fiverr FY2025 release and Form 20-F (sec.gov) |
| Upwork: 785k active clients (end of 2025), 763k (Q2 2026); RSS ended 20 Aug 2024 | investors.upwork.com; support.upwork.com |
| Word of mouth 65% (Localogy 2022), 62% (freelancermap 2025); 73% say finding clients is their top challenge (Payoneer 2023) | localogy.com; freelancermap.com; businesswire.com |
| HoneyBook reactivation and referral requests (Aug 2025); Jobber Referrals $29/mo; Google's free review link | help.honeybook.com; help.getjobber.com; support.google.com/business/answer/16816815 |
| Only 11% of sole proprietors use CRM software (May 2022) | marketingcharts.com; businesswire.com |
| GBP not available to online-only businesses | support.google.com/business/answer/7039811 |
| FTC fake-review rule in force since 21 Oct 2024 | ftc.gov press release (Aug 2024) |
| Nepal: 5% advance tax on foreign software income; $500/yr prepaid dollar card; social-media ban 4–9 Sep 2025 | samriddhi.org; nepalitelecom.com; timeslive.co.za |

### Inferred (reasoning shown in the files)

- Fewer buyers and clients on Fiverr and Upwork means more competition per job (`01`).
- Dodo's fixed fee makes sub-$8 monthly pricing unattractive (`03`, Round 3).
- At an assumed 6%/mo churn the average lifetime is about 17 months; at the reviewer's 8.9%, about 11 months (`03`).
- South Asian freelancers lean on marketplaces partly because marketplaces solve payment (`01`).
- A user-sends design (deep links) avoids messaging-API cost and anti-spam problems (`03`, Round 4).

### Still unknown (and how to find out)

| Unknown | How to find out |
|---|---|
| Whether Dodo or Paddle will onboard and pay out to a Nepal-ID individual today | Written answer from each (test 1) |
| Whether prompted referral asks produce extra paid work | 6-week concierge test (test 2) |
| Customer acquisition cost for any segment here | Log hours and money per participant (test 3) |
| Churn of solo-provider and tutor tools | Ask TutorBird and Teachworks users; find published benchmarks |
| Size of the "established but not full" tutor segment | Screening questions while recruiting for test 2 |
| Nepal Privacy Act duties for a SaaS storing users' clients' data | Nepali lawyer (personal task 4) |
| Hosting cost; Syften, Who Sponsors Stuff and DevelopmentAid prices; current Upwork Freelancer Plus and Fiverr Seller Plus prices | Open the vendors' pricing pages |
| Reddit user voices (excluded from search here) | Re-run the user-voice searches with network access |
