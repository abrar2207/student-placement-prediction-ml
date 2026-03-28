Student Placement Prediction using Machine Learning

Overview:
This project predicts whether a student will be placed or not based on their academic performance and skills using machine learning.

Objective:
To build a model that can help identify placement chances of students.

Dataset:
- 100,000 student records
- Features:
  - CGPA
  - Coding skills
  - Communication skills
  - Internships
  - Projects
  - Certifications
  - College tier
  - Branch

- Target:
  - Placement Status (0 = Not Placed, 1 = Placed)

Technologies Used:
- Python
- Pandas
- Scikit-learn
- XGBoost
- Matplotlib

Models Used:
- Logistic Regression (baseline)
- XGBoost (final model)

Model Improvements:
- Handled class imbalance using class weighting
- Adjusted threshold from 0.5 to 0.35

Results:
- Accuracy: ~69%
- Balanced performance between classes

Key Insights:
- College tier and internships have strong impact on placement
- Dataset imbalance affects prediction of minority class

Future Scope:
- Use real-world dataset
- Improve accuracy with more features
- Deploy as a web application

## 👤 Author
Abrar Ahamed
