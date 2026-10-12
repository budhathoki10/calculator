# 01 — Problems: how individuals get paying customers today, and where it fails

Research date: 12 October 2026. Researcher: Claude (Claude Code session).

## Read this first: what the evidence labels mean in this research

The research environment's network policy blocked every direct page fetch: `WebFetch` and `curl` failed for stripe.com, paddle.com, dodopayments.com, upwork.com, reddit.com, esewa.com.np, khalti.com, nrb.org.np and even wikipedia.org. Reddit is also excluded from the search tool, so Reddit voices are missing. The founder was asked whether to widen network access and declined, so the work went ahead with the web-search tool only. That tool returns excerpts of named pages, not the pages themselves.

Your rule 1 says a search snippet must not be presented as something I read. So **nothing in this research is labelled "Verified".** The labels used are:

| Label | Meaning |
|---|---|
| **[SE]** Search excerpt | The search tool returned this text or figure attributed to the named URL. **I did not open the page.** It is evidence of what the source probably says, weaker than "Verified". Every [SE] that a decision depends on is listed in the ledger in `04-recommendation.md` to open and confirm. |
| **[I]** Inference | My reasoning from [SE] facts. The reasoning is shown. |
| **[A]** Assumption | Untested. A test is given. |

Dates are the source's publication or "as of" date where the excerpt showed one. "Date unknown" means it did not show one. Sources older than about two years (before October 2024) are marked **(old)**.

Quotes are short fragments as the search tool returned them. Where the tool paraphrased, no quotation marks are used.

---

## Group 1 — Freelancers on marketplaces (Upwork, Fiverr and similar)

### What they pay to get customers

| Cost | Figure | Label and source |
|---|---|---|
| Upwork freelancer service fee | Variable 0–15% per contract since 1 May 2025 (was a flat 10%) | [SE] golance.com/blogs/upwork-fees-explained-2026 (2026); upworkalerts.com/blog/upwork-fees (2026). Third-party. Upwork's own help page could not be reached. |
| Upwork Connects (paid bids) | $0.15 each; Basic accounts get 10 free a month | [SE] same sources |
| Upwork Freelancer Plus | Sources conflict: $14.99 or $19.99 a month | [SE] same sources. **Unknown** which is current; check upwork.com/pricing. |
| Upwork "boost" | Bid auction; one user was charged with "0 proposals viewed • 0 freelancers shortlisted" | [SE] community.upwork.com thread (2024) |
| Fiverr seller commission | Flat 20% of every order, tips included | [SE] hireinsouth.com/post/fiverr-pricing (2026); jobbers.io (2026) |
| Fiverr Seller Plus | Conflicting: $19/mo (older review) vs $29–$49/mo (2026 guide) | [SE] fastlancer.org; hireinsouth.com. **Unknown** which is current. |
| Preply (tutors) | Preply takes 100% of the trial lesson, then an 18–33% sliding commission | [SE] pensight.com/post/how-much-does-preply-actually-cost-tutors-2026 (2026); languatalk.com/blog/preply-review (Apr 2024). LanguaTalk is a competitor. |
| Wyzant (tutors) | "All tutors will retain 75% of their posted hourly rate … Wyzant will retain a 25% Platform Fee" | [SE] support.wyzant.com/…/what-is-the-fee-structure-for-tutors-listed-on-wyzant (date unknown, official help page) |
| italki (tutors) | Conflicting: 15%→21% (tutor guide) vs 40% (review blog) | [SE] andromedajones.substack.com (2025); myengineeringbuddy.com (2025). **Unknown.** |

### The platforms' own numbers (company filings)

- **Fiverr is shrinking in buyers.** "Annual active buyers as of December 31, 2025, were 3.1 million, compared to 3.6 million as of December 31, 2024" (−13.6%). Marketplace take rate 27.7%. Marketplace GMV $1,073.0M, down 2.2%. [SE] Fiverr Q4/FY2025 results, fiverr.com/news/fiverr-q4-earnings-2025 (18 Feb 2026), and the Form 20-F on sec.gov.
- **Repeat buyers carry Fiverr.** "Repeat buyers contributed 68% of our revenue on our marketplace for 2025 and 2024." [SE] Fiverr Form 20-F FY2025, sec.gov/Archives/edgar/data/0001762301/000117891326000858/zk2634486.htm (2026).
- **Upwork is flat to shrinking.** 785,000 active clients at 31 Dec 2025. FY2025 revenue $787.8M (+2%). [SE] investors.upwork.com Q4 2025 release (Feb 2026). Q2 2026: 763,000 active clients and GSV $966.4M, down 4% year on year. [SE] barchart.com, Upwork Q2 2026 results (Aug 2026).

