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

They have decided to employ data engineer into the project and expect them to create high grade data pipelines that are dynamic and built from reusable tasks, can be monitored, and allow easy backfills. They have also noted that the data quality plays a big part when analyses are executed on top the data warehouse and want to run tests against their datasets after the ETL steps have been executed to catch any discrepancies in the datasets.

The source data resides in S3 and needs to be processed in Sparkify's data warehouse in Amazon Redshift. The source datasets consist of JSON logs that tell about user activity in the application and JSON metadata about the songs the users listen to.


# Datasets

For this project, datasets that will be working on are as follows with the s3 links for each:

Log data: s3://udacity-dend/log_data

Song data: s3://udacity-dend/song_data


# Project Template

With these template files, will be able see the new DAG in the Airflow UI. The graph view should look like this:

![image](https://user-images.githubusercontent.com/103359089/222222170-fe356c67-5796-41a4-8401-b2793d8024a6.png)


# Configuring the DAG

Configuring the task dependencies so that after the dependencies are set, the graph view follows the flow shown in the image below.



![image](https://user-images.githubusercontent.com/103359089/222222449-94319f7e-b8fd-475f-9757-29717c0d0da4.png)


# The Project Workspace:

After updating the DAG, will need to run /opt/airflow/start.sh command to start the Airflow web server. Once the Airflow web server is ready, we can access the Airflow UI by clicking on the blue Access Airflow button.
