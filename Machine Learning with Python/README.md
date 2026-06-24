# Machine Learning with Python
## Title: Building a Rainfall Prediction Classifier

---

**Completed:** October 2025 | **IBM Data Science Professional Certificate** 

## 📌 Course Overview

This repository contains the projects, lab notebooks, and assignments completed as part of the **Machine Learning with Python** course, a core component of the **IBM Data Science Professional Certificate**. 

The primary objective of this course was to transition from foundational data analysis to predictive modeling. It covered the theoretical and practical applications of machine learning algorithms using Python. The curriculum focused on data preprocessing, model selection, training, evaluation, and tuning across both supervised and unsupervised learning paradigms.

---

## 🔍 Key Findings

Throughout the course, several predictive models were built and evaluated. Key insights include:
* **Classification Performance:** Evaluated multiple classification algorithms (KNN, Decision Trees, SVM, Logistic Regression) using metrics like Jaccard Score, F1-Score, and LogLoss. Found that non-linear classification boundaries (like RBF kernel in SVM) or ensemble-like structures often yielded higher accuracy on complex datasets compared to simple linear classifiers.
* **Regression Modeling:** Developed linear, non-linear, and polynomial regression models to forecast continuous trends, optimizing performance by minimizing Mean Squared Error (MSE) and maximizing $R^2$ scores.
* **Clustering Patterns:** Applied K-Means and Density-Based (DBSCAN) clustering to segment data without historical labels. K-Means effectively grouped spherical data clusters (e.g., customer segmentation), while DBSCAN excelled at identifying arbitrary shapes and filtering out noise/outliers.

---

## 🛠️ Technical Stack

* | Category | Tools |
|----------|-------|
| **Language** | Python 3.x |
| **Python Libraries** | `pandas`, `numpy` (**Data Manipulation**), `scikit-learn`, `scipy` (**Machine Learning**), `matplotlib`, `seaborn` (**Data Visualization**) |
| **Environment** | Jupyter Notebooks / IBM Cloud Watson Studio |


---

## 📂 Project Structure

### Deliverables
'FinalProject_AUSWeather.ipynb' -  Jupyter Notebook documentation

---

## 📊 Data Sources
- The models in this module were trained and evaluated using benchmark datasets provided by IBM, including:
  - **Loan Application Data** - Historical loan records used to predict whether a customer will pay off or default on a loan.
  - **Telecommunications Customer Churn** - Customer demographics and usage metrics used for predicting churn behaviors.
  - **Automobile Datasets** - Technical specifications of vehicles used to predict fuel consumption and market pricing.
  - **Co2 Emissions Data** - Engine features utilized to model and predict environmental impact trends.
 
---

## 🏆 Key Skills Demonstrated
- **Data Preprocessing & Feature Engineering** - Handling missing values, converting categorical variables into numerical formats (One-Hot Encoding), and normalizing data using StandardScaler.
- **Supervised Learning** - Building and optimizing Regression and Classification models.
- **Unsupervised Learning** - Pattern extraction and data segmentation using Clustering techniques.
- **Model Evaluation & Hyperparameter Tuning** - Utilizing train/test splits, K-Fold Cross-Validation, and evaluating performance using confusion matrices, ROC curves, F1-Score, Jaccard Index, and LogLoss.

---

## 📈 Visualization Highlights

- Data visualizations were critical for interpreting model decisions and checking assumptions. Key visual assets included:
  - **Correlation Heatmaps** - Leveraged seaborn heatmaps to detect multi-collinearity among features before training regression models.
  - **Decision Boundaries** - Visualizing how different classifiers split data classes across two-dimensional feature spaces.
  - **Elbow Method Plots** - Plotting within-cluster sum of squares (WCSS) against the number of clusters ($K$) to mathematically determine the optimal cluster count.
  - **Confusion Matrices** - Detailed heatmaps mapping True Positives vs. False Positives to visually diagnose classification errors.
 
## 🔗 Links

- **Repository:** [GitHub](https://github.com/richardlam4391/IBM-Data-Analyst-Professional-Certificate/edit/main/Python%20Project%20for%20Data%20Science/README.md)
- **Certification:** IBM Data Science Professional Certificate (Coursera)
