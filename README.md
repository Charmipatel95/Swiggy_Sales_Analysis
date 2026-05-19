🍕 Swiggy Sales Analysis — Python Data Analysis Project
A complete end-to-end data analysis project built using Python, Pandas, NumPy, and Matplotlib on real Swiggy food order data — covering data cleaning, KPI calculation, chart design, and business insights.
---
📌 Problem Statement
Food delivery platforms generate thousands of orders daily. The challenge is converting raw transactional data into clear business insights — understanding which states, cities, restaurants, and dishes are driving revenue, how customer behavior changes across time, and where the biggest opportunities lie.
This project analyzes 1,97,403 Swiggy orders across 8 months (January–August 2025) and 28 Indian states to answer these questions using Python.
---
📊 Dataset Overview
Field	Detail
Source	Swiggy sales data (Excel)
Time Period	January 2025 – August 2025
Total Records	1,97,403 orders
States Covered	28
Key Columns	Order Date, Dish Name, Restaurant Name, City, State, Price (INR), Rating, Rating Count
---
🔢 Key Performance Indicators (KPIs)
Metric	Value
💰 Total Sales	₹5.30 Crore
📦 Total Orders	1,97,403
🧾 Average Order Value	₹268.50
⭐ Average Rating	4.3 / 5
📝 Total Rating Count	55,91,171
---
📈 Charts Produced (11 Total)
#	Chart	Type
1	Monthly Sales Trend	Line
2	Daily Revenue Trend	Bar
3	Veg vs Non-Veg Revenue Share	Pie
4	Veg vs Non-Veg Order Count	Bar
5	Revenue by State	Horizontal Bar
6	Top 5 Cities by Sales	Horizontal Bar
7	Top 10 Restaurants by Revenue	Horizontal Bar
8	Top 10 Most Ordered Dishes	Horizontal Bar
9	Top 10 Dishes by Revenue	Horizontal Bar
10	Quarterly Performance Summary	Table
11	Weekly Revenue Trend	Line
---
💡 Key Findings & Insights
1. Karnataka Dominated All States — By a Wide Margin
Karnataka generated ₹54.6L in revenue — 75% more than Uttar Pradesh (₹31.2L), the second-highest state. The reason: Karnataka means Bengaluru, and Bengaluru is India's tech capital with the highest concentration of working professionals who rely on food delivery daily.
2. Bengaluru is the Single Biggest Revenue Driver
Bengaluru alone contributed ₹54.6L, matching Karnataka's entire state total. The top 5 cities (Bengaluru, Lucknow, Hyderabad, Mumbai, New Delhi) are all large metros — confirming food delivery demand is concentrated where working populations are densest.
3. All Top 5 Restaurants Are Fast-Food Chains
KFC (₹42.5L), McDonald's (₹33.4L), Pizza Hut (₹21.3L), Burger King (₹19L), and Domino's (₹18.3L) together account for 25.4% of total revenue. Every one is a fast-food brand — reflecting the working-professional customer base who want quick, reliable, affordable meals.
4. Non-Veg Customers Spend ₹101 More Per Order Than Veg
Veg dominates in volume — 70.7% of orders and 62.9% of revenue. But Non-Veg customers spend an average of ₹340 per order vs ₹239 for Veg. Non-Veg is the high-value, lower-frequency segment worth targeting with premium promotions.
5. Most Popular Dish ≠ Most Profitable Dish
Choco Lava Cake leads in orders (303) but does not appear in the top 10 revenue list. The highest revenue dish is Bold BBQ Veggie Thin n Crispy at ₹99,617. Premium combo meals generate far more revenue than cheap, popular add-ons. Volume does not equal profitability.
6. Revenue is Remarkably Stable Month-Over-Month
Monthly revenue stays tightly between ₹62.7L (February) and ₹68.2L (January) across 8 months — no crashes, no dramatic spikes. This signals a loyal, habitual customer base ordering regularly rather than seasonally.
7. Saturday Peaks, Tuesday Dips — But the Gap is Small
Saturday is the highest revenue day (₹77.8L) and Tuesday the lowest (₹73.6L) — a difference of only ₹4.2L. Strong demand exists every day of the week. Tuesday flash deals could easily close this gap.
8. Q3 Is On Track to Match Q1 and Q2
Q1 (₹1.97Cr) and Q2 (₹1.99Cr) are essentially flat. Q3 shows ₹1.34Cr but covers only July–August. Projected to full quarter: ₹2.01Cr — matching Q1 and Q2 perfectly. Average rating holds at 4.34 across all three quarters.
---
🛠️ Tech Stack
Tool	Purpose
Python 3	Core language
Pandas	Data loading, cleaning, grouping, aggregation
NumPy	Numerical operations, food category labeling
Matplotlib	All 11 charts and visualisations
Google Colab	Development and execution environment
Microsoft Excel (.xlsx)	Raw data source
---
📂 Project Structure
```
swiggy-sales-analysis/
│
├── SWIGGY\_SALES\_ANALYSIS.ipynb   ← Main Colab notebook
├── swiggy\_data.xlsx              ← Raw dataset
├── Swiggy\_PPT.pptx               ← Presentation deck
└── README.md                     ← This file
```
---
🚀 How to Run
Open Google Colab
Upload `SWIGGY\_SALES\_ANALYSIS.ipynb`
Upload `swiggy\_data.xlsx` using the folder icon on the left sidebar
Click Runtime → Run All
---
🧠 Skills Demonstrated
Data cleaning (duplicate removal, type conversion, keyword-based categorisation)
Feature engineering (YearMonth, DayName, Quarter, Week columns)
Grouped aggregations with Pandas
KPI calculation and business interpretation
Data visualisation with Matplotlib
Translating chart outputs into actionable business insights
---
👩‍💻 About
Charmi | Aspiring Data Analyst  
Python · SQL · Excel · Power BI · Data Visualisation
Built as part of a data analytics portfolio to demonstrate real-world analysis skills.
