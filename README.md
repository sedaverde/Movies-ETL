# Movies-ETL
## Overview
The purpose of this project was to take movie data downloaded from Wikipedia and Kaggle, and use the ETL method to create a pipeline from the raw data to a Postgres database. This was accomplished by creating four blocks of code as outlined below.

-ETL_function_test: used to define a function that would read in the three different file at one time and transform them into three corresponding dataframes.
-ETL_clean_wiki_movies and ETL_clean_kaggle_data: used to thoroughly edit the data imported from the files download from Wikipedia dn Kaggle.
-ETL_create_database: code used to import cleaned data into a premade Postgres database.
