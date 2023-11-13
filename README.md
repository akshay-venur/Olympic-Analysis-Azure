# Olympic Data Analysis Using Azure

#### Tools Used: MySQL, HDFS, Sqoop, Hive, HBase, Snowflake, Snowpipe, Azure Data Factory, Azure Databricks, AWS, PowerBI

Project Description:
*	There were two datasets that had information about the Olympic games and the athlete's performance. 
*	The main objective was to build different kinds of pipelines to analyze the Olympic data.
*	In the first pipeline, we loaded the data from the local file system into MySQL tables, and then using the SQOOP import we moved the data into HIVE tables.
*	We partitioned the Hive tables based on the country and game types for faster query performance.
*	Then we analyzed the datasets using Hive Queries.
*	In the second pipeline, we utilized Azure and Snowflake. Data was stored in Azure and using copyInto activity we copied the data from ADLS to the snowflake, then analyzed the data using the snowflake query.
*	In the third pipeline, we utilized AWS and Snowflake. Data was stored in AWS and using snowpipe activity we copied the data from S3 to the snowflake, then analyzed the data using the snowflake query. The advantage of Snowpipe is that whenever data is available at the source it will load that data into the target automatically.
*	Finally we connected the snowflake with PowerBI to visualize the Olympic data and draw insight from it.
