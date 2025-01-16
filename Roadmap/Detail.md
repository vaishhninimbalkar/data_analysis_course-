# Data Analysis Course Outline

## **Chapter 1: Data Analysis with Excel**
### **Overview:**
Excel is a powerful and accessible tool for data analysis. This chapter focuses on using its features to analyze, summarize, and visualize data.

### **Topics:**
#### 1.1 Introduction to Excel for Data Analysis
- What is Excel?
- Importance of Excel in data analysis.
- Overview of Excel’s interface and functionalities (Ribbon, Sheets, and Menus).

#### 1.2 Data Cleaning in Excel
- Removing duplicates.
- Using filters to sort and organize data.
- Text-to-columns and splitting data.
- Using conditional formatting to highlight anomalies.

#### 1.3 Excel Formulas and Functions for Analysis
- Commonly used formulas:
  - **SUM, AVERAGE, COUNT, MIN, MAX.**
  - Logical functions: **IF, AND, OR, NOT.**
  - Text functions: **CONCATENATE, LEFT, RIGHT, FIND, TRIM.**
  - Lookup functions: **VLOOKUP, HLOOKUP, INDEX, MATCH.**
- Using nested formulas.

#### 1.4 Data Visualization in Excel
- Creating basic charts: bar, column, line, and pie charts.
- Advanced charts: scatter plots, histograms, and pivot charts.
- Adding slicers for interactivity.

#### 1.5 Pivot Tables and Dashboards
- Creating and formatting pivot tables.
- Adding calculated fields in pivot tables.
- Designing dynamic dashboards with charts and slicers.

### **Practical Exercises:**
- Analyze sales data using pivot tables.
- Visualize trends in employee performance using charts.
- Clean and prepare messy datasets for analysis.

---

## **Chapter 2: Data Analysis with SQL**
### **Overview:**
SQL (Structured Query Language) is used to extract, manipulate, and analyze data stored in relational databases. This chapter covers SQL’s essential commands and techniques.

### **Topics:**
#### 2.1 Introduction to SQL
- What is SQL?
- Understanding relational databases.
- Overview of database management systems (MySQL, PostgreSQL, SQLite).

#### 2.2 SQL Queries for Data Analysis
- **SELECT:** Extracting data from tables.
- **WHERE:** Filtering data with conditions.
- **ORDER BY:** Sorting data (ascending/descending).
- **GROUP BY:** Summarizing data.
- **HAVING:** Filtering aggregated data.

#### 2.3 Joins and Relationships
- Types of joins:
  - Inner Join, Left Join, Right Join, Full Outer Join.
- Understanding primary keys and foreign keys.
- Combining data from multiple tables.

#### 2.4 Aggregation and Subqueries
- Aggregation functions: **SUM, AVG, COUNT, MAX, MIN.**
- Writing subqueries to filter and organize data.
- Using CTEs (Common Table Expressions) for readability.

#### 2.5 Advanced SQL for Analysis
- **Window Functions:** ROW_NUMBER, RANK, PARTITION BY.
- **CASE Statements:** Conditional logic in SQL.
- Creating temporary tables for analysis.

### **Practical Exercises:**
- Analyze sales performance by region using SQL queries.
- Join customer and transaction data to identify buying patterns.
- Summarize monthly trends in a dataset using GROUP BY and aggregation functions.

---

## **Chapter 3: Data Analysis with Python**
### **Overview:**
Python is a versatile programming language widely used in data analysis due to its powerful libraries. This chapter introduces the essential libraries and techniques for Python-based analysis.

### **Topics:**
#### 3.1 Setting Up Python for Data Analysis
- Installing Python and IDEs (Jupyter Notebook, VS Code).
- Overview of Python libraries for data analysis:
  - **Pandas:** Data manipulation.
  - **NumPy:** Numerical computation.
  - **Matplotlib/Seaborn:** Data visualization.

#### 3.2 Data Manipulation with Pandas
- Importing and exporting data (CSV, Excel, SQL).
- DataFrames: Creating, viewing, and modifying.
- Handling missing data: **fillna, dropna.**
- Filtering, sorting, and grouping data.

#### 3.3 Exploratory Data Analysis (EDA)
- Descriptive statistics: **mean, median, mode, std, describe.**
- Visualizing data with **Matplotlib** and **Seaborn:**
  - Line plots, scatter plots, histograms, heatmaps.
- Finding correlations and identifying outliers.

#### 3.4 Advanced Analysis with Python
- Merging, concatenating, and joining datasets.
- Writing user-defined functions for repetitive tasks.
- Introduction to regression analysis (e.g., linear regression with **scikit-learn**).

### **Practical Exercises:**
- Clean a dataset with missing values using Pandas.
- Visualize product sales trends using Seaborn.
- Perform EDA on a public dataset (e.g., COVID-19 data).

---

## **Chapter 4: Data Visualization with Tableau**
### **Overview:**
Tableau is a powerful tool for creating interactive visualizations and dashboards. This chapter focuses on building intuitive and insightful visual representations of data.

### **Topics:**
#### 4.1 Getting Started with Tableau
- Installing Tableau Public.
- Connecting to datasets (Excel, CSV, SQL databases).
- Understanding Tableau’s interface: Sheets, Dashboards, and Storyboards.

#### 4.2 Creating Basic Visualizations
- Bar charts, line charts, and scatter plots.
- Building pie charts and tree maps.
- Formatting charts (colors, labels, tooltips).

#### 4.3 Advanced Visualizations in Tableau
- Dual-axis charts and combo charts.
- Creating calculated fields and parameters.
- Using filters and slicers for interactivity.

#### 4.4 Designing Dashboards and Storyboards
- Combining multiple sheets into dashboards.
- Adding interactivity with actions (filter, highlight).
- Best practices for dashboard design.

#### 4.5 Tableau for Advanced Analysis
- Using Tableau Prep for data cleaning.
- Creating maps and geographic visualizations.
- Forecasting and trend analysis.

### **Practical Exercises:**
- Build an interactive sales dashboard using Tableau.
- Visualize geographic data (e.g., population by state).
- Create a storyboard to present key insights from a dataset.

---

## **Chapter 5: Capstone Project**
### **Goal:**
Apply the knowledge gained across all tools to solve a real-world problem.

### **Project Ideas:**
1. **Customer Analysis:**
   - Use Excel for initial data cleaning.
   - Extract and summarize customer data using SQL.
   - Perform EDA in Python and visualize findings in Tableau.

2. **Sales Performance Analysis:**
   - Analyze sales trends across regions and product categories.
   - Use regression analysis in Python to forecast future sales.

3. **COVID-19 Impact Study:**
   - Use SQL to extract relevant data from a large dataset.
   - Analyze trends using Python and present findings in Tableau.

### **Deliverables:**
- Data cleaning and preprocessing steps.
- Key insights and findings (graphs, tables).
- Final dashboard or report summarizing the analysis.
