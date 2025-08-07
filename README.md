#  Borrowing Behaviour Analysis: The Role of Income and Homeownership

This project investigates how income levels and homeownership status influence borrowing behaviour—specifically loan amounts and loan purposes—using statistical modelling and data visualisation.

---

##  Repository Structure

- `Data(Excel)/`: Contains raw and cleaned datasets in CSV format.
- `Report/`: Includes the final report detailing analysis, methodology, findings, and recommendations.
- `STATA doc/`: Contains .dta files and STATA outputs used for econometric modelling.
- `README.md`: You're here!

---

##  Project Overview

This study aims to explore the relationship between:
- **Annual Income** and **Loan Amounts**.
- **Homeownership Status** and **Loan Purposes**.

Using a dataset of nearly 40,000 individuals, we apply:
- **OLS Regression** for continuous loan amounts.
- **Multinomial Logistic Regression** for categorical loan purposes.

---

##  Key Questions

1. How does annual income affect the amount borrowed?
2. What influence does homeownership status have on the purpose of loans?

---

## Dataset

The dataset includes:
- `Annual Income` (continuous)
- `Loan Amount` (continuous)
- `Homeownership Status` (categorical: Rent, Mortgage, Own, Other)
- `Loan Purpose` (14 categories including car, credit card, education, small business)
- `Debt-to-Income Ratio (DTI)`
- `Loan Term`

---

##  Methodology

### 1. **Data Cleaning**
- Encoding categorical variables
- Handling missing values using mean imputation

### 2. **OLS Regression**
Modelled loan amounts as a function of:
- Income  
- Homeownership  
- DTI  
- Loan term

### 3. **Multinomial Logistic Regression**
Modelled the probability of choosing specific loan purposes based on:
- Income  
- Homeownership  

Statistical assumptions such as multicollinearity, normality, homoscedasticity, and IIA were tested and addressed.

---

##  Key Findings

- **Higher Income** → Higher loan amounts
- **Homeowners** borrow significantly more than renters
- **Homeowners** are more likely to borrow for home improvements
- **Lower-income individuals** lean towards loans for essentials and debt consolidation

---

##  Visualizations

- Box plots: Loan amounts by homeownership category
- Histograms: Residuals from OLS models to verify normality
- Summary tables of regression outputs

---

## ⚖ Limitations

- Cross-sectional dataset limits causal inference
- Omitted variables (e.g., credit scores, employment type)
- Possible reporting bias in income
- The multinomial model may violate the IIA assumption

---

##  References

- Lusardi & Tufano (2015)
- Sufi & Mian (2011)
- Wooldridge (2020)
- Gujarati & Porter (2009)

---

##  Conclusion

This analysis offers practical insights for:
- **Policymakers**, to design income-sensitive loan products.
- **Financial institutions**, to tailor credit strategies for homeowners and renters.
- **Researchers**, to expand on this study with longitudinal data and deeper variable inclusion.

---


