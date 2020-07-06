## Project Name
Data Modeling with Apache Cassandra<br><br>
## Purpose
To perform ETL process on Spakify's dataset, which is stored as CSV files<br><br>
## Description
This project is a part of Udacity's Data Engineering Nanodegree program. Sparkify is a startup that runs music streaming app. The company's analytics team wants to know which songs its users listen to, and requested answers to <u>three specific questions</u>. Raw data from the app is stored in local CSV files, and ETL is performed on the data using Python module cassandra.
#### The Three Questions asked by Sparkify
1. Give me the artist, song title and song's length in the music app history that was heard during sessionId = 338, and itemInSession = 4
2. Give me only the following: name of artist, song (sorted by itemInSession) and user (first and last name) for userid = 10, sessionid = 182
3. Give me every user name (first and last) in my music app history who listened to the song 'All Hands Against His Own<br><br>
## How to run
Run cassandra_etl.ipynb in Jupyter Notebook<br><br>
## ETL Process
1. Get a list relevaent CSV files contained in a directory
2. Use a for loop to extract data from them, and put them into three tables (one table for each query)<br><br>
## Result
3 tables, one for each query (or question)
