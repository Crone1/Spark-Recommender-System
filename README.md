This repository contains the college work I did during the module 'Data Analysis at Speed and Scale' using the big data tool - Spark.

In this work, I used the MovieLens datast to build a recommender system for movies and users in this data.

A description of the original MovieLens dataset can be seen at http://files.grouplens.org/datasets/movielens/ml-latest-small-README.html, however, for this project I used a cleaned version of this dataset. As I had already used this dataset for analysis in PIG & Hive, see https://github.com/Crone1/Pig & https://github.com/Crone1/Hive respectively, I had already cleaned this data and uploaded the cleaned data to the HDFS cluster. This cleaning involved seperation of columns and joining of the data into one table and was done in Pig.

This work was done using the Google Cloud Platform and a jupyter notebook web interface for the hosted cluster.

In order to run this code, you will need to set up your own Google Cloud Platform cluster and run the code in the MovieLens_cleaning.pig file in the https://github.com/Crone1/Pig resository. This will then put you in a position to create the jupyter notebook with the code in this repository and run this developed recommender system.
