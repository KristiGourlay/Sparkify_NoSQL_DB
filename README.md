# Sparkify_NoSQL_DB

The follow repo is data modeling project using Apache Cassandra. The start up, Sparkify, wants to analyze the songs and user activity on their music streaming app; in particular, they are interested in analyzing what types of songs and music their users are interested in. In this project, I created part of an ETL pipeline to transfer data from a set of CSV files into Apache Cassandra tables.

With Apache Cassandra, we model the database tables based on the queries we want to run. Thus, the three queries that our end-user will be interested in are:
* Query 1: Give me the artist, song title and song's length in the music app history that was heard during sessionId A and itemInSession B.
* Query 2: Give me the name of artist, song (sorted by itemInSession) and user (first and last name) for userid C and sessionid D.
* Query 3: Give me every user name (first and last) in my music app history who listened to the song "All Hands Against His Own"
