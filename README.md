## Alvin Agustio Hans

**Data Engineering | Business Intelligence | Applied Data Science**

I build practical data systems that turn raw data into reliable, decision-ready outputs. My work spans data pipelines, ETL/ELT, SQL, Python, data warehousing, analytics, and lightweight ML applications. I care about clean architecture, data quality, measurable outcomes, and building tools that are useful in real-world workflows.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/alvinagustio)
[![Email](https://img.shields.io/badge/alvinagustio79@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:alvinagustio79@gmail.com)

---

### At a Glance

| | |
|---|---|
| **Education** | B.S. Information Systems, Minor in Big Data, Universitas Multimedia Nusantara \| **GPA 3.81 / 4.00** |
| **Experience** | Data Science Intern @ **Matahari Putra Prima (Lippo Group)** \| Data Visualization Intern @ **Asia Pulp & Paper (Sinarmas Group)** |
| **Focus Areas** | Data Engineering | Data Warehousing | Business Intelligence | Analytics Engineering |
| **Languages** | Bahasa Indonesia \| English |

---

### Featured Work

#### [Retail Price Intelligence Pipeline](https://github.com/alvin-agustio/retail-price-intelligence-pipeline)

End-to-end **data engineering pipeline** for comparing public electronics catalog prices across Indonesian retailers. Collects reproducible product observations into raw MinIO storage, validates and standardizes them with Pydantic and Parquet, then serves an analytics-ready PostgreSQL + dbt warehouse.

| Metric | Value |
|--------|-------|
| Retailers Modeled | **4** |
| Product Categories | **3** |
| Data Flow | **Bronze → Silver → Gold** |

`Python` | `MinIO` | `Parquet` | `PostgreSQL` | `dbt` | `Docker Compose`

---

#### [Hybrid Search & Recommendation Engine](https://github.com/alvin-agustio/hybrid-search-recommendation-api)

End-to-end product search service deployed on FastAPI, combining **BM25 lexical retrieval** with **IndoBERT semantic embeddings** through reciprocal rank fusion. Includes two-stage fine-tuning, typo recovery with SymSpell, and segment-aware re-ranking for more relevant product discovery.

| Metric | Value |
|--------|-------|
| NDCG@10 | **0.798** |
| MRR | **0.373** |
| Recall@5 | **0.558** |
| Median Latency | **~99 ms** |

`Python` | `PyTorch` | `HuggingFace Transformers` | `FAISS` | `FastAPI` | `ClickHouse`

---

#### [ABSA Fintech Review](https://github.com/alvin-agustio/absa-fintech-review)

End-to-end NLP platform for analyzing **505K+ Indonesian fintech reviews** from Akulaku and Kredivo across **risk**, **trust**, and **service** aspects. Covers preprocessing, weak-label reconciliation, **PEFT (LoRA) transformer fine-tuning**, model evaluation, and a research dashboard for live and offline analysis.

| Metric | Value |
|--------|-------|
| Reviews Analyzed | **505K+** |
| Training Time Reduction | **up to 40%** |
| Best Accuracy | **95.22%** |

`Python` | `PyTorch` | `Transformers` | `PEFT` | `Streamlit` | `DuckDB`

---

#### [Loyalty KPI Dashboard](https://github.com/alvin-agustio/loyalty-kpi-dashboard)

Executive analytics dashboard for tracking YoY and YTD KPIs, retention funnels, healthiness scoring, and sales decomposition across retail loyalty programs. Built with modular Streamlit architecture to support multiple stakeholder views in one product.

`Python` | `Streamlit` | `ClickHouse`

---

#### [Customer Segmentation Analytics](https://github.com/alvin-agustio/customer-segmentation-analytics)

Analyzed **8M+ retail transactions** across **2M+ customers** to build behavioral segments with RFM feature engineering and unsupervised clustering. Also includes ABC-XYZ demand classification over **70K+ SKUs** and market basket analysis for cross-sell opportunities, wrapped in an interactive Streamlit dashboard.

`Python` | `scikit-learn` | `mlxtend` | `Streamlit` | `ClickHouse`

---

### Technical Skills

```text
Languages          Python, SQL
Data Engineering   ETL/ELT, Data Pipelines, Apache Airflow, dbt, MinIO, Parquet, Docker Compose
Databases & DWH    PostgreSQL, MySQL, ClickHouse, BigQuery, Data Warehousing
BI & Analytics     Power BI, Tableau, Streamlit, Looker Studio
Backend & Tools    FastAPI, REST APIs, Git
ML & NLP           PyTorch, HuggingFace, scikit-learn, FAISS
```

---

### Currently

I enjoy building the full shape of a data product, from raw data ingestion and transformation to reliable datasets, analytics, models, and interfaces that help people make better decisions.

**[Let's connect! ->](https://linkedin.com/in/alvinagustio)**
