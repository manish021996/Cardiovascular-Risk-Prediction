# Cardiovascular-Risk-Prediction

## Project Summary -
This project utilizes data from an ongoing cardiovascular study conducted in Framingham, Massachusetts, consisting of over 4,000 records with 15 attributes.

The main objective is to predict a patient's 10-year risk of future coronary heart disease (CHD) using various demographic, behavioral, and medical risk factors.

After evaluating multiple machine learning models, including LogisticLigression,Decision Tree, Random Forest, XGBOOST, and KNN, Naive Bayes and SVM with GridSearchCV, the best-performing models were identified based on high recall scores.

The key important features influencing the prediction include age, heart_rate, total_cholesterol, Cigs_per_day, and education, providing valuable insights for assessing and managing CHD risk in patients.

## Problem Statement
The classification goal is to predict whether the patient has a 10-year risk of future Cardiovascular Disease (CVD) considering the other features.

Though CVDs cannot be treated, predicting the risk of the disease and taking the necessary precautions and medications can help to avoid severe symptoms and, in some cases, even death.

As a result, it is critical that we accurately predict the risk of heart disease in order to avert as many fatalities as possible.

## Conclusion
### EDA Insight:

#### Distribution Conclusions :

* Majority of patients have education level 1 and are female.
* Smokers and non-smokers are almost evenly split.
* Approximately 100 patients take BP medication.
* About 22 patients have experienced a stroke.
* Around 1100 patients have hypertension, and 87 patients are diabetics.

#### Risk of Coronary Heart Disease (CHD) :

* Males have a higher risk (19%) compared to females (12%).
* Smokers have a higher risk (16%) compared to non-smokers (14%).
* Patients on BP medication have a significantly higher risk (33%) compared to others (15%).
* Patients who had a stroke have a higher risk (45%) compared to others (15%).
* Hypertensive patients have a higher risk (24%) compared to others (11%).
* Diabetic patients have a higher risk (38%) compared to others (11%).
  
#### General Conclusions :

* 15% of patients were exposed to CHD risk after a 10-year study.
* Data imbalance exists in the dependent variable.
* Positive correlations between 'is_smoking' and 'cigs_per_day' as well as 'systolic_bp' and 'diastolic_bp'.
* Blood pressure influences hypertension development/management.
* Age group around 40 years is most prevalent.
* Patients who smoke consume an average of 10 cigarettes per day.
  
### ML Models:


