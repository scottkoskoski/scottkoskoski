# Scott Koskoski

**Senior Analytics Engineer**
Memphis, TN · [LinkedIn](https://linkedin.com/in/scott-koskoski) · [Email](mailto:scottkoskoski@gmail.com)
*M.S. Computer Science, University of Tennessee (May 2026) · M.A. Economics, University of Memphis*

---

## About

I build production data pipelines, statistical and machine learning models, and analytics tooling. Seven years across logistics, retail, and finance, working end to end from SQL and Python pipelines through model evaluation to tested, repeatable deployment. Recent focus: deployment and migration automation for Microsoft Fabric and Power BI, per-customer anomaly detection, and LLM pipelines checked against production data.

---

## Pinned Repositories

| Repository | What it does |
|---|---|
| **[Stream Sentinel](https://github.com/scottkoskoski/stream-sentinel)** | Real-time fraud detection on Apache Kafka and Redis. Optuna-tuned XGBoost trained on 590,000+ real IEEE-CIS transactions (0.97 AUC on a stratified validation split), scored in 0.32 ms per message through a C++ inference path (about 3,100 messages per second per consumer). Hot-swappable model registry, live A/B testing via two-proportion z-tests, and PSI drift alerts that queue retraining. |
| **[DDoS Detection (PySpark)](https://github.com/scottkoskoski/ddos-pyspark)** | PySpark MLlib pipeline over 225,000+ network flows from the Canadian Institute for Cybersecurity. Compares logistic regression, random forest, and gradient-boosted trees; the grid-searched random forest reaches 99.9% recall and 99.99% precision on held-out data. Containerized Jupyter environment for reproducibility. |
| **[Civic Pulse](https://github.com/scottkoskoski/civic-pulse)** | dbt project on public Memphis crime data ingested from the city's open-data API. Staging-to-marts star schema with surrogate keys, generic and singular tests, Jinja macros, an incremental fact model, and an SCD Type 2 snapshot. |
| **[RISC-V RV32IM Emulator](https://github.com/scottkoskoski/isa-project)** | 32-bit RISC-V processor emulator in C with a classical five-stage pipeline. Full RV32I and RV32M instruction support, six-format decoder, ELF loader, 1 MiB little-endian memory with bounds checking. |
| **[Gardening App](https://github.com/scottkoskoski/gardening-app)** | Full-stack personalized gardening platform: plant scoring against user profile (zone, season, sunlight, space), weather-aware task reminders, interactive garden planner. Flask + SQLAlchemy backend, React + TypeScript + Vite frontend. |

Proprietary work at Green Mountain Technology (Microsoft Fabric and Power BI deployment automation, anomaly detection, the Cost Efficiency Index ML platform) and private repos (RAG-Lab, a retrieval-augmented explorer for Bureau of Labor Statistics wage data) can be discussed in interviews.

---

## Core Stack

**ML & Modeling** — XGBoost, LightGBM, CatBoost, scikit-learn, Spark MLlib, Optuna, TensorFlow/Keras, PyTorch

**Statistics & Experimentation** — Anomaly detection, A/B testing (two-proportion z-tests), causal and multivariate modeling, ARIMA/GAM forecasting, drift monitoring, model evaluation design

**LLMs & Retrieval** — RAG, FAISS, BGE embeddings, Hugging Face, DeepSeek-V3, LLM output evaluation

**Data Engineering** — dbt, Microsoft Fabric (lakehouses, OneLake), SQL Server, PostgreSQL, Apache Kafka, Redis, Spark/PySpark, pandas, Polars, NumPy

**BI & Visualization** — Power BI (semantic models, deployment pipelines), Tableau, R Shiny

**Languages** — Python, SQL (T-SQL), R, C/C++, TypeScript

**Tools & Platforms** — Git, GitHub Actions, GitLab, Docker, FastAPI, Flask, Azure

---

## Experience

**Senior Analytics Engineer** — Green Mountain Technology (Nov 2025 – Present)
*Previously: Senior Solutions Engineer (Apr–Oct 2025), Solutions Engineer II (Oct 2022 – Mar 2025), Solutions Engineer I (Aug 2020 – Apr 2022)*

**Data Analyst** — AutoZone (May 2022 – Oct 2022)

**Analytics Associate, Merchant Analytics** — Verisk Financial Argus / TransUnion (Jun 2019 – Jul 2020)

Full work history and project detail on my [resume](./ScottKoskoski.pdf).

---

*Last updated: November 2026*
