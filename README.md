## Bank Analysis Report
## 🎯 Objective
The report dives into critical loan metrics, tracking dynamic changes over time to:
- Monitor loan portfolio health
- Uncover lending trends
- Support strategic decisions and risk assessment

## 🏦 Business Problem
The bank needed a centralized dashboard to monitor:
- The volume and status of loan applications
- Amounts funded and received
- Risk indicators such as interest rates and DTI
- Good vs. bad loan performance across time and region
## 🧾 Data Source
The data was stored in **Microsoft SQL Server**, consisting of:
- 38,576 loan applications
- Fields like application date, loan status, funded amount, amount received, interest rate, DTI, term, and location

## 🛠 Tools & Technologies
- **SQL Server** – Data storage, preprocessing, and querying
- **Power BI Desktop** – Dashboard creation and DAX analysis
- **DAX** – Custom measures and time intelligence
- **Power Query** – Data transformation and modeling
- **Excel** – For initial data verification
- **PySpark (in future expansion)** – Potential for handling large-scale data

## ✨ Project Highlights

### 🔸 SQL Server
- Optimized data loading and structured storage
- Wrote efficient SQL queries for meaningful extractions
- Ensured data completeness and consistency

### 🔸 Power BI
- Imported cleaned data from SQL Server
- Validated data types and structure for reliable reporting
- Created calculated measures using **DAX**
- Built visuals: KPI cards, donut charts, area graphs, bar charts, and map visualizations
- Implemented Role-Level Security (RLS) and drill-through features
- Delivered a fully interactive and dynamic report


## 📈 Key Insights

### Loan Application Trends:
- Total loan applications processed: **38,576**
- Applications in December: **4,314** (↑ from November's 4,035)

### Funded Amount:
- Total funded amount: **$435.76 million**
- December funding: **$53.98 million** (↑ from $47.75 million)

### Amount Received:
- Total amount received: **$473.07 million**
- December received: **$58.07 million** (↑ from $50.13 million)

### Interest Rates:
- Average overall interest rate: **12.04%**
- December average: **12.35%** (↑ from 11.94%)

### Debt-to-Income (DTI):
- Average overall DTI: **13.32**
- December average: **13.66** (↑ from 13.30)

### Loan Performance:
- **Good Loans:** 33,243 applications (86.17%)  
  - Funded: **$370.22M**, Received: **$435.79M**
- **Bad Loans:** 5,333 applications (13.82%)  
  - Funded: **$65.53M**, Received: **$37.28M**

## 🖼 Dashboard Screenshots
> *![Bank Analysis Report](https://github.com/user-attachments/assets/3e0ada16-9282-4851-b25e-d3b0f6f6f88d)*
📊 Explore the Live Dashboard:https://app.powerbi.com/view?r=eyJrIjoiOWY3NDZlOTItNDY2OC00ZTI3LWI3ZDgtMTA1NDU3MDRmYzNiIiwidCI6IjRlZjY3YTA1LTEwOTAtNDU2MC1hMjE4LWI4MzdhNWVkN2Q2MSJ9

## ✅ Recommendations
- **Optimize approval criteria** for applicants with DTI > 15, as these correlate with higher default rates.
- **Increase staff** during December–January to manage peak application load.
- **Expand operations** in regions with consistently high repayment rates (use map visuals for targeting).
- Use insights to **refine lending strategy** and reduce bad loan ratio from 13.8% to under 10%.


## 🙋‍♂️ About Me  
Sanjay Vijay Divate  
📧 sanjaydivate12@gmail.com  
📱 +91-9404262162  
💼 Data Analytics Professional | Power BI | SQL | Python | HDFS | PySpark | Databricks | Tableau | Advanced Excel | Data Analysis | Visualization | Reporting | Data Modelling | Aspiring Data Engineer  
🌐 [LinkedIn](https://www.linkedin.com/in/sanjay-divate/)

