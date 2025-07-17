<img width="990" height="360" alt="image" src="https://github.com/user-attachments/assets/7049aa2c-06a4-48b4-a6a6-d7c028049866" />

<h1 align="center">ML NLP Project for Career Level Prediction</h1>

<h4><u>Objective :</u></h4> 
Build a machine learning model to perform <b>NLP</b> based on a private dataset from a company of recruitment. Project done in python on jupyter notebook.

# Table of Contents

- [A. Pipeline Overview](#apipeline-overview)
  - [A.1. Data Import](#a1-data-import--from-kaggle)
  - [A.2. Exploratory Data Analysis (EDA) & Data Visualization](#a2-exploratory-data-analysis-eda--data-visualization)
  - [A.3. Data Preprocessing](#a3-data-preprocessing)
  - [A.5. Model Training](#a5-model-training)
  - [A.6. Model Evaluation](#a6-model-evaluation)
  - [A.7. Model Deployment](#a7-model-deployment--not-included)
- [B. Prediction Model Summary](#b-the-file-summarizing-the-prediction-models-includes-the-accuracy-f1-score-and-time-taken-parameters-and-prediction-execution-time-based-on-this-dataset)
  - [B.1. Score metrics and confusion matrix](#b1-score-metrics-and-confusion-matrix)
  - [B.2. Quickly check other models](#b2-quickly-check-other-models-through-accuracy-roc-auc-f1-score)
- [C. Results](#c-results)


# A.Pipeline-Overview

1. **Data Import** : from Kaggle
2. **Exploratory Data Analysis (EDA) & Data Visualization**  
   - Check for missing values
   - Delete lines containing NaN values
   - Synchronize a class name in the target column from German to English
   - Filter and remove/retain geographically redundant values
3. **Data Preprocessing**
   - Chi square
   - Deleting/Keeping unnecessary features according to SelectKBest and SelectPercentile
   - Train/Test split
   - GridSearchCV to find the bests hyperparameters
5. **Model Training** 
   - Random Forest
   - Decision Tree  
   - SVC
   - GaussianNB
   - KNN
6. **Model Evaluation** 
   - Accuracy, Precision, Recall, F1-score  
   - Classification report  
   - Confusion matrix
   - ROC AUC
7. **Model Deployment** : not included


# B. The file summarizing the prediction models includes the Accuracy, F1 score and Time Taken parameters and prediction execution time based on this dataset. 

#### B.1. Score metrics and confusion matrix
<img width="889" height="590" alt="image" src="https://github.com/user-attachments/assets/c264db63-6bcf-4e3d-8de3-bee7ee4b6f84" />

<img width="1273" height="1090" alt="image" src="https://github.com/user-attachments/assets/58a1a534-9059-43a5-b4fe-c63686f41069" />




#### B.2. Quickly check other models through Accuracy, ROC AUC, F1 Score

<img width="375" height="133" alt="image" src="https://github.com/user-attachments/assets/06420c77-a076-42df-a5c7-e67ab9173aaa" />


# C. Results
- All models were trained and evaluated to identify the best-performing one for this multiclass classification of NLP task.
- Reusability on other datasets thanks to calling the pickle library to store the models.
