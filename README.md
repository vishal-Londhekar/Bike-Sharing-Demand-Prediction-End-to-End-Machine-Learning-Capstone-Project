# 🚲 Bike Sharing Demand Prediction

## 📌 Objective
To forecast hourly bike rental demand using historical weather and seasonal data with a regression model. This helps optimize bike availability and resource planning.

## 📂 Dataset
- Source: Kaggle – [Bike Sharing Dataset](https://www.kaggle.com/datasets/lakshmi25npathi/bike-sharing-dataset)
- Records: ~17,000 hourly data points
- Features: Date, Hour, Season, Weather, Temperature, Humidity, Windspeed, Holiday, Working Day, Count (target)

## 🧰 Tools & Technologies
- Python, Pandas, NumPy
- Scikit-learn (Random Forest, Linear Regression)
- Matplotlib, Seaborn
- Jupyter Notebook

## 🚀 Workflow Summary
1. 🧹 **Data Cleaning & Feature Engineering**
   - Handled missing data and converted datetime features
   - Created new features like "Hour", "Day Type", and "Weekend"

2. 📊 **Exploratory Data Analysis**
   - Identified peak rental hours and demand trends by day, weather, and season
   - Visualized correlations and outliers

3. 🤖 **Modeling**
   - Trained **Random Forest Regressor** and **Linear Regression**
   - Chose Random Forest (best R² = **91%**)
   - Evaluated using MAE, RMSE, and R² score

4. 📈 **Insights**
   - High rental demand during commuting hours (8-10 AM, 5-7 PM)
   - Bad weather significantly reduces demand
   - Holidays and weekends shift usage patterns


## 💼 Business Value
- Helps city planners & bike-sharing platforms:
  - Ensure optimal bike allocation by time and location
  - Reduce customer dissatisfaction during peak hours
  - Improve predictive maintenance planning based on usage
