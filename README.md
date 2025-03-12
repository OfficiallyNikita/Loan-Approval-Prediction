# Loan-Approval-Prediction
This project focuses on predicting loan approval status based on applicant details using machine learning techniques.
<br>
## </h>📌Project Overview <br>
 </p>The dataset consists of various financial and demographic attributes such as applicant income, credit history, loan amount, and more. The goal is to preprocess the data, perform exploratory data analysis (EDA), and apply machine learning models to predict whether a loan will be approved or not. <p>
<br>
  
## 📌Dataset Description <br> 
The dataset contains 614 entries with 13 columns, including: <br>
Loan_ID: Unique identifier for each loan application. <br>
Gender: Applicant’s gender (Male/Female). <br>
Married: Marital status of the applicant. <br>
Dependents: Number of dependents. <br>
Education: Educational background (Graduate/Not Graduate). <br>
Self_Employed: Whether the applicant is self-employed. <br>
ApplicantIncome: Monthly income of the applicant. <br>
CoapplicantIncome: Monthly income of the co-applicant. <br>
LoanAmount: Amount of loan requested. <br>
Loan_Amount_Term: Duration of the loan in months. <br>
Credit_History: Whether the applicant has a credit history (1: Yes, 0: No). <br>
Property_Area: Type of property area (Urban, Semiurban, Rural). <br>
Loan_Status: Loan approval status (Y: Approved, N: Not Approved) (Target Variable).   <br>

## </h> 📌  Exploratory Data Analysis (EDA)
 </p> # Visualized distributions of numerical features. <br>
# Checked the correlation between loan approval status and key features.<br>
# Identified patterns in income, loan amount, and credit history. <br>
<br>
 
## </h> 📌 Model Preparation
 </p>Feature Selection: Selected relevant columns for prediction.
Encoding Categorical Data: Converted categorical variables into numerical format.
Splitting Data: Separated independent (X) and dependent (y) variables. <p>
  <br>
 
## </h> 📌  Machine Learning Model
 </p>The dataset was prepared for machine learning using Support Vector Machine (SVM) to predict Loan_Status.
Further models like Logistic Regression, Decision Tree, and Random Forest can be implemented to improve accuracy. <p>

## Conclusion <br>
The Loan Approval Prediction model successfully classifies loan applications based on applicant details, improving decision-making in the loan approval process. By leveraging SVM and data preprocessing techniques, the model achieves a reliable accuracy, aiding financial institutions in assessing credit risk efficiently. Further improvements can be made by incorporating advanced feature engineering and optimizing hyperparameters for better performance.
