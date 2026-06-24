# neurological-disease-prediction-
Machine Learning and Data Mining project for early detection of Parkinson's Disease, Alzheimer's Disease, and Epilepsy using classification, clustering, and association rule mining techniques. The project analyzes clinical and behavioral datasets to support early diagnosis and risk prediction.

Predictive Analytics for Early Detection of Neurological Conditions

Overview
This project applies Data Mining and Machine Learning techniques to detect neurological disorders such as Parkinson's Disease, Alzheimer's Disease, and Epilepsy at an early stage. The system analyzes patient clinical and behavioral data, identifies risk patterns, and predicts disease occurrence using multiple ML algorithms.

Objectives
Early prediction of neurological disorders.
Perform Exploratory Data Analysis (EDA).
Apply clustering techniques.
Generate association rules using Apriori Algorithm.
Compare multiple classification models.
Evaluate model performance using accuracy, ROC curves, and confusion matrices.
Datasets

The project uses three datasets:
Parkinson's Disease Dataset
Alzheimer's Disease Dataset
Epilepsy Dataset
Each dataset contains approximately 20,000 patient records.

Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-Learn
XGBoost
LightGBM
CatBoost
Mlxtend

Project Workflow
1. Data Preprocessing
Dataset loading
Missing value checking
Feature encoding
Feature selection
Data scaling

3. Exploratory Data Analysis
Univariate Analysis
Bivariate Analysis
Multivariate Analysis
Correlation Heatmaps

5. Clustering
K-Means Clustering
Hierarchical Clustering
DBSCAN Clustering

7. Association Rule Mining
Apriori Algorithm
Frequent Itemset Generation
Association Rule Extraction

9. Classification Models
Logistic Regression
Random Forest
Support Vector Machine (SVM)
Naive Bayes
Decision Tree
AdaBoost
Gradient Boosting
XGBoost
LightGBM
CatBoost

Results
Parkinson's Dataset Model Comparison
Model	Accuracy
AdaBoost	51.35%
XGBoost	50.75%
Gradient Boosting	50.38%
Logistic Regression	50.30%
Random Forest	50.20%
Best Performing Model: AdaBoost Classifier with 51.35% accuracy.

Key Findings
Clustering techniques did not clearly separate disease classes.
DBSCAN was effective for identifying outliers.
Apriori analysis showed weak associations among individual features.
Neurological disease prediction requires supervised learning approaches due to complex feature interactions.
Folder Structure
neurological-disease-prediction/
│
├── datasets/
│   ├── parkinsons_dataset.csv
│   ├── alzheimers_dataset.csv
│   └── epilepsy_dataset.csv
│
├── notebooks/
│   └── Neurological_Disease_Prediction.ipynb
│
├── images/
│   ├── roc_curve.png
│   ├── confusion_matrix.png
│   └── model_comparison.png
│
├── requirements.txt
├── README.md
└── LICENSE
