# Data Analysis with Python
## House Sales in King County, USA

---
**Comnpleted:** May 2025 | **IBM Data Analyst Professional Certificate**

---

## 📊 Course Overview
This module focuses on moving from raw data to actionable data-driven insights using Python's robust scientific ecosystem. The curriculum bridges the gap between basic data manipulation and statistical machine learning, focusing on cleaning messy datasets, identifying critical feature interactions, and building predictive models to estimate continuous variables.

---

## 🎯 Key Findings

- Identified that features such as highway-mpg, engine-size, and horsepower share the strongest Pearson correlations with the target pricing index.Model
- Moving from a Simple Linear Regression model to a Multiple Linear Regression model reduced the Mean Squared Error (MSE) significantly and boosted the $R^2$ score.
- Applying Ridge Regression with optimized alpha hyperparameters via Grid Search successfully mitigated overfitting trends observed in high-degree polynomial regressions, establishing a highly robust model for deployment.

---

## 🛠️ Technical Stack

| Category | Tools |
| :--- | :--- |
| **Language** | Python 3.x |
| **Data Manipulation** | `pandas`, `NumPy`|
| **Exploratory Data Analysis & Statistical Testing** | `SciPy` (ANOVA, Pearson Correlation) |
| **Data Visualization** | `Matplotlib`, `Seaborn` |
| **Machine Learning & Model Evaluation** | `scikit-learn` (Linear, Polynomial, Ridge Regression, Grid Search CV)|
| **Environment** | Jupyter Notebooks / IBM Skills Network Labs |

---

## Project Structure

### Deliverables

- `historical_automobile_sales.csv` - Source and processed datasets
- `Lab6b Project.ipynb` - Core Jupyter Notebook project files

---

## 📊 Data Source

* **Primary Dataset** - Automobile Pricing Database / King County House Sales (Standard IBM Data Source)
* **Description** - Contains comprehensive technical, structural, and performance metrics utilized to predict market valuations.
* **Attributes** - Features a mix of categorical, continuous numerical, and discrete variables requiring format conversions and imputation.

---

## 💡 Key Skills Demonstrated

- **Data Wrangling & Quality Assurance** - Identifying and dropping/imputing missing values (`dropna()`, `fillna()`), standardizing units, normalizing numerical metrics (min-max / z-score), and data binning for categorical alignment.
- **Advanced Exploratory Data Analysis (EDA)** - Computing descriptive statistics, calculating Pearson correlation coefficients, and executing ANOVA (Analysis of Variance) tests to determine statistical significance between categorical groups and a target variable.
- **Predictive Modeling** - Developing Simple Linear Regression (SLR), Multiple Linear Regression (MLR), and multi-degree Polynomial models.
- **Model Regularization & Optimization** - Implementing Ridge Regression to prevent overfitting and using `GridSearchCV` for hyperparameter optimization.

---

## 📈 Visualization Highlights

- Leveraging Matplotlib and Seaborn, the following visual assets were developed to unlock dataset narratives:

    * **Regression Plots (sns.regplot)** - Utilized to isolate linear trends between continuous engine features and price.

    * **Residual Plots (sns.residplot)** - Employed to analyze error variances and confirm the appropriateness of linear models versus polynomial transformations.

    * **Distribution Plots (sns.kdeplot)** - Overlaid actual data targets against predicted outputs to visually assess model accuracy across different pricing brackets.

    * **Box Plots (sns.boxplot)** - Created to observe variations in price distributions across categorical segments like drive-wheels or engine location.
 
---

## 🔗 Links

- **Repository:** [GitHub](https://github.com/richardlam4391/IBM_Data_Science_Professional_Certificate/tree/main/Data%20Analysis%20with%20Python)
- **Certification:** IBM Data Science Professional Certificate (Coursera)
