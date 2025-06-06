# Student Success Analysis ML

---

---

## Overview

Addressing the challenge of student retention and academic success in higher education by leveraging machine learning techniques to predict student outcomes. By analyzing a comprehensive dataset of student demographics, academic history, and socioeconomic factors, the aim is to support early intervention and improve student success rates.

---

## Objective

The core objective is to **support early intervention** by predicting a student’s academic outcome—whether they will:

- **Drop out**
- **Remain Enrolled**
- **Successfully Graduate**

This is framed as a **three-class classification problem** with real-world class imbalance, providing practical challenges for predictive modeling and educational analytics.

---

## Dataset

- **Instances:** 4,424 students
- **Features:** 36 (demographic, academic, and economic)
- **Target Variable:** `Target` (Dropout, Enrolled, Graduate)

### Feature Categories

1. **Demographics & Socioeconomic:** Gender, Age, Marital Status, Nationality, Parental Education/Occupation, Scholarship, Tuition Fees, Application Mode
2. **Academic History:** Degree Program, Curricular Units Enrolled/Approved, Grades, Admission Grade, Previous Qualification
3. **External Factors:** GDP, Inflation Rate, Unemployment Rate at Enrollment

---

## Methodology

1. **Data Cleaning & Preprocessing**
   - Handling missing values and outliers
   - Encoding categorical variables
   - Feature scaling and transformation

2. **Dimensionality Reduction**
   - Applied Principal Component Analysis (PCA) to reduce feature space and improve model performance

3. **Model Building**
   - Evaluated K-Nearest Neighbors (KNN) and Random Forest Classifier (RFC)
   - Hyperparameter tuning using GridSearchCV
   - Model evaluation using accuracy, confusion matrix, and classification report

4. **Feature Importance Analysis**
   - Identified key factors influencing student outcomes

---

## Key Findings

1. **Academic Performance is the Primary Predictor**
   - First-semester grades are strong indicators of eventual outcomes
   - Consistent academic performance increases graduation likelihood

2. **Financial Stability is Crucial**
   - Scholarship holders and students with up-to-date tuition payments have higher success rates
   - Financial interventions are effective for retention

3. **Background Factors Matter**
   - Parental education, age at enrollment, and gender influence outcomes

4. **Economic Context Impacts Success**
   - Enrollment during favorable economic conditions correlates with better outcomes

---

## Recommendations

1. **Early Intervention**
   - Implement early warning systems based on academic performance
   - Provide targeted academic and peer support

2. **Financial Support**
   - Expand scholarships and emergency aid
   - Offer financial literacy programs

3. **Targeted Programs**
   - Support first-generation and at-risk students
   - Foster community and flexible academic pathways

4. **Economic Resilience**
   - Develop contingency plans and work-study opportunities
   - Partner with employers for internships and job placement

---

## Author

[JaberAlJ GitHub](https://github.com/JaberAlJ)

---

