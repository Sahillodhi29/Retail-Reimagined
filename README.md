# 🛍️ Retail Reimagined – End-to-End Analytics on Customer Behavior & Store Experimentation

**Author:** Sahil Lodhi  
🔗 [LinkedIn](https://www.linkedin.com/in/sahil-lodhi/) • 🔗 [GitHub](https://github.com/Sahillodhi29)

---

## 📌 Project Overview

**Retail Reimagined** is a complete, two-phase analytics project simulating a real-world business scenario for a national retail chain's chips category.  
It combines **customer behavior analytics** with **experimental testing** to uncover actionable insights that influence pricing, promotion, and layout decisions.

---

### 🔍 Phases Breakdown

| Phase | Focus Area | Key Skills |
|-------|------------|------------|
| 🧠 Phase 1 | Customer & Transaction Behavior | EDA, feature engineering, customer segmentation, statistical testing |
| 🧪 Phase 2 | Experimentation & Uplift Testing | Trial vs control design, correlation analysis, T-tests, business insight reporting |

This project was inspired by the **Quantium Analytics Virtual Internship** (via Forage), and independently executed entirely using **Python**.

---

## 🧠 Phase 1 – Customer & Transaction Analysis

🎯 Objective: Understand who buys chips, what they prefer, and how spending behavior varies by demographic.

### 📊 Key Work:
- Cleaned and filtered chip transactions
- Engineered features like `PACK_SIZE` and standardized `BRAND`
- Segmented customers by `LIFESTAGE × PREMIUM_CUSTOMER`
- Identified top-spending segments
- Compared brand/pack size preferences using statistical testing

### 💡 Insights:
- Target **Mainstream Young Singles/Couples** — highest sales contribution
- Focus promotions on **brands they love** and preferred pack sizes (**150g–175g**)
- Avoid pricing promotions — this segment is **less price sensitive**

📁 Full Details → `Phase1_Customer_Insights/`

---

## 🧪 Phase 2 – Experimentation & Uplift Testing

🎯 Objective: Measure the sales impact of a store layout trial using matched control stores and statistical significance testing.

### 📊 Key Work:
- Identified 3 trial stores and matched control stores using correlation and sales magnitude
- Visualized pre-trial similarity to validate control-store matching
- Analyzed Feb–Apr 2019 trial sales vs control sales
- Calculated **% uplift** and ran **Welch's T-Test** for significance

### 📈 Results Summary:

| Trial Store | Control Store | Uplift % | P-Value   | Statistically Significant? |
|-------------|----------------|----------|-----------|-----------------------------|
| 77          | 195            | +40.28%  | 0.02680   | ✅ Yes                      |
| 86          | 259            | -8.75%   | 0.29365   | ❌ No                       |
| 88          | 36             | +49.66%  | 0.00049   | ✅ Yes                      |

### 💡 Insights:
- Stores **77 and 88**: Statistically significant uplift — rollout recommended ✅  
- Store **86**: Slight dip but not significant — not a concern ⚠️  
- The trial design and evaluation method is validated and ready to scale 🔄

📁 Full Details → `Phase2_Experimentation_Testing/`

---

## 🛠️ Tools & Technologies Used

- **Python (Jupyter Notebooks)**
- **Pandas & NumPy** – Data manipulation and aggregation
- **Matplotlib & Seaborn** – Visualizations and trend analysis
- **SciPy** – Statistical significance testing (T-Tests)
- **Excel / CSV** – Source transaction and customer files

---

## 🧠 What I Learned

- Translating professional-grade analytics workflows from R to Python
- Structuring complex retail analytics into digestible phases
- Framing insights in business language (not just technical results)
- Using data to drive **strategic decisions** in marketing, pricing, and rollout

---

## ✅ Status

✅ Project Complete  
🎯 Ready for presentation, interview discussion, or deployment  
📂 Clean folder structure for recruiters, hiring managers, and mentors

---

## 📬 Contact

**Sahil Lodhi**  
Aspiring Data Analyst | Python • Tableau • SQL  
🔗 [LinkedIn](https://www.linkedin.com/in/sahil-lodhi/)  
🔗 [GitHub](https://github.com/Sahillodhi29)



