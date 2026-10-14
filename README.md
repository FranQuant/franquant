## J. Francisco Salazar, CQF

**Quant researcher · systematic trading & asset allocation · AI for investment research** · Bogotá 🇨🇴

> *Models commoditize; pipelines don't.*

I build the research infrastructure where systematic edge actually lives: point-in-time data, pre-registered tests, and LLM workflows that handle the tedious 80% of research while humans keep the judgment calls.




---

### Selected work

| Project | What it shows | Stack |
|---|---|---|
| [**llm-regime-allocator**](https://github.com/FranQuant/llm-regime-allocator) | Four LLM families read 222 point-in-time macro snapshots (2007–2026) and call the next quarter's regime; a fixed 8-ETF playbook turns the call into weights. The headline Sharpe is 0.83 with a −14% max drawdown, against 0.66 / −32% for 60/40. A memory audit shows the models recognize the exact month 84% of the time from raw data; blinding the snapshots cuts that to 14% and the forecasts still beat ML on the same inputs. The Sharpe gaps aren't significant, so a pre-registered live log starts at the October 2026 month-end. | `anthropic` `openai` `scikit-learn` `FRED/ALFRED` |
| [**multi-asset-portfolio-lab**](https://github.com/FranQuant/multi-asset-portfolio-lab) | Seven allocation models (GMV, MaxSharpe, β-targeted MV, Black–Litterman, MDP, ERC, HRP) with covariance shrinkage and vol targeting, run walk-forward on 13 cross-asset ETFs (2009–2026) net of costs. After Holm / Romano–Wolf corrections none beats equal weight on Sharpe, and a power analysis shows why 17 years can't tell them apart. They differ in risk instead: vol targeting roughly halves the 2020 drawdown. | `numpy` `scipy` `pandas` `pytest` |
| [**ai-pairs-trading**](https://github.com/FranQuant/ai-pairs-trading) | OU-diagnostic pair selection on ~11 years of LatAm ADRs lifts Sharpe from ≈0 (cointegration only) to 0.81; an earnings gate takes it to ~1.05, robust across holding windows. The news-sentiment overlay fails, and the repo documents why. | `pandas` `numpy` `EODHD` |
| [**filings-qa-rag-demo**](https://github.com/FranQuant/filings-qa-rag-demo) | Cited RAG over SEC filings: every claim is traceable to a retrieved chunk, citations are validated, and generation switches between OpenAI and Anthropic. | `EDGAR` `openai` `anthropic` |
| [**next-gen-agentic-finance**](https://github.com/FranQuant/next-gen-agentic-finance) | Ten-step progression of agentic research patterns, ending in an evidence → interpretation → open-gaps handoff for human review. Read-only tools, no execution. | `agno` `tavily` `duckdb` `mcp` |
| [**the-ai-engineer**](https://github.com/FranQuant/the-ai-engineer) | Four capstones: gradient descent and backprop from scratch, a decoder-only transformer measuring FOMC textual surprise (pre-registered test), and an auditable MCP agent with telemetry replay. | `pytorch` `mcp` |

---

[LinkedIn](https://www.linkedin.com/in/j-francisco-salazar) · [X](https://twitter.com/frasagui2014)
