🎓 Student Performance Classification using SVM

📌 Project Overview

This project leverages a Support Vector Machine (SVM) to classify student performance based on various demographic, social, and academic features. The target is to predict whether a student will Pass or Fail using their final grade (G3) as the benchmark.

🧠 Objective

Predict the academic outcome (Pass/Fail) of students based on features like study time, absences, failures, parental education, etc.

🗃️ Dataset

Source: UCI Machine Learning Repository

File: student-mat.csv

Delimiter: ; (semicolon-separated)

Target Column: G3 (final grade)

Classification Target:

Pass (G3 ≥ 10)

Fail (G3 < 10)

🧰 Tools & Libraries

pandas 🐼 – Data manipulation

scikit-learn 🤖 – Preprocessing, modeling, evaluation

matplotlib, seaborn 📊 – Visualization

🚀 Steps Involved

Importing & Reading Data

Preprocessing

Label Encoding categorical features

Converting G3 to Result (Pass/Fail)

Feature Scaling

Splitting Dataset

Training an SVM Classifier

Prediction

Evaluation

Accuracy

Classification Report

Confusion Matrix

📈 Model Performance

Model: Support Vector Classifier (SVC)

Accuracy: ~XX.XX% (replace after execution)

Classification Report: Includes Precision, Recall, F1-score

Visualization: Confusion Matrix for real vs. predicted labels

🖼️ Confusion Matrix

A heatmap visualization helps interpret the classification results more intuitively.

📂 Folder Structure

📦student-performance-svm
 ┣ 📄 student-mat.csv
 ┣ 📄 svm_student_pass_fail.ipynb
 ┗ 📄 README.md
💡 Real-World Use Case

This project is ideal for:

Academic institutions to identify at-risk students

Education researchers for data-driven interventions

EdTech platforms offering personalized learning suggestions

🏁 Conclusion

SVM proves to be an effective classifier for educational performance prediction. With further tuning and feature engineering, the model can support early intervention systems in real-world academic environments.
