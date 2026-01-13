# Clinical-Patients-Outcome-Prediction-SUPPORT-II-
This project analyzes the SUPPORT II clinical trial dataset to predict treatment outcomes and survival probabilities for seriously ill hospitalized patients, helping healthcare providers make informed decisions about end-of-life care and resource allocation strategies. 

The objective of this report is to understand the treatment outcomes and prognosis of seriously ill
hospitalized patients. This research improves decision-making ability in patients at the end of life
when they have little control over their physical and mental state, thereby reducing chronic pain
and a prolonged dying process. Support II, the study includes an intervention that provided the
doctors or physicians with accurate predictive results on patients’ survival chances at two months
and six months.

**Definition**
In the Exploratory Data Analysis (EDA) of support II, the main objective is to use patient
demographic data to predict the outcome of prognosis at the end-of-life care. I have engineered
four different models to check for the best suited model and predict the outcome. Target variable
in this dataset falls into categorical data hence Logistic Regression, Gradient Boosting, SVM and
Random Forest models were used. 

**Data Collection**
The Exploratory Data Analysis was engineered in an open-source integrated development
environment (IDE), JupyterLab within the code was written in Jupyter Notebook.
The dataset has been extracted and imported from the ucimlrepo package using pip3 command
with dataset of id = 880. The dataset contains 9105 instances with 47 variables. 

**Analysis Findings**
1. Identified strong associations between disease category and survival outcomes; patients in Coma and MOSF with malignancy groups showed consistently lower 2- and 6-month survival probabilities compared to other disease groups.
2. Observed gender-based differences where male patients exhibited slightly higher 2- and 6-month survival probabilities, while hospital mortality rates were marginally higher among female patients.
3. Correlation analysis revealed redundancy among cost-related and physiological variables, leading to feature reduction to minimize multicollinearity and noise in modeling.
4. Gradient Boosting outperformed Logistic Regression, Random Forest, and SVM models for both survival targets, indicating its effectiveness on mixed clinical tabular data.
5. Model outputs demonstrated high discriminatory power via ROC curves for both 2-month and 6-month survival predictions, supporting reliability of the predictive framework.

**Future Work**
1. Apply advanced imputation techniques such as multiple imputation or model-based methods to reduce bias introduced by high missingness.
2. Perform model explainability using SHAP or feature importance to improve clinical interpretability and physician trust.
3. Extend the framework into a decision-support prototype that simulates how predictive outputs could guide end-of-life care planning and resource utilization.


