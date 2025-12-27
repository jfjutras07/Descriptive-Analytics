# Descriptive Analytics Project : AI Impact on Jobs 2030

This project investigates the **potential impact of artificial intelligence on jobs by 2030** using **descriptive and statistical analyses**. The goal is to understand **which occupations are most exposed to automation**, how **job characteristics such as salary, experience, education, and AI exposure are distributed**, and how these relate to **automation probability**. Analyses are exploratory and descriptive, without making predictive or causal claims.

> *Which types of jobs are most at risk of automation, and how do job characteristics distribute across different levels of automation risk?*

## Contents

1. **AI Impact on Jobs 2030 - EDA** – Data Loading and Overview  
   - Load the AI Impact on Jobs 2030 dataset containing 3,000 observations across 20 job titles  
   - Inspect dataset structure, missing values, duplicates, and variable types  
   - Provide a statistical summary of numeric variables (Average_Salary, Years_Experience, AI_Exposure_Index, Tech_Growth_Factor, Automation_Probability_2030)  
   - Describe dataset columns and provide context for AI exposure and automation risk  
   - Initial univariate exploration to highlight patterns across occupations  

2. **AI Impact on Jobs 2030 - Stats** – Relationships Between Job Characteristics and Automation Risk  
   - Examine distributions of salary, experience, education, and AI exposure across automation risk levels  
   - Conduct normality and homogeneity tests for parametric analyses  
   - Apply Kruskal-Wallis and post-hoc Dunn tests to assess automation probability by education level  
   - Perform ANOVA and Welch ANOVA to examine differences in automation probability across job titles  
   - Conduct Games–Howell post-hoc comparisons for occupational stratification  
   - Fit mixed-effects Beta regression with job title as a random intercept to assess individual-level predictors  

3. **AI Impact on Jobs 2030 - Insights** – Insights into High-, Medium-, and Low-Risk Jobs  
   - Explore distributions of key metrics (Average_Salary, Years_Experience, AI_Exposure_Index, Tech_Growth_Factor) within each Risk_Category  
   - Visualize automation probability by job title using boxplots and stacked bar charts  
   - Summarize central tendencies for each risk category with radar charts  
   - Examine intra-occupational heterogeneity for high-risk jobs, including salary, experience, AI exposure, tech growth, and education  
