# Instagram_User_Engagement_Analysis
Manisha Pasunuri | Data Analyst
EDA on Instagram user behavior to improve engagement quality and reduce churn risk

## 📌 Business Problem
Instagram leadership wanted to shift focus from raw time spent 
to meaningful engagement. This project analyses user behaviour 
to improve Engagement Quality Efficiency (EQE) and reduce 
churn risk across 1.5M users.

## 🔑 Key Metrics Designed
- Meaningful Engagement (ME): Weighted score of likes, 
  comments, DMs, posts (weights based on effort per action)
- Attention (A): Total time spent across Feed, Reels, 
  Explore and Messages
- EQE = ME / A: Engagement efficiency per unit of time spent

## 👥 User Segments Identified
- High EQE — Less time, more meaningful actions
- Low EQE — More time, passive scrolling behaviour
- High Dormancy Risk — Efficient but login less often
- Low Dormancy Risk — Frequent logins but passive usage

## 📊 Key Findings
1. Users with fewer sessions had significantly higher EQE — 
   quality of engagement matters more than frequency
2. High reels time consistently drove Low EQE — confirming 
   doom scrolling reduces meaningful engagement
3. Stress was the strongest lifestyle signal negatively 
   correlated with EQE (~0.4 correlation)

## 🛠️ Tools Used
Python | Pandas | NumPy | Matplotlib | Seaborn | Tableau

## 📊 Tableau Dashboard
https://public.tableau.com/app/profile/pasunuri.manisha/viz/NL_Instagram_17702194425180/EQEPerformanceOverview

## 📁 Dataset
Instagram usage lifestyle dataset — 1.5M users across 
demographics, platform behaviour and lifestyle metrics
