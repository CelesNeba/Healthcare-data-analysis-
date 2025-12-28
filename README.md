# Healthcare-data-analysis-
Hospital operations, quality of care, and financial performance analysis


### Problem statement

A hospital needs a unified analytics solution to understand how patient care, operational performance, and financial outcomes are connected. Key metrics such as length of stay, readmissions, department utilization, and revenue performance are currently spread across multiple systems, making it difficult for leaders to identify performance trends, capacity issues, and improvement opportunities.

This project aims to integrate clinical, admissions, and billing data into a single analytics platform and provide insights that help the hospital improve patient outcomes, optimize resource use, and strengthen financial performance.


### Project title

Hospital operations, quality of care, and financial performance analysis

### Tools used

•	MySQL: Data storage, joins, KPI queries

• Jupyter Notebook (Python): Data validation, feature engineering, EDA

• Power BI: Executive dashboards & storytelling

### STEP 1: Define Business Questions

This analysis  will answer healthcare questions such as: 

### Operational

o	What is the average length of stay (LOS) by diagnosis and department?

o Which departments are over capacity?

### Quality of care

o Which diagnoses have the highest 30-day readmission rates?

o Are outcomes improving over time?

### Financial

o What diagnoses and departments drive the most revenue?

o Where are insurance reimbursement gaps?

### STEP 2: Data Model (Healthcare-Realistic Schema)

Tables I  will create

• patients

• admissions

• diagnoses

• procedures

• billing

• providers

### STEP 3: MySQL Database Schema

##### Table 1: patients
![Healthcare Patients Table Screenshot](https://github.com/CelesNeba/Healthcare-data-analysis-/blob/main/healthcare%20patients%20table%20screenshot.JPG)


##### Table 2: admissions
![Healthcare Admissions Table Screenshot](https://github.com/CelesNeba/Healthcare-data-analysis-/blob/main/healthcare%20admissions%20table%20screenshot.JPG)


##### Table 3: diagnoses
![Healthcare Diagnosis Table Screenshot](https://github.com/CelesNeba/Healthcare-data-analysis-/blob/main/healthcare%20diagnosis%20table%20screenshot.JPG)


##### Table 4: procedures
![Healthcare Procedures Table Screenshot](https://github.com/CelesNeba/Healthcare-data-analysis-/blob/main/healthcare%20procedures%20table%20screenshot.JPG)


##### Table 5: billing
![Healthcare Billing Table Screenshot](https://github.com/CelesNeba/Healthcare-data-analysis-/blob/main/healthcare%20billing%20table%20screenshot.JPG)



##### Table 6: providers
![Healthcare Provider Table Screenshot](https://github.com/CelesNeba/Healthcare-data-analysis-/blob/main/healthcare%20provider%20table%20screenshot.JPG)



### STEP 4: Generate synthetic healthcare data

#### Value 1: patients
![Healthcare Patients Table Value Screenshot](https://github.com/CelesNeba/Healthcare-data-analysis-/blob/main/healthcare%20patients%20table_Value%20screenshot.JPG)


#### Value 2: admissions
![Healthcare Admission Table Value Screenshot](https://github.com/CelesNeba/Healthcare-data-analysis-/blob/main/healthcare%20admission%20table_Value%20screenshot.JPG)


#### Value 3: diagnoses
![Healthcare Diagnoses Table Value Screenshot](https://github.com/CelesNeba/Healthcare-data-analysis-/blob/main/healthcare%20diagnoses%20table_Value%20screenshot.JPG)


#### Value 4: procedures
![Healthcare Procedures Table Value Screenshot](https://github.com/CelesNeba/Healthcare-data-analysis-/blob/main/healthcare%20procedures%20table_Value%20screenshot.JPG)


#### Value 5: billing
![Healthcare Billing Table Value Screenshot](https://github.com/CelesNeba/Healthcare-data-analysis-/blob/main/healthcare%20billing%20table_Value%20screenshot.JPG)



#### Value 6: providers
![Healthcare Providers Table Value Screenshot](https://github.com/CelesNeba/Healthcare-data-analysis-/blob/main/healthcare%20providers%20table_Value%20screenshot.JPG)


### STEP 5:  SQL queries

#### 1. Length of stay


##### Note: 
DATEDIFF() in MySQL returns the result in days (as an integer).

When we wrap it in AVG(), MySQL treats it as a numeric average, so it formats the result with four decimal places, but the value is still in days.

So:

5.0000 = 5 days

1.0000 = 1 day

The decimal formatting is just how MySQL displays averages, not hours or fractions.

![Mysql los screenshot](https://github.com/CelesNeba/Healthcare-data-analysis-/blob/main/Mysql%20los%20screenshot.JPG)





#### 2. Readmission proxy (within 30 days)

![Reamission within 30 days](https://github.com/CelesNeba/Healthcare-data-analysis-/blob/main/Reamission%20within%2030%20days.JPG)


#### 3.Revenue by department

![Total_Revenue_by_dept](https://github.com/CelesNeba/Healthcare-data-analysis-/blob/main/Total_Revenue_by_dept.JPG)





## 3 STEP 6: Jupyter Notebook (Python Analysis)

#### What I will do in Python

1. Connect to MySQL

2. Validate data quality

3. Engineer features

4. Exploratory Data Analysis (EDA)


![Jupyter analysis](https://github.com/CelesNeba/Healthcare-data-analysis-/blob/main/Jupyter%20analysis.JPG)


## STEP 7: Power BI dashboard

• Overall patient care rating

• Total admission by admission type

• Revenue by diagnosis

• Average length of stay

• Total admission by month and year

• Average satisfaction rating by department 






## 🏥 Healthcare Performance & Quality Analytics Dashboard

This project analyzes key healthcare performance metrics including patient admissions, operational efficiency, financial outcomes, and quality-of-care indicators such as patient satisfaction and readmission patterns.

![Healthcare Dashboard](https://github.com/CelesNeba/Healthcare-data-analysis-/blob/main/healthcare%20dashboard.JPG)

### 📊 Key Insights Visualized
- 🩺 **Patient Satisfaction & Quality of Care**
- 🏥 **Total Admissions & Length of Stay**
- 💵 **Revenue & Financial Performance**
- 🧾 **Department-Level Performance Metrics**

Built using **Power BI, DAX, and simulated healthcare datasets** to demonstrate data modeling, analytics, and dashboard storytelling skills.



### My recommendation

Based on the analysis, I recommend prioritizing improvements in care quality and operational efficiency, particularly in departments with lower patient satisfaction and longer average lengths of stay. Strengthening process workflows, enhancing staff–patient communication, and targeting resource optimization in underperforming units will help reduce readmissions, improve patient outcomes, and sustain financial performance while maintaining high-quality care delivery.





