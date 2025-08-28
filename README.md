# 🛒 Rossmann Sales Forecasting

We aimed to forecast daily sales for Rossmann retail stores using a combination of traditional time series models (SARIMA/SARIMAX) and modern machine learning models (CatBoost, XGBoost).  

---

## 👥 Team Members and Contributions

| Member                   | Main Contributions                                                                 |
|---------------------------|------------------------------------------------------------------------------------|
| **Florence Tan Hui Ping** | Abstract, Objectives & Motivation, Preprocessing & Sampling, Feature Engineering, CatBoost modeling, Project Framework, Report formatting |
| **Alia Marliana**         | Background, Problem Statement, Exploratory Data Analysis (EDA), SARIMA/SARIMAX modeling, Conclusion & Future Research, Jupyter Notebook formatting |
| **Teoh Zhi Qiang**        | Data Description, Data Cleaning & Merge, XGBoost modeling, Scope & Limitations, Poster design |

---

## 📊 Abstract (Summary)

Accurate sales forecasting is crucial for retail chains to optimize inventory, staffing, and promotions.  
This project evaluated three forecasting models on the **Rossmann Store Sales dataset**:

- **SARIMA/SARIMAX** – Traditional time-series models  
- **CatBoost** – Gradient boosting optimized for categorical features  
- **XGBoost** – Gradient boosting for complex interactions  

**Findings:**  
- **XGBoost** achieved the best performance for store-level predictions (Store 262).  
- **CatBoost** outperformed others for global aggregated forecasts.  
- Machine learning models significantly outperformed SARIMA/SARIIMAX, demonstrating their robustness for modern retail forecasting tasks.  

---

## 💪 My Personal Contributions (Alia Marliana)

While the project was a group effort, my **key contributions** were:  
- Writing the **Background** and **Problem Statement** sections  
- Conducting **Exploratory Data Analysis (EDA)** with visualizations and insights  
- Implementing and analyzing the **SARIMA/SARIMAX modeling** (both Store 262 and global forecasts)  
- Drafting the **Conclusion & Future Research Directions**  
- Formatting and documenting the **Jupyter Notebook**  
- Literature Review & Methodology sections for SARIMA  

---

## 📂 Dataset

The dataset used is the **[Rossmann Store Sales Dataset](https://www.kaggle.com/competitions/rossmann-store-sales/data)** from Kaggle.  
Due to computational constraints, a **10% stratified sample** was used for modeling.  

---

## 🛠️ Tools & Libraries
- Python (pandas, numpy, matplotlib, seaborn, scikit-learn, statsmodels, xgboost, catboost)  
- Jupyter Notebook  

---

## 📌 Conclusion

- **XGBoost** is most effective for store-level (micro) sales forecasts.  
- **CatBoost** excels at global-level (macro) aggregated sales prediction.  
- Ensemble machine learning models outperform traditional time-series methods in capturing retail sales dynamics.  

---
