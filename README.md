# Customer Trends Analysis

Analyzed a retail customer dataset to understand shopping patterns — things like which segments spend the most, how seasons affect buying behavior, and whether promo codes actually move the needle. The work spans SQL, Python (EDA + viz), and a Power BI dashboard, with a final report and slides for presentation.

---

## Repo Contents

```
Customer-Trends-Analysis/
│
├── customer_shopping_behavior.csv             # Raw dataset
├── Customer_Shopping_Behavior_Analysis.ipynb  # Main analysis notebook
├── customer_behavior_sql_queries.sql          # SQL queries used for exploration
├── customer_behavior_dashboard.pbix           # Power BI dashboard
├── Customer Shopping Behavior Analysis.pdf    # Full analysis report
├── Customer-Shopping-Behavior-Analysis.pptx  # Presentation slides
└── Business Problem Document.pdf             # Project background and objectives
```

---

## Analysis Coverage

Started with basic demographic breakdowns (age, gender, location) then moved into category-level trends, seasonal fluctuations, and promo/discount impact. Also looked at how subscribed customers behave differently from non-subscribed ones in terms of frequency and average spend.

---

## Stack

- Python (Pandas, NumPy, Matplotlib, Seaborn) for cleaning and exploratory analysis
- SQL for slicing and aggregating the data
- Power BI for the interactive dashboard
- Jupyter Notebook as the main working environment

---

## Running Locally

Requires Python 3.8+, Jupyter, and Power BI Desktop for the dashboard.

```bash
git clone https://github.com/Harshv0708/Customer-Trends-Analysis.git
cd Customer-Trends-Analysis
pip install pandas numpy matplotlib seaborn jupyter
jupyter notebook Customer_Shopping_Behavior_Analysis.ipynb
```

Open `customer_behavior_dashboard.pbix` directly in Power BI Desktop.

---

## Dataset

File: `customer_shopping_behavior.csv`

Each row represents a customer transaction and includes age, gender, location, item purchased, category, purchase amount, season, payment method, discount/promo applied, review rating, subscription status, and purchase frequency.

---

## What Came Out of It

A handful of age groups and categories account for a big portion of revenue. Seasonal dips and spikes are pretty consistent. Promo codes do influence behavior but not evenly across all segments — some groups respond strongly, others not so much. Subscribed customers are notably more consistent buyers compared to irregular ones.

---

## Deliverables

- **Business Problem Document** — project scope and objectives
- **Analysis Report (PDF)** — full writeup with charts and takeaways
- **Presentation (PPTX)** — summary deck of the key findings
