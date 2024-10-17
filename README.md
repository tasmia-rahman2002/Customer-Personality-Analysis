# Customer-Personality-Analysis
Project Description

This project analyzes a marketing campaign dataset to understand customer behavior and predict responses to marketing campaigns. It involves data loading, preprocessing, exploratory data analysis (EDA), and applying machine learning models for prediction.

Working Process

Data Loading and Preprocessing: The project begins by loading the dataset from a CSV file and performs data cleaning. Missing values in the 'Income' column are imputed using the median income based on education level.

Feature Engineering: New features are extracted, such as 'Age,' 'Spending,' and 'Seniority,' to enhance the dataset's predictive power. Categorical features like 'Marital_Status' and 'Education' are simplified for analysis.

Exploratory Data Analysis (EDA): Univariate and multivariate analysis are conducted to gain insights into the data. Distributions, correlations, and relationships between variables are explored using visualizations and statistical measures.

Data Preparation for Machine Learning: Categorical features are encoded using label encoding to prepare the data for machine learning models. Unnecessary columns are dropped, and the dataset is split into training and testing sets.

Model Training and Evaluation: Three machine learning models - Decision Tree, Random Forest, and Logistic Regression - are trained on the training data. These models are evaluated on the testing data, calculating metrics like accuracy and error rate to assess their performance.
