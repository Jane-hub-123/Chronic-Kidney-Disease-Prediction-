# Chronic-Kidney-Disease-Prediction

A Machine Learning Approach to Early Detection and Stage Classification of Chronic Kidney Disease

## Project Definition 
This project focuses on predicting Chronic Kidney Disease (CKD) using machine learning techniques. The goal is to build a model that can classify whether a patient has CKD based on medical attributes.

Early detection of CKD can help improve treatment outcomes and reduce complications.

This project addresses the need for an automated, data-driven tool that can accurately predict both the presence of CKD and its stage of progression using Machine learning techniques.The goal is to build come up with the best model that can classify whether a patient has Chlonic Kidney Disease and it stage . It is a multi-class classification task across five categories: Healthy Kidney, Mild CKD (Stage 1-2), Moderate CKD (Stage 3), Severe CKD (Stage 4), and Kidney Failure (Stage 5).
A key analytical challenge inherent in this dataset is class imbalance: approximately 75% of training records represent healthy patients, which risks biasing models toward the majority class. Addressing this challenge is central to the methodological design of this project.

##  Dataset Description
The dataset Is from Kaggle and it contains the train data set and the test data sets which contains medical information used to predict kidney disease.

Files included:
- Training_CKD_dataset.csv
- Testing_CKD_dataset.csv

Key features include:
- Blood pressure
- Serum creatinine
- eGFR
- Urine protein levels
- Family history
- Other clinical indicators

## Objectives
-Preprocess and validate the CKD dataset for modelling readiness
-Identify the most significant clinical predictors of CDK through statistical analysis 
-Build and evaluate 3 classical machine learning models for multi-class CDK stage prediction  



Clean and preprocess the dataset
- Handle missing values and categorical variables
- Build a machine learning model for classification
- Evaluate model performance using appropriate metrics
- Make predictions on test data

---

##  Tools and Libraries Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn
- Tensor flow and Keras

---

##  Project Workflow
1. Data loading and exploration
2. Data cleaning and preprocessing
3. Feature engineering
4. Encoding categorical variables
5. Standardization of numerical features
6. Trained and evaluated: Logistic Regression, XGBoost, and a Neural Network-based Deep Learning model.
7. Model evaluation (accuracy, precision, recall, F1-score)
8.  Deployment 


##  Model Evaluation
The model was evaluated using:
- Accuracy Score
- Confusion Matrix
- Precision, Recall, and F1-score

##  How to Run the Project
git clone https://github.com/Jane-hub-123/Chronic-Kidney-Disease-Prediction-.git


## Results /Findings
 -The confusion matrix showed zero misclassifications across all 4,800 test samples.
 -Both Logistic Regression and a Deep Neural Network (with BatchNorm + Dropout + EarlyStopping) achieved perfect scores.
 -The DNN converged very quickly to near-perfect validation accuracy by Epoch 2 to 3. 

## Future improvements 
 -Validate on real-world data - Perfect scores are a red flag for data leakage or synthetic data; test on clinical/external datasets.

## Author 
-Jane Ndwigah 
-Caroline Kipruto
-Frackline Keraro