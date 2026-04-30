Heart Disease Prediction & Analysis 
A comprehensive machine learning pipeline designed to predict the likelihood of heart disease in patients based on clinical parameters.

✨ Key Features
Machine Learning: Implements and compares Logistic Regression and Decision Tree classifiers to identify at-risk patients.
Medical Insights: Feature importance analysis to identify top predictors like chest pain type (cp) and maximum heart rate (thalach).
Comprehensive Evaluation: Utilizes Confusion Matrices (critical for medical diagnostics) and ROC-AUC Curves to ensure model reliability.
Data Visualization: Detailed Exploratory Data Analysis (EDA) using Seaborn and Matplotlib to uncover clinical correlations.

📁 Project Structure
/data: Contains the UCI Heart Disease Dataset.
/notebooks: Jupyter Notebooks covering Data Cleaning, EDA, and Model Training.
/models: Saved versions of the trained classification models.
/scripts: Python scripts for the feature scaling and evaluation pipeline.

🛠️ Tech Stack
Language: Python 3.10+
Libraries: Pandas, NumPy, Scikit-Learn
Visualization: Matplotlib, Seaborn
Techniques: Feature Scaling, Binary Classification, Correlation Mapping

📊 Dataset Overview
The model is trained on 14 key clinical features, including:
Age & Sex
Chest Pain Type (cp)
Resting Blood Pressure (trestbps)

Serum Cholesterol (chol)

Maximum Heart Rate Achieved (thalach)
