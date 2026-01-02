Big Data Analysis with Apache Spark
This project focuses on implementing big data processing and analysis techniques using the Apache Spark ecosystem. The study explores the core logic of MapReduce, distributed SQL querying, and machine learning applications on a movie dataset.

📌 Project Overview
The primary objective of this project is to master the fundamental components of Spark for data engineering and data science tasks:

MapReduce: Understanding distributed data processing through RDD transformations.

Spark SQL: Performing complex data analysis and joining structured datasets.

Machine Learning: Building predictive models using Spark's MLlib.

🛠 Tech Stack

Language: Python (PySpark).

Engine: Apache Spark.

Libraries: PySpark SQL, PySpark ML, Matplotlib, Pandas.

Environment: Spark Virtual Machine.

📊 Dataset
The analysis uses the MovieLens dataset, which contains comprehensive information about film categories and user preferences:

movies.csv: Includes Movie IDs, titles, and genres.

ratings.csv: Includes User IDs, ratings, and timestamps.

🚀 Key Features
1. MapReduce: Movie Count by Genre
Utilizing RDDs and the MapReduce paradigm to calculate the total number of movies for each genre.

Applied flatMap to handle movies belonging to multiple categories.

Used reduceByKey to aggregate movie counts efficiently across the cluster.

Result: Identified Drama and Comedy as the most prevalent genres in the dataset.

2. SQL Analysis
Executed high-performance queries using Spark SQL to extract meaningful insights:

Popular & High-Rated Movies: Filtered for movies with over 100 votes to ensure statistical reliability, identifying top-rated classics like The Shawshank Redemption and The Godfather.

Average Ratings by Genre: Leveraged split and explode functions to analyze ratings for individual genres within multi-genre films.

3. Machine Learning (MLlib)
Developed predictive models to demonstrate Spark's machine learning capabilities:

Classification (Logistic Regression): Predicted movie popularity (popular vs. non-popular) based on rating counts and average ratings.

Regression (Linear Regression): Modeled the relationship between vote counts and average ratings, evaluating performance via RMSE.

📈 Visualizations
The project includes data visualizations created with Matplotlib to illustrate the findings:

Popularity Clusters: Visualizing the separation of popular movies from the general dataset.

Regression Analysis: Plotting the prediction line for average movie ratings against vote counts.
