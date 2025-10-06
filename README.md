
# 🏷️ Nike Sales Intelligence Dashboard: Azure Edition

[![Python](https://img.shields.io/badge/python-3.11-blue.svg)](https://www.python.org/)
[![Azure](https://img.shields.io/badge/azure-cloud-blueviolet.svg)](https://azure.microsoft.com/)
[![Power BI](https://img.shields.io/badge/power--bi-report-yellowgreen.svg)](https://powerbi.microsoft.com/)
[![License](https://img.shields.io/badge/license-MIT-lightgrey.svg)](LICENSE)

## 📊 From Raw Data to Smart Decisions

---

### 🔍 Overview

This project transforms messy, real-world Nike retail sales data into actionable business insights using **Azure cloud services**. It demonstrates how Nike’s Supply Chain Intelligence team can leverage cloud-scale analytics to optimize product flow, balance speed and cost, and improve profitability.

---

### 🎯 Goals
- Build a **clean, reliable data pipeline** using Azure.
- Perform **exploratory and predictive analysis** on sales data.
- Deliver **interactive Power BI dashboards** for decision-makers.
- Explore **ML models** for profit prediction and sales segmentation.

---

### 🧱 Architecture
**Azure Services Used:**
- **Azure Data Factory** – Data ingestion
- **Azure Data Lake Storage Gen2** – Raw and cleaned data storage
- **Azure Databricks** – Data cleaning, EDA, ML modeling
- **Azure SQL / Synapse Analytics** – Structured querying
- **Azure Machine Learning** – Optional ML deployment
- **Power BI** – Visualization
- **GitHub** – Version control and collaboration

---

### 📁 Repository Structure

```
nike-sales-intelligence-azure/
├── README.md
├── LICENSE
├── .gitignore
├── requirements.txt
├── azure-pipeline.yml
│
├── data/
│   ├── raw/
│   ├── cleaned/
│   └── sample/
│
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_eda.ipynb
│   ├── 03_ml_profit_prediction.ipynb
│   ├── 04_ml_segmentation.ipynb
│   ├── 05_anomaly_detection.ipynb
│   └── 06_forecasting.ipynb
│
├── scripts/
│   ├── ingest_data.py
│   ├── clean_data.py
│   ├── ml_models.py
│   └── utils.py
│
├── dashboard/
│   ├── dashboard.pbix
│   ├── screenshots/
│   └── dashboard_notes.md
│
├── docs/
│   ├── architecture.md
│   ├── insights_report.md
│   ├── timeline.md
│   └── demo_script.md
│
└── azure/
    ├── setup_instructions.md
    ├── bicep_templates/
    └── terraform/
```

---

### 📌 Key Features
- **Cloud-scale data pipeline** from ingestion to visualization
- **ML models** for profit prediction and segmentation
- **Interactive dashboards** with filters and KPIs
- **Real-time updates** via Azure SQL/Synapse integration

---

### 🏃 Running Notebooks Locally

1. **Clone the repository:**
```bash
git clone https://github.com/yourusername/nike-sales-intelligence-azure.git
cd nike-sales-intelligence-azure
```

2. **Create a virtual environment:**
```bash
python -m venv venv
source venv/bin/activate      # Linux/Mac
venv\Scripts\activate         # Windows
```

3. **Install dependencies:**
```bash
pip install -r requirements.txt
```

4. **Launch Jupyter Notebook:**
```bash
jupyter notebook
```

5. Open the notebooks in the `notebooks/` folder and run cells sequentially.

> ⚠️ **Note:** Some notebooks require access to Azure services (Data Lake, Databricks, SQL). You can mock data in `data/sample/` for local testing.

---

### 📅 Timeline
| Week | Activities |
|------|------------|
| 1    | Load raw dataset to Azure, assess quality, define cleaning strategy |
| 2    | Perform full cleaning in Databricks; document results |
| 3    | Conduct EDA and implement ML models |
| 4    | Build Power BI dashboard; connect to Azure SQL/Synapse |
| 5    | Final report, GitHub publishing, demo video |

---

### 📈 Expected Outcomes
- Insights on top products, regions, and discount strategies
- ML-driven profit predictions and segmentation
- Strategic recommendations for Nike’s sales and supply chain teams
