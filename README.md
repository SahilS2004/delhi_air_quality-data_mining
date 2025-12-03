# Project 3: Delhi Air Quality & Pollution Trends

# Course: Data Mining (Semester 5, 2025)
Team Name: DataFlix
Members:
- Manu Vahan 
- Sahil Sarawgi
- Mentor: Sanchit Aggarwal

---

# 🔍 Problem Statement
Delhi consistently ranks among the world’s most polluted cities. Using the "Delhi Air Quality Dataset" (Kaggle), we analyze how air quality varies over time, across seasons, and among pollutants. We also study the impact of policy interventions (odd–even rule, lockdowns, stubble burning) on pollution trends.

Dataset: [Delhi Air Quality Dataset](https://www.kaggle.com/datasets/kunshbhatia/delhi-air-quality-dataset)

---

# 🎯 Research Objectives
1. Analyze long-term air quality trends in Delhi.  
2. Identify seasonal pollution spikes and their causes.  
3. Compare pollutant contributions (PM2.5, PM10, NO₂, SO₂, CO, O₃).  
4. Examine correlation among pollutants and station-wise variations.  
5. Evaluate impacts of major interventions (lockdown, Diwali, stubble burning, odd–even).  
6. Detect outlier months using interactive visualizations.  
7. Quantify how often pollutant levels exceed WHO limits.

---

# 🧩 Tools & Libraries
- Python 3.10  
- pandas, numpy, matplotlib, seaborn, plotly  
- scikit-learn (for later predictive phase)  
- Jupyter Notebook  
- GitHub for version control  

---

# 🧪 Methodology Overview
## Phase 1: Understanding + EDA (Completed)
1. Data Collection → Kaggle dataset import.  
2. Data Cleaning & Preprocessing (notebook: `data-preprocessing.ipynb`)
   - Handle missing, duplicate, invalid entries.  
   - Standardize timestamps, numeric types, units.  
   - Add `year`, `month`, `season` columns.  
3. Exploratory Data Analysis (EDA) (notebook: `EDA and Feature Expansion.ipynb`)
   - Time-series trends.  
   - Monthly/seasonal boxplots.  
   - Correlation heatmaps.  
   - Station comparisons.  
   - Outlier detection and interactive visualizations.  
4. Feature Engineering & Expansion
   - Additional derived features for analysis.  
5. Model Training
   - Initial predictive models for air quality forecasting.  
6. Documentation 
   - Insights, methods, and role division.

---

# 📆 Phase-wise Plan
| Phase | Focus | Deliverables | Lead | Status |
|-------|--------|--------------|------|--------|
| 1 | Understanding + EDA | Cleaned data, notebook, visuals, report | Manu | ✅ Completed |
| 2 | Predictive + Policy Impact | Forecasting, intervention analysis, final report | Sahil Sarawgi | ✅ Completed |

Project completed successfully with all phases delivered.

---

# 📊 Expected Outcomes
- Clear understanding of pollution patterns. 
- Identification of major contributors & event impacts. 
- Foundation for predictive analysis (Phase 2).
- Feature engineering and expansion for enhanced analysis.
- Visualizations and model training.

---
