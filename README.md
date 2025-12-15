🎯 Aim

The aim of this project is to design, implement, and evaluate a Decision Tree–based supervised learning model for predicting loan approval outcomes using a realistic financial dataset. The project emphasizes systematic data preprocessing, categorical feature encoding, and model optimization through controlled hyperparameter selection. By leveraging entropy-based information gain and class balancing techniques, the model aims to achieve robust classification performance while effectively handling feature heterogeneity and class imbalance inherent in real-world loan approval data.

🛠 Technologies Used
🔹 Programming Language

Python – Selected for its extensive support for data analysis, machine learning pipelines, and rapid prototyping of classification models.

🔹 Development Environment

Google Colab – Utilized for cloud-based execution, scalable computational resources, and seamless integration with data science libraries.

🔹 Libraries and Frameworks

Pandas

Used for structured data ingestion, duplicate removal, missing value handling, and feature selection.

NumPy

Applied for efficient numerical operations, vectorized computations, and data transformation support.

Scikit-learn

Employed as the core machine learning framework for the end-to-end pipeline, including:

Data partitioning using stratified train_test_split to preserve class distribution

Categorical feature transformation using LabelEncoder

Model construction using DecisionTreeClassifier with entropy-based splitting criteria

Hyperparameter tuning controls, including max_depth, min_samples_split, and min_samples_leaf, to mitigate overfitting

Class imbalance handling using class_weight='balanced'

Model evaluation using accuracy_score for quantitative performance assessment
