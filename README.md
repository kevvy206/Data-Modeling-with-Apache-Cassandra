### How to run:
Run cassandra_etl.ipynb

### Project Name
Data Modeling with Apache Cassandra

### Purpose
To perform ETL process on Spakify's dataset for its analytics team
* Sparkify is a startup that runs music streaming app
* The analytics team wants answers to three specific questions,
  and the answers can be obtained by three specific queries
* Since data has to be designed upon the final queries,
  Apache Cassandra will be used.
* Raw data from the app is stored in CSV files, and this project
  extracts data from them using a Python module.
  
### The Three Questions asked by Sparkify
1. Give me the artist, song title and song's length in the music app history
   that was heard during sessionId = 338, and itemInSession = 4
2. Give me only the following: name of artist, song (sorted by itemInSession)
   and user (first and last name) for userid = 10, sessionid = 182
3. Give me every user name (first and last) in my music app history
   who listened to the song 'All Hands Against His Own

### ETL Process
1. Get a list relevaent CSV files contained in a directory
2. Use a for loop to extract data from them, and put them into three tables
   (a table for each query)

### Result
3 tables, one for each query(or question)