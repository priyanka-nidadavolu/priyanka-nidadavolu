# 👋 Hi, I'm Priyanka Nidadavolu

I'm a **Master's student in Data Science at UC San Diego** (GPA 3.77, graduating June 2027) and former **Software Engineer at IBM** (2.5 years). I build end-to-end AI systems — from LLM-based agents and RAG pipelines to data infrastructure and evaluation frameworks. My work sits at the boundary between ML engineering and applied research, where the goal is always to ship something that actually works in the real world.

---

## 🏆 Recent Highlights

- **2nd Place, Cloud Track** — DataHacks 2026, UC San Diego (Apr 2026): Built GridGreen, a carbon-aware ML copilot with an AI agent built on Anthropic Claude via MCP, Databricks DLT, Snowflake, and AWS SageMaker
- **Star of the Month** — IBM (Nov 2023): Production LLM system that reduced cloud compute costs by 40%
- **People's Choice Award** — IBM: Peer-nominated for data-driven decision-making
- **Top 30** — CodeHers Coding Challenge, India (2022)

---

## 🔧 Technical Skills

**Languages:** Python, SQL, R, C++, JavaScript/TypeScript  
**ML & AI:** PyTorch, scikit-learn, XGBoost, LLMs, RAG, NLP, Transformers, agentic frameworks (MCP), Anthropic Claude, LLaMA 3  
**Systems:** Triton (GPU kernels), CUDA, MPI (distributed training), autodiff  
**Data & Cloud:** PostgreSQL, MongoDB, Neo4j, Qdrant, Databricks DLT, Snowflake, AWS (S3, SageMaker), Kafka, Airflow  
**Backend & APIs:** FastAPI, REST APIs, Docker, CI/CD (Git, Jenkins)  
**Visualization:** Tableau, Matplotlib, Seaborn, Plotly, Streamlit  

---

## 💼 Experience

### UC San Diego, Information Technology Services *(Oct 2025 – Present)*
**Student Build & Release Engineer (Part-Time)**
Maintains CI/CD infrastructure for campus engineering services. Writes automation and runbooks so failures are diagnosed and resolved without starting from scratch.

### IBM *(Jan 2023 – Jul 2025)*
**Software Developer** *(promoted from Intern)*
- Shipped an LLM-based AI agent on production code diffs: classified cloud environment impact, routed CI/CD test runs autonomously, cut compute costs by 40%
- Rebuilt a data validation and preprocessing pipeline silently corrupting downstream ML releases; restructured logic end-to-end, reducing processing time by 90%
- Contributed to WatsonX Generative AI evaluation: prompt design, output quality assessment, failure pattern documentation
- Built multi-cloud provisioning backend using Python and IBM Cloud APIs across AWS, Azure, and IBM Cloud

### Samsung PRISM *(Jun 2021 – Mar 2022)*
**Research Intern, NLP & Speech**
- Applied Wav2Vec2 to validate phoneme accuracy against ground truth, improving speech recognition by 10%
- Built a programmatic data pipeline generating a structured phoneme dataset from 10,000+ contact names

---

## 🚀 Projects

### [GridGreen](https://github.com/datahacks-2026/grid-green) — 2nd Place, Cloud Track, DataHacks 2026
Carbon-aware ML copilot that reads training scripts, estimates compute and CO₂ cost using published scaling laws, and retrieves greener model alternatives via RAG.
- AI agent built with **Anthropic Claude via MCP**, running inside Cursor and Claude Desktop
- Databricks DLT data pipeline, AWS SageMaker batch inference, 48-hour Prophet forecasts
- Reproducible evaluation harness across 4 scenarios with 56 pytest tests
*Python, Anthropic Claude, MCP, Databricks DLT, Snowflake, AWS SageMaker, FastAPI, RAG*

### Socially-Aware Recommendation System — [Live Demo](https://priyankanidada-recommended-systems.hf.space/ui)
Top-N ranking system on Epinions (664K+ reviews, 49K users) handling 99.99% matrix sparsity using social trust-graph features.
- Beat a published IJCAI 2017 research baseline by 6% on AUC
- Deployed via FastAPI and Docker on Hugging Face Spaces with A/B model comparison UI
*Python, XGBoost, NetworkX, FastAPI, Docker*

### Clinical Decision-Support (MediDB)
AI-powered drug safety and recommendation system for clinical workflows.
- Multi-store retrieval: graph queries (Neo4j), vector search over FAERS adverse events (Qdrant), relational EHR records (PostgreSQL)
- ETL from Synthea synthetic EHR data with documented cleaning logic throughout
*Python, PostgreSQL, Neo4j, Qdrant, MongoDB, FastAPI*

### Autodiff Engine + Transformer Language Model
Built a custom automatic differentiation engine from scratch (no PyTorch autograd) and used it to train a decoder-only Transformer with causal self-attention and autoregressive decoding.
*Python, PyTorch, deep learning systems*

### GPU Kernel Optimization + Distributed Transformer Training
- Implemented a fused Triton kernel for D = ReLU(AxB + C) with shared memory tiling, operator fusion, and grid search tuning
- Built distributed Transformer training from scratch with MPI: AllReduce, AllToAll, data parallelism, tensor model parallelism
*Python, Triton, CUDA, MPI*

### GameSoul: Emotion-Driven Game Discovery *(In Progress)*
LLM pipeline using LLaMA 3 to extract 9-dimensional emotional vectors from Steam reviews at scale, with Thompson sampling bandit for personalization and Kafka streaming for continual learning.
*Python, LLaMA 3, Kafka, Airflow, Qdrant, FastAPI, Streamlit*

---

## 🎓 Education

**MS in Data Science** — UC San Diego *(2025 – Jun 2027)*  
GPA: 3.77/4.0 | Coursework: Machine Learning, Scalable Data Systems, Statistical Modeling, Recommender Systems

**B.Tech in Computer Science** — KL University *(2019 – 2023)*  
GPA: 3.67/4.0 | Specialization: Data Science & Big Data Analytics

---

## 🎯 What I'm Working On

- Extending GridGreen's evaluation harness with retrieval quality metrics (hit rate, MRR) and LLM-as-judge scoring
- Shipping GameSoul as a live deployed application
- Research assistantship exploration at UCSD's HDSI and Database Lab

---

## 📫 Let's Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-priyanka--nidadavolu-blue)](https://linkedin.com/in/priyanka-nidadavolu)
[![GitHub](https://img.shields.io/badge/GitHub-Priyanka--Nidadavolu-black)](https://github.com/Priyanka-Nidadavolu)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-green)](https://priyanka-nidadavolu.github.io/portfolio/)

📧 pnidadavolu@ucsd.edu
