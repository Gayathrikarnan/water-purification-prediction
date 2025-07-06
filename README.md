# WATER QUALITY PREDICTION
This project aims to predict multiple water quality parameters using machine learning techniques, specifically MultiOutputRegressor wrapped around a RandomForestRegressor

# OVERVIEW
This project aims to predict the concentration levels of six key water pollutants using historical environmental monitoring data. By utilizing machine learning, it helps forecast pollution trends at different water monitoring stations based on the year of interest.

# POLLUTANTS PREDICTED:

O2 (Oxygen)
NO3 (Nitrate)
NO2 (Nitrite)
SO4 (Sulfate)
PO4 (Phosphate)
CL (Chloride)

 # TECHNOLOGIES USED
  python - 3.11
  Scikit-learn — Model building (RandomForest + MultiOutputRegressor)
  pandas / numpy — Data cleaning & transformation
  Joblib — Model serialization  
  Streamlit — Web app for deployment
  Metrics — MSE, R² Score for evaluation

# DATA PREPROCESSING:
Loading Data
Date Parsing & Sorting
Feature Engineering
Handling Missing Values
Feature Encoding

# MODEL:
 Multi-Output Regression and
 Random Forest Regressor

# DEPLOYMENT:
Saved trained model using joblib to pollution_model.pkl.
Saved the list of model input columns to model_columns.pkl for reproducible inference.
