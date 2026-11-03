# 🌧️ Rainfall Prediction in Australia using Machine Learning

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![Scikit-Learn](https://img.shields.io/badge/Library-Scikit--Learn-orange.svg)](https://scikit-learn.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 📌 Project Overview
Predicting whether it will rain tomorrow is a critical classification task in meteorology. This project utilizes open-source daily weather observation data from the Australian Bureau of Meteorology to build and evaluate predictive machine learning models. 

By comparing **Random Forest Classifier** and **Logistic Regression**, this analysis highlights the performance trade-offs between overall accuracy, precision, and True Positive Rate (Recall) when handling imbalanced weather datasets.

Developed as part of practical machine learning coursework with **IBM**.

---

## 📊 Dataset Overview
The dataset contains daily weather observations from across Australia over multiple years, including parameters such as:
* **Temperature:** Minimum and maximum daily temperatures (`MinTemp`, `MaxTemp`).
* **Humidity & Pressure:** Morning and afternoon measurements (`Humidity9am`, `Humidity3pm`, `Pressure9am`, `Pressure3pm`).
* **Wind:** Gust speed and direction (`WindGustSpeed`, `WindDir9am`, `WindDir3pm`).
* **Precipitation:** Today's rainfall amount (`Rainfall`) and binary indicators (`RainToday`, `RainTomorrow`).

**Target Variable:** `RainTomorrow` (Binary: `Yes` / `No`)

---

## 🛠️ Tech Stack & Dependencies
* **Programming Language:** Python
* **Data Processing & Analysis:** `pandas`, `numpy`
* **Data Visualization:** `matplotlib`, `seaborn`
* **Machine Learning:** `scikit-learn`

To install the required dependencies:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
