<h1 align="center">Akshay Raju</h1>

<p align="center">
  <b>Aspiring Data Engineer</b> &nbsp;·&nbsp; Assistant System Engineer @ TCS &nbsp;·&nbsp; Bangalore, India
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/akshay-raju-8485b0374">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
</p>

---

### About

- 🏦 I work in **production support for a Tier-1 global bank's Data Integration Service** at TCS: about 15 Linux servers across 3 regions, running Informatica ETL scheduled by Control-M
- 🛠️ I handle incidents (SSL, SFTP, Informatica failures), monitor ETL batches, and run ITIL change and problem management
- 🎯 I'm moving into **data engineering**, building pipelines on the same patterns I support at work, with an open-source stack
- 🎓 B.E. in Artificial Intelligence & Machine Learning

### Currently Building

**🌾 Mandi Price Pulse: daily ELT pipeline for Indian wholesale commodity prices**
An idempotent pipeline that turns the raw AGMARKNET feed into a clean, deduplicated, tested price history joined with district rainfall, so questions like *"Is tomato price in Kolar abnormal this week, and is rainfall a driver?"* have a table to query.
- **Ingest:** a Python extractor in Airflow pulls the paginated data.gov.in API with retries and lands raw JSON in MinIO, partitioned by date
- **Transform:** dbt models move the data through staging, intermediate and mart layers in PostgreSQL, fixing inconsistent names, gaps and duplicates
- **Context:** a separate monthly DAG loads IMD rainfall data into the same warehouse
- **Serve:** a Metabase dashboard, with the whole stack running in Docker Compose

`Python` · `Airflow` · `MinIO` · `PostgreSQL` · `dbt` · `Metabase` · `Docker Compose`

### Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-121011?style=flat-square&logo=gnu-bash&logoColor=white)

**Data Engineering**

![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle_19c-F80000?style=flat-square&logo=oracle&logoColor=white)
![MinIO](https://img.shields.io/badge/MinIO-C72E49?style=flat-square&logo=minio&logoColor=white)
![Metabase](https://img.shields.io/badge/Metabase-509EE3?style=flat-square&logo=metabase&logoColor=white)
![Informatica](https://img.shields.io/badge/Informatica_PowerCenter_%7C_IDMC-FF4500?style=flat-square)

**Infrastructure & Operations**

![Linux](https://img.shields.io/badge/Linux_(RHEL)-EE0000?style=flat-square&logo=redhat&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Control-M](https://img.shields.io/badge/Control--M-00A1E0?style=flat-square)
![ServiceNow](https://img.shields.io/badge/ServiceNow-62D84E?style=flat-square&logo=servicenow&logoColor=white)

### Education

**B.E., Artificial Intelligence & Machine Learning**, Sri Sairam College of Engineering (VTU), 2021–2025 · CGPA 8.5

---

<p align="center"><i>"Consistency beats talent when talent doesn't stay consistent."</i></p>
