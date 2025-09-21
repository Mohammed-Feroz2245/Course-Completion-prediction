# 🎓 Predicting Course Completion Using Machine Learning

## 📌 Problem Statement  
Online learning platforms often face the challenge of learners dropping out before completing a course.  
The goal of this project is to *predict whether a learner will complete a course* based on their activity, demographic, and interaction data.  

Such predictions can help platforms take early interventions — e.g., sending reminders, suggesting study plans, or offering mentoring.  

---

## 📊 Dataset  
The dataset contains information about learners, including:  
- *Demographics* (e.g., age, gender, region)  
- *Course engagement* (e.g., number of sessions, time spent, quizzes attempted)  
- *Performance indicators* (e.g., test scores, assignments submitted)  

- *Target Variable (y):* course_completed (1 = completed, 0 = not completed)  
- *Features (X):* All other numeric + encoded categorical variables.  

---

## ⚙ Process  

### 1. Data Preprocessing  
- Handled missing values.  
- Converted *categorical variables into numeric* using encoding.  
- Standardized numerical columns.  
- Split dataset into training and test sets.  

### 2. Feature Engineering  
- Selected relevant features (engagement + demographics).  
- Removed redundant/low-variance columns.  

### 3. Model Training  
We tested 3 classification models:  
- *Logistic Regression* (baseline)  
- *Decision Tree Classifier*  
- *Random Forest Classifier*  

### 4. Model Evaluation  
- Metrics: Accuracy, Precision, Recall, F1-score  
- Used Confusion Matrix and ROC-AUC for visualization.  

---

## 📈 Results  

- Logistic Regression   
- Decision Tree y  
- Random Forest → *Best performance  

📌 Random Forest was the most robust model, handling categorical & numeric data effectively while avoiding overfitting.  

Example Plots:  
- Feature Importance (Random Forest)  
- Confusion Matrix  
- ROC-AUC Curve  

---
## 💡 Key Learnings  
- Encoding categorical variables correctly is crucial.  
- Simple models (Logistic Regression) provide interpretability but may underperform.  
- Ensemble methods (Random Forest) balance accuracy and robustness.  
- Feature importance analysis helps in understanding 
