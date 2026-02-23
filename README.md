# 🩺 Heart Disease Prediction System (Multi-Class Classification)

### 🚀 Project Overview
This project is a comprehensive Machine Learning pipeline designed to predict the severity of heart disease. Using the **UCI Cleveland Dataset**, the model analyzes 14 clinical attributes to categorize heart health into 5 distinct stages (from 0: No Disease to 4: Critical).

### 🧠 Technical Highlights
* **Advanced Data Imputation:** Implemented **IterativeImputer** with **RandomForestRegressor** to accurately fill missing clinical values in features like `thal`, `ca`, and `slope`.
* **Exploratory Data Analysis (EDA):** Performed deep statistical analysis using **Plotly Express** and **Seaborn** to visualize age-risk correlations and demographic distributions.
* **Outlier Management:** Identified and removed physiological anomalies (e.g., zero blood pressure readings) to ensure model robustness.
* **Model Selection:** Evaluated 10+ classifiers including **XGBoost**, **Random Forest**, and **SVM** using Scikit-Learn pipelines.

### 🛠️ Tech Stack
* **Language:** Python
* **Data Science:** Pandas, NumPy, Scikit-Learn
* **Visualization:** Matplotlib, Seaborn, Plotly
* **ML Algorithms:** Random Forest, Gradient Boosting, XGBoost, Logistic Regression

### 📂 Repository Structure
* `heart_prediction.ipynb`: Full end-to-end data analysis and model training code.
* `heart_disease_uci.csv`: The clinical dataset used for training.
* `heart_disease_model.pkl`: The final trained model ready for deployment.

### 📈 Key Insights from EDA
* **High-Risk Age Group:** Most cases of heart disease in the dataset occur between ages 53-55.
* **Gender Distribution:** Males represent ~79% of the dataset, showing a significantly higher frequency of clinical reports in this study.

---
**Author:** Shivam Ghosh  
*Chemical Engineering Undergrad at Jadavpur University*
