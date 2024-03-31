Netflix Dataset Analysis
Overview
This repository contains an analysis of the Netflix dataset, which includes information about various movies and TV shows available on the platform. The analysis aims to gain insights into the content distribution, viewer preferences, and trends over time.

Dataset Description
The Netflix dataset consists of information about movies and TV shows, including attributes such as title, cast, director, listed genres, country of origin, release year, rating, duration, and description. The dataset is explored and analyzed using Python programming language and popular data analysis libraries such as Pandas, Matplotlib, Seaborn, and TensorFlow.

Process
Data Preparation: The dataset is loaded into a Pandas DataFrame and cleaned by handling missing values.
Data Exploration: Various exploratory data analysis techniques are applied to understand the distribution of content types (movies vs. TV shows), popular genres, countries producing content, and temporal trends.
Visualization: Matplotlib and Seaborn libraries are used to create visualizations such as pie charts, histograms, count plots, and heatmaps to visualize the distribution and relationships within the dataset.
Statistical Analysis: Descriptive statistics are computed to summarize the numerical attributes of the dataset, such as release year and duration.
Model Building: For continuous variables, distribution plots (distplots) are created to visualize the distribution of movie durations and release years. For categorical variables, count plots and histograms are used to visualize the distribution of countries, genres, and ratings.
Insights Generation: Based on the analysis, insights are derived regarding popular content types, preferred genres, countries producing the most content, and temporal trends in content release.
Insights
The dataset contains a larger proportion of movies compared to TV shows, indicating Netflix's focus on movie content.
United States tops the list of countries producing content for Netflix, followed by India and the United Kingdom.
The average duration of movies on Netflix is around 107 minutes, with a median of 104 minutes.
Most movies in the dataset were released in the years 2020 and 2021, indicating recent content additions.
Genres like dramas, international movies, and comedies are among the most popular listed genres for both movies and TV shows.
ResNet50 achieved the highest test accuracy of 90% in the vegetable classifier analysis, followed by VGG19 with 87%, MobileNet with 80%, CNN with 79%, and the custom CNN with 67.8%.
Recommendations
Netflix may consider focusing more on producing and acquiring content in popular genres like dramas, comedies, and international movies.
Content production efforts could be targeted towards countries like India, the United States, and the United Kingdom, which have a high demand for Netflix content.
Continuous monitoring of viewer preferences and trends in content consumption can help Netflix adapt its content strategy to meet evolving viewer demands.
