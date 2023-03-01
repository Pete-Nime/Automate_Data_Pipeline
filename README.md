# Automate_Data_Pipeline

# Content

- Create an IAM User in AWS.

- Follow the steps on the page Create an IAM User in AWS in the lesson Data Pipelines.

- Create a redshift cluster in AWS.

- Follow the steps on the page Create an AWS Redshift Cluster in the lesson Data Pipelines. Create the cluster in the us-west-2 region. This is important as the s3-bucket that tht will be employ in  this project is in us-west-2.

- Setting up Connections

- Connect Airflow and AWS

- Following the steps on the page Connect Airflow to AWS in the lesson Data Pipelines.
- Using the workspace provided on the page Project Workspace in this lesson.

- Connect Airflow to the AWS Redshift Cluster

- Following the steps on the page Add Airflow Connections to AWS Redshift in the lesson Data Pipelines.


# Executive Summary 

A music streaming company, Sparkify, has decided that it is time to introduce more automation and monitoring to their data warehouse ETL pipelines and come to the conclusion that the best tool to achieve this is Apache Airflow.

They have decided to bring you into the project and expect you to create high grade data pipelines that are dynamic and built from reusable tasks, can be monitored, and allow easy backfills. They have also noted that the data quality plays a big part when analyses are executed on top the data warehouse and want to run tests against their datasets after the ETL steps have been executed to catch any discrepancies in the datasets.

The source data resides in S3 and needs to be processed in Sparkify's data warehouse in Amazon Redshift. The source datasets consist of JSON logs that tell about user activity in the application and JSON metadata about the songs the users listen to.
