# Data_Eng
Data Engineering Projects

-- (1) Data_modeling in PostGres SQL
        -- Building an ETL Pipeline using Python and SQL for a Music and User activity for Music Streaming App
        
        
Description :-
  - A startup Sparkify wants to analyze the data on songs and user activity on their new music streaming app.
  - The analytics team is particularly interested in understanding what songs users are listening to
  - There is requirement to create a database schema and ETL pipeline for this analysis.
  - Should be able to test the database and ETL pipeline by running queries given the analytics team from Sparkify
  
  
Impementation Details :-
  - The SQL Queries are written in a separate file :- 'sql_queries.py'
  - The DataBase Schema, table creation and Insertion of Data is done in the file 'create_tables.py'
  - The SQL QUeries processing into ETL pipeline is done using Python with the file :- 'etl.py'
  - Star Based Schema implemented to Make the Relation on Song Id and Artist Id
  
  Run the files in order to get results :-
    (1) Run the file create_tables.py
        --> run -i 'create_tables.py'  (This file requires sql_queries.py as an input)
     
    (2) Run the file etl.py
        --> run -i 'etl.py' 
