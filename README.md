<h1 align="center">bsdgsmm</h1>
<h3 align="center">Data Engineer · Analytics Engineer · Building reliable data platforms end to end</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Focus-Data%20Engineering-0A66C2?style=flat-square" alt="Focus" />
  <img src="https://img.shields.io/badge/Stack-Python%20%7C%20SQL%20%7C%20Spark-3776AB?style=flat-square" alt="Stack" />
  <img src="https://img.shields.io/badge/Open%20to-Collaboration-2EA44F?style=flat-square" alt="Open to collaboration" />
  <a href="https://github.com/bsdgsmm?tab=followers"><img src="https://img.shields.io/github/followers/bsdgsmm?label=Follow&style=flat-square&logo=github" alt="Follow" /></a>
</p>

---

## About Me

I design and build **production-style data systems**: batch and streaming pipelines, lakehouse architectures, dimensional models and the quality gates that keep them trustworthy.

- **Pipelines:** ingestion → validation → transformation → serving, orchestrated with **Airflow**
- **Modeling:** star schemas, dbt layers (staging → intermediate → marts), metric definitions
- **Streaming:** event pipelines with **Redpanda (Kafka API)** and **ClickHouse**, dead-letter queues, deduplication, late events
- **Lakehouse:** Bronze / Silver / Gold with **PySpark** and **Parquet**
- **Data quality first:** schema contracts, tests and quality gates that block bad data before it reaches dashboards

> A pipeline is done when it is tested, observable and reproducible, not when it first runs.

---

## Featured Projects

| Project | What it does | Key tech |
|---|---|---|
| [**dataforge-end-to-end-data-pipeline**](https://github.com/bsdgsmm/dataforge-end-to-end-data-pipeline) | End-to-end batch pipeline from raw ingestion to analytics-ready tables with automated quality checks | Python · PostgreSQL · Airflow · dbt |
| [**streampulse-realtime-analytics**](https://github.com/bsdgsmm/streampulse-realtime-analytics) | Real-time e-commerce event pipeline with schema validation, deduplication, late-event handling and a dead-letter queue | Redpanda · ClickHouse · Python |
| [**lakeforge-modern-data-lakehouse**](https://github.com/bsdgsmm/lakeforge-modern-data-lakehouse) | Medallion (Bronze/Silver/Gold) lakehouse for a synthetic online marketplace | PySpark · Parquet |
| [**dataops-sentinel**](https://github.com/bsdgsmm/dataops-sentinel) | Daily ETL platform with validated ingestion, dbt models and data-quality gates | Airflow · dbt · PostgreSQL |
| [**metricflow**](https://github.com/bsdgsmm/metricflow) | Analytics engineering platform: dimensional modeling, tested transformations, business metrics and BI dashboards | dbt · SQL · BI |
| [**retailpulse-ecommerce-analytics**](https://github.com/bsdgsmm/retailpulse-ecommerce-analytics) | Analytics on ~542K UK retail transactions: cleaning, star schema, 31 analytical SQL queries and a Streamlit dashboard | pandas · PostgreSQL · Streamlit |

---

## How My Projects Fit Together

```mermaid
flowchart LR
    A[Sources<br/>CSV · APIs · Events] --> B{Ingestion}
    B -->|batch| C[PostgreSQL / Parquet<br/>Bronze]
    B -->|stream| D[Redpanda]
    D --> E[ClickHouse]
    C --> F[dbt / PySpark<br/>Silver → Gold]
    F --> G[Quality Gates]
    G --> H[Marts & Metrics]
    H --> I[Dashboards<br/>Streamlit · BI]
    E --> I
```

---

## Tech Stack

**Languages**
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white" alt="SQL" />
</p>

**Processing & Orchestration**
<p>
  <img src="https://img.shields.io/badge/Apache%20Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white" alt="Airflow" />
  <img src="https://img.shields.io/badge/dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white" alt="dbt" />
  <img src="https://img.shields.io/badge/Apache%20Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white" alt="Spark" />
  <img src="https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="pandas" />
</p>

**Storage & Streaming**
<p>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/ClickHouse-FFCC01?style=for-the-badge&logo=clickhouse&logoColor=black" alt="ClickHouse" />
  <img src="https://img.shields.io/badge/Redpanda-E2401B?style=for-the-badge&logo=apachekafka&logoColor=white" alt="Redpanda" />
  <img src="https://img.shields.io/badge/Parquet-50ABF1?style=for-the-badge&logo=apache&logoColor=white" alt="Parquet" />
</p>

**Tooling & Visualization**
<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" alt="Streamlit" />
</p>

---

## GitHub Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=bsdgsmm&show_icons=true&hide_border=true&count_private=true" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=bsdgsmm&layout=compact&hide_border=true" alt="Top languages" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=bsdgsmm&hide_border=true" alt="GitHub streak" />
</p>

---

## Currently

- Extending my pipelines with CI/CD, data contracts and observability
- Deepening my knowledge of streaming architectures and cloud data warehouses
- Open to collaborating on **data engineering & analytics** projects

---

<p align="center">
  If you find these projects useful, feel free to star a repo or follow for updates.
</p>
