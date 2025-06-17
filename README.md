<div align="center">

# 🔬 Data Science Internship Projects

**Real-world Applications of Machine Learning, Forecasting & Anomaly Detection**  
🔗 _by [Skillfied Mentors]_ • 🧠 _Intern: Aryan Jha_

</div>

---

## 📦 Project Repository Overview

This repository contains a collection of 3 mini-projects completed as part of a hands-on data science internship.  
Each task showcases a different branch of data science — including **regression**, **time series forecasting**, and **fraud detection using classification**.

---

## ✅ Completed Projects

---

### 1️⃣ 🌡️ Temperature Prediction from Humidity

A regression-based project where a simple linear model is used to predict **temperature** based on **humidity**.

#### 📁 Dataset: `humidity.csv`

| Column       | Description                         |
|--------------|-------------------------------------|
| `humidity`   | Relative humidity (%)               |
| `temperature`| Temperature in Celsius              |
| `sensor_id`  | Sensor ID (not used in modeling)    |
| `lat`, `lon` | Sensor location coordinates         |
| `pressure`   | Atmospheric pressure (optional)     |

#### 🔍 Workflow:

- Load & clean the data  
- Drop missing values  
- Summary stats & correlation  
- Scatter plot (humidity vs temp)  
- Linear regression model  
- Evaluation & visualization  
- ✅ Conclusion: Consider polynomial regression for more complex patterns

---

### 2️⃣ 📈 Quantity Forecasting using Time Series Analysis

A time-series forecasting task using **ARIMA modeling** to predict quantity sold over time from transactional order data.

#### 📁 Dataset: `Raw Data_Predictive Analysis.xlsx`

| Column Name          | Description                     |
|----------------------|---------------------------------|
| `OrderDate`          | Date of the order               |
| `total_qty_sales`    | Total quantity sold             |
| `ParentProductNew`   | Product name                    |
| `ProductCategoryNew` | Category                        |
| `productListViews`   | Product views (optional)        |
| `productListClicks`  | Product clicks (optional)       |

#### 🔍 Workflow:

- Load and inspect timestamped data  
- Resample daily to weekly  
- Visualize sales trends  
- Time series decomposition  
- Train/test split  
- ARIMA model fitting  
- Forecasting + Evaluation  
- ✅ Conclusion: Consider SARIMA, Prophet, or LSTM for complex seasonality

---

### 3️⃣ 💳 Credit Card Fraud Detection (Binary Classification)

A classification project that applies **logistic regression** to detect fraudulent transactions from anonymized credit card data.

#### 📁 Dataset: `creditcard.csv`

| Column       | Description                           |
|--------------|---------------------------------------|
| `V1` - `V28` | PCA-transformed features (anonymized) |
| `Time`       | Seconds elapsed between transactions  |
| `Amount`     | Transaction amount                    |
| `Class`      | Target (1 = fraud, 0 = normal)        |

#### 🔍 Workflow:

- Feature scaling for `Time` and `Amount`  
- Checked class distribution and handled imbalance via stratified split  
- Trained a logistic regression model  
- Evaluated using confusion matrix, precision, recall  
- ✅ Conclusion: Accuracy is misleading due to imbalance.  
  ➕ Future: Try SMOTE, Random Forest, XGBoost, or Deep Learning

---

## 🕒 Internship Status

✅ **All 3 internship tasks successfully completed.**  
🧠 Projects span **regression, forecasting, and classification.**  
📈 Next: Continue exploring advanced modeling and deployment (e.g., Streamlit dashboards or model APIs).

---

## 👨‍💻 Author

**Aryan Jha**  
_BTech | Data Science Intern | ML Enthusiast_  
[🔗 Portfolio Website](https://aryannn2412.github.io)

---

## ⭐️ Show Your Support

If this repo helped you, feel free to:

- ⭐ Star it  
- 🍴 Fork it  
- 👀 Share it

---

