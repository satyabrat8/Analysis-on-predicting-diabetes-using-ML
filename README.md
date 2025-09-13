# Analysis-on-predicting-diabetes-using-ML


#  Predicting Diabetes with Machine Learning

##  Introduction
Diabetes is a widespread lifestyle-related disease that arises from ineffective insulin usage, leading to increased blood sugar levels.  
If not detected early, it can cause severe health issues including heart disease, kidney failure, and vision problems.  

This project applies **machine learning models** to predict whether an individual is diabetic or non-diabetic based on medical and lifestyle features.

##  Objectives
- Explore patient health data and identify the main risk factors for diabetes.  
- Develop and train different **machine learning classifiers**.  
- Compare algorithm performance and highlight the best predictive approach.  

## Dataset Details
- **Features:** 8 input features + 1 target variable (Outcome)  
- **Examples of features:** Pregnancies, Glucose, Blood Pressure, Skin Thickness, Insulin, BMI, Diabetes Pedigree Function, Age  
- **Challenges:**  
  - Missing values represented by zeroes  
  - Outliers in several attributes  
  - Slight imbalance between diabetic and non-diabetic cases  
- **Preprocessing Steps:**  
  - Handling missing/invalid values  
  - Outlier treatment  
  - Feature scaling and engineering  
  - Multicollinearity checks with VIF  

## Exploratory Data Analysis (EDA)
- **Pie Chart:** 71.5% non-diabetic vs 28.5% diabetic cases.  
- **Histograms & Count Plots:** Show feature distributions.  
- **Pair Plots & Heatmaps:** Highlight correlations among predictors.  
- **Key Finding:** Glucose, BMI, and Age were the strongest predictors.  

## Insights
- **Glucose** was the most important feature for predicting diabetes.  
- **BMI** and **Age** also had significant impact.  
- **Decision Tree** had the weakest accuracy (~72%).  
- **SVM and KNN** achieved the highest performance (~83%).  
- Ensemble approaches (Bagging, AdaBoost, Random Forest) gave consistent and reliable results.  

- Dataset required cleaning and balancing before model training.  
- Ensemble methods offered balanced results compared to single models.  
- **Boosting** methods and **SVM/KNN** are the most reliable choices for deployment in real-world scenarios.  


   git clone https://github.com/your-username/diabetes-prediction.git
   cd diabetes-prediction
