# Australia Weather & Rain Prediction

A machine learning project designed to predict daily rainfall in Australia using historical weather data. The project covers data preprocessing, feature engineering, handling class imbalance, hyperparameter tuning, and model evaluation using `scikit-learn`.

---

## 📌 Project Overview
The objective of this project is to build a binary classification model that predicts whether it will rain tomorrow (`RainTomorrow`: Yes/No) based on various atmospheric and meteorological measurements (such as humidity, pressure, temperature, and wind speed).

---

## 🛠️ Key Steps & Methodology
* **Data Cleaning & Preprocessing:** Handled missing values, encoded categorical attributes, and scaled numerical features.
* **Feature Engineering:** Extracted seasonal components from dates, renamed features for clarity, and addressed correlated features.
* **Class Imbalance Management:** Implemented techniques to balance target classes for better real-world prediction accuracy.
* **Model Training & Hyperparameter Tuning:** Trained classification algorithms (including Random Forest) and tuned parameters using `GridSearchCV`.
* **Evaluation:** Evaluated performance using accuracy, precision, recall, F1-score, and confusion matrices.

---

## 📁 Repository Structure
```text
├── data/                  # Weather dataset files
├── notebooks/             # Exploratory Data Analysis & Model Training notebooks
├── src/                   # Helper scripts and ML pipeline functions
├── .gitignore             # Standard Python gitignore configuration
└── README.md              # Project documentation
