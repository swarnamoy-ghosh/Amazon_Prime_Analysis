📊 Amazon Prime Video Content Analysis
This project provides a comprehensive exploratory data analysis (EDA) of Amazon Prime Video’s content catalog, focusing on key trends, content distribution, viewer preferences, and performance metrics. The goal is to generate actionable insights to support business decisions in the OTT (Over-The-Top) entertainment space.

📁 Dataset Description
The dataset includes metadata about titles available on Amazon Prime, including:

title: Name of the show or movie

type: Movie or Show

release_year: Year of release

age_certification: Audience suitability rating

runtime: Runtime in minutes

genres: List of associated genres

production_countries: Country of origin

seasons: Number of seasons (for shows)

imdb_score, imdb_votes: IMDb ratings and votes

tmdb_score, tmdb_popularity: TMDb ratings and popularity metrics

📌 Objectives
Clean and preprocess raw data

Understand content type distribution

Analyze genre and country-based trends

Explore rating correlations (IMDb & TMDb)

Identify top-rated, most-voted, and most-popular titles

Examine trends over time using time series

Derive business-impacting insights

🧹 Data Cleaning & Preprocessing
Removed duplicates and whitespace

Converted list columns (e.g., genres, countries) from strings to Python lists

Filled missing values intelligently (e.g., averages, placeholders)

Assigned unique IMDb IDs where missing

Separated analysis for MOVIE and SHOW

📊 Key Visualizations
Distribution of Content Type (Bar & Pie Chart)

Genre Popularity (Bar Chart with color mapping)

Top Content-Producing Countries (Bar Chart & Treemap)

Ratings Correlation Heatmaps (for Movies & Shows)

Genre-wise IMDb Scores (Bar Chart)

Content Growth Over Time (Time Series)

Age Certification Distribution (Countplot & Pie Chart)

Top Rated & Popular Titles (Bar & Bubble Charts)

🔍 Insights
📈 Highest content growth occurred between 2018–2021

🌍 U.S., India, and U.K. lead in production volume

🎭 Drama is the most frequent genre across types

🌟 Titles with high IMDb/TMDb scores correlate with high votes and popularity

🧒 Diverse age certification allows targeting multiple audience segments

✅ Business Impact
Positive:
Improve recommendation systems with genre and rating insights

Focus marketing efforts on high-performing regions and genres

Increase user retention by promoting top-rated content

Negative:
Overdependence on few genres or countries may limit diversity

Inconsistent content addition may confuse long-term users

🚀 Suggestions for Improvement
Introduce more localized content for underrepresented regions

Promote high-quality shows with growing popularity trends

Monitor underperforming genres and replace with better alternatives

📌 Tools Used
Python (Pandas, NumPy, Matplotlib, Seaborn, Plotly)

Jupyter/Google Colab for interactive analysis

Plotly for interactive dashboards

🧠 Conclusion
This project gives a data-backed perspective into Amazon Prime's catalog, offering insights that help in content planning, audience targeting, and strategic content curation. The methodology and findings can be adapted for other OTT platforms as well.
