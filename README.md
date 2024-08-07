### CSC 6621 Final Project: Predicting Patient Readmission Rates using Random Forests and Gradient Boosting 

- **Brief Description**: predict hospital readmission rates for patients using Random Forests and Gradient Boosting algorithms. The goal is to identify high-risk patients and provide them with additional care to prevent readmission.
- **Data**: https://data.cms.gov/provider-data/dataset/9n3s-kdb3
- **Preprocessing**: To prepare the dataset, we will start by cleaning the data, handling missing values, and converting date columns to a usable format. We will create new features such as the duration of the observation period and encode categorical variables like facility name, state, and measure name. Numerical features such as number of discharges and predicted readmission rate will be normalized to ensure consistent scaling. Finally, we will define the target variable, likely based on number of readmissions or excess readmission ratio, to train the models effectively.
- **Baseline Model**:
    - Model: Linear Regression - start with using basic features
    - Evaluation Metrics: Accuracy, R^2 score
- **Optimized and Improved Model**:
    - Model: Random Forests and Gradient Boosting (e.g., XGBoost) - Use Random Forests for initial improvement and then apply Gradient Boosting (e.g., XGBoost) if necessary for better performance. Incorporate feature selection techniques to identify the most relevant features and perform hyperparameter tuning.
    - Fine-tune the number of trees, maximum depth, learning rate, and other hyperparameters. Use cross-validation for model evaluation and feature engineering to create new, informative features
    - Evaluation Metrics: Improved accuracy, R^2 Score
- **Experimental Models**: 
    - This is to test the robustness of our Random Forest model and to help identify the optimal approach for predicting readmission rates, and to balance model complexity as well. There are three experimental models:
        - Increasing the Train-Test Split Ratio
        - Omitting Feature Engineering
        - Implementing a Simple Neural Network


##### Authors:
- Ben Paulson
- Ethan Traas
- Sumedha Sanjeev


##### Project authored for:
- CSC 6621: Applied Machine Learning @ Milwaukee School of Engineering
- Summer 2024
- Professor: Dr. Sebastian Berisha