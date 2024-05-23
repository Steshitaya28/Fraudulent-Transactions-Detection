# Fraudulent-Transactions-Detection
## Overview
This project focuses on developing a robust model for predicting fraudulent transactions and gaining insights for future improvements. The process involves several steps, including data cleaning, feature engineering, visualization, model development, and hyperparameter tuning.

## Table of Contents
Data Cleaning
Label Encoding
Data Visualization
Feature Selection
Model Development
Hyperparameter Tuning
Conclusion
### Data Cleaning
The first step in building the fraud detection model is to clean the dataset. This includes:

1.Handling missing values
2.Removing outliers
3.Standardizing the data formats
These steps ensure that the dataset is in the best possible shape for model training.

### Label Encoding
Categorical data in the dataset is converted to numerical data using Label Encoding. This step is crucial as most machine learning algorithms require numerical input to perform calculations.

### Data Visualization
Data visualization is performed to gain deeper insights into the dataset. This involves:

1.Plotting distributions of various features
2.Identifying patterns and anomalies
3.Visualizing relationships between features and the target variable

### Feature Selection
Feature selection is an important step to identify the most relevant features for the model. This process involves:

### Calculating correlation coefficients
Selecting features that have a strong correlation with the target variable
Only the selected features are used for building the model, which helps in improving the model's performance and reducing overfitting.

### Model Development
Before developing the model, the dataset is split into training and testing sets using train_test_split. Various machine learning classification models are then used to find the best possible accuracy. The models evaluated include:

1.Logistic Regression
2.Decision Trees
3.Random Forest
4.Gradient Boosting
5.KNN

### Hyperparameter Tuning
After building the initial models, hyperparameter tuning is performed to further improve the model's accuracy. Techniques such as Grid Search and Random Search are used to find the optimal parameters for each model.

### Conclusion
The final model is selected based on the best performance metrics after hyperparameter tuning. This project demonstrates a comprehensive approach to fraud detection using machine learning, and provides valuable insights for future improvements in predicting fraudulent transactions.
