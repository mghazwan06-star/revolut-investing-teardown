# Synthesis: what six student interviews say (Phase 3)

Drafted Mon Oct 19, 2026 from six private interview notes (not published). **Status: Decision G2 made by Muhammad on Mon Oct 19: option 1.** All evidence is Primary (his own interviews) unless marked Secondary. Participants appear by number only. Quotes are under 15 words and taken from the interview text.

Plain-language key: *affinity grouping* = put every friction moment on one board and group the ones that mean the same thing. *Unprompted* = the person raised it before we asked about it. *Severity* = how much it cost them: 1 annoyed, 2 delayed, 3 stopped or lost money.

## 1. Who and how (so the evidence can be judged)

| | P1 | P2 | P3 | P4 | P5 | P6 |
| --- | --- | --- | --- | --- | --- | --- |
| Segment | Invests regularly | Started recently | Started recently | Never invested | Invests regularly | Never invested |
| App | Trading 212 | Revolut | Revolut | Revolut | Revolut + crypto exchange | Revolut |
| Student | Yes | Yes | Yes | Yes | Yes (finance society) | Yes (finance society) |
| Reached a cost screen | Yes | Yes | Yes | No | Yes | No |
| Screen task done | No | No | Yes | Yes | Yes | Yes |

Method: P1 and P2 are typed notes taken during the call; P3 to P6 are voice recordings turned into text with an AI tool and checked by the researcher. Interviews followed [interview guide](../03-research/interview-guide.md).

## 2. Affinity groups (the friction moments, grouped)

"Spontaneous" means raised in parts 2 to 4, before the screen task. "In screen task" means it appeared only once they were shown or asked to find a fund.

