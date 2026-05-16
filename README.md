📌 Project Title
Student Grades Prediction System

🧠 Project Overview
The Student Grades Prediction System is a machine learning-based application designed to identify secondary school students who are at risk of underperforming. Instead of relying only on academic grades, the system uses a broader range of student behavioral and personal factors to generate more accurate and holistic predictions.

The goal is to help educators detect at-risk students early and provide timely academic support.

⚙️ Methodology
The system uses a Random Forest Regression model to predict students’ final grades based on multiple features such as:
Past academic performance (grades, failures)
Study time
Health status
Family and romantic relationships
Parents’ education level
Free time and social activities
Travel time and going out habits

🧹 Data Processing
To ensure high-quality predictions, the following steps were applied:
Handling missing values
Detecting and treating outliers
Feature selection and engineering
Identifying the most impactful variables for prediction

📊 Model Evaluation
The model was evaluated using standard regression metrics:
R² Score: 0.81 (81% accuracy in explaining variance)
Mean Absolute Error (MAE): 0.94
Mean Squared Error (MSE): 2.25

These results show that the model performs reliably in predicting student performance.

📈 Tools & Technologies
Python
Pandas
NumPy
Scikit-learn
Random Forest Regression
Matplotlib / Seaborn (for visualization)
Jupyter Notebook
Flask

🎯 Key Outcome

The system successfully predicts final student grades and helps identify students who may need additional academic support, enabling early intervention and better educational outcomes.
