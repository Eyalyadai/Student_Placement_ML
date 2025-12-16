# Student Career Placement Prediction 🎓

## 📌 Project Overview
An end-to-end Machine Learning project designed to assist students in finding their ideal career path in a competitive job market.

Built by **Eyal Yadai**, this project moves beyond simple prediction by implementing a full Data Science pipeline—from cleaning and dimensionality reduction to hyperparameter tuning—to match students with roles like *Data Scientist*, *Web Developer*, or *Technical Support*.

---

## 🎯 The Challenge
Many students struggle to identify which job role best fits their unique combination of skills and academic history.
* **The Goal:** To create a data-driven framework that analyzes academic scores, technical skills, and personal interests to predict the most suitable career trajectory.
* **The Value:** Helping students focus their efforts on roles where they are most likely to succeed.

---

## 🛠️ Methodology & Technical Approach
Unlike basic models, this project implements a professional **Data Science Pipeline**:

### 1. Data Preprocessing & Cleaning
* **Handling Missing Data:** Used `KNNImputer` to intelligently fill gaps based on nearest neighbors (rather than simple mean/median).
* **Scaling & Encoding:** Applied `RobustScaler` for numerical scores (to handle outliers) and `OneHotEncoder` for categorical skills.

### 2. Dimensionality Reduction
* **PCA (Principal Component Analysis):** Applied PCA to reduce noise and focus on the most impactful variance in the data. This ensures the model generalizes well to real-world data and avoids overfitting.

### 3. Model Selection & Tuning
* **Algorithms Compared:** KNN, Naive Bayes, Decision Tree.
* **Hyperparameter Tuning:** Used `GridSearchCV` to exhaustively search for the optimal parameters for each model.

---

## 📊 Evaluation & Results
After rigorous tuning and validation, the **K-Nearest Neighbors (KNN)** model emerged as the best performer, achieving a strong balance between precision and recall.

| Model | Accuracy | Performance Note |
|-------|----------|------------------|
| **K-Nearest Neighbors (KNN)** | **87.3%** 🏆 | Best balance of Precision/Recall |
| Decision Tree | ~85% | Good, but slightly prone to overfitting |
| Naive Bayes | ~82% | Lower accuracy due to feature independence assumption |

> **Note:** While some models might reach 100% on small training sets, using PCA ensures that this 87.3% represents **true generalization** capabilities on unseen data.

---

## 🔍 Key Insights
* **Skills > Grades:** Specific technical skills (e.g., proficiency in Python or SQL) were stronger predictors for specific job roles than a general GPA.
* **The "Math" Factor:** High scores in Mathematics served as a strong indicator for **Data Science** roles.
* **Holistic View:** Academic performance combined with personal interests yields better predictions than grades alone.

---

## 🧰 Tech Stack
* **Python:** Core language.
* **Scikit-Learn:** Pipeline construction, PCA, GridSearchCV, Models.
* **Pandas & NumPy:** Data manipulation and linear algebra.
* **Matplotlib & Seaborn:** Data visualization and EDA.
* **Joblib:** Model persistence.

---

## 🚀 How to Run
If you want to run this code on your machine:

```bash
# 1. Clone this repository
git clone [https://github.com/Eyalyadai/Student_Placement_ML.git](https://github.com/Eyalyadai/Student_Placement_ML.git)

# 2. Install requirements
pip install -r requirements.txt

# 3. Run the Notebook
jupyter notebook notebooks/Student_Placement.ipynb
