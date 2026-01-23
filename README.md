\# EasyVisa – Visa Approval Prediction



\## Project Overview

This project applies machine learning techniques to predict visa application approval outcomes based on applicant demographics, education, job experience, and employment-related attributes. The objective is to support more consistent, data-driven certification decisions by identifying key approval drivers and high-risk cases early in the process.



---



\## Business Problem

Visa certification decisions involve evaluating multiple applicant and employer-related factors and can be time-consuming and inconsistent. The goal of this project is to build predictive models that estimate approval likelihood, helping decision-makers prioritize applications and improve operational efficiency.



---



\## Dataset

The dataset consists of historical visa application records containing:

\- Applicant demographics and education level  

\- Job experience and employment characteristics  

\- Employer-related attributes  

\- Target variable indicating visa \*\*approval\*\* or \*\*denial\*\*



The data represents a \*\*binary classification\*\* problem with class imbalance.



---



\## Approach

The project follows an end-to-end data science workflow:

1\. Data cleaning and preprocessing  

2\. Exploratory Data Analysis (EDA)  

3\. Feature engineering and transformation  

4\. Handling class imbalance  

5\. Model training and evaluation  

6\. Model explainability and interpretation  



---



\## Models Used

The following supervised and ensemble learning models were trained and evaluated:

\- Logistic Regression  

\- Decision Tree  

\- Bagging Classifier  

\- AdaBoost  

\- Gradient Boosting  

\- XGBoost  

\- Stacking Ensemble  



---



\## Model Evaluation

Given the imbalanced nature of the dataset, model performance was evaluated using:

\- Precision  

\- Recall  

\- \*\*F1-score\*\* (primary metric)  

\- ROC-AUC  



Cross-validation and threshold tuning were applied to balance predictive performance with business relevance.



---



\## Results

The final stacked ensemble model achieved:

\- \*\*F1-score:\*\* 0.83  

\- \*\*ROC-AUC:\*\* 0.79  



Model explainability techniques (SHAP) were used to identify key drivers of visa approval decisions, enabling transparent interpretation of model outputs for decision support.



---



\## Key Insights

\- Higher education levels and relevant job experience significantly increase approval likelihood  

\- Certain job categories consistently show higher approval rates  

\- Explainable ML techniques improve transparency and trust in predictive outputs  



---



\## Limitations \& Future Improvements

\- Incorporate additional employer-level and historical trend data  

\- Apply time-based validation to account for policy changes  

\- Deploy the model as a batch scoring pipeline or API for real-world use  



---



\## Repository Structure



easyvisa-approval-prediction/

├── README.md

├── LICENSE

├── Data/

│   └── EasyVisa.csv

├── Notebooks/

│   ├── Notebook\_EasyVisa.ipynb

│   └── Notebook\_EasyVisa\_Sayan.html

├── Project\_Summary.pdf

└── Requirements.txt

---



\## Data Source \& Usage

The dataset used in this project was provided by \*\*Great Learning\*\* as part of the \*Post Graduate Program in Data Science and Business Analytics\* for academic and educational purposes.



This dataset is included solely to demonstrate the analytical methodology, modeling approach, and interpretation of results. The MIT License included in this repository applies \*\*only to the code, notebooks, and documentation\*\*. All rights to the dataset remain with the original data provider.



---

