<h2 align="center">Houcem Hammami — Technical Manager, AI & Data Engineering</h2>

<p align="center">
  AI & Data systems engineer · Tunisia &nbsp;|&nbsp;
  <a href="https://linkedin.com/in/houcem-hammami">LinkedIn</a> &nbsp;·&nbsp;
  <a href="mailto:houcem0508@gmail.com">houcem0508@gmail.com</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Open%20To-Technical%20Manager%20%7C%20AI%20Engineering%20Manager%20%7C%20Data%20Engineering%20Manager-0077B5?style=flat-square"/>
</p>

---

I design and build data-intensive systems end-to-end: streaming pipelines, ML fraud detection platforms, LLM-native ETL engines, and modern analytics stacks. My work combines engineering depth with technical leadership — architecture decisions documented in ADRs, systems governed by quality contracts, and everything reproducible.

Currently a researcher at **LATICE Laboratory, ENSIT, Université de Tunis**, building toward Technical Manager and AI Engineering Manager roles in AI/Data platform engineering.

---

## Featured Projects

### Real-Time Schema Drift Detection
**[realtime-streaming-pipeline](https://github.com/houcem58/realtime-streaming-pipeline)** · Python · Kafka · Docker

Stateful micro-batch drift detector for Apache Kafka streams. Detects 5 drift types (schema rename, type, missingness, value, distribution) validated across 4 public datasets. Includes full evaluation framework with F1/Precision/Recall/FPR reporting, threshold calibration documentation, and two Architecture Decision Records explaining the design choices.

`kafka` · `drift-detection` · `mlops` · `streaming` · `python`

---

### Modern Data Platform
**[modern-data-platform-demo](https://github.com/houcem58/modern-data-platform-demo)** · dbt · Airflow · PostgreSQL · Power BI

4-layer Kimball star schema (staging → dimensions → fact → consumption) with 9 source quality gates, 8-task Airflow DAG with SLA monitoring, Power BI semantic layer with rolling window DAX measures, and 28 unit tests covering ingestion and validation logic.

`dbt` · `airflow` · `postgresql` · `power-bi` · `data-engineering`

---

### AML Fraud Detection Platform
**[aml-fraud-detection-platform](https://github.com/houcem58/aml-fraud-detection-platform)** · GNN · XGBoost · Kafka · FastAPI

Anti-money laundering platform combining HybridGAT graph neural network with XGBoost tabular scoring, context-aware fusion (ISOLATED vs DENSE transaction network contexts), BCT/ACPR/FinCEN regulatory rule engine, SHAP explainability, and nightly RLHF recalibration with automatic rollback. Full model card and ADR included.

`fraud-detection` · `graph-neural-network` · `aml` · `kafka` · `fintech` · `regulatory`

---

### ConversaETL — Typed Conversational ETL
**[ConversaETL-Showcase](https://github.com/houcem58/ConversaETL-Showcase)** · LLM · Python · Research

Converts natural-language ETL requests into validated, reproducible dataframe transformations via LLM-assisted typed planning + deterministic compiler stack + output contract validation. ConversaBench evaluation: HC F1=0.847 vs. direct LLM code generation F1=0.691. No LLM-generated code executed at runtime. Research under review.

`llm` · `etl` · `typed-compilation` · `nlp` · `research` · `generative-ai`

---

## Stack

| Domain | Technologies |
|---|---|
| Data Engineering | dbt · Apache Airflow · Apache Kafka · PostgreSQL · Python |
| Machine Learning | XGBoost · LightGBM · PyTorch Geometric · HuggingFace Transformers · scikit-learn |
| MLOps | SHAP explainability · RLHF · drift detection · model versioning · GitHub Actions |
| Infrastructure | Docker · Docker Compose · CI/CD pipelines |
| Analytics | Power BI · DAX · Kimball star schema · rolling window aggregations |
| Documentation | Architecture Decision Records · Model Cards · Runbooks · Sequence diagrams |
| Languages | Python · SQL (PostgreSQL, dbt-SQL) |

---

## Engineering Approach

Every repo in this portfolio includes:

- **ADRs** — architecture decisions with rejected alternatives and review triggers
- **Model cards** — evaluation metrics, fairness considerations, limitations
- **Runbooks** — operational procedures and failure recovery steps
- **Sequence diagrams** — system interaction flows in Mermaid
- **Engineering standards** — contribution guidelines and quality gates

---

## Open To

**Technical Manager** / **AI Engineering Manager** / **Data Engineering Manager** / **Technical Program Manager** / **AI Platform Lead**

Remote · Tunisia · France · Open to relocation for senior roles.

---

<p align="center">
  <a href="https://github.com/houcem58/realtime-streaming-pipeline">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=houcem58&repo=realtime-streaming-pipeline&theme=default&hide_border=true" alt="realtime-streaming-pipeline"/>
  </a>
  <a href="https://github.com/houcem58/aml-fraud-detection-platform">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=houcem58&repo=aml-fraud-detection-platform&theme=default&hide_border=true" alt="aml-fraud-detection-platform"/>
  </a>
</p>
<p align="center">
  <a href="https://github.com/houcem58/modern-data-platform-demo">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=houcem58&repo=modern-data-platform-demo&theme=default&hide_border=true" alt="modern-data-platform-demo"/>
  </a>
  <a href="https://github.com/houcem58/ConversaETL-Showcase">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=houcem58&repo=ConversaETL-Showcase&theme=default&hide_border=true" alt="ConversaETL-Showcase"/>
  </a>
</p>
