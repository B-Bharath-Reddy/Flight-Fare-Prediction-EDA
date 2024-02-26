# Flight-Fare-Prediction-EDA
### Flight Fare Prediction

This repository contains the code and documentation for predicting flight fares based on exploratory data analysis (EDA) and the training of various machine learning models. 

#### Overview:
The goal of this project is to accurately predict flight fares based on several features such as departure time, arrival time, airline, route, etc. 

#### Approach:
1. **Exploratory Data Analysis (EDA):** 
   - Conducted thorough analysis of the dataset to understand the distribution of features, identify correlations, and explore trends.
   - Visualized key insights using matplotlib and seaborn to gain deeper understanding of the data.

2. **Model Training:**
   - Trained over 20 machine learning models including Linear Regression, Ridge Regression, Lasso Regression, Decision Trees, Random Forest, Gradient Boosting, XGBoost, etc.
   - Experimented with various hyperparameters and techniques such as feature engineering and feature selection to improve model performance.

#### Results:
- After comprehensive analysis and model training, it was found that the XGBoost algorithm consistently outperformed other models in terms of predictive accuracy.
- The trained XGBoost model achieved the highest \( R^2 \) score, indicating its superior performance in predicting flight fares.

#### Repository Structure:
- **Notebooks:** Contains Jupyter notebooks detailing the EDA process, feature engineering, and model training.
- **Data:** Dataset used for training and evaluation.
- **Models:** Saved trained models in pickle or other formats.
- **Documentation:** Additional documentation including project report, model evaluation metrics, and insights.

#### Future Work:
- Further fine-tuning of hyperparameters to improve model performance.
- Exploration of advanced techniques such as ensemble methods and neural networks.
- Deployment of the best-performing model as a web application or API for real-time fare prediction.

#### Conclusion:
This project demonstrates the effectiveness of machine learning in predicting flight fares and provides valuable insights into the factors influencing ticket prices. The trained models can be used by airlines, travel agencies, and passengers to make informed decisions and plan their travel more efficiently.
