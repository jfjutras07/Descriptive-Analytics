# Descriptive Analytics Project: Global Conflict Analysis (1979–2021)

This project analyzes the **Global Conflict Events Dataset (1979–2021, Kaggle)** to extract **descriptive insights on patterns of conflict and violence across countries and time**. The aim is to provide actionable information that helps **organizations, governments, and decision-makers** understand conflict trends and severity, as well as media coverage patterns.

## Contents

1. **Global-conflict-analysis-1979-2021-eda.ipynb** – Introduction and Exploratory Data Analysis (EDA)  
   - Overview of global conflict trends and patterns  
   - Initial exploration of dataset features: event counts, severity (GoldsteinScale), media coverage (AvgNumMentions), and media tone (AvgAvgTone)  
   - Descriptive statistics for continuous, discrete, and categorical variables  
   - Data transformation techniques (Box-Cox and log transformations) to address skewness and extreme values  
   - Visualizations: histograms, boxplots, Q-Q plots, pie charts, and temporal trends  
   - Identification of the most frequent conflict types and countries most affected  
   - Limitations of the dataset and potential reporting biases  

2. **Global-conflict-analysis-1979-2021-stats.ipynb** – Statistical Analysis  
   - Compute Spearman correlations to examine relationships between conflict severity (GoldsteinScale), media coverage (AvgNumMentions, SumNumMentions), and event counts  
   - Conduct continental and regional breakdowns to explore spatial patterns  
   - Test ANOVA assumptions: normality of groups and homogeneity of variances (Levene’s test, Brown-Forsythe test)  
   - Perform Welch ANOVA to assess differences in average media coverage across regions  
   - Apply Games-Howell post-hoc tests to identify specific regional contrasts accounting for unequal variances and sample sizes  
   - Aggregate events per 1,000 inhabitants to standardize comparisons across countries  
   - Filter for severe conflict events (GoldsteinScale ≤ -9) to analyze extreme incidents  
   - Construct contingency tables (Region × Event Type) and conduct Chi-square tests of independence  
   - Compute standardized residuals to detect over- or under-represented event types by region  
   - Visualize distributions and patterns using violin plots, heatmaps, and choropleth maps  

3. **Global-conflict-analysis-1979-2021-insights.ipynb** – Visualization and Synthesis of Insights  
   - Visualize trends using line charts and choropleth maps for event frequency, severity, and media coverage  
   - Examine countries most affected by severe conflicts using bar charts and normalized metrics  
   - Provide actionable insights for decision-makers and suggest next steps for deeper temporal and media coverage analyses  

