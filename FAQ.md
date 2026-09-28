# Bungee Funded Perps — FAQ

### Links to add

Placeholders left in the text, to swap for real URLs:

- In-app chat, Discord and the support email, in "How do I contact support?"

---

## 1. Getting Started

_New to Bungee Funded Perps? Start here._

### What is Bungee Funded Perps?

Bungee Funded Perps is Bungee's prop trading program for perpetual futures, covering crypto, stocks, indices and commodities. You pay a one-time fee for an evaluation, then trade it in the Bungee terminal. Pass the evaluation without breaking the risk limits and you move to a funded account, where you keep **80%** of the profits you make.

There's no time limit, no minimum number of trading days and no consistency rule.

### What is prop trading?

In proprietary ("prop") trading, you trade a firm's capital instead of your own and keep a share of the profits. Modern prop firms run it as a two-stage programme: you pay a fee to take an **evaluation** that tests whether you can hit a profit target while staying inside set risk limits, and if you pass you get a **funded account** and a cut of what you make on it. The firm carries the downside; your loss is capped at the fee you paid.

Crypto-native prop firms run the same model on perpetual futures, with no brokerage account to open. Bungee Funded Perps is Bungee's version of it, built into the Bungee terminal, and its markets cover crypto alongside stocks, indices and commodities.

One thing to be clear about: in this model you're being evaluated on the trading decisions you make, not investing your own money in the market.

### How do I get started?

1. **Choose an evaluation:** sign in with Google or your wallet, pick a track (Classic, Pro or Turbo) and an account size, and pay in USDC on Base.
2. **Pass the evaluation:** hit the profit target without reaching the daily loss limit or maximum drawdown.
3. **Verify your identity:** complete KYC after you pass, before your first funded payout.
4. **Trade your funded account.**
5. **Get paid:** request payouts in USDC. You keep 80% of your profits.

### What is an evaluation?

An evaluation is the test you buy to prove you can trade to our risk limits. You pick a track (Classic, Pro or Turbo) and an account size, then trade that account in the Bungee terminal.

To pass, you hit the profit target without reaching the daily loss limit or the maximum drawdown. There's no time limit, no minimum number of trading days and no consistency rule, so you can take as long as you need. Break a limit and the evaluation ends in a hard breach; to try again, you buy a new one.

### What is a funded account?

A funded account is what you trade after you pass an evaluation. It opens at the same account size as the evaluation you passed, and you keep **80%** of the profits you make on it, paid out in USDC. You'll need to complete KYC before your first payout.

Funded accounts run on the same risk limits as evaluations: the same daily loss limit, the same maximum drawdown and the same prohibited practices. Breaching them closes the account. There's no profit target on a funded account, so you can keep trading it for as long as you stay inside the limits.

### Can I lose more than my evaluation fee?

No. The evaluation fee is the only money you put in. You don't deposit trading capital, you're not trading your own funds, and you can't end up owing Bungee anything if an account loses money.

If you breach an account's risk limits, the account closes. That's the extent of it: your downside is the fee you already paid.

### Can anyone be funded?

Almost anyone can. You need to be of legal age in the country you live in, and you can't be in a country we're unable to serve or on a sanctions list. Bungee Funded Perps isn't available everywhere, and the current restrictions are set out in our Terms.

You don't need trading qualifications, a brokerage account or your own capital. You do need to pass KYC and compliance checks before your first funded payout.

### Is this a live trading account?

Evaluation and funded trading both use **simulated accounts**. You're not placing orders on an exchange yourself, and you never deposit trading capital.

Behind the scenes, Bungee may simulate your trades internally, hedge some or all of the exposure, net exposure across accounts, or execute externally, at its discretion. Either way, you don't own or control Bungee's capital or any hedge positions, and your results are set by Bungee's account ledger and the program rules.

---

## 2. Evaluation

_Buying an evaluation, the three tracks, and what happens when you pass._

### What evaluations can I buy?

One-step evaluations in three tracks: **Classic**, **Pro** and **Turbo**. Each track comes in a range of account sizes, and each has its own profit target, daily loss limit and maximum drawdown.