| # | Group | Spontaneous | In screen task only | Raised by (of 6) | Severity per person |
| --- | --- | --- | --- | --- | --- |
| A | **Can't choose between near-identical funds** (mostly S&P 500 trackers) | P2, P4, P6 | P3, P5 | **5** | P2: 2 (never tried an ETF), P3: 2 (would leave and return), P4: **3** (left, didn't buy), P5: 1 (resolves it outside the app), P6: **3** (left, didn't buy) |
| B | **Don't understand what they're buying or the risk** (jargon, stocks vs ETFs, "can I lose it all?") | P1, P3, P4, P6 | P5 | **5** | P1: 2, P3: 2, P4: 2, P5: 1, P6: 2 |
| C | **The decision leaves the app** (go to Google, YouTube, fund documents, then don't come back) | P4, P6 | P3, P5 | **4** | P3: 2, P4: **3**, P5: 1, P6: **3** |
| D | **No concrete goal or amount** ("is €50 even worth it?", "what am I buying it for?") | P3, P4, P6 | | **3** | P3: 2, P4: 2, P6: 2 |
| E | **Purchases come from suggestions, news, friends or gurus**, not a plan | P1, P2, P3 | | **3** | Guardrail, not a stall |
| F | **Onboarding feels heavy** (long documents, registered twice, approval wait, CFD test) | P1, P2, P3 | P5 (minor) | 3 to 4 | 1 each. **Nobody quit** |
| G | **Costs** | none surprised | | 0 | P1, P2, P3 never looked; P4 and P6 never reached a cost screen; P5 checks carefully |
| H | **Free-trade allowance unknown** | | | P3, P4, P6 don't know it; P5 knows there's a limit; P2 knows it | No harm reported |
| I | **Recurring buy feels like losing control of money** | P2 | | 1 | Single case, not used as evidence |
| J | **In-app convenience is a reason to start** (no second app) | P2, P3, P5 | | 3 | Positive. What works |

Scoring rule: severity points added across the people who raised the group. A = 11, B = 9, C = 9, D = 6, F = 4, G and H = 0. This is my judgment of severity from the notes; Muhammad can adjust it.

Quotes that carry the finding:
- P6: "The problem wasn't finding products. It was knowing how to choose between them."
- P4: "I wanted someone to tell me which one I was actually supposed to choose."
- P3: "I didn't want to pick one randomly."
- P5 (on setup): "For me, the platform wasn't the biggest barrier."

## 3. The decision rule, applied (set before the interviews)

Rule: a problem counts only if at least 3 of 6 raise it unprompted, **or** 2 describe it as a reason they stopped or lost money.

| Group | 3 of 6 unprompted? | 2 stopped or lost money? | Passes? |
| --- | --- | --- | --- |
| A Can't choose between similar funds | Yes (3 spontaneous, 5 in total) | Yes (P4, P6 left the app and didn't buy) | **Yes, on both tests** |
| B Don't understand the product or the risk | Yes (4 spontaneous) | No (it delays, rarely the single reason) | Yes, first test only |
| C Decision leaves the app | Yes (2 spontaneous, 4 total) | Yes (P4, P6) | Partly. It is a *symptom* of A and B |
| D No goal or amount | Yes (3) | No | Yes, but it is a root cause outside the app's control |
| E Suggestion-led buying | Yes (3) | No | Guardrail, not a problem to solve |
| F Onboarding | Yes (3) | **No, nobody stopped** | Fails the second test; mild friction only |
| G Costs | No | No | **Fails** |
| H Free-trade allowance | No | No | **Fails** |

## 4. What happened to each hypothesis

| # | Hypothesis | Verdict | Confidence | Why |
| --- | --- | --- | --- | --- |
| H1 | Fees surprise people on small first purchases | **Not supported** | Medium. Only 4 of 6 reached a cost screen | Nobody was surprised. Competitors charge about the same (Secondary: [alternatives comparison](../02-teardown/alternatives-comparison.md)) |
| H2a | The right product is **hard to find** | **Not supported** | Medium | P3 to P6 found S&P 500 funds with the search bar. The "three taps deep" worry (S38) did not show up |
| H2b | **Choosing between** the right products is hard | **Strongly supported** | Medium-high within this sample | Group A, B, C above |
| H3 | Free-trade allowance is confusing | **Weak** | Medium | Many don't know it, but nobody was hurt or confused in a way that mattered |
| H4 | Onboarding effort makes people quit | **Not supported as a cause** | Medium | Friction yes, quitting no. Non-starters (P4, P6) cite no goal, not setup |

Honest note: the strongest candidate going in (H2) survived, but in a different form than we wrote it. The original wording blamed discoverability; the interviews point at choice and understanding.

## 5. The problem (Decision G2 candidate)

**Job statement:** When I'm a student with a small amount of spare money and want to start investing for the long term, I want to tell which of several near-identical funds is the right one, and what risk I'm taking, so I can buy with confidence without spending hours researching somewhere else.

**Evidence in one paragraph (Primary, n = 6):** Five of six students raised difficulty choosing between similar funds or understanding what they were buying. Three raised the fund-choice problem before they were shown anything. Two (P4 and P6, both never invested) opened the app, searched "S&P 500", saw several similar results, could not tell them apart, and left to research elsewhere without buying. Two more (P2, P3) avoided or delayed buying an ETF for the same reason. The app's search and execution worked for all of them; the stall happens between "I know what I want exposure to" and "I'm sure I'm picking the right one."

**What is not the problem:** fees, the free-trade allowance, onboarding length, finding funds.

**Why this one:**
- It passes the decision rule on both tests.
- It maps to a part of the app we have seen (ETF search results, S38).
- It is addressable inside the product (explanation, comparison, clarity on risk) without needing a regulatory change.
- It protects the user: it moves first-timers toward broad funds and away from news-driven single stocks (E), which fits the regulator guardrail.

## 6. Options considered for G2

| Option | Problem | Pros | Cons |
| --- | --- | --- | --- |
| **1 (recommended)** | Student can't tell near-identical funds apart or understand the risk, so they stall or leave | Passes both tests, strongest evidence, product-addressable | Root cause may partly be "no goal" (D); needs a screenshot of what they saw |
| 2 | Students don't understand risk ("can I lose it all?", "can I withdraw?") | Raised by P1, P3, P4 | Thinner; one person was stopped by it. Better treated as part of option 1 |
| 3 | Suggestion-led single-stock buying | Matches a regulator concern | No harm shown in the interviews; it is a guardrail, not a pain |
| 4 | "The product is strong here; the opportunity is narrow" | Honest fallback | Not needed. Option 1 passes the rule |

## 7. Opportunity framing (not solutions yet)

Outcome we care about: *more students who want a long-term fund make a first purchase they feel confident about.*

- Opportunity 1: after searching a broad index (for example S&P 500), the student can see what makes the results different in plain words.
- Opportunity 2: the student can see the risk and how to withdraw before they commit.
- Opportunity 3: the student can pick an amount and a purpose without leaving the app.
- Guardrail: do not push first-timers to trade more, or toward single stocks, and do not tip into personal investment advice (regulated; to verify before the PRD).

Solutions come in the PRD, and only as options tied to these.

## 8. Journey map correction (feeling line)

Updated from the hypothesis in [journey map](../02-teardown/journey-map.md), 1 unsure to 5 confident:

| Phase | Hypothesis (Oct 18) | After interviews | Note |
| --- | --- | --- | --- |
| 1 Arrive and explore | 4 | **4** | In-app convenience is a reason to start (J) |
| 2 Open the account | 2.5 | **3** | Heavy, repeated, but nobody quit |
| 3 Choose what to buy | 2 | **1.5 to 2** | The lowest point. Fund choice stalls and leaves the app |
| 4 Place the first order | 3 | **4** | Those who got there found it simple |
| 5 After the order | not observed | **3** | Only P3 spoke; price swings made them check often |

## 9. How sure are we, and what would change our mind

**Strengths:** all six independently landed on the same S&P 500 stall; two never-invested students stopped there; interviews followed a pre-set rule.

**Weaknesses and biases (state these in the PRD):**
- n = 6, all young students, one university context likely, five on Revolut. Early evidence, not proof.
- P5 and P6 are in a finance society, so they are more informed than a typical student.
- The screen task named a concrete task (a ten-year, €50 fund), and in two cases the near-identical finding showed up only there.
- P4 and P6 only knew "S&P 500" by name. The search term shapes what they saw.
- (Resolved Oct 19.) The S&P 500 search screen is now captured in S40 to S45. It shows three similar funds with no comparison cue, which matches what P2, P4 and P6 described.
- AI-assisted transcripts for P3 to P6.
- "No goal" (D) could be the real cause, with fund choice as the excuse. P6 says they kept saying they'd research first.

**Would change our mind if:**
- Four more students (not in a finance society) find the choice easy.
- The search results turn out to show a clear plain-language differentiator we missed.
- The stall disappears when the student has a stated goal.

## 9b. New evidence from the search screen (Oct 19, S40 to S45)

- The screen the interviewees described exists as they said: three near-identical S&P 500 funds, no comparison cue (S40).
- The data for a comparison already sits on each fund page: size, dividend yield, net expense ratio, risk indicator 5/7, country exposure and a KID link (S44, S45). The gap is the side-by-side view at the point of choice, not missing data.
- The same search mixes in CFD versions of ETFs with near-identical names, and an unrelated stock called "S&P" (S40, S41).
- Effect on the solution: the opportunity is "show what the app already knows, together and in plain words", not "add new data". PRD and PR/FAQ updated.

## 10. To do next

- [x] (M) Screenshot what Revolut shows when you search "S&P 500". Done Oct 19 (S40 to S45). Optional: also screenshot a search for "world" or "global".
- [ ] (M) **Decision G2:** approve option 1 or choose another.
- [ ] (C) Fill the PR/FAQ template once G2 is approved.
- [ ] (C) Verify the "personal advice" regulatory boundary from a public source before the PRD proposes anything that names a fund.
- [ ] (M, optional) Add 1 or 2 non-finance-society students if time allows, to weaken the bias above.
