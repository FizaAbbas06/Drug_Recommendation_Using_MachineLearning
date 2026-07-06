# Drug_Recommendation_Using_MachineLearning
This project presents a Drug Recommendation System developed using multiple machine learning algorithms to predict the most appropriate drug for a patient based on demographic information and clinical measurements. The system analyzes patient characteristics such as age, sex, blood pressure, cholesterol level, sodium (Na), and potassium (K) levels to recommend the most suitable medication.

The project was completed as an assignment for the Machine Learning Certification Course offered by Intellipaat Academy. It demonstrates the complete end-to-end machine learning workflow, including data preprocessing, exploratory data analysis (EDA), model training, evaluation, explainability, and drug recommendation.
# Project Objective

The primary objective of this project is to build an intelligent machine learning model capable of recommending the most appropriate drug for patients using their clinical information.

The project also compares multiple machine learning algorithms to identify the best-performing model for drug recommendation.
# Dataset

The dataset contains patient information with the following features:

| Feature | Description |
| :--- | :--- |
| **Age** | Patient age |
| **Sex** | Male / Female |
| **BP** | Blood Pressure |
| **Cholesterol** | Cholesterol Level |
| **Na** | Sodium Level |
| **K** | Potassium Level |
| **Drug** | Target variable (Recommended Drug) |

# Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* XGBoost
 # Exploratory Data Analysis (EDA)

The following analyses were performed:

* Dataset overview
* Missing value analysis
* Duplicate value analysis
* Drug class distribution
* Age distribution
* Gender distribution
* Blood pressure distribution
* Cholesterol distribution
* Sodium (Na) distribution
* Potassium (K) distribution
* Correlation heatmap
# Data Preprocessing
The preprocessing pipeline includes:
* Handling categorical variables using One-Hot Encoding
* Label Encoding for the target variable
* Feature Scaling using StandardScaler
# Machine Learning Models

The following classifiers were implemented and compared:

* Logistic Regression
* Decision Tree
* Random Forest
* K-Nearest Neighbors (KNN)
* Support Vector Machine (SVM)
* XGBoost
* Gradient Boosting Classifier
* Train-Test Split
  
 # Model Evaluation

Each model was evaluated using:

* Accuracy
* Precision (Macro Average)
* Recall (Macro Average)
* F1 Score (Macro Average)
* Confusion Matrix
* ROC Curve (One-vs-Rest)
* 5-Fold Cross Validation

# Explainable Machine Learning

To improve model interpretability, feature importance analysis was performed using:

* **XGBoost Feature Importance**
* **Logistic Regression Coefficient-Based Feature Importance**

These analyses help identify the clinical features that contribute most to the drug recommendation process.
# Drug Recommendation

The best-performing models were used to recommend drugs for unseen patients in the test dataset.

The project includes:
* Drug recommendation on the test dataset
* Comparison between actual and predicted drugs

# Learning and Development

This project was completed as part of the **Machine Learning Certification Course** provided by **Intellipaat Academy**.

During the development of this project, I:
* Applied concepts learned throughout the course.
* Explored additional learning resources, including educational YouTube tutorials, to strengthen my understanding of machine learning concepts and implementation techniques.
* Used AI-based tools as learning assistants for code refinement, debugging, explanations, and improving documentation while ensuring that I understood and verified the implemented workflow.

The project reflects my practical understanding of the complete machine learning pipeline and serves as part of my learning portfolio.
