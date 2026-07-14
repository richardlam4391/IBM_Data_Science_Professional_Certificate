# Databases and SQL for Data Science with Python
## Chicago Socioeconomic Data 

---

**Completed:** April 2025 | **IBM Data Science Professional Certificate**

---

## 📊 Course Overview

This module focuses on working with relational database systems, utilizing SQL (Structured Query Language) to manage, query, and analyze data, and integrating these database operations directly into Python workflows. The curriculum covers foundational database concepts, writing advanced SQL queries (including joins, subqueries, and analytical functions), and connecting to cloud-hosted databases using Python libraries. The final capstone elements involve analyzing real-world datasets—such as socioeconomic indicators, public school performance, and crime statistics—to solve complex, data-driven problems.

---

## 🎯 Key Findings

* **Socioeconomic Impacts** - Identified distinct correlations between community hardship indexes, per capita income levels, and local enrollment rates.
* **School Performance Trends** - Uncovered structural patterns in school safety scores and academic success metrics across different neighborhood demographics.
* **Crime Hotspots** - Map-based and frequency-based analysis pinpointed specific areas with disproportionately high frequencies of specific crime categories, providing actionable insight for public resource allocation.
* **Python-SQL Synergy** - Demonstrated that moving heavy data-filtering and aggregation workloads to the database engine via SQL significantly reduces memory overhead in Python compared to processing raw data entirely within Pandas.

1) Find the total number of crimes recorded in the CRIME table
![Solution of Chicago Census Data 1](https://github.com/richardlam4391/IBM_Data_Science_Professional_Certificate/blob/main/Databases%20and%20SQL%20for%20Data%20Science%20with%20Python/Solution%20of%20Chicago%20Census%20Data%201.png)

2) List community area names and numbers with per capita income less than 11000
![Solution of Chicago Census Data 2](https://github.com/richardlam4391/IBM_Data_Science_Professional_Certificate/blob/main/Databases%20and%20SQL%20for%20Data%20Science%20with%20Python/Solution%20of%20Chicago%20Census%20Data%202.png)

3) List all case number for crimes involving minors? (children are not considered minors for the purposes of crime analysis)
![Solution of Chicago Census Data 3](https://github.com/richardlam4391/IBM_Data_Science_Professional_Certificate/blob/main/Databases%20and%20SQL%20for%20Data%20Science%20with%20Python/Solution%20of%20Chicago%20Census%20Data%203.png)

4) List all kidnapping crimes involving a child?
![Solution of Chicago Census Data 4](https://github.com/richardlam4391/IBM_Data_Science_Professional_Certificate/blob/main/Databases%20and%20SQL%20for%20Data%20Science%20with%20Python/Solution%20of%20Chicago%20Census%20Data%204.png)

5) List the kind of crimes that were recorded at schools. (No repetitions)
![Solution of Chicago Census Data 5](https://github.com/richardlam4391/IBM_Data_Science_Professional_Certificate/blob/main/Databases%20and%20SQL%20for%20Data%20Science%20with%20Python/Solution%20of%20Chicago%20Census%20Data%205.png)

6) List the type of schools along with the average safety score for each type.
![Solution of Chicago Census Data 6](https://github.com/richardlam4391/IBM_Data_Science_Professional_Certificate/blob/main/Databases%20and%20SQL%20for%20Data%20Science%20with%20Python/Solution%20of%20Chicago%20Census%20Data%206.png)

7) List 5 community areas with highest % of households below poverty line.
![Solution of Chicago Census Data 7](https://github.com/richardlam4391/IBM_Data_Science_Professional_Certificate/blob/main/Databases%20and%20SQL%20for%20Data%20Science%20with%20Python/Solution%20of%20Chicago%20Census%20Data%207.png)

8) Which community area is most crime prone? Display the coumminty area number only.
![Solution of Chicago Census Data 8](https://github.com/richardlam4391/IBM_Data_Science_Professional_Certificate/blob/main/Databases%20and%20SQL%20for%20Data%20Science%20with%20Python/Solution%20of%20Chicago%20Census%20Data%208.png)

9) Use a sub-query to find the name of the community area with highest hardship index.
![Solution of Chicago Census Data 9](https://github.com/richardlam4391/IBM_Data_Science_Professional_Certificate/blob/main/Databases%20and%20SQL%20for%20Data%20Science%20with%20Python/Solution%20of%20Chicago%20Census%20Data%209.png)

10) Use a sub-query to determine the Community Area Name with most number of crimes?
![Solution of Chicago Census Data 10](https://github.com/richardlam4391/IBM_Data_Science_Professional_Certificate/blob/main/Databases%20and%20SQL%20for%20Data%20Science%20with%20Python/Solution%20of%20Chicago%20Census%20Data%2010.png)

---

## 🛠️ Technical Stack

| Category | Tools |
|----------|-------|
| **Language** | SQL, Python |
| **Database Management Systems** | IBM Db2 (Cloud/Lite), SQLite, MySQL |
| **Python Libraries** | ipython-sql (SQL Magic commands for Jupyter Notebooks), ibm_db & ibm_db_sa (IBM Db2 driver and SQLAlchemy adapter), pandas (Data manipulation and analysis), matplotlib / seaborn (Data visualization) |

---

## 📁 Project Structure

### Deliverables

* `mod5_final_project` — Core Jupyter Notebook project files
* .csv files - Source and processed datasets
* Solution of Chicago Census Data 1 -10 (PNG files) - Visual results from MySQL WorkBench screenshots
* Chicago Census Data 1 - 10 (SQL files) - SQL query statements
  
---

## 📊 Data Sources

The analytical projects in this module utilize public datasets sourced directly from the [City of Chicago Data Portal](https://data.cityofchicago.org/):
* **Socioeconomic Indicators:** Census data detailing per capita income, unemployment rates, and hardship indexes across various Chicago community areas.
* **Public School Performance:** Comprehensive school-level data covering academic metrics, safety ratings, and enrollment figures.
* **Crime Records:** Historical logs of reported incidents within the city, including crime types, locations, and arrest outcomes.

---

## 💡 Key Skills Demonstrated

* **Relational Database Concepts** - Designing and querying relational databases using DDL (Data Definition Language) and DML (Data Manipulation Language).
* **Advanced Querying** - Executing complex multi-table JOIN operations, nested SUBQUERIES, and built-in database functions.
* **Python Database Integration** - Using database APIs (DB-API) and connection strings to execute queries directly from Jupyter Notebooks and seamlessly load result sets into Pandas DataFrames.
* **Data Analysis & Filtering** - Sorting, grouping (GROUP BY, HAVING), and aggregating data to extract high-level summaries from massive rows of raw records.

---

## 📈 Visualization Highlights

* **Hardship vs. Income Scatter Plots** - Showcasing the negative correlation between a community’s hardship index and its per capita income.
* **Enrollment Distribution Histograms** - Visualizing the distribution of student enrollment across Chicago elementary, middle, and high schools.
* **Crime Type Bar Charts** - Highlighting the most frequent types of crimes committed to assist in trend identification.

---

## 🔗 Links

* **Repository:** [GitHub](https://github.com/richardlam4391/IBM_Data_Science_Professional_Certificate/tree/main/Databases%20and%20SQL%20for%20Data%20Science%20with%20Python)
* **Certification:** [Databases and SQL for Data Science with Python (Coursera)](https://www.coursera.org/account/accomplishments/verify/NL7BBVS8KQMB)
