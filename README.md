# Analysis on data from both Wikipedia and Kaggle on Movies.

## Overview
Performs the ETL(Extract, Transform and Load) process by adding the data to a PostgreSQL database.

## Purpose
The purpose of this challenge is to create an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables. In order to do this, I needed to refactor the code from this module to create one function that takes in the three files—Wikipedia data, Kaggle metadata, and the MovieLens rating data—and performs the ETL process by adding the data to a PostgreSQL database.

# Results
The movies table consists of 31 columns holding a range of information for 6052 different movies:

<img width="350" alt="Screen Shot 2022-08-13 at 5 11 20 PM" src="https://user-images.githubusercontent.com/107584891/184516270-f4b04dfc-f7f8-4335-b470-f33d00bfaa79.png">

The ratings table consists of 5 different columns containing information on over 26 million individual user ratings.

<img width="348" alt="Screen Shot 2022-08-13 at 5 11 55 PM" src="https://user-images.githubusercontent.com/107584891/184516279-97d73f18-6921-425d-907d-32ccdd05d19b.png">
