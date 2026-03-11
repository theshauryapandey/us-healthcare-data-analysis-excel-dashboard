<div align="center">

# 🏥 US Healthcare Data Analysis Dashboard

📊 **Healthcare Analytics Project | Excel Dashboard | Data Analysis**

![Excel](https://img.shields.io/badge/Tool-Excel-green)
![PowerQuery](https://img.shields.io/badge/Tool-PowerQuery-blue)
![DataAnalysis](https://img.shields.io/badge/Field-Data%20Analytics-orange)
![Dashboard](https://img.shields.io/badge/Project-Dashboard-purple)
![Status](https://img.shields.io/badge/Status-Completed-success)

</div>

---

# 📊 Project Overview

Healthcare organizations generate massive amounts of operational and patient data.  
Without proper analysis, it becomes difficult for healthcare executives to understand patterns affecting:

- Treatment costs  
- Patient demographics  
- Hospital resource utilization  

This project analyzes **10,000 patient records from 100 hospitals** to uncover insights about:

✔ Patient demographics  
✔ Medical condition distribution  
✔ Hospital admission trends  
✔ Healthcare costs  
✔ Insurance provider impact  

The goal is to convert **raw healthcare data into actionable insights** that support **data-driven decision making**.

---

# 🎯 Business Problem

The **US Healthcare Department** required analysis to answer three key questions.

### 1️⃣ Demographic Analysis of Medical Conditions
Identify the most common medical conditions across different patient demographic groups.

### 2️⃣ Patient Price Optimization
Analyze the **average billing amount** across multiple factors and recommend ways to reduce healthcare costs.

### 3️⃣ Hospital Resource Management
Identify **hospital admission trends** to improve workload planning and resource management.

---

# 📂 Dataset Information

The dataset contains healthcare records from **100 hospitals in the US healthcare system**.

### Dataset Size

| Metric | Value |
|------|------|
| Total Patients | 10,000 |
| Hospitals | 100 |
| Medical Conditions | 6 Types |
| Insurance Providers | Multiple |

---

# 📊 Dataset Columns

| Column | Description |
|------|-------------|
| Age | Patient age |
| Gender | Patient gender |
| Medical Condition | Diagnosed disease |
| Hospital | Hospital where patient was admitted |
| Insurance Provider | Patient insurance company |
| Admission Type | Emergency, Elective, Urgent |
| Billing Amount | Total treatment cost |
| Length of Stay | Number of hospital days |
| Admission Date | Date of hospital admission |

---

# 📊 Key Performance Indicators

| KPI | Value |
|------|------|
| 👥 Total Patients | 10,000 |
| 💰 Average Billing Amount | $23,388.57 |
| 🏥 Average Length of Stay | 13.82 Days |
| 🚑 Emergency Admission Rate | 35.87% |
| ⚕️ Most Common Condition | Hypertension |

---

# 🛠 Tools & Technologies

- Microsoft Excel  
- Power Query  
- Pivot Tables  
- Data Cleaning  
- Data Transformation  
- Data Visualization  
- Interactive Dashboard Design  

---

# 🔄 Data Analysis Workflow

### 1️⃣ Data Collection
Imported the raw healthcare dataset containing patient, hospital, and insurance information.

### 2️⃣ Data Cleaning
Performed preprocessing tasks:

- Removed inconsistencies  
- Standardized categorical values  
- Handled missing data  

### 3️⃣ Data Transformation
Created additional analytical fields:

- Age Groups  
- Admission Month  
- Length of Stay  
- Cost Aggregation Metrics  

### 4️⃣ Data Analysis
Analyzed relationships between:

- Demographics and diseases  
- Admission types and hospital workload  
- Billing amounts and medical conditions  

### 5️⃣ Dashboard Development
Built an **interactive Excel dashboard** with filters for:

- Age group  
- Gender  
- Hospital  
- Insurance provider  
- Admission type  

### 6️⃣ Insights Generation
Converted analytical findings into **business insights for healthcare executives**.

---

# 📸 Dashboard Preview

<img src="dashboard.png" width="900">

---

# 🧮 Calculated Columns & Formulas

| Column | Purpose | Formula |
|------|------|------|
| Age Group | Categorize patients into demographic groups | `=IF([Age]<19,"0–18",IF([Age]<36,"19–35",IF([Age]<51,"36–50",IF([Age]<66,"51–65","66+"))))` |
| Length of Stay | Calculate hospital stay duration | `=[Discharge Date]-[Admission Date]` |
| Admission Month | Extract month for time analysis | `=TEXT([Admission Date],"mmm-yyyy")` |
| Billing Validation | Detect missing billing values | `=IF([Billing Amount]="","Check Billing","OK")` |
| LOS Validation | Detect incorrect stay calculations | `=IF([Length of Stay]<0,"Check Dates","OK")` |

---

# 📊 Data Visualization

Charts used in the dashboard:

| Chart | Purpose |
|------|------|
| Stacked Bar Chart | Condition distribution by age group |
| Column Chart | Billing comparison |
| Line Chart | Admission trends |
| Bar Chart | Hospital performance |

---

# 🔍 Key Insights

### 1️⃣ Hypertension is the Most Common Condition
Hypertension appears most frequently across multiple age groups.

### 2️⃣ Higher Costs for Cancer and Diabetes
These conditions show significantly higher treatment costs.

### 3️⃣ Older Patients Drive Hospital Demand
Patients aged **51+ represent the largest share of hospital admissions**.

### 4️⃣ High Emergency Admission Rate
Approximately **35.87% of hospital admissions** are emergency cases.

### 5️⃣ Hospital Efficiency Variation
Length of stay varies significantly across hospitals.

---

# 📈 Business Impact

### 🏥 Improved Resource Allocation
Hospitals can better manage:

- Staff scheduling  
- ICU bed availability  
- Emergency department workload  

### 💰 Healthcare Cost Optimization
Helps identify **high-cost treatments and cost drivers**.

### 🧑‍⚕️ Preventive Healthcare
High hypertension prevalence suggests **focus on preventive care programs**.

### 📊 Data-Driven Decisions
Provides healthcare leaders with **clear operational insights**.

---

# 📁 Project Structure

```
Healthcare-Data-Analytics-Dashboard
│
├── Healthcare_Dataset.xlsx
├── Excel_Dashboard.xlsx
├── dashboard.png
└── README.md
```

---

# 🚀 How to Use

### 1️⃣ Clone Repository

```bash
git clone https://github.com/yourusername/healthcare-data-analysis.git
```

### 2️⃣ Open Excel Dashboard

Open **Excel_Dashboard.xlsx**

### 3️⃣ Explore Dashboard

Use **slicers and filters** to analyze trends.

---

# 📌 Skills Demonstrated

✔ Data Cleaning  
✔ Data Transformation  
✔ Exploratory Data Analysis  
✔ Dashboard Development  
✔ Data Visualization  
✔ Business Insight Generation  
✔ Excel Automation  

---

# 👨‍💻 Author

**Shaurya Pandey**

📊 Data Analyst | MIS Executive  

**Skills**

- Advanced Excel  
- Power BI  
- SQL  
- Python  

🔗 LinkedIn: (Add your LinkedIn profile link)

---

⭐ If you found this project useful, consider giving it a **star on GitHub**.1️⃣ Demographic Analysis of Medical Conditions
Identify the most common medical conditions across different patient demographic groups.
2️⃣ Patient Price Optimization
Analyze the average billing amount across multiple factors and recommend ways to reduce healthcare costs.
3️⃣ Hospital Resource Management
Identify admission trends over time to help hospitals improve resource planning and workload management.
📂 Dataset Information
The dataset contains healthcare records from 100 hospitals in the US healthcare system.
Dataset Size
Metric
Value
Total Patients
10,000
Hospitals
100
Medical Conditions
6 Types
Insurance Providers
Multiple
Key Dataset Columns
Column
Description
Age
Patient age
Gender
Patient gender
Medical Condition
Diagnosed disease
Hospital
Hospital where patient was admitted
Insurance Provider
Patient insurance company
Admission Type
Emergency, Elective, Urgent
Billing Amount
Total treatment cost
Length of Stay
Number of hospital days
Admission Date
Date of hospital admission
📊 Key Performance Indicators (KPIs)
KPI
Value
👥 Total Patients
10,000
💰 Average Billing Amount
$23,388.57
🏥 Average Length of Stay
13.82 Days
🚑 Emergency Admission Rate
35.87%
⚕️ Most Common Condition
Hypertension
🛠 Tools & Technologies Used
The project was built using:
Microsoft Excel
Power Query
Pivot Tables
Data Cleaning
Data Transformation
Data Visualization
Interactive Dashboard Design
🔄 Data Analysis Workflow
1️⃣ Data Collection
Imported the raw healthcare dataset containing patient, hospital, and insurance information.
2️⃣ Data Cleaning
Performed preprocessing tasks:
Removed inconsistencies
Standardized categorical variables
Handled missing values
3️⃣ Data Transformation
Created additional fields for analysis:
Age groups
Admission month
Length of stay
Cost aggregation metrics
4️⃣ Data Analysis
Explored relationships between:
Demographics and medical conditions
Admission types and hospital workload
Billing amount and treatment categories
5️⃣ Dashboard Creation
Built an interactive Excel dashboard that allows filtering by:
Age group
Gender
Hospital
Insurance provider
Admission type
6️⃣ Insights Generation
Converted analysis results into clear business insights for healthcare executives.
📸 Dashboard Preview
The dashboard provides an executive overview of healthcare trends including demographics, costs, and hospital performance.
�
🧮 Calculated Columns & Formulas Used
Several calculated columns were created to transform raw data into analysis-ready variables.
Column
Purpose
Formula
Age Group
Categorize patients into demographic buckets
=IF([Age]<19,"0–18",IF([Age]<36,"19–35",IF([Age]<51,"36–50",IF([Age]<66,"51–65","66+"))))
Length of Stay
Calculate hospital stay duration
=[Discharge Date]-[Admission Date]
Admission Month
Extract month for time-series analysis
=TEXT([Admission Date],"mmm-yyyy")
Billing Validation
Check missing billing values
=IF([Billing Amount]="","Check Billing","OK")
LOS Validation
Identify incorrect stay calculations
=IF([Length of Stay]<0,"Check Dates","OK")
These calculations helped ensure the dataset was clean, structured, and analysis-ready.
⚙️ Advanced Excel Techniques Used
This project demonstrates several advanced Excel capabilities used by professional data analysts.
🔹 Power Query (ETL)
Used for:
Importing raw data
Cleaning inconsistent values
Transforming datasets into analysis-ready format
🔹 Pivot Tables
Used to perform multi-dimensional analysis such as:
Condition distribution by age group
Average billing by condition
Admission trends
🔹 Interactive Dashboard with Slicers
Dashboard filters allow dynamic exploration by:
Age group
Gender
Hospital
Insurance provider
Admission type
🔹 KPI Metrics
Excel formulas and pivot calculations were used to create executive-level metrics.
🔹 Data Visualization
Charts used in the dashboard include:
Chart Type
Purpose
Stacked Bar Chart
Condition distribution by age group
Column Chart
Billing comparison
Line Chart
Admission trends
Bar Chart
Hospital performance
🔍 Key Insights
1️⃣ Hypertension is the Most Common Condition
Hypertension appears most frequently across multiple age groups.
2️⃣ Higher Costs for Certain Conditions
Patients with Cancer and Diabetes tend to have higher treatment costs.
3️⃣ Older Patients Drive Hospital Demand
Patients aged 51+ account for the largest share of hospital admissions.
4️⃣ Emergency Admissions Are Significant
Approximately 35.87% of hospital admissions are emergency cases.
5️⃣ Variation in Hospital Efficiency
Length of stay varies significantly across hospitals, indicating differences in operational efficiency.
📈 Business Impact of This Analysis
🏥 Improved Resource Allocation
Hospitals can better manage:
Staff allocation
ICU bed availability
Emergency department workload
💰 Healthcare Cost Optimization
Identifying high-cost treatments helps improve billing efficiency and cost transparency.
🧑‍⚕️ Preventive Healthcare Strategy
Since hypertension is highly prevalent, hospitals can focus on preventive healthcare programs.
📊 Data-Driven Decision Making
The dashboard enables executives to quickly analyze trends and make strategic decisions.
📁 Project Structure
Copy code

Healthcare-Data-Analytics-Dashboard
│
├── Healthcare_Dataset.xlsx
├── Excel_Dashboard.xlsx
├── dashboard.png
└── README.md
🚀 How to Use This Project
Step 1
Clone the repository
Copy code

git clone https://github.com/yourusername/healthcare-data-analysis.git
Step 2
Open the Excel workbook
Step 3
Explore pivot tables and the dashboard
Step 4
Use filters to analyze healthcare trends
📌 Skills Demonstrated
This project showcases the following data analyst skills:
Data Cleaning
Data Transformation
Exploratory Data Analysis
Dashboard Development
Data Visualization
Business Insight Generation
Excel Automation
👨‍💻 Author
Shaurya Pandey
📊 Data Analyst | MIS Executive
Skills:
Advanced Excel
Power BI
SQL
Python
🔗 LinkedIn: (Add your LinkedIn profile here)
