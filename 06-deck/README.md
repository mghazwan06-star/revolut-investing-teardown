[← PRD](../05-prd/prd.md) · **Step 6 of 7: Deck** · [Prototype test →](../07-prototype-test/README.md) · [Overview](../README.md)

# The case in twelve slides

Read it here, or [download the PDF](revolut-teardown-deck.pdf). Each title is the slide's conclusion, so the titles alone tell the story. Slides 1 to 3 give the answer, the results and the evidence trail; slides 4 to 12 go through the work in order. The plan behind the storyline is in [storyline.md](storyline.md).

### 1. Overview
![Overview. Students stall at choosing a fund, not at fees. A neutral side-by-side view helped them choose. The question: how can Revolut help a first-time student choose with confidence, without giving advice? My answer in three parts: group funds that track the same index; explain each difference and the risk in plain words; never rank. Results from a 30-person test, today versus the new view: chose a fund and could say why 40% to 60%; understood the risk 30% to 60%; read the screen as advice 30% to 10%. Next step: help the 40% still stuck, then a controlled experiment.](slides/slide-01-overview.png)

### 2. Results
![Results. In a 30-person test, the new view lifted confident choices from 40% to 60% and doubled risk understanding. One square per tester, today and new: chose a long-term fund and could explain why 40% to 60%, plus 20 points; saw the risk and could explain it 30% to 60%, twice as many; read the screen as advice 30% to 10%, minus 20 points. Still open: 40% still could not choose and explain; 1 in 10 still read it as advice; everyone saw both versions, so some gain may be practice.](slides/slide-02-results.png)
Details: [prototype test](../07-prototype-test/README.md)

### 3. The evidence
![The evidence. Scope, look, listen, decide, then test: every claim has a number, every number a source. Scope, 18 Oct: 4 hypotheses, 1 decision rule set in advance. Look, 18 to 19 Oct: 45 app screens logged, 3 competitors checked on official pages. Listen, 19 Oct: 6 student interviews, 1 guess of four held up. Decide, 19 Oct: 8 requirements, 6 must-have; 1 metric and 3 guardrails. Test, November 2026: 30 first-time investors, 3 of 3 measures improved. Each number names the file that proves it.](slides/slide-03-evidence.png)

### 4. How I worked
![I tested four guesses with an app walkthrough and six student interviews, using a rule set in advance. Five steps: walk the app, write four guesses, interview six students, apply the rule, write the fix. Two students never invested, two started recently, two invest regularly. Rule: a problem counts only if 3 of 6 raise it unprompted, or 2 say it made them stop.](slides/slide-04-method.png)
Details: [brief](../01-scope/brief.md) · [interview guide](../03-research/interview-guide.md)

### 5. Where confidence drops
![Students lose the most confidence at one step: choosing between near-identical funds. Confidence from 1 to 5 at each step: arrive 4, sign up 3, choose a fund 1.5 to 2, place the order 4, afterwards 3. Both students who had never invested left at the choose-a-fund step.](slides/slide-05-journey.png)
Details: [journey map](../02-teardown/journey-map.md)

### 6. What students said
![Five of six students struggled to pick between similar funds. None were surprised by fees. A grid of six participants against eight friction points. Passed the rule: can't choose between near-identical funds, 5 of 6; didn't understand the product or the risk, 5 of 6. Did not hold up: surprised by fees, 0 of 6; free-trade allowance caused a problem, 0 of 6.](slides/slide-06-interviews.png)
Details: [synthesis](../03-research/synthesis.md)

### 7. The screen where they stalled
![Search S&P 500 and three funds appear, with nothing that says how they differ. Five numbered notes on the screenshot: three funds track one index; the only visible difference is the jargon Dist and Acc; different unit prices read as different value; three words per fund; CFD versions with near-identical names further down.](slides/slide-07-search.png)
Details: [screenshots](../02-teardown/screenshots/)

### 8. My guesses versus the evidence
![Only one of my starting guesses held up, and in a narrower form than I wrote it. Fees surprise people: not supported. Funds are hard to find: not supported. Choosing between funds is hard: supported. Free-trade allowance confuses: weak. Sign-up makes people quit: not supported.](slides/slide-08-guesses.png)

### 9. The proposal
![The fix uses facts the app already has: side by side, in plain words, with no ranking. Four parts: reuse what exists; translate the jargon; inform, never advise; risk in two lines. Path: search, same index what's different, pick a fund, risk summary, order as today.](slides/slide-09-proposal.png)
Details: [PR/FAQ](../04-prfaq/prfaq.md) · [PRD](../05-prd/prd.md)

### 10. The prototype test
![Each part of the fix moved its own measure. Plain-words risk changed most. Goal: a first-time investor with no help picks a fund, can say why and understands the risk, without feeling told what to buy. Bars, today versus new: 40% to 60%, 30% to 60%, 30% to 10%. What changed: same-index grouping and five plain fields (R1, R2) for choice; a plain-words risk summary (R4) for risk; no ranking or badges (R3) for advice. Still open: 4 in 10 still stuck, 1 in 10 still read it as advice.](slides/slide-10-test.png)
Details: [prototype test](../07-prototype-test/README.md) · [requirements](../05-prd/prd.md#7-requirements)

### 11. What comes next
![The prototype passed its first test. The real proof is more first orders without more trading. Primary metric: of students who open a broad index fund, the share who place a first order within 7 days, baseline to be measured. Guardrails that must not rise: trades per month, single-stock or leveraged buys, fee complaints and withdrawals. Steps: prototype test done; fix what blocks the 40% and a compliance review; controlled experiment; go or stop.](slides/slide-11-measure.png)
Details: [PRD metrics](../05-prd/prd.md#5-success-metrics-g3-approved-oct-19) · [assumption map on Miro](https://miro.com/app/board/uXjVEYcX4L0=/?moveToWidget=3458764687766369806)

### 12. What I learned
![My first guess was wrong. Writing the rule down first is what caught it. Four lessons: set the bar before the evidence; finding is not choosing; use what the product already has; test cheaply and report the cost too. Limits: small samples; both versions in one session; I ran and scored the tests; students only and no Revolut data; advice boundary from secondary sources.](slides/slide-12-lessons.png)

---

[← PRD](../05-prd/prd.md) · [Prototype test →](../07-prototype-test/README.md) · [Overview](../README.md)
