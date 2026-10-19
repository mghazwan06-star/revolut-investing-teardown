[← Brief](brief.md) · **Step 1 of 6: Scope** · Next: [Teardown log →](../02-teardown/teardown-log.md)

# Research method

How product teams at top tech companies run discovery, and how I applied each practice here.

## Principles I followed

| Practice | What it means | How I applied it |
| --- | --- | --- |
| **Working backwards** (Amazon PR/FAQ) | Write the press release and FAQ before any requirements, so the customer problem anchors the scope | The [PR/FAQ](../04-prfaq/prfaq.md) was written and agreed before the [PRD](../05-prd/prd.md) |
| **Problem first, then evidence** | A PRD opens with the problem and its evidence, then one primary metric, guardrails and explicit non-goals | [PRD sections 1 to 5](../05-prd/prd.md) |
| **The Mom Test** | Ask about specific past behaviour, not opinions or hypotheticals; never pitch the idea | The [interview guide](../03-research/interview-guide.md) asks "walk me through the last time", and screens come last |
| **Jobs to be done** | Write the problem as "When ___, I want to ___, so I can ___" | The job statement in the [synthesis](../03-research/synthesis.md#5-the-problem-decision-g2) |
| **Journey mapping** (Nielsen Norman Group) | Actor, scenario, phases, actions, feelings and opportunities on one map | The [journey map](../02-teardown/journey-map.md) |
| **Pre-registered decision rule** | Decide before the research what evidence would count | A problem counts only if 3 of 6 raise it unprompted, or 2 say it made them stop |
| **Opportunity solution tree** (Teresa Torres) | Link the outcome to customer needs, solution ideas and the tests behind them | [Miro frame 4](https://miro.com/app/board/uXjVEYcX4L0=/?moveToWidget=3458764687766336443) |
| **Assumption mapping** | Rank assumptions by importance and evidence; test the risky ones first | [Miro frame 5](https://miro.com/app/board/uXjVEYcX4L0=/?moveToWidget=3458764687766369806) |
| **Guardrail metrics** | A metric that must not get worse while the main metric improves | In a regulated investing product, the fix must not push first-timers to trade more (FCA research, UK context) |

## Sample size

Patterns usually appear by about the fifth interview; guides suggest 10 to 15 for real confidence in a problem definition. Six interviews are therefore early evidence, and every document says so.

## How the PR/FAQ and PRD follow industry practice

- **PR/FAQ:** headline, dateline, problem, solution, a real customer quote, how to start, customer FAQ and internal FAQ (customer size, why build it, effort, alternatives, riskiest assumption, stop criteria).
- **PRD:** header, TL;DR, problem and evidence, why now, users and stories, goals and non-goals, metrics with guardrails, solution flow, P0/P1 requirements with acceptance criteria, edge cases, alternatives, assumptions, rollout, risks, open questions, change log.
- **Deliberate deviations:** Amazon PR/FAQs often use invented customer and leader quotes; mine uses only real interview quotes and my own words. The PRD gives no target numbers or effort estimates, because I have no access to Revolut data or its team; baselines are "to be measured".

## Sources for the method

Amazon "Working Backwards" PR/FAQ write-ups; PRD best-practice guides; jobs-to-be-done guides; *The Mom Test*; Nielsen Norman Group, "Journey Mapping 101"; Teresa Torres on opportunity solution trees and interview snapshots; FCA research "Gaming trading". Dated links in [sources.md](../sources.md).

---

[← Brief](brief.md) · Next: [Teardown log →](../02-teardown/teardown-log.md)
