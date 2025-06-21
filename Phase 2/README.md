# 🧪 Retail Reimagined – Phase 2: Experimentation & Uplift Testing – Trial vs Control Store Impact

## 📌 Overview

This project is the **second phase of a comprehensive analytics initiative** focused on improving chip sales across a national retail chain.

After performing deep customer and product-level behavioral analysis in Phase 1, we now enter Phase 2: **measuring the impact of a store trial experiment** using real transactional data and statistical testing.

The objective of this phase is to:
- Select suitable control stores using data-backed correlation
- Compare sales performance of trial stores against their matched controls
- Quantify the sales uplift (or decline) and validate it using statistical tests

This phase simulates real-world **A/B testing** commonly used in business to guide strategic rollouts.

---

## 🛠️ Tools & Technologies

- **Python 3.x**
- **Pandas** – Time series manipulation
- **NumPy** – Numeric operations
- **Matplotlib / Seaborn** – Sales visualizations
- **SciPy** – Statistical significance testing (T-Test)
- **Jupyter Notebook** – Interactive analysis environment

---

## 📂 Data Used

- `QVI_transaction_data.csv`: Complete transaction history including store numbers and total sales per line item.
- Focused on chip category products only, consistent with Phase 1.

---

## 📊 Key Analysis Steps

1. **Pre-Trial Store Matching**
   - Filtered 3 months of sales data before the trial period (Nov 2018 – Jan 2019)
   - Created pivot tables to compare monthly sales across stores
   - Computed correlation between trial stores and all other stores
   - Selected control stores with:
     - High sales trend correlation
     - Similar sales magnitude
     - No missing pre-trial months

2. **Trial Period Comparison**
   - Isolated trial period: Feb–Apr 2019
   - Aggregated total monthly sales per trial and control store
   - Visualized trial vs control trends side by side

3. **Uplift Measurement**
   - Calculated average sales for trial and control stores
   - Computed % uplift for each store pair
   - Conducted **Welch’s T-Test** to check statistical significance

---

## 📈 Results Summary

| Trial Store | Control Store | Uplift % | P-Value   | Statistically Significant? |
|-------------|----------------|----------|-----------|-----------------------------|
| 77          | 195            | +40.28%  | 0.02680   | ✅ Yes                      |
| 86          | 259            | -8.75%   | 0.29365   | ❌ No                       |
| 88          | 36             | +49.66%  | 0.00049   | ✅ Yes                      |

---

## 💡 Business Insights & Recommendations

- ✅ **Trial Stores 77 and 88** demonstrated a **statistically significant uplift** in sales. These stores should be prioritized for layout/strategy rollout.
- ⚠️ **Store 86** showed a minor drop, but it was **not statistically significant** — likely just random variation.
- 📊 The experimental approach was validated and is ready for use across more stores.
- 📦 Monitoring these rollouts with dashboards and KPIs would help optimize long-term strategy.

---

## 🧠 What I Learned

- How to simulate real-world **A/B testing** in a retail analytics scenario
- Matching control groups using **correlation and sales magnitude**
- Applying **Welch’s T-Test** to test significance of results
- Building trustworthy, insight-backed visual stories
- Translating statistical results into **clear business decisions**

---

## 📁 Project Status

✅ Completed (Phase 2: Experimental Testing & Impact Measurement)  
🧪 Completed uplift validation across trial and control stores  
📈 Ready to scale or present to stakeholders as a business case

---

## 📬 Contact

**Sahil Lodhi**  
Aspiring Data Analyst | Python • Tableau • SQL  
🔗 [LinkedIn](https://www.linkedin.com/in/sahil-lodhi/)  
🔗 [GitHub](https://github.com/Sahillodhi29)
# 🧪 Retail Reimagined – Phase 2: Experimentation & Uplift Testing – Trial vs Control Store Impact

## 📌 Overview

This project is the **second phase of a comprehensive analytics initiative** focused on improving chip sales across a national retail chain.

After performing deep customer and product-level behavioral analysis in Phase 1, we now enter Phase 2: **measuring the impact of a store trial experiment** using real transactional data and statistical testing.

The objective of this phase is to:
- Select suitable control stores using data-backed correlation
- Compare sales performance of trial stores against their matched controls
- Quantify the sales uplift (or decline) and validate it using statistical tests

This phase simulates real-world **A/B testing** commonly used in business to guide strategic rollouts.

---

## 🛠️ Tools & Technologies

- **Python 3.x**
- **Pandas** – Time series manipulation
- **NumPy** – Numeric operations
- **Matplotlib / Seaborn** – Sales visualizations
- **SciPy** – Statistical significance testing (T-Test)
- **Jupyter Notebook** – Interactive analysis environment

---

## 📂 Data Used

- `QVI_transaction_data.csv`: Complete transaction history including store numbers and total sales per line item.
- Focused on chip category products only, consistent with Phase 1.

---

## 📊 Key Analysis Steps

1. **Pre-Trial Store Matching**
   - Filtered 3 months of sales data before the trial period (Nov 2018 – Jan 2019)
   - Created pivot tables to compare monthly sales across stores
   - Computed correlation between trial stores and all other stores
   - Selected control stores with:
     - High sales trend correlation
     - Similar sales magnitude
     - No missing pre-trial months

2. **Trial Period Comparison**
   - Isolated trial period: Feb–Apr 2019
   - Aggregated total monthly sales per trial and control store
   - Visualized trial vs control trends side by side

3. **Uplift Measurement**
   - Calculated average sales for trial and control stores
   - Computed % uplift for each store pair
   - Conducted **Welch’s T-Test** to check statistical significance

---

## 📈 Results Summary

| Trial Store | Control Store | Uplift % | P-Value   | Statistically Significant? |
|-------------|----------------|----------|-----------|-----------------------------|
| 77          | 195            | +40.28%  | 0.02680   | ✅ Yes                      |
| 86          | 259            | -8.75%   | 0.29365   | ❌ No                       |
| 88          | 36             | +49.66%  | 0.00049   | ✅ Yes                      |

---

## 💡 Business Insights & Recommendations

- ✅ **Trial Stores 77 and 88** demonstrated a **statistically significant uplift** in sales. These stores should be prioritized for layout/strategy rollout.
- ⚠️ **Store 86** showed a minor drop, but it was **not statistically significant** — likely just random variation.
- 📊 The experimental approach was validated and is ready for use across more stores.
- 📦 Monitoring these rollouts with dashboards and KPIs would help optimize long-term strategy.

---

## 🧠 What I Learned

- How to simulate real-world **A/B testing** in a retail analytics scenario
- Matching control groups using **correlation and sales magnitude**
- Applying **Welch’s T-Test** to test significance of results
- Building trustworthy, insight-backed visual stories
- Translating statistical results into **clear business decisions**

---

## 📁 Project Status

✅ Completed (Phase 2: Experimental Testing & Impact Measurement)  
🧪 Completed uplift validation across trial and control stores  
📈 Ready to scale or present to stakeholders as a business case

---

## 📬 Contact

**Sahil Lodhi**  
Aspiring Data Analyst | Python • Tableau • SQL  
🔗 [LinkedIn](https://www.linkedin.com/in/sahil-lodhi/)  
🔗 [GitHub](https://github.com/Sahillodhi29)