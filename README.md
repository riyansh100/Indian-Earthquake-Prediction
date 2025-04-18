# Earthquake Prediction & Magnitude Forecasting (India-Centric)

This project focuses on predicting the **significance** and **magnitude** of earthquakes in India using machine learning techniques.  
It involves both **classification** and **regression** models, along with interactive map visualizations.
Since magnitude is a continuous variable, I have tried using regression models for estimation purposes. 
Meanwhile, classification models were used for other attributes to show the significance and the probability of the earthquake.

## Overview

- **Classification Task**: Predict whether an earthquake is *Significant* (Magnitude ≥ 4.0).
- **Regression Task**: Predict the actual *magnitude* of upcoming earthquakes.
- **Region Focus**: India (filtered by latitude and longitude).
- **Visualization**: Folium-based interactive maps for both classification and regression predictions.

## File description

- `best_earthquake_model.pkl` – Trained Random Forest Classifier  
- `best_magnitude_model.pkl` – Trained Gradient Boosting Regressor  
- `predicted_magnitude_map_india.html` – Map of high predicted magnitudes  
- `high_risk_earthquakes.html` – Map of significant predicted earthquakes  
- `earthquake_data.csv` – Cleaned dataset used  
- `earthquake_prediction.ipynb` – Jupyter Notebook with complete workflow


## Tools & Libraries

- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Folium)
- Machine Learning models: Linear regression, Logistic Regression, Random Forest classifier & regressor, SVM & SVR, MLP, Gradient Boosting Regressor
