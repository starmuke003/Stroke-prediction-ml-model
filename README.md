# Development of a Machine Learning Model for Early Stroke Risk Prediction in Adults

## Project Overview

This project focuses on developing a machine learning model to predict stroke risk in adults using demographic and clinical health indicators.

The project explores healthcare data through data preprocessing, exploratory data analysis (EDA), feature selection, model development, and evaluation. The goal is to investigate how machine learning can be applied to support early stroke risk assessment.

This project was developed as part of a Computer Science research project with a case study focus on Lusaka, Zambia.

## Objectives

* Preprocess and prepare healthcare data for machine learning.
* Perform Exploratory Data Analysis (EDA) to identify patterns associated with stroke risk.
* Identify important features that contribute to stroke prediction.
* Develop a machine learning classification model using Random Forest.
* Evaluate the model using standard classification metrics.
* Prepare the trained model for potential integration into a software application.

## Key Features

The project explores demographic and clinical indicators including:

* Age
* Hypertension
* Heart disease
* Average glucose level
* BMI
* Gender
* Other relevant patient characteristics

Feature selection identified **Age, Hypertension, Heart Disease, Average Glucose Level, and BMI** as important predictors considered by the model.

## Machine Learning Approach

The project uses a machine learning pipeline built with Scikit-learn.

### Preprocessing

* Missing-value handling
* Numerical feature scaling using `StandardScaler`
* Categorical feature encoding using `OneHotEncoder`
* Feature preprocessing using `ColumnTransformer`

### Model

The primary classification algorithm used is:

**Random Forest Classifier**

The model was configured and evaluated as part of an end-to-end machine learning pipeline.

### Evaluation

Model performance was assessed using:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion matrix

## Exploratory Data Analysis

The analysis examined relationships between patient characteristics and stroke outcomes.

Two important patterns explored were:

### Age and Stroke Risk

Stroke cases were more concentrated among older adults, indicating age as an important predictor of stroke risk within the dataset.

### Average Glucose Level and Stroke Risk

The analysis showed differences in average glucose levels between patients with and without recorded stroke outcomes, highlighting glucose level as an important feature for further investigation.

## Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Scikit-learn**
* **Joblib**
* **Google Colab / Jupyter Notebook**

## Project Notebook

The main analysis and machine learning workflow is available in:

`stroke_prediction_model.ipynb`

The notebook contains the data preparation, exploratory analysis, model development, and evaluation workflow.

## Future Development

Potential future improvements include:

* Further model optimization and hyperparameter tuning
* Evaluation using additional healthcare datasets
* Improved handling of class imbalance
* Deployment of the trained model through an API
* Integration with the NeuroCare mobile application interface
* Further validation using locally relevant healthcare data

## Disclaimer

This project is intended for **academic and research purposes**. The model is not intended to provide medical diagnosis or replace professional medical assessment.
