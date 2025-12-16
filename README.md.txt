# 🎓 Student Career Placement Prediction

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Scikit-Learn](https://img.shields.io/badge/Library-Scikit--Learn-orange)
![Status](https://img.shields.io/badge/Status-Completed-green)

## 📌 Overview
This project focuses on predicting the most suitable career path for students based on their academic performance, technical skills, and personal attributes.

In today's competitive job market, students often struggle to identify the role that best fits their strengths. By leveraging **Machine Learning**, this project analyzes historical student data to recommend profiles such as **Data Scientist**, **Web Developer**, **Technical Support**, and more.

## 🔍 Key Findings & Insights
* **Skill Correlation:** Technical skills (e.g., Python, SQL, Java) showed the highest correlation with specific job profiles.
* **Academic Impact:** While GPA is important, specific subject scores (like DSA for developers or Math for Data Scientists) were more predictive than the overall average.
* **Model Performance:** The K-Nearest Neighbors (KNN) model outperformed others after hyperparameter tuning.

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:**
  * `pandas` & `numpy` (Data Manipulation)
  * `matplotlib` & `seaborn` (Data Visualization)
  * `scikit-learn` (Machine Learning & Preprocessing)

## 📊 Model Performance
I evaluated three different models to find the best predictor. Hyperparameter tuning was performed using `GridSearchCV`.

| Model | Accuracy (Approx) |
|-------|------------------|
| **K-Nearest Neighbors (KNN)** | **~98%** (Best Performer) |
| Decision Tree | ~95% |
| Naive Bayes | ~92% |

## 🚀 How to Run
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/](https://github.com/)[Eyalyadai]/Student-Placement-Prediction.git