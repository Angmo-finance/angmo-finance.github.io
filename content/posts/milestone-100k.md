---
title: "The $100,000 milestone archived"
date: 2022-02-11T12:00:00+08:00
draft: false
---

Less than half a year ago I published a list of my financial goals and now I'm pleased to report the second milestone, S$100,000 net worth, is archived! It also coincided with the end of the year, so I'll use the opportunity to do the year end review.

<!--more-->

### People say: The first 100k are the hardest

But why? Well, there are at least 3 reasons I can think of:

1. To save such amount of money one needs to establish good financial habits. Adapting new habits is always hard. And then, to reach 100k, the habits must be maintained for long enough.
2. On the way to 100k people are learning how to deal with money and make their mistakes, sometimes costly ones.
2. 100k is a large enough amount to start producing meaningful and visible return that helps to reach the next milestone.

### How did I get here?

At the end of 2020 I realized the importance of savings, paid all my debts and finally got the opportunity to put aside enough money every month. How do I know what is enough? Most personal [finance literature](https://www.investopedia.com/ask/answers/022916/what-502030-budget-rule.asp) recommends to save at least 20% of monthly income. While adepts of [FIRE movement](https://en.wikipedia.org/wiki/FIRE_movement) go to extremes of up to 90%.

I personally think something in between is a sweet spot if one can afford it. In my case, if I try to stash away 90% of income, I'll have to live on a street and eat only png from [cai png](https://en.wikipedia.org/wiki/Economy_rice) store. On another hand, I don't like inflating my lifestyle as my income increases and I don't need to spend 80% of what I earn now.

Since moving to Singapore, I actually manage to increase my income thanks to much low taxes here. Though it was somewhat balanced by increased rent. As the result over the last 1 year I archived an average saving rate of 57%. And it dropped below 60% only once in December due to my trip home.

On February 1, more than 100% of my net worth came from savings. To be exact, I saved $4,933 more than I have now. Yes, I currently experience some losses due to the correction of stock market and crypto crash in the beginning of the year.

### Breakdown

Let's dig deeper into each category of my financial worth from big to small. The assets distribution at the time of writing:

{{< chart >}}
{
  type: 'pie',
  data: {
    labels: ['Robo-Advisors', 'Crypto', 'Cash-like', 'ETFs', 'Stock picks'],
    datasets: [{
      label: 'February 2022',
      data: [49.63,18,12.4,12.13,7.84],
      backgroundColor: [
        'rgba(255, 99, 132)',
        'rgba(54, 162, 235)',
        'rgba(255, 206, 86)',
        'rgba(75, 192, 192)',
        'rgba(153, 102, 255)'
      ],
    }]
  },
  options: {
    maintainAspectRatio: false,
    plugins: {
      tooltip: {
        callbacks: {
          label: (v) => v.label +': ' + v.formattedValue + '%'
        }
      }
    }
  }
}
{{< /chart >}}

#### Robo Advisers

A half of my net worth is allocated to Robo Advisers, split into the following groups:

- StashAway 22% Risk Index - my retirement savings
- StashAway 10% Risk Index - mid term savings
- Syfe Equity 100 - has a different set of underlying securities so I can compare StashAway performance not only against indexes but other strategy too

All portfolios are currently slightly red.

I started seriously contributing to StashAway in December 2020. StashAway allocates ~15% of funds to China Tech. So I got a big hit to returns there:

![KWEB December 2020 to February 2022](/images/kweb-dec2020-feb2022.png)

Since the beginning of my journey with them, my portfolio went through multiple re-optimizations so it is hard for me trace the rest of under performers. As I get more financially savvy, I also start to question allocation into Gold and Australia equities and I would like more transparency on re-optimizations.

Despite rather disappointing returns after 1 year, I'm still happy with StashAway. They indeed do what was promised from the beginning (low fees, low volatility, active management to react to change in macroeconomic indicators). And 1 year is way too short period of time to judge their ability to generate profit.

My Syfe account also got hit but this time due to huge exposure to US Tech (QQQ + S&P500 account for a half of the portfolio) that crashed in the beginning of the year.

#### Crypto

It is a new asset class for me, I haven't written about before.

My current allocation here is rather simple with ETH and BTC taking the most of it. I dollar cost averaged on the way up and down, skipping the recent all time high. My third biggest coin is Luna and I use Terra ecosystem for its stablecoin[^1] as well.

I also got myself Crypto.com debit cart and staked S$500 in CRO. Besides, I have tiny allocations to other altcoins such as Sol, Avax, One, Atom.

This is the category with the most losses due to my attempts to trade with leverage which I will touch later in another post about my learnings.

Overall I'm very comfortable with the current allocation percentage to crypto and I plan to keep it ~15-20% long term by contributing more cash when it drops and withdrawing to less risky asset classes when it overshoots the target.

[^1]: Algorithmic decentralized stablecoin, it is supposed to equal to 1 USD most of the time.

#### Cash-like

I count interest bearing part of my emergency fund and war chest[^2] as a part of my net worth. I stopped using Singlife to get higher (but riskier) interest from stablecoins.

I use the following coins and services:
- UST with [Anchor protocol](https://www.anchorprotocol.com/) on Terra blockchain. It pays me around 19.5% APY[^3].
- GUSD with [Celsius](https://celsiusnetwork.app.link/11486762b1). It pays 8.50% APY at the time of writing.

I use GUSD instead of USDC or USDT because [Gemini](https://www.gemini.com/share/wwmamvxhe) is my main exchange to on-ramp SGD. It is fully USD-backed and I don't need to pay any fees to transfer it between Celsius and Gemini.

Keeping savings in stablecoins is a controversial topic, especially with something like UST which is not backed by real dollars. But I'm comfortable enough with risk/reward to convert ~2/3 of the emergency fund to coins.

Currently, it is the only green category which brought me extra ~S$1000 so far.

[^2]: Money I can use for new investment opportunities if I find something very attractive.
[^3]: Annual Percentage Yield, a return earned on an investment, taking into account the effect of compounding interest.

#### ETFs

For the last half a year I continued learning and I got comfortable with traditional brokers. ETFs is a big topic to explore and I'll write separate posts about it in the future. For now let's just take a look at my holdings:

- [IWDA](https://www.ishares.com/uk/individual/en/products/251882/ishares-msci-world-ucits-etf-acc-fund) aka iShares Core MSCI World UCITS ETF - broad index of companies from 23 developed countries to complement my StashAway portfolio.
- [3067](https://www.blackrock.com/hk/en/products/315923/ishares-hang-seng-tech-etf) aka iShares Hang Seng TECH ETF - 30 largest stocks Chinese stocks from HK stock exchange as I'm a big believer in Chinese tech.

I bought my share of 3067 in August and started contributing to IWDA monthly the same month. Both indexes are currently red.

#### Stock picks

Back in April last year, I opened my first brokerage account to try what I learnt about stock market in practice.

Currently, I use this account for multiple purposes with only small allocation to each:
- Learning and experimenting - trading can't be too hard, right? Wrong! But I understand it only after I try.
- There are some companies I like so I want to bet on them.
- I also use it as a replacement to [TOTO](https://en.wikipedia.org/wiki/Toto_(lottery)) by throwing a hundred bucks into meme stocks from time to time.

This category is also in red because some of the companies I like are located in China and it was a difficult year for them.

### Conclusion and Moving forward

I'm very excited to reach this milestone so fast.

Despite current state of the portfolio and macro headwind I feel optimistic about the future and believe I'll be able to archive my next goal soon.

I'll also publish another post with my learnings on the way to 100k soon.

As a bonus, I have updated my [Net Worth Tracker](/net-worth-tracker), so you can see how my net worth was changing month-by-month.
