# Movies-ETL MODULE 8
ETL - Extract, Transform, Load

## Purpose of the repository.
Amazing Prime needs your help to create an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables.
I need to refactor the code from this module to create one function that takes in the three files—Wikipedia data, Kaggle metadata, and the MovieLens rating data 
and performs the ETL process by adding the data to a PostgreSQL database.

## Results: 
I reviewed and cleaned the following files:
* movies_metadata.csv
* ratings.csv
* Wikipedia-movies.json
1. I extracted the Wikipedia Movies JSON
2. I extracted the Kaggle Data
3. I investigated the files
4. Iterative Process for Cleaning Data
a) Inspect
b) Make a plan
c) Execute 
5. The JASON file was the most complex and needed more time to clean.
a) Eliminating duplicates
b) Merging columns with same data
c) Dropping null values
d) Update the data types
6. After both data were cleaned I merged them together
7. I decided which data to keep
8. I used the PgAdmin to load both tables

![movies_query](https://user-images.githubusercontent.com/95668609/155263517-060c7b52-5faf-4848-b4c2-8730865bd399.png)
(movies_query.png)

![ratings_query](https://user-images.githubusercontent.com/95668609/155263529-ce86a631-114d-4f2a-af58-753fd58668bb.png)

(ratings_query.png)