[I] Fewer buyers (Fiverr −13.6%) and fewer active clients (Upwork 785k → 763k) shared by the same or more sellers means more competition per job. Sellers' complaints below are consistent with this.

### Most repeated complaints (user voices)

- Fiverr: "impressions on their best gig went from around 1000+ to basically zero over night", with "only generic responses from Fiverr support". [SE] community.fiverr.com post 341384 (date unknown, 2024–2025 range). A Top Rated seller "since several years" reports "a significant drop since post September". [SE] community.fiverr.com post 339165. Another reports having "not been receiving orders" in 2024. [SE] post 332336.
- Fiverr's own answer (July 2025) blames demand and keywords: "fluctuations in your analytics are completely normal". [SE] community.fiverr.com/public/blogs/what-to-do-if-your-impressions-clicks-or-conversions-are-down-2025-07-18.
- Upwork: "something like 1/50 in the last 2 weeks have been viewed". [SE] community.upwork.com thread "99% of proposals aren't being viewed" (old, 2023). Connects are not refunded when a client never hires (Upwork staff reply, 2022, old).
- Preply: one tutor's account was blocked "with no reason given" after "more than 1,600 lessons"; another says their account was "permanently deactivated on 24 December 2025" with earnings frozen. [SE] sikayetvar.com/en/preply-us (late 2025 – mid 2026, self-selected complaint site).
- Preply "owns the students, you don't". [SE] edisonos.com Preply review (2025, competitor).

### Tools they pay for, and why they cancel

- Upwork job-alert and bidding tools: Vollna (directory listing: $4 / $19 / $49 a month; a competitor reports $24 / $62) [SE] softwaresuggest.com/vollna; uphunt.io/blog/vollna-alternatives. GigRadar: "Start" $129/mo, and it also requires a $20/mo Upwork Agency Plus subscription [SE] gigradar.io/pricing (2026).
- Why demand for alert tools rose: Upwork "officially discontinued support for RSS feeds after August 20, 2024". [SE] support.upwork.com/hc/en-us/articles/52052528243731-RSS-deprecation. A Vollna Trustpilot reviewer (Aug 2024) moved to Vollna "after the removal of the RSS feature from Upwork". [SE] trustpilot.com/review/vollna.com.
- Cancellation reasons: **unknown** from opened sources. [A] Hypothesis: people cancel once they land steady work. Test: ask 10 ex-subscribers of Vollna-type tools.

### What one new customer is worth

- Upwork GSV per active client was $5,129 in Q4 2025 (the client's total spend across all freelancers, not one freelancer's earnings). [SE] Upwork Q4 2025 release.
- Fiverr annual spend per buyer was $342 in 2025. [SE] Fiverr FY2025 release.
- Tutor: Wyzant markets an average of "$35 - 60 per hour" [SE] wyzant.com/getstarted (date unknown, vendor marketing). Preply's own guide gives English lessons "$15 to $50 an hour", with adults averaging $16/hr [SE] preply.com/en/blog/english-tutor-rates (date unknown).
- [I] A weekly student at $16–$60/hr is worth roughly $64–$240 a month to a tutor while they stay (4 lessons × rate). How long students stay is **unknown**. Test: ask 10 tutors for their average student lifetime.

---

## Group 2 — Freelancers who find clients themselves (outreach, referrals, portfolios, LinkedIn)

### How they get clients

- **Word of mouth is the top channel in every survey found.**
  - Localogy (2022, old): word of mouth 65%, freelancing platforms 54%, social media 50%, agencies 46%, job boards 44%. [SE] localogy.com/2022/02/benchmark-bytes-through-what-channels-do-freelancers-find-work
  - freelancermap study 2025: "62% of freelancers get projects from passive sources such as referrals". [SE] freelancermap.com/blog/client-referrals-for-freelancers (2025)
  - MBO Partners via the Atlanta Journal-Constitution: 75% word of mouth. Undated and probably old. [SE] ajc.com
- **Finding new clients is the top problem.** Payoneer's 2023 Freelancer Insights report (about 2,000 freelancers, 122 countries): 73% named "finding new clients" their biggest challenge, and "70% of freelancers surveyed find most of their work through online marketplaces". [SE] freelanceinformer.com; businesswire.com/news/home/20230321005195 (Mar 2023, old). In Bangladesh 86% named it. [SE] thefinancialexpress.com.bd.
- Contently survey: 62% of freelancers pursue new clients at least monthly. [SE] contently.net (date unknown).

