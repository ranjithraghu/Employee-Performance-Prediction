# Employee Performance Prediction using Machine Learning

## Project Overview

Employee performance plays a crucial role in organizational growth, productivity, and employee retention. This project focuses on analyzing employee-related data and building Machine Learning models to predict employee performance ratings based on workplace, compensation, and employee behavioral factors.

The project combines:
- Data Analysis
- Data Visualization
- Feature Engineering
- Machine Learning
- HR Analytics
- Predictive Modeling

to generate meaningful business insights for HR decision-making.

---

# Business Objective

The main objective of this project is to:

- Analyze employee performance patterns
- Identify important factors affecting employee productivity
- Predict employee performance ratings using Machine Learning
- Support HR departments in employee evaluation and workforce planning
- Improve employee engagement and organizational efficiency

---

# Dataset Information

## Dataset Used
`INX_Future_Inc_Employee_Performance_CDS_Project2_Data_V1.8.xls`

## Dataset Includes
- Employee demographics
- Department information
- Job roles
- Work environment factors
- Salary hike details
- Promotion history
- Work experience
- Employee satisfaction metrics
- Performance ratings

---

# Problem Type

## Multi-Class Classification Problem

### Target Variable
`PerformanceRating`

| Rating | Meaning |
|---|---|
| 2 | Low Performance |
| 3 | Medium Performance |
| 4 | High Performance |

---

# Technologies & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost

---

# Machine Learning Workflow

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Outlier Detection
5. Feature Engineering
6. Encoding Categorical Variables
7. Feature Scaling using RobustScaler
8. Train-Test Split
9. Model Building
10. Model Evaluation

---

# Exploratory Data Analysis (EDA)

EDA was performed to analyze:
- Employee behavior
- Data distributions
- Correlations
- Outliers
- Performance influencing factors

Several visualizations such as:
- Histograms
- Countplots
- Scatterplots
- Heatmaps
- Boxplots
- Pairplots

were used to extract business insights.

---

# Key Insights

## Overtime Increases Attrition
Employees working overtime are more likely to leave the organization due to:
- Work stress
- Burnout
- Poor work-life balance

---

## Salary Hikes Improve Performance
Employees receiving salary hikes greater than 20% tend to achieve higher performance ratings.

This indicates:
- Better compensation improves motivation
- Recognition positively impacts productivity

---

## Distance From Home Impacts Productivity
Employees living closer to the workplace tend to perform better due to:
- Reduced travel stress
- Better punctuality
- Improved work-life balance

---

## Promotions Improve Employee Performance
Employees with better promotion opportunities and higher hourly rates tend to show improved performance ratings.

---

## Highly Experienced Employees Show Slight Performance Decline
Employees with more than 11 years of experience showed relatively lower performance ratings due to:
- Career stagnation
- Reduced motivation
- Work fatigue

---

# Data Preprocessing

## Handling Missing Values
- No missing values were found in the dataset.

## Outlier Handling
Outliers were detected using boxplots and handled using:
- RobustScaler

## Encoding Techniques
Categorical variables were converted into numerical format using:
- One-Hot Encoding
- Label Mapping

---

# Machine Learning Models Used

The following classification algorithms were implemented:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- XGBoost Classifier

---

# Model Evaluation Metrics

Models were evaluated using:
- Accuracy Score
- Classification Report
- Confusion Matrix

---

# Best Performing Model

## XGBoost Classifier

### Accuracy Achieved: ~92%

### Why XGBoost Performed Better
- Handles complex patterns efficiently
- Reduces overfitting using boosting
- Works well with structured/tabular data
- Provides strong predictive performance

---

# Important Features Affecting Employee Performance

Top factors influencing employee performance:
- Overtime
- Salary Hike Percentage
- Distance From Home
- Work Experience
- Promotion Opportunities
- Hourly Rate
- Work-Life Balance

---

# Business Recommendations

- Reduce excessive overtime to improve employee retention
- Provide performance-based salary hikes and incentives
- Encourage continuous learning and employee upskilling
- Improve employee engagement programs
- Support work-life balance initiatives
- Offer flexible work arrangements for long-distance employees
- Create better career growth opportunities

---

# Project Outcome

Successfully developed a Machine Learning-based Employee Performance Prediction System capable of:
- Predicting employee performance ratings
- Identifying key performance-driving factors
- Supporting HR decision-making
- Generating actionable business insights

---

# Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Visualization
- Feature Engineering
- Machine Learning
- Model Evaluation
- Predictive Analytics
- HR Analytics
- Business Insight Generation

---

# Conclusion

This project successfully developed a Machine Learning model to predict employee performance using employee-related organizational data.

Data preprocessing, exploratory data analysis, feature engineering, and multiple classification algorithms were applied to improve model performance and generate meaningful business insights.

Among all the models tested, the XGBoost Classifier achieved the best performance with an accuracy of approximately 92%.

This project demonstrates how Machine Learning and HR Analytics can help organizations make better hiring decisions, improve employee productivity, reduce attrition, and support data-driven business strategies.

---

# Author

## Ranjith T

Aspiring Data Scientist skilled in:
- Python
- Machine Learning
- SQL
- Power BI
- Data Analytics

GitHub:
https://github.com/ranjithraghu
