### Purushottam Kumar

Data and analytics consultant with 4 years of experience (7-market loyalty transformation, fraud detection, lead-propensity modelling) and an MBA. I build AI systems alongside the consulting work: data-quality agents, retrieval pipelines and evaluation harnesses. Open to full-time strategy and GenAI consulting roles, and to global opportunities.

Everything below is built on synthetic or public data and is labelled as such in each repo. Where tests mock the model, the repo says so.

---

**What I have built**

- [**10xConsulting**](https://10xconsulting-dusky.vercel.app): a live, hypothesis-first AI diagnostic (Next.js, Supabase, Trigger.dev), verified against 449 tests. The source repo is private; the live site is the demo.
- [**VeriGreen**](https://github.com/CAPP-Financials/verigreen): ESG claim substantiation. A Python service extracts claims from sustainability reports in three independent Claude passes, escalates disagreement, maps claims to GRI and SASB, and routes doubtful ones to a human review queue in a multi-tenant app. 140 ML-service tests with a mocked model; not validated on real reports.
- [**LangGraph Data Quality System**](https://github.com/CAPP-Financials/langgraph-dq-system): a five-agent state machine for profiling, validating and remediating data. 42 deterministic rules, no model in the validation path, two-key routing so only high-confidence fixes are applied automatically. 187 tests pass.
- [**Enterprise RAG Pipeline**](https://github.com/CAPP-Financials/enterprise-rag-pipeline): semantic chunking, BM25 plus dense hybrid retrieval, query expansion and RAGAS evaluation on LangGraph. 123 tests with a mocked LLM; relevance gains are a design target and have not been measured.
- [**HackerRank Orchestrate (September 2026)**](https://github.com/CAPP-Financials/hackerrank-orchestrate-september26): a 24-hour hackathon build, "Buy or Wait?", an agent that decides whether a user can safely afford a purchase. A deterministic forecasting and planning core, with Claude used only to extract facts from receipts and messages. 250 of 250 rows generated with no invariant violations; 17 of 25 sample requests matched exactly on the public samples.

---

**Currently:** open to full-time Strategy and GenAI consulting roles, alongside independent AI consulting work.

[LinkedIn](https://www.linkedin.com/in/purushottamkumar-strategy/) · [Portfolio](https://portfolio-seven-dusky-78.vercel.app) · 193purushottam@gmail.com · Based in India (IST)
