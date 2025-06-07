# 🧠 Customer & Transaction Analysis – Retail Chips Insights

## 📌 Overview

This project is the **first phase of a broader business analytics initiative** aimed at improving chip sales performance across a national retail chain.

In this phase, we performed a complete end-to-end customer and product behavior analysis using **Python**, with a goal to:
- Understand customer segments
- Discover brand and pack-size preferences
- Identify price sensitivity and spending behavior

This standalone analysis provides critical **foundational insights** to inform marketing strategy, product packaging, and stock decisions. The next phase (to be executed later) will involve **experimentation through trial vs control store comparisons** to evaluate the impact of specific business interventions.

---

## 🛠️ Tools & Technologies

- **Python 3.x**
- **Pandas** – Data manipulation
- **NumPy** – Numeric operations
- **Matplotlib / Seaborn** – Data visualizations
- **SciPy** – Statistical testing (T-Test)
- **Jupyter Notebook** – Code documentation and analysis presentation

---

## 📂 Data Used

- `QVI_transaction_data.csv`: Contains individual transaction details such as date, product, sales, and customer ID.
- `QVI_purchase_behaviour.csv`: Contains customer demographic segments such as `LIFESTAGE` and `PREMIUM_CUSTOMER`.

---

## 📊 Key Analysis Steps

1. **Data Loading & Merging**
   - Loaded both transaction and customer data
   - Merged using loyalty card number

2. **Data Cleaning**
   - Converted date formats
   - Filtered only chip-related products
   - Removed outliers (e.g., 200+ items in one transaction)

3. **Exploratory Data Analysis (EDA)**
   - Transaction trends over time
   - Missing data checks
   - Seasonality (e.g., December holiday spikes)

4. **Feature Engineering**
   - Extracted `PACK_SIZE` from product names
   - Extracted `BRAND` and standardized inconsistencies

5. **Customer Segmentation**
   - Analyzed total sales, number of customers, and average units by segment (`LIFESTAGE` × `PREMIUM_CUSTOMER`)
   - Identified top spending groups

6. **Statistical Testing**
   - Performed a **T-Test** to compare price sensitivity between segments
   - Identified statistically significant differences

7. **Deep Dive into High-Value Segments**
   - Brand affinity scores for top customer segment
   - Pack size preferences visualized and compared

---

## 💡 Business Insights & Recommendations

- 🎯 Focus on **Mainstream Young Singles/Couples** — they spend the most and show brand loyalty.
- 💸 These customers are **less price-sensitive** — price-based promotions may be less effective than exclusivity or bundling.
- 🏷️ Promote **high-affinity brands** through targeted campaigns.
- 📦 Keep stock of **150g–175g** packs — the preferred size range.
- 📊 Use this type of analysis regularly to adjust strategies and drive sales.

---

## 🧠 What I Learned

- Translating a professional R analysis into **Python with full context**
- Applying real-world EDA and feature extraction
- Conducting and interpreting **statistical tests** (like t-test)
- Framing **data insights as actionable business strategies**
- Laying groundwork for future **experimental testing** (Trial vs Control)

---

## 📁 Project Status

✅ Completed (Phase 1: Behavioral Insights)  
📈 Ready for next phase (Experimentation/Uplift Testing)  
📄 Ideal for use in portfolio, case studies, or interview discussion

---

## 📬 Contact

**Sahil Lodhi**  
Aspiring Data Analyst | Python • Tableau • SQL  
🔗 [LinkedIn](https://www.linkedin.com/in/sahil-lodhi/)  
🔗 [GitHub](https://github.com/Sahillodhi29)
