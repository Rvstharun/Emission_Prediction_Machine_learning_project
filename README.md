# Emission_Prediction_Machine_learning_project

This machine learning project predicts **India's total CO₂ emissions** based on multiple contributing sectors and economic indicators. The goal is to analyze the pattern of emissions and identify which model can best estimate future emission trends.

## 📌 Project Overview

- **Objective**: Predict total CO₂ emissions in India using economic and industrial features.
- **Dataset**: Real-world emissions dataset from the [CORGIS Datasets Project](https://corgis-edu.github.io/corgis/csv/emissions).
- **Environment**: Built and tested using **Google Colab**, **Python**, and **Scikit-Learn**.

---

## 🔧 Technologies & Libraries Used

- `Python` (Core language)
- `Pandas` (Data handling)
- `Matplotlib` (Basic visualization)
- `Scikit-learn` (Modeling & Evaluation)
- `Google Colab` (Cloud-based development)

---

## 📊 Features Used for Prediction

- CO₂ from Cement
- CO₂ from Coal
- CO₂ from Gas
- CO₂ from Oil
- GDP
- Population

---

## 🧠 Machine Learning Models Used

| Model                | R² Score   | MAE   |
|---------------------|------------|--------|
| Linear Regression   | 0.9999 ✅  | 0.39   |
| Random Forest       | 0.9982     | 14.59  |

> **Conclusion**: Linear Regression gave the best results due to strong linear relationships in the dataset.

---

## 📈 Key Insight

> “Total CO₂ emissions in India are strongly dependent on fossil fuel usage and GDP trends. Linear models captured this effectively, making them ideal for clean and explainable forecasting.”

---

## 📁 Files in This Repo

- `Emission_Prediction_ML_Project.ipynb` — Main Colab notebook with data cleaning, modeling, and results.
- `README.md` — Project overview (this file).

Author
- **Name**: Venkata Sai Tharun Rompilli
- **Project Built With**: Passion for learning & applying ML to real-world problems 🌿



