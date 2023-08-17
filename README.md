# Titanic Survival Prediction
![RMS Titanic](https://upload.wikimedia.org/wikipedia/commons/6/6e/RMS_Titanic_3.jpg)
## Introduction
This repository contains a machine learning project that focuses on predicting the survival status of passengers aboard the Titanic using various data analysis and machine learning techniques. The dataset used for this project is sourced from the Kaggle competition "Titanic: Machine Learning from Disaster."

## Project Overview
The project involves the following key steps:

1. **Data Loading and Exploration:** The initial step involves loading the dataset and gaining an understanding of its structure and content.

2. **Data Cleaning:** This step focuses on handling missing values and removing unnecessary columns that don't contribute to the prediction.

3. **Feature Engineering:** Categorical features are transformed into numerical format using one-hot encoding to prepare the data for modeling.

4. **Data Splitting:** The dataset is split into training and testing sets to evaluate the model's performance.

5. **Model Building and Evaluation:** Logistic Regression and Support Vector Machine (SVM) models are trained on the training data and evaluated using various performance metrics.

6. **Handling Class Imbalance:** To tackle class imbalance, Random Oversampling is applied to the training data, followed by retraining and evaluation of the Logistic Regression and SVM models.

7. **Improving SVM Performance:** The SVM model's performance is improved by adjusting class weights and evaluating its impact on accuracy and other metrics.

8. **Visualization:** Visualizations such as bar plots are used to showcase the distribution of survival classes and the comparison of actual vs. predicted outcomes.

## Requirements
- Python 3.x
- Jupyter Notebook
- Required Python libraries (numpy, pandas, scikit-learn, seaborn, matplotlib, imbalanced-learn)


## Usage
1. Clone the repository: `git clone https://github.com/yadus1111/Titanic_Survival_Prediction.git`
2. Navigate to the project directory: `cd Titanic_Survival_Prediction`
3. Install the required libraries: `pip install -r requirements.txt`

## Results
The project demonstrates the predictive power of machine learning models in determining passenger survival on the Titanic. It showcases different techniques to handle class imbalance and improve model performance.

## Conclusion
This project provides valuable insights into the data preprocessing, feature engineering, model selection, and evaluation process. By addressing class imbalance and optimizing model parameters, the project aims to improve the accuracy and reliability of predictions.
