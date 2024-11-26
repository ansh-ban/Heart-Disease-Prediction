Heart Disease Prediction Model
This repository contains a project that predicts whether a person has heart disease based on medical data using Logistic Regression. The implementation is built with Python, leveraging libraries like NumPy, Pandas, and Scikit-learn.

Features
Data Analysis and Processing: Load, inspect, and preprocess the dataset.
Model Training: Logistic Regression is used to build the prediction model.
Evaluation: Assess the model's accuracy on training and test datasets.
Prediction System: Use the trained model to predict heart disease for new data inputs.
Dataset
Source: The dataset used in this project contains 303 rows and 14 columns, including:
Medical attributes such as age, sex, chest pain type (cp), cholesterol level (chol), etc.
target: Label indicating heart disease presence (1) or absence (0).
Steps in the Project
Import Dependencies
Libraries used:

numpy: Array operations
pandas: Data loading and manipulation
scikit-learn: Model building and evaluation
Data Processing

Load the dataset (data.csv).
Check for missing values and ensure data integrity.
Split features (X) and labels (Y).
Split the data into training (80%) and test (20%) sets.
Model Training

Train a Logistic Regression model on the training data.
Model Evaluation

Evaluate the model on training and test sets using accuracy metrics:
Training Accuracy: 85.12%
Test Accuracy: 81.97%
Predictive System

Predict heart disease for a new data instance and output the result:
Input Example: (62,0,0,140,268,0,0,160,0,3.6,0,2,2)
Prediction Output: "The Person does not have Heart Disease"
How to Run
Clone the repository:
git clone https://github.com/ansh-ban/heart-disease-prediction.git
Install the required libraries:
pip install numpy pandas scikit-learn
Run the script:
python heart_disease_prediction.py
Dependencies
Python 3.x
NumPy
Pandas
Scikit-learn
Notes
Address convergence warnings by scaling the data or increasing max_iter for Logistic Regression.
Future improvements may include using advanced models like Decision Trees or Neural Networks.
Acknowledgments
This project is inspired by real-world datasets for educational purposes.
