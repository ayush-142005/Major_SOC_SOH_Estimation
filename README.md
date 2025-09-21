# SOC and SOH Estimation for Batteries
## Overview
State of Charge (SOC) and State of Health (SOH) estimation are crucial for battery management, especially in electric vehicles and energy storage systems. SOC measures the remaining charge in a battery, while SOH tracks its aging and capacity loss over time.

## Key Estimation Methods
1. Coulomb Counting: Integrates current over time to track charge/discharge cycles. Errors may accumulate due to loss reactions and self-discharge. <br>
2. Voltage Profiling: Uses the battery’s voltage (often OCV) vs. SOC relationship. Accuracy varies with temperature and current load. <br>
3. Kalman Filters: Employs a dynamic model for recursive SOC/SOH updates. Well-suited for real-time applications but requires battery modeling and parameter identification. <br>
4. Data-driven Methods: Utilize machine learning models like LSTM, SVM, Randomforest, Xgboost for prediction based on historical data. <br>

## Dataset
1. https://www.kaggle.com/datasets/pythonafroz/state-of-charge-and-state-of-health-of-batteries?select=Experimental_data_aged_cell.csv
2. https://www.kaggle.com/datasets/patrickfleith/nasa-battery-dataset

## Profile 
Kaggle Profile : https://www.kaggle.com/ayushhood 
