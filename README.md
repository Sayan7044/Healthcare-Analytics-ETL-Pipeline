# Healthcare-Analytics-ETL-Pipeline
"End-to-end Healthcare data pipeline: Data cleaning and transformation using Python (Pandas) with an interactive multi-page Power BI dashboard for operational insights."

🏥 Project Overview
This project involves a comprehensive analysis of patient diagnostic data to identify trends in department performance, patient demographics, and revenue generation. The goal was to transform raw, messy healthcare records into actionable insights for hospital management.

🛠️ The Data Pipeline (ETL)
Unlike standard dashboards, this project utilized Python and Pandas for the initial heavy lifting.
Data Cleaning: Handled missing values (specifically in the Gender and Diagnosis columns).
Transformation: Categorized ages into groups (Child, Adult, Young, Senior) using Pandas logic to allow for better demographic segmentation.
Data Loading: Exported the cleaned dataframe to a structured CSV optimized for Power BI’s Star Schema.

📊 Key Insights & Analytics
Departmental Dominance: Neurology and Cardiology drive the highest revenue ($0.97M and $0.96M respectively).
Operational Bottleneck: Cardiology has the highest average waiting time, suggesting a need for better resource allocation in that department.
Demographic Focus: ~80% of the patient base falls under the "Adult" category, with Diabetes being the leading diagnosis (~22% of total patients).

How to Use
- View the HealthCasre_Data.ipynb to see the Pandas transformation logic.
- Open the Health_Care_Project.pbix to interact with the multi-page report.

