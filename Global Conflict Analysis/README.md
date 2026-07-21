# Global Conflict Analysis
### Exploring Conflict Dynamics Through Temporal, Geographic & Statistical Analysis
**Descriptive Assessment of Conflict Severity, Media Visibility & Global Conflict Patterns (1979–2021)**

---

The objective of this project is to analyze global conflict dynamics using a comprehensive conflict events dataset covering the period 1979–2021.

This analysis investigates how conflict events evolve over time, how severity varies across conflict categories and geographic areas, and whether media attention reflects conflict intensity or follows alternative structural patterns.

The central research questions are:

**How have global conflict patterns evolved between 1979 and 2021?**

**To what extent does conflict severity influence media visibility across countries and regions?**

The project combines descriptive analysis, statistical testing, and interactive visualization to identify temporal trends, geographic concentrations, and relationships between conflict activity and media coverage.

---

### Data Preparation & Conflict Structure Analysis

The dataset was prepared to support global, regional, and country-level analysis.

Key preparation steps included:

- Data validation:
  - Verification of country-region mappings
  - Standardization of geographic identifiers
  - Preparation of temporal and spatial aggregation levels

- Conflict structure assessment:
  - Analysis of four main conflict categories:
    - Assault
    - Coerce
    - Fight
    - Unconventional Mass Violence

<img width="1012" height="597" alt="image" src="https://github.com/user-attachments/assets/c8777b7d-4d5a-4400-92c9-5831c93db1d5" />

- Severity assessment:
  - Evaluation using the Goldstein Scale
  - Identification of extreme conflict events (GoldsteinScale ≤ -9)

**Key Finding:**

- Conflict categories present distinct severity profiles.
- Fight and Unconventional Mass Violence represent the most severe conflict categories.
- Coerce events are the most frequent category but display greater severity variability.

---

### Temporal Evolution of Global Conflicts (1979–2021)

Conflict activity was analyzed through yearly trends to identify long-term evolution patterns.

**Analysis Focus:**

- Total conflict event evolution
- Category-specific trajectories
- Changes in conflict intensity over time

**Findings:**

- Global conflict activity gradually increased until approximately 2014–2016.
- Event frequency declined after the mid-2010s peak.
- Average conflict severity slightly worsened over the analyzed period.
- The highest conflict intensity coincided with the period of maximum event activity.

<img width="1332" height="635" alt="image" src="https://github.com/user-attachments/assets/beaec8dc-1449-4168-94dd-2402183f86a5" />

**Key Insight:**

Conflict dynamics are not static, with global escalation and decline phases emerging clearly over the 40-year period.

---

### Conflict Severity Analysis

Conflict intensity was examined using the Goldstein Scale to distinguish between overall conflict exposure and extreme violence patterns.

The analysis focused on:

- Severity distribution across conflict types
- Countries experiencing the highest number of severe events
- Geographic concentration of extreme conflicts

**Findings:**

- Severe conflicts are unevenly distributed globally.
- Countries with the highest number of conflict events are not always those experiencing the most extreme events.
- Frequency and severity represent different dimensions of conflict burden.

<img width="1257" height="702" alt="image" src="https://github.com/user-attachments/assets/797ba8cd-f4f6-4e3d-ae49-9ba21e5c8891" />

**Key Insight:**

Understanding global conflict requires evaluating both how often conflicts occur and how intense individual events become.

---

### Media Coverage & Conflict Severity Analysis

To assess whether severe conflicts receive greater media attention, multiple statistical approaches were applied:

- Descriptive comparison of media coverage across severity levels
- Spearman correlation analysis
- Regional correlation assessment
- Welch ANOVA
- Games–Howell post-hoc comparisons

**Findings:**

- Conflict severity shows very weak relationships with media coverage.
- Media visibility is strongly associated with event volume rather than conflict intensity.
- Regional differences exist in average coverage levels, but the overall severity–coverage relationship remains consistent globally.

**Key Insight:**

Media attention appears to follow the quantity of conflict events more strongly than their severity.

---

### Geographic Distribution of Conflict Exposure

Interactive geographic analysis was conducted to identify global conflict patterns.

The analysis examines:

- Conflict events normalized by population
- Severe conflict events by country
- Regional concentration patterns

**Findings:**

