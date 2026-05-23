# Task 3: Loan Approval Prediction

## Objective
The objective of this task is to build a supervised machine learning model to predict loan approval status using borrower and loan-related features.

## Dataset
The dataset contains loan applicant details such as gender, marital status, dependents, education, employment status, income, loan amount, loan term, credit history, property area, and loan approval status.

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab
- GitHub

## Work Performed
- Loaded and explored the loan approval dataset
- Handled missing values
- Encoded categorical variables
- Created new features such as Total Income
- Applied log transformation
- Scaled features using StandardScaler
- Handled class imbalance using class weights
- Trained Logistic Regression, Decision Tree, and Random Forest models
- Evaluated models using precision, recall, F1-score, and ROC-AUC
- Performed threshold tuning
- Prepared business-oriented interpretation

## Model Performance

| Model | Accuracy | Precision | Recall | F1 Score | ROC-AUC |
|---|---:|---:|---:|---:|---:|
| Logistic Regression | 0.8293 | 0.8721 | 0.8824 | 0.8772 | 0.8632 |
| Decision Tree | 0.7642 | 0.8590 | 0.7882 | 0.8221 | 0.7494 |
| Random Forest | 0.8699 | 0.8710 | 0.9529 | 0.9101 | 0.8550 |

## Best Model
Random Forest was selected as the best model based on F1-score. It achieved the highest accuracy, recall, and F1-score among the compared models.

## Threshold Recommendation
A threshold of 0.50 is recommended for initial deployment because it achieved the best F1-score of 0.9101.

For a more conservative approval strategy, a threshold of 0.60 can be considered because it improves precision, but it may reduce recall.

## Business Interpretation
The model can support loan approval decision-making by identifying applicants likely to be approved. However, it should be used as a decision-support tool along with manual review, policy checks, and risk assessment.

## Deliverables
- Colab Notebook
- Model Evaluation Report
- Screenshots / Visualizations
