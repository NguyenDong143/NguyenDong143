<h1 align="center">Nguyễn Hoàng Đồng (Dong Nguyen Hoang)</h1>

<h3 align="center">Data Engineer · Financial Data Analyst · AI Researcher</h3>

<p align="center">
  <a href="mailto:donghoangnguyen214@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=flat-square&logo=gmail&logoColor=white"/></a>
  <a href="https://www.linkedin.com/in/dongnguyen143"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white"/></a>
  <a href="https://ieeexplore.ieee.org/document/11551622"><img src="https://img.shields.io/badge/IEEE_Paper-00629B?style=flat-square&logo=ieee&logoColor=white"/></a>
</p>

---

## About Me

Final-year Financial Technology student at **Posts and Telecommunications Institute of Technology (PTIT)**, specialising in Data Engineering, NLP, and AI-driven financial analytics.

I build production-grade data systems for financial intelligence — from Medallion data lakes and Airflow-orchestrated ETL pipelines to NLP-powered market surveillance platforms. My research on stock manipulation detection using PhoBERT and Granger Causality was accepted and presented at **IEEE DeFi 2025** as first author.

**Current focus:**
- 🏗️ Scalable financial data infrastructure (Medallion Architecture, Apache Airflow, Docker)
- 🤖 NLP for Vietnamese financial markets (PhoBERT, FinBERT, sentiment analytics)
- 📊 Credit scoring & alternative data analytics (WOE/IV, Logistic Regression)
- 📈 Quantitative market research (VAR/TVAR, Granger Causality, LSTM forecasting)

---

## Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)

**Data Engineering**

![Apache Airflow](https://img.shields.io/badge/Apache_Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MinIO](https://img.shields.io/badge/MinIO-C72E49?style=flat-square)

**ML & NLP**

![PhoBERT](https://img.shields.io/badge/PhoBERT-NLP-2ea44f?style=flat-square)
![FinBERT](https://img.shields.io/badge/FinBERT-NLP-0052cc?style=flat-square)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Stata](https://img.shields.io/badge/Stata-004B87?style=flat-square)

**Visualisation & APIs**

![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)

---

## Featured Projects

### 🇻🇳 Vietnam Fear & Greed Index (VN-FGI)
> Production-grade financial sentiment platform for the Vietnamese stock market

**Tech:** Apache Airflow · FastAPI · Docker · MinIO · Streamlit · PhoBERT · FinBERT

- Architected a **Medallion data lake** (Bronze/Silver/Gold) orchestrated with Airflow DAGs and containerised via Docker Compose
- Integrated 4 live data sources: VN-Index feeds, Vietnamese financial news, foreign capital flows, and social sentiment streams
- Applied **PhoBERT & FinBERT** to extract sentiment from 10K+ daily news articles, powering a composite Fear & Greed Index
- Deployed real-time analytics dashboard via FastAPI + Streamlit with sub-second index updates

🔗 [github.com/NguyenDong143/Stock-Sentiment-Econometric-Dashboard](https://github.com/NguyenDong143/Stock-Sentiment-Econometric-Dashboard)

---

### 📰 NLP-Driven Stock Manipulation Detection *(IEEE DeFi 2025)*
> AI-powered market surveillance — First Author, IEEE-Indexed Publication

**Tech:** PhoBERT · LSTM · VAR/TVAR · Granger Causality · SQL · Streamlit

- Designed an end-to-end surveillance pipeline integrating Vietnamese news sentiment with VN30 price/volume data
- Processed **500K+ structured and unstructured financial records**; applied Granger Causality to model sentiment-price lead-lag dynamics
- Achieved **~82% detection precision** on labeled manipulation events in backtesting
- Deployed real-time monitoring dashboard used by KTS Lab research team

📄 [IEEE Publication](https://ieeexplore.ieee.org/document/11551622) · 🔗 [github.com/NguyenDong143/V-NEST](https://github.com/NguyenDong143/V-NEST)

---

### 💳 Telecom Credit Scoring System
> Alternative-data credit scorecard using telecom behavioural data

**Tech:** Python · SQL · PostgreSQL · Logistic Regression · Power BI · Streamlit

- Built ETL pipelines integrating 300K+ customer behavioural and transactional records
- Applied **WOE/IV feature engineering** and Greedy Binning; reduced feature set by 40% while retaining 95%+ predictive signal
- Contributed to a **Gini coefficient improvement of ~8 points** through validated feature datasets
- Developed automated reporting and customer credit segmentation dashboards

---

### 📈 VN30 Sentiment-Driven Stock Forecasting
> LSTM forecasting framework enhanced with NLP-based sentiment signals

**Tech:** FinBERT · LSTM · SQL · Streamlit · REST API

- Aligned and processed **230K+ time-series and news records**; engineered sentiment features as lagged inputs to LSTM
- Achieved **~12% RMSE improvement** over baseline ARIMA on 5-day VN30 price forecasts
- Deployed interactive market dashboard with API-based data refresh and AI chatbot support

🔗 [github.com/NguyenDong143/VN30-Sentiment---Driven-Stock-Forecasting](https://github.com/NguyenDong143/VN30-Sentiment---Driven-Stock-Forecasting)

---

## Research & Achievements

| | |
|---|---|
| 🥇 | **First Author & Presenter** — IEEE DeFi 2025 (International FinTech Conference, IEEE-Indexed) |
| 🏅 | **Faculty Research Award ×2** — Excellence in Financial Data Analytics Research, PTIT (2024 & 2025) |
| 🎓 | **B.Sc. Financial Technology** — PTIT, Hanoi · GPA 3.2/4.0 · Expected July 2026 |
| 📜 | Python for Finance — Udemy · Investment Fundamentals & Data Analytics — 365 Data Science |

---

<p align="center"><i>"Turning financial data into digital intelligence."</i></p>
