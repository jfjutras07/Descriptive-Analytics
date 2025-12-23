# Life Expectancy (WHO): Descriptive Analytics

This project analyzes **World Health Organization (WHO) country-level health data** to answer the central question for **2015**:  

> *How are population health outcomes structured globally, and to what extent are disparities between countries and regions linked to economic development, education, and geography?*  

The goal is to provide a **clean, harmonized dataset and a series of analytical notebooks** that visualize and summarize global health outcomes, focusing on **life expectancy, mortality, and composite health indices**.

## Contents

1. **Life-Expectancy-WHO-EDA.ipynb** - Initial Data Overview and Cleaning
   - Load raw WHO health datasets (cross-sectional and panel)  
   - Inspect data structure, missing values, and inconsistencies  
   - Standardize column names across datasets for consistency  
   - Clean administrative columns (country names, regions, years) without altering core health or economic variables  

2. **Life-Expectancy-WHO-Data-Transformation.ipynb** – Composite Health Index and PCA  
   - Perform Principal Component Analysis (PCA) to summarize correlated health indicators  
   - Create the **PC1_health_index** as a composite measure of population health  
   - Validate PCA assumptions and interpret component loadings  
   - Prepare panel data (2000–2015) for longitudinal analyses  

3. **Life-Expectancy-WHO-Statistics.ipynb** – Statistical Analysis of Health Disparities  
   - Examine health differences by **development status** (developed vs developing countries)  
   - Perform **non-parametric tests** (Mann–Whitney U, Kruskal–Wallis, Dunn post-hoc)  
   - Conduct **panel regressions** to assess structural associations between education and health outcomes  
   - Confirm persistence of regional disparities over time (2000–2015)  

4. **Life-Expectancy-WHO-Synthesis.ipynb** – Visual Synthesis of Structural Health Disparities  
   - Provide **choropleth maps** to visualize global health distribution in 2015  
   - Create **regional boxplots** and tables highlighting outlier countries  
   - Scatter plots of PC1_health_index vs schooling to illustrate development-related health patterns  
   - Summarize spatial, temporal, and structural disparities in an interpretable, descriptive manner  
