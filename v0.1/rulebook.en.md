# ATH Funded Rulebook

## V0.1

> Working draft for product and legal review. This document is not yet a published rule set for purchasable accounts.

## 1. Overview

ATH Funded is a proprietary trading firm that evaluates traders in a simulated environment using live market data. Traders who pass an Evaluation receive a Funded Account, continue trading simulated capital, and become eligible to request real payouts.

The Evaluation fee is a one-time, non-refundable payment for access to the Evaluation. It is not a deposit or trading capital. Each Evaluation fee is paid into the payout pool. ATH Funded cannot withdraw from the pool independently; funds leave only when an eligible payout is executed.

Choose an Evaluation, trade within its risk limits, meet its objectives, and receive a Funded Account. A Funded Account is a simulated trading account that makes its owner eligible to request real payouts based on qualifying performance.

Rulebook V0.1 defines the rules for all ATH Funded Evaluations and Funded Accounts issued under this version.

## 2. Scope and simulated trading

All trading on Evaluation Accounts and Funded Accounts is simulated. No real capital or real liquidity participates in the trades. Market quotes are supplied by a trading provider using live market data.

Available asset classes are:

- Forex;
- cryptocurrencies;
- indices;
- stocks; and
- metals.

The available symbols, trading sessions, contract specifications, execution conditions, leverage for each instrument, commissions, swaps, and other charges are displayed in the trading platform and may depend on the trading provider. Applicable commissions and charges form part of the simulated trading result and affect Balance and Equity. Leverage is offered up to 1:100.

## 3. Eligibility and residence

Participation is available only to natural persons who are at least 18 years old and act on their own behalf. Companies, entrepreneurs acting as organisations, and other legal entities cannot purchase or hold an Evaluation Account or Funded Account under V0.1.

An Evaluation, account, agreement, identity verification, and payout belong to the same individual. Accounts cannot be sold, transferred, shared, or jointly operated.

Before payment, the applicant must:

1. provide their first and last name as shown on their government-issued identity document;
2. select their current country of residence; and
3. actively confirm that the selected country is their current country of residence and that they are not resident in a jurisdiction listed in the published Unsupported Jurisdictions List.

ATH Funded does not provide services where doing so is prohibited by applicable law or sanctions. Formal identity verification is governed by Section 14.

## 4. Definitions

**Evaluation** means the paid process in which a trader is assessed using simulated capital and live market data.

**Evaluation Account** means the simulated trading account issued after successful payment for an Evaluation.

**Funded Account** means a simulated trading account issued after the applicable Evaluation is passed. It does not contain customer deposits or live trading capital. It allows its owner to request real payouts from qualifying simulated performance.

**Starting Balance** means the initial account amount used to calculate objectives and risk limits.

**Balance** means the account result after closed trades, including applicable commissions and charges. It does not include unrealised profit or loss from open positions.

**Equity** means Balance plus the unrealised profit or loss of all open positions, including applicable commissions and charges.

**Profit Target** means the amount of closed profit required to pass an Evaluation phase.

**Daily Reference Equity** means Equity recorded at 00:00 UTC. Before the first 00:00 UTC snapshot of a new Evaluation phase, Starting Balance is used as Daily Reference Equity.

**Qualifying Trading Day** means a UTC calendar day during an Evaluation phase on which at least one of the following thresholds is reached:

- the absolute difference between current Balance and Balance recorded at 00:00 UTC reaches 0.3% of Starting Balance; or
- the absolute difference between current Equity and Daily Reference Equity reaches 0.5% of Starting Balance.

Before the first 00:00 UTC snapshot of a new Evaluation phase, Starting Balance is used as the reference Balance. Both positive and negative differences count. Once either threshold is reached, the date remains qualified even if Balance or Equity later returns toward its reference. A date can count as no more than one Qualifying Trading Day.

**Breached Account** means an Evaluation Account or Funded Account that has violated an applicable risk limit, trading rule, inactivity rule, or prohibited-practice rule. A Breached Account cannot return to an active state.

**News Execution Window** means the period beginning five minutes before and ending five minutes after a published high-impact event for an affected traditional-market instrument.

