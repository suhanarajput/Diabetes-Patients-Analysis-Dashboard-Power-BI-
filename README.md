# 📊 Diabetes Patient Analysis Dashboard

## Project Overview
This project analyzes a healthcare dataset of **768 patients** to identify key factors associated with diabetes. The goal is to explore patterns and differences between diabetic and non-diabetic individuals using data analysis and visualization techniques.

Data cleaning and exploratory analysis were performed using **Jupyter Notebook**, followed by building an interactive dashboard in **Power BI**.

---

## Objective
- Analyze patient health data to identify indicators of diabetes  
- Compare diabetic vs non-diabetic patients  
- Build an interactive dashboard for insights  

---

## Tools & Technologies
- Python (Pandas, NumPy)  
- Jupyter Notebook  
- Power BI  
- DAX & Power Query  

---

## Dataset Information
- Total Patients: **768**  
- Diabetic: **268 (34.9%)**  
- Non-Diabetic: **500 (65.1%)**  

### Features:
- Pregnancies  
- Glucose  
- Blood Pressure  
- Skin Thickness  
- Insulin  
- BMI  
- Diabetes Pedigree Function  
- Age  
- Outcome (0 = Non-Diabetic, 1 = Diabetic)  

---

## Data Cleaning & Preprocessing
- Replaced invalid zero values in:
  - Glucose, Blood Pressure, Skin Thickness, Insulin, BMI  
- Converted invalid values to **NaN**  
- Handled missing values using **median imputation**  
- Prepared clean dataset for analysis  

---

## Key Insights

- **Glucose Levels:**  
  Diabetic patients have significantly higher glucose levels, making it the strongest indicator.

- **BMI (Body Mass Index):**  
  Diabetic patients have higher BMI on average, with most falling in the **30–40 range**.

- **Age:**  
  Diabetic patients are generally older than non-diabetic patients.

- **Pregnancies:**  
  Slightly higher averages are observed among diabetic patients, but this is a weaker factor.

---

## Dashboard Features
- KPI Cards (Total Patients, Diabetic, Non-Diabetic, % Diabetic)  
- Pie Chart for distribution  
- Bar Charts:
  - Average Glucose by Outcome  
  - Average BMI by Outcome  
  - Average Age by Outcome  
- Histogram:
  - BMI Distribution by Outcome  

---

## Dashboard Preview
_Add screenshots of your Power BI dashboard here_

---

## 📌 Conclusion
The analysis shows that **glucose level is the strongest predictor of diabetes**, followed by **BMI and age**. These insights can help in early detection and better understanding of diabetes risk.

---
