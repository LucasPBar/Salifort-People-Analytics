# Salifort Motors – Employee Turnover Prediction  
**Predicting Employee Turnover at Salifort Motors**

<img width="1408" height="768" alt="Image" src="https://github.com/user-attachments/assets/151fd4ba-7275-45d8-bed4-fd9e0bc0c47a" />

---

[![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)](https://www.python.org/)  
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)  
[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)](https://jupyter.org/)  
[![Scikit-learn](https://img.shields.io/badge/Scikit--Learn-0.24-lightgrey?logo=scikitlearn)](https://scikit-learn.org/)  
![ML](https://img.shields.io/badge/Machine%20Learning-Regression-orange) 
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-lightblue?logo=pandas)  
![NumPy](https://img.shields.io/badge/NumPy-Scientific%20Computing-blue?logo=numpy)  
[![XGBoost](https://img.shields.io/badge/XGBoost-1.6-red?logo=xgboost)](https://xgboost.readthedocs.io/)  
![VS Code](https://img.shields.io/badge/VS%20Code-IDE-blue?logo=visualstudiocode)  
![Anaconda](https://img.shields.io/badge/Anaconda-Environment-green?logo=anaconda) 

---

## 📋 Table of Contents

- [Project Description](#project-description)  
- [Technologies & Tools](#technologies--tools)  
- [Data Understanding](#data-understanding)  
- [Business Problem & Objectives](#business-problem--objectives)  
- [Proposed Solutions](#proposed-solutions)  
- [Ethical Considerations](#ethical-considerations)  
- [Key Business Insights](#key-business-insights)  
- [Models and Metrics](#models-and-metrics)  
- [Sample Visualization](#sample-visualization)  
- [Contact](#contact) 

---

## Project Description

This project was developed as part of the Google Data Advanced Analytics certification to apply data science and machine learning techniques to predict employee turnover at the fictional company Salifort Motors. The HR department collected employee data with the goal of improving satisfaction and retention but needed data-driven insights to identify factors causing employees to leave.

---

## Technologies & Tools

- **Language:** Python  
- **Libraries:** `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `xgboost`  
- **Modeling Techniques:** Logistic Regression, Decision Tree, Random Forest  
- **Evaluation Metrics:** AUC, F1-score, Precision, Recall, Confusion Matrix  
- **Environment:** Jupyter Notebook  
- **Data Sources:** Kaggle, GitHub  

---

## Data Understanding

The dataset contains information on 15,000 employees, with features including: 

| Variable               | Description                                                      |
|------------------------|------------------------------------------------------------------|
| satisfaction_level     | Employee-reported job satisfaction level [0–1]                   |
| last_evaluation        | Score of employee’s last performance review [0–1]                |
| number_project         | Number of projects employee contributes to                       |
| average_monthly_hours  | Average number of hours employee worked per month                |
| time_spend_company     | How long the employee has been with the company (years)          |
| Work_accident          | Whether or not the employee experienced an accident while at work|
| left                   | Whether or not the employee left the company                     |
| promotion_last_5years  | Whether or not the employee was promoted in the last 5 years     |
| Department             | The employee’s department                                        |
| salary                 | The employee’s salary (U.S. dollars)                             |
 

**Dataset link:** [Hr Analytics Job Prediction](https://www.kaggle.com/datasets/ajaypalsinghlohana/hr-analytics-job-prediction)

---

## Business Problem & Objectives

### Business Problem  
HR wants to identify key factors influencing employee turnover to implement strategies that increase retention.

### Objectives  
- Analyze the dataset to identify turnover patterns  
- Build a predictive model to flag employees at risk of leaving  
- Support HR with actionable data-driven retention strategies  

---

## Proposed Solutions

1. **Reduce excessive workload:** Limit projects per employee and monitor burnout signs.  
2. **Promotions and recognition:** Clear policies to value and retain talent.  
3. **Work culture reform:** Reassess performance evaluations and overtime expectations.  
4. **HR strategic actions:** Team meetings to understand culture and dissatisfaction causes.  
5. **Feature engineering:** Create derived variables like "overworked" to capture workload.  
6. **Adopt predictive models:** Use Random Forest to predict turnover risk and guide decisions.  

---

## Ethical Considerations

This project reflects the responsible use of sensitive employee data by emphasizing:  
- **Privacy:** Ensuring data confidentiality throughout analysis  
- **Transparency:** Clear communication about data usage and model limitations  
- **Bias Mitigation:** Identifying and reducing biases to promote fair predictions  

---

## Key Business Insights

| Indicator                 | Insight                                                                                   |
|---------------------------|-------------------------------------------------------------------------------------------|
| Satisfaction Level        | Low satisfaction is the strongest predictor of turnover.                                 |
| Workload                  | More than 200 hours/month is linked to dissatisfaction and burnout.                      |
| Number of Projects        | Ideal range is 3 to 4 projects; 7 projects correlate with 100% turnover.                 |
| Tenure                    | Employees with over 6 years tend to stay; 4-year tenure group shows unusual dissatisfaction. |
| Promotions                | Promotions correlate with higher retention but are infrequent.                           |
| Performance Evaluations   | Should not rely solely on hours worked to avoid rewarding overwork.                      |

---

## Models and Metrics

| Model              | AUC (%) | F1-score | Precision | Recall | Notes                                      |
|--------------------|---------|----------|-----------|--------|--------------------------------------------|
| Logistic Regression | 89      | 0.85     | 0.83      | 0.86   | Baseline model                             |
| Decision Tree      | 91      | 0.87     | 0.85      | 0.89   | Easy to interpret                          |
| **Random Forest**  | **98**  | **0.93** | **0.92**  | **0.94** | Best performance, robust, less overfitting |

*Why Random Forest?*  
- Combines multiple trees for robustness  
- Captures complex variable interactions  
- Stable with unseen data  

---

## Contact

| Platform | Link / Email                                                  |
|----------|--------------------------------------------------------------|
| LinkedIn | [linkedin.com/in/lucaspimentabarretto](https://www.linkedin.com/in/lucaspimentabarretto) |
| GitHub   | [github.com/LucasPBar](https://github.com/LucasPBar)         |
| Email    | lucaspimenta1805@gmail.com                                    |




