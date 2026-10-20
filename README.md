<h1 align="left">Hi, I'm Vishal Sugur 👋</h1>

<p align="left">
Data Analyst turned Data Scientist — M.Sc. Data Science student at Fulda University of Applied Sciences, Germany.
9+ months of industry experience across two analytics internships. I build end-to-end data products — pipelines,
BI dashboards and ML models — that are validated, documented and honest about their limits.
Published researcher in AI-based image classification.
</p>

---

### 🔭 What I'm working on
- ⚙️ **Trustworthy AI for manufacturing** — an ML system for **JUMO GmbH & Co. KG** predicting sensor correction values on real production data (38K+ substrates, 324 features), applying the **VDE SPEC 90012** Trustworthy AI framework
- 📊 **BI migration with proof** — moving reporting from Tableau to self-hosted Apache Superset while automatically proving both dashboards show the same numbers
- 🤖 **LLM automation** — structured, human-in-the-loop workflows on the Claude API
- ⚖️ GDPR and the legal/ethical side of AI systems

---

### 📌 Featured Projects

**[ParityBI — Validated Tableau-to-Superset Migration](https://github.com/Vishalsugur/ParityBI-Validated-Tableau-to-Superset-Migration)**
End-to-end BI pipeline on real ServiceNow incident data (141K updates, 24.9K incidents). An Airflow DAG loads a PostgreSQL star schema, runs 17 data-quality checks, and serves the same KPIs to a legacy Tableau dashboard and a new Superset one — with **152 automated KPI parity checks per run**, 31 tests and CI. Fully documented for technical and business readers.
`Airflow` `PostgreSQL` `Superset` `Tableau` `Docker` `GitHub Actions`

**[Olist E-commerce KPI Dashboard + Late-Delivery Prediction](https://github.com/Vishalsugur/olist-kpi-project)**
Python ETL into a star schema, a 2-page Power BI dashboard and SQL KPIs on 99K real marketplace orders. Found that a late delivery makes a 1–2 star review **6.7× more likely**, and built a model that flags the 10% of orders containing **35% of all late deliveries** at checkout.
`Python` `Power BI` `DAX` `SQL` `DuckDB` `scikit-learn`

**[JUMO Laser Trimming — Trustworthy AI System](https://github.com/Vishalsugur/JUMO-Laser-Trimming-Trustworthy-AI-System)**
Production-grade ML system predicting the Nominal Correction Value for platinum thin-film temperature sensors on real manufacturing data from JUMO GmbH & Co. KG. Ridge Regression + Random Forest forward model achieving **99.5% tolerance-class yield**, with VDE SPEC 90012 (VCIO) assessment, fairness analysis and human-in-the-loop override logging.
`Python` `scikit-learn` `MLflow` `DVC` `PostgreSQL` `Power BI`

**[Parcel Exception Triage](https://github.com/Vishalsugur/parcel-exception-triage)**
LLM automation that classifies English and German parcel-delivery exception messages, extracts tracking/order IDs, drafts replies and escalates urgent cases to a human. Claude tool-use guarantees structured output; a keyword baseline runs at no cost. **94% category accuracy** on a synthetic evaluation set, served via FastAPI.
`Python` `Claude API` `FastAPI` `pytest`

**[Credit Default Prediction](https://github.com/Vishalsugur/credit-default-prediction)**
Compared 4 ML models on 30,000 Taiwanese credit card clients. XGBoost reached 82.9% accuracy / 0.83 AUC and cut false negatives by 16% vs. baseline using `scale_pos_weight` for class imbalance.
`Python` `XGBoost` `Random Forest` `SVM`

<details>
<summary><b>More projects</b></summary>
<br>

- **[Telco Customer Churn Dashboard](https://github.com/Vishalsugur/telco-customer-churn-dashboard)** — interactive R Shiny dashboard on churn drivers with dynamic filtering and Plotly charts. [Live demo →](https://76fyv9-sakshi-bhor.shinyapps.io/project/)
- **[Hospital Readmission ML — Literature Review](https://github.com/Vishalsugur/hospital-readmission-ml-literature-review)** — AI-assisted review of 8 PubMed studies (EndNote + Claude), with every AI extraction checked against the source and errors documented.
- **[ERA5 Climate Data Visualization](https://github.com/Vishalsugur/era5-data-visualization-)** — gridded reanalysis data with xarray: interpolation methods, scatterplot matrices, brushing & linking.
- **[AI Ethics & Legal Case Studies](https://github.com/Vishalsugur/ai-ethics-case-studies)** — analyses of real-world AI deployments, covering GDPR and automated decision-making rights.

</details>

---

### 🛠️ Tech Stack

**Languages & Querying**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat&logo=r&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat&logo=c&logoColor=white)

**Machine Learning & AI**

![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-red?style=flat)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat&logo=mlflow&logoColor=white)
![DVC](https://img.shields.io/badge/DVC-13ADC7?style=flat&logo=dvc&logoColor=white)
![Claude API](https://img.shields.io/badge/Claude_API-D97757?style=flat&logo=anthropic&logoColor=white)

**Data Engineering**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Apache Airflow](https://img.shields.io/badge/Apache_Airflow-017CEE?style=flat&logo=apacheairflow&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat&logo=duckdb&logoColor=black)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![Hadoop](https://img.shields.io/badge/Hadoop-66CCFF?style=flat&logo=apachehadoop&logoColor=black)

**BI & Visualization**

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat&logo=tableau&logoColor=white)
![Apache Superset](https://img.shields.io/badge/Apache_Superset-20A6C9?style=flat&logo=apachesuperset&logoColor=white)
![R Shiny](https://img.shields.io/badge/R_Shiny-276DC3?style=flat&logo=r&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat&logo=microsoft-excel&logoColor=white)

**Engineering & Cloud**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white)

---

### 📄 Publication
**Skin Disease Detection and Remedial System** — *International Journal of Innovative Science and Research Technology*, Vol. 9, Issue 5, May 2024. Peer-reviewed publication on AI/ML-based dermatological image classification.

---

### 🏆 Certifications & Achievements
- AWS Data Analytics — Amazon Web Services
- Machine Learning Specialization — Coursera (Andrew Ng)
- Python Problem Solving — HackerRank (Gold Badge)
- TCS CodeVita Season 11 — Top 5% nationally
- Wells Fargo Hackathon @ IIT Madras | Defense Innovation Hackathon

---

### 📫 Connect with me
- 📧 [vishalsugur22@gmail.com](mailto:vishalsugur22@gmail.com)
- 💼 [LinkedIn](https://linkedin.com/in/vishal-sugur-10846b24a)
- 📍 Fulda, Germany
