# Student Career Placement Prediction

## Project Overview
This project aims to predict the most suitable career path for students based on their academic performance, technical skills, and personal attributes. By analyzing historical data, the system identifies patterns that correlate specific competencies with job roles such as Data Scientist, Web Developer, and Technical Support.

The goal is to provide a data-driven approach to career counseling, helping educational institutions and students make informed decisions.

## Dataset
The dataset consists of student records including:
* **Academic Scores:** GPA, Mathematics, English, etc.
* **Technical Skills:** Proficiency in Python, SQL, Java, etc.
* **Soft Skills:** Communication, problem-solving, and teamwork scores.
* **Target Variable:** The recommended Job Profile.

## Methodology
The project follows a standard Data Science lifecycle:
1. **Data Preprocessing:** Cleaning missing values and encoding categorical variables.
2. **Exploratory Data Analysis (EDA):** Analyzing correlations between skills and job roles.
3. **Feature Engineering:** Selection of key features impacting the prediction.
4. **Model Training:** Implementation of supervised learning algorithms.
5. **Evaluation:** Comparing models based on accuracy metrics.

## Model Performance
The following models were trained and evaluated on the test set. Due to the clear distinction in the dataset patterns, the models achieved high accuracy scores.

| Model | Accuracy |
|-------|----------|
| K-Nearest Neighbors (KNN) | 100% |
| Decision Tree | 100% |
| Naive Bayes | 100% |

*Note: The high accuracy indicates strong separability in the provided dataset. In larger, real-world datasets, performance may vary.*

## Prerequisites
To run this project, you need the following libraries installed:
* Python 3.x
* pandas
* numpy
* scikit-learn
* matplotlib
* seaborn

## Installation & Usage
To run the analysis locally:

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/Eyalyadai/Student-Placement-Prediction.git](https://github.com/Eyalyadai/Student-Placement-Prediction.git)