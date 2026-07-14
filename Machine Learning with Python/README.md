# Machine Learning with Python
## Building a Rainfall Prediction Classifier

---

**Completed:** October 2025 | **IBM Data Science Professional Certificate** 

---

## 📊 Course Overview

This repository contains the projects, lab notebooks, and assignments completed as part of the **Machine Learning with Python** course, a core component of the **IBM Data Science Professional Certificate**. 

The primary objective of this course was to transition from foundational data analysis to predictive modeling. It covered the theoretical and practical applications of machine learning algorithms using Python. The curriculum focused on data preprocessing, model selection, training, evaluation, and tuning across both supervised and unsupervised learning paradigms.

---

## 🎯 Key Findings

* Throughout the course, several predictive models were built and evaluated. Key insights include:
  * **Classification Performance:** Evaluated multiple classification algorithms (KNN, Decision Trees, SVM, Logistic Regression) using metrics like Jaccard Score, F1-Score, and LogLoss. Found that non-linear classification boundaries (like RBF kernel in SVM) or ensemble-like structures often yielded higher accuracy on complex datasets compared to simple linear classifiers.
  * **Regression Modeling:** Developed linear, non-linear, and polynomial regression models to forecast continuous trends, optimizing performance by minimizing Mean Squared Error (MSE) and maximizing $R^2$ scores.
  * **Clustering Patterns:** Applied K-Means and Density-Based (DBSCAN) clustering to segment data without historical labels. K-Means effectively grouped spherical data clusters (e.g., customer segmentation), while DBSCAN excelled at identifying arbitrary shapes and filtering out noise/outliers.

---

## 🛠️ Technical Stack

| Category | Tools |
| :--- | :--- |
| **Language** | Python 3.x |
| **Python Libraries** | **Data Manipulation:** `pandas`, `numpy`, **Machine Learning:** `scikit-learn`, `scipy`, **Data Visualization:** `matplotlib`, `seaborn` |
| **Environment** | Jupyter Notebooks / IBM Cloud Watson Studio |


---

## 📂 Project Structure

### Deliverables

* `weatherAUS_2.csv` - Source and processed datasets
*`FinalProject_AUSWeather.ipynb` - Core Jupyter Notebook project files

---

## 📊 Data Sources

This module features multiple hands-on machine learning projects, utilizing real-world and simulated benchmark datasets to train, evaluate, and fine-tune models:

* **Rainfall Prediction (Final Project):** Weather observations from the [Australian Government's Bureau of Meteorology](https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package?resource=download&select=weatherAUS.csv), used to build and compare classification models to predict next-day precipitation.
* **Credit & Loan Applications:** Historical customer profiles and financial records used to classify loan repayment outcomes (Paid Off vs. Default).
* **Telecommunications Churn:** Customer demographics, plan details, and usage metrics leveraged to predict customer retention and churn behaviors.
* **Automobile Pricing & Efficiency:** Technical vehicle specifications utilized to model regression lines for fuel consumption and market valuation.
* **CO2 Emissions:** Engine specifications and fuel consumption profiles mapped to predict and analyze greenhouse gas emission trends.
 
---

## 💡 Key Skills Demonstrated

* **Data Preprocessing & Feature Engineering** - Handling missing values, converting categorical variables into numerical formats (One-Hot Encoding), and normalizing data using StandardScaler.
* **Supervised Learning** - Building and optimizing Regression and Classification models.
* **Unsupervised Learning** - Pattern extraction and data segmentation using Clustering techniques.
* **Model Evaluation & Hyperparameter Tuning** - Utilizing train/test splits, K-Fold Cross-Validation, and evaluating performance using confusion matrices, ROC curves, F1-Score, Jaccard Index, and LogLoss.

---

## 📈 Visualization Highlights

* Data visualizations were critical for interpreting model decisions and checking assumptions. Key visual assets included:
  * **Correlation Heatmaps** - Leveraged seaborn heatmaps to detect multi-collinearity among features before training regression models.
  * **Decision Boundaries** - Visualizing how different classifiers split data classes across two-dimensional feature spaces.
  * **Elbow Method Plots** - Plotting within-cluster sum of squares (WCSS) against the number of clusters ($K$) to mathematically determine the optimal cluster count.
  * **Confusion Matrices** - Detailed heatmaps mapping True Positives vs. False Positives to visually diagnose classification errors.

---
 
## 🔗 Links

* **Repository:** [GitHub](https://github.com/richardlam4391/IBM_Data_Science_Professional_Certificate/tree/main/Machine%20Learning%20with%20Python)
* **Certification:** [Machine Learning with Python (Coursera)](https://www.coursera.org/account/accomplishments/records/4C33QEW6QU3K)