- Conflict exposure is highly uneven across countries.
- Some countries experience very high conflict intensity relative to population size.
- Severe conflict hotspots do not always overlap with countries having the highest total event counts.

**Key Insight:**

Conflict burden cannot be represented by a single metric; exposure and intensity provide complementary perspectives.

---

### Regional Analysis of Severe Conflict Types

A Chi-square analysis was performed to determine whether severe conflict event types differ across regions.

**Methodology:**

- Region × Conflict Type contingency analysis
- Chi-square test of independence
- Standardized residual analysis

**Findings:**

- Severe conflict type distributions vary significantly across regions.
- Some regions show over- or under-representation of specific conflict categories.
- Regional conflict profiles display distinct structural patterns.

**Key Insight:**

Different regions experience different forms of severe conflict, highlighting the importance of geographic context.

---

### Media Visibility & Geographic Disparities

Additional indicators were developed to explore differences between conflict activity and media attention.

The analysis investigated:

- Media visibility relative to normalized conflict activity
- Country-level differences in coverage intensity
- Potential disparities between conflict burden and global attention

**Findings:**

- Countries with comparable conflict activity may receive substantially different levels of media attention.
- Media visibility is influenced by factors beyond conflict severity alone.
- Geographic disparities suggest potential differences in reporting intensity.

<img width="1257" height="722" alt="image" src="https://github.com/user-attachments/assets/c07d1766-7ea4-472b-8d69-414e2bf9429c" />

**Key Insight:**

Media coverage should not be considered a direct proxy for humanitarian impact or conflict severity.

---

### Strategic Insights

**Main Finding:**

Global conflict patterns reveal a complex relationship between conflict frequency, severity, geographic exposure, and media visibility.

The analysis highlights three major conclusions:

- Conflict intensity varies substantially across countries and regions.
- Extreme violence is concentrated in specific geographic areas.
- Media attention does not systematically reflect conflict severity.

Implications:

- Conflict monitoring should combine multiple indicators rather than relying on a single measure.
- High-intensity but low-visibility crises may require additional analytical attention.
- Geographic and statistical analysis can support better understanding of global instability patterns.

---

### Actionable Analytical Extensions

Potential future developments include:

- Developing severity-adjusted media visibility indicators.
- Integrating additional humanitarian and socioeconomic datasets:
  - Population displacement
  - Conflict fatalities
  - Economic indicators
  - Governance metrics

- Applying advanced analytical methods:
  - Conflict trajectory clustering
  - Structural break detection
  - Multivariate modeling of conflict drivers

- Building scenario-based frameworks for deeper conflict risk assessment.

---

### Limitations & Future Improvements

- The dataset only captures recorded and reported conflict events.
- Media indicators may reflect reporting practices rather than actual conflict importance.
- Goldstein Scale measures event intensity but does not capture all dimensions of human impact.
- Regional classifications simplify complex geopolitical realities.
- External socioeconomic and humanitarian factors are not included.

Future improvements could include multi-source validation, integration of humanitarian indicators, and advanced longitudinal modeling approaches.

---

### Project Structure

**Notebook 1 – Exploratory Analysis**
- Data preparation and validation
- Conflict category assessment
- Severity distribution analysis
- Temporal evolution analysis

**Notebook 2 – Statistical Analysis**
- Correlation analysis
- Regional comparisons
- Media coverage assessment
- Geographic conflict analysis

**Notebook 3 – Dashboard & Analytical Synthesis**
- Interactive visualization development
- Temporal trend exploration
- Media visibility analysis
- Strategic insights and future analytical directions

---

### Key Takeaways

- Global conflict activity increased until the mid-2010s before declining.
- Conflict categories display distinct severity profiles.
- Severe conflicts are geographically concentrated but do not always correspond to the highest event volumes.
- Media attention is primarily associated with conflict quantity rather than intensity.
- Combining statistical analysis and visualization provides a broader understanding of global conflict dynamics.

---

### Conclusion

This project demonstrates how descriptive analytics, statistical testing, and interactive visualization can reveal complex patterns in global conflict dynamics.

By combining temporal, geographic, and media visibility analyses, the framework provides a structured assessment of how conflicts evolve, where severe events concentrate, and why conflict severity alone does not determine global attention.