### What it costs them

- LinkedIn automation is off-limits. LinkedIn "bars third-party software, including bots, crawlers, and browser extensions, that scrape … or automate activity", citing User Agreement section 8.2. [SE] linkedin.com/help/linkedin/answer/a1341387 (date unknown, official help page). [I] Any client-getting product built on LinkedIn automation breaks LinkedIn's terms and is excluded by your ethics rules.
- Business-management suites: HoneyBook raised prices on 4 February 2025; Starter went to about $29–36 a month. Trustpilot 3.5 (570 reviews), with complaints about pricing and a 3% payment fee. [SE] prospeo.io/s/honeybook-alternatives (2026); agiled.app (2026), both competitor blogs. Dubsado about $20–28 Starter. [SE] assembly.com (2025).
- Personal CRMs: Dex about $12/mo; folk $30 per user per month ($24 billed annually). [SE] happenstance.ai/compare/folk-vs-dex; capterra.com/p/251534/folk/pricing (2026).

### Complaints and outcomes

- Income instability: in Bectu's UK creative-freelancer survey (Oct 2025), "39% were out of work and just 13% felt secure in their job". [SE] prospect.org.uk; workplacejournal.co.uk (Oct 2025). This is a UK creative-sector sample, not all freelancers.
- Portfolio and profile networks have failed. Read.cv was acquired by Perplexity and wound down from 17 January 2025. [SE] techcrunch.com/2025/01/17/perplexity-acquires-read-cv. Polywork closed in January 2025. [SE] kitemetric.com (weak source).

### What one new client is worth

- BNI says its members get an average of 27.7 referrals a year, each worth an average of $1,367, for a $699 annual fee. [SE] growwithbni.bni.com (date unknown). **Self-reported by a seller; treat as an upper-bound claim.**
- Nepal: freelancers earn "an average of USD 4,723 annually"; entry level USD 2,810. [SE] IIDS IT-industry study (2022 data, published Feb 2025), iids.org.np.

---

## Group 3 — Local service providers (tutors, trainers, photographers, beauty, repair, cleaning, home services)

### What they pay to get customers

| Channel | Cost | Label and source |
|---|---|---|
| Thumbtack (pay per lead) | Roughly $10 to $100+ per lead, varying by trade and city; Thumbtack publishes no cost data | [SE] leadcapture.io/blog/thumbtack-lead-cost (vendor blog); housecallpro.com guide |
| Thumbtack, a pro's view | Lead prices "went from about $9.50 to $30+ dollars a piece EVEN if the client does not purchase a service" | [SE] community.thumbtack.com/discussion/comment/756 (date unknown) |
| Thumbtack close rate | "Most businesses typically close between 10-30% of their leads" | [SE] housecallpro.com (vendor) |
| Bark (credits) | One lead took 18 credits, about €40, at €140 for 60 credits (Aug 2025) | [SE] productreview.com.au/listings/barkcom (Aug 2025) |
| Google Local Services Ads | Blended $53 per lead (888 contractors, 126,650 leads, Feb 2026); $63.29 (May 2026, 1,011 businesses); standard Google Search Ads $104 per lead | [SE] SearchLight Digital and The Data-Driven Trades benchmarks, as summarised by search (2026) |
| The Knot / WeddingWire (wedding pros) | One photographer reports $4,000–$6,500 a year for fewer than 10 bookings | [SE] french-touch-photography.com (date unknown) |
| Review and messaging suites | NiceJob Grow $75/mo (up to 2,500 customers a year); Podium Core $399/mo and Pro $599/mo on 12-month contracts | [SE] get.nicejob.com/pricing (official); pabau.com/blog/podium-cost (competitor) |
| Local SEO tools | BrightLocal from $39/mo; Localo from $69/mo; Paige from $99/mo | [SE] Capterra and Software Advice listings (2026) |

### Most repeated complaints

