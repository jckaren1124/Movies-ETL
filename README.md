# Movies-ETL

Amazing Prime Video is a platform for streaming movies and TV shows.  Amazing Prime would like to predict which low budget films will become popular in the future so that streaming rights can be purchased at a low price. A Hackathon event was created for participants to predict popular movies from a clean dataset of movie data.  The dataset came from 2 data sources: Wikipedia with all movies released since 1990 and rating data from the MovieLen's website. Data was extracted from both sources, transformed into one clean dataset, and that dataset was then loaded into a SQL table.


### Deliverable 1

An ETL function was written to read in the Wikipedia JSON file, Kaggle metadata file, and MovieLens ratings data file to a Pandas DataFrame.

***Wikipedia JSON file DataFrame***

![image](https://user-images.githubusercontent.com/89353378/141657940-7675e07a-aa92-45ee-8dbc-1b379d853cec.png)


***Kaggle metadata file DataFrame***

![image](https://user-images.githubusercontent.com/89353378/141657966-3b99f833-11bf-4dba-b5c4-6c9aaae9100f.png)

***MovieLens ratings data DataFrame***

![image](https://user-images.githubusercontent.com/89353378/141657984-f8d37489-b300-4a27-b8a2-9c366dccf661.png)


### Deliverable 2

The cleaned Wikipedia data is converted to a Pandas DataFrame.

![image](https://user-images.githubusercontent.com/89353378/141658260-8fdf042e-0b11-4549-acca-4bc3b3eff9d3.png)


### Deliverable 3

The Kaggle metadata and MovieLens ratings data are cleaned and merged together.

![image](https://user-images.githubusercontent.com/89353378/141658349-a17b2591-bf51-4ca7-a8af-de9257a776d1.png)


### Deliverable 4

The cleaned and merged dataset is uploaded to the SQL database with two new tables: movies_query and ratings_query.

![movies_query](https://user-images.githubusercontent.com/89353378/141658495-6d482854-95dc-4ae9-8ae8-8a0e22f01477.png)

![ratings_query](https://user-images.githubusercontent.com/89353378/141658503-ab448357-12a9-478b-a70f-33c8a3b39d81.png)





