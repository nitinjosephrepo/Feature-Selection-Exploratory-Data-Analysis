# Feature Selection with Exploratory Data Analysis (EDA)

Effort here is to identify important features in a given dataset in relation to our target variable (e.g conversion, lead, purchase etc) using multiple types of Correlation methods based on data type. In any given dataset some features are more significant than others, a comprehensive Feature Selection process helps us understands the relationship (Bivariate ) between a feature and our target variale. For eg. whats the relationship of purchase to distance that a shopper lives from a store location. 

Feature selection is important for ML models to avoid 'curse of dimensionality' but for this dataset we will be using it build our intution that benefits our later EDA effort 

When we are using features to predict a target, some features will be more important than others. 
E.g if we are predicting whether someone will default on loan, their credit score will be much better predicter of default than their height or gender.

We often determine the important features in relation to our target variable after fitting data in a ML algorithm like Logistic regression or Multiple linear regression, but effort here is to show feature selection methods like

- Variance thresholding: Remove features with too little or too much variation
- Univariate statistical selection: Use statistical test between features and the target to measure relationship strength.

The above are important in building intution that makes Exploratory Data Analysis (EDA) more affective in drawing insights which are so valuable for marketing campaigns and business