- Paying for leads that never hire. Bark: "paid for over 20 leads without booking a single job". [SE] g2.com/products/bark-com/reviews (date unknown). Thumbtack: Trustpilot reviewers (Dec 2025) charged when customers "contact several pros and hire none". [SE] uk.trustpilot.com/review/thumbtack.com.
- Regulators have acted. The FTC order against HomeAdvisor (Angi Leads) required payment of up to $7.2 million for deceptive lead-selling tactics; the final order was approved in April 2023. [SE] ftc.gov (Apr 2023, old but still the standing order). A 2016 class action, *In re HomeAdvisor* (D. Colo. 1:16-cv-01849), alleges leads that "were not verified and were bogus". [SE] chimicles.com (old).
- A Senate letter says "more than 200 formal complaints" reached the FTC about The Knot / WeddingWire. [SE] grassley.senate.gov (date unknown). Ex-employees say The Knot "swindles" advertisers. [SE] petapixel.com/2023/07/20 (Jul 2023, old).
- Suites are hard to cancel. Podium: a G2 reviewer cancelled 31 days before renewal and was still billed. Business.org: the chief complaint is "having an extremely hard time discontinuing". [SE] g2.com; business.org Podium review (dates unknown).
- NiceJob is well rated (G2 4.8 from 410 reviews), but "Expensive" is a listed con with 6 mentions. [SE] g2.com via search summary (2026).

### Free channels and the rules on them

- Google: "Google review count and review score factor into local search ranking"; local results rest on relevance, distance and prominence. [SE] support.google.com/business/answer/7091 (official; date unknown).
- Google bans incentivised reviews and "review gating": "Businesses should not discourage or prohibit negative reviews or selectively solicit positive reviews from customers." Asking all customers is allowed. [SE] demandhub.co; brightlocal.com/learn/review-platform-guidelines (secondary summaries of Google policy, 2026). **Google's own policy page was not opened.**
- Consumers: "97% of consumers read reviews online"; 74% look for reviews from the last three months; 31% will only use businesses rated 4.5 stars or higher. [SE] BrightLocal Local Consumer Review Survey 2026 (1,002 US adults, Feb 2026), via pinmeto.com and brightlocal.com. BrightLocal sells review software.
- Thumbtack staff advise replying "within the first few minutes", and "the average pro in your area and category responds within 21 minutes". [SE] community.thumbtack.com (date unknown).

### What one customer is worth

- **Unknown** for most trades. Thumbtack lead cost ($10–$100+) divided by close rate (10–30%) suggests [I] $33–$1,000 of lead spend per won job, which pros pay only because a job is worth more. That is an inference from vendor figures, not a measurement.

---

## Group 4 — Creators and educators (courses, coaching, digital products)

- Gumroad: 10% + $0.50 per sale plus processing, and 30% on sales via its Discover marketplace. [SE] ecomm.design/gumroad-review; dodopayments.com/blogs/gumroad-fees-explained (2026; both have commercial interests).
- Kajabi (2026): three plans, $143–$399 a month billed annually ($179–$499 monthly). [SE] ddiy.co/kajabi-pricing; learningrevolution.net (2026).
- Stan Store: $29–$99 a month according to a third-party site; Trustpilot about 4.8 from about 2K reviews, with complaints about charges after cancelling. [SE] tools.malwaretips.com; trustpilot.com/review/stan.store. **Price unverified.**
- Sponsorships: Passionfroot is free for creators. It takes a 15% "Sourcing Fee" on deals from its partner network and charges brands 5% on deals creators bring in themselves. [SE] help.passionfroot.me (2026, official help). Who Sponsors Stuff, a paid sponsor database, "brings in $100,000 a year". [SE] indiehustle.beehiiv.com (date unknown).
- Writers pay for curated pitch calls: Sonia Weiser's "Opportunities of the Week" costs $4/month. [SE] elitecontentmarketer.com (date unknown).

[I] Creators already pay a lot for selling (fees, suites) but little for *finding buyers*. The visible paid "find customers" products here are sponsor databases and opportunity newsletters, and they are cheap ($4/mo) or B2B-priced.

---

## Group 5 — People in lower-cost countries selling to higher-paying markets (Nepal and South Asia)

