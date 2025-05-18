IMDB Movie Dataset Exploratory Data Analysis (EDA)
Objective: 
The goal of this project is to perform Exploratory Data Analysis (EDA) on an IMDB movie dataset to uncover insights related to movie ratings, runtime, genres, budgets, gross revenue, and other attributes that contribute to a movie's success.
Libraries Used:
	Pandas 
	Numpy 
	Matplotlib 
	Seaborn
Key Steps and Highlights: 
1.Data Loading & Preprocessing: 
	Imported dataset using pandas. 
	Handled missing values and removed duplicates.
	Cleaned columns related to budget, gross earnings, and others by converting them into usable numerical formats.
2.Exploratory Data Analysis: 
	Descriptive Statistics: Summary statistics for numerical features. 
	Correlation Analysis: Used heatmaps and scatter plots to identify relationships between budget, gross, votes, and score.
	Found a strong correlation between budget and gross earnings. Votes and gross also show a positive correlation.
3.Visualizations: 
	Created visualizations using matplotlib and seaborn to understand: Top production companies. 
	Year-wise trends in movie release counts. Genre-wise distribution. Runtime distribution and its relation to rating. 
	Used bar plots, heatmaps, line plots, and scatter plots for comprehensive insight.
Key Insights: 
High-budget movies generally yield higher gross revenue. Movies with higher IMDB scores receive more votes. Certain genres like Drama and Action are more frequent. A few companies dominate the top-grossing movies. Year-wise, there's a steady increase in movie production.
Outcome: 
This project helps understand what factors potentially influence a movie’s success on IMDB using real-world data. It can be extended further with machine learning models for prediction, or deeper statistical analyses.
