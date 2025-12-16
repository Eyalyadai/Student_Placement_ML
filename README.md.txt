# Student Career Placement Prediction

Hello and Welcome!
I'm Eyal. This is a Data Science portfolio project where I explore how Machine Learning can help students find their ideal career path.

## What is this project?
In a competitive job market, many students are unsure which role fits them best.
This project uses Machine Learning to analyze student data - like academic scores, technical skills, and personal interests - to predict the most suitable job profile (e.g., Data Scientist, Web Developer, Technical Support).

##Methodology & Technical Approach
Unlike basic models, this project implements a professional Data Science Pipeline:
1.  Data Cleaning: Handling missing values using "KNNImputer".
2.  Preprocessing: Using "OneHotEncoder" for categorical skills and "RobustScaler" for numerical scores.
3.  Dimensionality Reduction: Applied PCA (Principal Component Analysis) to reduce noise and focus on the most important features.
4.  Model Selection: Compared multiple algorithms (KNN, Naive Bayes, Decision Tree).
5.  Hyperparameter Tuning: Used "GridSearchCV" to find the optimal parameters for each model.

## Key Findings
Skills matter more than grades: Specific technical skills (like Python or SQL) were stronger predictors for job roles than general GPA.
The "Math" factor: High scores in Mathematics were a strong indicator for Data Science roles.
Best Model: The K-Nearest Neighbors (KNN) model achieved the best balance between precision and recall.

## Results
After tuning and validation, the model achieved an accuracy of 87.3% on unseen test data.

| Model | Accuracy |
|-------|----------|
| K-Nearest Neighbors (KNN) | 87.3% |
| Decision Tree | ~85% |
| Naive Bayes | ~82% |

**(Note: While some models can reach 100% on small datasets, using PCA ensures the model generalizes better to real-world data.)**

## Tech Stack
I built this project using Python and the following libraries:
Pandas & NumPy: For data manipulation.
Scikit-Learn: For Pipelines, PCA, and Modeling.
Matplotlib & Seaborn: For visualization.
Joblib: For saving the trained model.

## How to Run it yourself
If you want to run this code on your machine:

1. Clone this repository:
   ```bash
   git clone (https://github.com/Eyalyadai/Student_Placement_ML.git)

2.  Install requirements:
   ```bash
   pip install -r requirements.txt

3. Run the Notebook:
  Open notebooks/Student_Placement.ipynb in Jupyter Notebook.

**Created by Eyal Yadai. If you have any questions or feedback, feel free to reach out!**