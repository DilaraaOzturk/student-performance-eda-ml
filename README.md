# 🎓 Student Performance EDA & Machine Learning

## 📌 Project Overview
This project focuses on **exploratory data analysis (EDA)** and **regression-based machine learning** to analyze and predict **student exam performance**.  
The aim is to understand how study habits, lifestyle factors, and demographic characteristics influence exam scores.

---

## 📊 Dataset Description
The dataset consists of **1000 rows and 16 features**, including:

- **Demographic features:**  
  `age`, `gender`, `parental_education_level`
- **Study & lifestyle features:**  
  `study_hours_per_day`, `sleep_hours`, `attendance_percentage`,  
  `social_media_hours`, `netflix_hours`, `exercise_frequency`
- **Target variable:**  
  `exam_score` (continuous)

Since the target variable is continuous, this project is formulated as a **regression problem**.

---

## 🔍 Exploratory Data Analysis (EDA)
The EDA process includes:

- Distribution analysis of numerical features  
- Handling missing values with low frequency  
- Outlier detection using the **Interquartile Range (IQR)** method  
- Visual exploration using histograms, box plots, and scatter plots  
- Interpretation of:
  - Near-linear relationships (e.g. study hours vs exam score)
  - Vertically dispersed patterns indicating weak or indirect effects
  - Frequency-based clustering in lifestyle-related variables

These analyses help reveal both direct and indirect factors affecting student performance.

---

## 🤖 Machine Learning Approach
- **Problem type:** Regression  
- **Baseline model:** Linear Regression  
- **Evaluation metrics:**  
  - R² Score  
  - RMSE (Root Mean Squared Error)

The model is trained to predict **exam_score** based on student-related features.

---

## 🎨 Visualization Styling
The visualization style used in this project is directly applied from the following open-source repository:

- **dhaitz / matplotlib-stylesheets**  
  https://github.com/dhaitz/matplotlib-stylesheets  
  Licensed under the **MIT License**

The original license terms are respected in accordance with the MIT License.

---

## 🛠️ Technologies Used
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

---

## 🚀 Future Work
- Improve model performance using advanced regression models  
- Feature engineering and interaction analysis  
- Integration of the trained model into an **interactive Python-based interface**
  (e.g. Streamlit) for real-time exam score prediction

---

## 📄 License
This project is licensed under the **MIT License**.
