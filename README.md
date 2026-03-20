# 🛒 Walmart Sales Forecasting & Inventory Optimization

## 📌 Project Overview
This project focuses on analyzing historical Walmart sales data and building a machine learning model to forecast future sales. The goal is to help retail stores manage inventory efficiently by predicting demand.

---

## 🎯 Objectives
- Analyze sales trends across different stores
- Identify factors affecting sales
- Build a predictive model for weekly sales
- Forecast sales for the next 12 weeks
- Create an interactive dashboard using Power BI

---

## 🧾 Dataset Information
The dataset contains 6435 rows and 8 features:

- Store: Store number
- Date: Weekly sales date
- Weekly_Sales: Sales amount
- Holiday_Flag: Holiday indicator
- Temperature: Temperature
- Fuel_Price: Fuel cost
- CPI: Consumer Price Index
- Unemployment: Unemployment rate

---

## ⚙️ Technologies Used
- Python (Pandas, NumPy, Scikit-learn)
- VS Code
- Power BI
- GitHub

---

## 🔍 Data Preprocessing
- Converted Date column to datetime format
- Sorted data by Store and Date
- Created new features (Year, Month, Week)
- Generated lag features for time series forecasting
- Handled missing values

---

## 🤖 Model Building
- Algorithm Used: Random Forest Regressor
- Time-based train-test split
- Feature engineering with lag variables and rolling averages

---

## 📊 Model Evaluation
The model was evaluated using:
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## 🔮 Forecasting
The model predicts weekly sales for the next 12 weeks using recursive forecasting techniques.

---

## 📈 Power BI Dashboard
An interactive dashboard was created to visualize:
- Sales trends over time
- Store-wise performance
- Holiday vs non-holiday sales
- Correlation with temperature and unemployment

---

## 📂 Project Structure
Capstone Project/
│
├── data/
│ ├── walmart.csv
│ ├── predictions.csv
│ ├── future_forecast.csv
│
├── notebooks/
│ └── walmart.ipynb
│
├── model/
│ └── sales_model.pkl
│
├── dashboard/
│ └── walmart_dashboard.pbix
│
├── requirements.txt
└── README.md


---

## 💾 Outputs
- Trained model file (`sales_model.pkl`)
- Predictions file (`predictions.csv`)
- Future forecast (`future_forecast.csv`)
- Power BI dashboard (`.pbix`)

---

---

## 🧠 Key Insights
- Sales increase during holiday periods
- Store performance varies significantly
- External factors like temperature and unemployment influence sales
- Machine learning improves forecasting accuracy

---

## 🚀 Future Scope
- Use LSTM (Deep Learning)
- Real-time forecasting
- Integration with supply chain systems
- Deployment as a web application

---

## 👨‍💻 Author
- Gangalakshmi Raja

---

## ⭐ Acknowledgment
This project was developed as part of a capstone project for learning data science and machine learning concepts.