# Measuring ROI on Sponsored Search Ads: A Causal Inference Approach

This project evaluates the **true impact of sponsored search advertising** for Bazaar.com using a natural experiment and Difference-in-Differences (DiD) methodology. By distinguishing between incremental and non-incremental traffic, we estimate a more accurate return on investment (ROI) and offer actionable insights for ad budget optimization.

## 🔍 Project Goals

- Quantify the causal impact of pausing Google sponsored ads.
- Identify the proportion of ad-driven traffic that is truly incremental.
- Correct traditional ROI calculations using statistical modeling.
- Inform ad strategy based on data-driven attribution.

## 📄 Files Included

- **`ROI-Sponsored-Causal-Report.pdf`**  
  Final written report with methods, findings, visualizations, and recommendations.

- **`ROI-Sponsored-Causal-Workbook.rmd`**  
  Full R Markdown analysis including data prep, regressions, plots, and ROI calculations.

## 🧪 Methods Used

- Difference-in-Differences (DiD) regression
- Pre-post comparison
- Parallel trends testing
- ROI decomposition and correction
- R-based data analysis and visualization

## 📈 Key Findings

- The naive ROI estimate was inflated due to misattributing organic traffic to paid ads.
- After adjusting for incrementality, the corrected ROI is **241%**.
- The DiD analysis revealed ~2,293 clicks would have occurred organically, highlighting the importance of causal methods in ROI analysis.

## 🛠 Technologies

- **R** (tidyverse, ggplot2, stats)
- **R Markdown** for reproducible analysis
- PDF report generated via RMarkdown to PDF

## ✅ Outcome

Bazaar.com gains a clearer picture of ad effectiveness, helping it reallocate budget toward channels and strategies that deliver **true incremental value**.

---

