# **Superstore Sales Prediction – Machine Learning Models Comparison**  

## 📌 Overview  
This project predicts sales for a retail store using the **Superstore dataset**. The workflow includes **data preprocessing, exploratory data analysis (EDA), outlier removal, and feature engineering**.  
Multiple regression models — **Linear Regression, Decision Tree Regressor, Random Forest Regressor, and Gradient Boosting Regressor** — are trained and compared to identify the most accurate predictor.  
Additionally, the project features a **Power BI interactive dashboard** for visualizing insights.  

---

## 📊 Dataset  
The dataset contains sales-related information, including:  
- Order Date, Ship Date, Region  
- Product Category, Sub-Category  
- Sales, Profit, Quantity, Discount  

---

## ⚙️ Workflow  

### 1. **Data Preprocessing**  
- Removed irrelevant columns (`Customer ID`, `Row ID`)  
- Handled missing values  
- Extracted year, month, and day from `Order Date` for feature engineering  
- Removed outliers using the IQR method  

### 2. **EDA (Exploratory Data Analysis)**  
- Heatmap for correlation analysis  
- Sales distribution across regions and categories  
- Trend analysis over time  

### 3. **Modeling**  
Trained and tested:  
- **Linear Regression**  
- **Decision Tree Regressor**  
- **Random Forest Regressor**  
- **Gradient Boosting Regressor**  

Compared models based on **R² Score**, **MAE**, and **RMSE**.  

### 4. **Visualization**  
- Predicted vs Actual sales plots for each model  
- Comparison graph of all models  
- Power BI dashboard for interactive exploration  

---

## 📈 Results  
- Gradient Boosting & Random Forest performed best with high accuracy and low error rates.  
- The Power BI dashboard enables filtering by **Region, Category, and Time Period**.  

---

## 🛠 Tech Stack  
- **Python**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Power BI**: Interactive dashboard  
- **Jupyter Notebook** for analysis  

---

## 🚀 How to Run  
```bash
# Clone repository
git clone <repo-link>

# Install dependencies
pip install -r requirements.txt

# Run Jupyter Notebook
jupyter notebook notebooks/superstore_sales_prediction.ipynb
