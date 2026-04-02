# Lead Quality Optimization (Marketing Analytics Case Study)

## Objective (Why are we doing this?)

The goal of this project is to evaluate whether we can improve lead quality from **8.1% to 9.6% (+20%)** to unlock a higher **Cost Per Lead (CPL) incentive ($30 → $33)**.

In performance marketing, increasing lead volume is not enough—**the quality of leads directly impacts conversion, revenue, and ROI**. This project simulates a real-world optimization problem faced by fintech and lead-generation platforms.

---

## Problem Statement (What are we doing?)

We aim to answer three key questions:

1. **Trend Analysis:**  
   Are we seeing any improvement or decline in lead quality over time?  
   Are these changes statistically significant?

2. **Drivers of Lead Quality:**  
   What factors influence lead quality?  
   - Campaign type  
   - Traffic source (partner)  
   - Ad placement  
   - User intent (e.g., debt level)

3. **Optimization Opportunity:**  
   Can we realistically achieve a **20% improvement in lead quality**?  
   If yes, what actions should be taken?

---

## Dataset Overview

The dataset contains ~**3,000 leads** with information across:

- **Lead outcome:** Closed, Good, Bad, Unknown  
- **Marketing campaign:** Campaign categories (Debt, Credit, etc.)  
- **Traffic source (partner):** e.g., Google, Yahoo, advertise.com  
- **Ad placement:** Position and format of ads  
- **User attributes:** Debt level, state, etc.  
- **Time variable:** Weekly data for trend analysis  

---

## Approach (How are we doing it?)

### 1. Data Cleaning
- Fixed inconsistent campaign labels (e.g., state values in campaign column)
- Standardized categorical variables
- Converted date fields for time-series analysis

### 2. Feature Engineering
- Created lead quality indicators:
  - Good vs Bad classification
- Built time-based features for weekly trend analysis

### 3. Exploratory Data Analysis
- Analyzed lead quality trends over time
- Segmented performance across:
  - Campaigns
  - Partners
  - Ad placements
  - Keywords
  - User intent (debt level)

### 4. Statistical Validation
- Conducted **t-test** to compare early vs late periods  
- Result: **p-value ≈ 0.96 → No statistically significant trend**

### 5. Performance Analysis
- Identified high-performing vs low-performing segments
- Evaluated variability across traffic sources and campaigns

---

## Key Insights (What did we find?)

- Lead quality is **stable over time**, with no significant trend  
- Performance is driven by **traffic mix, not time-based improvement**
- Strong variation across segments:
  - Certain campaigns outperform others
  - Specific partners (e.g., advertise.com) deliver better quality
  - Ad placement impacts conversion
  - High-intent users (higher debt levels) convert better

---

## Final Outcome (What did we achieve?)

- Identified that improving **lead composition (not volume)** is key  
- Demonstrated that reallocating traffic toward high-performing segments can:
  - Close the **1.5% gap**
  - Achieve the **9.6% target**

### Recommended Strategy:
- Shift budget to high-performing campaigns and partners  
- Reduce low-quality traffic sources  
- Optimize ad placements  
- Focus on high-intent keywords and user segments  

---

## Key Takeaway

> No single factor drives improvement—performance gains come from optimizing multiple high-impact segments.

---

## Tools Used

- Python (Pandas, NumPy, SciPy)
- Power BI (for dashboarding)
- Statistical Analysis (t-test)

---

## Real-World Relevance

This project mirrors how **fintech and marketing teams optimize lead generation pipelines**.

Companies improve profitability by:
- Prioritizing **high-quality leads over volume**
- Using **data-driven segmentation**
- Continuously optimizing **traffic mix and targeting**

Even a **1–2% improvement in lead quality can significantly impact revenue**, as demonstrated in this case.

---


