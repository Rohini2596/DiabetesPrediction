# DiabetesPrediction
This project builds a **machine learning model to predict diabetes** using the PIMA Indians Diabetes Dataset. Multiple ML algorithms are applied, evaluated, and optimized to determine the best-performing model.
# Project Objective
To classify whether a patient is diabetic (Outcome = 1) or non-diabetic (Outcome = 0) based on medical measurements such as glucose level, BMI, pregnancies, age, etc.
# Dataset
**PIMA Indians Diabetes Dataset (Kaggle)**
Contains: **768 samples** and **8 features**
* Pregnancies
* Glucose
* Blood Pressure
* Skin Thickness
* Insulin
* BMI
* Diabetes Pedigree Function
* Age
* Outcome (Target)
# Workflow
### **1. Data Exploration & Visualization**
* Histogram (Age, Glucose, BMI, etc.)
* Countplots (Pregnancies, Glucose)
* Boxplots for outliers
* Correlation matrix & heatmap
* Scatter matrix to study relationships
### **2. Data Preprocessing**
* Handling missing values (if any)
* Feature scaling using **StandardScaler**
* Train-test split (80–20)
* Optional: SMOTE for class imbalance improvement
### **3. Model Training**
The following models were trained:
* **Logistic Regression**
* **Decision Tree Classifier**
* **k-Nearest Neighbors**
* **Support Vector Machine**
* **Random Forest Classifier**
### **4. Hyperparameter Tuning**
* Performed using **GridSearchCV** for Random Forest & Decision Tree
* Identified optimal parameters to improve accuracy
### **5. Cross-Validation**
* Used **Stratified K-Fold (k=10)**
* Verified model stability and avoided overfitting
### **6. Evaluation Metrics**
* Accuracy Score
* Confusion Matrix
* Classification Report (Precision, Recall, F1-score)