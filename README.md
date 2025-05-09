# Project Title – Netflix Dashboard

## 📌 Overview

This interactive Tableau dashboard provides a comprehensive analysis of Netflix's global content library. It visualizes key insights such as total titles by country, top genres, content distribution (movies vs. TV shows), ratings breakdown, and yearly trends from 2008–2020. The dashboard helps users understand content availability, regional trends, genre preferences, and rating distributions, offering valuable insights for media analysts, content strategists, and data enthusiasts.

---

## 🔍 Problem Statement

With the rapid expansion of Netflix's content library across different countries, genres, and formats, it becomes increasingly difficult to track content distribution, genre popularity, and viewer accessibility. Stakeholders need a centralized, visual solution to analyze patterns in content availability, genre trends, and rating classifications across time and regions to make informed decisions about content strategy, localization, and user targeting.
---

## 📊 Tools & Technologies Used

- SQL
- Tableau
- Python (Pandas, NumPy, Matplotlib)
- Excel
- Git & GitHub

---

## 📁 Dataset

Used dataset from DataScience's site: represents a unique title and includes the following key features:
- Title – Name of the movie or TV show
- Type – Identifies if the content is a Movie or TV Show
- Genre – Describes content categories (e.g., Documentaries, Comedy)
- Description – Brief synopsis of the title
- Release Year – The year the title was originally released
- Date Added – When it was added to the Netflix platform
- Rating – Parental rating (e.g., TV-MA, PG-13)
- Duration – Runtime in minutes or number of seasons
- Country – Origin or availability country
- Additional Fields – Such as cast, director, or platform availability details.

---

## 🧠 Approach

1. Data Collection & Cleaning
- Source: Netflix Titles Dataset (publicly available CSV or Kaggle)
- Cleaned missing values (e.g., unknown ratings, empty genres)
- Standardized date formats and split multi-category fields (like genres)

2. Data Transformation
- Extracted year from date_added and release_year
- Created calculated fields for metrics like content type distribution, genre count, and country-wise totals
- Categorized ratings and grouped similar genres

3. Data Visualization in Tableau
- Built interactive filters (Type, Title, Year)
- Visualized:
    - Country-wise content distribution (Map)
    - Genre popularity (Bar chart)
    - Ratings breakdown (Bar chart)
    - Year-wise growth (Area chart)
    - Movies vs. TV Shows (Donut chart)


---

## 📈 Key Features

1. Interactive Filters
- Filter by Type, Title, and Release Year for tailored insights.

2. Global Content Distribution Map
- Visualizes total titles available by country with heat intensity.

3. Top 10 Genres Bar Chart
- Highlights the most popular content categories on Netflix.

4. Content Type Distribution
- Donut chart showing the ratio of Movies vs. TV Shows.

5. Ratings Breakdown
- Bar graph displaying content count by maturity rating (e.g., TV-MA, PG-13).

6. Yearly Trend Analysis
- Area chart tracking the growth of movies and TV shows from 2008 to 2020.

7. Title-Specific Details
- Shows rating, duration, genre, and description for selected titles.

8. Dark Theme UI
- Visually engaging layout optimized for clarity and emphasis.


---

## ✅ Results

1. Movies Dominate the Platform

- Movies account for ~68% of the total content, while TV shows make up ~32%.

2. United States Leads in Content Volume

- The U.S. has the highest number of available titles, significantly ahead of other countries.

3. Top Genres Identified

- Documentaries, Stand-Up Comedy, and Dramas are the most prevalent genres.

4. Ratings Distribution

- TV-MA is the most common rating, indicating a high volume of mature content.

5. Content Growth Over Time

- Steady increase in total titles from 2015 to a peak in 2019, followed by a slight decline in 2020.

6. Regional Diversity in Availability

- Countries across multiple continents show varying levels of Netflix library availability


---

## 📷 Screenshots

![Screenshot 2025-05-07 155650](https://github.com/user-attachments/assets/ea76a1e8-041b-4db3-83c3-ee52d4090f3f)



---

## 📚 Learnings

1. Content Type Distribution
- Movies dominate the platform, making up 68.42% of the total content, while TV Shows account for 31.58%.

2. Global Reach
- The United States leads by a wide margin in content production, with over 2,000 titles.
- Other high-contributing countries include India, United Kingdom, and Canada.

3. Top Genres
- The most prevalent genres on Netflix are:
  - Documentaries (299)
  - Stand-Up Comedy (273)
  - International Dramas (248)
  - Independent Dramas (186)
- These genres indicate a strong emphasis on informative and culturally diverse storytelling.

4. Ratings Distribution
- The majority of content is rated TV-MA (2,027 titles), suggesting a strong presence of mature content.
- Other common ratings include TV-14, TV-PG, and R.

5. Content Growth Over Time
- Netflix saw an exponential spike in content additions between 2016–2019.
- Both movies and TV shows grew significantly, with a sharp drop post-2019 (possibly reflecting data limits or platform strategy shifts).

6. Example Data Point
- The selected title “1 Chance 2 Dance” is a TV-PG rated movie from 2014, added to Netflix in 2017, categorized under Dramas and Romantic Movies.

🛠️ Built With
- Tableau Public
- Data visualization techniques including:
  - Choropleth maps
  - Bar and bubble charts
  - Area charts
  - Interactive filters (Type, Title


---
