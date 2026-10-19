# Alternatives comparison (secondary sources)

Built Sun Oct 18, 2026 from public pages. **Every figure comes from search results, mostly third-party reviews, and must be checked on each provider's own fee page before the PRD cites it.** Sources disagree on dates and details, which is itself a finding: nobody can quote these fees the same way twice. Only three alternatives are in scope (Trade Republic, DEGIRO, bunq).

| Dimension | Revolut (seen in-app) | Trade Republic | DEGIRO | bunq |
| --- | --- | --- | --- | --- |
| Cost of one small manual buy | First trade free each month on Standard (banner S26); fee after that not seen in-app. Exchange fee €0.09 on a $10 buy (S34). | Flat €1 per order regardless of size, per several reviews | Core Selection ETFs: €1 handling fee. Other ETFs: extra commission plus the €1. Sources differ on details. | Reviews call trading fees high; the US stock fee is described as not publicly disclosed |
| Long-term path for a beginner | Robo-Advisor (0.75 percent a year, from €10), Recurring buy, and a "No commission ETPs" list | Savings plans with €0 execution fee, from €1, per reviews | Core Selection list of several hundred ETFs | A curated stock list at launch in 2024; one review says its robo-style investing needs a paid plan |
| Starting amount | €1, €10 or €100 depending on the screen | From €1 | No minimum deposit | Fractional stocks from €10 at launch |
| Account costs | None seen | No custody or inactivity fee, per reviews | Small yearly connectivity fee per exchange, per reviews | None for investing accounts, per one review |
| Currency | Dollars asked for first on US stocks | Euro account | Mixed, with a conversion fee | Not verified |

## Details and caveats by provider

- **Trade Republic:** reviews state a flat €1 per manual stock or ETF order and €0 execution on savings plans (recurring investments) from €1; no custody, inactivity, deposit or withdrawal fees; euro-denominated account; thousands of ETFs available for savings plans per a third-party review. Sources: quantroutine.com/brokers/trade-republic-fees-explained/, us.fitgap.com/products/trade-republic, freenance.io review, curvo.eu (Dutch). One Dutch review mentions changes since July 2026 (two execution modes, "Directe prijs", and Trade Republic acting as its own market maker). Not verified on the official site.
- **DEGIRO:** curated "Core Selection" ETF list. Older reviews describe "one free trade per fund per month" and a €1 handling fee; a 2026 review says the structure changed in October 2025 (Core Selection routed through Tradegate, €1 per trade, no commission, with a possible lock-in on transfers). Non-core ETFs cost extra commission plus €1; Euronext Amsterdam ETFs reported at €3 per trade. Connectivity fee about €2.50 per exchange per year. Sources: curvo.eu/article/degiro-costs-etf, quantroutine.com/?p=1218, jeangalea.com, investingintheweb.com. Not verified on the official site.
- **bunq:** sources conflict on whether they describe bunq's Stocks product (launched Sept 2024 in beta in NL and France with a curated list, fractional shares from €10 and no commission for the first three months) or its robo-style investing (one review: requires a paid plan at €4.99 a month). BrokerChooser rates bunq's trading fees as high and not for beginners and says the US stock fee is not publicly disclosed. **Treat as unverified.**

## What this tells us

- **Revolut is not the outlier on fees.** Trade Republic and DEGIRO also charge about €1 on a small manual order, so a €10 purchase costs roughly 10 percent at all three. Revolut's free first trade each month is arguably better. This weakens H1 further.
- **Two competitors give long-term investors a named, cheap front door.** Trade Republic's savings plans and DEGIRO's Core Selection are described in public reviews as the products beginners are pointed to. Revolut has equivalents (Recurring buy, the No commission ETPs list, the Robo-Advisor), but in the walkthrough they sat deeper than single stocks and top movers. That supports H2 as a hypothesis, not a conclusion.
- **What we cannot know from text:** where these products sit in each app and how many taps it takes. Ask interviewees who use Trade Republic or DEGIRO to show how they first found their index fund.

## Official-source check (Mon Oct 19, 2026) — Secondary, official pages

These figures replace the review-based figures above where they differ. Tagged "checked Oct 19, 2026". Trade Republic and bunq were read through search summaries of the official support and help pages, not the full price list, so re-open the linked pages once before quoting them in the PRD.

- **DEGIRO (NL, official fee page, dated 01.10.2025 on the page):** ETF Kernselectie (Core Selection) is €0 commission plus €1 handling. Other ETFs ("ETF Wereldwijd") are €2 commission plus €1 handling. Connectivity fee is 0.25% of portfolio value, capped at €2.50 per exchange per year, and **Euronext Amsterdam and Brussels are free**. This corrects the review claims of "€3 on Euronext Amsterdam" and "about €2.50 per exchange" for a Dutch investor. Source: degiro.nl/tarieven.
- **Trade Republic (official support pages, NL/DE/other EEA):** no order commission. There is an "external settlement cost" of €1 per transaction, including fractional trades. Savings plans have no execution fee on purchases; the €1 applies only when selling. So "flat €1 per order" is roughly right for a one-off buy, but it is a pass-through cost, not a commission. Sources: support.traderepublic.com (articles 784, 778, 1420).
- **bunq (official help pages):** Stocks fee is **0.99% per trade** (buy and sell) after a 3-month promotion with no fees on up to €100,000 of orders; 0.79% on Pro and 0.49% on Elite. ETF TER is not charged by bunq. This **contradicts** the earlier "fee not publicly disclosed" note. On a €10 buy, 0.99% is about €0.10, far below the €1 at Trade Republic and DEGIRO. Sources: help.bunq.com (how-are-trading-fees-calculated, stocks-faq).

### What changes for the teardown

- **H1 weakens further.** On a small first purchase bunq is cheaper than a €1 flat fee, but its fee grows with size; Revolut's free first monthly trade is still competitive. Cost is not where Revolut loses.
- **The "€10 costs roughly 10 percent at all three" line is wrong for bunq** and should not be repeated.
- Still unverified: Revolut's fee for the second trade in a month (in-app only), and bunq's Core plan discount.

## To do

- [x] Verify competitor figures on official pages (done Oct 19; see above).
- [ ] Re-open the Trade Republic and bunq pages directly and copy exact wording before the PRD cites them.
- [ ] Check bunq's Core plan discount and the Dutch Trade Republic price page (the /pricing URL returned 404).
