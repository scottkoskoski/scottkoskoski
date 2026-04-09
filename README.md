# Scott Koskoski
**Senior Analytics Engineer · Data Scientist · ML Engineer**  
Memphis, TN | [LinkedIn](https://linkedin.com/in/scott-koskoski) | [Email](mailto:scottkoskoski@gmail.com)  
*Master of Science, Computer Science (in progress) · Master of Arts, Economics*

---

## Professional Focus

I build end-to-end data and machine-learning systems that translate complex, high-volume data into actionable, bottom-line impact.

My recent work includes:
* **Cost Efficiency Index (CEI) Platform** – GPU-accelerated models on 1M+ LTL shipments, delivering multimillion-dollar freight savings (proprietary)
* **Internal RAG Chatbot** – Self-hosted 120B-parameter LLM grounded in company knowledge base via TF-IDF retrieval with conversation-aware context boosting, deployed with Docker Compose and Open WebUI (proprietary)
* **Stream Sentinel** – Production-grade real-time fraud detection system with event-driven Kafka streaming, XGBoost ML scoring (99.42% AUC), Redis behavioral profiling, and a full MLOps pipeline with live drift detection and automated retraining
* **RAG-Lab** – Retrieval-augmented question-answering service over 150k U.S. wage records, combining BGE embeddings with DeepSeek-V3 (private repo; code available to interviewers)
* **Full-Stack Solutions** – React/TypeScript front-ends paired with FastAPI or Flask back-ends, secured with JWT and deployed in Docker containers

I work across the full lifecycle—data engineering, feature design, modeling, MLOps, API design, and front-end delivery—and communicate results to technical and executive stakeholders.

---

## Core Technical Competencies

| Area | Primary Tools |
|------|---------------|
| **Machine Learning & Gen AI** | PyTorch (+CUDA) · Hugging Face Transformers (BERT, DeepSeek-V3) · scikit-learn · XGBoost · LightGBM · CatBoost · TensorFlow/Keras · FAISS · RAG · Ollama · TF-IDF · Optuna · ONNX · Statsmodels |
| **Data Engineering & Analytics** | Python · SQL (T-SQL, PL/pgSQL) · Pandas · NumPy · Polars · PySpark · Apache Kafka · ClickHouse · Statistical Modeling · A/B Testing · Tableau · Matplotlib |
| **Cloud & Infrastructure** | Azure (VMs, Functions, Blob, ML) · AWS (S3, EC2, Lambda, DynamoDB) · Docker · Docker Compose · Redis · Prometheus · Grafana · Git · CI/CD · GPU Acceleration |
| **Software & Web Development** | FastAPI · Flask · React/TypeScript · REST/JSON · JWT Authentication · Database Design |

---

## Selected Public Repositories

| Repository | Description | Key Stack Elements |
|------------|-------------|--------------------|
| **[Stream Sentinel](https://github.com/scottkoskoski/stream-sentinel)** | Real-time fraud detection system processing financial transactions through Kafka, scoring with XGBoost (99.42% AUC, P50 latency 7.1ms), and managing behavioral profiles in Redis. Features a complete MLOps pipeline with live PSI-based drift detection, automated retraining triggers, A/B testing, and model versioning. 10 Docker services, 21k+ TPS consumer throughput, hybrid PostgreSQL/ClickHouse persistence. | Apache Kafka · XGBoost · Redis · PostgreSQL · ClickHouse · Prometheus · Grafana · Docker · Optuna · CUDA |
| **[DDoS Detection with PySpark](https://github.com/scottkoskoski/ddos-pyspark)** | Distributed cybersecurity analytics pipeline that ingests raw PCAP traffic, engineers features, and trains classifiers to detect DDoS attacks using the CIC dataset. Includes Dockerized Jupyter environment for rapid experimentation. | PySpark · MLlib · Docker · Jupyter · Network Analysis |
| **[RISC-V ISA Emulator](https://github.com/scottkoskoski/isa-project)** | Modular 32-bit RISC-V processor emulator written in C, supporting full RV32IM integer, multiplication, and division instructions. Demonstrates low-level systems programming and computer architecture knowledge. | C · RISC-V Assembly · ELF Processing · Makefile |
| **[Gardening App](https://github.com/scottkoskoski/gardening-app)** | Full-stack personalized gardening platform with 12 major features across ~22k lines of code. Scores and recommends plants against user profile (zone, season, sunlight, space), generates smart task reminders and weather-aware alerts, and includes an interactive CSS grid garden planner with companion planting logic. Production-hardened with rate limiting, security headers, structured logging, and health checks. 18 Flask blueprints, 7 data models, Google OAuth, and a fully custom React UI with no component library. | React 19 · TypeScript · Vite · Flask · SQLAlchemy · SQLite · JWT · Google OAuth · CSS Modules |

> **Note:** Proprietary enterprise work (CEI Platform) and private repositories (RAG-Lab) are omitted from GitHub but can be discussed and demonstrated in technical interviews.

---

## Professional Experience & Impact

**Senior Analytics Engineer** | Green Mountain Technology | *Nov 2025 – Present*
- Scaled a SQL-based pricing analytics platform by designing data transformations, building rate table pipelines, and extending calculation logic to support new business entities and vendor integrations
- Built an internal RAG chatbot grounding a self-hosted 120B-parameter LLM (Ollama) in a 65-page Confluence knowledge base using TF-IDF section-level retrieval with conversation-aware context boosting—deployed via Docker Compose and Open WebUI

**Senior Solutions Engineer** | Green Mountain Technology | *Apr 2025 – Oct 2025*
- Architected Cost Efficiency Index (CEI) platform ingesting LTL freight data from 6+ SQL Server DBs and training 5 GPU-accelerated models on 1M+ records with automated hyperparameter tuning
- Delivered a minutes-to-insight workflow adopted by 6 enterprise shippers, replacing multi-day analyses with real-time freight-cost optimization

**Solutions Engineer II** | Green Mountain Technology | *Oct 2022 – Mar 2025*
- Engineered anomaly-detection pipelines and optimized ETL processes (**-40% runtime**), cutting manual monitoring **10+ hrs/week** and enabling negotiations that reduced client freight spend **15% annually**

**Data Analyst** | AutoZone | *May 2022 – Oct 2022*
- Optimized product-assortment algorithms via statistical analysis (Python, SAS, SQL), improving inventory efficiency **12%**
- Designed A/B-test frameworks across **5k+ stores** and built causal & multivariate models to surface performance drivers

**Solutions Engineer I** | Green Mountain Technology | *Aug 2020 – Apr 2022*
- Automated freight-rating scripts in Python, cutting workload **25%** and eliminating manual errors

**Analytics Associate** | Verisk Financial Argus (now part of TransUnion) | *Jun 2019 – Jul 2020*
- Forecasted revenue with ARIMA & GAM models (**92% accuracy**) and deployed ML pipelines in R & Python
- Tuned SQL queries across **15+ PB** of transaction data and built interactive Tableau dashboards delivering real-time insights

### Education & Recognition
- **M.S. Computer Science** (Data Mining & Intelligent Systems) — University of Tennessee, Knoxville | *Anticipated May 2026*
- **M.A. Economics** — University of Memphis | *Outstanding Graduate Student 2019 · Wells Fargo Analytics Challenge Winner*
- **B.A. Economics, Minor Mathematics** — University of Arkansas, Fayetteville

---

## Current Technical Focus

Building next-generation AI systems with emphasis on:
- **Production RAG architectures** for enterprise knowledge management
- **Real-time streaming ML systems** with event-driven scoring and automated MLOps
- **GPU-optimized ML pipelines** with automated hyperparameter tuning  
- **Real-time optimization systems** for supply chain and logistics
- **Scalable MLOps** deployment to cloud platforms

---

## How I Work

1. **Business First** – Define the metric that matters; every line of code aligns to measurable impact
2. **End-to-End Ownership** – Data ingestion → modeling → deployment → monitoring → optimization
3. **Scalable Architecture** – Design for production from day one with proper MLOps and infrastructure
4. **Clear Communication** – Rigorous documentation, actionable dashboards, and concise stakeholder updates
5. **Continuous Improvement** – Iterate with experiment tracking, automated testing, and post-deployment feedback loops

---

## How to Engage

* **Recruiters & Hiring Managers** – Feel free to reach out via email or LinkedIn for code walkthroughs, case-study presentations, or technical references
* **Technical Collaborators** – Open to joint open-source projects or research initiatives in ML, Gen AI, and high-performance data systems
* **Students & Early-Career Professionals** – Always happy to discuss career paths in data science and machine learning

**Resume PDF:** [Download](./ScottKoskoski.pdf)

---

*Transforming data into strategic advantage through innovative machine learning and engineering solutions.*

*Last updated — April 2026*
