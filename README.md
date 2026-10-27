## Arthur Neau

Final-year student at **ENSAE Paris** (Institut Polytechnique de Paris), also enrolled in the
**M2 Modélisation Aléatoire (M2MO)** at Université Paris Cité, graduating in September 2027.

I work on **rates, credit and volatility**, and on what can be built on top of them. Previous
internships: **credit trading at Barclays** and **rates structuring at BNP Paribas**. I am
looking for a **quantitative trading internship or graduate programme**, in Europe or abroad.

This profile collects the projects I build on the side.

---

### Featured

**Credit Relative Value at Barclays** · *private, internship project: results cannot be shared, happy to discuss it 1:1*

Built during my internship on the **EUR investment-grade credit desk at Barclays**: a research
pipeline for **relative value between corporate bonds**. It covers the full chain, from cleaning
several years of daily bond-level data (thousands of issues) to building mean-reversion and
machine-learning signals on spreads, and backtesting them with the biases that usually inflate
such results (look-ahead in static fields, flaw in data due to a lack of liquidity in certain bonds, overlapping
returns) addressed one by one. The code and the numbers belong to the desk, so they are not
published here. If you have questions on the methodology, I would be glad to go through it in
a call.

**[Out of Sample](https://arthurnoo.pythonanywhere.com)** · *weekly newsletter, live* · [notebooks](https://github.com/Arthurnoo/out-of-sample)

A weekly quant newsletter: one testable idea per issue, replicated end to end on
free data only. Each article comes with a notebook that downloads its own data and runs top to
bottom in Colab with no setup, with every parameter gathered in one section so the reader can
change it and rerun. Issues so far cover buying the dip, risk-neutral pricing, whether quants
use the formulas that we are taught, covariance estimation, how much history to use, and what
happens when every variable goes into a regression.

**Portfolio Terminal** · *private repository, happy to walk through it on request*

A Bloomberg-style financial terminal that runs locally: a single-page web app on a Python/Flask
backend. Cross-asset market data, TradingView-style charts with drawing tools and indicators, a
stock screener, a sandboxed Python backtesting engine (Sharpe, Sortino, max drawdown,
walk-forward), paper trading with realistic fills, and a world-events map fed by public data
sources (OpenSky, AIS, USGS, NASA, World Bank).

**On how it was built:** I designed the product (what each module should contain, which metrics
matter, how the backtests should be specified), but the screener itself was coded with the help 
of AI. Models implemented remain my my own ideas and my own code, though.

---

### Incoming

**Social Media Alpha** · *private, research project with Candriam*

A project carried out with the asset manager **Candriam** on whether information extracted from
social media carries a signal for asset returns, and how much of it survives once it is tested
out of sample.

**[weather-alpha-for-commodities](https://github.com/Arthurnoo/weather-alpha-for-commodities)** · *in progress*

Identifying trading signals in commodity markets from weather data: linking temperature and
precipitation forecasts to supply and demand in weather-sensitive commodities, and testing
whether that link can be traded.

---

### Quantitative finance

**[Monte-Carlo](https://github.com/Arthurnoo/Monte-Carlo)**: Approximate Bayesian Computation
for **alpha-stable models**. Joint project.
Alpha-stable distributions are a natural model for heavy-tailed financial returns, but their
density has no closed form, so the likelihood cannot be written down. Following Peters, Sisson
and Fan (2012), we implement the Chambers-Mallows-Stuck generator, reduce its variance with
randomised quasi-Monte Carlo (Sobol, Halton) and antithetic variates, then estimate the four
parameters with several ABC samplers (plain rejection, regression-adjusted rejection, MCMC-ABC)
built on McCulloch's quantile statistics.

**[Markowitz_Portfolio_Sim](https://github.com/Arthurnoo/Markowitz_Portfolio_Sim)**: Portfolio
simulator built on Markowitz mean-variance optimisation, with an interactive interface for
exploring the efficient frontier. A deliberately classical method, with well-known limits
(estimation error on the covariance matrix, instability of the weights).

---

### Academic projects (ENSAE)

**StatApp with Olympique Lyonnais** · *private repository*

Applied statistics project run with **Olympique Lyonnais** on the club's own player tracking
data: measuring how specific training and match efforts affect the fatigue players report.

**[ensae_proj_prog_24](https://github.com/Arthurnoo/ensae_proj_prog_24)**: Python for data
science. A recommendation engine for music festivals in France. Honest outcome: with no dataset
of actual user preferences, we could not train a predictive model, so the project ended as a
filtering and ranking engine rather than the recommender we set out to build.

**[ensae-prog24](https://github.com/lysaar/ensae-prog24)**: Algorithmics. Sorting an
*n×n* grid into a target arrangement while minimising the number of moves: a search problem
solved by comparing greedy, BFS and A\* strategies on the state graph.

---

### Stack

Python (pandas, NumPy, SciPy, scikit-learn, XGBoost, Flask) · R · SQL · Git · LaTeX

### Contact

[LinkedIn](https://www.linkedin.com/in/arthur-neau) · arthur.neau@ensae.fr
