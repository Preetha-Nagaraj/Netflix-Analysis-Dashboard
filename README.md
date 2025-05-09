
📌 **About Netflix**

Netflix is a leading global streaming platform that provides a vast collection of TV series, films, documentaries, and original programming across various genres and languages. Established in 1997 and based in Los Gatos, California, it reaches audiences in more than 190 countries. By leveraging data and analytics, Netflix has revolutionized entertainment consumption and personalized viewing experiences for millions of users.

## Problem Statement:

Analyze Netflix's content and customer viewing behavior to derive meaningful business insights. The goal is to clean and visualize the data to understand customer engagement, content popularity, and subscription trends.


## What?

This analysis focused on Netflix and its users data.

## Who?

This analysis is useful for:

- 📊 **Business Analysts & Data Analysts** – to identify trends and correlations in Netflix’s content library.
- 🧠 **Content Strategy Teams** – to decide what genres or types of content to invest in.
- 🌍 **Regional Managers** – to understand regional content distribution and audience preferences.
- 🧩 **Marketing & Product Teams** – to tailor promotions based on content type and audience sentiment.

## How?

The main insights from the dashboard include:

- 🎬 **TV Shows and Movies distribution** – Breakdown of how much content is of each type.
- 🌍 **Geographical spread** – A map showing the number of shows available by country.
- 📈 **Top Ratings & Average Ratings** – Understanding which content types and genres receive higher ratings.
- 📊 **Content Classification by Rating** – Identification of which maturity ratings dominate Netflix’s library (e.g., TV-MA, PG-13).
- 🏆 **Popular Genres** – Highlighting genres with the highest average ratings.

## Key Considerations
- This dataset contains information about Netflix users and their Age, Gender, Country, Subscription type, Watch time, User ratings.
- Also contains data about Show and its type, Ratings, User rating, Date released, Date added Director and Cast
- Each dataset contains 20000 rows
- Dataset contains last 5 years of data (2020-2025)

## Ask

This analysis answers the following questions:

- 📉 *“Is there any correlation between watch time and average user rating?”*
- 🎥 *“What are the top-rated genres on Netflix?”*
- 🗺️ *“Which countries have the highest content consumption?”*
- 🧐 *“Which subscription type is widely used?”*
- 🔍 *“Engagement level of users according to age-group and gender?”*
- 📅 *“How watch time and average ratings changes over time?” ( Trend Analysis )*

## Prepare

To answer these questions, I gathered two datasets: 

1. Netflix customer ratings
2. Netflix TV show/ Movies info

## Process

I used Excel to clean the data and transform it to my needs.

The main cleaning jobs were:

- Transforming data types
- Removing Duplicates
- Creating new columns to specify metrics
- Performed Customer retention analysis

### **Key Takeaways**

1. **Watch Time ≠ Satisfaction**: Heavy usage doesn’t always translate to higher customer satisfaction. Users may continue watching out of habit or lack of alternatives rather than genuine enjoyment.
2. **Content Quality Matters More**: High engagement (watch time) alone isn’t a strong indicator of satisfaction. Ratings are likely influenced more by content relevance, genre preference, or storytelling quality.
3. **Focus on Feedback and Personalisation**: To improve satisfaction and retention, Netflix should **prioritise personalised recommendations and quality content**, not just increase user watch time.

I conducted this analysis in Power BI.

### 1. Overall Filters

- Show added year
- Titles
- Watch Time
- Total Customers
- Type (TV show/ movie)
- Total Customers
- Average Rating

### 2. WatchTime By Age and Gender
Dax used
TotalWatchTime_Hours = SUM('Netflix'[watch_time_minutes]) / 60

### 3. Country-wise Genre Preferences
### 4. Subscription type Vs Watch time
### 5. New Releases by Month & Year
### 6. Customer Retention Insights


# Conclusion

From the above dashboard, we can get a clear picture of Netflix’s global content performance, user engagement, subscription patterns and additional insights.
