# Prognosis Of Diabetic Readmission
## Data Mining Project


### 1. Introduction
The rising problem of early readmissions among diabetic patients presents formidable challenges for healthcare, resulting in complications and financial penalties. Our project seeks to forecast the combination of features that contribute to early hospital readmissions within a 30-day window, with a focus on addressing gaps in preventive care and enhancing patient outcomes. In contrast to conventional models, we delve into a range of machine learning approaches to gain deeper insights into the factors influencing early readmissions, creating a synergy between healthcare and data mining.

### 2. Background 
Diabetic patients frequently experience inadequate care, leading to complications and heightened hospital expenditures. The Center for Medicaid & Medicare Services (CMS) penalizes hospitals for elevated readmission rates, underscoring the financial impact and influencing quality ratings. Our project is dedicated to forecasting features that contribute early readmissions (within 30 days) for diabetic patients, addressing gaps in preventive care. In contrast to traditional regression models, we explore diverse models to gain a nuanced understanding of the factors contributing to early readmission. Positioned at the intersection of healthcare and data mining, this project aims to elevate patient outcomes, reduce costs, and optimize diabetes care practices.

### 3. Approach
** `Please review approach in report PDF` **

### 4. Results

Overall, the dataset's characteristics significantly influenced model performance. XGBoost's superiority diminished when tested on a small batch of a balanced dataset, emphasizing the importance of model selection based on dataset characteristics. Our confidence is bolstered by transparent documentation, a metric-aware approach, and a readiness to iteratively enhance our models based on observed limitations.

Naive Bayes:
Accuracy: 88.76%
Area under curve for Receiver Operating Characteristic: 56.75%

Support Vector Machine (SVM):
Accuracy: 88.76%
Area under curve for Receiver Operating Characteristic: 51.87%

Neural Networks:
Accuracy with least loss model: 88.75%
Area under curve for Receiver Operating Characteristic: 60%

Logistic Regression
Accuracy: 88.74%
Area under curve for Receiver Operating Characteristic: 51%

Random Forest: 
Accuracy: 89%
Area under curve for Receiver Operating Characteristic: 60%
XGBoost: 
Accuracy: 88.78%
Area under curve for Receiver Operating Characteristic: 62.93%

Comparison between methods:
Naive Bayes and SVM exhibit lower ROC-AUC scores.
Neural Networks and Logistic Regression show moderate ROC-AUC scores.
Random Forest demonstrates a balanced performance.
XGBoost outperforms other models with the highest ROC-AUC.

### Citation:
Centers for Disease Control and Prevention, “By the Numbers: Diabetes in America,” Centers for Disease Control and Prevention, 2022. https://www.cdc.gov/diabetes/health-equity/diabetes-by-the-numbers.html
Impact of HbA1c Measurement on Hospital Readmission Rates: Analysis of 70,000 Clinical Database Patient Records, Strack, DeShazo, Gennings, Olmo, Ventura, Cios,Clore, 2014.
Clore,John, Cios,Krzysztof, DeShazo,Jon, and Strack,Beata. (2014). Diabetes 130-US hospitals for years 1999-2008. UCI Machine Learning Repository. https://doi.org/10.24432/C5230J.
“Regularization in Machine Learning || Simplilearn,” Simplilearn.com. https://www.simplilearn.com/tutorials/machine-learning-tutorial/regularization-in-machine-learning#:~:text=ProgramExplore%20Program-
T. Kanstrén, “A Look at Precision, Recall, and F1-Score,” Medium, Oct. 31, 2020. https://towardsdatascience.com/a-look-at-precision-recall-and-f1-score-36b5fd0dd3ec
J. Brownlee, “SMOTE for Imbalanced Classification with Python,” Machine Learning Mastery, Jan. 16, 2020. https://machinelearningmastery.com/smote-oversampling-for-imbalanced-classification/

##### Authors: 
So Man Amanda Au Yeung
Yian Chen
Chun Wei Tseng
