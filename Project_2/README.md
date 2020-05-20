## Project Datawarehouse

### Overview

Sparkify is a music streaming startup with a growing user base and song database.


Their user activity and songs metadata data resides in json files in S3. The goal of the current project is to build an ETL pipeline that extracts their data from S3, stages them in Redshift, and transforms data into a set of dimensional tables for their analytics team to continue finding insights in what songs their users are listening to.


### Follow the below steps to run the project

1. Fill dwh.cfg accordingly (Note : please dont share the credentials with any one as per guideline)

2. Run the create_tables.py script to set up the needed infrastructure for this project.

3. Finally, run the etl.py script to extract data from the files in S3, stage it in redshift, and finally store it in the dimensional tables.



REMINDER: Do not include your AWS access keys in your code when sharing this project!
