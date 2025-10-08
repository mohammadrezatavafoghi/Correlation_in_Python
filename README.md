# Movie Dataset Correlation Analysis

This project explores the relationships between different movie features using **Python, Pandas, NumPy, Matplotlib, and Seaborn**.  
The goal is to perform **Exploratory Data Analysis (EDA)** and uncover how budget, revenue, votes, runtime, and IMDb scores are connected.

---

## Dataset
- **Movies:** 7,668  
- **Features:** 15  
- **Missing values:**  
  - Budget → 2,171  
  - Gross → 189  
  - Rating → 77  
  - Company → 17  
  - Runtime → 4  

---

## Key Findings
- **Budget ↔ Gross:** +0.74  
- **Gross ↔ Votes:** +0.63  
- **Budget ↔ Votes:** +0.44  
- **Score ↔ Votes:** +0.41  
- **Score ↔ Runtime:** +0.40  

Bigger budgets usually lead to higher revenues, and popular movies (votes) often align with better scores and grosses.

---

## Project Structure

├─ data/
│ └─ movies.csv
├─ notebooks/
│ └─ movies.ipynb
├─ reports/
│ └─ corr_heatmap.png
└─ README.md


---