**Traditional Markets** means all available asset classes other than cryptocurrencies.

## 5. Products and objectives

| Product | Evaluation phases | Phase 1 target | Phase 2 target | Daily limit | Max Drawdown |
|---|---:|---:|---:|---:|---:|
| ATH ONE | 1 | 10% | — | 3% Trailing Daily Loss | 6% static |
| ATH PRO | 2 | 10% | 5% | 5% Max Daily Loss | 10% static |

Available Starting Balances under V0.1 are $5,000, $10,000, $25,000, $50,000, and $100,000.

The daily-limit method and Max Drawdown applicable to the selected Evaluation continue to apply to its Funded Account. A Funded Account has no Profit Target.

## 6. Phase progression

Each new phase begins with the original Starting Balance. Profit and loss from Phase 1 do not carry into Phase 2. Profit and loss from an Evaluation do not carry into the Funded Account.

An Evaluation phase is passed only when:

- all positions are closed;
- Balance has reached the applicable Profit Target; and
- at least five Qualifying Trading Days have been completed in that phase; and
- every applicable rule has been followed.

Each Evaluation phase requires five Qualifying Trading Days. They do not need to be consecutive. Qualifying Trading Days from one phase do not carry into another phase. A Funded Account has no Minimum Trading Days requirement.

There is no maximum time limit for an Evaluation phase or Funded Account. There is no Consistency Rule.

## 7. Risk limits

### 7.1 Max Drawdown

Max Drawdown is static for every ATH Funded product. Its monetary boundary is:

`Starting Balance × (1 − Max Drawdown percentage)`

The boundary does not rise with profits and is not a high-water mark.

### 7.2 Max Daily Loss

Max Daily Loss applies to ATH PRO Evaluation Accounts and their Funded Accounts.

The daily monetary allowance is:

`Starting Balance × Max Daily Loss percentage`

The daily boundary is:

`Equity recorded at 00:00 UTC − daily monetary allowance`

The boundary is fixed at 00:00 UTC and does not move during that trading day. The next 00:00 UTC snapshot replaces it.

### 7.3 Trailing Daily Loss

Trailing Daily Loss applies to ATH ONE Evaluation Accounts and their Funded Accounts.

The daily monetary allowance is:

`Starting Balance × Trailing Daily Loss percentage`

The daily boundary is:

`Equity recorded at 00:00 UTC − daily monetary allowance`

The boundary is fixed at 00:00 UTC and does not move during that trading day. Each new snapshot replaces the previous snapshot. No permanent high-water mark is stored.

### 7.4 Boundary monitoring

Balance and Equity are monitored independently against every applicable boundary. If either Balance or Equity touches an applicable boundary, the account is breached. The amount or duration of the contact and whether the responsible position remains open do not change the result.

## 8. General trading conditions

- A stop-loss is optional except where the trader chooses to use one. There is no mandatory stop-loss rule.
- There is no minimum position-holding time.
- V0.1 imposes no separate maximum risk or position-size percentage per trade. Platform and instrument specifications still apply.
- A period of 30 consecutive days during which there is neither an open position nor an executed trade breaches an Evaluation Account or Funded Account. For a new account, the period begins when the account is issued. It then restarts from the most recent executed trade. Keeping a position open interrupts the inactivity period.

## 9. News, overnight, and weekend trading

| Market and stage | ATH ONE | ATH PRO |
|---|---|---|
| Cryptocurrency — Evaluation | News, overnight, and weekend trading allowed | Allowed |
| Cryptocurrency — Funded Account | Allowed 24/7 | Allowed 24/7 |
| Traditional Markets — Evaluation | News, overnight, and weekend trading allowed | Allowed |
| Traditional Markets — Funded weekday overnight | Allowed | Allowed |
| Traditional Markets — Funded weekend holding | Allowed | Not allowed |
| Traditional Markets — Funded news execution | News Execution Window applies | News Execution Window applies |

### 9.1 News Execution Window

The News Execution Window applies only to ATH ONE and ATH PRO Funded Accounts trading affected Traditional Market instruments.

