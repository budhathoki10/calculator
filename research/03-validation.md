# 03 — Validation: five rounds, eliminations and scores

Labels are as in `01-problems.md`: **[SE]** search excerpt (page not opened), **[I]** inference, **[A]** assumption. Evidence already cited in 01 and 02 is referred to, not repeated. Each round below adds **new** evidence.

## Fixed scoring rules (stated before any scoring, not changed afterwards)

| Criterion | Code | Weight |
|---|---|---|
| Evidence of painful, frequent demand | D | 20% |
| Users plausibly earn more than they pay | E | 20% |
| Willingness to pay (people already pay for similar things) | W | 15% |
| Can reach the first 100 paying users without a big budget | R | 15% |
| Differentiation from existing products | Df | 10% |
| Feasible for a solo founder in Nepal (payments, law, cost) | F | 10% |
| Retention (a reason to keep paying every month) | Rt | 10% |

- Each criterion is scored 1–10. Weighted total = Σ(score × weight), out of 10.
- **(LC)** marks a low-confidence score, meaning it rests mainly on inference or on one weak source.
- **Thresholds, set before scoring:**
  - Recommend building only if the total is ≥ 7.0 **and** no criterion is ≤ 3.
  - 6.0–6.9 means test cheaply, without code, before building.
  - Below 6.0 means not good enough.
- **Kill criteria** are the ones in your brief, applied per round.

---

## Round 1 — Demand and pain

Question: is there real, repeated, recent evidence that people want this and already spend money or time on it? Kill if the evidence is thin, old, or comes only from sellers of similar tools.

New evidence gathered this round:

