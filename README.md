
# Lung Cancer Risk-Level Classification Using Machine Learning

## PROJECT OVERVIEW

This project focuses on classifying lung cancer risk levels using Machine Learning techniques and a structured tabular dataset.

The objective is to predict three risk categories: Low, Medium, and High based on demographic information, lifestyle factors, environmental exposure, and health-related symptoms.

## DATASET INFORMATION

- Total Records: 1,000
- Input Features: 23
- Target Variable: Level
- Classification Type: Multiclass Classification
- Target Classes: Low, Medium, High

Dataset Source: [Add the original Kaggle dataset URL here]

## TECHNOLOGIES USED

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- Joblib

## PROJECT WORKFLOW

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Feature Scaling
6. Train-Test Split
7. Model Training
8. Model Evaluation
9. Cross-Validation
10. Feature Importance Analysis
11. Final Model Saving

## MACHINE LEARNING ALGORITHMS

The following algorithms were implemented:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)

## MODEL EVALUATION

All five models achieved 100% accuracy on the evaluated 80/20 train-test split.

All five models also achieved 100% mean accuracy across 5-fold stratified cross-validation, with zero standard deviation.

These unusually perfect results require caution. They indicate strong separability within this particular dataset and do not establish real-world clinical performance.

## FEATURE IMPORTANCE

Random Forest feature importance analysis identified the following influential predictive features:

- Coughing of Blood
- Obesity
- Passive Smoker
- Wheezing
- Fatigue
- Smoking

These are dataset-specific predictive importance results, not evidence of medical causation.

## SAVED MODEL

The final SVM pipeline was saved using Joblib.

Files:
- lung_cancer_risk_svm.pkl
- lung_cancer_features.pkl

The SVM pipeline includes feature scaling and classification.

## PROJECT STRUCTURE

Lung-Cancer-Risk-Level-Classification/
│
├── Lung.ipynb
├── dataset.csv
├── lung_cancer_risk_svm.pkl
├── lung_cancer_features.pkl
├── requirements.txt
└── README.md

## LIMITATIONS

- This project uses a 1,000-record educational tabular dataset.
- The target variable represents Low, Medium, and High risk levels.
- The dataset is not established as a clinically validated patient dataset.
- Perfect classification results should not be interpreted as clinical accuracy.
- This model is intended for educational and portfolio purposes only.
- It must not be used for medical diagnosis or treatment decisions.

## CONCLUSION

This project demonstrates the implementation and comparison of multiple Machine Learning algorithms for multiclass risk-level classification using tabular data.

The project covers the complete machine learning workflow, from data exploration and feature engineering to model evaluation and saving the final trained model.