During the News Execution Window, no order concerning the affected instrument may execute if it opens, closes, increases, or reduces a position, whether fully or partially. This prohibition includes:

- market orders;
- pending orders;
- stop-loss orders;
- take-profit orders;
- partial closes; and
- any other execution that changes exposure.

A position opened before the window may remain open, but no order concerning that position may execute during the window.

The restriction applies only when ATH Funded's published economic calendar identifies the event, its official time, its high-impact classification, and the affected instrument. Scheduled events and affected instruments are determined using the published calendar in effect at the time of the event.

### 9.2 ATH PRO weekend and market-break rule

For a Traditional Market instrument on an ATH PRO Funded Account, all open positions and active pending orders must be closed before:

- the instrument's weekend market close; or
- a scheduled interruption in that instrument's trading session lasting more than two hours.

This restriction does not apply to ATH PRO Evaluation Accounts or to cryptocurrency positions.

## 10. Permitted trading strategies

A trading strategy is permitted unless this Rulebook expressly prohibits it. Permitted strategies include:

- manual and discretionary trading;
- intraday trading;
- swing and position trading;
- ordinary scalping;
- use of lawfully available public analysis and trading signals;
- Expert Advisors, bots, and algorithmic systems;
- grid trading;
- martingale;
- position averaging; and
- stacking multiple positions in the same instrument.

A strategy's short duration, profitability, unusual style, or use of automation does not independently constitute a breach. A permitted strategy becomes prohibited only to the extent that its actual implementation uses a practice prohibited by Section 11.

## 11. Prohibited trading practices

### 11.1 Price, data, and execution exploitation

A trader must not intentionally use or attempt to use:

- erroneous, stale, delayed, frozen, or non-market prices;
- a delay between an external price source and the ATH Funded price feed;
- an order execution that would not reasonably be available under comparable market conditions;
- an error in commissions, swaps, contract size, symbol specifications, order processing, or platform behaviour; or
- any characteristic of the simulated environment to obtain an execution advantage unavailable in the relevant market.

### 11.2 Arbitrage and tick exploitation

The following are prohibited:

- latency arbitrage;
- tick-feed exploitation and abusive tick scalping;
- statistical arbitrage;
- cross-market or cross-instrument arbitrage; and
- any arbitrage or related strategy based on differences in ATH Funded's price feed, order processing, or simulated execution.

Ordinary scalping based on market risk rather than a technical execution advantage remains permitted.

### 11.3 HFT and infrastructure abuse

A trader must not use an automated or manual system that:

- floods the platform with orders, modifications, cancellations, or requests;
- interferes with the platform's normal operation;
- bypasses a published technical limit; or
- derives its material advantage from interaction speed or properties of the simulated infrastructure rather than market risk.

Short holding time or high trading activity alone does not establish HFT or infrastructure abuse.

### 11.4 Hedging and coordinated risk offsetting

Hedging opposite exposure within a single account is prohibited.

A trader must not coordinate opposite positions or offset risk:

- between their own ATH Funded accounts;
- between accounts belonging to different people;
- between an ATH Funded account and an external account; or
- as part of a coordinated group arrangement.

This includes arrangements intended to guarantee that one account passes, concentrate a payout in a selected account, or distribute a single trading risk between accounts.

### 11.5 Copy trading

Copying trades between any accounts is prohibited. This includes:

- copying between the trader's own ATH Funded accounts;
- copying from or to another person's account;
- copying from or to an external trading or prop-firm account; and
- automatically mirroring an external account.

Using the same publicly available analysis, signal, indicator, or lawfully obtained tool does not by itself prove copying. It does not permit automatic mirroring, coordinated execution, or third-party control.

### 11.6 Account operation by third parties

A trader must not:

- give another person access to or control of an account;
- access or trade another person's account;
- use an account-sharing or account-management service;
- buy or provide a service intended to pass an Evaluation; or
- sell, transfer, or jointly operate an account.

The registered individual remains responsible for personally controlling every Evaluation Account and Funded Account issued to them.

### 11.7 Circumvention and manipulation

