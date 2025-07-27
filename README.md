# UM-Task--2-Netflix-Data-Analysis-
Netflix Data_ Cleaning, Analysis and Visualization_ _ ML _ FA _ DA projects


# 📺 Netflix Data Analysis Project
This project explores and analyzes a Netflix dataset using Python in a Jupyter Notebook environment. It involves data cleaning, transformation, visualization, and deriving insights about content on the streaming platform.

# 📁 Dataset
The dataset used is netflix1.csv, which includes metadata of Netflix content such as:

* Title

* Type (Movie/TV Show)

* Director

* Cast

* Country

* Date added

* Release year

* Duration

* Genres (listed_in)

* Description

# 🧹 Data Cleaning
Key preprocessing steps:

* Removed missing and duplicate values

* Converted date_added to datetime format

* Converted release_year to numeric

* Created new columns:

* genre_count: number of genres listed

* primary_genre: the first listed genre

# 📈 Exploratory Data Analysis (EDA)
The analysis includes:

* Distribution of content types (Movies vs TV Shows)

* Trend of content added over the years

* Most common genres

* Country-wise content production

* WordCloud of popular titles and descriptions

# 📊 Visualizations
Utilized Matplotlib, Seaborn, and WordCloud to create:

* Bar plots - Rating Distribution
    What it shows: The number of titles available for each rating category (like TV-MA, PG, R, etc.).

Insight: TV-MA (Mature Audience) and TV-14 are the most common ratings, indicating Netflix content targets a mature audience more than children.


* Count plots  – Rating Categories
    What it shows: Frequency of each rating using bars.

Insight: Confirms that Netflix has a large volume of adult and teen-friendly content, and relatively fewer shows targeted at children.


* Pie charts – Rating Share
   What it shows: Proportion of total content each rating represents.

Insight: TV-MA alone takes up the largest slice, further proving the adult-oriented content focus.


* Bar Plot – Top 10 Countries
   What it shows: Top countries producing content available on Netflix.

Insight: The United States dominates with the highest number of titles, followed by India, indicating both global and regional focus.


* Stacked Bar Chart – Monthly Releases
   What it shows: How many Movies vs TV Shows were added in each month.

Insight: More content is added in July, October, and December, possibly aligning with user demand and global release schedules.


* Line graphs - Yearly Releases
   What it shows: Trends in how many titles (Movies and TV Shows) were added each year.

Insight: There’s a steep rise from 2015 to 2019, showing Netflix’s aggressive expansion phase. A decline in 2020-2021 may relate to COVID-19’s impact on production.



* Word clouds for description analysis – Title & Description Analysis
   What it shows: Frequently used words in titles and descriptions.

Insight: Words like love, life, family, murder, and friendship frequently appear, suggesting strong thematic trends in Netflix content.


# 🔍 Key Insights
* Netflix has a higher number of Movies than TV Shows.

* Most content is added in recent years, especially post-2015.

* The U.S. leads in content production followed by India.

* "Dramas", "Comedies", and "Action" are the most common genres.

* Word clouds revealed frequent use of keywords like "love", "life", and "family".

# 🛠️ Technologies Used
* Python (Pandas, Matplotlib, Seaborn, WordCloud)

* Google Colab

# ✅ Project Outcome
* The project provides a solid understanding of Netflix's content distribution over time, across countries and genres. It also offers a base for building recommendation systems or deeper content analytics.


# 🧠 Decisions & Recommendations

## 🎯 1. Content Strategy: Focus on Popular Genres and Ratings
Since TV-MA and TV-14 ratings dominate, Netflix should continue producing or acquiring mature content.

Genres like Dramas, Comedies, and Action are the most frequent — focus on expanding these categories with fresh themes to retain viewer interest.

## 🌍 2. Country-Specific Expansion
The United States leads in content availability, followed by India and other countries.

Recommendation: Expand content partnerships in emerging markets like India, South Korea, and Japan, where there's high growth potential and cultural export value.

## 🗓️ 3. Optimize Release Schedule
Peaks in content release occur in July, October, and December — possibly aligning with holidays and festive seasons.

Recommendation: Continue aligning marketing and release plans with seasonal demand, and use data to fine-tune high-impact launch months.

## 📉 4. Content Decline During Pandemic
A noticeable drop in content release during 2020–2021, likely due to COVID-19.

Recommendation: Re-evaluate post-pandemic content production and acquisition pipelines to recover volume and maintain user engagement.

## 🔍 5. Content Discovery Optimization
Word clouds reveal recurring themes like “love”, “life”, “family”, “murder”, and “friendship.”

Recommendation: Use these keywords to improve metadata, SEO, and personalized recommendations for users searching within the platform.

## 📺 6. Balance Between TV Shows and Movies
Movies dominate Netflix’s library.

## Recommendation: Consider investing more in TV shows to increase subscriber retention, as episodic content generally encourages longer engagement.


