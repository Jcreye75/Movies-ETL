# Movies-ETL

## Overview of the analysis: 
Amazing Prime loves the dataset and wants to keep it updated on a daily basis. Britta needs your help to create an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables. You’ll need to refactor the code from this module to create one function that takes in the three files—Wikipedia data, Kaggle metadata, and the MovieLens rating data—and performs the ETL process by adding the data to a PostgreSQL database.

## Resources
- Data Source: movies_metadata.csv; ratings.csv; wikipedia-movies.json
- Software: Git version 2.33.0.windows.2, pgAdmin 4 Version 5.7 PostgreSQL 11

## Results
### Deliverable 1: Write an ETL Function to Read Three Data Files
- Wiki_Movies Dataframe
![Wiki_Movies_df](https://github.com/Jcreye75/Movies-ETL/blob/c3b2c336778a8fcfbaee2512d332c9071f5e3377/Resources/Wiki_Movies_df.png)
- Kaggle_Metadata Dataframe
![Kaggle_metadata](https://github.com/Jcreye75/Movies-ETL/blob/c3b2c336778a8fcfbaee2512d332c9071f5e3377/Resources/Kaggle_metadata.png)
- Ratings Datafame
![Ratings](https://github.com/Jcreye75/Movies-ETL/blob/c3b2c336778a8fcfbaee2512d332c9071f5e3377/Resources/Ratings.png)


### Deliverable 2: Extract and Transform the Wikipedia Data
- Wiki Transformed
![Wiki_Movies_Transformed](https://github.com/Jcreye75/Movies-ETL/blob/c3b2c336778a8fcfbaee2512d332c9071f5e3377/Resources/Wiki_Movies_Transformed.png)
- Wiki Columns updated
![Wiki_Movies_Columns](https://github.com/Jcreye75/Movies-ETL/blob/c3b2c336778a8fcfbaee2512d332c9071f5e3377/Resources/Wiki_Movies_Columns.png)

### Deliverable 3: Extract and Transform the Kaggle Data 
- Movies_with_ratings_df Dataframe
![Movies_with_Ratings](https://github.com/Jcreye75/Movies-ETL/blob/c3b2c336778a8fcfbaee2512d332c9071f5e3377/Resources/Movies_with_Ratings.png)
- movies_df Dataframe
![Movies_Dataframe](https://github.com/Jcreye75/Movies-ETL/blob/c3b2c336778a8fcfbaee2512d332c9071f5e3377/Resources/Movies_Dataframe.png)

### Deliverable 4: Create the Movie Database
- Movie_Database in PgAdmin
![movies_query](https://github.com/Jcreye75/Movies-ETL/blob/c3b2c336778a8fcfbaee2512d332c9071f5e3377/Resources/movies_query.png)
- Ratings_DAtabase in PgAdmin
![ratings_query](https://github.com/Jcreye75/Movies-ETL/blob/c3b2c336778a8fcfbaee2512d332c9071f5e3377/Resources/ratings_query.png)