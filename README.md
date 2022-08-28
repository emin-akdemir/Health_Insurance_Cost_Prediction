# Health_Insurance_Cost_Prediction - Global AI Hub

## 1) Problem Overview
Medical Cost Analysis:
The aim of the project is to estimate the approximate cost of a person's health insurance based on the given variables.

## 2) Collecting of data
In this project, I used the Medical Cost Personal Datasets at the [link](https://www.kaggle.com/datasets/mirichoi0218/insurance).
 * Importing the required libraries
   *	Numpy
   *	Pandas
   *	Scikit-learn
 * Read the data

## 3) Examination and visualization of data
 * General overview to data
 * Visualize the data

## 4) Fitting Data to Machine Learning Models
 * LabelEncoder
 * One Hot Encoder
 * Features and Labels
 * Split the data
 * Normalization

## 5) Model Selection - Creating and Training of the Models
  * LGBMRegressor
  * XGBRegressor
  * RandomForestRegressor
  * DecisionTreeRegressor
  * CatBoostRegressor
  * GradientBoostingRegressor
#### Conclusion: When the cross validation results are evaluated, it is seen that the model with the best performance is the XGBRegressor() model.Therefore, we continue by choosing the XGBRegressor() model.

## 6) Hyper-parameter Optimization with Grid Search

## 7) Evaluation of the optimized model using regression model evaluation criteria: 
 * R2
 * MAE
 * MSE
