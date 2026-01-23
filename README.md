# 🏏 IPL Data Analysis (2008–2024)

## 📊 End-to-End Exploratory Data Analysis on Indian Premier League Cricket Data

---

## ⭐ Overview

This project presents an **in-depth Exploratory Data Analysis (EDA)** of **Indian Premier League (IPL) matches from 2008 to 2024**, focusing on match outcomes, team dominance, player performance, toss impact, & scoring patterns.

The goal is to **extract actionable insights** from historical IPL data that can support **sports analytics, strategy formulation, and predictive modeling**.

---

## 🎯 Objectives

- Analyze IPL match data spanning **17+ seasons (2008–2024)**
- Identify **top-performing teams and players**
- Understand **key factors influencing match outcomes**
- Build a strong **analytical foundation** for future ML-based sports models

---

## 📁 Dataset Description

- **Total Rows:** 1095  
- **Total Columns:** 20  
- **Time Period:** 2008 – 2024  

### Key Columns
- `id` – Match ID  
- `season` – IPL season year  
- `city` – Match city  
- `date` – Match date  
- `match_type` – League / T20  
- `team1`, `team2` – Competing teams  
- `toss_winner`, `toss_decision` – Toss details  
- `winner` – Match winner  
- `result`, `result_margin` – Match outcome  
- `target_runs`, `target_overs` – Chasing details  
- `player_of_match` – Best performer  
- `super_over`, `method` – Match conditions  

---

## 🧹 Data Cleaning & Preprocessing

- Removed **all missing values**
- Verified **zero duplicate records**
- Standardized team names and formats
- Ensured consistency across all seasons

---

## 📈 Exploratory Data Analysis

### 🔹 Univariate Analysis

- **Mumbai Indians** lead IPL history with **150+ wins**
- **Chennai Super Kings** closely follow
- **Rising Pune Supergiants** have the lowest wins
- Most target scores fall in the **160–165 runs** range

---

### 🔹 Summary Statistics

| Metric | Max | Average | Min |
|------|-----|---------|-----|
| Result Margin (Runs) | 146 | 17 | 1 |
| Target Runs | 288 | 165 | 50 |
| Target Overs | 20 | 19.75 | 5 |

- **2013** recorded the **highest number of matches (76)**
- **2009** had the **fewest matches (57)**

---

### 🔹 Bivariate Analysis

- **Sunrisers Hyderabad (SRH)** recorded the highest winning run totals
- **Rising Pune Supergiants (RPS)** had the lowest
- Outliers were removed to improve analysis accuracy

---

### 🔹 Correlation Analysis

- `result_margin` ↔ `target_runs` → **0.39**
- `target_runs` ↔ `target_overs` → **0.35**
- Match ID has **no meaningful correlation**

---

### 🔹 Toss vs Match Outcome

- Toss-winning teams show **only a marginal advantage**
- Toss result is **not a decisive factor** in winning matches

---

## 🏆 Key Insights

- **Mumbai Indians** are the most successful IPL team
- **SRH** holds the highest IPL scores (287 & 277)
- **KKR** recorded the third-highest score (272)
- **AB de Villiers** leads with **30+ Player of the Match awards**
- Target scores stabilize around **160–165 runs**
- **RCB and CSK** consistently post high totals

---

## 💡 Business & Analytical Impact

- Enables **team strategy optimization**
- Supports **player performance evaluation**
- Acts as a base for:
  - Match outcome prediction
  - Toss impact modeling
  - Fantasy sports analytics
  - Sports intelligence dashboards

---

## 🛠️ Tech Stack

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**

---

## 🚀 Future Enhancements

- Build ML models for match outcome prediction
- Player performance forecasting
- Venue-based win probability analysis
- Interactive IPL analytics dashboard

---

## 👤 Author

**Syed Huzaifa**  
🎓 B.Tech – Artificial Intelligence & Data Science  
🏫 Aditya College of Engineering Madanapalle

🔗 GitHub: https://github.com/SyedHuzaifa12  
🔗 LinkedIn: https://www.linkedin.com/in/syed-huzaifa-b4b64a27b  

---

## 📜 License

This project is intended for **learning, research, & academic use**.
