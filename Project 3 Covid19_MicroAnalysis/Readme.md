# 🐍 Python Data Analyst Project – 3/15
# 🎯 Covid-19 Micro Analysis

After analyzing ecommerce behavior and student performance in my first two projects, I wanted to dive into something that impacted all of us globally — Covid-19 data. 🌍

For this project, I worked with a Kaggle dataset (~19K rows) containing information up to April 29, 2020. My goal was to conduct a micro-level analysis using Pandas and visualization techniques to uncover regional and country-specific insights.

Here’s what I found:

* 📂 Data Exploration – The dataset included Date, State, Region, Confirmed, Deaths, and Recovered cases.
* ⚠️ Null Values – Found 181 missing values in the State column, visualized via a heatmap
* 🌍 Regional Trends – Identified which regions had the highest and lowest confirmed cases and fatalities.
* 🧹 Data Filtering – Removed entries with fewer than 10 confirmed cases to focus on significant impact zones.
* 📊 Aggregation – Leveraged groupby() to compute total confirmed, recovered, and death counts across regions.
* 🇮🇳 India-Specific Insight – Extracted all reported figures for India till April 29, 2020, for a focused perspective.
* 📑 Sorting & Ranking – Ranked regions by confirmed and recovered cases to highlight both the most and least affected areas.

📌 Key Takeaway:

This project shows how data cleaning, aggregation, and visualization can turn raw Covid-19 records into meaningful insights — the kind that help policymakers, researchers, and the public understand the spread and impact of the pandemic.

🔥 That’s 3 projects down, 12 more to go! Each dataset feels like uncovering a new story hidden in numbers.

