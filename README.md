<p align="left"><img src="https://komarev.com/ghpvc/?username=FranQuant&label=Profile%20views&color=0e75b6&style=flat-square" alt="Profile views"/></p>

## J. Francisco Salazar, CQF

**Quant researcher · systematic trading & asset allocation**

> *Models commoditize; pipelines don't.*

I build the research infrastructure where systematic edge actually lives: point-in-time data, pre-registered tests, and LLM workflows that handle the tedious 80% of research while humans keep the judgment calls.

---

### Selected work

| Project | What it shows | Stack |
|---|---|---|
| [**llm-regime-allocator**](https://github.com/FranQuant/llm-regime-allocator) | Four LLM families read 222 point-in-time macro snapshots (2007–2026) and call the next quarter's regime; a fixed 8-ETF playbook turns the call into weights. The headline Sharpe is 0.83 with a −14% max drawdown, against 0.66 / −32% for 60/40. A memory audit shows the models recognize the exact month 84% of the time from raw data; blinding the snapshots cuts that to 14% and the forecasts still beat ML on the same inputs. The Sharpe gaps aren't significant, so a pre-registered live log starts at the October 2026 month-end. | ![Anthropic](https://img.shields.io/badge/Anthropic-191919?style=flat-square&logo=anthropic&logoColor=white) ![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square) ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white) ![FRED/ALFRED](https://img.shields.io/badge/FRED%2FALFRED-2E5C8A?style=flat-square) |
| [**multi-asset-portfolio-lab**](https://github.com/FranQuant/multi-asset-portfolio-lab) | Seven allocation models (GMV, MaxSharpe, β-targeted MV, Black–Litterman, MDP, ERC, HRP) with covariance shrinkage and vol targeting, run walk-forward on 13 cross-asset ETFs (2009–2026) net of costs. After Holm / Romano–Wolf corrections none beats equal weight on Sharpe, and a power analysis shows why 17 years can't tell them apart. They differ in risk instead: vol targeting roughly halves the 2020 drawdown. | ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white) ![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white) ![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white) ![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white) |
| [**ai-pairs-trading**](https://github.com/FranQuant/ai-pairs-trading) | OU-diagnostic pair selection on ~11 years of LatAm ADRs lifts Sharpe from ≈0 (cointegration only) to 0.81; an earnings gate takes it to ~1.05, robust across holding windows. The news-sentiment overlay fails, and the repo documents why. | ![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white) ![EODHD](https://img.shields.io/badge/EODHD-555555?style=flat-square) |
| [**filings-qa-rag-demo**](https://github.com/FranQuant/filings-qa-rag-demo) | Cited RAG over SEC filings: every claim is traceable to a retrieved chunk, citations are validated, and generation switches between OpenAI and Anthropic. | ![SEC EDGAR](https://img.shields.io/badge/SEC%20EDGAR-1F3A5F?style=flat-square) ![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square) ![Anthropic](https://img.shields.io/badge/Anthropic-191919?style=flat-square&logo=anthropic&logoColor=white) |
| [**next-gen-agentic-finance**](https://github.com/FranQuant/next-gen-agentic-finance) | Ten-step progression of agentic research patterns, ending in an evidence → interpretation → open-gaps handoff for human review. Read-only tools, no execution. | ![Agno](https://img.shields.io/badge/Agno-333333?style=flat-square) ![Tavily](https://img.shields.io/badge/Tavily-333333?style=flat-square) ![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black) ![MCP](https://img.shields.io/badge/MCP-333333?style=flat-square) |
| [**the-ai-engineer**](https://github.com/FranQuant/the-ai-engineer) | Four capstones: gradient descent and backprop from scratch, a decoder-only transformer measuring FOMC textual surprise (pre-registered test), and an auditable MCP agent with telemetry replay. | ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![MCP](https://img.shields.io/badge/MCP-333333?style=flat-square) |

---

[LinkedIn](https://www.linkedin.com/in/j-francisco-salazar) · [X](https://twitter.com/frasagui2014)
