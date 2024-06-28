# Heart Disease Risk Predication Project

## Overview 
This project is part of the final assignment of IronHack Data Analytics bootcamp, for the Data Science track. The objective is to predict the risk of heart disease in patients using various machine learning classifiers and to evaluate their performance. Given the critical nature of predicting heart disease, the focus is on models that provide high recall for identifying at-risk patients.

## Dataset
The dataset used for this project is titled heart_disease.csv and it is sourced from [Kaggle](https://www.kaggle.com/datasets/mirzahasnine/heart-disease-dataset?select=heart_disease.csv). It contains various features related to patients' health conditions and a target variable indicating the presence of heart disease.

### Features 
- Gender: The gender of the individual (male or female).
- Age: The age of the individual in years.
- Education: The highest level of education achieved by the individual.
- CurrentSmoker: Whether the individual is currently a smoker (1 if yes, 0 if no).
- CigsPerDay: The number of cigarettes smoked per day by the individual (if current smoker).
- BPMeds: Whether the individual is on blood pressure medication (1 if yes, 0 if no).
- PrevalentStroke: Whether the individual has previously had a stroke (1 if yes, 0 if no).
- PrevalentHyp: Whether the individual is hypertensive (1 if yes, 0 if no).
- Diabetes: Whether the individual has diabetes (1 if yes, 0 if no).
- TotChol: Total cholesterol level in mg/dL.
- SysBP: Systolic blood pressure in mmHg.
- DiaBP: Diastolic blood pressure in mmHg.
- BMI: Body mass index, a measure of body fat based on height and weight.
- HeartRate: Resting heart rate in beats per minute.
- Glucose: Blood glucose level in mg/dL.
- Heart_Stroke: History of heart attack or stroke (1 if yes, 0 if no).

## Methodology
### Data Preprocessing
1. Data Cleaning: Handle missing values and outliers.
2. Encoding: Convert categorical variables into numerical formats.
3. Normalization/Scaling: Normalize or scale the features for better model performance.
4. Handling Imbalance: Use SMOTE (Synthetic Minority Over-sampling Technique) to balance the target variable.

## Exploratory Data Analysis (EDA)
1. Descriptive Statistics: Summary statistics of the dataset.
2. Data Visualization: Visualize the distribution of features and the target variable.
3. Correlation Analysis: Examine correlations between features and the target variable.

### Model Building
1. Logistic Regression
2. Decision Tree
3. Random Forest

### Model Evaluation
- Accuracy: The ratio of correctly predicted instances to the total instances.
- Confusion Matrix: A table to describe the performance of a classification model.
- Precision: The ratio of correctly predicted positive observations to the total predicted positives.
- Recall: The ratio of correctly predicted positive observations to all observations in the actual class.
- F1-Score: The harmonic mean of precision and recall.
- ROC-AUC: The area under the Receiver Operating Characteristic curve.

## Results
### Logistic Regression
- Accuracy: 0.62
- Confusion Matrix: [[445, 260], [59, 67]]
- Classification Report: Precision, recall, and F1-score for both classes.
- ROC-AUC: 0.64

### Decision Tree
- Accuracy: 0.68
- Confusion Matrix: [[530, 175], [94, 32]]
- Classification Report: Precision, recall, and F1-score for both classes.
= ROC-AUC: 0.50

### Random Forest
- Accuracy: 0.79
- Confusion Matrix: [[628, 77], [95, 31]]
-  Report: Precision, recall, and F1-score for both classes.
-  ROC-AUC: 0.65

### Conclusion
Given the importance of identifying patients at risk of heart disease, Logistic Regression is preferred due to its higher recall for the positive class (patients at risk). This ensures that more at-risk patients are correctly identified, which is critical in a life/death scenario.

## Presentation
Presentation: [Heart Disease](https://www.canva.com/design/DAGJYpf-X3o/oFpB6XnRiEzkf_t663EGng/edit?utm_content=DAGJYpf-X3o&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)
