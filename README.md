# Sowing Success: Using Machine Learning to Help Farmers Select the Best Crops

## Project Overview  

In modern agriculture, selecting the right crop to plant is crucial for maximizing yield and ensuring sustainability. Soil condition plays a vital role in determining the optimal crop for a given field. However, measuring essential soil metrics such as nitrogen, phosphorus, potassium levels, and pH can be both expensive and time-consuming. As a result, farmers often face challenges in prioritizing which metrics to assess based on their budget constraints.  

This project aims to leverage machine learning to assist farmers in selecting the best crop for their fields based on soil measurements. By analyzing these metrics, I predicted the most suitable crop to plant, ultimately helping the farmers optimize their yield.  

## Dataset Description  

The dataset provided for this project is called `soil_measures.csv`, which contains the following columns:  

| Column Name | Description                                                 |  
|-------------|-------------------------------------------------------------|  
| `N`         | Nitrogen content ratio in the soil                          |  
| `P`         | Phosphorous content ratio in the soil                       |  
| `K`         | Potassium content ratio in the soil                         |  
| `pH`       | pH value of the soil                                        |  
| `crop`      | Categorical variable representing the optimal crop choice   |  

Each row in this dataset represents various measures of the soil in a particular field, with the corresponding optimal crop indicated in the `crop` column.  

## Objectives  

1. **Data Preparation**: Clean and preprocess the dataset for analysis, including handling any missing values or outliers.  
2. **Model Development**: Build multi-class classification models to predict the type of crop based on the soil metrics.  
3. **Feature Importance Analysis**: Identify the single most important feature that contributes to predictive performance in crop selection.  

## Methodology  

1. **Data Exploration**: Analyze the dataset to understand the distribution of soil metrics and the variety of crops.  
2. **Data Preprocessing**: Normalize the soil metrics and encode the target variable for model training.  
3. **Model Selection**: Implement various classification algorithms (e.g., Decision Trees, Random Forest, Support Vector Machines) to predict crop types.  
4. **Model Evaluation**: Use metrics such as accuracy, precision, recall, and F1-score to evaluate model performance.  
5. **Feature Importance**: Utilize techniques like permutation importance or SHAP values to determine the most influential soil metric for predicting crop yield.  

## Expected Outcomes  

- A robust machine learning model that accurately predicts the optimal crop based on soil conditions.  
- Insights into which soil metric is the most significant for crop selection, aiding farmers in making informed decisions.  
