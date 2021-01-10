# Overview
This repository contains work I did in Spark to build a recommender system for movies and users in MovieLens dataset. This was done as part of the college module 'Data Analysis at Speed and Scale'.

A description of the original MovieLens dataset can be seen at http://files.grouplens.org/datasets/movielens/ml-latest-small-README.html, however, for the recommendation system project I used a cleaned version of this dataset.

As I had already used this dataset for analysis in PIG & Hive, see https://github.com/Crone1/Pig_and_Hive_MovieLens_Analysis, I already had code to clean this data. This code was again used for this project and the cleaned data was uploaded to the HDFS cluster. This cleaning involved seperation of columns and joining of the data into one table and was done in Pig.

While both the Pig and Spark work was done using the Google Cloud Platform, the coding in Spark involved using a jupyter notebook web interface for the hosted cluster.

# Running the code
In order to run this code, you will need to:
1. Set up your own Google Cloud Platform cluster,
2. Run the code in the Pig_movieLens_cleaning.pig file,
3. Create the jupyter notebook with the code in this repository,
4. Run this developed recommender system.