A trader must not use pending orders, related accounts, multiple identities, third parties, coordinated groups, or any other arrangement to bypass:

- the News Execution Window;
- weekend or market-break restrictions;
- account-allocation limits;
- identity and residence requirements;
- product-specific rules; or
- technical platform limits.

Order spam, platform manipulation, and intentional exploitation of a defect are prohibited.

Terms such as gambling, excessive risk, unusual trading, or a change in style are not independent grounds for breach unless the conduct also violates an objective rule in this Rulebook.

## 12. Account limits and lifecycle

The combined Starting Balance of all active Evaluation Accounts held by one person cannot exceed $200,000.

One person may hold no more than one active Funded Account at a time. Evaluation Accounts may remain active while that person has an active Funded Account.

If another Evaluation is passed while a Funded Account is active, activation of the new Funded Account is deferred until the existing Funded Account is no longer active. A payout does not close a Funded Account.

Merging accounts is not permitted. Scaling and account-size increases are not offered under V0.1.

The public lifecycle is:

- `Evaluation Account → Funded Account → Breached Account`; or
- `Evaluation Account → Breached Account`.

There is no reverse transition from a Breached Account. A person whose account is breached may purchase a new Evaluation if they continue to satisfy the eligibility and jurisdiction requirements.

## 13. Payouts

### 13.1 Eligibility

A payout can be requested only from a Funded Account and only when:

- there is no other payout request being processed;
- the selected payout interval has elapsed;
- the identity-verification requirements have been satisfied; and
- Balance is at least 1% above Starting Balance:

`Balance ≥ Starting Balance × 1.01`

Unrealised profit in Equity does not create payout eligibility.

### 13.2 Profit Split and request intervals

The trader selects one of the following combinations when purchasing the Evaluation:

| Profit Split | Request interval |
|---:|---:|
| 80% | Every 7 days |
| 90% | Every 14 days |
| 100% | Every 30 days |

The selected combination is fixed for that account and cannot be changed. A different combination may be selected when purchasing a new Evaluation.

The first interval begins when the account becomes a Funded Account. Each later interval begins when the previous payout request is accepted for processing, regardless of when the payout is received. Submitting a request that is not accepted for processing, fails validation, or is rejected before acceptance does not begin a new interval.

### 13.3 Amounts and processing

Partial and repeated payouts are permitted. There is no payout cap under V0.1.

The trader specifies a gross payout amount. That gross amount is deducted from Balance, and the amount payable to the trader is calculated using the selected Profit Split.

Only one payout request may be processed at a time. Payouts are processed within 24 hours. ATH Funded pays the network fee for executing the payout.

A partial or full payout does not close the Funded Account. The trader may continue trading and may submit later requests when all requirements are met again.

## 14. Identity verification

Identity verification is required before the first payout and may be completed earlier. Verification may be performed by an external identity-verification provider.

ATH Funded may require a repeated identity check. A payout subject to a repeated check is paused until the check is completed; assigning the check does not by itself cancel the request.

The consequences of failed verification, false information, fraudulent documents, or residence in an unsupported jurisdiction are governed by the Terms of Service and applicable law.

## 15. Breach consequences

An Evaluation Account or Funded Account becomes a Breached Account if:

- Balance or Equity touches an applicable risk boundary;
- the inactivity rule is violated;
- a product-specific news, weekend, or market-break rule is violated; or
- a prohibited trading practice is used.

A Breached Account is closed and is not restored. The trader may purchase a new Evaluation if otherwise eligible.

## 16. Rule versions

The Profit Targets, drawdown rules, and selected Profit Split and request interval applicable to a purchased account cannot be changed for that account.

The Unsupported Jurisdictions List may be updated to comply with applicable law, sanctions, and provider requirements. The list of prohibited conduct that exploits simulated trading may also be expanded.

Readable versions and revision history are intended to be published through public GitHub releases. A cryptographic fingerprint of the published document set is intended to be recorded on a blockchain, and each purchase is intended to be linked to the applicable fingerprint. The final publication, effective-date, notice, and version-application procedure remains subject to legal review before accounts are offered for purchase.
