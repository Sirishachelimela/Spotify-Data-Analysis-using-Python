<img width="1024" height="651" alt="image" src="https://github.com/user-attachments/assets/4c506947-de34-445e-a97f-631160726b01" />
🎵 Spotify Data Analysis using Python
📌 Project Overview
_____________________________________________________________________________________________________________________________________________________________________________
This project performs an exploratory data analysis (EDA) on Spotify track and artist data to uncover insights about music trends, artist popularity, audio features, and factors influencing song success.
The analysis is designed from a data analyst perspective, focusing on data cleaning, feature engineering, visualization, and business-oriented insights.

🎯 Objectives
_____________________________________________________________________________________________________________________________________________________________________________
Understand the structure and quality of Spotify track and artist data

Analyze factors that influence song and artist popularity

Explore music trends over time (release patterns, song duration)

Perform artist-level analysis including popularity distribution, genres, and emerging artists

Translate findings into business-relevant insights

📂 Dataset Description
_____________________________________________________________________________________________________________________________________________________________________________
The project uses two datasets:

tracks.csv – song-level metadata including popularity, audio features, duration, and release date

artists.csv – artist-level metadata including popularity, followers, and genres

Source: Spotify metadata dataset (commonly available on Kaggle)

🛠️ Tools & Libraries Used

Python
_____________________________________________________________________________________________________________________________________________________________________________
Pandas – data manipulation and cleaning

NumPy – numerical operations

Matplotlib & Seaborn – data visualization

Google Colab – execution environment

🧹 Data Cleaning & Preparation
_____________________________________________________________________________________________________________________________________________________________________________
Checked and handled missing values

Dropped records with minimal missing critical information

Converted:

duration_ms → minutes for readability

release_date → datetime format

Created derived columns such as release_year for trend analysis

📊 Key Analysis Performed

🔹 Track-Level Analysis

Top and least popular tracks

Correlation between audio features (energy, loudness, danceability) and popularity

Trends in:

Number of songs released per year

Average song duration over time

🔹 Artist-Level Analysis

Distribution of artist popularity

Relationship between followers and popularity

Genre-based popularity analysis

Identification of emerging artists (low followers but high popularity)

📈 Key Visualizations
_____________________________________________________________________________________________________________________________________________________________________________
Correlation heatmap of audio features

Popularity distribution plots

Followers vs popularity scatter plot

Time-series trends of song releases and duration

🔍 Key Insights
_____________________________________________________________________________________________________________________________________________________________________________
Artist and track popularity are highly skewed, with a small number dominating engagement

Audio features like energy and loudness show a positive relationship with popularity

Songs are becoming shorter over time, aligning with modern streaming behavior

High follower count does not always guarantee high popularity, indicating the impact of recent trends and virality

Certain genres consistently produce more popular artists

💡 Business Value
_____________________________________________________________________________________________________________________________________________________________________________
Helps streaming platforms optimize recommendation algorithms

Supports music labels in identifying high-potential and emerging artists

Assists artists in understanding which audio features resonate more with audiences

Enables data-driven content promotion and playlist curation

📌 Conclusion
_____________________________________________________________________________________________________________________________________________________________________________
This analysis demonstrates how structured EDA can transform raw music metadata into actionable insights. By combining statistical analysis with visual exploration, the project highlights trends in music consumption and artist performance that are valuable for business and strategic decision-making.
