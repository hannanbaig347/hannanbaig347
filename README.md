<h1 align="center"> Hannan Baig </h1>
<h3 align="center"> Data Analyst | Business Intelligence </h3>

<p align="center">
  <a href="https://www.linkedin.com/in/hannan-baig/">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat-square&logo=linkedin" alt="LinkedIn">
  </a>
  <a href="mailto:muhammadhannanbaig@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email">
  </a>
</p>

---

I am a data analyst with experience in managing high-volume, regulation-sensitive administrative datasets within the public sector. I bridge the gap between messy operational realities and strategic decision-making. 

I specialize in converting fragmented datasets into **auditable, decision-ready systems** using Power BI, Python, SQL, and Excel.

Rather than building dashboards for reporting, I build systems that answer:

> *What is happening, why it is happening, and what should be done next?*

---

## Featured Projects

### [1. Border Wait Time Analytics: A Real-Time Automated Data Platform for U.S. Land Ports](https://github.com/hannanbaig347/border-wait-time-analytics-fabric-powerbi)

**Domain:** Transportation Analytics | Data Engineering | Predictive Analytics

**Stack:** Microsoft Fabric, PySpark, Delta Lake, Power BI, DAX, Python, Scikit-learn, MLflow

This end-to-end Microsoft Fabric data pipeline ingests live U.S. Customs and Border Protection data, processes it via a PySpark Medallion architecture to forecast wait times using machine learning, and powers a Direct Lake Power BI model to help decision-makers monitor congestion and operational trends.

**What I built**:

- Built an end-to-end Microsoft Fabric data platform ingesting live CBP border wait time data through automated pipelines
- Implemented a Bronze–Silver–Gold Medallion architecture and designed a star schema for Direct Lake analytics
- Developed a Random Forest forecasting model using historical traffic patterns to predict future border wait times
- Created an interactive Power BI solution for monitoring congestion, lane performance, and port-level operations

**Key Outcomes**:

- Automated processing of live hourly border telemetry into decision-ready analytical datasets
- Built a scalable Lakehouse with four dimension tables and three fact tables for operational reporting
- Achieved R² = 0.795 with a 40.8% reduction in MAE compared to a baseline forecasting approach
- Delivered executive dashboards enabling real-time monitoring of congestion and operational bottlenecks

Focus: Microsoft Fabric, Lakehouse Architecture, Business Intelligence, Predictive Analytics

### [2. Provincial Enforcement Command Center](https://github.com/hannanbaig347/provincial-enforcement-command-center-powerbi)
**Domain:** Government Operations | Fraud Detection | Revenue Leakage  
**Stack:** Python (Selenium, Pandas, SciPy), SQL, Power BI, DAX  

A full-scale analytics system designed to audit Pakistan’s price enforcement infrastructure using real scraped data and simulated inspection telemetry.

**What I built**
- End-to-end data pipeline (web scraping → cleaning → warehouse → dashboard)
- Reconstructed corrupted government datasets using Python engineering logic
- Built a SQLite star-schema data warehouse for auditability
- Designed statistical fraud detection system using:
  - Z-score anomaly detection  
  - Moving average price deviation analysis  
  - Behavioral profiling of enforcement officers  

**Key Outcomes**
- Identified simulated **Rs. 4.7M revenue leakage**
- Detected high-risk enforcement behavior patterns across 145 officers
- Flagged systemic hoarding patterns across commodity markets
- Delivered an executive Power BI monitoring dashboard with drill-down analysis

**Focus:** Fraud detection systems, public sector analytics, statistical auditing



### [3. Pakistan Large Scale Manufacturing Industrial Dashboard](https://github.com/hannanbaig347/pakistan-large-scale-manufacturing-powerBI-dashboard)

**Domain:** Economic Policy | Industrial Intelligence  
**Stack:** Power BI, DAX, Power Query, Excel  

A policy intelligence dashboard analyzing Pakistan’s industrial sector across 31 manufacturing industries using official government data.

**What I built**
- Weighted economic impact model to correct misleading growth signals
- Star-schema data model for scalable analysis
- DAX-based contribution metrics to identify real economic drivers
- Executive-level dashboard for policy interpretation

**Key Outcomes**
- Revealed **K-shaped industrial recovery pattern**
- Identified structural decline in industrial inputs despite headline growth
- Exposed dominance of automobile sector in GDP narrative distortion
- Enabled sector-level policy prioritization instead of aggregate reporting

**Focus:** Economic modeling, policy analytics, weighted KPI systems


### [4. Multi-Client Operations Intelligence System](https://github.com/hannanbaig347/multi-client-operations-excel-intelligence-system)

**Domain:** Business Intelligence, Operations Analytics & Executive Reporting  
**Stack:** Excel, Power Query, Power Pivot, DAX, VBA

