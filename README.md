# Movies-ETL

## Overview of the analysis: 
Amazing Prime loves the dataset and wants to keep it updated on a daily basis. Britta needs your help to create an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables. You’ll need to refactor the code from this module to create one function that takes in the three files—Wikipedia data, Kaggle metadata, and the MovieLens rating data—and performs the ETL process by adding the data to a PostgreSQL database.

## Resources
- Data Source: movies_metadata.csv; ratings.csv; wikipedia-movies.json
- Software: Git version 2.33.0.windows.2, pgAdmin 4 Version 5.7 PostgreSQL 11

## Results
### Deliverable 1: Write an ETL Function to Read Three Data Files
- Wiki_Movies Dataframe
![Wiki_Movies_df]()
- Kaggle_Metadata Dataframe
![Kaggle_metadata]()
- Ratings Datafame
![Ratings]()


### Deliverable 2: Extract and Transform the Wikipedia Data
- Wiki Transformed
![Wiki_Movies_Transformed]()
- Wiki Columns updated
![Wiki_Movies_Columns]()

### Deliverable 3: Extract and Transform the Kaggle Data 
- Movies_with_ratings_df Dataframe
![Movies_with_Ratings]()
- movies_df Dataframe
![Movies_Dataframe]()

### Deliverable 4: Create the Movie Database
- Movie_Database in PgAdmin
![movies_query]()
- Ratings_DAtabase in PgAdmin
![ratings_query]()