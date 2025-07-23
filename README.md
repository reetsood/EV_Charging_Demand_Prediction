# ⚡ Electric Vehicle Charging Demand Prediction

As electric vehicle (EV) adoption rapidly increases, city and state planners must anticipate the infrastructure needs of tomorrow. This project focuses on forecasting future EV adoption trends using historical registration data, with the ultimate goal of aiding urban planners in making data-driven decisions about EV charging infrastructure.

---

## 📌 Problem Statement

With the growth of electric vehicles, inadequate planning for charging infrastructure can cause congestion, long wait times, and ultimately hinder sustainability efforts. Using historical vehicle registration data provided by the Washington State Department of Licensing, this project builds a regression model to **forecast future EV adoption trends**, helping stakeholders prepare for increased charging demand.

---

## 🎯 Goal

Develop a **machine learning regression model** that predicts the **future number of registered electric vehicles** in Washington based on:

- Historical registration trends  
- Types of vehicles (BEVs, PHEVs)  
- Regional and county-level distribution  
- Overall EV growth patterns

---

## 📊 Dataset Overview

The dataset contains monthly records of vehicle registrations from **January 2017 to February 2024**, with the following key columns:

- **Date**: Last day of the month for each record  
- **County**: Geographic region within Washington State  
- **Battery Electric Vehicles (BEVs)**: Count of fully electric vehicles  
- **Plug-In Hybrid Electric Vehicles (PHEVs)**: Count of hybrid electric vehicles  
- **EV Total**: Sum of BEVs and PHEVs  
- **Non-Electric Vehicle Total**: Count of vehicles using non-electric propulsion  
- **Total Vehicles**: All registered vehicles  
- **Percent Electric Vehicles**: Ratio of EVs to total vehicles  

---

## 🧠 Approach

1. **Data Preprocessing**
   - Handling missing values and formatting
   - Aggregating and grouping data (by county/year)
   - Feature engineering (e.g., EV growth rate)

2. **Exploratory Data Analysis (EDA)**
   - Visualize adoption trends and growth patterns
   - Identify correlations and seasonal behavior

3. **Model Building**
   - Use regression models such as: 
     - Random Forest  
   - Evaluate using metrics: RMSE, MAE, R²

4. **Forecasting**
   - Predict EV counts for future months/years
   - Visualize demand growth and insights

---

## 🛠️ Tech Stack

- Python  
- Pandas, NumPy  
- Scikit-learn 
- Matplotlib, Seaborn  
- Jupyter Notebook

---

## 📈 Results

- Successfully forecasted future EV registration trends  
- Identified high-growth counties to prioritize infrastructure  
- Provided valuable data-driven recommendations for planning






