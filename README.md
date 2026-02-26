# DataCo Smart Supply Chain Analysis

A comprehensive, multi-level data analytics project analyzing DataCo Global's supply chain operations. This project demonstrates progressive data analytics skills — from exploratory analysis to interactive dashboards to predictive machine learning models.

## 📊 Dataset

**Source:** [DataCo Smart Supply Chain for Big Data Analysis](https://www.kaggle.com/datasets/shashwatwork/dataco-smart-supply-chain-for-big-data-analysis)

The dataset contains **180,000+ order records** with **50+ features** from DataCo Global, covering:
- Customer orders across multiple countries
- Product categories (Clothing, Sports, Electronics)
- Shipping modes and delivery performance
- Financial data (sales, profit, discounts)
- Fraud indicators

---

## 🗂️ Project Structure

```
dataco-supply-chain-analysis/
│
├── README.md                          # Project overview (you are here)
├── requirements.txt                   # Python dependencies
├── .gitignore                         # Files to exclude from git
│
├── data/
│   ├── raw/                           # Original dataset (not tracked in git)
│   └── processed/                     # Cleaned & transformed data
│
├── notebooks/
│   ├── 01_eda_data_cleaning.ipynb     # Deliverable 1: EDA & Data Cleaning
│   ├── 02_sql_kpi_analysis.ipynb      # Deliverable 2: SQL & KPI Analysis
│   └── 03_predictive_modeling.ipynb   # Deliverable 3: ML & Fraud Detection
│
├── src/
│   ├── __init__.py
│   ├── data_cleaning.py               # Reusable cleaning functions
│   ├── feature_engineering.py         # Feature creation for ML models
│   └── visualization.py              # Custom plotting functions
│
├── sql/
│   └── supply_chain_queries.sql       # SQL queries for KPI extraction
│
├── dashboards/
│   └── app.py                         # Plotly Dash interactive dashboard
│
├── models/
│   └── (saved model files .pkl)       # Trained model artifacts
│
└── reports/
    └── figures/                       # Exported charts and visualizations
```

---

## 🚀 Deliverables

### Deliverable 1 — Beginner: Exploratory Data Analysis & Data Cleaning
**Notebook:** `notebooks/01_eda_data_cleaning.ipynb`

- Data import, profiling, and quality assessment
- Handling missing values, duplicates, and data type conversions
- Descriptive statistics across key supply chain metrics
- 10+ visualizations covering order trends, delivery performance, regional breakdowns, and profitability
- Key business findings summarized

**Skills:** Python, Pandas, Matplotlib, Seaborn, Data Wrangling

---

### Deliverable 2 — Intermediate: Supply Chain KPI Dashboard
**Notebook:** `notebooks/02_sql_kpi_analysis.ipynb` | **Dashboard:** `dashboards/app.py`

- SQL queries extracting core supply chain KPIs (on-time delivery rate, avg shipping delay, revenue by category, customer segmentation)
- Interactive Plotly Dash dashboard with filters for region, product category, and time period
- Written business recommendations backed by data

**Skills:** SQL, SQLite, Plotly Dash, KPI Development, Business Analysis

---

### Deliverable 3 — Expert: Predictive Modeling & Fraud Detection
**Notebook:** `notebooks/03_predictive_modeling.ipynb`

- **Late Delivery Prediction** — Classification model predicting delivery delays with feature importance analysis
- **Fraud Detection** — Identifying fraudulent orders with precision/recall optimization
- Model evaluation: confusion matrices, ROC curves, cross-validation
- Business impact assessment and recommendations

**Skills:** Scikit-learn, XGBoost, Machine Learning, Model Evaluation, Feature Engineering

---

## ⚙️ Setup & Installation

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/dataco-supply-chain-analysis.git
cd dataco-supply-chain-analysis

# Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Download the dataset from Kaggle and place in data/raw/
# https://www.kaggle.com/datasets/shashwatwork/dataco-smart-supply-chain-for-big-data-analysis
```

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python 3.10+ | Core language |
| Pandas / NumPy | Data manipulation |
| Matplotlib / Seaborn | Static visualizations |
| Plotly / Dash | Interactive dashboard |
| SQLite | SQL-based analysis |
| Scikit-learn | Machine learning |
| XGBoost | Gradient boosting models |
| Jupyter Notebook | Analysis environment |

---

## 👤 Author

**Samuel — Data Analyst**
- [LinkedIn](https://www.linkedin.com/in/samuel-manson-endeboh-7a66a4136/)
- [GitHub](https://github.com/abiyes-stack)

---

## 📜 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.