- **Upwork alerts (#1):** Upwork ended RSS feeds after 20 August 2024 [SE support.upwork.com/…/RSS-deprecation]. A Hacker News thread discussed the removal [SE hn.svelte.dev/item/41174888]. Paid replacements appeared (Vollna, UpworkAlerts, UpHunt "up to $89 per month" [SE alternativeto.net/software/uphunt]). A competitor's analysis of about 44,863 jobs says "six in ten proposals arrive within the first hour" [SE uphunt.io/blog/how-many-proposals-upwork-jobs-get-2026, competitor].
- **Intent monitoring (#3):** GummySearch had a paying customer base until it closed in November 2025 [SE gummysearch.com/closing-time].
- **Local review and referral engine (#4) and photographers (#7):** the BrightLocal 2026 survey shows consumer reliance on recent reviews (01). The Knot and Thumbtack spend complaints (01) show money already spent on acquisition.
- **Freelancer reactivation (#5):** referrals are the top channel (62–75%) and Fiverr repeat buyers are 68% of its revenue (01). Freelancers on the Upwork forum report repeat-client rates "around the 30% mark" [SE community.upwork.com, old]. That is a forum anecdote.
- **Tutors (#6):** a Blind poster wants to escape Wyzant's "25% cut" and find students directly [SE teamblind.com/post/where-to-find-tutoring-clients-rntqm6nl, date unknown]. A Wise vendor blog describes one tutor who got "60% of his new students via referrals after offering 20% discounts on referrals" [SE wise.live/blog, vendor, single case]. TES says most private-tuition work "comes through word of mouth" [SE tes.com/magazine/archive/private-tuition, date unknown]. **No tutor survey with a percentage was found.**
- **Development-sector digest (#15):** new negative evidence. US aid termination in Nepal (34 projects, $329M, unverified) [SE kathmandupost.com 12 Mar 2025]; about 30,000 jobs lost, an estimate [SE kathmandupost.com Aug 2025]; OECD official development assistance falling for a third year in 2026 [SE oecd.org Jun 2026].
- **Nepal ideas (#12, #13, #18):** searches found app listings and undated promotional articles only. No complaint data, no spend data, no surveys.

### Round 1 verdicts

| # | Idea | Verdict | Why |
|---|---|---|---|
| 1 | Upwork Job Radar | Survives | Repeated, recent evidence: RSS removal, several paid tools, forum complaints about unviewed proposals |
| 2 | Profile/proposal coach | Survives | Unviewed-proposal complaints; sellers buy proposal templates |
| 3 | Intent monitor | Survives | GummySearch had paying users until 2025 |
| 4 | Local review and referral engine | Survives | Paid category (NiceJob, Podium, ReviewNudger); consumer review reliance; lead-spend pain |
| 5 | Freelancer client garden | Survives | Referrals and repeat are the dominant channel in independent surveys and filings |
| 6 | Tutor growth kit | Survives (LC) | Commission pain documented; referral evidence is anecdotal |
| 7 | Photographer rebooking | Survives | The Knot spend complaints; photographers pay for CRMs |
| 8 | GBP autopilot | Survives | Google's own statement on reviews and ranking; paid tools exist |
| 9 | AI receptionist | **Killed** | The demand evidence found is almost entirely vendor or vendor-affiliated blogs (trillet.ai, powerednow.com, ringly.io). No independent user voices were found. |
| 10 | Online referral circle | **Killed** | Demand evidence for paid referral groups is BNI's own self-reported figures (a seller). No evidence that people want an *online* version. Free Alignable and Slack groups exist. |
| 11 | Paid-lead accelerator | Survives | Strong, independent pain (FTC order, Trustpilot, Bark reviews) |
| 12 | Nepal tuition marketplace | **Killed** | Thin: app-store listings only; no Nepal data on tutor pain, spend or commissions |
| 13 | Nepal home-services marketplace | **Killed** | Thin and undated; several incumbents; comparable Indian startups (DoorMint, Taskbob) shut down [SE inc42.com] |
| 14 | Curated South Asian talent marketplace | **Killed** | No buyer-side evidence that overseas small businesses want another curated marketplace; freelancer pain alone does not prove buyer demand |
| 15 | Development-sector ToR digest | **Killed** | Recent evidence shows the buyer side shrinking (US aid termination; OECD third yearly decline). The only paid-digest evidence is Devex itself, a seller. |
| 16 | Sponsor finder | Survives | Who Sponsors Stuff revenue claim; Passionfroot raised funding (parsers.vc, unverified) |
| 17 | Client-acquisition sprint | Survives | Finding clients is the #1 challenge (Payoneer 73%) |
| 18 | Hamro Page (Nepal) | **Killed** | No Nepal-specific evidence of pain or spend; Facebook and other platforms it would rely on were blocked nationally in September 2025 |

### Scores after Round 1 (11 survivors)

| # | D 20% | E 20% | W 15% | R 15% | Df 10% | F 10% | Rt 10% | **Total** |
|---|---|---|---|---|---|---|---|---|
| 1 Upwork Radar | 7 RSS gone, paid tools, complaints | 6 (LC) one contract covers a year; lift unproven | 7 Vollna, GigRadar, Freelancer Plus are paid | 7 (LC) Nepali freelancers are the founder's own community | 2 Vollna at $4/mo plus native Upwork alerts | 3 Upwork API approval is manual; scraping not allowed | 5 needed only while job-hunting | **5.70** |
| 2 Proposal coach | 6 unviewed-proposal complaints | 5 (LC) | 5 templates sell cheaply | 7 (LC) | 2 Upwork Uma built in | 7 | 3 one-off need | **5.20** |
| 3 Intent monitor | 5 | 5 (LC) | 5 (LC) | 5 | 3 F5Bot free | 2 Reddit licence, X pay-per-use | 5 | **4.50** |
| 4 Local engine | 6 | 6 (LC) | 6 NiceJob $75, ReviewNudger $29 | 3 (LC) US/UK local providers, far from founder | 4 | 8 | 6 | **5.55** |
| 5 Client garden | 6 | 6 (LC) | 5 Dex $12, HoneyBook | 5 (LC) | 4 | 8 | 5 | **5.60** |
| 6 Tutor kit | 6 | 7 (LC) one student = $64–240/mo | 5 TutorBird $14.95 | 5 (LC) | 5 | 8 | 6 | **6.00** |
| 7 Photographers | 5 | 6 (LC) | 6 Studio Ninja $24+, The Knot $4–6.5k/yr | 3 | 3 | 8 | 6 | **5.25** |
| 8 GBP autopilot | 6 | 5 (LC) | 6 BrightLocal $39+ | 3 | 2 | 6 | 5 | **4.85** |
| 11 Lead accelerator | 7 | 6 (LC) | 7 pros pay $10–100/lead | 2 US trades only | 2 | 3 | 6 | **5.05** |
| 16 Sponsor finder | 5 | 5 (LC) | 5 | 5 | 2 | 5 | 5 | **4.70** |
| 17 Sprint | 7 | 5 (LC) | 4 | 6 | 3 | 3 | 3 | **4.80** |

---

## Round 2 — Competition and differentiation

Question: who already solves it, at what price, and what do their users complain about? Kill if a free or dominant product already does it well and we have no clear, defensible difference.

New evidence this round:

- **Upwork's own tools:** Uma drafts proposals; Basic users get limited use and "Freelancer Plus gives full access" [SE support.upwork.com/hc/en-us/articles/22983791592595]. Saved searches with notifications replaced RSS [SE gigradar.io/blog/upwork-rss-feed]. Vollna's cheapest tier is $4/mo [SE softwaresuggest.com]. No Vollna complaints were found in search (01 has a positive Aug 2024 review). [I] The cheapest competitor is cheaper than any price that covers Dodo's $0.40 fixed fee plus support.
- **Free intent monitor:** F5Bot is "a free service" with "no restrictions on the number of terms" (Reddit and Hacker News) [SE stork.ai/alternatives/f5bot].
- **Local SEO tools:** BrightLocal from $39, Localo from $69, Paige $99 [SE Capterra / Software Advice 2026]. The Google Business Profile app is free.
- **Thumbtack integrations:** Jobber creates a client and request for "each new direct lead in Thumbtack" [SE help.getjobber.com/en/articles/jobber-and-thumbtack-integration]. Housecall Pro's Job Inbox does the same [SE help.housecallpro.com/en/articles/6499957]. "Thumbtack only supports one third-party integration at a time" [SE support.contractorplus.app/en/articles/11576511].
- **Creator sponsors:** Passionfroot is free for creators [SE help.passionfroot.me]. Who Sponsors Stuff already covers "500+ newsletters" and "3,000+ email sponsors" [SE inboxreads.co].
- **Photographers:** Pixieset Studio Manager has a **free** tier inside the gallery product photographers already use; paid tiers are $10–$50 [SE costbench.com/software/photography-studio-software/pixieset].
- **Tutor tools:** TutorBird is rated 4.8 from 265 Capterra reviews. Its complaints are slow support and missing package and scheduling features. **No referral or parent-review feature was found** [SE capterra.com/p/181623/TutorBird/reviews, updated 13 Mar 2026].
- **Freelancer CRMs:** Dex has only 3 Capterra reviews [SE capterra.com/p/275020/Dex]. folk is rated 4.5 (G2, 318 reviews), with complaints about no mobile app and key features locked in Premium [SE prospeo.io/s/folk-pricing-reviews-pros-and-cons, vendor-written]. HoneyBook's February 2025 price rise drew complaints (01). **No product found that focuses on getting repeat and referral work from past clients for freelancers.**
- **Local review tools:** NiceJob's "Expensive" con; Podium's cancellation complaints and 12-month contracts (01). ReviewNudger at $29/mo [SE getapp listings] narrows the price gap.

### Round 2 verdicts

| # | Verdict | Reason |
|---|---|---|
| 1 Upwork Radar | **Killed** | Cheap incumbents (Vollna $4), Upwork's own free notifications, and Upwork could ship the same feature at any time. No defensible difference. |
| 2 Proposal coach | **Killed** | Upwork's built-in Uma does the core job; free general chatbots do the rest |
| 3 Intent monitor | **Killed** | F5Bot does the Reddit and Hacker News version free. Beyond those, data access is the barrier (see Round 4 notes in the scoring). |
| 4 Local engine | Survives (weak) | Difference: solo price point plus manual, personal sending with no messaging API cost plus a referral focus. ReviewNudger at $29 and Google's free review link limit how defensible this is. |
| 5 Client garden | Survives | No focused competitor found; personal CRMs are generic and thinly reviewed |
| 6 Tutor kit | Survives | No tutor tool found that does referral, review or progress-note growth; the admin incumbent (TutorBird) is liked but has no growth features |
| 7 Photographers | **Killed** | Pixieset's free studio manager sits inside the tool photographers already use; Studio Ninja and HoneyBook cover CRM. A rebooking feature is easy for them to add. |
| 8 GBP autopilot | **Killed** | BrightLocal ($39) and others, plus Google's free app; no difference |
| 11 Lead accelerator | **Killed** | Jobber and Housecall Pro already integrate Thumbtack leads, and Thumbtack allows one integration per pro, so a newcomer must displace the pro's whole job-management system |
| 16 Sponsor finder | **Killed** | Passionfroot is free for creators with a sponsor network; Who Sponsors Stuff has the data lead |
| 17 Sprint | Survives (weak) | Crowded with courses, but accountability plus tooling could differ. Decided in Round 4. |

### Scores after Round 2 (4 survivors)

Differentiation re-scored with this round's evidence; other scores unchanged.

| # | D | E | W | R | Df | F | Rt | **Total** |
|---|---|---|---|---|---|---|---|---|
| 4 Local engine | 6 | 6 (LC) | 6 | 3 (LC) | 4 ReviewNudger $29 is close | 8 | 6 | **5.55** |
| 5 Client garden | 6 | 6 (LC) | 5 | 5 (LC) | 5 no focused tool | 8 | 5 | **5.70** |
| 6 Tutor kit | 6 | 7 (LC) | 5 | 5 (LC) | 6 no growth-focused tutor tool | 8 | 6 | **6.10** |
| 17 Sprint | 7 | 5 (LC) | 4 | 6 | 3 | 3 | 3 | **4.80** |

---

## Round 3 — Economics for both sides

### My side: price, fees, running costs, acquisition cost

New evidence:

- **Dodo fees** (if Dodo onboards a Nepal-ID merchant; see Round 4): 4% + 40¢ base, +1.5% for customers outside the USA, +0.5% for subscriptions; $1 per refund; $30 per dispute. Payouts: "Free with Fee of $5 if payout <$1000" (pricing page) vs "0.5% + $5 per payout" (docs). The two conflict [SE dodopayments.com/pricing; docs.dodopayments.com/miscellaneous/pricing-and-fee-structure].
- [I] On a $12/mo non-US subscriber: 6% × $12 = $0.72, plus $0.40 = **$1.12 per charge (9.3%)**. On a US subscriber: 4.5% × $12 + $0.40 = **$0.94 (7.8%)**. A $4/mo price would lose 14–16% to fees, which is why sub-$8 pricing is unattractive.
- **Email** (for the founder's own transactional mail, not customer messaging): Resend free for 3,000 emails/mo (100/day), Pro $20/mo for 50,000; Postmark $15/mo for 10,000 [SE solodevstack.com; freetier.co, 2026].
- **Hosting:** the price was not found in this research (**unknown**; check Hetzner or Render pricing pages). [I] An app with no messaging API, no AI calls per message and no heavy data stays small, but the dollar figure is unknown.
- **Messaging:** $0. Messages go through the user's own WhatsApp, SMS or email via deep links (`wa.me/`, `sms:`, `mailto:`), so there is no WhatsApp Business API charge. For comparison, Meta's per-message billing since 1 July 2025 charges about ₹0.78 for a marketing message in India [SE exchange4media.com], which a user-sends design avoids.
- **Churn benchmarks:** Recurly's overall subscription churn is 3.60%/month across industries; a B2C figure of 6.5%/month is attributed to Recurly by a third party [SE withorb.com; eightx.co, 2026]. **Small-business-tool churn for solo providers is unknown.** [I] Use 5–7%/month as a planning range; at 6%/month the average customer lifetime is about 17 months.
- **Acquisition cost:** **unknown** for all ideas. No sourced CAC exists for these segments. [A] Assume no paid ads for the first 100 users (channels in `04`). Test: track hours and money per paying user during the waitlist test.

[I] At $12/mo, 17-month average lifetime and about $1.05 average fees, lifetime gross is about $186 per customer before support and hosting. This works only if acquisition is mostly organic. Paid ads would need a CAC well under $100; that figure is unknown.

### User side: do they plausibly earn more than they pay in the first few months?

| Idea | Price [A] | What has to be true | Inputs | Verdict |
|---|---|---|---|---|
| 6 Tutor kit | $12/mo | **One extra student in the first ~5 months**, if that student stays at least one month. Covers 5 months of fees. | One student weekly at Preply's adult average of $16/hr = $64/mo [SE preply.com]; at Wyzant's marketed $35–60/hr = $140–240/mo [SE wyzant.com]; South Asia tutors $8–15/hr = $32–60/mo [SE review site, weak] | Plausible. Supported by the referral norm (anecdotal) and Wyzant's acknowledgement that tutors have outside students. **The mechanism (prompted parent referrals) is untested.** |
| 5 Client garden | $10/mo | One extra project a year worth ≥ $120, **and** the user must have past *direct* clients to reactivate | Nepal freelancers average $4,723/yr [SE IIDS]; 70% of freelancers get most work from marketplaces [SE Payoneer 2023], whose clients cannot be taken off-platform for 24 months [SE Upwork] | Plausible only for freelancers who already have direct clients. That excludes much of the founder's home audience. |
| 4 Local engine | $12/mo | One extra job per quarter with ≥ $36 margin | Job values by trade **unknown**; Google says reviews affect ranking [SE support.google.com/business/answer/7091] | Plausible but unsourced job values (LC) |
| 17 Sprint | $99 + $10/mo | One client from the cohort | Coaching outcome rates unknown | Weak; also see Round 4 |

**Kill check:** the brief says kill if the return depends on *unsupported* assumptions. For 4, 5 and 6 the key mechanism, that prompted personal asks produce extra referrals or repeat work, is **weakly supported**, not unsupported:

- referred customers are worth at least 16% more and churn less (Schmitt, Skiera & Van den Bulte, *Journal of Marketing* 75, Jan 2011, 10,000 German bank customers) [SE faculty.wharton.upenn.edu PDF; old, different industry];
- referrals are the top freelance channel in independent surveys;
- repeat buyers are 68% of Fiverr's marketplace revenue (filing).

The often-quoted "83% willing to refer, 29% do" (Texas Tech) could not be traced to an original study, so it is **not used** [SE entrepreneur.com 2016]. No idea is killed in Round 3. 4, 5 and 6 carry an explicit gating test (Round 5 and `04`).

### Scores after Round 3

E is re-scored with the worked numbers; F includes fee drag.

| # | D | E | W | R | Df | F | Rt | **Total** |
|---|---|---|---|---|---|---|---|---|
| 4 Local engine | 6 | 5 (LC) job values unknown | 6 | 3 (LC) | 4 | 7 fees 8–9% at $12 | 6 | **5.25** |
| 5 Client garden | 6 | 5 (LC) needs existing direct clients | 5 | 5 (LC) | 5 | 7 | 5 | **5.50** |
| 6 Tutor kit | 6 | 7 (LC) one student pays for ~5 months even at $8–15/hr | 5 | 5 (LC) | 6 | 7 | 6 | **6.00** |
| 17 Sprint | 7 | 4 | 4 | 6 | 3 | 3 | 3 | **4.60** |

---

## Round 4 — Feasibility and risk

New evidence:

1. **Payments to the founder.**
   - Dodo's accepted-countries page applies to designations "on or after March 23, 2026". Eligibility follows the country that issued the founder's ID, and payouts go only to listed countries. The excerpt was cut off before "N", so **Nepal's current status is unconfirmed** [SE docs.dodopayments.com/miscellaneous/accepted-countries-and-territories]. An older, mirrored Merchant Acceptance page listed Nepal [SE translate.goog mirror of docs.dodopayments.com/miscellaneous/merchant-acceptance]. Dodo's feedback board has users "blocked at onboarding" in under-served countries [SE feedback.dodopayments.com].
   - Dodo **supports individual accounts**: "Individual account needs KYC + Bank Form"; KYC via Persona (government ID plus selfie); the bank-account name must match the ID; review takes "one to three business days" [SE docs.dodopayments.com/miscellaneous/verification-process; /tax-forms; dodopayments.com/blogs/kyb-verification].
   - Paddle: "built to serve software companies"; Nepal is absent from its unsupported list in the excerpt, but the authoritative check is its `/countries` API [SE paddle.com/support/aup; developer.paddle.com].
   - Lemon Squeezy pays out by PayPal in 200+ countries [SE docs.lemonsqueezy.com/help/getting-started/getting-paid], but PayPal receiving in Nepal is contested (01), so it is **not a safe fallback**. Creem pays out in 86 countries; Nepal **unknown** [SE docs.creem.io].
   - **Fit with the business model:** a SaaS subscription sold to individuals is squarely what Dodo and Paddle accept. Dodo excludes "coaching calls, or 'done-for-you' consulting" and services sold as digital unless "largely productized and automated" [SE docs.dodopayments.com/miscellaneous/merchant-acceptance]. Paddle prohibits "human services that are not related to a software offering (e.g., pure consulting or advisory services, including … coaching …)" [SE paddle.com/support/aup].
2. **Money between users:** none of 4, 5 or 6 touches it. If a tutor offers a referral reward (for example a free lesson), the tutor gives it directly; the product only records it. This avoids NRB payment licensing [SE pradhanlaw.com, Licensing Policy 2079 (2023)] and Dodo's escrow exclusion.
3. **Nepal law for the founder's own income:** foreign-currency receipts for software services face a 5% advance tax under the Finance Act 2080 [SE samriddhi.org]. NRB's 2023 facilities for IT and service exporters exist [SE sharesansar.com 8 Aug 2023]. These are compliance tasks, not blockers.
4. **Platform rules:**
   - Google Business Profile: "Business Profiles aren't for online-only businesses"; online-only tutors and freelancers are **not eligible**, while tutors who visit students or have a location are [SE support.google.com/business/answer/7039811, official]. [I] For online tutors (#6) and freelancers (#5), the review destination must be the product's own verified-review page (or Trustpilot), not Google.
   - FTC rule (effective 21 October 2024): bans fake reviews, undisclosed-connection reviews and paying for positive or negative reviews; penalties up to "nearly $52,000 per violation" [SE ftc.gov press release Aug 2024; hunton.com]. [I] Review pages must collect only from real clients, show all reviews (no gating), and any referral reward must reward the *referral*, never a review.
   - Messaging: user-sent, one-to-one messages to the user's *own* clients via deep links; not bulk, no scraping, no automation of WhatsApp or LinkedIn.
5. **Data protection:** the product stores the users' clients' names and contact details. [I] The founder is a data processor for EU/UK users (GDPR), so a data-processing agreement, deletion and export are needed. Nepal's Individual Privacy Act requirements were **not researched (unknown)**. Test: one hour with a Nepali lawyer (see `04`).
6. **Solo build and support:** [I] All three are CRUD-plus-reminders apps with templates; no real-time systems and no marketplace liquidity. One person can build and support them.

### Round 4 verdicts

| # | Verdict | Reason |
|---|---|---|
| 4 Local engine | Survives | No legal or technical blocker; distribution from Nepal is the problem (scored under R) |
| 5 Client garden | Survives | No blocker; no Google reviews for online-only freelancers (own review page instead) |
| 6 Tutor kit | Survives | No blocker; must not facilitate off-platform moves of Preply or Wyzant students; online-only tutors use own review page |
| 17 Sprint | **Killed** | Both payment routes exclude coaching and done-for-you services. Founder time also does not scale. Unfixable under the payment constraint. |

**Shared risk, not yet a kill:** if Dodo does **not** currently onboard Nepal-ID individuals **and** Paddle also declines, every idea is blocked. This must be confirmed in writing **before any build** (first item in `04`).

### Scores after Round 4

| # | D | E | W | R | Df | F | Rt | **Total** |
|---|---|---|---|---|---|---|---|---|
| 4 Local engine | 6 | 5 (LC) | 6 | 3 (LC) | 4 | 6 Dodo-Nepal unconfirmed | 6 | **5.15** |
| 5 Client garden | 6 | 5 (LC) | 5 | 5 (LC) | 5 | 6 same | 5 | **5.40** |
| 6 Tutor kit | 6 | 7 (LC) | 5 | 5 (LC) | 6 | 6 same | 6 | **5.90** |

---

## Round 5 — Adversarial review

A separate agent with no stake in the ideas read files 01–03 and ran about 35 new searches under the same labelling rules. It wrote the strongest honest failure case for each survivor. Its full report is in `03a-adversarial-review-raw.md`. Below, each point gets an answer with evidence, or is **conceded**. Its two most decisive claims were re-checked with my own searches before relying on them:

- **HoneyBook:** confirmed. HoneyBook's own help centre describes AI follow-up suggestions for "unconverted leads … who haven't engaged in more than 3 months". Separately: "When HoneyBook identifies that a project might be completed, it'll suggest you send a referral request", with a referral link to a lead form [SE help.honeybook.com/en/articles/11669595; /9055403; August 2025 product update].
- **Jobber:** confirmed. "Referrals as a $29 USD per month add-on for all plans … Marketing Suite for $79USD per month … referrals, reviews, and campaigns"; Reviews add-on $39/mo [SE help.getjobber.com/hc/en-us/articles/20959257809815, official help].
- **Act! survey:** confirmed. "Only about 1 in 10 sole proprietors reported using CRM software" (Act!/Researchscape, 1,146 US SMBs, May 2022, old) [SE marketingcharts.com/…-226721; businesswire.com 26 Jul 2022].

### Points against all three ideas

| Point | Answer |
|---|---|
| A1 The founder may not be able to get paid (Dodo's Nepal status unconfirmed; users blocked at onboarding) | **Conceded as an open risk.** Not a reason to prefer one idea over another; it gates all of them. It must be confirmed in writing first (see `04`). |
| A2 Only 11% of sole proprietors use CRM software (2022) | **Conceded.** Re-checked and confirmed. It cuts both ways ("under-served" vs "don't want it"), and no evidence was found that settles which. Unanswered. |
| A3 Micro-business churn about 8.9%/mo, 4.6-month average contracts | **Partly answered.** The figure comes from vendor blogs that probably share one dataset, so it is weak. But I have nothing better than Recurly's 3.6–6.5%, so the lifetime range has to widen to about 11–28 months. That widening weakens the economics. |
| A4 No study shows a prompted *ask* adds referrals rather than taking credit for ones that would happen anyway; referral coupons underperform regular coupons (Iyengar) | **Conceded.** My Round 3 support (Schmitt et al. 2011) shows referred customers are *more valuable*, not that *asking* creates them. This is the central claim of all three ideas and no evidence answers it. |
| A5 Spreadable (referral tool for small businesses) shut down months after launch despite about $550k invested; Ambassador reached end of life in 2021 | **Partly answered.** Old precedents (2010, 2021), and Spreadable sent emails from a service, which the user-sends design avoids. But a better-funded attempt at the same job failed, and I have no counter-example of a solo-priced referral tool succeeding. |
| A6 Attribution: more than half of small firms don't track customer sources (22% no tracking, 34% informal) [SE pymnts.com 2026] | **Conceded.** If users can't see the return, they can't verify "earn more than you pay", and that undermines retention, the reason they'd keep paying. |
| A7 The home market can't pay USD easily; Indian buyers pay about 50% less; the $500 dollar-card cap | **Conceded.** Consistent with my own 01 findings. |

### #4 Local review-and-referral engine

| Reviewer's point | Answer |
|---|---|
| 1 Google gives a free review link and QR, and suggests sending via WhatsApp [SE support.google.com/business/answer/16816815] | **Conceded.** The review half of the product is free from Google. |
| 2 Jobber ($29 Referrals, $79 suite), Housecall Pro (auto review on job completion) and Fresha already trigger asks automatically | **Conceded**, re-checked for Jobber. #4 has no trigger event; the incumbents do. |
| 3 Manual sending makes users drop off | **Conceded**, by inference; the Dex founder's account supports it. |
| 4 Reach is close to nil | **Conceded.** R was already 3. |
| 5–8 (price-switchers, "full" churn, incentive risk, half-proven mechanism) | 6 partly answered (review recency gives a reason to keep asking, BrightLocal 74%); the others are conceded. |

**Verdict: killed.** The strongest failure case (free Google tools plus incumbents with automatic triggers plus no reach) stands unanswered.

### #5 Client garden

| Reviewer's point | Answer |
|---|---|
| 3 HoneyBook shipped reactivation, timed referral asks and referral-source tracking in August 2025 | **Conceded, re-checked.** Round 2's "no focused competitor found" is overturned for the paying end of the segment. |
| 2 Personal CRM is a graveyard; Dex (YC-backed) took about 2.5 years to reach 1,000 customers at an LTV of about $231 | **Conceded** (old figures, but no counter-evidence). |
| 1 The paying segment excludes the founder's own marketplace-dependent community | **Conceded.** Already flagged in Round 3. |
| 4–8 (free Monica and calendar substitutes; too infrequent for a subscription; asking is contested; attribution; regional price) | **Conceded.** No evidence answers them. |

**Verdict: killed.** The strongest failure case stands unanswered.

### #6 Tutor growth kit

| Reviewer's point | Answer |
|---|---|
| 1 Full tutors don't need it; empty tutors have no parents to ask | **Not answered.** The paying "middle" segment (established, not full) has unknown size. No survey of tutors' capacity or enquiry levels was found. |
| 2 Capacity cap plus seasonality ("summer break can cut tutoring revenue") | **Partly answered.** The waitlist is useful precisely when a tutor is full, and UK demand is broad (Sutton Trust: 29% of secondary pupils have ever had a private tutor, 11% in 2025 alone [SE suttontrust.com Private-Tutoring-2026.pdf, Feb 2026]). Neither fixes summer churn. |
| 3 TutorBird holds the data and can add the feature; Wyzant has its own referral programme; cheaper tools in South Asia (Wise, Teachmint) | **Partly answered.** No evidence found that TutorBird has shipped growth features (its Capterra complaints are about admin). Wyzant's programme is for bringing students *onto* Wyzant, and those lessons carry a 9% student service fee [SE support.wyzant.com fee page]. But copy risk is real and unanswered. |
| 4 The most motivated users (escaping marketplace commission) are the ones the product must refuse | **Conceded.** This removes the emotional hook. |
| 5 Mechanism evidence is one vendor anecdote; referral coupons underperform | **Conceded** (same as A4). |
| 6 Nepali tutors earn NPR 5,000–30,000 a month per student but can't pay USD easily; paying markets are unreachable | **Conceded.** |
| 7 Progress notes are a chore; tutors ask for admin, not growth | **Partly answered** (AI drafting cuts the effort), but the demand signal is conceded. |
| 8 Data about minors raises the compliance bar | **Conceded** as added cost, not a blocker. |
| 9 Tutorspree and FEV Tutor shut down | **Answered.** Those are marketplace and school-contract businesses, a different model; little weight. |

**Verdict: killed.** The strongest failure case (the full-or-empty paradox plus an unproven ask mechanism) stands unanswered. The kill criterion requires elimination.

### Final scores after Round 5 (recorded for the record, although all three were eliminated)

| # | D | E | W | R | Df | F | Rt | **Total** | Changes from Round 4 |
|---|---|---|---|---|---|---|---|---|---|
| 4 Local engine | 6 | 5 (LC) | 6 | 3 | **2** | 6 | **5** | **4.85** | Df: Google free link and Jobber/HCP triggers. Rt: "full" churn. |
| 5 Client garden | 6 | **4** (LC) | 5 | **4** | **2** | 6 | **4** | **4.55** | Df: HoneyBook shipped the core. E/R: home audience excluded. Rt: infrequent use. |
| 6 Tutor kit | **5** | **6** (LC) | 5 | **4** | **5** | 6 | **4** | **5.05** | D: full-or-empty paradox. E: mechanism unproven. R: no channel found. Df: copy risk. Rt: seasonality and capacity. |

### Elimination log (all 18 ideas)

| Round | Killed | Main reason |
|---|---|---|
| Pre-screen | LinkedIn automation, off-platform client mover, scraped-lead cold email, escrow marketplace, incentivised reviews | Ethics, law, platform terms |
| 1 Demand | 9 AI receptionist, 10 referral circle, 12 Nepal tuition marketplace, 13 Nepal home services, 14 South Asian talent marketplace, 15 development-sector digest, 18 Hamro Page | Evidence thin, seller-only, or shows a shrinking market |
| 2 Competition | 1 Upwork Radar, 2 proposal coach, 3 intent monitor, 7 photographers, 8 GBP autopilot, 11 lead accelerator, 16 sponsor finder | Free or dominant incumbent, no defensible difference |
| 3 Economics | none | 4, 5 and 6 carried forward as weakly supported, low confidence |
| 4 Feasibility | 17 client-acquisition sprint | Dodo and Paddle both exclude coaching and done-for-you services |
| 5 Adversarial | 4 local engine, 5 client garden, 6 tutor kit | Strongest failure case unanswered |

**Result: no idea survives all five rounds.** The highest final score is 5.05 (tutor kit), below the 6.0 "test first" bar and far below the 7.0 "build" bar set before scoring.
