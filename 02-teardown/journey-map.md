# Journey map: first purchase on Revolut investing

Built Sun Oct 18, 2026 in the **Nielsen Norman Group journey-map format**: actor, scenario and expectations, journey phases, actions, mindsets and emotions, opportunities. Emotions are plotted as one line across the phases. The actions come from Muhammad's own walkthrough (S numbers refer to [teardown log](../02-teardown/teardown-log.md)). **The feelings are hypotheses until the interviews**, and the map must be corrected on Wednesday with what people really said. (A drawn version of the feeling line existed in the chat's project doc; redraw it as an image or in the deck.)

- **Actor:** a first-time investor living in the Netherlands or EEA.
- **Scenario:** from opening the Invest tab to a first purchase they feel confident about.
- **Expectation:** quick, clear about cost, and suited to a long-term goal.

## Feeling line (hypothesis, scale 1 unsure to 5 confident)

| Phase | Hypothesised feeling | Note |
| --- | --- | --- |
| 1 Arrive and explore | 4 (curious) | Busy, but inviting |
| 2 Open the account | 2.5 | **Test in interviews**: effort, personal questions, passport |
| 3 Choose what to buy | 2 | **Test in interviews**: many paths, best-fit product hard to find |
| 4 Place the first order | 3 | Costs visible, but selfie step and wording may surprise |

Headline hypothesis: the lowest points are opening the account and choosing what to buy.

## Phases, actions and moments to test

| Phase | Screens | What the user does | Costs, rules and nudges | To test with interviews |
| --- | --- | --- | --- | --- |
| 1 Arrive and explore | S01-S05, S35, S39 | Opens the Invest tab and scrolls past Start investing, Popular first-time buys, a watchlist, five product types, top movers, most traded, a feed and events. | The only cost line is "Invest today, from €1". Risk wording appears only at the bottom of the tab. Top movers, buy/sell splits and Recommended buys are engagement features. | H2: do people feel pulled to single stocks and daily movers? |
| 2 Open the account | S06-S11, S13-S14 | Answers a goal question, income, net worth, a passport number and a block of acknowledgements, then waits for review. About 8 minutes to submit and about 2 more for approval. | Steps are required by regulation, per the app. Costs appear only as a linked ex-ante cost document inside the acknowledgements, and a Select all box accepts everything at once. | H4: did anyone nearly quit here? Did they open the documents? |
| 3 Choose what to buy | S15-S30, S37-S38 | Meets four paths: the Robo-Advisor (10 questions and a recommended portfolio), CFDs (a knowledge test that turned the walkthrough down), a single stock page with a Buy suggestion, and ETFs. | Robo-Advisor fee is 0.75 percent a year, not shown on its page. Starting amount shown as €1, €10 or €100. A banner says 1 free trade a month. Commission-free broad index ETFs sit about three taps deep. | H2 and H1: can people find a broad index fund, and how long does it take? |
| 4 Place the first order | S31-S34 | Enters an amount in dollars, sees the euro equivalent, picks an order type, passes a selfie security check and reaches the confirmation screen. | Confirmation shows "No fees" beside a €0.09 exchange fee. It does not say a free trade was used or what the next trade costs. | H1 and H3: did the fee wording make sense? Did the selfie step come as a surprise? |
| 5 After the order | Not observed | We stopped before Submit. | Unknown | Ask what happened after their first purchase. |

## Opportunities (hypotheses, ranked by how solid the evidence is)

1. Make the best-fit long-term products easier to reach for someone who said long-term growth. Evidence: S12, S27, S38 and the competitor comparison. Still needs interview support. **Strongest candidate.**
2. Make cost wording consistent: one starting amount, and say what the free trade covers. Evidence: S22, S24, S26, S34.
3. Check engagement features against a guardrail: they must not push first-timers to trade more. Evidence: S03, S27, S39 and the regulator research.

**Caveat:** all of this rests on one walkthrough by one person who already knows the product. The interviews can change every line.

## Later: Miro board

Planned for after the interviews (Phase 5), when the map has real feelings in it. Needs the Miro connector added to Claude Code, or build it by hand from this file.

## Update after six interviews (Oct 19)

The feeling line is corrected in [synthesis](../03-research/synthesis.md) section 8. Summary: arrive 4, open account 3, choose what to buy 1.5 to 2 (lowest point), place order 4, after the order 3. The "best-fit products are hard to find" opportunity is replaced by "choosing between near-identical funds is hard".
