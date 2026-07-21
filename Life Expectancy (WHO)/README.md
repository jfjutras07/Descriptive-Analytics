# Global Health and Life Expectancy Analysis
### Structural Assessment of Global Health Disparities Through Economic, Educational & Regional Perspectives
**Cross-Country Health Analysis, Composite Index Construction & Longitudinal Regional Trends (2000–2015)**

---

The objective of this project is to examine how economic development, education, and regional context are associated with differences in population health outcomes across countries.

Using the WHO Life Expectancy dataset, this analysis investigates global health disparities through a combination of descriptive exploration, statistical testing, dimensionality reduction, and longitudinal analysis. A composite health index was developed using Principal Component Analysis (PCA) to summarize correlated health indicators into a single interpretable measure of population health.

The project focuses on understanding whether observed health inequalities in 2015 represent isolated differences or persistent structural patterns over time.

---

## Research Questions

- How do population health outcomes differ between developed and developing countries?
- Are regional health disparities statistically significant?
- How strongly are education and economic development associated with health outcomes?
- Do global health inequalities persist over time despite overall improvements?

---

## Analytical Framework

The analysis was conducted through four sequential notebooks:

### 1. Data Preparation & Exploratory Analysis

- Dataset validation and cleaning
- Missing value assessment
- Variable exploration and distribution analysis
- Initial identification of health and socioeconomic relationships

### 2. Composite Health Index Construction

- Principal Component Analysis (PCA) applied to life expectancy, adult mortality, and BMI
- Creation of `PC1_health_index` capturing the dominant health dimension

<img width="1305" height="486" alt="image" src="https://github.com/user-attachments/assets/2bc86890-f765-4193-b561-e8f263d80cbb" />

- Multicollinearity assessment using correlation analysis and Variance Inflation Factors (VIF)
- Distribution analysis and targeted transformations for continuous variables

The resulting health index provides a unified measure of population health while reducing redundancy among correlated indicators.

### 3. Statistical Analysis & Panel Trends (2000–2015)

Multiple statistical approaches were applied according to data characteristics:

- Mann–Whitney U test for developed vs. developing country comparisons
- Kruskal–Wallis test for regional differences
- Dunn’s post-hoc comparisons with Bonferroni correction
- Robust regression models accounting for non-normality and outliers
- Fixed-effects panel regression to evaluate within-region temporal associations

The analysis demonstrated strong and persistent differences in population health across development levels and regions.

### 4. Visual Synthesis of Structural Disparities

A final communication layer was developed to translate analytical findings into interpretable visual evidence:

- Global health choropleth mapping
- Regional distribution comparisons
- Development status comparisons
- Education-health relationship visualization
- Identification of regional health outliers

<img width="1352" height="737" alt="image" src="https://github.com/user-attachments/assets/257e8022-f433-4178-9814-9008acb74f50" />

---

## Key Findings

### Persistent Global Health Inequalities

Developed countries consistently exhibit better population health profiles, characterized by:

- Higher life expectancy
- Lower adult mortality
- More favorable nutritional indicators
- Higher educational attainment

The Mann–Whitney U test confirmed a statistically significant separation between developed and developing countries:
- **U = 479**
- **p < 0.001**
- **Cliff’s Delta = −0.82**

indicating a large distributional difference in overall health outcomes.

---

### Strong Regional Health Disparities

Health outcomes differ significantly across geographic regions:

- Kruskal–Wallis test:
  - **H = 108.09**
  - **p < 0.001**

Post-hoc analysis identified substantial differences between regions, particularly between Africa and higher-income regions such as Europe, North America, and Oceania.

---

### Education as a Major Health Dimension

Schooling demonstrates a strong association with population health:

- Spearman correlation between schooling and health index:
  - **ρ ≈ −0.74**

However, the strong relationship between education and health requires cautious interpretation, as education and development status capture overlapping structural factors.

---

### Structural Persistence Over Time

Panel analysis from 2000 to 2015 indicates that health disparities are not temporary fluctuations:

- Between-region variance:
  - **≈ 1.04**

- Within-region temporal variance:
  - **≈ 0.067**

Regional differences remain substantially larger than year-to-year changes, suggesting persistent structural inequalities.

---

## Methodological Considerations

Several analytical decisions were made to account for dataset characteristics:

- PCA was used to reduce multicollinearity among correlated health indicators.
- Non-parametric statistical tests were selected due to non-normal distributions.
- Robust regression methods were applied to reduce sensitivity to outliers and heteroskedasticity.
- Fixed-effects panel models controlled for persistent regional characteristics.

The results should be interpreted as descriptive and associative rather than causal.

---

## Main Limitations

- The analysis identifies relationships but does not establish causal mechanisms.
- The composite health index may hide differences between individual health indicators.
- Regional aggregation may mask important country-level variation.
- The dataset covers 2000–2015 and does not capture more recent developments.
- Education, economic development, and health outcomes are strongly interconnected, limiting causal separation.

---

## Conclusion

This project demonstrates that global health inequalities are strongly structured by economic development, education, and geography.

While overall health improved between 2000 and 2015, regional rankings remained relatively stable, indicating that disparities are deeply embedded rather than temporary. Combining PCA-based index construction, non-parametric inference, robust modeling, and longitudinal analysis provides a comprehensive framework for understanding complex global health patterns.
