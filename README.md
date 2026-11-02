# Revathi Muppala: Research Portfolio

Senior Business Analyst and NISM-certified Research Analyst (Series XV), with an MBA (Finance) and
13 years in financial data and analytics, including nearly seven years validating listed-company
fundamentals at Thomson Reuters. I am looking for research roles in Indian capital markets, with a
focus on **equity research, fund research and financial planning**.

This repository showcases personal projects from 2024 to present. I defined each product, wrote the
specifications and built it with Claude Code.

---

## 1. Personal Wealth and Goal Tracker

A goal-based financial planning and fund research tool for Indian investors.

- Maps investments across brokers (Zerodha, Groww, Dhan, INDmoney), CAS statements (CAMS/KFintech,
  NSDL/CDSL) and manually entered assets to financial goals, and flags each goal as on track or at risk.
- Projects lump-sum, SIP and step-up SIP contributions, with a Monte Carlo probability of reaching
  each goal.
- A **what-if simulator** previews the effect of extra investments, a shorter timeline or a smaller target.
- Shows each goal's portfolio composition by sector and market cap.
- Compares mutual funds with their category peers and benchmark.
- Reports realised and unrealised P&L and capital-gains tax estimates per tax account (self, spouse, HUF).

**Demo** (sample household, not real data): goals dashboard → retirement goal and portfolio
composition → what-if simulator (an extra ₹25,000/month SIP and a ₹5 lakh lump sum raise the
probability of reaching the target from 22.7% to 48.9%) → assets → tax optimization.

![Goal tracker demo](docs/demo/goal_tracker_demo.gif)

[Watch in higher quality (MP4)](docs/demo/goal_tracker_demo.mp4)

---

## 2. Learning Project: Systematic Equity Strategies (Nifty 200 / Nifty 500)

Built to learn quantitative investing and AI-assisted development.

- Specified 30-stock momentum and alpha portfolios drawn from the Nifty 200 and Nifty 500.
- Back-tested each strategy version against pre-set pass criteria and evaluated it on CAGR,
  Sharpe, Sortino, Jensen's alpha and maximum drawdown.
- Set up paper-trading portfolios to forward-test the strategies against the Nifty Alpha 30.

**Demo:** backtest library with pass/fail verdicts → one strategy version's pass criteria and
trials → paper-trading books with risk-adjusted performance.

![Backtests and paper trading demo](docs/demo/backtests_demo.gif)

[Watch in higher quality (MP4)](docs/demo/backtests_demo.mp4)

> All backtest and paper-trading results are simulated. They are not real trades or investment advice.

---

## Skills shown

- **Equity research:** industry and company analysis, financial statements, annual reports and
  management discussion, ratio analysis, relative valuation, peer comparison
- **Fund research:** category peer comparison, portfolio holdings, risk and return measures
  (Sharpe, Sortino, drawdown)
- **Financial planning:** goal-based planning, SIP and step-up SIP projections, what-if scenarios
- **Data and tools:** SQL, Power BI, Excel, Thomson Reuters Eikon, Claude Code
