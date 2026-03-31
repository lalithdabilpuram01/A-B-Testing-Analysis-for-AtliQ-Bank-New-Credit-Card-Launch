# AtliQo Bank: Data-Driven Credit Card Launch & A/B Testing

This repository contains a high-impact, two-phase data science project focused on market penetration and product validation for AtliQo Bank. The project transitions from deep exploratory data analysis to rigorous statistical hypothesis testing to justify a new credit card product launch.

---

## Project Objective
To identify a high-potential, underserved customer segment within AtliQo Bank’s ecosystem and validate a targeted credit card launch strategy using A/B testing and statistical inference.

---

## Phase 1: Strategic Market Identification
The first phase focuses on unearthing hidden patterns in customer behavior to define the "Ideal Customer Profile" for the new launch.

### Key Technical Milestones:
* **Data Orchestration**: Engineered a unified dataset by merging complex customer demographics, credit profiles, and historical transaction logs.
* **Advanced EDA**: Utilized Python and Seaborn to visualize spending habits, revealing a massive opportunity in the 18–25 age demographic.
* **Segment Insights**: 
    * **The Opportunity**: This segment accounts for approximately 26% of the total customer base but remains under-leveraged.
    * **The Barrier**: Identified that low credit history and annual incomes (typically <$50k) lead to low credit limits and infrequent usage.
    * **Consumer Behavior**: Mapped top spending categories to Electronics, Fashion & Apparel, and Beauty & Personal Care, providing a blueprint for reward-point optimization.

---

## Phase 2: Statistical Validation (A/B Testing)
To minimize risk, a trial launch was simulated and analyzed using frequentist statistical methods to ensure the results were not due to random chance.

### Experimental Design:
* **Hypothesis**: The targeted marketing strategy for the 18–25 group will result in significantly higher transaction values compared to a general control group.
* **Methodology**: Implemented a One-Tailed Z-Test to compare the test group average transactions against the control group average.

### The Results:
* **Z-Statistic**: 2.748
* **P-Value**: 0.0029
* **Conclusion**: With a p-value well below the 0.05 significance threshold, the null hypothesis was rejected. The data provides strong evidence that the targeted launch strategy is statistically significant and ready for full-scale deployment.

---

## Tech Stack & Expertise
* **Languages**: Python (Pandas, NumPy)
* **Statistical Modeling**: Statsmodels (Z-Test, Hypothesis Testing)
* **Visualization**: Matplotlib, Seaborn
* **Domain Knowledge**: Fintech, Credit Risk Profiling, A/B Testing Frameworks

---

## Project Structure
* `phase_1_atliqo_bank.ipynb`: Data cleaning, segmentation, and untapped market discovery.
* `phase_2_atliqo_bank.ipynb`: A/B test implementation and statistical validation.

---

## Business Impact
By shifting focus to a younger demographic with tailored rewards in high-volume categories, AtliQo Bank can increase credit card adoption rates by tapping into a segment that represents over a quarter of their existing audience, supported by a 99% statistical confidence level.
