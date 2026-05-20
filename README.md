# CodeAlpha_Sales_Prediction
# 📈 Sales Forecasting & Advertising Impact Analysis

A clean end to end Machine Learning pipeline built in Python to analyze advertising spend across TV, Radio and Newspaper channels and forecast future sales with actionable business insights.

## 🎯 Project Overview
This project evaluates marketing budgets to maximize ROI. It trains a Multi Variable Linear Regression model to understand how different advertising mediums affect sales and programmatically generates data driven recommendations for business strategies.

---

## 🛠️ Pipeline Architecture
The project is structured into 5 sequential cells in a Jupyter Notebook:

1. **Future Sales Prediction:** Sets up initial data loading, basic checks, and train-test split tracking.
2. **Data Pipeline & Scaling:** Handles data quality checks (nulls & duplicates) and normalizes features using `StandardScaler`.
3. **Sales Forecasting Engine:** Trains the Multi-Variable Linear Regression model and evaluates accuracy using **RMSE** and **$R^2$ Score**.
4. **Impact Analysis & Visualization:** Extracts model coefficients and generates a sorted bar chart to visually map channel performance.
5. **Actionable Strategy Delivery:** Dynamic text generation that translates raw model weights into explicit strategic recommendations for stakeholders.

---

## 💻 Tech Stack
* **Language:** Python 3
* **Libraries:** `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone [https://github.com/ahsanali-source/CodeAlpha_Sales_Prediction](https://github.com/ahsanali-source/CodeAlpha_Sales_Prediction.git)
