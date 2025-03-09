# 📊 Walmart Sales Forecasting

## 📌 Project Overview
This project focuses on **analyzing and forecasting weekly sales** for **45 Walmart stores**. The goal is to explore how different factors such as **temperature, CPI, unemployment, and holidays** influence sales and develop a predictive model for future sales trends.

---
## 🎯 Features
✅ Time series analysis of Walmart sales data  
✅ SARIMA-based forecasting for weekly sales  
✅ Impact analysis of external factors (temperature, holidays, etc.)  
✅ Data visualization and insights for business strategies  

---
## 🛠️ Technologies Used
- 🐍 Python
- 📊 Pandas, NumPy
- 📈 Statsmodels, Scikit-learn
- 📉 Matplotlib, Seaborn

---
## 🔍 Techniques Used

### 1️⃣ Data Pre-processing
🛠️ **Data Importing:** Loaded Walmart sales dataset using Pandas  
📊 **Exploratory Data Analysis (EDA):** Checked missing values, duplicates, and feature relationships  
📆 **Date Conversion:** Transformed the 'Date' column to datetime format  
📉 **Stationarity Tests:** Conducted tests to determine if differencing was needed for SARIMA modeling  

### 2️⃣ Time Series Forecasting with SARIMA
🔄 **SARIMA Model:** Built **Seasonal AutoRegressive Integrated Moving Average (SARIMA)** models to predict future sales  
📊 **Trend & Seasonality Analysis:** Used seasonal decomposition to identify patterns  
📉 **Model Training & Testing:** Trained SARIMA models and evaluated predictions  
📈 **12-Week Forecasting:** Predicted future sales for each store  

### 3️⃣ Model Evaluation & Insights
📊 **Performance Metrics:** Evaluated accuracy using RMSE and MAPE  
📌 **Impact Analysis:** Studied how holidays, temperature, and economic factors affect sales  
🏪 **Store-wise Insights:** Identified high and low-performing stores  

---
## 🗂️ Data Description
The dataset used in this project is a **trial dataset** that simulates Walmart's weekly sales, including information on:
- 🏪 Store ID
- 📆 Weekly Sales
- 🌡️ Temperature
- 💰 CPI (Consumer Price Index)
- 📉 Unemployment Rate
- 🎉 Holiday Flags

🔹 **Disclaimer:** This dataset is for educational and testing purposes only and does not represent actual Walmart sales data.

---
## 🚀 How to Use
1️⃣ Load the dataset `Walmart_Sales.csv`.  
2️⃣ Run the Jupyter Notebook to process the data and train the SARIMA model.  
3️⃣ Analyze visualizations and forecasts for better business decisions.  

---
## 🔮 Future Enhancements
📢 **Incorporate More External Factors:** Include weather, fuel prices, or promotional data for improved predictions.  
📊 **Advanced Models:** Experiment with Prophet, LSTM, or XGBoost for better accuracy.  
📡 **Real-time Forecasting:** Integrate with live data feeds for dynamic predictions.  

---
## 📌 Conclusion
This project provides a **data-driven approach to sales forecasting** for Walmart stores. By leveraging **SARIMA models**, we can predict future sales trends and optimize inventory management, marketing strategies, and business operations.

---
## 📚 References
- Pandas: [pandas.pydata.org](https://pandas.pydata.org/)  
- Matplotlib: [matplotlib.org](https://matplotlib.org/)  
- Seaborn: [seaborn.pydata.org](https://seaborn.pydata.org/)  
- Statsmodels: [statsmodels.org](https://www.statsmodels.org/)  
- Scikit-learn: [scikit-learn.org](https://scikit-learn.org/)  
- pmdarima (SARIMA): [pypi.org/project/pmdarima](https://pypi.org/project/pmdarima/)  
