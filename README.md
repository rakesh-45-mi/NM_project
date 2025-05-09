# Cracking the Market Code with AI-Driven Stock Price Prediction

This project leverages AI and time series analysis to predict stock price movement and closing values using historical stock data. It demonstrates model interpretability with visualizations to enhance trust and understanding in AI-based financial forecasting.

## 📌 Problem Statement

Financial markets are highly dynamic and volatile. Predicting stock prices accurately remains a challenging task due to numerous influencing factors. This project proposes a machine learning-based solution that predicts stock price trends and values while offering visual model insights.

## 🎯 Objectives

* Predict whether stock prices will go up or down.
* Estimate the stock's closing price using regression.
* Interpret and visualize model behavior for trust and transparency.
* Analyze feature importance and residual patterns.

## 🛠️ Tools & Technologies

* **Language:** Python
* **IDE:** Jupyter Notebook / VSCode
* **Libraries:** `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `xgboost`

## 📚 Dataset

* **File:** `synthetic_stock_dataset.csv`
* **Description:** A synthetic dataset simulating stock prices with features such as `Open`, `High`, `Low`, `Close`, and `Volume`.

## 🔍 Methodology

1. **Data Preprocessing** – Cleaning, feature selection, and target construction.
2. **Exploratory Data Analysis (EDA)** – Visualization of trends and correlations.
3. **Model Building**

   * **Regression:** XGBoost to predict `Close` prices.
   * **Classification:** Random Forest to predict `Price_Up` movement.
4. **Evaluation & Visualization**

   * Confusion Matrix
   * ROC Curve
   * Feature Importance
   * Residual Plots

## 📈 Results & Insights

The notebook generates plots to interpret model performance and behavior:

* 📊 **Confusion Matrix:** Reveals classification accuracy for predicting price direction.
* 📈 **ROC Curve:** Evaluates classifier performance in distinguishing ups/downs.
* 🔍 **Feature Importance:** Highlights the top factors influencing price direction.
* 📉 **Residual Plots:** Diagnoses regression model fit by checking prediction errors.

## 📁 Files in this Repository

* `main.ipynb` – Contains full preprocessing, modeling, and visualization pipeline.
* `synthetic_stock_dataset.csv` – The input dataset.
* `README.md` – This file.

## ▶️ Usage

To run the notebook locally:

1. Install dependencies using:

   ```bash
   pip install -r requirements.txt
   ```
2. Open `main.ipynb` in Jupyter Notebook or VSCode.
3. Run all cells to preprocess data, train models, and view visualizations.

## 🔮 Future Enhancements

* Include GNNs for capturing inter-stock correlations
* Real-time price prediction using live APIs
* Build a web dashboard using Streamlit

## 👥 Authors

**Rakesh R**
**Mohamed Yasin M**
**Mohamed Afzer M**
**Mohamed Afrith J**
Department of Electronics and Communication Engineering
Dhaanish Ahmed College of Engineering

