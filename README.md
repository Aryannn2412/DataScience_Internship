🌡️ Temperature Prediction from Humidity – Data Science Project
🔍 Overview
This project is part of my Data Science Internship at Skillfied Mentors. The objective is to predict temperature based on humidity readings using linear regression. It introduces exploratory data analysis, basic modeling, and evaluation — all using Python.
📁 Dataset Description
The dataset contains hourly or daily sensor readings with the following features:
Column	Description
humidity	Relative humidity (%)
temperature	Temperature in Celsius
sensor_id	Sensor ID (not used in modeling)
lat, lon	Sensor location coordinates
pressure	Atmospheric pressure (optional)
📌 Only humidity and temperature were used in modeling.
📊 Project Workflow
Load and Inspect Data
Drop missing values
Summary statistics and EDA (scatter plot, correlation)
Train Linear Regression model
Evaluate performance (MSE, R²)
Visualize predictions
🧠 Model Used
Linear Regression (from sklearn)
Optional: Code structured to allow easy replacement with Polynomial Regression
📈 Evaluation Metrics
Mean Squared Error (MSE)
R² Score
📌 Sample Output

Actual vs Predicted Temperature (based on humidity)
✅ Conclusion
A simple linear regression model was used to predict temperature from humidity.
Future Scope:
Use Polynomial Regression for better fit
Add timestamps to explore time series forecasting
Build a web interface using Streamlit
🛠️ Tech Stack
Python
Pandas, NumPy
Matplotlib, Seaborn
Scikit-learn
📂 Files
File	Description
Temperature_Prediction_Test.ipynb	Jupyter notebook with full workflow
humidity.csv	Dataset used for training and evaluation
README.md	Project documentation
🤝 Credits
Internship by Skillfied Mentors
Project guided under their Data Science Task Series