Current account sizes, prices and rules are on the [evaluation page](https://app.bungee.exchange/funded-perps#pricing), which is always the source of truth.

### What's the difference between Classic, Pro and Turbo?

Each track sets a different balance between how much profit you need to make and how much room you have to lose. The exact profit target, daily loss limit and maximum drawdown for each track are shown on the [evaluation page](https://app.bungee.exchange/funded-perps#pricing) before you buy, and in your dashboard once you're trading.

### Does unrealized profit count toward the profit target?

No. Only **realized** profit counts, so a trade has to be closed before it moves you toward the target. Unrealized profit on an open position still counts toward your daily loss and drawdown, but it won't pass you.

### Can I request a payout during an evaluation?

No. Profit made during an evaluation isn't withdrawable; it's there to show you can hit the target. Payouts start once you're on a funded account.

### What happens after I pass?

You're promoted automatically. Once your realized profit reaches the target and you're flat, with no open positions and no pending orders, your evaluation closes and a funded account of the same size opens for you.

The funded account starts fresh: positions, profit and orders from the evaluation don't carry over. After completing KYC, you can start requesting payouts on the profits you make there.

Your evaluation fee isn't returned to you with your payouts.

---

## 3. Trading Rules

_Loss limits, drawdown, and what counts as a breach._

The answers below cover the rules most traders ask about. For the full set, including how breaches are handled and what counts as prohibited trading, read the [Bungee Funded Perps rulebook](https://github.com/SocketDotTech/rulebook/blob/main/RULEBOOK.md).

### What are the main rules?

- Don't reach your track's **daily loss limit.**
- Don't reach your track's **maximum drawdown.**
- Don't use **prohibited trading practices.**
- Follow the rulebook and the Bungee Funded Perps Terms.

Reaching a daily loss or maximum drawdown limit is a **hard breach.** Prohibited trading may lead to payout denial and further enforcement, including an account breach.

### What's the difference between balance and equity?

**Balance** is the settled cash in your account: your starting balance plus the profit and loss of trades you've closed. It only moves when a position closes.

**Equity** is your balance plus the profit or loss of any position still open, minus fees and funding charged so far. It moves with the market, tick by tick.

Both your daily loss limit and your maximum drawdown are measured on **equity**, not balance. A position that's deep in the red counts against your limits while it's still open, so you can breach an account without closing a single trade.

### What is the daily loss limit, and how is it calculated?

The daily loss limit caps how much you can lose in a single day. If you reach it, the account is breached. It resets each day, so a bad day ends at the reset rather than following you through the evaluation. Your track sets the percentage, and your dashboard shows how much room you have left today.

Daily loss is measured on **account equity**, so it can include:

- realized P&L
- unrealized P&L from open positions
- trading fees
- funding charges
- other account charges

A losing open position counts toward your daily loss even before you close it.

The day runs on UTC: your limit resets at **00:00 UTC**, and that's when your starting equity for the new day is set. Your dashboard shows the percentage for your track and how much room you have left.

### What is the maximum drawdown, and how is it calculated?

The maximum drawdown caps how much you can lose in total over the life of the account, rather than in a single day. If you reach it, the account is breached.

It's **static**: measured from your account's starting balance, and it doesn't trail upward as you make profits. So if you're in profit, your gains sit on top of that fixed floor and your total room to lose grows. Like the daily limit, it's based on equity, so fees, funding and unrealized P&L all count toward it.

After each approved funded payout, the account resets to its original balance and default risk limits. Unpaid eligible profits stay separately claimable and don't increase your trading equity or drawdown allowance.

### What happens if I breach a rule?

- Your open positions may be force-closed.
- The account may be permanently disabled.
- To keep trading, you buy a new evaluation.

There's no automatic forgiveness, reset, grace period or soft breach. The dashboard may warn you as you approach a limit, but warnings don't change the limits.

### What if I breach while my account is in profit?

The breach still stands. Limits are measured on equity in the moment, so a sharp move against an open position can take you past your daily loss limit or maximum drawdown even if you were up beforehand, or are up again shortly after. There's no look-back and no netting against earlier profit.

That's also why unrealized profit doesn't pass an evaluation: profit counts when you close the trade, while risk counts continuously. Full details of how breaches are handled are in the [Bungee Funded Perps rulebook](https://github.com/SocketDotTech/rulebook/blob/main/RULEBOOK.md).

### Is there a leverage or position-size limit?

Yes, and there are two of them.

**Leverage is fixed.** Every market trades at a fixed leverage set by Bungee, and you can't choose your own. The fixed value isn't the same on every market, and Bungee may change a market's leverage going forward based on liquidity, volatility and risk. Changes apply to new orders; positions you already have open keep the leverage they were opened with.

**Each market has a maximum position size.** More liquid markets may allow larger positions than thin or volatile ones, and Bungee may reduce a market's limit, make it reduce-only or disable it when conditions require.

Your dashboard shows the current leverage and maximum position size for every market.

### How many positions can I have open at once?

You can hold positions in several markets at the same time. Each market holds one position in one direction, so you can't stack two separate BTC trades or be long and short the same market at once.

What limits you in practice is size rather than count: every market has its own maximum position size, and your account's risk limits apply across everything you have open.

### Is there a minimum holding time?

No. There's no fixed minimum holding period, and profit isn't automatically removed just because a trade closes quickly. A single short-duration trade doesn't, by itself, establish scalping or HFT.

Bot activity, HFT and scalping are still prohibited. Holding trades longer doesn't exempt a prohibited pattern from review.

### What counts as scalping or high-frequency trading (HFT)?

**Scalping** means repeated or systematic rapid entries and exits intended to capture small price moves, spreads or short-lived execution advantages. It applies whether you trade manually or through automation.

**HFT** means systematic high-speed order submission, modification, cancellation or execution, including bursts designed to exploit latency, stale prices or differences in execution speed.

Bungee monitors order and execution logs, trading frequency, order-to-trade and cancellation ratios, holding times, repeated sizes and timing, evidence of automation, and how much activity or profit comes from these patterns. Related accounts may be reviewed together.

Payouts may be held during an investigation. If prohibited bot activity, HFT or scalping is confirmed, **the applicable payout request is denied.** Bungee may also restrict trading, suspend or breach an account, or take other action under the rulebook.

### Do I have to use a stop-loss?

No. A stop-loss isn't required, and you won't be breached for trading without one. How you manage risk is up to you.

That said, both limits are measured on equity, which means an open position moving against you counts toward your daily loss and drawdown before you close it. A position left unattended can breach the account on its own, so a stop-loss is a practical way to keep that from happening.

You can attach a **stop-loss and a take-profit** to any position in the terminal. They resize with the position, so if you close part of it the remaining protection adjusts to what's left. Once one triggers it can't be cancelled or edited.

---

## 4. Trading Restrictions

_What you can and can’t do while trading._

### Which trading practices are prohibited?

- **Bot activity, HFT and scalping:** automated trading decisions or order activity, systematic high-speed orders, or repeated rapid entries and exits to capture small price moves or execution advantages.
- **Copy trading and coordinated trading:** automatically mirroring another trader's account, controlling several accounts centrally, synchronising trades to get around risk limits, or using services built to game prop-firm evaluations.
- **Cross-account hedging:** e.g. long BTC in one account and short in another, using correlated assets to create offsetting exposure, or coordinating opposite positions with another trader.
- **Technical exploits:**
  - latency or stale-price exploitation
  - exploiting feed errors or platform bugs
  - manipulating Bungee's execution or risk systems
  - strategies that depend on flaws in the simulated market
- **Market abuse:** front-running on non-public information, trading on material non-public information, or splitting exposure across identities or accounts to get around limits.
- **Account sharing:** sharing logins, transferring or selling an account, letting someone else trade it, trading on another person's behalf, or using multiple identities.

Bungee looks at the overall economic substance and pattern of trading, not just individual trades. It may also investigate behaviour that looks designed to exploit the program even if it isn't specifically listed.

The full list, and how breaches are handled, is in the [Bungee Funded Perps rulebook](https://github.com/SocketDotTech/rulebook/blob/main/RULEBOOK.md).

### Can I use trading bots or an API?

No. Using software, scripts, automated trading systems or APIs to make trading decisions or automatically submit, modify or cancel orders is prohibited on evaluation and funded accounts. Ordinary stop-loss and take-profit orders you configure aren't, by themselves, bot activity.

Bungee monitors automation and coordinated activity. Confirmed prohibited bot activity leads to denial of the applicable payout request and may lead to further enforcement under the rulebook.

### Can I follow trade ideas from others?

Yes. You can learn from public commentary, follow public trade ideas, use public research, and act on what you find independently. Automatically mirroring another trader or running coordinated accounts isn't allowed without Bungee's approval.

### Can I hedge?

No, in either case:

**Across accounts**, hedging is prohibited: holding long BTC in one Bungee account and short BTC in another, using correlated markets to create offsetting exposure, or coordinating opposite positions with another trader.

**Within one account**, positions are one-way. Each market holds a single position in a single direction, so you can't be long and short the same market at the same time. Trading in the opposite direction reduces or closes the position you already have.

### Can I trade during news events?

Yes. There are no news-trading restrictions: you can hold positions through high-impact releases and open or close trades around them.

### Can I hold positions overnight or over the weekend?

Yes. There's no requirement to close positions at the end of the day or before the weekend, and crypto perpetual markets trade 24/7.

Two things to keep in mind while a position stays open: funding is charged every hour, and unrealized losses count toward your daily loss limit and drawdown around the clock, including while you're away from the screen.

---

## 5. Funded Account & Payouts

_How and when you get paid._

### Can I withdraw the profits I make?

Yes. Profit you realize on a funded account is yours to withdraw, minus Bungee's share of the split. There's no target to hit first: once you have realized profit, you can request your first payout.

Only **realized** profit counts. Profit sitting in an open position isn't withdrawable until you close the trade. Payouts remain subject to eligibility and trading-rule reviews.

Each funded account is capped at **$20,000 gross in any rolling 24-hour period**, before the profit split. Additional payouts are allowed while allowance remains, and unpaid eligible profit stays claimable for a later request.

### What's the profit split?

You keep **80%** of the profits you make on your funded account; Bungee keeps 20%.

### Are the rules the same on a funded account?

Yes. A funded account has the same daily loss limit, the same maximum drawdown and the same prohibited practices as the evaluation you passed. The limits are measured the same way, on account equity, so open positions, fees and funding all count. Breaching a limit closes the funded account.

### Is there a profit target on a funded account?

No. The profit target only applies to the evaluation. Once you're funded there's no target to hit and no time limit; you keep trading inside the risk limits and request payouts when you have withdrawable profit.

### How and when can I request a payout?

Whenever you have realized profit on a funded account. There's no fixed payout cycle and no minimum number of trading days to wait through.

The **24-hour cooldown** applies to each processed payout amount. You can request additional payouts while sufficient allowance remains under the account's $20,000 gross cap. Each amount stops counting toward the cap 24 hours after it is processed and the account is reset. The limit applies to each funded account separately.

Only one request can be pending at a time. Pending, rejected or cancelled requests don't consume allowance or start a cooldown. If a processed payout is reversed, its gross amount no longer counts toward the cap.

To be eligible, you need to:

- be on an eligible funded account
- have realized, withdrawable profit
- complete KYC and compliance checks
- have no unresolved hard breach
- have no unresolved abuse or risk investigation
- have no confirmed prohibited bot activity, HFT or scalping for the payout period
- have completed any applicable cooldown, with sufficient allowance for the requested gross amount
- meet any operational requirements shown in your dashboard

### How much can I take out at once?

Up to **$20,000 gross per request per 24 hours**, whatever your account size or track, provided enough allowance remains. Total gross payouts from each account can't exceed $20,000 in any rolling 24-hour period, even across multiple requests. The cap applies before the profit split, so a full $20,000 request pays you $16,000 at 80%.

If you withdraw the full $20,000 at once, you wait 24 hours before another payout. If you split it across payouts, allowance becomes available as each amount passes its 24-hour mark. Profit above the cap isn't lost: it stays claimable for later payouts, subject to eligibility.

### What's the minimum payout?

**$50** after the profit split.

### How long does a payout take?

Bungee aims to process valid payout requests within **1 business day.** That's a target, not a guarantee. It can take longer if:

- KYC is incomplete
- a compliance or risk review is needed
- the payout involves unusual or thin-market profits
- there's a technical or operational issue

### What happens to my account after a payout?

After every approved payout, including your first, your funded account **resets** to its default state. It goes back to its original starting balance, with the default daily loss limit and maximum drawdown for its size and track. The account stays funded: you don't need a new evaluation.

Any eligible profit you didn't withdraw isn't lost. It's recorded separately and stays claimable in later payouts, subject to the same cap, split, cooldown and eligibility rules. While it's held there, it doesn't count toward your trading balance, your equity or your risk limits, so it doesn't give you extra room to lose.

For example, a $10,000 Classic account grows to a realized $35,000, which includes $25,000 of eligible profit. You request the maximum $20,000 payout and receive $16,000 at the 80% split. The remaining $5,000 of profit stays claimable, and the account resets to a $10,000 balance with its drawdown floor back at $9,400, giving you $600 of room. You can request the remaining $5,000 once the 24-hour cooldown has passed.

A pending, rejected, cancelled or reversed payout doesn't trigger a reset, and a reset doesn't clear an unresolved breach or investigation.

### Can a payout be reviewed or denied?

Yes. Bungee may manually review payouts and trading, especially when profits come from:

- thin or illiquid markets
- unusually large positions
- sudden liquidity events
- potentially manipulated markets
- suspicious or coordinated trading
- bot activity, HFT or scalping

Payouts may be held during an investigation. Confirmed prohibited bot activity, HFT or scalping means the applicable payout request is denied. Other ineligible payouts may also be denied, and payouts credited in error may be reversed.

### Do I have to pay tax on my payouts?

You're responsible for meeting any tax obligations that apply to you in your own jurisdiction. Bungee doesn't provide tax advice.

---

## 6. Trading Terminal & Markets

_Markets, leverage, fees, funding and how orders fill._

### What can I trade?

Perpetual futures on an approved list of markets, spanning crypto, stocks, indices and commodities. Every market is reviewed and enabled by Bungee before it can be traded, and we add more over time as they pass that review.

All markets are **isolated-margin** perpetuals: margin is assigned to each position on its own and isn't shared with your other positions. Cross margin isn't supported. Account-level limits still apply across everything you have open, so P&L, fees and funding from every position count toward your daily loss and drawdown.

The current list is on the [assets page](https://app.bungee.exchange/funded-perps/assets), and your dashboard always shows what's tradable on your account right now.

### Why can't I trade every market on Hyperliquid?

Every market has to be explicitly approved and enabled by Bungee first. We look at liquidity, order-book depth, volatility, manipulation risk, venue constraints, and whether the exposure can be hedged or executed. A market being listed on a venue doesn't make it tradable here. We'll add more markets as they pass review.

### How does leverage work?

Leverage is fixed for each market and set by Bungee, so you can't pick your own. Whatever a market's fixed leverage is, every trade on that market uses it. The value isn't the same on every market, and Bungee may change it going forward based on liquidity, volatility and risk. Your dashboard shows the current leverage for each market.

### What are the trading fees?

**1.5 bps (0.015%)** of executed notional, for both maker and taker orders. You pay it when you open a position and again when you close it.

Example: opening and closing a $10,000 position costs about **$3.00** in total.

Fees count toward your equity, daily loss, drawdown and payouts.

### Is there funding?

Yes. Funding is charged **every hour** on the notional of your open positions. The rate is dynamic: it moves with market conditions, and the dashboard shows the charges applied to your account.

Two things to know about how it works here:

- **The minimum rate is 0%**, so some hours cost you nothing.
- **Funding is never paid to you.** The rate can't go negative and won't create a credit, which is different from a live exchange where funding flips between longs and shorts.

Funding counts toward your P&L, daily loss, drawdown and payout eligibility.

### Will my order fill at the price I see?

Not always, and that's deliberate. Your orders fill against the **real order book**, at the prices and depth actually available in the market, so execution behaves the way it would with real money on the line:

- **Spread and slippage apply.** A large order works through the book and fills at several price levels, not one quoted price.
- **Partial fills happen.** If a crossing order runs out of available depth, you keep what filled and the rest is cancelled. A limit order keeps its unfilled remainder open at your price.
- **Fees and funding are charged** on what actually fills.
- **Orders can be rejected or resized** if they exceed available liquidity, a market's position limit, your account's risk limits or venue constraints.

What isn't taken from the market is other traders' order flow: **each account gets its own copy of the book's depth**, so your fills never compete with another Bungee trader's, and nobody can eat the liquidity you were aiming at.

You can also edit the price of a resting limit order. A stop-loss or take-profit that has already triggered can't be edited or cancelled.

### Can you add a market I want to trade?

Possibly. New markets go through a review before they're enabled, covering liquidity, order-book depth, volatility and how the exposure can be managed, so there's no fixed schedule for additions. Markets that pass are added, and the assets page and your dashboard always show what's currently tradable.

If there's a market you'd like to see, tell us in Discord. Requests feed into what we review next.

### Can I trade on mobile?

There's no Bungee Funded Perps mobile app at the moment. The terminal is web-based, so you trade it in the browser.

### What happens during extreme volatility?

Bungee may:

- reduce maximum position sizes
- change leverage for new trades
- put a market into reduce-only mode
- reject new orders
- force-close positions where the risk rules require it
- temporarily suspend or delist a market

---

## 7. Orders, Billing & KYC

_Paying for evaluations, refunds and identity verification._

### How do I sign in?

With your Google account or a crypto wallet.

### How do I pay for an evaluation?

In **USDC on Base.** At checkout you'll see a deposit address with a QR code, the exact amount to send and a payment deadline. Your account opens as soon as the payment is confirmed.

| If you…                      | Then…                                                   |
| ---------------------------- | ------------------------------------------------------- |
| Send the full amount or more | Your account opens                                      |
| Send less than the amount    | No account opens, and the payment goes to manual review |
| Miss the deadline            | No account opens; start a new purchase                  |

### Is the fee one-time, or is it a subscription?

One-time. You pay once per evaluation, and that's it: there's no subscription, no monthly fee and no renewal. If you breach an account and want to trade again, you buy a new evaluation.

### Can I have more than one account?

Yes. You can hold several active accounts at once, as long as their combined account size stays within **$100,000**. For example:

- one $100,000 account = $100,000
- two $50,000 accounts = $100,000
- four $25,000 accounts = $100,000

The cap counts the size of your active accounts, not margin used or position size, and checkout shows how much of it you've selected. Closed accounts don't count toward it. Each account keeps its own risk limits and is evaluated separately.

You can buy several accounts in a single purchase, provided the total stays within the $100,000 cap.

### When do I need to complete KYC?

After you pass your evaluation, before your first funded payout. You don't need to verify your identity to buy an evaluation or to trade one.

### What do I need for KYC?

Identity verification is handled by **Sumsub**, our verification provider. You'll need:

- a **government-issued photo ID**, such as a passport, national ID card or driving licence
- a **selfie check**, taken in the flow, to confirm the ID belongs to you

The check usually takes a few minutes, and you can start it from your dashboard once you've passed your evaluation.

### What happens if my KYC is rejected?

Payouts stay on hold until your identity is verified. Sumsub will tell you what needs correcting, and Bungee support can help if you're stuck.

---

## 8. Account & Support

_Your agreement with Bungee, disputes and platform issues._

### How do I contact support?

Three ways:

- **In-app chat** in the Bungee terminal
- **Discord**, for general questions and help from the community
- **Email**, for account-specific or payout issues

### What if I think there's a mistake on my account?

Raise a dispute through Bungee support. Bungee reviews disputes against its execution, account, pricing and risk logs, and may correct clear technical or accounting errors. Screenshots, spreadsheets, third-party charts and your own calculations don't override Bungee's records.

### What happens if Bungee has an outage?

Where an outage originates from Bungee infrastructure, Bungee may review affected accounts and determine an appropriate remedy at its discretion.

Bungee isn't responsible for losses or missed trading opportunities caused solely by:

- internet connectivity issues on your side
- device failures
- third-party software
- exchange or venue outages
- network congestion
- market-data interruptions
- force majeure events

### Can the rules change?

Yes. Bungee may update supported markets, leverage, position limits, fees, funding, evaluation availability, operational requirements and risk controls. Material changes will be communicated through the platform or the terms. Market-risk changes can take effect immediately when needed to protect traders, Bungee, venues or liquidity providers.

---

## 9. Referrals

_Info about the Bungee referral programme._

### Is there a referral programme?

Yes. Share your referral code and you earn **1% commission** on eligible purchases made with it, while the person you refer gets **10% off** their first eligible purchase.

There's also a **Founding Trader discount of 15%** on evaluation purchases.

You get one referral code, and it's yours permanently once created. The discount applies to a referred trader's first eligible purchase only, and you can't refer yourself.

### How do I get my referral earnings?

From the referrals page in your dashboard, which shows your commission rate, total earnings and how much is available to pay out, along with every confirmed purchase made with your code.

When you have commission available, request a payout and it's paid in **USDC on Base**. Referral payouts are processed manually and are separate from funded-account payouts, so the two don't affect each other.
