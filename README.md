# Movies-ETL

## Project Overview
In this module we'll be using the ETL process to extract movies data from Wikipedia and Kaggle, transform it into one clean data set then load it into a clean SQL database for participants of Amazing Prime's sponsored hackathon. 

### Resources
- Data Sources: wikipedia-movies.json, ratings.csv, movies_metadata.csv
- Result Files: practice.ipynb, ETL_function_test.ipynb, ETL_clean_kaggle_data.ipynb, ETL_clean_wiki_movies.ipynb, ETL_create_database.ipynb
- Image Files: movies_query.png, practice.ipynb
- Software: PostgreSQL 12.3, pgAdmin4, Python 3.7.6, Anaconda 4.8.3, Jupyter Notebook 6.0.3

## Results
Using the 3 data sources we have successufully extracted, transformed and loaded the data into the database. The resulting tables in the movie_data database are movies and ratings. The [movies tables](movies_query.png) has 6,075 records while the [ratings tables](ratings_query.png) has 26,024,289 records.