Built an end-to-end Excel-based BI system that unified operational data from three client products into a single reporting layer, enabling cross-client performance monitoring, risk detection, and automated executive reporting without requiring a dedicated data warehouse or BI platform.

**What I Built:**
- Designed ETL pipelines in Power Query to clean and standardize multi-source operational data
- Developed a Power Pivot star schema connecting garage, rental, and app adoption datasets
- Created DAX measures to identify profitability, operational risk, and user retention patterns
- Automated dashboard refresh and PDF report generation using VBA


**Key Outcomes:**
- Unified 27,000+ records from three independent business systems
- Identified high-risk rental properties with combined financial and operational issues
- Exposed loss-making service categories and mechanic performance gaps
- Enabled one-click generation of executive-ready PDF report

**Focus:** ETL, Data Modeling, Excel BI, Operational Analytics, Reporting Automation.


### [5. Aviation Operations BI System](https://github.com/hannanbaig347/aviation-operations-BIsystem-oracle)

**Domain:** Aviation Operations, Business Intelligence, Operational Analytics

**Stack:** Oracle Analytics Desktop, Excel, Power Query, Python, K-Means Clustering 

Built an aviation analytics platform on 3 million U.S. flight records to monitor operational performance, identify disruption patterns, and uncover the root causes of delays using business intelligence and unsupervised machine learning.

**What I Built:**
- Cleaned and prepared 3M flight records using Excel, Power Query, and Oracle Analytics Desktop
- Developed a three-layer BI solution covering executive KPIs, operational diagnostics, and trend monitoring
- Built a K-Means++ clustering pipeline to segment flights into distinct operational performance groups
- Created interactive dashboards with geospatial analysis, drill-down capabilities, and anomaly visualization


**Key Outcomes:**
- Identified that 74.39% of delay minutes originated from controllable airline operations
- Segmented 395,239 flights into four operational archetypes, including a high-risk disruption cluster
- Revealed hub dependency risks across major airports such as ATL, DFW, and ORD
- Highlighted 71 million minutes of ground movement as a significant operational inefficiency

**Focus:** Business Intelligence, Operational Analytics, Machine Learning, Root Cause Analysis, Data Visualization.

### 6. MS Thesis — Geospatial Air Quality Estimation
**Domain:** Geospatial Analytics, Environmental Data Engineering  
**Stack:** Python (Pandas, NumPy, Rasterio, Scikit-Learn, Matplotlib), Sentinel-2 Satellites, ERA5 Reanalysis 

Ground sensors for air quality monitoring cost hundreds of thousands of dollars and Pakistan has almost none outside major cities. This thesis asked whether a deep learning model trained on Lahore's data could estimate NO₂ pollution in Quettam a city with zero ground sensors, using only satellite imagery and weather data.

Naive transfer failed catastrophically (R² as low as -17.85). I implemented Domain Adversarial Neural Networks (DANN) to force the model to learn city-invariant features, then built a diagnostic pipeline to correct for spatial translation gaps and magnitude bias inherited from Lahore's higher pollution levels.

Final validated results without using a single Quetta ground-truth training point:
- Best single-day spatial R²: **0.659** 

- Outperforms the base paper's reported R² of 0.54

**Focus**: Geospatial ML, environmental intelligence, remote sensing analytics

---

## Other Projects

| Project | What It Does | Core Methods |
|---|---|---|
| [Retail Sales Forecasting](https://github.com/hannanbaig347/Forecasting-for-a-Retail-Store) | 6-month demand forecast with 95% confidence intervals for inventory planning | SARIMAX, Prophet, ARIMA comparison |
| [Customer Sentiment Analysis](https://github.com/hannanbaig347/Customer_Review_Sentiment_Analysis_VADER_TextBlob_LogRegression) | Classifies 1,000 reviews and identifies root causes of dissatisfaction by product | Logistic Regression (93.5% accuracy), VADER, TextBlob, LDA topic modeling |
| [Customer Segmentation](https://github.com/hannanbaig347/customer-value-maximization-pipeline-with-segmentation) | RFM-based behavioral clustering for retention and upsell targeting | K-Means, Hierarchical, DBSCAN |
| [A/B Test Analysis](https://github.com/hannanbaig347/from-data-to-revenue-leveraging-AB-testing-to-enhance-conversion-and-engagement) | Measures conversion lift from a redesigned feature with statistical rigor | Z-test, T-test, power analysis, segment analysis |

---

## Let's Connect

I am actively seeking Data Analyst and Business Intelligence roles where I can take ownership of messy data and build the systems that drive confident, profitable decisions.

* **Email:** [muhammadhannanbaig@gmail.com](mailto:muhammadhannanbaig@gmail.com)
* **LinkedIn:** [Hannan Baig](https://www.linkedin.com/in/hannanbaig)


