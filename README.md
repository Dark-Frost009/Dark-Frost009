### Hi, I'm Sayantan 👋

**Early-career applied AI developer.** I build LLM agents and make them verifiable: grounded answers, validated outputs, bounded costs and tested failure modes. I moved into AI from a Biosciences background through a 16-month Data Science & AI program, and I bring the same habit of checking evidence to how AI systems are built.

I use AI coding assistants for much of the implementation; my own focus is the architecture, specifications and validation rules, tests, debugging and integration.

🔍 **Open to junior / associate roles** in Generative AI, agentic AI, LLM evaluation and AI automation: remote from India, or hybrid / onsite in Indian metros. Available immediately.

---

#### 🔎 [Research Agent](https://github.com/Dark-Frost009/research-agent) · [offline portfolio demo](https://research-agent-frosty.streamlit.app/)
A LangGraph research agent that only cites evidence it can verify.
- Plans sub-questions, searches with Tavily, fetches pages through an **SSRF-protected fetcher** and lets a critic decide whether more research is needed
- A citation is trusted only after **exact-quote grounding** and a separate **semantic verification** pass; if verification fails, it returns a safe fallback instead of a confident guess
- Whole-run budgets on searches, page fetches and LLM calls; offline evaluation scenarios, including adversarial page instructions; 2,100+ pytest tests
- `Python` `LangGraph` `Gemini` `Tavily` `Pydantic` `Streamlit` `pytest`

#### 📊 [AI Data Analyst Agent](https://github.com/Dark-Frost009/ai-data-analyst-agent) · [demo](https://groq-data-analyst.streamlit.app/) (access code required)
Upload a CSV, ask a question in plain English, get validated SQL, a chart and an explanation.
- LLM-generated SQL is treated as untrusted: **SQLGlot AST validation** (read-only, single statement, table and function allowlists, result limits) runs before a sandboxed **DuckDB** executes anything
- Disk-backed path for CSVs up to 100 MB / 2M rows; bounded follow-up questions within a session
- GitHub Actions CI with tests and a Docker health check; 460+ pytest tests, ~89% coverage
- `Python` `Groq` `DuckDB` `SQLGlot` `Pandas` `Plotly` `Streamlit`

---

**What I work with**
- **LLM apps & agents:** LangGraph, LangChain, RAG (ChromaDB, vector embeddings), prompt and context engineering, structured outputs with Pydantic, LLM APIs (Gemini, Groq, OpenAI)
- **Reliability & safety:** LLM evaluation scenarios, grounding and citation checks, prompt-injection safeguards, SSRF protection, SQL validation
- **Engineering practice:** Python, pytest, Git / GitHub, GitHub Actions, Docker, Streamlit
- **Data & ML foundations:** Pandas, NumPy, SQL, DuckDB, Matplotlib, Seaborn, Power BI, Scikit-learn (regression, classification, clustering), TensorFlow / Keras (ANN, CNN, RNN / LSTM), EDA, statistics

**Earlier projects**, including a [RAG conversational AI](https://github.com/Dark-Frost009/RAG-Conversational-AI), an [LSTM sentiment classifier](https://github.com/Dark-Frost009/Sentiment-Analysis-LSTM), recommender systems and predictive models, are in my repositories.

🎓 Executive Post-Graduate Certification in Data Science & AI, iHUB DivyaSampark, IIT Roorkee (with Intellipaat), May 2026  
🧬 B.Sc. (General), Biology, Siliguri College, 2023

📫 [LinkedIn](https://www.linkedin.com/in/sayantan-chaklader-06933127a) · [Portfolio](https://sayantancportfolio.netlify.app) · sayantan.c@protonmail.com
