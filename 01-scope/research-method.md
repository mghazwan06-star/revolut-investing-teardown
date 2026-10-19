# Research method: what top product teams do, and how we apply it

Researched Oct 18, 2026. Used to shape the plan, the interview guide, the PRD and the journey map.

## Principles

1. **Start with the customer, not the features.** Amazon teams write a one-page press release and FAQ (PR/FAQ) before they ask for budget, a team or code. The PR/FAQ comes before the PRD and becomes its scope anchor. Gather customer evidence first.
2. **A PRD opens with the problem and the evidence.** It has one primary success metric, counter-metrics (things we do not want to hurt) and explicit non-goals. If QA cannot write a test for a requirement, rewrite it. Beware vanity metrics that only go up, like total signups.
3. **Interviews ask about the past** (the Mom Test): specific past behaviour, not opinions or hypotheticals. Never mention your idea. Patterns usually show up by about the fifth interview. Guides suggest 10 to 15 interviews for real confidence in a problem definition, so 5 to 6 is early evidence and the PRD says so.
4. **Problems are written as jobs to be done:** "When [situation], I want to [motivation], so I can [outcome]."
5. **Journey maps** follow the Nielsen Norman Group format (see [journey map](../02-teardown/journey-map.md)).
6. **For a regulated fintech product, a guardrail matters.** The FCA found engagement features (push notifications, prize draws) can increase trading frequency and risk-taking. Our PRD therefore needs a counter-metric: the fix must not push first-timers to trade more.

## PRD structure to use (see the PRD template)

Problem with evidence; goals; non-goals; one primary metric; secondary and counter-metrics; users and jobs; numbered requirements with acceptance criteria; rollout; risks; open questions. Evidence labelled Primary or Secondary. Targets are proposals with "baseline to be measured" because Muhammad has no access to Revolut data.

## Prioritisation (keep it light)

Rank the candidate problems by how many interviewees raised each and how bad it was, using the decision rule in [interview guide](../03-research/interview-guide.md). A simple impact and effort or RICE sort can be added for the requirements, but do not overbuild: the deadline is five days.

## Industry-standard check of the PR/FAQ and PRD (Oct 19)

Checked against the Amazon "Working Backwards" PR/FAQ format and common big-tech PRD structures (problem first, TL;DR, goals and non-goals, metrics with guardrails, prioritised requirements, alternatives, assumptions, rollout).

- **PR/FAQ, added:** dateline, author quote, customer and internal FAQ split, customer size ("to be measured"), why Revolut should build it, build effort, alternatives considered, riskiest assumption.
- **PR/FAQ, deliberate deviation:** Amazon PR/FAQs often invent customer and leader quotes. This one uses only real interview quotes and the author's own words, because of the "never invent evidence" rule.
- **PRD, added:** document header, TL;DR, why now, user stories, a solution flow diagram (Mermaid, renders on GitHub), P0/P1 priorities, edge cases, alternatives, assumptions, dependencies, change log.
- **PRD, deliberate deviation:** no target numbers or effort estimates, because there is no access to Revolut data or the team. Baselines are "to be measured".

## Sources used

- Amazon "Working Backwards" PR/FAQ guides (several write-ups).
- PRD best-practice guides (problem first, success metrics, non-goals).
- Jobs-to-be-done framework guides.
- The Mom Test interview method summaries.
- Nielsen Norman Group, "Journey Mapping 101".
- FCA research "Gaming trading" and the FCA discussion paper on expanding consumer access to investments.
