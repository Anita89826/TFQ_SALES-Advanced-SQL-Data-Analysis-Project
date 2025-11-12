**TFQ_SALES – Advanced SQL Data Analysis Project**

**Overview**

**The TFQ_SALES**

project demonstrates the use of **advanced SQL techniques** to analyze and gain insights from a retail business database.

It focuses on **sales performance, employee earnings, and departmental comparisons** using **subqueries, Common Table Expressions (CTEs), aggregate functions, and conditional logic**

This project showcases real-world problem-solving skills in **data analysis and reporting**

using SQL.

### **Project  Description**

The project is built on three main tables:

- **employee** – Contains employee details such as `emp_ID`, `emp_NAME`, `DEPT_NAME`, and `salary`.
- **dept** – Stores department information like `dept_ID` and `dept_name`.
- **sales** – Includes transaction-level sales data with `store_id`, `store_name`, `cost`, and `quantity`

### **Key Business Questions & Analysis**

The project answers critical business questions such as:

1. **Employee Performance & Salary Insights**
    - Identify employees earning **above the average salary** of all employees.
    - Find the **highest-paid employee in each department.**
    - Add **remarks** for employees who earn more than the average pay.
    - Determine **departments with no employees.**
2. **Store Sales & Profitability**
    - Find stores whose **total sales cost** is higher than the **average cost across all store.**
    - Identify stores that **sold more units** than the **average quantity sold** across all stores.

### **SQL Techniques Used**

- **Subqueries**: Scalar, multiple-row, and correlated subqueries for comparisons and conditional checks.
- **Common Table Expressions (CTEs)**: Simplified complex nested queries for better readability and performance.
- **Aggregate Functions**: `AVG()`, `MAX()`, `SUM()` for salary and sales analysis.
- **Conditional Logic**: `CASE WHEN` to classify employees as *Above Average* or *Average/Below*.
- **Joins**: Combined results from multiple derived tables to answer multi-step business questions.

### **Key Insights**

- Identified **top-performing employees and departments** based on salary distribution.
- Highlighted **high-performing stores** with above-average sales costs and unit sales.
- Exposed **underperforming departments** with no active employees.

### **Skills Demonstrated**

- Advanced SQL querying and optimization
- Data summarization and transformation
- Business reporting and insight generation

### **Tools & Environment**

- **Database**: MySQL (can also run on PostgreSQL/SQL Server with minor syntax adjustments)
- **Query Editor**: MySQL Workbench / DBeaver / Azure Data Studio

### Recommendations

- **Reward High Performers** – Provide bonuses or career growth plans for employees earning above the company-wide average salary.
- **Review Departments with No Employees** – Hire staff, merge with other units, or discontinue inactive departments.
- **Boost Top-Performing Stores** – Increase marketing, inventory, or promotions for stores with above-average sales and units sold.
- **Support Low-Performing Stores** – Investigate location, pricing, and product mix to improve performance.
- **Maintain Competitive Salaries** – Benchmark employee pay against market rates to retain key talent.
- **Optimize Queries & Reporting** – Use CTEs, indexing, and scheduled SQL reports to improve efficiency and automate insights.
