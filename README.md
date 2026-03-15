# Restaurant Tips Visualization

## Project Overview
This project explores customer tipping behavior at a restaurant chain using Python’s **Matplotlib** and **Seaborn** libraries. The analysis focuses on visualizing total tips collected by day, the distribution of tip amounts, and the relationship between total bill and tip amounts.

The dataset used is the built-in **Tips** dataset from Seaborn, which contains customer bills, tips, day of the week, party size, and other relevant details.

---

## Dataset
- **Source:** Seaborn built-in dataset (`sns.load_dataset('tips')`)  
- **Key columns used:**
  - `total_bill` — Total bill amount ($)
  - `tip` — Tip amount ($)
  - `day` — Day of the week
  - `size` — Number of people in the party

---

## Tasks & Visualizations

### Task 1 — Total Tip Amount by Day
- **Visualization:** Bar chart using Matplotlib  
- **Purpose:** Shows total tips collected per day of the week.  
- **Insight:** Saturdays collect the highest tips, while weekdays have lower totals.

### Task 2 — Tip Distribution
- **Visualization:** Histogram with KDE using Seaborn  
- **Purpose:** Shows how tip amounts are distributed across customers.  
- **Insight:** Most tips fall between $2–$4; distribution is right-skewed. The KDE curve highlights the overall trend.

### Task 3 — Total Bill vs Tip
- **Visualization:** Scatter plot with hue by day using Seaborn  
- **Purpose:** Explores the relationship between total bill and tip amount.  
- **Insight:** Higher bills generally lead to higher tips. Saturday shows more high-value bills and tips.

---

## Libraries Used
- Python 3.x  
- [Matplotlib](https://matplotlib.org/) — for bar charts and basic plotting  
- [Seaborn](https://seaborn.pydata.org/) — for histograms, KDE, and scatter plots  
- Pandas (via Seaborn) — for data manipulation

---

