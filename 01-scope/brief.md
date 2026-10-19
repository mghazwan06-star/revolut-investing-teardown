# Project brief: Revolut investing, first-purchase teardown

Saved from the project doc created Oct 18, 2026. Scope was confirmed ("locked") by Muhammad on Oct 18.

## Scope

- **User (narrowed Oct 19 by M):** a **student** (about 18 to 25) who is a first-time or early-stage investor, living in the Netherlands or EEA. Original wording: a first-time or early-stage investor in the NL or EEA.
- **Journey:** from opening the Invest tab to the first confirmed purchase.
- **Question:** where do first-timers lose confidence or get surprised?
- **Why this slice:** one journey is deep enough to show real product thinking in five days. A whole-app teardown would stay shallow.
- **Verified in-app on Oct 18:** the account is served by **Revolut Securities Europe UAB** (regulated by the Bank of Lithuania) and is on the **Standard** plan.

## Hypotheses (guesses to test, never conclusions)

| # | Hypothesis | What we would hear if true | Where we test it | What would disprove it |
| --- | --- | --- | --- | --- |
| H1 | Fees surprise people on small first purchases | "I didn't know it would cost that." Fee noticed only at confirmation. | App walkthrough; interview block 4 | Interviewees knew the fee beforehand and were not bothered |
| H2 | Too much choice, or the right product is hard to find, stalls the first purchase | Long searching, defaulting to famous names, never finding index funds, giving up | Walkthrough; interview block 3 and screen task | People choose quickly and can say why |
| H3 | The monthly free-trade allowance by plan is confusing | They cannot say which plan they are on or how many free trades they get | Walkthrough; interview block 4 | Interviewees know their allowance |
| H4 (added later) | Onboarding effort (two questionnaires, passport number, review wait, selfie check) makes people stall or quit | They stopped, delayed or nearly quit during signup | Interview block 2 | Signup felt easy and quick |

Current status of each is in the hypothesis table in the [synthesis](../03-research/synthesis.md).

## Deliverables

- Journey map of the first-purchase flow, corrected with interview evidence
- Three alternatives compared on fees and choice, checked on official pages
- Six student interviews, synthesised against a decision rule set in advance
- One-page PR/FAQ
- PRD: one problem, one primary metric, counter-metrics, non-goals
- Eight-slide deck

## Non-goals (on purpose)

- A teardown of all of Revolut investing or the whole app
- Wireframes beyond 2 to 3 rough sketches
- More than three alternatives in the comparison
- A financial model or invented numbers. Metric targets are proposals with "baseline to be measured".
- Pitching a solution during interviews
- Real names anywhere in the public repo
- Claiming statistical proof from 5 to 6 interviews. It is early evidence and the PRD says so.

## Evidence plan

| Label | What it is | Used for |
| --- | --- | --- |
| Primary | The app walkthrough and the 5 to 6 interviews | The problem chosen and the evidence behind it |
| Secondary (public) | Revolut's own pages and legal documents, annual report, regulator research, third-party reviews | Context, checking what interviewees say, guardrails |

Rules: public sources support or challenge the interviews and never replace them. Every fee or feature is tagged "checked [date], in-app". Everything is paraphrased with the source named. Reviewers and interviewees are never named.


## Interviews (participant numbers only, never names)

| # | Segment | Status |
| --- | --- | --- |
| 1 | Invests regularly | Done Oct 19 (P1, Trading 212 user, regular small monthly buys). |
| 2 | Started recently | Done Oct 19 (P2, Revolut user, student). |
| 3 | Started recently | Done Oct 19 (P3, Revolut user). |
| 4 | Never invested (P4) | Done Oct 19 (P4, Revolut user, never invested). |
| 5 | Invests regularly | Done Oct 19 (P5, Revolut user plus crypto exchange, finance society). |
| 6 | Never invested (P6) | Done Oct 19 (P6, Revolut user, finance society). |

Muhammad sent requests to 8 to 10 people on Oct 18. On Mon Oct 19 he said he has interviewees for all segments (exact count and dates not given to Claude). Pilot not yet done. Update the Status column per interview as they happen.

## Interview method (one statement, used wherever the method is described)

Interviews 1 and 2 were taken as typed notes during the call. Interviews 3 to 6 were voice-recorded with the participant's knowledge and turned into text with an AI tool; Muhammad checked the text. Say this in the PRD and README.

## Decision log

| Gate | When | Decision | Choice |
| --- | --- | --- | --- |
| G1 | Sun Oct 18 | Scope | Locked as written above. **Amended Mon Oct 19 by M: narrowed to students**, because all 6 interviewees are students and a narrower user gives a sharper PRD. |
| G2 | Mon Oct 19 | The one problem the PRD solves | **Option 1**: students who want a long-term fund can't tell near-identical funds apart or understand the risk, so they stall or leave. See [synthesis](../03-research/synthesis.md). |
| G3 | Thu Oct 22 | Primary success metric and non-goals | Open |
