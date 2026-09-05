<p align="center">
  <a href="https://github.com/ayoub-azacri">
    <img src="https://capsule-render.vercel.app/api?type=transparent&fontColor=2ea043&fontSize=48&height=80&width=900&text=Hello!%20I'm%20Ayoub%20Azacri%20%F0%9F%91%8B" alt="Ayoub Azacri" />
  </a>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=2ea043&center=true&vCenter=true&width=750&height=40&lines=Data%20Engineer%20%7C%20Lakehouse%20%26%20Streaming;Databricks%20%E2%80%A2%20Apache%20Spark%20%E2%80%A2%20dbt%20%E2%80%A2%20Airflow%20%E2%80%A2%20Kafka;Software%20Craftsmanship%20Applied%20to%20Data" alt="Typing headlines" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/ayoub-azacri/" target="_blank" rel="noopener noreferrer"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:ayoub.azacri@gmail.com" target="_blank" rel="noopener noreferrer"><img src="https://img.shields.io/badge/Email-ayoub.azacri@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <img src="https://img.shields.io/badge/Status-Seeking%20Alternance%20(12--24m)-00C853?style=for-the-badge" alt="Alternance Status" />
  <img src="https://img.shields.io/badge/Rythme-3%20sem.%20Entreprise%20%2F%201%20sem.%20HETIC-blue?style=for-the-badge" alt="Rythme" />
</p>

---

### 🚀 About Me

Software Engineer specialized in **Data Engineering**, currently completing a Master's in Data & AI at **HETIC** (Paris). I apply Software Craftsmanship principles (**OOP, Clean Code, TDD, CI/CD**) to design distributed, resilient, and production-ready Lakehouse and real-time streaming architectures.

* 🎯 **Contract Search:** Data Engineering Apprenticeship (12 or 24 months) • Available immediately • Île-de-France / Hybrid
* 🌱 **Current Deep-Dive:** dbt Core, Apache Airflow 3, Databricks Unity Catalog & Agentic Databases (Ghost)
* 💬 **Ask me about:** PySpark, Medallion Architecture, dbt incremental models, Kafka KRaft, Docker, DataOps

---

### 🏗️ Pipeline Architecture Blueprint

```text
  [ Sources: CDC / APIs / Events ]
                │
                ▼
  [ INGESTION & STREAMING ] ────► Apache Kafka (KRaft) ──► Spark Structured Streaming
                │
                ▼
  [ STORAGE: MEDALLION LAKEHOUSE ]
       ├── Bronze (Raw Storage)  : MinIO (S3) / PostgreSQL CDC
       ├── Silver (Cleaned / OBT): Databricks Delta Lake / PySpark
       └── Gold   (Business / DM): dbt Core (SCD Type 2, Kimball Star Schema)
                │
                ▼
  [ SERVING & ANALYTICS ] ──────► Redis (<5ms Cache) | Elasticsearch 8 (Hybrid Search) | BigQuery
                ▲
                │
  [ ORCHESTRATION & QUALITY ] ──► Apache Airflow 3 (Dockerized DAGs) + dbt tests + Pytest
```

---

### 📂 Featured Production Repositories

| Project | Core Stack | Architecture Highlights | Link |
| :--- | :--- | :--- | :---: |
| **Retail Lakehouse** | `Databricks` `dbt Core` `Airflow 3` `PostgreSQL` | Ingestion CDC (100k+ rows) → Silver OBT via Jinja macros → Gold SCD2 snapshots & fact_orders | [**Inspect Code** ➔](https://github.com/Ayoub-Azacri/Walmart_Airflow_Dbt_Project) |
| **Music Streaming Platform** | `Kafka KRaft` `Spark Streaming` `Redis` `MinIO` | Real-time event streaming (>1k evt/s), stateful fraud detection, distributed checkpoints, <5ms cache | [**Inspect Code** ➔](https://github.com/Ayoub-Azacri/spotifydata-project) |
| **Enterprise SQL DWH** | `SQL Server` `T-SQL` `Kimball` | Bronze-Silver-Gold ETL via stored procedures, Star Schema dimensional modeling (-45% query latency) | [**Inspect Code** ➔](https://github.com/Ayoub-Azacri/sql-data-warehouse-project) |
| **CineSearch & RAG Platform** | `Elasticsearch 8` `LangChain` `Docker` | Hybrid search (BM25 + kNN vector embeddings), contextual movie recommendation engine | [**Inspect Code** ➔](https://github.com/Ayoub-Azacri/elk-movies-platform) |

---

### 🛠️ Technical Stack Matrix

* **Distributed Engines & Lakehouse:**  
  <img src="https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white" /> <img src="https://img.shields.io/badge/Apache_Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white" /> <img src="https://img.shields.io/badge/dbt_Core-FF694B?style=flat-square&logo=dbt&logoColor=white" /> <img src="https://img.shields.io/badge/Apache_Airflow_3-017CEE?style=flat-square&logo=apacheairflow&logoColor=white" /> <img src="https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white" /> <img src="https://img.shields.io/badge/Delta_Lake-00ADD8?style=flat-square&logoColor=white" />

* **Databases, Cache & Search:**  
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" /> <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" /> <img src="https://img.shields.io/badge/Elasticsearch_8-005571?style=flat-square&logo=elasticsearch&logoColor=white" /> <img src="https://img.shields.io/badge/Google_BigQuery-4285F4?style=flat-square&logo=googlecloud&logoColor=white" /> <img src="https://img.shields.io/badge/AWS_S3-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white" /> <img src="https://img.shields.io/badge/Agentic_DB_(Ghost)-555555?style=flat-square" />

* **Languages & Scripting:**  
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" /> <img src="https://img.shields.io/badge/SQL_(Advanced)-4479A1?style=flat-square&logo=postgresql&logoColor=white" /> <img src="https://img.shields.io/badge/T--SQL-CC292B?style=flat-square&logo=microsoftsqlserver&logoColor=white" /> <img src="https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white" /> <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" />

* **DevOps, Testing & Quality:**  
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" /> <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" /> <img src="https://img.shields.io/badge/GitLab_CI-FC6D26?style=flat-square&logo=gitlab&logoColor=white" /> <img src="https://img.shields.io/badge/Pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white" /> <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" />

---

### 📊 GitHub Activity & Metrics

<p align="center">
  <img height="160" src="https://github-readme-stats-five-sigma-99.vercel.app/api?username=ayoub-azacri&show_icons=true&theme=tokyonight&title_color=2ea043&icon_color=2ea043&hide_border=true&bg_color=00000000&count_private=true&hide_rank=true" alt="stats" />
  <img height="160" src="https://github-readme-stats-five-sigma-99.vercel.app/api/top-langs/?username=ayoub-azacri&layout=compact&theme=tokyonight&title_color=2ea043&icon_color=2ea043&hide_border=true&bg_color=00000000&hide=html,css,javascript" alt="top langs" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=ayoub-azacri&theme=tokyonight&hide_border=true" alt="GitHub Streak" />
</p>

---
<p align="center"><i>⭐️ Engineered with Software Craftsmanship by <a href="https://github.com/ayoub-azacri">Ayoub Azacri</a></i></p>
