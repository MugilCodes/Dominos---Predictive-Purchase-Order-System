# Dominos---Predictive-Purchase-Order-System
Domino’s Predictive Purchase Order System uses time series forecasting and machine learning to predict weekly sales and generate optimal ingredient orders. It reduces waste, prevents stockouts, and boosts inventory efficiency. Built using Python, SQL, and Power BI, it’s a smart solution for food service operations.

# 🍕 Dominos – Predictive Purchase Order System  

## 📌 Project Overview  
This project helps **Dominos** optimize inventory by predicting pizza sales for the next 7 days and generating a **purchase order for required ingredients**.  
By using **time series forecasting models** and historical sales data, the system ensures the right stock levels, reduces waste, and prevents stockouts.  

---

## 🎯 Problem Statement  
Dominos needs an automated way to forecast sales and calculate ingredient requirements. Accurate forecasting ensures:  
- ✅ Optimal inventory management  
- ✅ Reduced costs by minimizing waste  
- ✅ Improved supply chain efficiency  
- ✅ Data-driven business decisions  

---

## 🏆 Business Use Cases  
- **Inventory Management** – Maintain the right stock levels  
- **Cost Reduction** – Avoid waste from excess stock  
- **Sales Forecasting** – Predict pizza sales trends  
- **Supply Chain Optimization** – Auto-generate purchase orders  

---

## 🔑 Skills & Technologies Used  
- Data Cleaning & Preprocessing  
- Exploratory Data Analysis (EDA)  
- Time Series Forecasting (ARIMA, SARIMA, Prophet, LSTM, RandomForest)  
- Predictive Modeling  
- Python (Pandas, Numpy, Scikit-learn, Statsmodels, Prophet, TensorFlow/Keras)  
- Visualization (Matplotlib, Seaborn)  

---

## 📂 Dataset  
1. **Sales Data** – Historical records (date, pizza type, quantity, price, category, ingredients)  
2. **Ingredients Data** – Pizza recipes (pizza name, ingredients, qty per pizza in grams)  

---

## 📊 Approach  
1. **Data Preprocessing & Cleaning** – Remove missing values, outliers, duplicates  
2. **EDA** – Sales trends, seasonality, categories  
3. **Feature Engineering** – Day, month, weekday/weekend, promotions, seasonality  
4. **Model Training & Evaluation** – ARIMA, SARIMA, Prophet, LSTM, RandomForest  
   - Evaluated using **MAPE (Mean Absolute Percentage Error)**  
   - Best model: **Prophet (MAPE ≈ 16.38%)**  
5. **Sales Forecasting** – Predict pizza sales for the next 7 days  
6. **Ingredient Calculation** – Convert sales forecasts into ingredient requirements  
7. **Purchase Order Generation** – Save as **purchase_order_next_7days.csv**  

---

## 📈 Results  
- Accurate pizza sales forecast  
- Ingredient-level purchase order generated  
- Example Output:  

| Ingredient         | Required (grams) | Required (kg) |  
|---------------------|------------------|---------------|  
| Mozzarella Cheese  | 12,500           | 12.5          |  
| Tomato Sauce       | 8,900            | 8.9           |  
| Chicken            | 7,300            | 7.3           |  

---

## 📑 Deliverables  
- ✅ Cleaned datasets  
- ✅ EDA with insights  
- ✅ Predictive models + evaluation metrics  
- ✅ Pizza-wise sales forecast (CSV)  
- ✅ Ingredient purchase order (CSV)  
- ✅ Jupyter Notebook (end-to-end code)  
- ✅ README.md & Project Report  

---

## ⚙️ Installation & Setup  

### 1. Clone Repository  
```bash
git clone https://github.com/yourusername/Dominos-Purchase-Order-System.git
cd Dominos-Purchase-Order-System
