
# Insurance Premium Prediction Dataset


### * Problem Statement:
The objective of this project is to predict insurance claim amounts based on various features of the insured individuals. Accurate predictions can assist insurance companies in pricing policies appropriately and managing risk effectively

### * Asking the Right Questions
What are the key factors influencing insurance claim amounts?
How accurately can we predict claim amounts using regression models?
Are there any patterns or trends in the data that provide insights into insurance claims?

### * Data Collection and Dataset Overview

The dataset used in this project is sourced from Kaggle's "Regression with an Insurance Dataset" competition. It includes features such as age, sex, BMI, number of children, smoking status, region, and charges. 

[![Kaggle DataSource]](https://www.kaggle.com/datasets/schran/insurance-premium-prediction)

[! [Google Drive Link for Dataset]](https://drive.google.com/drive/folders/1Emap5GUHl_mnLjVAdgRRi-JlqsHgaskv?usp=drive_link)

#### DataSet Overview insights
The goal is to facilitate the development and testing of regression models for predicting insurance premiums based on various customer characteristics and policy details. This synthetic dataset simulates real-world scenarios to help practitioners practice feature engineering, data cleaning, and model training

- This dataset contains 2Lk+ and 20 features with a mix of categorical, numerical, and text data. It includes missing values, incorrect data types, and skewed distributions to mimic the complexities faced in real-world datasets. The target variable for prediction is the "Premium Amount".

#### Features
- Age: Age of the insured individual (Numerical)
- Gender: Gender of the insured individual (Categorical: Male, Female)
- Annual Income: Annual income of the insured individual (Numerical, skewed)
- Marital Status: Marital status of the insured individual (Categorical: Single, Married, Divorced)
- Number of Dependents: Number of dependents (Numerical, with missing values)
- Education Level: Highest education level attained (Categorical: High School, Bachelor's, Master's, PhD)
- Occupation: Occupation of the insured individual (Categorical: Employed, Self-Employed, Unemployed)
- Health Score: A score representing the health status (Numerical, skewed)
- Location: Type of location (Categorical: Urban, Suburban, Rural)
- Policy Type: Type of insurance policy (Categorical: Basic, Comprehensive, Premium)
- Previous Claims: Number of previous claims made (Numerical, with outliers)
- Vehicle Age: Age of the vehicle insured (Numerical)
- Credit Score: Credit score of the insured individual (Numerical, with missing values)
- Insurance Duration: Duration of the insurance policy (Numerical, in years)
- Premium Amount: Target variable representing the insurance premium amount (Numerical, skewed)
- Policy Start Date: Start date of the insurance policy (Text, improperly formatted)
- Customer Feedback: Short feedback comments from customers (Text)
- Smoking Status: Smoking status of the insured individual (Categorical: Yes, No)
- Exercise Frequency: Frequency of exercise (Categorical: Daily, Weekly, Monthly, Rarely)
- Property Type: Type of property owned (Categorical: House, Apartment, Condo)
#### Data Characteristics
- **Missing Values**: Certain features contain missing values to simulate real-world data collection issues.
- **Incorrect Data Types**: Some fields are intentionally set to incorrect data types to practice data cleaning.
- **Skewed Distributions**: Numerical features like Annual Income and Premium Amount have skewed distributions, which can be addressed through transformations.

### Data Wrangling (Preprocessing)
- **Handling Missing Values**  : The dataset was examined for missing values, and appropriate imputation techniques were applied where necessary.
- **Outlier Detection**: Outliers were identified and addressed to prevent skewing the model's performance.
- **Data Type Conversion**: Categorical variables were encoded using one-hot encoding to make them suitable for regression analysis.
- **Feature Engineering**: New features were created to capture interactions between existing variables, potentially enhancing model performance.
- **Feature Scaling**: Numerical features were standardized to ensure uniformity across variables.

### Exploratory Data Analysis (EDA)

EDA was conducted to understand the relationships between features and the target variable (charges). Key findings include:

- **Correlation Analysis**: Identified strong correlations between certain features and the target variable.
- **Distribution Plots**: Visualized the distribution of charges across different categories, such as smoking status and region.
- **Trend Analysis**: Observed trends indicating higher charges for smokers compared to non-smokers.

### Predictive Analysis

- **Data Splitting**: The dataset was divided into training and testing sets to evaluate model performance.
- **Model Selection**: Multiple regression algorithms were considered, including Linear Regression, Ridge Regression, and Lasso Regression.
- **Model Evaluation**: Models were assessed using metrics such as R², RMSE, and MAE to determine accuracy.
- **Model Optimization**: Hyperparameter tuning was performed to enhance model performance.


### Submission Links:

Jupyter code file:
[View the Jupyter Notebook](https://github.com/zeeshanrafiqrana/DS-RegressionAnalysis/blob/main/s4_e12_regression_analysis_for_insurance_dataset.ipynb)

[ViewDataset](https://drive.google.com/drive/folders/1Emap5GUHl_mnLjVAdgRRi-JlqsHgaskv?usp=drive_link)

Loom Videos for Basic Implmentation explanation:
- Part 1 (5min): [Basic Overview of Dataset and Work](https://www.loom.com/share/12c54752a74c4453ad6103829612678c)
- Part 2 (5min)[Data Wrangling, Feature Engineering etc](https://www.loom.com/share/1caa682ddcca4a1c904afafba488fd8a)
- Part 3 (5min) [Conclusion](https://www.loom.com/share/51e4fb1776c04f67bad82dfa0590bc3c)




## 🔗 Reference Links

ZEESHAN RAFIQUE (2024-MSDS-114)

[![linkedin](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/zeeshanrafiqrana)

[![kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)](https://www.kaggle.com/zeeshanrafiqrana)

[![google-dev](https://img.shields.io/badge/Google%20Developer-4285F4?style=for-the-badge&logo=google&logoColor=white)](https://g.dev/zeeshanrafiq)

[![github](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/zeeshanrafiqrana)
