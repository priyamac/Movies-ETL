# Movies-ETL

---
## Overview 

This paper sets out to create an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables. It will refactor the code from this module to create one function that takes in the three files—Wikipedia data, Kaggle metadata, and the MovieLens rating data—and performs the ETL process by adding the data to a PostgreSQL database.

### Aim 

The aim of this paper is to:
  1) Write an ETL Function to Read Three Data Files
  2) Extract and Transform the Wikipedia Data
  3) Extract and Transform the Kaggle data
  4) Create the Movie Database

---

### Read Data File 
[ETL_function_test.ipynb](ETL_function_test.ipynb)

- The first step was to create an ETL function to read in the three data data files and convert the JSON data and csv files to a Pandas DataFrame.  
- Next was to make a path to the file directory and create variables for the three files
- Then Setting the three variables to equal the ETL function reassigns the variables to the variables in the return statement.

### Wikipedia Data 

[ETL_clean_wiki_movies.ipynb](ETL_clean_wiki_movies.ipynb)

### Kaggle Data 

[ETL_clean_kaggle_data.ipynb](ETL_clean_kaggle_data.ipynb)

### Movie Database 

[ETL_create_database.ipynb](ETL_create_database.ipynb)

*This is the part where I struggles to get all the information. I'm still playing around with trying to get the data into the correct data type so it will run properly and I can resubmit. But for now I managed to get the querey resutls.*

---
## Summary 
