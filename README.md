# 🚀 Falcon 9 Landing Prediction — Applied Data Science Capstone

## 📌 Project Overview

This project focuses on analyzing SpaceX Falcon 9 launch data to understand the key factors that influence first-stage landing success. Since the reusability of the Falcon 9 booster significantly reduces launch costs, predicting whether the first stage will successfully land can provide valuable insights into mission reliability and cost estimation.

Using real-world launch data collected from the SpaceX API and web sources, this project combines **data engineering, exploratory analysis, visualization, and machine learning** techniques to build a predictive classification model capable of forecasting landing outcomes.

---

## 🎯 Business Objective

SpaceX has revolutionized the commercial space industry by introducing reusable rocket technology. A Falcon 9 launch costs approximately **$62 million**, while traditional providers may exceed **$165 million** per launch.

The main objective of this project is to determine whether the Falcon 9 first-stage booster will successfully land, helping evaluate:
- Launch success probability.
- Factors affecting booster recovery.
- Potential impact on launch cost optimization.

---

## ❓ Key Research Questions

- How do factors such as **payload mass, launch site, flight number, and orbit type** influence landing success?
- Has Falcon 9 landing performance improved over time?
- Which machine learning algorithm provides the most accurate prediction for landing success?

---

## 🛠️ Project Workflow

### 1. Data Acquisition
- Collected launch records using the **SpaceX REST API**.
- Extracted additional information through **web scraping from Wikipedia**.

### 2. Data Preparation
- Cleaned and transformed raw data.
- Handled missing values and inconsistent records.
- Applied feature encoding techniques for machine learning preparation.

### 3. Exploratory Data Analysis
- Investigated relationships between launch characteristics and landing outcomes.
- Used **Python visualization tools and SQL queries** to extract insights.

### 4. Interactive Analytics
- Built interactive visualizations using:
  - **Folium** for geographical launch analysis.
  - **Plotly Dash** for dynamic dashboards.

### 5. Predictive Modeling
- Developed binary classification models to predict booster landing success.
- Applied hyperparameter tuning and model evaluation.
- Compared algorithms to identify the best-performing approach.

---

## 📊 Technologies Used

**Programming & Analysis**
- Python
- Pandas
- NumPy
- Matplotlib

**Data Collection**
- SpaceX REST API
- BeautifulSoup (Web Scraping)

**Database & Analytics**
- SQL

**Visualization**
- Folium
- Plotly Dash

**Machine Learning**
- Scikit-learn
- Classification Algorithms
- Model Evaluation Metrics

---

## 🚀 Project Outcome

The project delivers a complete data science pipeline, from raw data collection to predictive modeling, providing insights into Falcon 9 launch performance and identifying the most effective machine learning approach for landing prediction.
