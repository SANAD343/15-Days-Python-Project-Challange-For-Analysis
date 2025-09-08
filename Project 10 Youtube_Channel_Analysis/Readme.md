# 🐍 Python Data Analyst Project – YouTube Channels Analysis 10/15 📺🎬

YouTube isn’t just entertainment — it’s data. Behind every video upload, subscriber count, and view lies a story waiting to be uncovered. So, I decided to explore a dataset of the Top 5000 YouTube Channels from Kaggle to understand what really drives channel growth.

📂 The Dataset
This dataset covers rank, subscribers, uploads, and views of 5000 channels. Using Python (Pandas, NumPy, Seaborn, Matplotlib), I cleaned, transformed, and analyzed the data to uncover patterns.

🔍 My Journey Through the Data

* 🎬 Loading & Overview → Imported data with Pandas and checked the shape, structure, and memory footprint.
* 🎬 Data Insights → Used .info() to identify column types and potential issues.
* 🎬 Statistics → With .describe(), I summarized numeric columns (views, uploads, subscribers).
* 🎬 Data Cleaning → Replaced placeholders (‘--’) with NaN, fixed missing values, converted ranks/uploads/subscribers into clean numeric columns.
* 🎬 Feature Engineering → Transformed raw text fields into meaningful numeric data to make comparisons possible.

🎬 Exploratory Data Analysis (EDA) →
* ✅ Found top channels by subscribers & views
* ✅ Checked which channels upload the most videos
* ✅ Created a correlation matrix to see how uploads, views, and subscribers interact
* ✅ Visualized key patterns using Seaborn & Matplotlib

💡 Key Takeaways

Some channels gain millions of subscribers with fewer uploads (quality-driven growth).

Others rely on consistent, high-volume uploads to reach audiences.

Strong correlation exists between views & subscribers, but uploads alone don’t guarantee success.

🎯 Big Picture
YouTube success is more than just content quantity — it’s about strategic consistency, niche focus, and building loyal subscribers. The data shows us that numbers tell the story, but strategy writes it.

👉 If you had a YouTube channel, would you focus on quality uploads or high-volume consistency?

