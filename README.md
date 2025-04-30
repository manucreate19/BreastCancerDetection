BREAST CANCER PREDICTION USING LOGISTIC REGRESSION


Introduction

Breast cancer is one of the most common types of cancer, and early detection plays a crucial role in increasing survival rates. This project aims to build a machine learning model using Logistic Regression to predict whether a tumor is malignant or benign based on input features.


Objectives

Develop a predictive model for breast cancer classification.
Preprocess the dataset to handle missing values and improve accuracy.
Train a Logistic Regression model using labeled data.
Evaluate model performance using key classification metrics.
Deploy the model as a web application using Flask.


Methodology
1. Dataset Handling
Load the dataset.
Check for missing values and handle them appropriately.
Remove duplicate records to ensure data integrity.
2. Data Preprocessing
Map categorical labels: Convert 'M' (Malignant) to 1 and 'B' (Benign) to 0.
Train-test split: Divide the dataset into training and testing sets.
Apply Label Encoding where necessary.
Feature scaling: Use StandardScaler to normalize the feature values.
3. Model Training
Use Logistic Regression as the classification model.
Train the model using the training dataset.
Evaluate the model using metrics like accuracy, precision, recall, F1-score, and confusion matrix.
4. Model Deployment
Save the trained model as a .pkl file using Pickle.
Integrate the model with a Flask web application.
Build a user-friendly website where users can input data and get predictions.
Host the application on a local server platform.


Advantages
Early Detection: Helps identify breast cancer at an early stage, improving survival rates.


Efficiency: Automates diagnosis, reducing the workload for medical professionals.


User-Friendly: Provides an accessible web-based interface for easy predictions.


Conclusion
This project demonstrates how Machine Learning can be applied to healthcare for early breast cancer detection. It covers data preprocessing, model training, evaluation, and deployment as a web application using Flask. With further improvements, this system can serve as an effective diagnostic aid. 

