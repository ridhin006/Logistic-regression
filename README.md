Breast Cancer Prediction Model
Overview:
This repository contains a machine learning model built using Logistic Regression to predict breast cancer based on a set of features in the dataset. The primary goal of the model
is to classify whether a breast tumor is malignant or benign using key attributes such as cell characteristics, tumor size, and other medical features.

Dataset
The dataset used in this project is the Breast Cancer Wisconsin (Diagnostic) Dataset, which is publicly available from the Kaggle https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data.

Number of features: 30 numeric features.
Target variable: The diagnosis of breast cancer (malignant or benign).
Classes:
Malignant (M)
Benign (B)
Features
The dataset includes the following features (attributes of cell nuclei):

radius (mean)
texture (mean)
perimeter (mean)
area (mean)
smoothness (mean)
And more...
Model
Logistic Regression
Logistic Regression is a statistical method that models the probability of a binary outcome. It is well-suited for medical diagnosis problems like breast cancer detection, where the goal is to classify cases into two categories (malignant vs. benign).

Model Workflow
Data Preprocessing:

Missing values handled (if any).
Features scaled using StandardScaler to normalize the input data.
Categorical variables (target) encoded using LabelEncoder.
Train-Test Split:

The dataset is split into training and testing sets using an 80-20 ratio for model evaluation.
Model Training:

Logistic Regression model is used as the classifier.
Hyperparameters tuned (if applicable).
Model Evaluation:

Performance evaluated using Accuracy, Precision, Recall, F1-Score, and a Confusion Matrix.




