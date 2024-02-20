# Bank Customer Churn Prediction

## Overview
This project focuses on predicting customer churn in the banking sector using supervised learning techniques coupled with extensive feature engineering. By analyzing a comprehensive dataset from Kaggle, we aim to identify key factors influencing customer churn and provide actionable insights to reduce this churn rate.

## Dataset
The dataset includes information on customers' credit score, geography, gender, age, tenure, account balance, number of products used, credit card ownership, active membership status, estimated salary, and churn status. Additional features such as customer complaints, satisfaction scores, and card types are also included to enrich the analysis.

## Key Insights
- Certain demographic factors like age and geography significantly influence churn rates.
- Financial attributes such as account balance and number of products used are critical indicators of customer loyalty.
- Customer service metrics, specifically complaints and satisfaction scores, are directly correlated with churn.

## Methodology
1. **Exploratory Data Analysis (EDA):** Initial analysis to understand the dataset's structure, identify missing values, and observe the distribution of key variables.
2. **Feature Engineering:** Processing and transformation of variables to better highlight underlying patterns related to churn.
3. **Modeling:** Application of machine learning techniques to predict churn. The process involved handling imbalanced data, tuning model parameters, and evaluating model performance using metrics like precision and recall.
4. **Hyperparameter Tuning:** Utilizing Optuna for optimizing model parameters to improve prediction accuracy.

## Results
The model's performance was evaluated based on precision and recall metrics, balancing the need to accurately identify churn without overly predicting non-churn customers. Insights generated from the model emphasize the importance of targeted interventions for older customers and those with specific service complaints.

## Business Implications
- Tailored retention strategies can be developed for high-risk customer segments.
- Improvements in customer service could significantly reduce churn rates.
- Financial products and services can be better aligned with customer needs to enhance loyalty.

## Future Work
Further tuning of the model to address potential overfitting and exploration of additional features that may influence churn. Integration of more granular customer transaction data could also refine predictions.

## Technologies Used
- Python: For data processing and modeling.
- Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Imbalanced-learn, Optuna.

## How to Use
1. Clone the repository.
2. Install required Python packages.
3. Run the Jupyter notebooks to perform EDA, feature engineering, and model training.
