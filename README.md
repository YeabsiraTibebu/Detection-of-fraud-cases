# Detection-of-fraud-cases

# Task-1: Data Analysis and Preprocessing
1. Handle Missing Values
   - Impute or drop missing values
2. Data Cleaning
   - Remove duplicates
   - Correct data types
3. Exploratory Data Analysis (EDA)
   - Univariate analysis 
   - Bivariate analysis
4. Merge Datasets for Geolocation Analysis
   - Convert IP addresses to integer format
   - Merge Fraud_Data.csv with IpAddress_to_Country.csv
5. Feature Engineering
   - Transaction frequency and velocity for Fraud_Data.csv
   - Time-Based features for Fraud_Data.csv
     - hour_of _day
     - day_of_week
6. Normalization and Scaling
7. Encode Categorical Features

# Task-2: Model Building and Training
1. Data Preparation:
   - Feature and target separation
   - Train-Test split
2. Model Selection:
   - Using several models to compare performance
3. Model Training and Evaluation:
   - Training models for both credit card and fraud data datasets
4. MLOps Steps:
   - Versioning and Experiment Tracking
   - Using tools like Mlflow to track experiments log parameters, metrics, and version models
  
# Task-3:  Model Explainability
1. Using SHAP for Explainability:
   - SHAP values provide a unified measure of feature importance, explaining the contribution of each feature to the prediction.
   - SHAP Plots
      - Summary Plot: Provides an overview of the most important features.
      - Force Plot: Visualizes the contribution of features for a single prediction.
      - Dependence Plot: This shows the relationship between a feature and the model output.
2. Using LIME for Explainability:
   - LIME explains individual predictions by approximating the model locally with an interpretable model.
   - LIME Plots
      - Feature Importance Plot: Shows the most influential features of a specific prediction.

