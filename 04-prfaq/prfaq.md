[← Synthesis](../03-research/synthesis.md) · **Step 4 of 6: PR/FAQ** · Next: [PRD →](../05-prd/prd.md)

# PR/FAQ: choosing a first long-term fund

**Format:** Amazon "Working Backwards" PR/FAQ. A one-page press release written as if the feature has launched, followed by customer and internal FAQs, used to decide whether the idea is worth building before any design or code.
**Status:** v1.1, Oct 19, 2026. Author: Muhammad Ghazwan. Written after decision G2 (the problem) and agreed before the PRD.
**Important:** this is an independent student proposal. It is not a Revolut plan, and nothing here is endorsed by Revolut. Evidence is labelled **Primary** (own interviews and app walkthrough, Oct 18 to 19, 2026) or **Secondary** (public sources, date checked). Where Amazon's format uses invented customer and leader quotes, this version uses only real interview quotes and the author's own words.

---

## Press release

### Choose your first index fund with confidence, without leaving the app

**A plain-words comparison of funds that track the same index, and a two-line risk summary, help students make a first long-term investment they understand.**

**AMSTERDAM, [launch date to be set]:** Revolut's Invest tab now shows, side by side, what differs between funds that track the same index, such as the several S&P 500 funds a search returns today. Before a first order, a short summary says in plain words what could be lost and how to take money out. It is built for students and other first-time investors in the EEA, it uses only information the app already shows on each fund's page, and it never ranks or recommends a fund.

**The problem.** Students who decide to invest for the long term usually know the name of one index, most often the S&P 500. When they search it, they see several funds with near-identical names and different prices, and nothing that explains how they differ. In six interviews with students, five found it hard to choose between similar funds or to understand what they were buying. Two who had never invested searched "S&P 500", could not tell the results apart, and left the app to research elsewhere without buying. Two more avoided or delayed buying a fund for the same reason. *(Primary, n = 6.)*

**The solution.** When a student searches an index or opens a fund that shares its index with others, a "Same index, what's different?" button opens one screen with the funds side by side: yearly cost, whether income is paid out or reinvested, fund size, provider and the index tracked, each explained in one line. The facts already exist on each fund's page today; this puts them together at the moment of choice. Before the first order, two lines say that the value can fall, money can be lost, and how and how fast money can be withdrawn.

**From the author of this proposal.** "Students told me the hard part isn't finding a fund, it's choosing one. Revolut already knows what separates these funds. This simply puts it side by side, in words a first-timer understands." *(Muhammad Ghazwan.)*

**How to get started.** Open Invest, search "S&P 500" or "world", and tap "Same index, what's different?".

**What a student said.** "The problem wasn't finding products. It was knowing how to choose between them." *(Interview participant, anonymised.)*

---

## FAQ: customers

**What is new compared with the fund page today?** Today each fund's page shows its own cost, size and risk indicator (Primary, S44). To compare, you open each page and remember the numbers. The new view shows them together and explains each one.

**Which funds are included?** Funds that track exactly the same index. A fund on a different index (for example an S&P 500 *Growth* fund) or a CFD is not grouped with them.

**Is this advice?** No. It shows facts about each fund and does not say which one to buy. Nothing is ranked or marked "best". Under EU rules, investment advice is a personal recommendation presented as suitable for you; objective information without a suggestion is generally not advice (Secondary: ESMA guidance and law-firm summaries, checked Oct 19, 2026; legal review still needed).

**Will it cost me anything?** No. It is information inside the existing flow. Trading costs do not change.

**I already invest. Does anything change for me?** No. The view is optional, and buying works as before.

**What happens to my data?** Nothing new is collected. The view uses fund data the app already shows.

---

## FAQ: internal

**Who is the customer, and how many are there?** Students and other first-time investors in the EEA who open a broad index fund and do not buy. Their number is **to be measured**: count the people who search or open a broad index fund and place no order within 7 days. Revolut reports 68.3 million retail customers overall (Secondary, 2025 annual results, March 2026), but the size of this group is not public.

**Why should Revolut build this?** Revolut's Wealth revenue grew 31 percent to $876m in 2025, and it rolled out zero-commission ETF investment plans in the EEA (Secondary, 2025 annual results, March 2026). Broad funds are now cheap to reach. The interviews suggest the stall is the choice itself. **Hypothesis, not measured:** a confident first fund purchase leads to repeat investing and a longer customer relationship.

**What is the primary metric?** Of students who open a broad index fund page, the share who place a first order for a broad index fund within 7 days. **Baseline: to be measured.** The target is set from the baseline before the test.

**What must not get worse (counter-metrics)?** Trades per month among first-timers; the share of single-stock or leveraged purchases among first-timers; fee complaints and withdrawals within 30 days of a first order.

**What will it take to build?** It reuses data the app already holds (S44) and adds one screen, one button and two lines of copy. It needs design, mobile engineering, data science for the experiment, and compliance sign-off. A size estimate has to come from the team; none is given here.

**What else did we consider?**

| Option | Why not chosen |
| --- | --- |
| Do nothing | Two of six students left without buying at this exact screen |
| Move "Get started with ETFs" higher in search | Cheap and worth testing alongside, but a general article does not answer "which of these three?" |
| Recommend a default fund | Likely to count as advice; also not what students asked for ("I don't think I need someone to tell me what to buy", P6) |
| Point first-timers to the Robo-Advisor | A different product with a yearly fee; does not help someone who has already chosen to buy an index fund |
| **Side-by-side comparison in plain words** | **Chosen:** matches what students asked for, uses existing data, stays information |

**What could go wrong?** The view could read as a recommendation. It could add clutter. It could push people to buy sooner than they are ready to, so the risk lines stay neutral and the counter-metrics are watched.

**What is out of scope?** Onboarding, fees and the free-trade allowance (all failed our pre-set decision rule), robo-advice, recurring buy, CFDs, single-stock discovery, anything that names a "best" fund, and engagement features.

**What is not proven?** Six young students, five on Revolut, two in a finance society: early evidence, not proof. Interviews 3 to 6 were voice-recorded and transcribed with an AI tool, then checked by the author. The search screen itself is captured (S40 to S45, Oct 19): three S&P 500 funds appear with only name, price and a three-word description.

**Riskiest assumption, and how we test it first.** That seeing the differences side by side resolves the stall. Test with a clickable prototype and 5 to 8 students outside the finance society before any build.

**What would make us stop?** If more students find the choice easy, if the prototype does not improve comprehension, or if the stall disappears once a student has a goal (meaning the root cause is "no goal", not fund choice).

---

**Sources.** Primary: interviews 1 to 6 (private notes, summarised in [synthesis](../03-research/synthesis.md)) and the app walkthrough ([teardown log](../02-teardown/teardown-log.md), S01 to S45). Secondary: Revolut 2025 annual results (March 2026, as recorded in the teardown log); ESMA guidance on the definition of investment advice, via ESMA pages and law-firm summaries, checked Oct 19, 2026.

---

[← Synthesis](../03-research/synthesis.md) · Next: [PRD →](../05-prd/prd.md)
