# Fraud-Detection-System
This repository contains a comprehensive fraud detection system implemented using Python. The project involves data preprocessing, exploratory data analysis (EDA), and building machine learning models to predict fraudulent transactions.

### Project Overview
The goal of this project is to build a machine learning model that can accurately identify fraudulent transactions from a given dataset. We utilize two models: Random Forest Classifier and Decision Tree, to compare their performances in detecting fraud.

### Dataset
The dataset contains various transaction records, including features such as transaction amount, balances before and after the transaction, and whether the transaction was flagged as fraud. The dataset is located in Fraud.csv.

### Steps Involved
1. Data Loading and Initial Exploration
  a. Load the dataset and display the first few rows and summary statistics.
  b. Check for missing values and dataset dimensions.
2.Data Cleaning
  a.Remove outliers using the IQR method.
  b.Encode categorical variables using label encoding.
3.Exploratory Data Analysis (EDA)
  a.Visualize the distribution of fraudulent and non-fraudulent transactions.
  b.Plot a correlation heatmap to identify relationships between features.
4.Feature Engineering
  a.Create new features by encoding transaction types and destinations.
  b.Drop unnecessary columns to simplify the dataset.
5.Model Training and Evaluation
  a.Split the dataset into training and test sets.
  b.Train Logistic Regression and Decision Tree models.
  c.Evaluate model performance using accuracy scores and classification reports.
6.Visualization
  a.Generate visualizations to aid in understanding data distributions and model performance.
7.User Input and Prediction
  a.Implement functions to accept user input and predict whether a transaction is fraudulent using trained models.

### Key Findings
1.The dataset is highly imbalanced, with a very small percentage of fraudulent transactions.
2.The Logistic Regression model achieved high accuracy, indicating its effectiveness in detecting fraud.
3.Decision Tree also performed well, offering an alternative with similar accuracy.

### Future Work
1.Explore advanced techniques such as SMOTE for handling imbalanced data.
2.Implement additional machine learning models like Random Forest or Gradient Boosting.
3.Incorporate real-time data processing for live fraud detection.

### Run the Project:
Ensure Fraud.csv is in the working directory and execute the main script to see the results.

### Contributing
Contributions are welcome! Please fork this repository and submit pull requests for any enhancements or bug fixes.
