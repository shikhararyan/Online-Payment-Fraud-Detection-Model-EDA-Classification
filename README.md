# Online Payment Fraud Detection Model EDA + Classification

## Overview
This project focuses on the development of a machine learning model for online payment fraud detection. It includes exploratory data analysis (EDA) and classification using decision tree classifier. The dataset used contains information about various transactions including transaction type, amount, old and new balances, and fraud labels.

## Steps

### 1. Importing Libraries
- Libraries such as pandas, numpy, plotly, sklearn, matplotlib, and seaborn are imported for data manipulation, visualization, and model training.

### 2. Loading the Dataset
- The dataset containing transaction details is loaded.

### 3. Visualizing Missing Values
- Heatmap visualization is used to identify missing values in the dataset.

### 4. Exploratory Data Analysis
- Visualization of transaction type distribution.
- Analysis of transaction types and their corresponding amounts.
- Examination of fraudulent transactions distribution.
- Distribution analysis of the 'step' column.
- Joint plot visualization of 'step' and 'amount'.
- Countplot of fraudulent transactions based on transaction type.

### 5. Correlation Analysis
- Correlation between features and the 'isFraud' column is checked.

### 6. Transformation (Categorical to Numerical)
- Categorical features are transformed into numerical values.
- 'isFraud' column values are converted to 'No Fraud' and 'Fraud' labels.

### 7. Data Splitting
- Data is split into training and testing sets.

### 8. Model Training
- A decision tree classifier is trained using the training data.

### 9. Prediction
- Predictions are made using the trained model for sample features.

## Conclusion
The decision tree classifier achieves a high accuracy of 90+ % in detecting fraudulent transactions. The model shows promising results in identifying potential fraud in online payment transactions.
