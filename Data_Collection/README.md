#Summary
Each region of interest has its own listener that utilizes the Twitter Streaming API to access tweets in a particular bounding box. These tweets are then parsed and the desired features are binned in to 4 tables in a Postgres database set up through Amazon RDS.

# Dependencies
These scripts are particular to our environment. The format of our database tables can be found in Assets/psql_tables.txt.
