# fema-eligibility-prediction
Machine learning project to predict FEMA rental assistance eligibility based on applicant data.
# FEMA Rental Assistance Eligibility Prediction 🏠

A machine learning project to predict FEMA rental assistance eligibility using open-source disaster response data.

## 📘 Project Overview

Disasters like hurricanes and storms leave many in urgent need of housing. FEMA’s rental assistance process can take 2–3 weeks. This project aims to speed up decisions using supervised machine learning to predict eligibility, helping survivors get help faster.

We used over **6.3 million records** from FEMA’s Individual Assistance dataset and built multiple classification models to predict if an applicant qualifies for rental assistance.

---

## 📊 Tools & Technologies

- Python, Pandas, NumPy
- Scikit-learn (Logistic Regression, Decision Tree, KNN)
- Matplotlib, Seaborn
- Jupyter Notebook
- Azure Data Factory (ETL), AWS Redshift
- FEMA OpenFEMA API (Data Source)

---

## 🔍 Methodology

- **Data Cleaning**: Handled missing values, encoded categoricals, scaled features
- **Feature Selection**: Used correlation analysis and domain knowledge
- **Modeling**: Trained logistic regression, decision tree, and KNN models
- **Evaluation**:
  - **Logistic Regression**: Accuracy 65.97%, Precision 70.73%, Sensitivity 2.98%
  - **Decision Tree**: Accuracy 68.83%, Precision 43.03%, Sensitivity 1.30%
  - **KNN**: Accuracy 70%, Precision 45.61%, Sensitivity 16.80%

---

## 📈 Key Features Used

- Household composition
- Gross income
- Special needs
- Residence type
- Insurance coverage
- Inspection & damage data (flood, roof, foundation, etc.)

---

## ✅ Conclusion

This project highlights the potential of machine learning in streamlining disaster aid. With further improvement, such models could power **self-assessment tools** that empower disaster victims to pre-check eligibility and speed up recovery support.

---

## 📂 Project Structure

