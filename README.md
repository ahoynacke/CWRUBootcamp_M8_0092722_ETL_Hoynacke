# CWRUBootcamp_M8_0092722_ETL_Hoynacke
## Note to Grader: 
I had to compress the resource folder due to size of files - I hope that does not affect the final submission 

## Background 
Amazing Prime loves the dataset and wants to keep it updated on a daily basis. Britta needs your help to create an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables. You’ll need to refactor the code from this module to create one function that takes in the three files—Wikipedia data, Kaggle metadata, and the MovieLens rating data—and performs the ETL process by adding the data to a PostgreSQL database.

## Project Deliverables 
This new assignment consists of four technical analysis deliverables: 

Deliverable 1: Write an ETL Function to Read Three Data Files
Deliverable 2: Extract and Transform the Wikipedia Data
Deliverable 3: Extract and Transform the Kaggle data
Deliverable 4: Create the Movie Database

## Deliverable 1  

1. An ETL function is written to read in the three data files
2. The function converts the Wikipedia JSON file to a Pandas DataFrame, and the DataFrame is displayed in the ETL_function_test.ipynb file. 
3. The function converts the Kaggle metadata file to a Pandas DataFrame, and the DataFrame is displayed in the ETL_function_test.ipynb file.
4. The function converts the MovieLens ratings data file to a Pandas DataFrame, and the DataFrame is displayed in the ETL_function_test.ipynb file. 

## Deliverable 2 

1. The TV shows are filtered out, and the wiki_movies_df DataFrame is created.
2. A try-except block is used to catch errors while extracting the IMDb IDs with a regular expression and dropping duplicate IDs. 
3. The extract and transform of the Wikipedia data 
4. The cleaned Wikipedia data is converted to a Pandas DataFrame, and the DataFrame is displayed in the ETL_clean_wiki_movies.ipynb file. 

## Deliverable 3 

1. Extract and transform the Kaggle metadata using the ETL function 
2. Extract and transform the MovieLens ratings data using the ETL function 
3. The movies_with_ratings_df and the movies_df DataFrames are displayed in the ETL_clean_kaggle_data.ipynb file.

## Deliverable 4

1. The data from the movies_df DataFrame replaces the current data in the movies table in the SQL database, as determined by the movies_query.png. 
2. The data from the MovieLens rating CSV file is added to the ratings table in the SQL database, as determined by the ratings_query.png. 
3. The elapsed time to add the data to the database is displayed in the ETL_create_database.ipynb file. 

## Project Summary - Analysis 
For this project we had 3 difference resources in which we cleaned and re structured. Using the ETL method we extracted, transformed and loaded the data. We were merging two different types of data for this project - json and csv. Each file submitted as a deliverable built on top of eachother resulting in a clean dataset. 
