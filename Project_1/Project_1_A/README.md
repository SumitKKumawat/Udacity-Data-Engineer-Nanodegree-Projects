Follow the below steps to run the project:

1. Open Terminal
2. Run command "Python create_tables.py" to create tables in database.
3. Now run command "python etl.py" to process data son files.

For more info, please open {Run CMD1.png, Run CMD2.png, Run CMD3.png}

Note_1: For the table to be created successfully all these dependencies (dimensions) must be created first then create the songplays table (fact table). To do so, just change the ordering of the tables in the create_table_queries list to be as below

create_table_queries = [user_table_create, song_table_create, artist_table_create, time_table_create,songplay_table_create]

Note_2 : REMEMBER: Restart this notebook to close connection to sparkifydb

Each time you run the cells above, remember to restart this notebook to close the connection to your database. Otherwise, you won't be able to run your code in create_tables.py, etl.py, or etl.ipynb files since you can't make multiple connections to the same database (in this case, sparkifydb).
