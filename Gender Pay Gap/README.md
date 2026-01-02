# Gender Pay Gap Analysis: Descriptive and Adjusted Insights

This project investigates **gender-based compensation disparities across job roles** using **descriptive, stratified, and adjusted statistical analyses**. The goal is to understand **whether gender systematically affects base pay and bonuses**, how **gender representation varies across roles and departments**, and how **perceptions of pay gaps may arise from internal imbalances rather than actual inequities**. Analyses are exploratory, descriptive, and adjusted to account for professional characteristics.

> *To what extent does gender influence compensation levels across comparable job titles and professional characteristics, and where are actionable interventions warranted?*

## Contents

1. **Gender Pay Gap - EDA** – Data Loading and Overview  
   - Load the Glassdoor Gender Pay Gap dataset containing job title, gender, age, education, department, seniority, BasePay, Bonus, and performance evaluation  
   - Inspect dataset structure, missing values, duplicates, and variable types  
   - Provide statistical summaries of numeric variables (BasePay, Bonus, Age, Seniority, PerfEval)  
   - Describe dataset columns and provide context for compensation, performance, and education  
   - Conduct initial univariate, bivariate, and multivariate exploration to highlight patterns across job roles  
   - Perform preliminary descriptive analyses of BasePay and Bonus by gender to identify potential disparities  

2. **Gender Pay Gap - Stats** – Adjusted Analyses and Stratified Comparisons  
   - Conduct **Chi-square tests** to examine independence between gender and categorical variables (e.g., Education, Seniority)  
   - Apply **ANOVA / Robust ANOVA** to explore differences in pay across Education levels and Seniority  
   - Fit **Multivariate Linear Regression (MLR)** models for BasePay and Bonus, adjusting for job title, department, education, seniority, age, and performance evaluation  
   - Interpret adjusted analyses to determine whether apparent gender pay differences persist after controlling for professional characteristics  

3. **Gender Pay Gap - Insights** – Understanding Perceptions vs. Adjusted Reality  
   - Conduct **Chi-square tests for Job Titles** to identify gender imbalances within roles.
   - Highlight roles with notable segregation (e.g., Manager, Marketing Associate, Software Engineer) that may drive the **perception of a gender pay gap**.
   - Perform Mann–Whitney U tests stratified by Department × Seniority.
   - Calculate Cliff’s Delta effect sizes to quantify directional differences.
   - Apply FDR correction for multiple comparisons to adjust significance levels.
   - Results show **no systematic disadvantage for women** in BasePay or Bonus after adjustment.
   - **Actionable Insights (Summary)**
        - **Occupational Segregation**: Implement targeted hiring programs and structured internal mobility to improve representation.
        - **BasePay**: Standardize starting salary offers and use predictive tools to ensure equity.
        - **Bonus Allocation**: Review bonus calculation criteria and monitor outcomes to prevent disparities.
        - **Education & Development**: Provide incentives, scholarships, and accessible learning programs for advanced education.
        - **Mentorship & Career Advancement**: Establish mentorship programs and development pathways to increase leadership access.
        - **Monitoring & Impact Evaluation**: Track KPIs, promotions, internal mobility, and salary trends to assess intervention effectiveness.


  
