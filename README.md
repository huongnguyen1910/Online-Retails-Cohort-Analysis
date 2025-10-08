# Online-Retails-Cohort-Analysis

## Overview
This project analyzes **e-commerce transactional data** to uncover key business insights and demonstrate skills in **data analysis, KPI tracking, and statistical testing** .

I explore customer purchasing patterns, revenue trends, and retention, then run **hypothesis testing (Welch’s t-test)** to compare **new vs returning customers**.  
Finally, I summarize actionable business recommendations.

---

## Objectives
- Clean and explore raw transactional data (~1M rows).  
- Calculate key metrics:  
  - **Revenue** over time  
  - **Customer growth** (new vs returning)  
  - **Average Order Value (AOV)** and **Order Size**  
- Conduct **cohort analysis** for retention tracking.  
- Perform **statistical testing** to compare **returning vs new customers**.  
- Provide actionable recommendations to improve business strategy.

---

## Hypothesis Testing

**Hypothesis:**  
> Returning customers spend **more** and have **larger order sizes** compared to new customers.

- Test: **Welch’s t-test** (independent samples, unequal variances).  
- Metrics tested: **Average Order Value (AOV)** & **Order Size**.

**Business implications:**  
- If returning customers spend significantly more → **invest in retention strategies** (loyalty programs, personalized offers).  
- If no significant difference → **focus on acquiring new customers**.

---

## Key Insights

- **Seasonality:** Revenue peaks in **November–December** (holiday sales), with low performance in Q1.  
- **Market concentration:** **>85% revenue from UK** → high dependency on one market.  
- **Top SKUs:** ~20 products generate ~15% of total revenue, many are **packs/bundles**.  
- **Retention:** Only ~25% of customers return in the 2nd month, <10% remain after 6 months.  
- **Statistical testing:** Returning customers show **significantly higher AOV (18,5% higher in AOV) (p < 0.05)**.


---
## Recommendations

- **Focus on retention:** Returning customers show higher AOV and larger orders → invest in loyalty programs, post-purchase emails, personalized offers.
- **Diversify markets:** UK contributes >85% revenue → pilot campaigns in other countries to reduce risk.
- **Optimize SKU mix & pricing:** Keep top-selling SKUs always in stock, bundle low-margin with high-margin items, test small price changes.

---

## Tech Stack
- **Python:** pandas, numpy, matplotlib, seaborn, scipy
- **Data Visualization:** Matplotlib, Seaborn  
- **Dashboard:** Power BI  
- **Statistical Analysis:** Welch’s t-test  

---
