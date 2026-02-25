# J.P. Morgan Quantitative Research Simulation

This project serves as a comprehensive simulation of Quantitative Research roles within both Commodity Trading and Retail Risk Management. It was developed to demonstrate the technical and analytical rigor required for advanced financial engineering programs.

## 📈 Project Overview

### Part 1: Energy Derivatives & Pricing
* **Time-Series Decomposition:** Analyzed natural gas historical data using an additive model ($Y_t = T_t + S_t + e_t$) to isolate secular trends from 12-month seasonal cycles.
* **Pricing Engine:** Developed an extrapolation function combining linear regression with seasonal re-injection to estimate future contract prices.
* **Valuation:** Built a storage contract pricing tool accounting for injection/withdrawal fees, monthly storage costs, and physical capacity constraints.

### Part 2: Credit Risk & Machine Learning
* **PD Modeling:** Trained a Logistic Regression model to predict the Probability of Default (PD) using borrower features (FICO, DTI, Income).
* **Regulatory Analytics:** Implemented Expected Loss (EL) calculations: $EL = PD \times LGD \times EAD$.
* **Optimal Bucketing:** Used **Dynamic Programming** to maximize the Log-Likelihood of FICO score buckets, ensuring statistically significant risk tiers for the bank's rating map.

## 🛠️ Tech Stack
* **Language:** Python 3.11
* **Libraries:** `pandas`, `scikit-learn`, `statsmodels`, `matplotlib`
* **Techniques:** Linear/Logistic Regression, Seasonal Decomposition, Dynamic Programming, Quantitative Finance.

---
*Developed as a portfolio asset for Master in financial engeneering / Quantitative Finance applications.*

**Note on Participation:** This project was completed as part of the J.P. Morgan Quantitative Research Job Simulation on Forage. All datasets provided are synthetic and used exclusively for educational and career-advancement purposes.
