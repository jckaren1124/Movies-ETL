# Movies-ETL

Amazing Prime Video is a platform for streaming movies and TV shows.  Amazing Prime would like to predict which low budget films will become popular in the future so that streaming rights can be purchased at a low price. A Hackathon event was created for participants to predict popular movies from a clean dataset of movie data.  The dataset came from 2 data sources: wikipedia with all movies released since 1990 and rating data from the Movie Land's website. Data was extracted from both sources, transformed into one clean dataset, and that dataset was then loaded into a SQL table.

Extract: gathering data from one or multiple sources, such as CSV, API, JSON, Excel, web scraping or data queries.

Transform: manipulating data to your liking before inserting into the final database (i.e. read your data into Pandas and removing null values, or remove entire columns as it is not required in your analysis).

Load: load transformed data into its final destination (i.e. use Pandas to_sql method and sqlAlchemy).
