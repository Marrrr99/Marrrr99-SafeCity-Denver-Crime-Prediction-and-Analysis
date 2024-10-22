# SafeCity Denver: Crime Prediction and Analysis using PySpark

This project analyzes a dataset of crimes in Denver using PySpark. The primary goal is to leverage machine learning models for crime classification and gain insights into patterns of criminal activity in Denver. The following steps were taken in the project:

## Steps of the Project:
1. *Data Cleaning*: Cleaning the dataset to handle missing and inconsistent data.
2. *Data Transformation*: Transforming the data into a suitable format for machine learning.
3. *Exploratory Data Analysis (EDA)*: Investigating trends and patterns in the crime data.
4. *Modeling*: Applying machine learning models for crime classification.

## Machine Learning Models

Two machine learning models were used to classify crimes:

### 1. RandomForestClassifier
The Random Forest algorithm was applied, and the model achieved an accuracy of *89.12%*. This model is effective in handling multi-class classification and provides reliable accuracy for crime prediction.

### 2. Multilayer Perceptron Classifier (MLP)
The Multilayer Perceptron (MLP), a neural network model, was also used, achieving an accuracy of *47.44%*. While the accuracy is lower compared to the Random Forest model, the MLP offers a deeper understanding of the data through its multiple layers.

## Results Summary
- *Random Forest Classifier Accuracy*: 89.12%
- *Multilayer Perceptron Classifier Accuracy*: 47.44%

## Conclusion
The Random Forest model outperformed the MLP in terms of accuracy, making it the better model for crime classification in this dataset. Future improvements can include tuning hyperparameters and exploring additional models to enhance accuracy.

## How to Run the Project
1. Install the required dependencies.
2. Run the PySpark environment.
3. Load the dataset and execute the provided code to clean, transform, and analyze the data.
4. Train and evaluate the machine learning models.
