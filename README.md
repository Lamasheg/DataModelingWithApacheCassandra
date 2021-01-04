# DataModelingWithApacheCassandra
 
### Table of Contents

1. [Project Overview](#summary)
2. [File Structure](#Files)
3. [Results of Queriess](#results)
4. [Acknowledgements](#licensing)


    
## Project Overview<a name="summary"></a>

A startup called Sparkify wants to analyze the data they've been collecting on songs and user activity on their new music streaming app. The analysis 
team is particularly interested in understanding what songs users are listening to. Currently, there is no easy way to query the data to generate 
the results, since the data reside in a directory of CSV files on user activity on the app.

They'd like a data engineer to create an Apache Cassandra database which can create queries on song play data to answer the questions, 
and wish to bring you on the project. Your role is to create a database for this analysis. You'll be able to test your database by running queries 
given to you by the analytics team from Sparkify to create the results.

## File Structure<a name="Files"></a>

1. event_data: folder containing 30 event data files
2. images: containing a snapshot of the event_data_file_new.csv file and query results 
3. Project_1B_ Project_Template.ipynb: pyhton file that Extracts data from data file, Transfer and Load data using Apache Cassandra
4. event_data_file_new.csv: file generated using Project_1B_ Project_Template.ipynb to hold all data in seperate events files
   
## Results of Queries<a name="results"></a>

1. Give me the artist, song title and song's length in the music app history that was heard during sessionId = 338, and itemInSession = 4:
![](images/q1.png?raw=true)

2. SGive me only the following: name of artist, song (sorted by itemInSession) and user (first and last name) for userid = 10, sessionid = 182:
![](images/q2.png?raw=true)

3. Give me every user name (first and last) in my music app history who listened to the song 'All Hands Against His Own':
![](images/q3.png?raw=true)

## Acknowledgements<a name="licensing"></a>
Credits go to udacity for providing the opportunity to practice our skills!
