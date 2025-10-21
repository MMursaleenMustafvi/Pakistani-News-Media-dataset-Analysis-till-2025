# Pakistani-News-Media-dataset-Analysis-till-2025
Analyzed Pakistan’s media dataset to explore bias, sentiment, revenue influence, and journalist coverage. Performed data cleaning, EDA, and visualizations to uncover how advertising and politics may shape news reporting. A data-driven case study on media accountability.
📊 Media Bias & Accountability Analysis – Pakistan News Dataset
📌 Overview

This project investigates how media narratives are shaped in Pakistan by analyzing a synthetic dataset of news channels, newspapers, journalists, advertising revenues, sentiment, and airtime distribution. The goal is to detect bias, editorial influence, and potential data manipulation in news reporting.

This dataset was created as part of a case study by the Media Accountability Network (MAN) — a non-profit dedicated to promoting transparency in journalism.

🗂️ Dataset Description
Column	Description
ID	Unique identifier for each news record
Journalist	Name of the reporter or anchor
Channel / Newspaper	Media outlet publishing/broadcasting the story
Region / City	Geographic origin of the news report
Topic	Category of the story (Politics, Sports, Crime, Health, etc.)
Headline	Title or summary of the news story
Ratings (TRP)	Viewership/popularity score
Revenue / AdSpend	Earnings & advertisement spending (may include units like PKR, lakh, crore)
Airtime	Time dedicated to the news story
SentimentScore	Sentiment value (-negative to +positive)
BiasScore	Bias level (0 = neutral to 10 = highly biased)
Viewership / Shares	Audience engagement metrics
ControversyFlag / MissingDataFlag	Indicates controversial or missing data
Date	Publication date
Language	English/Urdu
PoliticalAffiliation	Political alignment (Pro-Govt, Opposition, Neutral)
🎯 Project Objective

✔ Clean and preprocess inconsistent media data
✔ Standardize names, units (PKR/lakh/crore), missing values, and outliers
✔ Analyze whether financial revenue influences bias or sentiment
✔ Explore if pro-government channels receive more ad spend
✔ Check if journalists are shifted from their usual beats
✔ Study underreporting of sensitive topics like corruption vs entertainment
✔ Provide visual and statistical evidence with ethical reflections

🔍 Key Insights

Some channels with pro-government alignment show higher ad revenue, especially during political events.

Journalists often cover topics outside their expertise, indicating possible editorial influence.

Topics like corruption and political scandals receive less airtime compared to entertainment or sports.

Several inconsistencies found: invalid ratings (>100), mixed revenue formats, missing or inconsistent flags.

🚀 Technologies Used

Python (Pandas, NumPy, Matplotlib, Seaborn)

Jupyter Notebook for EDA & Visualizations

Data preprocessing, normalization, outlier detection, encoding
