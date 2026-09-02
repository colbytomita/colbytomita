# Hey, I'm Colby 👋

Cloud and data engineer in Honolulu. I build production systems end to end at Kamehameha Schools — Microsoft Fabric and Azure underneath, Power Platform and Power BI where the staff actually work. The habit I care most about is measuring what a design claims instead of trusting it, which is how I end up deleting my own features.

## 🔭 Current

* Building AI agents and RAG systems on top of our Fabric lakehouse, and the guardrails that keep them citing sources instead of inventing them
* ARL: testing whether a small local LLM beats a purely extractive slot-filler on paper abstracts. On a held-out topic it ties, so it stays off
* Sukui: bilingual EN/JP retrieval platform, solo build, live in production

## 🧰 Toolbox

Microsoft Fabric • Azure • Power BI • Power Platform • Python • TypeScript • SQL • PySpark • Next.js • Postgres/pgvector • Claude API • scikit-learn

## 🚀 Featured Projects

* ARL, AI Research Landscape (private) — turns a topic string into a self-contained HTML map of a research area: ranked papers, sub-area clusters, real citation edges, insight cards with sentence-level provenance. Four stages passing JSON on disk, so any stage re-runs without refetching and ~20 scoring ablations were affordable offline. Its own eval harness (recall@k, nDCG@k, clustering ARI) measured nDCG@25 at 0.859 and disproved six of my design spec's own prescriptions.
* [Sukui](https://sukui.org) — bilingual EN/JP platform with a source-grounded streaming chatbot. OpenAI embeddings into Supabase pgvector with IVFFlat, a custom Postgres cosine-similarity retrieval function, Claude API over SSE, salted IP-hash rate limiting. Next.js 14 and TypeScript, solo.
* [Water Reservoir Forecasting](https://github.com/colbytomita/water_reservoir_ml_predictor) — PLNU capstone. Django and Postgres app serving live predictions over 13 years of data across 16 reservoirs, comparing six regression models by MAE and MAPE in Plotly dashboards.

## 📈 What I'm learning

PL-300 (Power BI), IR evaluation beyond nDCG, Fabric governance and cost control

## 🤝 Connect

* Email: [tomitacolby@gmail.com](mailto:tomitacolby@gmail.com)
* LinkedIn: https://www.linkedin.com/in/colbytomita
* Website: https://sukui.org
