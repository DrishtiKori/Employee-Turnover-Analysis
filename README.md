# 🏢 Employee Turnover Analytics – Machine Learning Project

 Overview
Employee turnover is a major challenge for businesses, leading to loss of talent and increased recruitment costs.  
This project uses **Machine Learning** to analyze employee data and predict whether an employee is likely to leave the organization.

 Objectives
The main goals of this project are:
- Identify **key factors** influencing employee attrition.
- Build an **ML model** to predict employee turnover.
- Provide actionable **HR insights** to reduce attrition rates.

 Tools & Libraries
- **Python**
- **pandas** – Data manipulation
- **numpy** – Numerical computations
- **matplotlib** – Visualization
- **seaborn** – Statistical plots
- **scikit-learn** – ML models and preprocessing

 Dataset
- **File**: 'employee_data.csv' *(Replace with actual file name if different)*
- **Key Features**:
  - 'Age'
  - 'Department'
  - 'JobRole'
  - 'MonthlyIncome'
  - 'JobSatisfaction'
  - 'YearsAtCompany'
  - 'Attrition' *(Target Variable: Yes/No)*

 Methodology
1. **Data Loading & Exploration**
   - Imported dataset using Pandas.
   - Checked data types, null values, and descriptive statistics.

2. **Data Cleaning & Preprocessing**
   - Handled missing values (if any).
   - Encoded categorical features using Label Encoding & One-Hot Encoding.
   - Standardized numerical features.

3. **Exploratory Data Analysis**
   - Distribution of employees across departments & job roles.
   - Relationship between attrition and age, income, job satisfaction, etc.
   - Correlation heatmaps to identify significant factors.

4. **Model Building**
   - Train-Test Split (80:20 ratio).
   - Tried multiple ML models:
     - Logistic Regression
     - Decision Tree Classifier
     - Random Forest Classifier
   - Tuned hyperparameters for better accuracy.

5. **Model Evaluation**
   - Metrics: Accuracy, Precision, Recall, F1-Score, Confusion Matrix.
   - Selected the **best performing model** for final predictions.

 Key Insights
- **Younger employees** tend to leave more often.
- **Low job satisfaction** strongly correlates with higher attrition.
- **Monthly income** plays a significant role in retention.
- Certain job roles (e.g., Sales) have a higher turnover rate.

