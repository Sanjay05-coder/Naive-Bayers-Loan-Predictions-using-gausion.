
# Loan Prediction using Naive Bayes

## Overview
This project demonstrates the use of the **Naive Bayes algorithm** for predicting loan approval status based on selected applicant features. 

## Dataset
The dataset includes features such as:  
- Gender  
- Marital Status  
- Dependents  
- Education  
- Self Employment Status  
- Property Area  
- Loan Amount  
- Loan Term  
- Credit History  

## Methodology
1. **Data Cleaning & Preprocessing**
   - Handling missing values using median, mode, or a default value where appropriate.  
   - Encoding categorical features using `LabelEncoder` to convert them into numeric form.  

2. **Model Training**
   - The Naive Bayes classifier was trained on the preprocessed training dataset.  
   - Categorical and numerical features were included to improve prediction accuracy.

3. **Evaluation**
   - The model achieved an **accuracy of 66.67%**.  
   - The **confusion matrix** highlights the types of prediction errors.  
   - Despite reasonable performance, further tuning and feature engineering could improve results.


