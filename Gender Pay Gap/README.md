# Gender Pay Gap Analysis
### Investigating Compensation Equity Through Workforce Structure & Statistical Modeling
**Evidence-Based Assessment of Gender Disparities, Occupational Segregation & Adjusted Compensation Outcomes**

---

The objective of this project is to assess whether gender influences compensation outcomes after accounting for relevant professional characteristics.

Using the Glassdoor Gender Pay Gap dataset, this analysis investigates whether observed compensation differences reflect true gender-based disparities or are primarily explained by workforce composition, job distribution, seniority, education, and performance-related factors.

The central research question is:

**To what extent does gender influence compensation levels across comparable job titles and professional characteristics?**

The project combines descriptive analysis, statistical testing, and adjusted regression modeling to move beyond raw comparisons and identify the structural drivers behind observed compensation patterns.

---

### Data Preparation & Workforce Composition Analysis

- Compensation Validation:
  - Assessment of BasePay and Bonus distributions
  - Identification and contextual validation of extreme compensation values

- Workforce Structure Analysis:
  - Gender distribution across departments
  - Representation patterns across job titles
  - Education and seniority composition assessment
 
<img width="1212" height="767" alt="image" src="https://github.com/user-attachments/assets/1ce402d1-7b5f-464f-b5ee-074c9ded594d" />

**Key Finding:**

- Gender representation is relatively balanced across departments.
- Significant imbalances emerge primarily across job titles, suggesting occupational segregation as a major driver of observed compensation differences.

---

### Statistical Assessment of Compensation Differences

To evaluate how professional characteristics influence compensation, multiple statistical analyses were conducted:

- Two-way ANOVA:
  - Education and Gender effects on BasePay
  - Seniority and Gender effects on BasePay

- Robust ANOVA:
  - Applied following transformation and diagnostic assessment of model assumptions

- Post-hoc comparisons:
  - Identification of significant differences between education and seniority levels

**Findings:**

- Education and seniority are strong determinants of BasePay.
- Higher education levels and increased seniority consistently correspond to higher compensation.
- Raw gender differences remain visible before controlling for organizational factors, motivating adjusted analysis.

---

### Adjusted Compensation Modeling

Multiple Linear Regression models were developed to estimate gender effects while controlling for relevant professional characteristics.

**BasePay Model**

Controlled factors:

- Job Title
- Department
- Education
- Seniority
- Age
- Gender

**Results:**

- The model explains approximately 84% of BasePay variability.
- Gender is not statistically significant after accounting for professional characteristics.
- Observed salary differences are largely explained by role allocation, seniority, and career-related factors.

<img width="1247" height="752" alt="image" src="https://github.com/user-attachments/assets/12832682-9f39-4eef-aa2c-bda5aca4bb36" />

---

**Bonus Model**

Controlled factors:

- Job Title
- Department
- Education
- Seniority
- Age
- Gender
- Performance Evaluation

**Results:**

- The model explains approximately 93% of Bonus variability.
- Performance Evaluation is the strongest predictor of bonus outcomes.
- Adjusted results show a small gender effect, with males receiving slightly lower bonuses after controlling for relevant variables.

---

### Occupational Segregation Analysis

A Chi-square test was performed to evaluate the relationship between gender and job title distribution.

**Findings:**

- Gender and job title are significantly associated.
- Strong representation differences were identified in key roles:

  - Manager positions → predominantly male
  - Software Engineer roles → predominantly male
  - Marketing Associate roles → predominantly female

 <img width="752" height="485" alt="image" src="https://github.com/user-attachments/assets/2ae399ef-afaf-44d9-8003-f7bbfb4685b0" />

**Key Insight:**

Company-level compensation differences are largely influenced by workforce composition and role distribution rather than evidence of systematic unequal pay within comparable positions.

---

### Role-Level Compensation Insights

Selected job categories were investigated to better understand observed differences.

**Manager**

- Female managers show slightly higher average BasePay despite fewer advanced degrees.
- Compensation patterns suggest alignment after considering role characteristics.

**Marketing Associate**

- Women represent the majority of employees.
- Male associates show higher average BasePay, potentially influenced by experience and workforce composition differences.

**Software Engineer**

- Male employees are more represented and slightly more senior.
- Differences in compensation appear partly associated with seniority and professional profile differences.

---

### Performance Evaluation & Bonus Attribution

Performance evaluations were compared between genders within equivalent Department × Seniority groups.

**Methodology:**

- Mann–Whitney U tests
- Cliff’s Delta effect sizes
- False Discovery Rate correction for multiple comparisons

**Findings:**

- Some individual groups show directional differences.
- After correction for multiple testing, no systematic gender differences in performance evaluations are identified.

**Key Insight:**

Observed bonus differences are not explained by measurable performance disparities across comparable organizational contexts.

---

### Strategic Insights

**Main Finding:**

The analysis does not identify evidence of a systematic gender pay gap after controlling for professional characteristics.

The primary structural challenge identified is:

**Occupational segregation rather than unequal compensation.**

Implications:

- Compensation systems appear largely equitable once role characteristics are considered.
- Workforce representation differences across job categories explain most observed disparities.
- Improvement opportunities should focus on access, mobility, and representation.

---

### Actionable Recommendations

- Implement workforce composition monitoring by role and seniority level.
- Develop structured mobility pathways toward underrepresented positions.
- Improve transparency in recruitment and promotion processes.
- Standardize compensation frameworks for comparable roles.
- Review bonus allocation criteria regularly.
- Track long-term indicators such as promotion rates, compensation alignment, and internal mobility.

---

### Limitations & Future Improvements

- The dataset represents a single organizational snapshot and does not include internal compensation policies.
- Market benchmarks, geographic factors, and benefits are unavailable.
- Skills, certifications, project complexity, and informal responsibilities are not captured.
- Smaller job categories limit detailed role-level comparisons.

Future improvements could include longitudinal employee data, richer HR variables, and causal inference approaches.

---

### Project Structure

**Notebook 1 – Exploratory Analysis**
- Compensation distribution analysis
- Workforce composition assessment
- Gender representation patterns

**Notebook 2 – Statistical Analysis**
- Hypothesis testing
- ANOVA and robust statistical comparisons
- Adjusted BasePay and Bonus regression models

**Notebook 3 – Adjusted Disparities & Strategic Insights**
- Occupational segregation analysis
- Role-level investigations
- Performance attribution analysis
- Evidence-based recommendations

---

### Key Takeaways

- Raw compensation differences are primarily explained by workforce structure and job allocation.
- Job title, seniority, education, age, and performance factors explain most compensation variation.
- Adjusted models do not identify a systematic BasePay disadvantage for women.
- Data-driven interventions should prioritize representation, career mobility, and transparent decision processes.

---

### Conclusion

This project demonstrates how statistical analysis can move beyond simple compensation comparisons to distinguish between apparent disparities and underlying structural drivers.

By integrating workforce analysis, hypothesis testing, and adjusted modeling, the framework provides an evidence-based approach for evaluating compensation equity and identifying meaningful organizational improvement opportunities.
