# Analyst-Portfolio
A collection of projects showcasing my studies and experimentations in SQL, Python, and techniques essential to data analysis.

## About Me

I bring a unique perspective to data analytics through a diverse professional background spanning manufacturing operations, AI/machine learning, and education. Currently pursuing a **B.S. in Data Analytics** at Western Governors University, I pair analytical precision with strong communication and cross-cultural expertise.

My journey has provided a distinctive toolkit of technical and soft skills. In my recent role as a Junior Account Specialist at EPTAM Precision Molding, I applied data analytics to boost KPIs such as gross margin and on-time delivery. Earlier work as an educator sharpened my ability to translate complex concepts into accessible insights—essential in analytics. Advanced Japanese proficiency and international experience further add a global dimension to my profile.

**I Excel In:**
- **Data Analysis with Python & SQL**  
- **Business Process Optimization**  
- **Cross-Functional Communication**  
- **Data Visualization & Reporting**  
- **Problem Solving & Root-Cause Analysis**  
- **Project Coordination**

My varied background isn’t just a career path—it’s a strength that lets me approach analytics with a human-centered perspective. I’m especially interested in projects where my mix of technical skill and interpersonal insight can drive meaningful results.

I’m currently seeking opportunities to apply this blend of analytical, communicative, and cross-cultural skills to help organizations make data-driven decisions.

## Projects

### Analyzing Gross-Margin Fluctuations in a Manufacturing Environment

**Goal**  
Investigate the drivers behind a sudden dip in profit margins highlighted on enterprise-wide Power BI dashboards and recommend data-backed actions.

---

#### Approach

1. **Data Collection & Integration**  
   - Pulled historical sales and live production data from the ERP via **SAP Crystal Reports**.  
   - Scraped internal pricing-demo spreadsheets for costing assumptions and factor percentages.  
   - Conducted interviews with Engineering, Finance, and Production teams to validate data and define outlier-handling rules.  
   - Consolidated cleaned data in a local **MySQL** database and staged it in **Excel** for analysis.

2. **Analysis Techniques**  
   - Multiple linear regression to quantify cost drivers.  
   - Time-series analysis on margins, order volumes, material prices, and production costs.  
   - Exploratory data analysis and anomaly detection to surface inconsistencies between ERP values and pricing spreadsheets.

3. **Visualization & Communication**  
   - Built pivot-table dashboards and charts in Excel.  
   - Summarized insights and process-alignment recommendations in an executive presentation.

---

#### Key Findings

- **Order quantity** and **raw-material price** explained the majority of the margin variance.  
- Costing logic differed between systems:  
  - The ERP amortized setup costs across every 1,000-piece batch.  
  - Pricing tools treated setup as a one-time charge, enabling aggressive quantity discounts.  
- Additional factors (cycle time, secondary operations, BOM discrepancies) affected individual products but were not systemic.

---

#### Outcome

The analysis clarified costing misalignments, enabling leadership to realign pricing models and update ERP parameters for greater margin visibility. The resulting workflow changes now provide more accurate margin forecasting and support continued KPI improvement.

---

#### Skills & Tools

`SAP Crystal Reports` • `MySQL` • `Excel (Power Query, PivotTables)` • Multiple Linear Regression • Time-Series Analysis • ETL • EDA • Root-Cause Analysis • Data Visualization • Cross-Functional Collaboration


### Exploring NYC Public School SAT Performance

**Goal**  
Discover meaningful trends in SAT results across **375 NYC public high schools**.

**Approach**  
- Analyzed a dataset with school names, boroughs, percent of students tested, and average SAT section scores (Math, Reading, Writing).  
- Used **Python** (`pandas`, `NumPy`) in a **Jupyter Notebook** to clean, transform, and explore the data.  
- Built targeted subsets:  
  - Schools with average **Math > 640** (80 % of the possible 800).  
  - The **top 10** schools based on combined SAT scores.  
  - The borough with the **largest standard deviation** of total scores.  
- Performed EDA with scatterplots to visualize the relationship between testing-rate percentages and total scores, both by school and by borough.

**Code**
[Exploring NYC Public School SAT Performance.ipynb](notebook.ipynb)

**Key Findings**  
- A higher **percentage of students tested** correlated with both a **higher average total SAT score** and a **larger score spread** within the borough.  
- Insights generated several hypotheses for future study, including:  
  1. Environmental or resource factors may affect both test participation and performance.  
  2. Early-grade “practice” test-takers widen score variance yet can lift overall averages.  
  3. Increasing participation in the **Bronx** and **Brooklyn** could improve scores if supporting factors are addressed.  

**Skills & Tools**  
`EDA` • `data manipulation` • `summary statistics` • `data visualization`  
Technologies: **Python**, **pandas**, **NumPy**, **matplotlib**, **Jupyter Notebook**

**Code**  
[Project repository / notebook](https://www.datacamp.com/projects/1596)