- **Getting paid is hard.** PayPal's Nepal status is contested: one source says it "does not currently support account creation"; Merokalam says NRB was "actively working to connect with PayPal" in 2024. [SE] skydo.com; merokalam.com (2026). Payoneer is "the most widely used answer" among Nepali professionals. [SE] merokalam.com/blog/payoneer-card-in-nepal (Apr 2026, blog with commercial interest).
- **Paying for foreign tools is capped.** Nepal's prepaid dollar card is "capped at USD 500 in one given year". [SE] nepalitelecom.com (undated). An NRB card-limit notice of November 2025 said "no change in the provisions regarding prepaid cards". [SE] sharesansar.com (11 Nov 2025). [I] A Nepali freelancer paying a $10/mo foreign SaaS uses $120 of a $500 yearly allowance, a real constraint.
- **Tax:** a "5% advance tax deduction" applies to foreign-currency receipts for software, consultancy and similar services under the Finance Act 2080. [SE] samriddhi.org/blog/nepals-freelance-frenzy-dollars-and-dilemmas (date unknown). Only "9,400 individuals were registered as freelancers in the IRD database in the financial year 2021/22" (old). [SE] same source.
- **Scale:** Nepal's IT service exports were about $515M in 2022 (IIDS). Industry says exports passed $1B in 2025, but that is "based on industry growth patterns and multiple informal assessments". [SE] kathmandupost.com/national/2026/02/25 (Feb 2026).
- **Platform risk at home:** Nepal blocked 26 social platforms, including Facebook, X and YouTube, in September 2025 for failing to register with the ministry. The ban was lifted on 9 September 2025 after 19 people were killed in protests. [SE] timeslive.co.za (9 Sep 2025); scroll.in.
- **Dependence on marketplaces:** [I] Payoneer's 70% marketplace figure and the Nepal payment frictions together suggest South Asian freelancers lean on marketplaces partly *because* marketplaces solve payment. A product that moves them to direct clients must not leave them unable to get paid.

---

## Group 6 — Other groups found to be badly served

- **Development-sector consultants in Nepal (shrinking market).** 34 USAID projects worth $329M were terminated in Nepal; numbers "have not been independently verified". [SE] kathmandupost.com/national/2025/03/12. The NGO Federation estimates about 30,000 jobs lost. [SE] kathmandupost.com (Aug 2025). The OECD projects official development assistance to fall 6.9% in 2026, a third yearly decline. [SE] oecd.org ODA projections (19 Jun 2026). Only 136 of about 250 INGOs that have worked in Nepal are active. [SE] ekantipur.com (5 Aug 2026).
- **Independent tutors in Nepal.** Several tutor-matching apps exist (TeachMandu, E-Tutor Class, Seekshya, Learnify). [SE] App Store listings. There is no data on their traction and no Nepal-specific tuition-bureau commission data (**unknown**).
- **Nepal home services.** Sajilo Sewa (since 2017, "more than 50 home services", 250+ providers), Skill Sewa, Sajilo Mistri and Nirman Sathi already operate. [SE] english.onlinekhabar.com (undated). Comparable Indian startups DoorMint and Taskbob shut down. [SE] inc42.com (old).

---

## Ranking: problems by pain × frequency × expense

Scale 1–5 per factor. The scores are my judgement [I] from the evidence above; the evidence column says why.

| # | Problem | Pain | Freq. | Expense | Total | Strongest evidence |
|---|---|---|---|---|---|---|
| 1 | **Paying for leads or visibility that don't convert** (Thumbtack, Bark, Angi, LSA, The Knot, Upwork Connects and boosts) | 5 | 4 | 5 | **14** | FTC $7.2M order; Bark €40/lead with zero hires; LSA $53–63/lead; Thumbtack "$9.50 to $30+ … EVEN if" no hire |
| 2 | **Finding new clients at all** (the top-ranked freelancer challenge) | 5 | 5 | 3 | **13** | Payoneer 2023: 73% globally, 86% in Bangladesh |
| 3 | **Referral and repeat channel under-used** (the biggest channel, but no affordable system for solos) | 3 | 5 | 4 | **12** | Word of mouth 62–75% in surveys; Fiverr repeat buyers = 68% of revenue; NiceJob $75, Podium $399 with contracts, BNI $699/yr |
| 4 | **Marketplace dependence and take rates** (20% Fiverr, 0–15% Upwork, 18–33% plus 100% of trials Preply, 25% Wyzant; sudden visibility or account loss) | 4 | 4 | 4 | **12** | Fiverr buyers −13.6%; impressions-collapse threads; Preply account blocks |
| 5 | **Lower-cost-country payment and access barriers** (PayPal, $500 card cap, 5% tax) | 4 | 3 | 3 | **10** | Nepal sources above |
| 6 | **Creator monetisation fees** (Gumroad 10%+, Kajabi $143+) | 2 | 3 | 3 | **8** | Fee pages; competitor-written complaints |
| 7 | **Shrinking local markets** (Nepal development sector) | 4 | 2 | 2 | **8** | USAID terminations; OECD decline |

**What this ranking says.** [I] The money is lost at the point of *conversion* (#1) and in the *channel people already trust but don't systematise* (#3). Problem #2 is the most painful but also the most crowded, since every marketplace and lead seller claims to solve it. Solutions to #1 and #3 can be judged on whether the user earns more than they pay, which is your core test.
