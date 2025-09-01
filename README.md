# Titanic-Survival-Prediction

##  Project Overview
This project analyzes the Titanic passenger dataset to predict survival outcomes. Using exploratory data analysis (EDA), data cleaning, feature engineering, and machine learning models, the goal is to identify key factors that influenced passenger survival.

## Objective
- Understand the factors affecting Titanic passenger survival.
-Build predictive models to classify whether a passenger survived or not.
- Compare model performance and interpret results.

  
## Approach
###  1 - Data Loading & Exploration :
   - Loaded the Titanic dataset and examined data structure, missing values, and distributions.
### 2 - Data Cleaning & Preprocessing :
   - Handled missing values, encoded categorical variables, and normalized numerical features.
### 3 - Feature Engineering :
   - Created new features like FamilySize, Title extracted from names, etc.
### 4 - Model Building :
   - Tested multiple models including Logistic Regression, Decision Tree, Random Forest, and Gradient Boosting.
### 5 - Evaluation & Interpretation :
   - Evaluated models using accuracy, confusion matrix, and classification reports.
   - Visualized important features and insights from the dataset.

## Tech Stack
- Python
- Libraries: pandas, numpy, seaborn, matplotlib, scikit-learn, matplotlib
- Tools: Jupyter Notebook

## Highlights
- Thorough EDA with insightful visualizations (survival rates by gender, class, age, etc.).
- Implemented data cleaning and feature engineering to improve model performance.
- Built multiple predictive models and compared their results.
- Concluded with the best-performing model and actionable insights.

## Conclusion
- The Random Forest / Gradient Boosting model (whichever performed best) achieved the highest accuracy.
- Gender, passenger class, and age were key factors influencing survival.
- Potential improvements: hyperparameter tuning, cross-validation, and exploring ensemble methods for better prediction.
