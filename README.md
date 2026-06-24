# 🛒 Olist E-Commerce — Sales & Customer Behaviour Analysis

An end-to-end exploratory data analysis of the Brazilian Olist e-commerce dataset — covering 100,000+ orders across 20 product categories, 15 Brazilian states, and 2 years of trading data. The analysis culminates in an **RFM customer segmentation** model identifying five distinct customer value tiers.

---

## 📊 Key Questions Explored

- How did Olist's revenue grow between 2016 and 2018?
- Which product categories drive the most revenue and order volume?
- Does delivery speed affect customer review scores — and by how much?
- Which states generate the most sales?
- How can we segment customers into actionable value tiers using RFM analysis?

---

## 📁 Project Structure

```
olist-ecommerce-analysis/
│
├── olist_ecommerce_analysis.ipynb  # Main analysis notebook
├── monthly_revenue.png             # Revenue trend with peak annotation
├── top_categories.png              # Top 10 categories by revenue & volume
├── review_by_category.png          # Avg review score per category
├── delivery_vs_review.png          # Delivery time vs customer satisfaction
├── revenue_by_state.png            # Revenue breakdown by Brazilian state
├── rfm_segments.png                # RFM segment bar charts
├── rfm_scatter.png                 # Recency vs spend scatter by segment
└── README.md
```

---

## 🛠️ Tools & Libraries

| Tool | Purpose |
|---|---|
| `pandas` | Data generation, groupby aggregations, RFM calculations |
| `NumPy` | Simulating realistic order distributions |
| `Matplotlib` | Revenue trends, bar charts, delivery analysis |
| `seaborn` | Styled plots and colour palettes |
| `Jupyter Notebook` | Interactive analysis environment |

---

## 📦 Dataset

- **Original source:** [Olist Brazilian E-Commerce — Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
- **Licence:** CC BY-NC-SA 4.0
- **Coverage:** 100,000+ orders, Sep 2016 – Aug 2018, 9 relational tables
- **Note:** This notebook uses a statistically representative simulation of the Olist dataset that mirrors the original's structure, distributions, and category relationships — making it fully self-contained with no downloads required.

---

## 🚀 How to Run

```bash
# 1. Clone this repository
git clone https://github.com/YOUR_USERNAME/olist-ecommerce-analysis.git
cd olist-ecommerce-analysis

# 2. Install dependencies
pip install pandas numpy matplotlib seaborn jupyter

# 3. Launch Jupyter
jupyter notebook olist_ecommerce_analysis.ipynb
```

> No internet connection required — the dataset is generated inside the notebook.

---

## 📌 Key Findings

- **Revenue grew consistently** from Sep 2016 to Aug 2018, with a clear spike in Nov–Dec (Black Friday / holiday season).
- **`bed_bath_table`** and **`health_beauty`** are the top categories by both revenue and order volume.
- **Delivery speed is the strongest driver of customer satisfaction** — orders delivered within 7 days average a 4.5+ review score; orders taking 30+ days drop below 3.2.
- **São Paulo (SP)** accounts for ~42% of all orders — logistics infrastructure is heavily concentrated there.
- **RFM segmentation** revealed that most customers are one-time buyers, highlighting a major opportunity for retention campaigns targeting the `At Risk` and `Potential Loyalists` segments.
- **Champions** (high-spend, recent, repeat buyers) should be rewarded with loyalty programmes and early access deals.

---

## 💡 Business Recommendations

| Segment | Recommended Action |
|---|---|
| Champions | Loyalty rewards, early product access |
| Loyal Customers | Upsell higher-value categories |
| Potential Loyalists | Personalised follow-up emails |
| At Risk | Win-back campaigns with discount codes |
| Lost | Broad re-engagement or sunset |

---

## 👤 Author

**Opeyemi Ogunbona** — Junior Data Scientist  
[LinkedIn](https://www.linkedin.com/in/opeyemi-ogunbona-29a45a231/) · [GitHub](https://github.com/Damilola308)

