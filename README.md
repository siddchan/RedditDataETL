# RedditDataETL

## Introduction:
This project involves building a data pipeline using the Reddit API to collect and analyze Reddit data. Utilizing Airflow for orchestration and Celery for task management, the data is ingested into S3, processed with Glue Crawler and Athena, and stored in Redshift. Visualizations and insights are generated using QuickSight for data-driven decision-making.


## Architecture:
![Project Architecture](data-flow-diagram/RedditDataEngineering.png)


## Technologies Used:
1. Programming Language - Python
2. Scripting Language - PySpark, SQL
3. Amazon Web Services
     - S3 Object Storage
     - Glue Catalog
     - Glue Crawler
     - Amazon Athena
     - Amazon Redshift
4. Orchestration Tool - Airflow
5. Docker


## Links
**Getting started with Reddit API:** https://www.reddit.com/r/reddit.com/wiki/api/
 
**Creating Reddit Apps:** https://www.reddit.com/prefs/apps/

**Airflow Documentation:** https://airflow.apache.org/docs/
 
 

 
