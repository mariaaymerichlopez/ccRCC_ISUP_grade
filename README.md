# ccRCC_ISUP_grade
Radiomics-Based Classification of Clear Cell Renal Cell Carcinoma ISUP Grade: A Machine Learning Approach with SHAP-Enhanced Explainability

This repository contains the Jupyter Notebook developed for the classification of ISUP grade in renal cell carcinoma using radiomics features and machine learning models, including Support Vector Machines (SVM), Random Forest, and Logistic Regression. The pipeline supports performance evaluation through various metrics and ROC curve analysis. Also includes SHAP global and local explainability.

---

## Data Availability

The dataset used in this study is not publicly available due to institutional and ethical restrictions.  
As a result, the notebook will not execute correctly unless the user provides a compatible dataset matching the expected structure and variable names.

**Data Loading Placeholder:**
```python
df_MRS = pd.read_csv("your_data.csv")  # Replace "your_data.csv" with your own dataset

or

**Data Loading Placeholder:**
```python
df_MRS=pd.read_excel("Database.xlsx",sheet_name="Sheet1")
