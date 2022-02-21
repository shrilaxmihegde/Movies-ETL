# OverView the project.
In this Movies_ETL project Britta needs our help to create an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables.
1. Create an ETL pipeline from raw data to a SQL database.
2. Extract data from disparate sources using Python.
3. Clean and transform data using Pandas.
4.Use regular expressions to parse data and to transform text into numbers.
5.Load data with PostgreSQL.
 ## Write an ETL function to read three data files:
Here we created the three saperate files.Read the Kaggle metadata and MovieLens ratings CSV as panda DataFrames. Opened the wikipedia JSON file and read the Wiki_movies file.

## Extract and Transform the Kaggle and rating data
 Again, we consolidated the redundant data, removed the duplicates, formatted and grouped the data.
The Kaggle and rating data were then merged with the Wikipedia movies DataFrame.
## Load the data to a PostgreSQL Movie Database:
![movies_query](/Resources/movies_query.png)
![ratings_query)](/Resources/ratings_query.png)

# Summary:
The ETL function created collects and cleans movie data from different sources (Wikipedia JSON and Kaggle and ratings csv files). It transforms and merges the data and loads it into two updatable PostgreSQL dataset tables ready to be used by the hackathon participants for their analysis.