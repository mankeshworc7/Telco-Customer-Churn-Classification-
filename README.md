This project demonstrates a full machine learning pipeline for predicting customer churn in a telecom company using Python and Scikit-Learn. It follows industry-standard practices for preprocessing, model building, evaluation, and deployment.

Key Features:

- End-to-end pipeline: Handles preprocessing, feature engineering, model training, and evaluation automatically.

- ColumnTransformer & Pipeline: Numeric and categorical features are processed using imputation, scaling, and one-hot encoding — no manual transformations needed.

- Multiple models evaluated: Logistic Regression, Decision Tree, Random Forest, Gradient Boosting.

- Hyperparameter tuning: Best model selected and tuned using GridSearchCV for optimized performance.

- Evaluation metrics: Accuracy, Precision, Recall, F1-score, ROC-AUC, and cross-validation results.

- Visualizations: ROC curves, confusion matrices, feature importance charts.

- Deployment-ready: Saves the tuned pipeline as a .pkl file for direct use on raw customer data.

Tools & Libraries:

Python | Pandas | NumPy | Matplotlib | Seaborn | Scikit-Learn | Joblib

Results:

Best model: Logistic Regression (tuned)

Test ROC-AUC: 0.846

Accuracy: 0.805

Precision (Churn): 0.668

Recall (Churn): 0.527

Highlights:

Industry-standard ML pipeline without data leakage

Automated preprocessing & feature engineering

Reproducible and ready for deployment

Suitable for intermediate-to-advanced learners in ML

