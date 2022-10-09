# Movies-ETL
## Overview
Code was generated to create one function that takes in the three files, Wikipedia data, Kaggle metadata, and the MovieLens rating data contained in csv and json formats, performs the appropriate transformations, and loads the data into a comprehensive PostgreSQL database.
## Resources
### Software
•	Jupyter NB

•	Python

•	pgAdmin

### Data files
•	wikipedia-movies.json

•	ratings.csv

•	movies_metadata.csv
## Summary
Data was parsed into a two table SQL database. Table 1 “movies” contains IMDB link and ID, year, title actor, director, composer, producer, budget, release data amongst others for 6051 movie entries.  Table 2 “ratings” contains 26M+ movie ratings.
