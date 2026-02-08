# 🎓 Student Performance EDA, Statistical Analysis & Machine Learning

## 📌 Project Overview
This project aims to analyze and predict **student exam performance** through **exploratory data analysis (EDA)**, **statistical hypothesis testing**, **feature selection**, and **regression-based machine learning**.  
The study focuses on understanding how academic habits, lifestyle factors, and demographic variables influence exam scores, both individually and in combination.

---

## 📊 Dataset Description
The dataset contains **1000 observations and 16 features**, including:

- **Demographic features:**  
  `age`, `gender`, `parental_education_level`
- **Study & lifestyle features:**  
  `study_hours_per_day`, `sleep_hours`, `attendance_percentage`,  
  `social_media_hours`, `netflix_hours`, `exercise_frequency`
- **Target variable:**  
  `exam_score` (continuous)

Given the continuous nature of the target variable, the problem is formulated as a **regression task**.

---

## 🔍 Exploratory Data Analysis (EDA)
The EDA process includes:

- Distribution and density analysis of numerical features  
- Missing value handling (low-frequency, single-column NaNs)  
- Outlier detection using the **Interquartile Range (IQR)** method  
- Visual exploration using histograms, box plots, and scatter plots  
- Pattern interpretation, including:
  - Near-linear relationships (e.g. study hours vs exam score)
  - Vertically dispersed patterns indicating weak or indirect effects
  - Frequency-based clustering in lifestyle-related variables

---

## 📐 Statistical Analysis & Feature Selection
To support data-driven feature selection, the following statistical methods are planned:

- **Correlation analysis**  
  - Pearson correlation (parametric)  
  - Spearman rank correlation (non-parametric)
- **Hypothesis testing**
  - ANOVA (for numerical vs categorical relationships)
  - Chi-square tests (for categorical variables)
- **Feature selection techniques**
  - Statistical significance-based filtering  
  - Correlation thresholding  
  - Model-based feature importance (regression coefficients, tree-based models)

These methods help identify the most informative features while reducing redundancy and noise.

---

## 🤖 Machine Learning Approach
- **Problem type:** Regression  
- **Baseline model:** Linear Regression  
- **Extendable models:** Ridge, Lasso, tree-based regressors  
- **Evaluation metrics:**  
  - R² Score  
  - RMSE (Root Mean Squared Error)

---

## 🎨 Visualization Styling
The visualization style used in this project is directly applied from the following open-source repository:

- **dhaitz / matplotlib-stylesheets**  
  https://github.com/dhaitz/matplotlib-stylesheets  
  Licensed under the **MIT License**

The original license terms are respected in accordance with the MIT License.

---

## 🛠️ Technologies & Libraries
- **Python**
- **Data analysis:** Pandas, NumPy  
- **Visualization:** Matplotlib, Seaborn  
- **Statistical analysis:** SciPy, Statsmodels  
- **Machine learning:** Scikit-learn  
- **Deployment / UI (planned):** Streamlit  

---

## 🚀 Future Work
- Perform detailed statistical testing for feature validation  
- Apply advanced feature selection strategies  
- Improve predictive performance with ensemble regressors  
- Integrate the trained model into an **interactive Streamlit interface**
  for real-time exam score prediction

---

## 📄 License
This project is licensed under the **MIT License**.
