# 📈 Sales Forecasting with Time Series Models

## 📌 Project Overview
This project focuses on **Time Series Forecasting for Product Price Prediction**. Predicting future product prices is essential for the **Sales Department** to optimize pricing strategies, manage inventory efficiently, and improve revenue forecasting.

By leveraging historical sales data, this project applies advanced time series forecasting techniques, including **Prophet**, to generate future price predictions.

---

## 🎯 Business Objective
Accurate forecasting enables businesses to:
✅ Optimize pricing strategies.  
✅ Improve demand planning.  
✅ Reduce financial risks associated with market fluctuations.  

The goal of this project is to **develop a robust forecasting model** to help businesses anticipate price trends, improving **financial planning** and **decision-making**.

---

## 🏢 Case Study Overview
We applied time series forecasting techniques to analyze historical price trends and generate predictions for future product prices. 

### **🔍 Key Steps in the Analysis**
1️⃣ Understanding the business problem and defining objectives.  
2️⃣ Preprocessing the dataset (handling missing values, outliers, and time-based features).  
3️⃣ Performing **Exploratory Data Analysis (EDA)** to visualize historical price trends.  
4️⃣ Implementing **Prophet** for time series forecasting.  
5️⃣ Evaluating model performance using **MAPE, RMSE, and cross-validation**.  
6️⃣ Comparing Prophet’s results with traditional forecasting models (**ARIMA, LSTM, etc.**).  

---

## 📊 Dataset & Features
The dataset contains **historical sales data**, including:
- 📅 **Date**: Time-series index for price forecasting.  
- 🏬 **Store ID**: Unique identifier for each store.  
- 💰 **Sales**: Target variable representing daily sales revenue.  
- 👥 **Customers**: Number of customers per store per day.  
- 🔥 **Promotions**: Binary indicator for promotional events.  
- 🎉 **State & School Holidays**: Impact of holidays on sales.  
- 📏 **Competition Distance**: Distance to the closest competitor store.  

🔗 **Data Source:** [Kaggle - Rossmann Store Sales Dataset](https://www.kaggle.com/c/rossmann-store-sales/data)  

---

## 🛠️ Tech Stack & Tools Used
✅ **Programming Languages**: Python  
✅ **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
✅ **Time Series Models**: Prophet, ARIMA, LSTM  
✅ **Data Visualization**: Seaborn, Matplotlib  
✅ **Version Control**: GitHub  

---

## 📈 Model Implementation & Evaluation
### **1️⃣ Data Preprocessing**
- Handled missing values and outliers.
- Engineered new time-based features for better model performance.

### **2️⃣ Time Series Forecasting with Prophet**
- Implemented **Facebook’s Prophet model** to capture seasonality and trends.
- Compared Prophet’s performance with **ARIMA** and **LSTM** models.
- Evaluated the models using **Mean Absolute Percentage Error (MAPE)** and **Root Mean Square Error (RMSE)**.

### **3️⃣ Impact of Holidays & Promotions**
- Included public holidays and school holidays as additional regressors in the model.
- Analyzed the impact of promotions on sales trends.

---

## 📌 Key Findings
 
📍 Including holidays improved forecasting accuracy.  
📍 Promotional events had a significant impact on sales trends.  
📍 The model successfully captured seasonal variations in product pricing.  

---

## 🚀 Future Improvements
🔹 Implement **LSTM-based deep learning models** for improved long-term forecasting.  
🔹 Enhance feature engineering with external economic indicators.  
🔹 Deploy the model in a **real-time forecasting dashboard**.  

---

## ✉️ Contact
If you have any questions, feel free to reach out:  
📧 Email: [jpachecoparedes@gmail.com] 
🔗 LinkedIn: [www.linkedin.com/in/juanpachecods] 

