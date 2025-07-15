# 📊 Employee Performance & Project Cost Automation using Python & Pandas

This project showcases a fictional HR use case where employee performance evaluation, promotions, demotions, and project cost reporting have been automated using Python and Pandas. It simulates an end-to-end data pipeline for HR analytics and reporting.

## 🚀 Project Overview

### Objective:
Automate HR evaluation rules, calculate project costs, determine bonuses, and process promotions/demotions based on employee performance data.

### Key Features:
- Automated employee bonus calculations based on project completion.
- Designation adjustments based on project failure counts and employee age.
- Running average imputation for missing project costs.
- Clean and formatted dataset ready for further analytics or reporting.
- Conditional formatting of employee titles based on gender.

---

## 🗂️ Data Sources

| File        | Description                     |
|-------------|---------------------------------|
| `employee.csv`   | Basic employee demographics (ID, Name, Gender, City, Age) |
| `seniority.csv`  | Employee designation levels |
| `project.csv`    | Project assignments, costs, and status (Finished, Ongoing, Failed) |

---

## 🔧 Technologies Used
- **Python 3.x**
- **Pandas**
- **NumPy**
- **Jupyter Notebook**

---

## 📄 Workflow Summary

### 1️⃣ Data Cleaning & Preparation:
- Split full names into `First Name` and `Last Name`
- Filled missing project costs using a running average technique
- Ensured proper data types for all numeric columns

### 2️⃣ Data Integration:
- Merged employee, seniority, and project data into a unified dataset

### 3️⃣ Business Logic Implementation:
- Bonus = 5% of project cost if the project is marked 'Finished'
- Employees demoted for failed projects (designation level increased by count of failures)
- Employees promoted if age > 29 (designation level decreased by 1, if > 1)
- Removed employees with designation level exceeding 4

### 4️⃣ Additional Processing:
- Gender-based title formatting (`Mr.` / `Mrs.`)
- Summarized total project cost per employee
- City-based filtering example (cities containing the letter 'o')

---

## 📊 Outputs (CSV Files Generated)
- `employee_updated.csv`
- `project_filled.csv`
- `final.csv`
- `final_with_bonus.csv`
- `final_demotion_applied.csv`

---

## 🔍 Key Insights
- Clean, consolidated dataset for HR reporting
- Clear visibility into project costs, bonuses, and employee status
- Structured, reproducible Python workflow for HR analytics

---


## 💡 How to Run This Project

### Requirements:
```bash
pip install pandas numpy
```

### Recommended Environment:
- Jupyter Notebook / Jupyter Lab
- VS Code with Python Extension

### Running the Notebook:
Open `Employee_Performance_Analysis.ipynb` in Jupyter and execute step-by-step.

---

## 👨‍💻 About Me

**Gurpreet Singh** | Data Analyst | Python | Power BI | SQL  
🔗 [LinkedIn](https://linkedin.com/in/gurpreetsingh1998)  
💻 [GitHub](https://github.com/gurpreet998)  
🌐 [Portfolio](https://gurpreet-singh-998.vercel.app/)  
📩 gs268197@gmail.com  

---

## ⭐ If you found this useful, feel free to star this repository! ⭐
