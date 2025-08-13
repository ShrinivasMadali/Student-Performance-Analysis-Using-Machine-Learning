# Student Performance Prediction 🚀

This project focuses on building and evaluating machine learning models to predict student grades based on a variety of features, including study time, demographics, and extra-curricular activities. The primary goal is to compare the performance of different classification algorithms and identify which model provides the most accurate predictions.

---

## 📝 Problem Statement

**Core Question:**  
*"Can we accurately predict a student's final grade using a set of demographic, social, and study-related features?"*

By answering this, we can gain insights into the key factors influencing student performance, which could be used to implement targeted interventions or support programs.

---

## 📊 Key Questions & Answers

**1. What are the key predictors of student grades?**  
- Features like `weeklystudytime` and `Absent` days show strong relationships with final grades.  
- `weeklystudytime` → positive correlation (more study time → higher grades)  
- `Absent` → negative correlation (more absences → lower grades)  

**2. Which machine learning model performs best?**  
- The **Random Forest Classifier** achieved the highest accuracy (~91%).  
- Its ability to handle complex, non-linear relationships gave it an edge over other models.  

**3. How accurate are the model predictions?**  
| Model                     | Accuracy Score |
|----------------------------|---------------|
| Random Forest Classifier   | ~91.0%        |
| Support Vector Machine     | ~82.3%        |
| Logistic Regression        | ~63.0%        |

The Random Forest model correctly predicts student grades more than 9 out of 10 times.

---

## 🛠️ Tools & Technologies

- **Python**: Primary programming language  
- **Pandas & NumPy**: Data manipulation & numerical operations  
- **Scikit-learn**: Machine learning, feature scaling, model training, evaluation  
- **Matplotlib & Seaborn**: Data visualization and plotting (e.g., correlation matrices, ROC curves)  

---

## 📈 Model Performance Summary

| Model                     | Accuracy Score |
|----------------------------|---------------|
| Random Forest              | ~91.0%        |
| Support Vector Machine     | ~82.3%        |
| Logistic Regression        | ~63.0%        |

**Best Model:** Random Forest Classifier – strong performance due to its ability to capture complex relationships in the data.

---

## 🖼️ Visualizations

- **Correlation Matrix**: Heatmap showing correlation between all features, highlighting which variables strongly impact final grade.  
- **Confusion Matrix (Random Forest)**: Displays correct vs. incorrect predictions per grade category.  
- **ROC Curve**: Illustrates model performance across all classification thresholds. Higher curves and larger AUC indicate better performance.

---

## 💡 Project Insights & Conclusion

- **Model Selection**: Random Forest Classifier is the most effective model, outperforming SVM and Logistic Regression.  
- **Influential Features**: `weeklystudytime` and `Absent` are the most predictive of final grades.  
- **Real-World Application**:  
  - Can help educators identify at-risk students early.  
  - Allows proactive interventions like tutoring or mentorship to improve student success.  

**Summary:** This project demonstrates a clear, repeatable process for analyzing student performance data using machine learning and deriving actionable insights.

---

