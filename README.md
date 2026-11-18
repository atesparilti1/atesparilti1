<h1>Ates Parilti</h1>

<p>
  <b>Industrial Engineering @ TU Eindhoven</b> · I build AI and data tools that turn messy data into decisions.
</p>

<p>
  <a href="https://atesparilti.com"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-atesparilti.com-0B1F3A?style=flat-square"></a>
  <img alt="Based in" src="https://img.shields.io/badge/Based%20in-the%20Netherlands-2B4BFF?style=flat-square">
</p>

My rule for every project: **the model handles language, code handles the facts.** LLMs read, summarise and explain. The numbers come from code, and every claim can be traced to its source. Each project below is shipped with a live demo and tests.

## Featured work

| Project | What it does | Result | |
|---|---|---|---|
| **[SEC Filing Analyzer](https://github.com/atesparilti1/SEC-filer)** | LLM analysis of 10-K / 10-Q filings: risks, opportunities and red flags, each tied to a quote from the filing. Financials computed from SEC XBRL in Python, never by the model. | FastAPI · strict JSON-schema output · Ollama or OpenAI · cached · filing-to-filing comparison | [Live](https://atesparilti1.github.io/SEC-filer/) |
| **[EUV Supply Risk](https://github.com/atesparilti1/asml-euv-supply-risk)** | Monte Carlo study (20,000 paths) of ASML's single-source EUV supply chain. Every buffer policy is valued through my own DCF. | Recommended buffer: **+€59m** equity value vs none; uniform buffers **−€193m** | [Live](https://atesparilti1.github.io/asml-euv-supply-risk/) |
| **[ASML DCF Valuation](https://github.com/atesparilti1/asml-dcf-valuation)** | Ten-year DCF with a bottom-up revenue build (units × ASP), WACC, two terminal methods, comps and scenarios. Excel model plus an interactive site. | **€935** / share vs €1,611 market · 27/27 model checks pass | [Live](https://atesparilti1.github.io/asml-dcf-valuation/) |
| **[Demand Forecaster](https://github.com/atesparilti1/demand-forecaster)** | XGBoost global model across 500 product series, backtested, turned into safety stock, reorder point and order quantity. | MASE **0.74**: beats seasonal-naive by ~26% | [Live](https://atesparilti1.github.io/demand-forecaster/) |
| **[Discount Policy Simulator](https://github.com/atesparilti1/supplychain-dashboard)** | Cleans 51,290 order lines and simulates discount caps per category and market. | Above 20% off every category loses money; a cap lifts profit **+55% to +70%** | [Live](https://atesparilti1.github.io/supplychain-dashboard/) |

## Toolbox

**AI & data** · Python, pandas, XGBoost, statsmodels, SciPy, LLM APIs (OpenAI, Ollama), structured outputs, Monte Carlo simulation<br>
**Backend** · FastAPI, Pydantic, SQLAlchemy, SQLite / PostgreSQL, REST APIs, pytest<br>
**Frontend** · React, TypeScript, Vite, Tailwind CSS, Recharts, Flutter<br>
**Finance & operations** · DCF and comps, inventory policy, forecasting, Excel modelling<br>
**Daily tools** · Claude, Cursor, Git, GitHub Actions, Vercel

## Now

- Building AI systems that are grounded and measurable: source-checked outputs, eval sets, no invented numbers.
- Open to AI and software engineering roles in the Netherlands, part-time alongside my studies or full-time.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/atesparilti1/atesparilti1/output/github-snake-dark.svg">
  <img alt="Contribution snake" src="https://raw.githubusercontent.com/atesparilti1/atesparilti1/output/github-snake.svg">
</picture>
