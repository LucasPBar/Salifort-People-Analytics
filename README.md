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

This project was developed as part of the **Google Advanced Data Analytics Professional Certificate** to apply data science and machine learning techniques in predicting employee turnover at the fictional company Salifort Motors. The HR department at Salifort Motors has gathered comprehensive employee data aiming to enhance workforce satisfaction and retention. However, they faced uncertainty about how to extract actionable insights from this data. They engaged a data analytics professional to deliver data-driven answers to a key question: which factors are most likely to lead employees to leave the company?

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

- **Cost Reduction:**
Lowering expenses related to recruitment and training is a clear opportunity to enhance operational efficiency. By minimizing employee turnover, the company avoids recurring costs associated with hiring and onboarding new staff. These savings can be redirected to innovation initiatives, process improvements, or commercial expansion, strengthening the organization’s strategic position.

- **Improved Retention:**
Retaining skilled and engaged professionals contributes directly to team stability and performance. Long-term retention supports project continuity, preserves internal knowledge, and reduces the disruptions caused by unexpected departures. Moreover, a strong retention rate enhances the company’s reputation as an attractive workplace for top talent.

- **Risk Identification:**
The ability to anticipate potential resignations allows the company to take preventive action. By analyzing behavioral patterns and employee sentiment, it becomes possible to implement targeted measures to improve the work environment, adjust leadership practices, or offer development opportunities. This proactive approach helps maintain team productivity and reduces operational surprises.

- **Support for strategic decision-making:**
Data-driven decisions are more accurate and aligned with business goals. Predictive and exploratory analytics empower the HR department to act as a strategic partner, offering valuable insights on talent allocation, organizational structure, and succession planning. This strengthens the company’s adaptability in dynamic market conditions.
 
- **Promote Healthy Culture:**
Investing in a positive work environment encourages collaboration, creativity, and a sense of belonging. A well-defined culture boosts employee engagement, reduces absenteeism, and enhances innovation capacity. Organizations that cultivate strong values and trust-based relationships tend to be more resilient and appealing to high-performing professionals. 

---

## Project Conclusions

- Employees with high workloads, multiple projects, and low satisfaction levels are more likely to leave. This pattern highlights a clear risk of burnout and emotional fatigue. By identifying these profiles, the company can implement task redistribution policies, wellness programs, and active listening strategies to reduce turnover and retain valuable talent.
- All employees managing 7 projects eventually left the company. This finding underscores the need for healthy operational boundaries. Leadership should reassess project allocation per employee to ensure a balance between productivity and well-being, directly contributing to retention and engagement. 
- Employees with more than 6 years of tenure tend to stay longer. Long-term employment is linked to stability, trust, and cultural alignment. Investing in career development and ongoing recognition for this group strengthens organizational culture and reduces turnover.
- A culture of excessive overtime is strongly linked to higher turnover. This behavior suggests a high-pressure environment that may compromise mental health and performance. Revising time management practices and promoting balanced productivity are key to building a more sustainable workplace. 
- Recent promotions (within the last 5 years) correlate with higher retention rates. Recognizing and rewarding internal growth is a powerful motivator. Establishing clear policies for career progression and professional development helps boost engagement and employee loyalty.

---

## Proposed Solutions

1. **Reduce excessive workload:**
Limiting the number of projects per employee and monitoring signs of burnout are essential steps to protect mental health and maintain productivity. By balancing task distribution, the company fosters a more sustainable environment, lowers burnout risk, and improves talent retention.
2. **Promotions and recognition:**
Establishing clear policies for career advancement strengthens the employee-company relationship. Recognizing achievements and offering growth opportunities boosts engagement, enhances motivation, and reduces the likelihood of resignation. 
3. **Work culture reform:**
Reevaluating performance metrics and overtime practices is key to building a healthier organizational culture. By prioritizing sustainable outcomes over exhaustive work hours, the company promotes well-being and reinforces a sense of fairness and balance.
5. **HR strategic engagement:**
Facilitating team discussions to uncover sources of dissatisfaction enables more empathetic and effective action. HR becomes a transformative force, implementing changes that reflect employees’ real needs and build institutional trust.

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
