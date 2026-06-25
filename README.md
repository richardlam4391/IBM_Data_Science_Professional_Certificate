# IBM Data Science Professional Certificate Portfolio

Welcome to my portfolio repository documenting my journey and projects completed during the **IBM Data Science Professional Certificate** program on Coursera. 

This intensive 12-course program provides hands-on, job-ready training across the complete data science lifecycle—moving from initial business understanding and SQL database operations to predictive modeling and machine learning deployment.

---

## 📊 Key Skills Gained

* **Machine Learning Pipeline Engineering:** Implementing, tuning, and evaluating classical supervised and unsupervised ML models.
* **Exploratory Data Analysis (EDA) & Feature Engineering:** Handling missing values, analyzing mathematical distributions, removing anomalies, and optimizing features through One-Hot Encoding and normalization.
* **Data Science Methodology:** Using industry frameworks like **CRISP-DM** to translate ambiguous business questions into systematic, iterative analytical steps.
* **Data Extraction & Wrangling:** Automating extraction of unstructured data using web scraping (`BeautifulSoup`) and cleaning multi-source data through **Pandas** and **NumPy**.
* **Geospatial & Dynamic Visualization:** Tracking location clusters on interactive maps and creating multi-variable dashboards to surface hidden trends.

---

## 🛠️ Tools & Technologies

* **Languages:** Python, SQL
* **Machine Learning & Stats:** Scikit-learn, SciPy
* **Data Processing:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn, Folium (Geospatial maps), Plotly, Plotly Dash (Interactive Dashboards)
* **Databases & Environments:** SQLite, IBM Db2 Cloud, JupyterLab, Jupyter Notebooks, VS Code, Git
* **AI & Automation:** Generative AI for prompt engineering, script automation, and analytical storytelling

---

## 📋 Curriculum & Repository Structure

The repository is organized numerically to show the structured progression from fundamental principles to predictive algorithmic modeling:

| # | Course Module | Status |
| :--- | :--- | :--- |
| **01** | What is Data Science? | ✅ Completed in June 2025 |
| **02** | Tools for Data Science | ✅ Completed in June 2025 |
| **03** | Data Science Methodology | ✅ Completed in June 2025 |
| **04** | Python for Data Science & AI | ✅ Completed in April 2025 |
| **05** | Python Project for Data Science | ✅ Completed in April 2025 |
| **06** | Databases & SQL with Python | ✅ Completed in April 2025 |
| **07** | Data Analysis with Python | ✅ Completed in May 2025 |
| **08** | Data Visualization with Python | ✅ Completed in May 2025 |
| **09** | Machine Learning with Python | ✅ Completed in October 2025 |
| **10** | **Applied Data Science Capstone** | ✅ Completed in October 2025 |
| **11** | Generative AI Career Elevate | ✅ Completed in October 2025 |
| **12** | Career Guide & Interview Prep | ✅ Completed in October 2025 |

---

## 🏆 Portfolio Highlight: Applied Data Science Capstone
### SpaceX Falcon 9 First-Stage Landing Prediction

The program's capstone project involves a comprehensive application of data science techniques to solve a real-world commercial problem: **predicting whether the first stage of a SpaceX Falcon 9 rocket will land successfully.** Because first-stage reuse saves SpaceX roughly $115 million per launch, predicting success allows us to calculate accurate competitive launch costs.

#### Key Phases Executed:
1. **Data Acquisition:** Integrated data via REST API calls from the SpaceX API and extracted complementary rocket specifications using web scraping (`BeautifulSoup`).
2. **Data Cleansing & Preprocessing:** Standardized the target variable into an actionable binary classification format (`1` = landed, `0` = failed) and processed features using **One-Hot Encoding**.
3. **Exploratory Data Analysis (EDA):** Discovered insights using SQL queries to break down success rates relative to launch site locations, total payload masses, and orbit classifications.
4. **Geospatial & Dashboard Analysis:** Deployed **Folium** maps to highlight launch pad positioning relative to coastal margins and created a fully interactive **Plotly Dash** dashboard containing range-slider constraints on total weight metrics.
5. **Machine Learning Classification:** Trained and optimized four predictive classification frameworks utilizing `GridSearchCV` to tune optimal parameters:
    * *Logistic Regression*
    * *Support Vector Machine (SVM)*
    * *Decision Tree Classifier*
    * *K-Nearest Neighbors (KNN)*

**Explore the code, notebooks, and final presentation:** [Winning Space Race with Data Science]([./10_Applied_Data_Science_Capstone/](https://github.com/richardlam4391/IBM_Data_Science_Professional_Certificate/tree/main/Applied%20Data%20Science%20Capstone))

---

## 📚 **Notable Projects**

### **Core Analysis Projects**
- **[Data Analysis with Python: House Sales in King County, USA](./Data%20Analysis%20with%20Python)** — Regression modeling on real estate data
- **[Databases and SQL for Data Science: Chicago Socioeconomic Data](./Databases%20and%20SQL%20for%20Data%20Science%20with%20Python)** — SQL queries and relational data analysis
- **[Python Project for Data Science: Stock Data Analysis](./Python%20Project%20for%20Data%20Science)** — Financial data extraction and visualization
- **[Machine Learning with Python](https://github.com/richardlam4391/IBM_Data_Science_Professional_Certificate/tree/main/Machine%20Learning%20with%20Python)** - Learning Machine Classification

### **Dashboard & Visualization**
- **[Data Visualization with Python](./Data%20Visualization%20with%20Python)** — Interactive Plotly visualizations

---

## 🛠️ My Data Analysis Process

Every project within this certification followed a rigorous, structured data life cycle to ensure data integrity and actionable insights:

1.  **Data Acquisition:** Gathering data from diverse sources using Python REST APIs, relational databases (SQL), or unstructured formats via web scraping.
2.  **Data Cleaning & Wrangling:** Processing missing values, resolving data type inconsistencies, filtering outliers, and engineering key features using **Pandas** and **NumPy**.
3.  **Exploratory Data Analysis (EDA):** Discovering patterns, checking statistical assumptions, and analyzing feature correlations utilizing descriptive statistics and SQL-driven aggregations.
4.  **Data Visualization:** Designing clean, interpretable charts (scatter plots, line charts, histograms, and heatmaps) using **Matplotlib** and **Seaborn** to translate complex data distributions into clear narratives.
5.  **Geospatial & Interactive Dashboards:** Building interactive map overlays with **Folium** and dynamic interfaces with **Plotly/Dash** to allow stakeholders to filter data dynamically.
6.  **Predictive Modeling:** Applying supervised machine learning techniques using **Scikit-learn**, optimizing algorithms through cross-validation, and measuring performance metrics (Accuracy, Precision, Recall, F1-Score, and Confusion Matrices).

---

## 🎓 Certification

✅ [IBM Data Science Professional Certificate](https://www.coursera.org/account/accomplishments/specialization/0QDNHSLT2300) — October 2025

---

## 📊 **Getting Started**

To explore projects in this repository:

1. Clone or download the repository
2. Navigate to specific course folders
3. Open Jupyter notebooks (`.ipynb` files)
4. Install required dependencies: `pip install pandas numpy matplotlib seaborn scikit-learn plotly beautifulsoup4`
5. Run cells sequentially to reproduce analysis and visualizations

**Repository Last Updated:** October 2025
**Certificate Awarded:** October 2025
**Total Courses:** 12
**Program Duration:** 3 months

For more information about this program, visit [IBM Data Science Professional Certificate on Coursera](https://www.coursera.org/professional-certificates/ibm-data-science).
