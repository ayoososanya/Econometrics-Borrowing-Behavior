#  Econometrics Study on Borrowing Behavior  

##  Overview  
This project investigates **how annual income influences borrowing behaviour**, focusing on **loan amounts and purposes**. The analysis uses **OLS Regression** to predict loan sizes and **Multinomial Logit/Probit models** to determine why individuals take out loans.

##  Research Questions:
- How does **annual income** affect the amounts borrowed by individuals?  
- What influence does **homeownership status** have on loan purposes?  

##  Data & Methodology:
- **Dataset:** ~40,000 observations from a 2021 financial study.
  
- **Key Variables:**  
  -  `homeownership` → Determines housing stability (Rent = 1, Mortgage = 2, Own = 3).  
  -  `loan_purpose` → Encodes reasons for borrowing (Debt Consolidation = 3, Education = 4, etc.).  
  -  `loan_amount` → The dependent variable for OLS.  
  -  `annual_income` → The main independent variable.
    
- **Models Used:**  
  - OLS Regression for loan amounts  
  - Multinomial Logit/Probit for loan purposes  

##  Results Summary:
- **Income is positively correlated with loan size** in OLS Regression.
- **Homeownership significantly affects borrowing behaviour**.
- **Multinomial Logit/Probit showed that higher-income individuals borrow for investment, while lower-income individuals borrow for consumption.**


##  Next Steps:
🔹 Expand the study to include **time trends** and macroeconomic factors.  
🔹 Explore **machine learning models (e.g., Random Forest)** for loan prediction.  
🔹 Publish results in an **interactive Tableau/Power BI dashboard**.  

 **Author:** *Ayoola Ososanya*  
 **Skills Demonstrated:** Econometrics, STATA, Data Analysis, Regression Modeling  

