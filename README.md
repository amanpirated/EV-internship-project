⚡ Electric Vehicle Performance Prediction using Machine Learning

This project uses Machine Learning to analyze and predict battery health and charging cost of Electric Vehicles (EVs) based on parameters like battery capacity, charge cycles, average temperature, and usage data.
It’s designed as an internship project under the theme of Electric Vehicles and AI.

🚀 Project Overview

Electric vehicles are transforming modern transportation — but understanding how battery performance and charging cost vary under different conditions remains crucial.

This project builds a Multi-Output Regression Model that predicts:

🔋 Battery Health (%)

💰 Monthly Charging Cost (USD)

from real-world EV usage data.

🧠 Key Objectives

Predict EV battery health using performance and environmental data.

Estimate monthly charging costs based on energy usage.

Provide insights into factors affecting EV efficiency and cost.

Serve as a base for a Generative AI-powered EV assistant chatbot.

📂 Dataset

File: electric_vehicle_analytics.csv
The dataset includes:

Feature	Description
Make	EV manufacturer
Model	Vehicle model name
Battery_Capacity_kWh	Total battery capacity
Charge_Cycles	Number of full charging cycles completed
Avg_Temperature_C	Average operating temperature
Monthly_KM	Monthly distance driven
Battery_Health_%	Current battery condition
Monthly_Charging_Cost_USD	Monthly electricity cost for charging

(You can upload your dataset to the repository or link it if hosted elsewhere.)

🧩 Model Architecture

The model uses:

Supervised Learning (Regression)

Multi-Output Regression for predicting multiple targets

XGBoost Regressor wrapped in MultiOutputRegressor

Pipeline combining preprocessing + model training

⚙️ Tech Stack
Component	Library
Data Handling	pandas, numpy
ML Model	scikit-learn, xgboost
Visualization	matplotlib, seaborn
Model Persistence	pickle
