# machine_learning_project-supervised-learning

### Project Goals
1. Import and clean data
2. Analyze and visualize the relationships between variables
3. Handle missing values, outliers and imbalanced data
4. Perform feature engineering
5. Train a machine learning model

### Project dataset
The data set for this project is the "Diabetes" dataset from the National Institute of Diabetes and Digestive and Kidney Diseases 

### Project Description:
Use supervised learning techniques to build a machine learning model that can predict whether a patient has diabetes or not, based on pregnancies, glucose, bloodpressure, skinthickness, insulin, BMI, diabetesPedigreefunction, and age features. 

### Project Outcomes
1. Based on the correlation heatmap, Glucose is the most siginificant predictor of disbetes outcome. Also, age, BMI and pregnancy play important roles.
2. Proper preprocessing steps, including feature scaling, one-hot-encoding significantly improved the model's performance in this case.
3. The accuracy incresed for both models after removing the new generated feature - BMI_Category_Encoded.
4. Logistic Regression and Random Forest were developed as predictive models for diabetes outcome. Random Forest has a batter performance on the test dataset.
5. The dataset shows an imbalanced distribution, with a higher number of non-diabetic cases compared to diabetic cases.
