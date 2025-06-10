<div align="center">

# 🌡️ Temperature Prediction from Humidity

**A Data Science Internship Project**  
🔗 _by [Skillfied Mentors]_ • 🧠 _Intern: Aryan Jha_

</div>

---

## 📌 Overview

This project aims to **predict temperature from humidity** using a simple linear regression model. It's part of a hands-on data science internship task and serves as an introduction to supervised learning, exploratory data analysis, and evaluation.

---

## 📁 Dataset Description

The dataset (`humidity.csv`) contains sensor readings with the following features:

| Column       | Description                         |
|--------------|-------------------------------------|
| `humidity`   | Relative humidity (%)               |
| `temperature`| Temperature in Celsius              |
| `sensor_id`  | Sensor ID (not used in modeling)    |
| `lat`, `lon` | Sensor location coordinates         |
| `pressure`   | Atmospheric pressure (optional)     |

> ✅ **Only `humidity` and `temperature` are used for modeling.**

---

## 🔍 Project Workflow

- ✅ Load and inspect the dataset  
- ✅ Drop missing values  
- ✅ Summary statistics and correlation matrix  
- ✅ Scatter plot: Humidity vs Temperature  
- ✅ Linear Regression Model  
- ✅ Prediction and evaluation  
- ✅ Actual vs Predicted visualization  

---

## 📊 Exploratory Data Analysis

```python
# Summary statistics
df.describe()

# Correlation matrix
df.corr()

# Scatter plot
sns.scatterplot(data=df, x='humidity', y='temperature')
