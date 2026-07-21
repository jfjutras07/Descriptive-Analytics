# AI Impact on Jobs 2030
### Workforce Transformation Analysis & Occupational Automation Risk Assessment
**Descriptive Analytics, Statistical Testing & Occupation-Based Risk Profiling**

---

The objective of this project is to analyze occupational vulnerability to AI-driven automation using a simulated 2030 workforce dataset. It combines descriptive analytics and statistical methods to identify how automation risk varies across occupations and whether traditional workforce characteristics explain this variation.

The analysis integrates:

- Occupational Risk Assessment: Comparison of automation probability across 20 job categories.
- Workforce Characteristics: Analysis of salary, experience, education, AI exposure, and technology growth factors.
- Statistical Validation: Testing whether observed differences represent meaningful patterns.
- Risk Profiling: Exploration of Low, Medium, and High automation risk categories.

By combining exploratory analysis, statistical testing, and occupation-level profiling, the project provides insights into how automation vulnerability is structured and supports evidence-based workforce planning.

---

### Data Architecture & Preprocessing

- Dataset Integration: Simulated AI Impact on Jobs 2030 dataset from Kaggle, containing 3,000 observations across 20 occupations.
- Data Validation: Confirmed absence of missing values and duplicate records.
- Feature Selection: Focused analysis on automation probability, occupational characteristics, and workforce indicators.
- Data Limitation: Results represent patterns within simulated data and should not be interpreted as real-world forecasts.

**Feature Engineering**

- Automation Risk Classification:
  - Low, Medium, and High risk categories derived from automation probability.
- Workforce Indicators:
  - Salary
  - Years of experience
  - Education level
  - AI exposure index
  - Technology growth factor

---

### Descriptive Analysis & Occupational Profiling

- Distribution analysis of automation probability across occupations.
- Comparison of workforce characteristics by risk category.
- Assessment of relationships between automation probability and continuous variables.

**Key Findings:**

- Automation risk varies substantially across occupations.
- High-risk roles include Construction Worker, Retail Worker, Security Guard, Truck Driver, and Customer Support.
- Lower-risk roles include Doctor, Nurse, Teacher, Research Scientist, and AI Engineer.

<img width="1162" height="746" alt="image" src="https://github.com/user-attachments/assets/2452dd4d-6c41-4a53-8431-15a7634c4bc1" />

---

### Statistical Analysis

**Group Comparison Testing**

- Kruskal-Wallis and Dunn tests:
  - No significant automation risk differences across education levels.
- Welch ANOVA and Games-Howell post-hoc analysis:
  - Significant differences identified across occupations.

**Mixed-Effects Beta Regression**

- Modeled automation probability while accounting for occupational clustering.

Predictors:

- Average Salary
- Years of Experience
- AI Exposure Index
- Technology Growth Factor

**Results:**

- Individual-level characteristics showed limited explanatory power.
- Job title represented the dominant source of variation in automation probability.

---

### Risk-Based Insights

**High-Risk Occupations**

- Show substantial variation in:
  - Salary levels
  - Experience requirements
  - AI exposure
  - Technology growth sensitivity
 
<img width="823" height="598" alt="image" src="https://github.com/user-attachments/assets/5314ceca-76d7-49f1-abd9-dce0c9cb52c0" />

**Key Insight:**

- Automation vulnerability is primarily structured by occupational identity and task composition rather than individual characteristics.

---

### Validation & Robustness

- Statistical assumptions assessed before hypothesis testing.
- Parametric and non-parametric methods applied depending on data characteristics.
- Mixed-effects modeling used to separate occupation-level effects from individual predictors.

**Robustness Finding:**

- Multiple analytical approaches consistently identified occupation as the strongest determinant of automation risk.

---

### Strategic Insights

**Workforce Transformation Trade-offs**

- Education level alone is insufficient to assess automation vulnerability.
- Technology exposure does not automatically translate into higher automation risk.
- Workforce strategies should focus on tasks, skills, and occupational transitions.

**Key Implication:**

- Automation risk assessment requires occupation-based analysis rather than employee-level characteristics alone.

---

### Actionable Recommendations

- Develop occupation-based automation risk frameworks integrating task composition and technology adoption.
- Prioritize skill-based reskilling strategies rather than education-based segmentation.
- Combine occupational analysis with individual skill profiles to improve workforce transition planning.

---

### Project Structure

**Notebook 1 – Descriptive Analysis**
- Dataset exploration and validation
- Workforce characteristic analysis
- Automation probability distributions
- Occupational comparisons

**Notebook 2 – Statistical Analysis**
- Hypothesis testing
- Education and occupation comparisons
- Mixed-effects beta regression
- Statistical validation

**Notebook 3 – Insights**
- Risk-category profiling
- High-risk occupation analysis
- Workforce heterogeneity assessment

---

### Key Takeaways

- Occupational structure is the primary driver of automation risk in the dataset.
- Salary, experience, education, and AI exposure show limited explanatory power.
- High-risk occupations remain heterogeneous and require nuanced workforce analysis.
- Evidence-based workforce planning should focus on tasks and skills rather than job labels alone.

---

### Conclusion

This project demonstrates how applied analytics can support workforce transformation decisions by combining descriptive analysis, statistical validation, and occupational risk assessment.

It provides an interpretable framework to analyze technology disruption, identify workforce vulnerabilities, and support strategic planning in evolving labor markets.
