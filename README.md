# SparkifyDB project

developed by Miguel Marcondes

This repo contains an Udacity Nanodegree Data Engineering project focused on Data Modeling developed using PostGreSQL and Python. It was developed with the presence of an full-fledged ETL and a star schema to maximize the utility of the database.

## Description of contents

1. create_tables.py
    * Routine used to create and drop tables
2. sql_queries.py
    * File containing all queries used to build schemas and tables
3. etl.py
    * ETL file focused on dealing with multiple json files
4. data/log_data and data/song_data
    * data files
5. etl.ipynb
    * Step by step tutorial to build ETL file
6. test.ipynb
    * Routine tests
7. README.md
    * file focused on describing the project (you are here!)
 
## Running the ETL pipeline
Be sure you downloaded all corresponding files, including the data folder. Replace the connection string defined on create_tables.py with your own PostgreSQL server and then follow the next steps:

1. Run create_tables.py to initialise the database.

2. Start and run test.ipynb to validate all tables. Restart the kernel to actually run the core process.

3. Run create_tables.py to reinitialise the database.

4. Run etl.py to trigger the ETL data pipeline and treat all the files and jsons defined on the data folder, transfering them to an usable format.