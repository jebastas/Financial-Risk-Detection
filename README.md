# Financial-Risk-Detection

Overview:
This project focuses on leveraging machine learning techniques to detect financial risk in the context of loan default prediction for a consumer finance company. By analyzing historical loan application data and building predictive models, we aim to identify patterns and factors indicative of potential loan defaults, ultimately assisting the company in minimizing financial losses while ensuring fair and responsible lending practices.

Project Structure:

Data Collection:
Utilized two primary datasets: application_data.csv containing information about loan applicants and previous_application.csv providing historical loan application data.

Data Preprocessing:
Performed data cleaning and preprocessing steps, including handling missing values, encoding categorical variables, and feature selection.

Exploratory Data Analysis (EDA):
Conducted EDA to gain insights into the distribution of variables, identify correlations, and understand the relationship between features and the target variable (loan default).

Insights:
1.Client Profile Analysis
 1. Demographic Analysis Code Gender– F(0.053068), M(0.068934)
 2. Default rates based on Educational level – Lowest Secondary has the highest rate with 0.087514
 3. Default rates based on Employment level – waiters/ barmen staff has the highest rate when compared to others.
 4. Income Distribution of Default vs. Non-Default Clients – Non-Default has the highest value.
    
2. Financial Analysis
 1. Default Rates Vs. Approval Rates
![image](https://github.com/jebastas/Financial-Risk-Detection/assets/128833690/973ce4ca-2e00-49f7-8eb4-ebea48fb27ae)
 2. Income distribution among loan applicants
![image](https://github.com/jebastas/Financial-Risk-Detection/assets/128833690/a88b66f5-861e-43b2-b3af-7257d5fef39c)
3. Relationship between loan amount and income
![image](https://github.com/jebastas/Financial-Risk-Detection/assets/128833690/693443be-3638-4c86-b16c-992a61232c62)

3. Credit History Analysis
 1. Relationship between number of inquiries and past defaults
    ![image](https://github.com/jebastas/Financial-Risk-Detection/assets/128833690/7348f63e-4892-4652-a5b6-cfd9cb2601f2)
 2. Relationships between credit risk and reasons for rejection
    ![image](https://github.com/jebastas/Financial-Risk-Detection/assets/128833690/2e263cdb-2dcd-425b-b806-805892ff577c)
 3. Relationship between type and length of credit history and default risk
    ![image](https://github.com/jebastas/Financial-Risk-Detection/assets/128833690/23df998d-082a-40d7-b0d3-d572cd92e0e9)

4.  Loan Application Decisions Analysis
  1. Approval Rates by Loan Type
     ![image](https://github.com/jebastas/Financial-Risk-Detection/assets/128833690/1a893104-76b4-49b4-8e48-b91b30f099e4)
  2. Weekday of Application vs. Default Rate
  ![image](https://github.com/jebastas/Financial-Risk-Detection/assets/128833690/023dd38a-5266-4b9e-8aed-b68aec1458d2)

Model Building:
Implemented a Random Forest Classifier, a machine learning algorithm suitable for classification tasks, to predict loan default risk.

Model Evaluation:
Evaluated the performance of the trained model using metrics as confusion matrix to assess its effectiveness in predicting loan defaults.

Prediction and Accuracy Assessment:
Utilized the trained Random Forest Classifier to predict loan default risk for new loan applications.
Validated model performance on unseen data to ensure robustness and reliability.

Conclusion:
Summarized the project outcomes, including enhanced risk assessment, gained insights, operational efficiency.
