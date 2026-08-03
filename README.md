# Employee Attrition Prediction using Machine Learning

## Project Overview

Employee attrition is a major challenge for organizations as it impacts productivity, recruitment costs, and overall business performance. This project aims to predict whether an employee is likely to leave the company using Machine Learning techniques and to identify the key factors influencing employee attrition.

The project follows a complete end-to-end Machine Learning workflow, starting from Exploratory Data Analysis (EDA) and Data Preprocessing to Model Building, Hyperparameter Tuning, Business Insights, and Recommendations.

---

## Problem Statement

Develop a machine learning model to predict employee attrition using employee demographic, work-related, and compensation information. The objective is to help HR departments identify employees who are at risk of leaving and take proactive measures to improve employee retention.

---

## Dataset

**Dataset:** IBM HR Analytics Employee Attrition & Performance

The dataset contains employee information such as:

- Age
- Department
- Job Role
- Business Travel
- Monthly Income
- Overtime
- Distance From Home
- Job Satisfaction
- Total Working Years
- Years at Company
- Performance Rating
- Attrition (Target Variable)

Target Variable:

- **Attrition**
  - 0 → Employee Stays
  - 1 → Employee Leaves

---

## Project Workflow

### 1. Exploratory Data Analysis (EDA)

- Data understanding
- Dataset shape and structure
- Data types
- Missing value analysis
- Duplicate record check
- Statistical summary
- Univariate analysis
- Bivariate analysis
- Correlation analysis
- Outlier detection

---

### 2. Data Cleaning

- Removed unnecessary columns
- Handled missing values
- Replaced invalid values
- Removed duplicate records
- Treated outliers

---

### 3. Feature Engineering

- Label Encoding
- Feature Scaling using StandardScaler
- Feature Selection

---

### 4. Model Building

The following classification algorithms were trained and evaluated:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Gaussian Naive Bayes
- K-Nearest Neighbors (KNN)

---

### 5. Model Evaluation

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- 5-Fold Stratified Cross Validation

The best-performing model was selected based on the F1-Score.

---

### 6. Hyperparameter Tuning

Performed GridSearchCV on the best-performing model to obtain the optimal hyperparameters and improve model performance.

---

### 7. Employee Attrition Prediction

Predicted attrition for multiple new employee records using the trained model.

---

### 8. Feature Importance

Since Gaussian Naive Bayes does not provide built-in feature importance, a Random Forest model was trained separately to identify the most influential features affecting employee attrition.

---

### 9. Business Insights

The analysis identified the following major factors influencing employee attrition:

- Monthly Income
- Overtime
- Age
- Daily Rate
- Monthly Rate
- Hourly Rate
- Total Working Years
- Distance From Home
- Number of Companies Worked
- Years at Company

---

### 10. Business Recommendations

Based on the analysis, the following recommendations were proposed:

- Review employee compensation policies.
- Reduce excessive overtime and improve work-life balance.
- Implement career growth and employee development programs.
- Improve employee retention strategies across different age groups.
- Support employees with long commuting distances through flexible work arrangements.
- Introduce performance-based rewards and competitive salary revisions.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Joblib
- Jupyter Notebook

---

## Machine Learning Pipeline

Data Collection
↓
EDA
↓
Data Cleaning
↓
Feature Engineering
↓
Train-Test Split
↓
Feature Scaling
↓
Train Multiple Models
↓
Cross Validation
↓
Model Selection
↓
Hyperparameter Tuning
↓
Final Evaluation
↓
Predict New Employee Records
↓
Feature Importance
↓
Business Insights
↓
Business Recommendations
↓
Save Final Model

---

## Project Structure

```
employee-attrition-prediction-ml/
│
├── data/
│   └── WA_Fn-UseC_-HR-Employee-Attrition.csv
│
├── notebooks/
│   └── Employee_Attrition_Prediction.ipynb
│
├── docs/
│   ├── 
│   ├── 
│   └── 
│
├── requirements.txt
├── README.md
└── .gitignore
```

---

## How to Run

Clone the repository:

```bash
git clone https://github.com/<your-username>/employee-attrition-prediction-ml.git
```

Navigate to the project directory:

```bash
cd employee-attrition-prediction-ml
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open the notebook and execute all cells.

---

## Future Improvements

- Handle class imbalance using SMOTE.
- Perform advanced feature engineering.
- Use SHAP for model explainability.
- Build an interactive dashboard using Streamlit.
- Deploy the model using Flask or FastAPI.
- Containerize the application using Docker.

---

## Author

**Sanket Zambare**

GitHub: https://github.com/Sanketdev77

---

If you found this project helpful, consider giving it a Star!
