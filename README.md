<div align="center">

# Hooria Khan

### Perception Engineer · Data Engineer · Data Analyst

I build systems that turn **visual signals and raw data into useful decisions** — from real-time computer-vision pipelines to cloud data platforms and business analytics.

[![GitHub](https://img.shields.io/badge/GitHub-hooriaakhann-181717?style=for-the-badge&logo=github)](https://github.com/hooriaakhann)
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Computer Vision](https://img.shields.io/badge/Computer_Vision-Perception-6C63FF?style=for-the-badge)](#-perception--computer-vision)
[![Data Engineering](https://img.shields.io/badge/Data-Engineering-0A66C2?style=for-the-badge)](#-data-engineering)
[![Analytics](https://img.shields.io/badge/Data-Analytics-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](#-data-analytics)

</div>

---

## About me

I am a computer-science graduate working at the intersection of **AI perception, computer vision, data engineering, and analytics**.

My current engineering work focuses on perception for XR/AI systems: processing egocentric video, tracking hands and objects, extracting motion signals, and evaluating real-time computer-vision methods. Alongside that, I build cloud data pipelines and analytics solutions using technologies such as Azure, Kafka, Spark, Airflow, Docker, PySpark, Synapse, Power BI, and Python.

I am especially interested in graduate study and research involving **computer vision, multimodal AI, intelligent perception, machine learning, and scalable data systems**.

> My portfolio is intentionally split into three connected areas: **Perception**, **Data Engineering**, and **Data Analytics**.

---

# 👁️ Perception & Computer Vision

My primary professional focus is building systems that interpret real-world visual input reliably and efficiently.

### Areas I work with

`Computer Vision` `YOLO` `MediaPipe` `Optical Flow` `Object Tracking` `Hand Tracking` `CNNs` `RepNet` `Temporal Signals` `Multimodal AI` `OpenCV` `Python`

### Current technical themes

- Egocentric video understanding from smart-glasses / first-person camera streams
- Real-time object and hand detection for interactive XR workflows
- Motion tracking and temporal signal extraction from video
- Optical-flow and keypoint-based motion analysis
- Repetition / periodic-action estimation from video
- Model evaluation, failure analysis, and confidence-based fusion
- Low-latency perception pipelines designed for real-world use

> Some perception work is part of my current professional role and remains private. Public repositories use independent or sanitized examples rather than proprietary code, data, or internal system details.

---

# ⚙️ Data Engineering

I build pipelines that move data from source systems into reliable analytical layers, with an emphasis on reproducibility, incremental loading, orchestration, and clean serving models.

### 🏥 [Homecare Business Insights Platform](https://github.com/hooriaakhann/Homecare-Business-Insights-Platform) — Professional Client Project

A cloud-based homecare-services analytics platform integrating operational APIs into Azure for reporting and business intelligence.

```text
Operational APIs → Azure Durable Functions → ADLS Gen2
                                      ↓
                           Bronze → Silver → Gold
                                      ↓
                         Synapse Serverless SQL
                                      ↓
                                Power BI
```

**Stack:** `Python` `Azure Durable Functions` `ADLS Gen2` `Parquet` `Azure Synapse` `Power BI` `Bicep` `GitHub Actions`

**What it demonstrates:**
- Incremental, full-refresh and date-range ingestion strategies
- Watermark-based loading with overlap windows
- Immutable Bronze storage and replayable raw history
- Typed, normalized and deduplicated Silver datasets
- Gold facts, dimensions, history tables and reporting marts
- Synapse Serverless SQL over Parquet
- Azure infrastructure-as-code with Bicep
- CI/CD workflows for infrastructure, application and SQL deployment
- Privacy-aware handling of homecare operational data

> This is represented publicly as a sanitized case study. Real client data, credentials, production resource names and proprietary source code are intentionally excluded.

### 🚗 [PakWheels ETL Pipeline](https://github.com/hooriaakhann/PakWheels-ETL-Pipeline)

An end-to-end streaming data pipeline for automotive listings.

```text
PakWheels → Selenium → Kafka → Spark Structured Streaming → Parquet → Streamlit
                              ↑
                           Airflow
```

**Stack:** `Python` `Selenium` `Apache Kafka` `PySpark` `Apache Airflow` `Docker` `Parquet` `Streamlit`

**What it demonstrates:**
- Automated web-data extraction
- Event-driven ingestion with Kafka
- Streaming processing with Spark
- Workflow orchestration with Airflow
- Containerized infrastructure
- Analytical serving through a Streamlit dashboard

---

# 📊 Data Analytics

I also work on turning structured operational and business data into understandable KPIs, trends, and decision-support dashboards.

### 📊 [Revenue & Profit Tracker](https://github.com/hooriaakhann/Revenue-Profit-Tracker)

Interactive Power BI analysis of sales, revenue, profit, category performance, and payment behavior.

**Stack:** `Power BI` `DAX` `Power Query` `Data Modeling` `KPI Design`

### Analytics experience

`Power BI` `DAX` `Power Query` `Pandas` `NumPy` `SQL` `Matplotlib` `Data Cleaning` `Exploratory Data Analysis` `KPI Reporting` `Operational Analytics`

---

# 🤖 Machine Learning

### [ChurnSense](https://github.com/hooriaakhann/ChurnSense)

An end-to-end customer-churn analysis and machine-learning workflow built around the Telco Customer Churn dataset.

**Stack:** `Python` `PySpark` `MLlib` `Scikit-learn` `Pandas` `Jupyter`

The project covers data cleaning, EDA, feature engineering, model training, and evaluation while connecting model output to a real business-retention problem.

---

## 🧰 Technical toolbox

| Area | Technologies |
|---|---|
| **Perception / CV** | OpenCV, YOLO, MediaPipe, Optical Flow, Object Tracking, Hand Tracking, RepNet, CNNs |
| **ML / AI** | Scikit-learn, PySpark MLlib, Neural Networks, RAG, LLM workflows, Multimodal AI |
| **Data Engineering** | Apache Kafka, Apache Spark, PySpark, Airflow, ETL/ELT, Parquet, Bronze/Silver/Gold |
| **Analytics** | Power BI, DAX, Power Query, Pandas, NumPy, Matplotlib, SQL |
| **Cloud / Platforms** | Azure Functions, ADLS Gen2, Azure Synapse, Azure Key Vault, Application Insights, Microsoft Fabric |
| **DevOps / Infra** | Docker, Git, GitHub Actions, Bicep, CI/CD |
| **Programming** | Python, SQL, Jupyter |

---

## 🔬 Engineering mindset

I try to make projects demonstrate more than tool usage. I focus on:

- **Reproducibility** — clear setup, dependency files, environment templates, infrastructure-as-code, and version control
- **Evaluation** — measurable performance instead of screenshots alone
- **Modularity** — separating ingestion, transformation, modeling, and serving layers
- **Real-world constraints** — latency, noisy inputs, data quality, failures, schema changes, and maintainability
- **Data responsibility** — protecting secrets, private datasets, and client information
- **Communication** — documenting not only *what* was built, but *why* each technical choice was made

---

## 📌 Portfolio map

| Domain | Project | Focus |
|---|---|---|
| 👁️ Perception / CV | **Perception research & engineering** | Egocentric CV, hand/object tracking, motion analysis, temporal estimation |
| ☁️ Data Engineering | **[Homecare Business Insights Platform](https://github.com/hooriaakhann/Homecare-Business-Insights-Platform)** | Azure Functions, ADLS, Bronze/Silver/Gold, Synapse, Bicep, CI/CD |
| ⚙️ Data Engineering | **[PakWheels ETL Pipeline](https://github.com/hooriaakhann/PakWheels-ETL-Pipeline)** | Kafka, Spark, Airflow, Docker, streaming ETL |
| 🤖 Machine Learning | **[ChurnSense](https://github.com/hooriaakhann/ChurnSense)** | PySpark ML, feature engineering, classification |
| 📊 Data Analytics | **[Revenue & Profit Tracker](https://github.com/hooriaakhann/Revenue-Profit-Tracker)** | Power BI, DAX, KPI and profit analysis |

---

<div align="center">

### Building systems that see, process, and explain data.

`Perception` · `Computer Vision` · `Machine Learning` · `Data Engineering` · `Data Analytics`

</div>
