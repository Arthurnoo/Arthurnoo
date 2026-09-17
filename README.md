## Arthur Neau

Final-year student at **ENSAE Paris** (Institut Polytechnique de Paris), also enrolled in the
**M2 Modélisation Aléatoire (M2MO)** at Université Paris Cité — graduating in September 2027.

I work on **rates, credit and volatility**, and on what can be built on top of them. Previous
internships: **credit trading at Barclays** and **rates structuring at BNP Paribas**. I am
looking for a **quantitative trading internship or graduate programme**, in Europe or abroad.

This profile collects the projects I build on the side. Each one below says plainly what it is,
what it does, and what I actually did myself.

---

### Featured

**Portfolio Terminal** · *private repository — happy to walk through it on request*

A Bloomberg-style financial terminal that runs locally: a single-page web app on a Python/Flask
backend. Cross-asset market data, TradingView-style charts with drawing tools and indicators, a
stock screener, a sandboxed Python backtesting engine (Sharpe, Sortino, max drawdown,
walk-forward), paper trading with realistic fills, and a world-events map fed by public data
sources (OpenSky, AIS, USGS, NASA, World Bank).

**On how it was built:** I designed the product — what each module should contain, which metrics
matter, how the backtests should be specified — but the code itself was written with the
assistance of **Claude (Anthropic)**, in an iterative loop where I specified and reviewed each
feature. I mention this because it matters: it is a product and system-design project, not a
demonstration that I can write 20k lines of Flask by hand. What I take from it is the modelling
and the market plumbing — data sourcing, backtest methodology, execution assumptions.

---

### Quantitative finance

**[Markowitz_Portfolio_Sim](https://github.com/Arthurnoo/Markowitz_Portfolio_Sim)** — Portfolio
simulator built on Markowitz mean-variance optimisation, with an interactive interface for
exploring the efficient frontier. A deliberately classical method, with well-known limits
(estimation error on the covariance matrix, instability of the weights) — I built it to get
hands-on with the mechanics of portfolio construction rather than to propose it as a live tool.

**[Monte-Carlo](https://github.com/Arthurnoo/Monte-Carlo)** — Approximate Bayesian Computation
for **alpha-stable models**: inference on distributions whose likelihood has no closed form, a
setting that shows up whenever you take heavy tails in financial returns seriously. Joint work,
also mirrored at
[avnerelbaz3500/Monte-Carlo-ABC-for-alpha-stable-models](https://github.com/avnerelbaz3500/Monte-Carlo-ABC-for-alpha-stable-models) *(private)*.

---

### Academic projects (ENSAE)

**[ensae_proj_prog_24](https://github.com/Arthurnoo/ensae_proj_prog_24)** — Python for data
science. A recommendation engine for music festivals in France. Honest outcome: with no dataset
of actual user preferences, we could not train a predictive model, so the project ended as a
filtering and ranking engine rather than the recommender we set out to build.

**[lysaar/ensae-prog24](https://github.com/lysaar/ensae-prog24)** — Algorithmics. Sorting an
*n×n* grid into a target arrangement while minimising the number of moves: a search problem
solved by comparing greedy, BFS and A\* strategies on the state graph.

**romandb21/StatApp** *(private)* — Applied statistics in collaboration with **Olympique
Lyonnais**: measuring the effect of training and match workload on player fatigue, on club
tracking data.

---

### Stack

Python (pandas, NumPy, SciPy, scikit-learn, Flask) · R · SQL · Git · LaTeX

### Contact

[LinkedIn](https://www.linkedin.com/in/arthur-neau) · arthur.neau@ensae.fr
