## 📊 Employee Attrition Analysis & Dashboard

## 📝 Project Overview
This end-to-end data analytics project investigates the primary drivers of employee turnover using the IBM HR Analytics dataset. By performing data cleaning and exploratory data analysis (EDA) in Python, and building an interactive dashboard in Tableau, this project uncovers actionable business insights to help reduce attrition rates and improve employee retention.

## 🔗 Live Interactive Dashboard
**View the live Tableau Dashboard here:**  
👉 https://public.tableau.com/views/EmployeeAttritionAnalysis_17916394287150/EmployeeAttritionAnalysis?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

## 💡 Key Performance Indicators (KPIs)
* **Total Employees Analyzed:** 1,470
* **Total Attrition (Employees Left):** 237
* **Overall Attrition Rate:** 16.12%
* **Retention Rate:** 83.88%

## 🚀 Key Findings & Business Insights
Based on the EDA and dashboard visualizations, the primary drivers of employee attrition are:
1. **Overtime:** Employees working continuous overtime have a disproportionately higher risk of burnout and resignation.
2. **Compensation:** Lower monthly income brackets (average $4,787 for leavers vs. $6,833 for stayers) strongly correlate with early departures.
3. **Job Satisfaction:** Staff reporting low job satisfaction (Rating 1) show significantly higher quit rates.
4. **Commute Distance:** Employees with longer commutes (averaging over 10.6 miles) exhibit higher turnover compared to those living closer to the office.
5. **Departmental Trends:** The Research & Development (R&D) and Sales departments experience the highest total volume of attrition.

## 📂 Repository Structure
* **[`notebooks/`](./notebooks/)**: Contains the Python Jupyter Notebook ([`data_cleaning.ipynb`](./notebooks/data_cleaning.ipynb)) used for raw data preprocessing, handling data quality issues, and conducting Exploratory Data Analysis (EDA).
* **[`deliverables/`](./deliverables/)**: Contains formal PDF reports generated for this project:
  * [Business_Insights.pdf](./deliverables/Business_Insights.pdf) - Final actionable recommendations for HR.
  * [Data_Cleaning_Reports.pdf](./deliverables/Data_Cleaning_Reports.pdf) - Documentation of data formatting and cleaning steps.
  * [EDA_Report.pdf](./deliverables/EDA_Report.pdf) - Detailed statistical findings and visual charts.
    
## 🛠️ Tech Stack Used
* **Data Cleaning & EDA:** Python (Pandas, NumPy, Matplotlib, Seaborn)
* **Environment:** Jupyter Notebook / VS Code
* **Data Visualization:** Tableau Public

## 👨‍💻 How to Use This Repository
1. Click the **Live Dashboard Link** above to interact with the Tableau visualizations.
2. Navigate to the `deliverables/` folder to read the formal PDF reports.
3. Review the `notebooks/` folder to see the Python code used for cleaning and exploring the raw dataset.
