# IMDb-Movie-Dataset-Exploratory-Data-Analysis-EDA
## Objective: To analyze historical movie data and uncover patterns that can help stakeholders make informed decisions about movie production, budgeting, and marketing strategies.
## Dataset: 5,000+ IMDb movie records containing information such as budget, gross revenue, ratings, votes, runtime, and genre.
### Dataset Link: (https://www.kaggle.com/datasets/karrrimba/movie-metadatacsv/data)
## Key Steps:
- Data Cleaning: Removed duplicates, standardized column names, handled missing values, and converted data types for analysis.
- Outlier Analysis: Detected outliers in budget and gross using the IQR method; documented that removal is not recommended as they reflect genuine high-value movies.
- Univariate & Bivariate Analysis: Analyzed distributions of variables and relationships between budget, gross, ratings, and genres.
- Business-Oriented Questions: Answered 20+ questions including top revenue-generating genres, correlation between budget and revenue, and factors influencing IMDb ratings.
- Visualization: Created detailed charts (bar plots, box plots, scatter plots, heatmaps) to make patterns and correlations clear to stakeholders.
## Tools & Libraries: Python, Pandas, NumPy, Matplotlib, Seaborn
## Key Insights:
- Action movies with higher budgets tend to yield higher revenues but also involve higher risk.
- Certain genres consistently perform well despite lower budgets (e.g., horror, thrillers).
- Revenue and IMDb ratings are not strongly correlated, suggesting critical acclaim does not always equal commercial success.
- Presence of outliers highlights blockbuster performances which should not be ignored.
