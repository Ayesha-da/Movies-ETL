# Movies-ETL
## overview
 Extract, Transform, Load (ETL) is a process to create data pipelines. A data pipeline moves data from a source to a destination, and the ETL process creates data pipelines that also transform the data along the way.
 ## Purpose
 ETL process: To extract the Wikipedia and Kaggle data from their respective files, transform the datasets by cleaning them up and joining them together, and load the cleaned dataset into a SQL database.
 ## Summary
- The wiki_movies data had 7311 rows and  193 columns 
- kaggle_metadata  45466 rows and 24 columns and 
- ratings data had over 1048576 rows.

 This  data is then filtered, parsed, sorted, interpolated, pivoted, summarized, aggregated and merged. The goal was to create a consistent structure in the data.Finally, after    the data is transformed into a consistent structure, it's loaded into  relational database, PostgreSQL.
 The end result is cleaned is 6052 clean data rows and 31 columns from both wiki moivies and kaggle data combined.
 
 ![movies_query](https://user-images.githubusercontent.com/84524153/127746615-4b075713-77c1-4620-8cc7-e52bdf296bd2.png)
 ![movies_df](https://user-images.githubusercontent.com/84524153/127746987-b66e4a0a-40b5-4fc4-a5f4-2aed5b468156.png)

 
and ratings data end result were 26024289 rows ready to use.

![ratings_query](https://user-images.githubusercontent.com/84524153/127746619-41c1a8a2-f473-4c0e-9876-1651d74e5095.png)
![movie_with_ratings](https://user-images.githubusercontent.com/84524153/127747000-b664c65e-fa9f-42d1-bfe7-65003cc2dfff.png)
![movie_with_ratings1](https://user-images.githubusercontent.com/84524153/127747002-5c72e291-2cbf-4d7b-95a8-3c6ad11326a0.png)

