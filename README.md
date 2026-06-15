🌍 MINspire – Earthquake Magnitude Modeling (Nepal Seismicity Analysis 1990–2026)

A data-driven geoscience and machine learning project analyzing earthquake activity in Nepal and the Himalayan region using historical seismic records.

The project focuses on **exploratory data analysis (EDA), feature engineering, and regression-based modeling** to study patterns in earthquake magnitude.

🎯 Objective

This project aims to:

* Analyze long-term earthquake patterns in Nepal and surrounding regions
* Study relationships between magnitude, depth, and spatial distribution
* Explore statistical signals in seismic activity data
* Build regression models to understand and estimate earthquake magnitude trends


 📊 Dataset

* **Source:** Kaggle – Nepal Earthquake Seismicity Dataset (1990–2026)
* [https://www.kaggle.com/datasets/amansinghnp/nepal-earthquake-seismicity-dataset-1990-2026](https://www.kaggle.com/datasets/amansinghnp/nepal-earthquake-seismicity-dataset-1990-2026)
* **Region:** Nepal / Himalayan seismic belt
* **Time Period:** 1990 – 2026

 📌 Features include:

* Magnitude
* Depth
* Latitude & Longitude
* Number of stations 
* Sensor gap / recording quality 


## 📈 Exploratory Data Analysis (EDA)

### 🌐 Temporal Trends

* Highest seismic activity observed in **2015 (316 earthquakes)**
* Lowest recorded activity: **1992 (7 earthquakes)**
* Significant activity also observed in **2008 (158 earthquakes)**
* **2025 shows elevated activity (124 earthquakes)**
---

### 🌋 Magnitude Distribution

* Average magnitude: **~4.38**
* Most earthquakes lie in the **3.5 – 4.5 range**
* Only a small fraction exceed **magnitude ≥ 6**
* Maximum recorded magnitude: **7.8 (Gorkha earthquake, 2015)**

---

### 🌊 Depth Analysis

* Median depth: **~10 km (dominantly shallow earthquakes)**
* Around **58% of earthquakes occur at depth < 20 km**
* Very few deep events (>70 km)

---

### 🗺️ Spatial Distribution

* Latitude range: **~26°N – 31°N**
* Longitude range: **~80°E – 89°E**
* Earthquakes show clustering along the **Himalayan seismic belt**



## 🔗 Correlation Analysis

* Depth vs Magnitude: **weak negative correlation (~ -0.056)**
* Sensor-related variable (if used): strongest negative correlation (~ -0.571)
* Number of stations: moderate positive correlation (~ +0.521)


---

## ⚙️ Methodology

1. Data Collection (Kaggle dataset)
2. Data Cleaning & Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Model Training & Evaluation



## 🤖 Machine Learning Models

* Linear Regression
* Ridge Regression
* Lasso Regression



## 📉 Results & Interpretation

* Linear models capture **basic statistical trends in magnitude**
* Performance is limited due to:

  * High noise in seismic data
  * Weak feature–target relationships
  * Rare extreme earthquake events



## 🧠 Key Insights

* Earthquakes in Nepal are mostly **low to moderate magnitude**
* Shallow earthquakes dominate the dataset
* Spatial clustering aligns with Himalayan tectonic zones
* Magnitude is weakly correlated with simple physical features
* Data shows strong randomness and non-linear behavior



## 📁 Project Structure

```bash
MINspire-Earthquake-Modeling/
│
├── earthquake_analysis.ipynb   # Main notebook (EDA + modeling)
├── data/
│   └── nepal_earthquakes.csv  # Kaggle dataset
└── README.md
```



## 🛠️ Tools & Libraries

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn

---


## 🚀 Future Work

* Incorporate real-time seismic APIs (USGS / NSC streaming data)
* Apply advanced models (Random Forest, XGBoost, LSTM)
* Add spatial geostatistical modeling
* Improve feature engineering using tectonic data
* Expand dataset across full Himalayan region

---

## 👤 Author

* **Name:** Kawach Pokharel
* **Program:** MINspire Capstone Project
* **Team:** The detectors




---

If you reply with answers, I can upgrade this again into a **top 1% “MIT-level research README + LinkedIn post + paper abstract bundle”**.
