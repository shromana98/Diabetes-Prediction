# Diabetes-Prediction
Diabetes poses a severe health challenge in India due to its high prevalence and associated complications. By identifying diabetes in its early stages, individuals can adopt lifestyle changes and receive appropriate medical treatment to minimize the risk of complications.

# 🎯Objective:
The primary aim of this project is to accurately identify individuals at risk of diabetes based on different features.

# 🔍 Data Cleaning:
 PIMA Indian Diabetes Dataset(Source: Kaggle).

Dealt with the null values, duplicates, zero values, data type of columns.

# 📊 Exploratory Data Analysis (EDA) :

# 💡 Insights:

- Individuals with diabetes tend to have higher average glucose levels (141.26 mg/dL) compared to those without diabetes with an average glucose level of 109.98 mg/dL. 
-People with diabetes appear to have slightly higher skin thickness and insulin levels compared to those without diabetes, but the difference is not drastic. 
- Individuals with diabetes have a higher average BMI (35.14) compared to those without diabetes (30.30). This suggests a correlation between higher BMI and diabetes risk. 
-The Diabetes Pedigree Function is slightly higher for individuals with diabetes (0.5505) compared to those without diabetes (0.4297). 
- The average age of individuals with diabetes (37.07 years).
- 75% of the women have obese 
- Half of the diabetic women showed normal glucose level.
- The average value of 2h insulin of the samples show a normal range (140(mIU/L))

# ⚙️ Feature Selection: 

Recognizes and chooses important attributes using RFE .These characteristics are essential for accurately predicting diabetes. Glucose as a feature is the most important in this dataset.. 

# 🔄 Data Preprocessing:

Standardized the data to ensure fair comparisons between features.
And, selected relevant features to train the model..

# 🤖 Model Training and Evaluation:

- Implemented various models including KNN, SVM, Random Forest, Decision Tree, and XGBoost.
- Performed Cross Validation using GridSearchCV.
- Found SVM to be the most effective model with an testing accuracy score of 0.76.

# 💡 Model Evaluation:

- Achieved a ROC AUC score of approximately 0.7822, indicating moderate discrimination ability.
- Obtained an Average Precision Score (APS) of approximately 0.70, suggesting a moderate level of precision across all recall levels.

# 🚀 Conclusions: 
Early detection of diabetes plays a critical role in preventing complications, improving health outcomes, reducing healthcare costs, and empowering individuals to take control of their health through timely intervention and management. Hence, it is crucial!🌟
