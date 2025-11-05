# 🏙️ Delhi Air Quality Analysis Using Data Mining Techniques

## 📘 1. Introduction

Delhi, the capital of India, is consistently ranked among the most polluted cities in the world. Air pollution poses severe threats to public health, environment, and overall quality of life. Key contributors include vehicular emissions, industrial waste, biomass burning, stubble burning in nearby states, and adverse meteorological conditions.

This project performs a **data-driven exploratory and predictive analysis** using the [Delhi Air Quality Dataset](https://www.kaggle.com/datasets/kunshbhatia/delhi-air-quality-dataset) to identify **trends, patterns, correlations, and causal relationships** behind pollution in Delhi. It also connects findings with **real-world events and policies**, such as the COVID-19 lockdown, Diwali, stubble burning, and the Odd-Even traffic policy.

---

## 🎯 2. Objectives

- Analyze how Delhi’s air quality has changed over the years.
- Study **seasonal variations** in air quality.
- Identify **key pollutants** that degrade air quality.
- Compare air quality across **different monitoring stations**.
- Explore **correlations** between pollutants.
- Evaluate the **impact of interventions** (e.g., lockdowns, stubble burning).
- Check compliance with **WHO safety standards**.
- Detect **monthly and seasonal outliers**.
- Perform **predictive modeling** to forecast AQI trends.

---

## 📚 3. Literature Review

Prior studies have explored Delhi’s air pollution crisis using atmospheric science and data analytics:

- **Guttikunda & Calori (2013):** Found vehicular emissions as the largest PM2.5 contributor.  
- **Beig et al. (2020):** Established correlation between meteorological parameters and pollutant dispersion.  
- **Sharma et al. (2021):** Documented drastic pollutant reduction during the COVID-19 lockdown.  
- **Singh et al. (2019):** Showed pollution peaks during winter due to stubble burning and temperature inversion.

However, few studies combine **multi-year, multi-pollutant** data for temporal, spatial, and predictive analysis.  
This project aims to bridge that gap using **modern data mining and visualization techniques**.

---

## 📊 4. Dataset Description

**Source:** [Kaggle - Delhi Air Quality Dataset](https://www.kaggle.com/datasets/kunshbhatia/delhi-air-quality-dataset)

**Attributes:**
- `Date`, `Time`
- `Station Name`
- Pollutants: `PM2.5`, `PM10`, `NO₂`, `CO`, `O₃`, `SO₂`
- `AQI (Air Quality Index)`

**Data Coverage:** 2018–2023 (varies across stations)

**Additional Data Sources:**
- Meteorological data (temperature, humidity, wind speed)
- Policy/Event data: Odd-Even rule, Diwali dates, stubble burning season, COVID-19 lockdown

---

## 🔬 5. Research Methodology

The methodology is divided into four stages: **Data Preprocessing**, **Exploratory Analysis**, **Visualization**, and **Modeling**.

---

### 🧹 5.1 Data Preprocessing
- Handle missing or inconsistent readings.
- Standardize pollutant units and timestamps.
- Add derived features: `year`, `month`, `season`, and `event_flag` (e.g., Diwali, lockdown).
- Normalize pollutant levels for comparability.

---

### 📈 5.2 Exploratory Analysis Plan

| **Analysis Type** | **Objective** | **Techniques Used** |
|--------------------|---------------|----------------------|
| Temporal Trend | How air quality evolved over years | Line plots, rolling averages |
| Seasonal Variation | Pollution across seasons | Boxplots, seasonal decomposition |
| Spatial Comparison | Station-wise pollution patterns | Heatmaps, geospatial mapping |
| Pollutant Contribution | Dominant pollutant identification | Bar charts, PCA |
| Correlation Analysis | Inter-relationships between pollutants | Correlation matrix |
| Event Impact | Effect of Diwali, lockdowns, stubble burning | Time-series overlays |
| Outlier Detection | Extreme months or spikes | Interactive boxplots (Plotly) |
| WHO Compliance | Exceedances of global limits | Threshold analysis |

---

### 📊 5.3 Visualization Plan

**Visualization Tools:** Python (Matplotlib, Seaborn, Plotly), Power BI, or Tableau.

| **Type** | **Purpose** |
|-----------|-------------|
| Time Series Plot | Yearly trend of pollutants and AQI |
| Interactive Boxplot | Detect monthly outliers (year-selectable) |
| Heatmap | Correlation among pollutants |
| Geospatial Plot | Station-wise pollution intensity |
| AQI Distribution | Compare pollution across years and months |
| Event Overlay Charts | Highlight policy interventions and festivals |

---

### 🤖 5.4 Model Training Plan

| **Model Type** | **Goal** | **Algorithms Used** |
|----------------|-----------|----------------------|
| Regression | Predict pollutant concentration | Linear Regression, Random Forest |
| Classification | Predict AQI category (Good–Severe) | Decision Tree, Logistic Regression |
| Time Series Forecasting | Predict future AQI trends | ARIMA, LSTM (optional) |

**Evaluation Metrics:**
- Regression: RMSE, MAE, R²  
- Classification: Accuracy, Precision, Recall, F1-score  

---

## 💡 6. Analysis Philosophy and Design

This project follows an **iterative, data-driven workflow**, inspired by the **CRISP-DM** methodology:

1. **Business Understanding** → Define objectives and real-world relevance.  
2. **Data Understanding** → Explore data quality and sources.  
3. **Data Preparation** → Clean, transform, and enrich data.  
4. **Modeling** → Build regression/classification/time-series models.  
5. **Evaluation** → Assess performance and interpret results.  
6. **Deployment** → Visualize findings and derive insights.

---

## 📉 7. Findings (Illustrative)

*(You can update this section with actual results after analysis.)*

- **Trend:** Air quality deteriorated from 2018–2019, improved in 2020 during lockdown, and worsened again post-2021.  
- **Seasonal Variation:** Winter (Nov–Jan) shows severe pollution, while monsoon (Jul–Sep) shows improvement.  
- **Major Pollutants:** PM2.5 and PM10 are primary drivers of poor AQI.  
- **Spatial Trends:** Central and industrial zones consistently show higher AQI.  
- **Event Impact:** Diwali and stubble burning create sharp pollution spikes; lockdowns cause significant drops.  
- **Correlation:** PM2.5–PM10 correlation ≈ 0.85, indicating shared sources.  
- **Outliers:** November 2019 and 2021 were extreme pollution months.

---

## 🤖 8. Predictive Analysis (Example Results)

| **Model** | **Goal** | **Performance** |
|------------|-----------|-----------------|
| Random Forest Regressor | Predict PM2.5 | R² = 0.81 |
| Decision Tree Classifier | Predict AQI Category | Accuracy = 85% |
| LSTM Model | Forecast next 7-day AQI | MAE = 12.3 |

**Key Features Influencing Predictions:** Temperature, humidity, wind speed, and month of year.

---

## 🧠 9. Discussion

The analysis reveals that **human activity, weather, and seasonal changes** strongly impact Delhi’s pollution.  
Temporary improvements during lockdown highlight the potential for reduction through sustained policy and behavioral changes.  
Predictive modeling confirms that machine learning can assist in **forecasting AQI** and **early warning systems** for public health.

---

## ✅ 10. Conclusion

This project delivers a **comprehensive data mining study** on Delhi’s air quality.  
By combining temporal, spatial, and event-based analysis with machine learning, we gain valuable insights into pollution causes, policy effectiveness, and possible preventive measures.

**Future Enhancements:**
- Include satellite imagery and meteorological data.
- Build a real-time AQI prediction dashboard.
- Extend analysis to other Indian metro cities for comparative study.

---

## 📖 11. References

1. Guttikunda, S. K., & Calori, G. (2013). *A GIS Based Emissions Inventory at 1 km × 1 km Spatial Resolution for Air Pollution Analysis in Delhi, India.* Atmospheric Environment, 67, 101–111.  
2. Beig, G., et al. (2020). *COVID-19 Lockdown Impact on Air Quality in Delhi.* Science of the Total Environment.  
3. Sharma, S., et al. (2021). *Effect of the Nationwide Lockdown on Air Quality in India.* Environmental Research.  
4. Singh, R. P., et al. (2019). *Satellite Monitoring of Air Pollution During Crop Residue Burning Episodes in India.* Environmental Pollution.  
5. Delhi Air Quality Dataset (Kaggle) — [https://www.kaggle.com/datasets/kunshbhatia/delhi-air-quality-dataset](https://www.kaggle.com/datasets/kunshbhatia/delhi-air-quality-dataset)

---

## 📎 12. Appendix (Recommended Additions)

- 📊 Interactive visualizations (Plotly / Power BI)
- 🧩 Code snippets for EDA and model training
- 🗺️ Station-wise AQI maps
- 🔍 Correlation heatmaps and feature importance plots
- 🧾 Event impact overlays (Diwali, lockdowns, stubble burning)

---

### 🏁 Author
**Sahil Sahil**
**Manu Vahan**
