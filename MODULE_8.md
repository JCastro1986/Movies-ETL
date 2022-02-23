# Movies-ETL MODULE 8
ETL - Extract, Transform, Load

## Purpose of the repository.
Amazing Prime needs your help to create an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables.
I need to refactor the code from this module to create one function that takes in the three files—Wikipedia data, Kaggle metadata, and the MovieLens rating data 
and performs the ETL process by adding the data to a PostgreSQL database.

## Results: 
I reviwed and cleaned the following files:
* movies_metadata.csv
* ratings.csv
* wikipedia-movies.json
1. I extracted the Wikipedia Movies JSON
2. I extracted the Kaggle Data
3. I investigated the files
4. Iterative Process for Cleaning Data
a) Inspect
b) Make a plan
c) Execute 
5. The JASON file was the most complexe and neede more time to clean.
a) Eleminating duplicates
b) Merging colums with same data
c) Dropping null values
d) Update the data types
6. After both datas were cleaned I merged them togather
7. I decided whitch data to keep
8. I used the PgAdmin to load both tables

(movies_query.png)

(ratings_query.png)

