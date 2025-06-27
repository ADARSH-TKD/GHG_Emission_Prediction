# 🌍 Greenhouse Gas Emission Prediction


This project aims to predict **Greenhouse Gas (GHG) emissions** from various industrial and commodity sectors in the U.S. using data-driven machine learning models. The goal is to support climate action by helping industries analyze and reduce their carbon footprint.

---

## 🧠 Project Overview

With increasing concerns about climate change, forecasting GHG emissions is crucial. This project uses historical datasets and machine learning to predict emission trends across industries, enabling data-backed sustainability decisions.

---

## 🔧 Modules & Libraries Used

| Library       | Purpose |
|---------------|---------|
| `pandas`      | Data loading, cleaning, manipulation |
| `numpy`       | Numerical operations |
| `matplotlib`  | Visualization |
| `seaborn`     | Statistical plotting |
| `scikit-learn`| ML models and preprocessing |
| `xgboost`     | Gradient boosting regressor |
| `openpyxl`    | Excel file handling |
| `warnings`    | Warning suppression |
| `joblib`      | Model persistence |

---

## 📂 Dataset

- **Source**: Supply Chain Emission Factors for U.S. Industries & Commodities  
- **File**: `.xlsx` format  
- **Details**: Contains emissions by commodity, year, and industry type.

---

## 📌 Key Features

- Load and explore multi-sheet Excel files
- Handle and clean missing data
- Visualize data using charts and graphs
- Train and evaluate regression models
- Predict and visualize future emission values
- Save models for later use

---

## 🤖 Machine Learning Models

- **Linear Regression**
- **Random Forest Regressor**
- **XGBoost Regressor**

Evaluation metrics used:

- R² Score
- Mean Squared Error (MSE)

---

## 📈 Output

- Charts showing emission trends per industry
- Predicted values vs actual values
- Sector-wise emission factor analysis

---

## 🏁 Getting Started

To run the notebook locally:

```bash
git clone https://github.com/yourusername/ghg_emission_prediction.git
cd ghg_emission_prediction
pip install -r requirements.txt
jupyter notebook ghg_emission_prediction.ipynb
