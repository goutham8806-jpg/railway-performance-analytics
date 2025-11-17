🚆 Railway Operations Analytics

Comprehensive Delay & Performance Insights using Python, Pandas, Matplotlib & Power BI

This project analyzes Indian Railway operational performance, focusing on train delays, route efficiency, station bottlenecks, monthly trends, and train-wise rankings.
It includes Python analysis + Power BI dashboard for end-to-end operational insights.

📂 Project Structure
railway-performance-analytics/
│── data/
│   └── railway_data_2024.csv
│── scripts/
│   ├── delay_heatmap.ipynb
│   ├── monthly_delay.ipynb
│   ├── route_delay_bar.ipynb
│   └── train_ranking.ipynb
│── outputs/
│   ├── delay_heatmap.png
│   ├── monthly_delay.png
│   ├── route_delay_bar.png
│   └── train_ranking.png
│── powerbi/
│   └── railway_dashboard.pbix
└── README.md

🧠 Project Overview

This project delivers insights on:

Train delays

Route efficiency

Monthly performance

Station & destination delays

Train-wise ranking

Peak delay periods

Dataset includes: train number, route, station names, arrival/departure time, and delay values.

🔧 Technologies Used
🐍 Python

Pandas

NumPy

Matplotlib

Seaborn

📊 Power BI

DAX Measures

Multi-page dashboard

Interactive slicers & filters

📈 Key Insights

✔ Route-wise Delay Analysis — identifies worst-performing routes
✔ Train Ranking — evaluates trains by average delay
✔ Monthly Delay Trends — helps identify seasonal patterns
✔ Heatmaps — station vs destination bottlenecks

🖼 Python Visual Outputs
Output	Description
delay_heatmap.png	Station vs Destination delay heatmap
monthly_delay.png	Month-wise average delay
route_delay_bar.png	Route-level delay distribution
train_ranking.png	Train-level delay ranking
📊 Power BI Dashboard

Includes:

KPI Cards (Total Delay, Avg Delay, Worst Route)

Route & Train Filters

Monthly Trend

Route Delay Bar Chart

Train Ranking Table

File: powerbi/railway_dashboard.pbix

💻 How to Run

Install dependencies:

pip install pandas matplotlib seaborn


Run any analysis notebook:

python scripts/delay_heatmap.ipynb
python scripts/monthly_delay.ipynb
python scripts/route_delay_bar.ipynb
python scripts/train_ranking.ipynb

🎯 Conclusion

This project demonstrates:

Real-world data cleaning

Exploratory data analysis

Python visualization

Dashboarding with Power BI

Complete end-to-end analytics workflow
