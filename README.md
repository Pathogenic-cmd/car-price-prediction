
# 🚗 Car Price Prediction

## 📌 Overview

This project analyzes various car features to understand the **factors influencing car prices** and builds a **machine learning model** to predict car prices. Visualizations and feature importance analyses are included to support data-driven insights.

---

## 🎯 Objectives

- Identify key features affecting car prices.
- Build predictive models using regression techniques.
- Visualize results with clear and interactive charts.
- Deploy insights in Power BI for stakeholder presentations.

---

## 🗃️ Dataset

The dataset includes 205 cars with features such as:

- **Categorical:** `fueltype`, `carbody`, `drivewheel`, `doornumber`, `CarName`
- **Numerical:** `enginesize`, `horsepower`, `curbweight`, `wheelbase`, `price`
- **Derived:** `Brand` (extracted from `CarName`)
- **Target Variable:** `price`
- **Predicted Output:** `Price Predictions`

---

## 🔍 Exploratory Data Analysis (EDA)

- Strong correlations found between **engine size**, **curb weight**, and **price**
- **Car brands** and **body styles** show significant variation in pricing
- Outliers and non-linear relationships visualized through scatter and box plots

---

## 🤖 Model Development

### Algorithms Used:
- Linear Regression
- Gradient Boosting Regressor

### Evaluation Metrics:
| Metric | Value    |
|--------|----------|
| R² Score | 0.94     |
| MAE | ~1365.09 |
| RMSE | ~1992.65 |
| MAPE | ~4.18%   |

---

## 📊 Power BI Dashboard

The analysis is visualized in Power BI with:
- **KPI Cards** for average price, predicted price, prediction accuracy
- **Bar Charts** for price by brand and body type
- **Scatter Plots** showing relationships between price and features
- **Feature Importance Visual** (Gradient Boosting)

---

## 🛠️ Tools Used

- **Python**: pandas, scikit-learn, xgboost, matplotlib, seaborn
- **Power BI**: Visual dashboards and KPIs
- **Jupyter Notebook** for data exploration and modeling

---

## 📁 Project Files

| File | Description |
|------|-------------|
| `car_dataset.ipynb` | Full analysis and model development |
| `gbr_feature_importance.csv` | Exported feature importances for Power BI |
| `car_predictions.csv` | Original + predicted prices |
| `README.md` | Project overview |
| `requirements.txt` | Python dependencies |

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/Pathogenic-cmd/car-price-prediction.git
   cd car-price-prediction
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Open and run `car_dataset.ipynb`

---

## 📬 Contact

👤 **Daniel Awuma**  
📧 awumadaniel015@gmail.com  
🔗 www.linkedin.com/in/daniel-awuma-23201b22a
