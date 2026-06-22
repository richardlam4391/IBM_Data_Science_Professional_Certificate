# 🚀 Winning the Space Race with Data Science
### IBM Data Science Professional Certificate — Capstone Project
**Completed:** October 2025 | **IBM Data Science Professional Certificate** 

---

## 📌 Project Overview
SpaceX advertises Falcon 9 rocket launches on its website with a cost of $62 million, whereas other providers cost upwards of $165 million. Much of the cost savings is achieved because SpaceX can successfully reuse the first stage of the rocket. 

The core objective of this project is to predict whether the first stage of a Falcon 9 rocket will land successfully. By building a predictive machine learning model, we can accurately determine the actual cost of a launch and provide critical, data-driven financial and operational insights for alternate commercial space launch companies looking to compete with SpaceX.

### Primary Deliverable
**Interactive Tableau Dashboard:** [View on Tableau Public](https://public.tableau.com/app/profile/richardlam4391/viz/SpaceXDashboard_17807897119650/Dashboard1)

---

## 🔍 Key Findings & Insights
* **Model Evaluation:** Four classification algorithms (Logistic Regression, Support Vector Machine, Decision Tree, and K-Nearest Neighbors) were optimized via `GridSearchCV`. The top-performing models achieved a test accuracy score of **83.3%**, with the Decision Tree model showing slight variations in tuning behavior.
* **Launch Site Trends:** Exploratory analysis revealed that **KSC LC-39A** holds the highest overall landing success rate among the launch sites. **VAFB SLC-4E** and **CCAFS SLC-40** showed lower initial success profiles but improved over successive flight numbers.
* **Payload Impact:** Landing success rates drop significantly for payloads exceeding **10,000 kg** across specific orbits, while a "sweet spot" for high-probability successful landings occurs between **2,000 kg and 6,000 kg**.
* **Geospatial Proximity:** Using map visualization, all major launch sites were found to be strategically located directly adjacent to major coastlines and transport highways to maximize safety and logistically simplify first-stage shipping/recovery.

![SpaceX Dashboard (2).png](https://github.com/richardlam4391/IBM_Data_Science_Professional_Certificate/blob/main/Applied%20Data%20Science%20Capstone/SpaceX%20Dashboard%20(2).png)

---

## 🛠️ Technical Stack & Tools

| Category | Tools |
|----------|-------|
| **Languages:** | Python, SQL |
| **Data Gathering & Ingestion:** | REST APIs (SpaceX API), Web Scraping (`BeautifulSoup`), `Requests` |
| **Data Wrangling & Processing:** | `Pandas`, `NumPy` |
| **Exploratory Data Analysis (EDA):** | SQL (`SQLite3`), `Matplotlib`, `Seaborn` |
| **Interactive Business Intelligence:** | `Folium` (Geospatial maps), Plotly `Dash` (Interactive apps), Tableau Public |
| **Machine Learning & Modeling:** | `Scikit-learn` (StandardScaler, LogisticRegression, SVC, DecisionTreeClassifier, KNeighborsClassifier, GridSearchCV) |

---

## 📁 Project Structure

### Data Pipeline (Labs 1-3)
- **Lab 1:** Collecting the data
- **Lab 2:** Web scraping
- **Lab 3:** Data Wrangling

### Analysis & Visualization (Labs 4-8)
- **Lab 4:** Exploratory Data Analysis (EDA) with Data Visualization
- **Lab 5:** Exploratory Data Analysis (EDA) with Structured Query Language (SQL)
- **Lab 6:** Interactive Map with Folium
- **Lab 7:** Dashboard with Plotly Dash
- **Lab 8:** Predictive Analysis (Classification)

### Deliverables
- `2025 Richard Lam Data Science Capstone Project` — Executive summary
- `2025 Richard Lam Data Science Capstone Project.pdf` — Presentation PDF
- `IBM Data Analyst Capstone Project Tableau.pdf` — Dashboard documentation
- Dashboard exports (PNG files)
- Dashboard plotly (PY files)
