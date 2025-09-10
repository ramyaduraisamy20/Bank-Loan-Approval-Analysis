This project predicts bank loan approval status based on customer and financial data. It begins with a logistic regression baseline model and later improves performance using a Random Forest Classifier.
Project Overview
  Banks face risks when approving loans. Identifying whether a loan applicant is likely to be approved or rejected helps in:
  Reducing default risks
  Automating loan approval processes
  Supporting better decision-making
  This project applies supervised machine learning to predict loan approval.
I started with Logistic Regression as a baseline model to understand the dataset and evaluate performance. Logistic Regression gave an accuracy of around 73%, but it struggled to correctly classify rejected loans. 
To improve this, I applied a Random Forest Classifier, which captured the complex patterns much better and achieved an impressive 97.6% accuracy, with cross-validation confirming a stable performance of ~98.3%.

Dataset
  The dataset contains information about loan applicants, such as:
  Demographic details (education, employment status, dependents)
  Financial information (income, loan amount, loan term, credit score, assets)
  Target variable: loan_status (Approved / Rejected)

Steps in the Project
Data Cleaning & Preprocessing
  Removed duplicates and missing values
  Converted categorical values into numeric form (e.g., Approved = 1, Rejected = 0)
Exploratory Data Analysis (EDA)
  Histograms and boxplots for numerical features
  Countplots for categorical features
  Correlation heatmap to understand relationships between features
Modeling
  Logistic Regression: baseline model, accuracy ~73%
  Random Forest Classifier: improved model, accuracy ~97.6% and strong performance on both approved and rejected loans

Results
Logistic Regression: struggled with rejected loans (low recall)
Random Forest: balanced and highly accurate, confirmed with cross-validation (~98.3%)

This shows that tree-based models handle non-linear patterns in financial data better than simple linear models.
