<div align="center">

<!-- Banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,50:1e3a5a,100:0ea5e9&height=180&section=header&text=Data%20Engineer&fontSize=42&fontColor=ffffff&animation=twinkling" alt="header"/>

<br/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&duration=4000&pause=1200&color=38BDF8&center=true&vCenter=true&width=640&lines=Enterprise+data+platforms+%26+CDC;Oracle+%E2%86%92+Kafka+%E2%86%92+ClickHouse;Airflow+%C2%B7+ETL%2FELT+%C2%B7+Banking+DWH;Open+to+remote+opportunities)](https://git.io/typing-svg)

<br/>

[![Profile views](https://komarev.com/ghpvc/?username=donus0&label=Profile%20views&color=0ea5e9&style=flat-square)](https://github.com/donus0)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/donus0)
[![Telegram](https://img.shields.io/badge/Telegram-26A5E4?style=flat-square&logo=telegram&logoColor=white)](https://t.me/donus0)

</div>

---

## About me

I'm a **Data Engineer** building production data platforms in **banking / fintech**, with hands-on experience across orchestration, warehousing, and **change-data-capture (CDC)** pipelines.

I work end-to-end — from source systems and streaming ingestion to modeled layers, quality checks, and analytics delivery — with a focus on **reliability**, **clear data contracts**, and **measurable outcomes** (faster refreshes, fewer manual jobs, safer migrations).

```text
  Sources ──► CDC / Batch ──► Orchestration ──► Warehouse ──► Analytics
   Oracle         Kafka            Airflow        Oracle / CH      BI
   MS SQL      + Debezium           DAGs & CI      stage/fact/mart   dashboards
```

**Education:** B.S. in Applied Mathematics & Computer Science (AI department), Kosygin University — Moscow · expected **2027**

---

## Professional experience

**Data Engineer** · Corporate Data Warehouse · *Ingosstrakh Bank* · Sep 2025 — present

- Migrated operational sources from **MS SQL Server → Oracle** while keeping downstream business logic intact.
- Built **streaming CDC** in dev: **Oracle → Apache Kafka (Debezium) → ClickHouse** for near-real-time analytics paths.
- Operate shared **Apache Airflow** environments: access patterns, resource sharing, and cross-team workflow design.
- Stack: **Airflow, Kafka, Debezium, Oracle PL/SQL, Docker, Git**

**Database Administrator → Data platform work** · Retail analytics · *Ingosstrakh Bank* · Jul 2024 — Aug 2025

- Designed and maintained **Oracle** data marts (200+ objects): partitioning, indexes, incremental loads, materialized views.
- Moved from schema-per-use-case to a dedicated **Oracle DWH** layout (stage / fact / BI layers) — **~50% faster** data refresh.
- Replaced scheduled **DBMS Jobs** with **Airflow-orchestrated** source-to-target (S2T) pipelines; introduced **GitLab CI** for DAG delivery.
- Delivered **data-quality** monitoring in **Visiology** and automated Outlook alerts from Airflow metadata + warehouse state.

---

## What I work on

| Area | Focus |
|------|--------|
| **CDC & streaming** | Oracle CDC with **Kafka + Debezium**; replication to **ClickHouse** |
| **Pipelines** | Batch ETL/ELT, idempotent loads, incremental models |
| **Orchestration** | **Apache Airflow** — DAG design, SLAs, retries, multi-team platforms |
| **Storage** | **Oracle**, **PostgreSQL**, **ClickHouse** — modeling, performance, migrations |
| **Engineering** | **Python** & **SQL**, **Docker**, **Git** / CI for reproducible data jobs |
| **Analytics enablement** | Metrics, client segmentation, BI (Visiology, Superset, Excel/Power Pivot) |

---

## Tech stack

<h3 align="left">Languages & core</h3>
<p align="left">
  <a href="https://www.python.org" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python" width="40" height="40"/>
  </a>
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" alt="SQL"/>
</p>

<h3 align="left">Data platforms & orchestration</h3>
<p align="left">
  <a href="https://airflow.apache.org/" target="_blank" rel="noreferrer">
    <img src="./assets/airflow.svg" alt="Apache Airflow" width="35" height="35"/>
  </a>
  <a href="https://kafka.apache.org/" target="_blank" rel="noreferrer">
    <img src="./assets/kafka.svg" alt="Apache Kafka" width="35" height="35"/>
  </a>
  <a href="https://debezium.io/" target="_blank" rel="noreferrer">
    <img src="./assets/debezium.svg" alt="Debezium" width="35" height="35"/>
  </a>
  <a href="https://spark.apache.org/" target="_blank" rel="noreferrer">
    <img src="./assets/spark.svg" alt="Apache Spark" width="35" height="35"/>
  </a>
  <a href="https://clickhouse.com" target="_blank" rel="noreferrer">
    <img src="./assets/clickhouse.svg" alt="ClickHouse" width="35" height="35"/>
  </a>
  <a href="https://www.postgresql.org" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="PostgreSQL" width="40" height="40"/>
  </a>
  <a href="https://www.oracle.com/" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/oracle/oracle-original.svg" alt="Oracle" width="40" height="40"/>
  </a>
</p>

<h3 align="left">Infrastructure & tooling</h3>
<p align="left">
  <a href="https://www.docker.com/" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="Docker" width="40" height="40"/>
  </a>
  <a href="https://git-scm.com/" target="_blank" rel="noreferrer">
    <img src="./assets/git.svg" alt="Git" width="35" height="35"/>
  </a>
  <a href="https://www.linux.org/" target="_blank" rel="noreferrer">
    <img src="./assets/linux.svg" alt="Linux" width="35" height="35"/>
  </a>
</p>

<p align="left">
  <img src="https://img.shields.io/badge/CDC-Oracle%20%E2%86%92%20Kafka%20%E2%86%92%20ClickHouse-0ea5e9?style=for-the-badge" alt="CDC"/>
  <img src="https://img.shields.io/badge/ETL%2FELT-1e293b?style=for-the-badge" alt="ETL/ELT"/>
  <img src="https://img.shields.io/badge/Data%20Modeling-334155?style=for-the-badge" alt="Data Modeling"/>
  <img src="https://img.shields.io/badge/Data%20Quality-10b981?style=for-the-badge" alt="Data Quality"/>
</p>

---

## GitHub activity

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=donus0&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0f172a&title_color=38bdf8&icon_color=0ea5e9&text_color=e2e8f0&rank_icon=percentile" alt="GitHub stats" height="165"/>
<img src="https://github-readme-streak-stats.herokuapp.com/?user=donus0&theme=tokyonight&hide_border=true&background=0f172a&ring=0ea5e9&fire=38bdf8&currStreakLabel=e2e8f0" alt="GitHub streak" height="165"/>

<br/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=donus0&layout=compact&theme=tokyonight&hide_border=true&bg_color=0f172a&title_color=38bdf8&text_color=e2e8f0&langs_count=8" alt="Top languages" width="48%"/>

</div>

---

## Currently exploring

- Production-hardening **Oracle CDC** (Kafka + Debezium) and **ClickHouse** consumption patterns  
- **Airflow** platform patterns: SLAs, lineage, and shared multi-tenant clusters  
- Stronger **data quality** gates and contract tests in pipeline design  

---

## Let's connect

<div align="center">

Interested in **data engineering**, **CDC/streaming**, or **enterprise DWH** work — especially **remote-friendly** roles. Happy to chat.

<br/>

[![GitHub](https://img.shields.io/badge/GitHub-donus0-181717?style=for-the-badge&logo=github)](https://github.com/donus0)
[![Email](https://img.shields.io/badge/Email-artiom.trenin%40bk.ru-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:artiom.trenin@bk.ru)

</div>

<div align="center">
  <br/>
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,50:1e3a5a,100:0ea5e9&height=100&section=footer" alt="footer"/>
</div>
