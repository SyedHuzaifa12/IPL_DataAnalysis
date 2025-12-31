🏏 IPL Data Analysis (2008–2024)
📊 End-to-End Exploratory Data Analysis on Indian Premier League Cricket Data
⭐ Overview

This project presents an in-depth Exploratory Data Analysis (EDA) of Indian Premier League (IPL) matches from 2008 to 2024, focusing on match outcomes, team dominance, player performance, toss impact, and scoring patterns.

The goal is to extract actionable insights from historical IPL data that can support sports analytics, strategy formulation, and predictive modeling.

🎯 Objective

Analyze IPL match data spanning 17+ seasons (2008–2024)

Identify top-performing teams and players

Understand key factors influencing match outcomes

Provide a strong analytical foundation for future predictive and ML-based sports models

📁 Dataset Description

Total Rows: 1095

Total Columns: 20

Time Period: 2008 – 2024

Key Columns:

id – Unique match ID

season – IPL season year

city – Match city

date – Match date

match_type – League / T20

team1, team2 – Competing teams

toss_winner, toss_decision – Toss details

winner – Match winner

result, result_margin – Win type and margin

target_runs, target_overs – Chasing details

player_of_match – Best performer

super_over, method – Match conditions

umpires – Match officials

🧹 Data Cleaning

Removed all missing values

Verified no duplicate records

Ensured data consistency across seasons

Final dataset ready for robust analysis and visualization

📈 Exploratory Data Analysis
🔹 Univariate Analysis

Most Wins by Teams

Mumbai Indians lead IPL history with 150+ wins

Chennai Super Kings closely follow

Rising Pune Supergiants record the lowest wins (<20)

Target Runs Distribution

Most matches fall in the 160–165 runs target range

Indicates a competitive and balanced scoring benchmark

🔹 Summary Statistics
Metric	Max	Avg	Min
Result Margin (runs)	146	17	1
Target Runs	288	165	50
Target Overs	20	19.75	5

2013 had the maximum matches (76)

2009 had the fewest matches (57)

🔹 Bivariate Analysis

Runs Scored by Winning Teams

After removing outliers:

Sunrisers Hyderabad (SRH) scored the highest winning runs

Rising Pune Supergiants (RPS) recorded the lowest

Correlation Analysis

Moderate correlation:

result_margin ↔ target_runs → 0.39

target_runs ↔ target_overs → 0.35

Negligible correlation with id

🔹 Toss vs Match Outcome

Toss-winning teams have only a slight advantage

Toss outcome is not a decisive factor in match results

🏆 Key Insights

Mumbai Indians are the most successful IPL team historically

SRH holds the highest IPL scores (287 & 277)

KKR recorded the third-highest score (272)

AB de Villiers leads Man of the Match awards (30+)

Target scores mostly stabilize around 160–165 runs

RCB and CSK consistently post high target scores

💡 Business & Analytical Impact

Supports team strategy optimization

Enables player performance evaluation

Serves as a foundation for:

Win prediction models

Toss impact modeling

Fantasy sports analytics

Match outcome forecasting

🛠️ Tech Stack

Python

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook

🚀 Future Enhancements

Predict match outcomes using ML models

Player performance forecasting

Venue-based win probability analysis

Real-time IPL analytics dashboard

👤 Author

Syed Huzaifa
🎓 B.Tech (AI & Data Science), Aditya College of Engineering
💼 Data Science Intern @ InternX

🔗 LinkedIn: https://www.linkedin.com/in/syed-huzaifa-b4b64a27b

🔗 GitHub: https://github.com/SyedHuzaifa12

📜 License

This project is open for learning and academic use.
