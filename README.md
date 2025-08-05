# Personal Loan Acceptance Prediction

## Project Description  
This project aims to **predict whether a customer is likely to accept a personal loan offer** using classification models. The dataset is based on real-world marketing data collected from a Portuguese banking institution.

## Objective  
- Predict customer response to personal loan offers  
- Identify key customer characteristics that influence acceptance  
- Provide actionable insights to support marketing strategies using machine learning  

## Dataset Information  
- **Source**: UCI Machine Learning Repository – Bank Marketing Dataset  
- **File Used**: `bank-full.csv`  

## Project Steps

1. **Data Loading and Exploration**  
   Load the dataset and explore its structure, dimensions, and basic statistics.

2. **Understand Dataset Structure**  
   Review column names, data types, and identify potential issues (such as missing values).

3. **Visualize Key Features**  
   Use plots to explore important features such as:
   - Age distribution  
   - Job categories  
   - Marital status  
   - Loan acceptance by job

4. **Data Preprocessing**  
   Prepare the data for modeling by:
   - Encoding categorical features using Label Encoding  
   - Handling any inconsistencies or irrelevant data  

5. **Train-Test Split**  
   Split the dataset into training and test sets (e.g., 80/20 ratio).

6. **Modeling**  
   Train a classification model. This project uses:
   - Logistic Regression Classifier

7. **Evaluation**  
   Evaluate model performance using:
   - Accuracy score  
