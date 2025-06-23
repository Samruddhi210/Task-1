# Task-1  Data Cleaning & Preprocessing

This project focuses on the complete data cleaning and preprocessing pipeline using the Titanic Survival Prediction dataset. The goal is to prepare the raw dataset into a clean, consistent, and fully numeric form suitable for machine learning model development.

 Key Steps Performed:
1) Data Import & Exploration:
Loaded the dataset using Pandas
Explored structure, types, and missing values

2) Handling Missing Values:
Used median, mean, and mode imputation
Addressed nulls in Age, Fare, Embarked, and Cabin

3) Encoding Categorical Variables:
Label encoding for binary columns like Sex
One-hot encoding for columns like Embarked, Pclass, Cabin

4) Feature Scaling:
Standardized numerical features using StandardScaler
Ensured features are on similar scales for modeling

5) Outlier Detection & Removal:
 Visualized outliers using boxplots
 Removed outliers using the IQR method.

-> Tools & Libraries Used:
    Python (Google Colab)
    Pandas, NumPy
    Matplotlib, Seaborn
    Scikit-learn (StandardScaler, encoding tools)




