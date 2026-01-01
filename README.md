# 📊 Facebook Ad Performance Analytics

## 📖 Overview

This project is a data analytics solution for social media ad campaign performance. In this projects we work on Facebook Ad campaign while using Python for data pre Processing and PowerBi for visualizations

## 🛠️ Tech Stack & Workflow

### Data Processing (Python/Pandas):
* **Data Import:** Ingests raw campaign data (`KAG_conversion_data.csv`).
* **Data Cleaning:** Standardizes column names and parses demographic data (e.g., converting "30-34" age ranges into numerical averages for analysis).
* **KPI Engineering:** Calculates critical marketing metrics including:
    * **CTR (Click-Through Rate):** Measuring ad engagement.
    * **CPC (Cost Per Click) & CPM (Cost Per Mille):** Analyzing cost efficiency.
    * **ROI (Return on Investment):** Determining profitability per ad.
    * **CPA (Cost Per Acquisition):** Tracking the cost to acquire a paying customer.

### Reporting:
* **Excel Export:** Generates a final processed dataset (`facebook_ads_processed.xlsx`) ready for dashboarding in Power BI or Tableau.

## 📂 Project Structure
```
├── KAG_conversion_data.csv      # Raw dataset from Kaggle
├── main.ipynb                   # Jupyter Notebook for EDA, cleaning, and KPI calculation
├── facebook_ads_processed.xlsx  # Final processed output file with calculated KPIs
└── README.md                    # Project documentation
```
## 🔗 Dataset

**Kaggle Link:** [Sales Conversion Optimization (KAG_conversion_data.csv)](https://www.kaggle.com/datasets/loveall/clicks-conversion-tracking)
