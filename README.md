# Cardiovascular Disease Prediction

##Authors: Pablo Aguilar Ruiz - Guillem Gusart Verdú 

## 1. Objective:
The challenge is to analyze a medical dataset, identify patterns, and build a predictive model that can classify patients into two categories:
- **0**: Does not have cardiovascular disease.
- **1**: Has cardiovascular disease.

This classification can help medical professionals identify high-risk patients more efficiently and with fewer resources.

## 2. Dataset Description:
The dataset includes patient medical data such as:
- **Age, gender, height, and weight**: Demographic and physical factors.
- **Blood pressure**: Key indicators of cardiovascular health.
- **Cholesterol and glucose**: Important biochemical measures.
- **Personal habits**: Smoking, alcohol consumption, and physical activity.

All these variables have been analyzed and preprocessed to ensure efficient modeling.

## 3. Project Approach:
To achieve the objective, we followed these steps:
1. **Data visualization**: Begin by graphically analyzing the data to understand the distribution of variables.
2. **Data exploration**: Conduct descriptive analysis to identify relationships between variables, detect potential anomalies, and determine which variables may have the greatest impact on predicting cardiovascular diseases.
3. **Data preparation**: Perform key preprocessing steps, such as encoding categorical variables, handling outliers, and splitting the data into training and testing sets to ensure fair evaluation of the models.
4. **Model selection**: Test various classification algorithms, starting with a linear model like Logistic Regression to establish a baseline and then exploring more complex models like XGBoost to improve overall performance.

This approach combines exploratory analysis and advanced machine learning techniques to develop a robust model applicable to real-world scenarios.
