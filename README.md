# Salifort Motors – Employee Turnover Prediction  
*Predicting Employee Turnover at Salifort Motors*

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
- [Techniques Applied](#techniques-applied)  
- [Data Understanding](#data-understanding)  
- [Business Problem & Objectives](#business-problem--objectives)  
- [Context](#context)  
- [Benefits of the Project](#benefits-of-the-project)  
- [Project Conclusions](#project-conclusions)  
- [Proposed Solutions](#proposed-solutions)  
- [Ethical Considerations](#ethical-considerations)  
- [Key Business Insights](#key-business-insights)  
- [Models and Metrics](#models-and-metrics)  
- [Sample Visualization](#sample-visualization)  
- [Contact](#contact)  

---

## Project Description

This project was developed as part of the Google Data Advanced Analytics certification to apply data science and machine learning techniques in predicting employee turnover at the fictional company Salifort Motors. The HR department at Salifort Motors has gathered comprehensive employee data aiming to enhance workforce satisfaction and retention. However, they faced uncertainty about how to extract actionable insights from this data. They engaged a data analytics professional to deliver data-driven answers to a key question: which factors are most likely to lead employees to leave the company?

---

## Technologies & Tools

- **Language:** Python  
- **Libraries:** `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `xgboost`  
- **Modeling Techniques:** Logistic Regression, Decision Tree, Random Forest  
- **Evaluation Metrics:** AUC, F1-score, Precision, Recall, Confusion Matrix  
- **Environment:** Jupyter Notebook  
- **Data Sources:** Kaggle, GitHub  

---

## Techniques Applied

- Exploratory Data Analysis (EDA) to uncover patterns and data quality issues  
- Data visualization using Matplotlib and Seaborn to interpret key relationships  
- Classification modeling with Logistic Regression, Decision Tree, and Random Forest  
- Model evaluation using metrics such as AUC, F1-score, Precision, and Recall  
- Cross-validation to ensure robustness and prevent overfitting  

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
The HR team at Salifort Motors wants to understand the underlying causes that prompt employees to leave the company. Employee turnover not only disrupts team dynamics but also incurs significant financial and operational costs. Therefore, identifying predictive factors that signal an employee’s likelihood of leaving is essential. With these insights, the company can proactively create targeted strategies to enhance employee satisfaction, reduce turnover rates, and foster a healthier workplace culture.

### Objectives  
- Analyze the dataset to uncover key turnover drivers  
- Build a predictive model that flags employees at risk of leaving  
- Provide HR with actionable, data-driven recommendations for retention strategies  

---

## Context

When Salifort Motors’ HR team aims to improve talent retention, three key performance indicators (KPIs) guide strategic decision-making:

1. **Employee Turnover Rate:** Measures the proportion of employees leaving the company within a given period. A high turnover rate signals retention issues possibly related to dissatisfaction or workload stress.  
2. **Employee Satisfaction Score:** Reflects employee contentment with the workplace environment. Low satisfaction scores are strongly linked to voluntary employee departures.  
3. **Workload Index:** Represents average monthly hours worked and the number of projects assigned. Excessive workload is associated with burnout and increased turnover risk.

These KPIs help Salifort Motors identify the factors affecting employee retention and develop policies promoting well-being and productivity. The company’s goals are to minimize turnover rates, maximize employee satisfaction, and balance workloads to prevent burnout.

This project leverages data science and machine learning techniques to predict which employees are at risk of leaving, enabling proactive HR interventions.

---

## Benefits of the Project

- **Cost Reduction:** Decrease expenses related to recruitment and training new employees.  
- **Improved Retention:** Enhance employee satisfaction and reduce turnover rates.  
- **Risk Identification:** Detect patterns that signal higher turnover risk.  
- **Strategic Decision Support:** Provide data-driven insights to guide HR policies.  
- **Promote Healthy Culture:** Support initiatives that foster a positive and productive work environment.  

---

## Project Conclusions

- Employees with high workloads, multiple projects, and low satisfaction levels are more likely to leave.  
- All employees managing 7 projects eventually left the company.  
- Employees with more than 6 years of tenure tend to stay longer.  
- A culture of excessive overtime is strongly linked to higher turnover.  
- Recent promotions (within the last 5 years) correlate with higher retention rates.  

---

## Proposed Solutions

1. **Reduce excessive workload:** Limit projects per employee and monitor burnout signs.  
2. **Promotions and recognition:** Establish clear policies to reward and retain talent.  
3. **Work culture reform:** Reevaluate performance metrics and overtime practices.  
4. **HR strategic engagement:** Facilitate team discussions to identify dissatisfaction drivers.  
5. **Feature engineering:** Create derived variables like “overworked” to better capture workload stress.  
6. **Adopt predictive models:** Implement Random Forest to identify turnover risk and guide interventions.  

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

| Model               | Accuracy | Recall (Leavers) | Precision (Leavers) |
|---------------------|----------|------------------|---------------------|
| Logistic Regression  | 82%      | 26%              | 44%                 |
| Decision Tree       | 94%      | 92%              | 78%                 |
| Random Forest       | 96%      | 90%              | 87%                 |

*Why Random Forest?*  
- Combines multiple trees for robustness  
- Captures complex variable interactions  
- Maintains stability with unseen data  

---

## Contact

| Platform | Link / Email                                                  |
|----------|--------------------------------------------------------------|
| LinkedIn | [linkedin.com/in/lucaspimentabarretto](https://www.linkedin.com/in/lucaspimentabarretto) |
| GitHub   | [github.com/LucasPBar](https://github.com/LucasPBar)         |
| Email    | lucaspimenta1805@gmail.com                                    |
