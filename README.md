# AWS-S3-External-Stage-For-Snowflake
Create AWS S3 as external stage and  load data to Snowflake

Reference https://docs.snowflake.com/en/user-guide/data-load-s3-config.html

Option 1
Configure a storage integration object to delegate authentication responsibility for external cloud storage to a Snowflake identity and access management (IAM) entity.

Note:

  Snowflake highly recommend this option, which avoids the need to supply AWS IAM credentials when creating stages or loading data.



Step 1: Configure Access Permissions for the S3 Bucket

  AWS Access Control Requirements

  Creating an IAM Policy

Step 2: Create the IAM Role in AWS

Step 3: Create a Cloud Storage Integration in Snowflake

Step 4: Retrieve the AWS IAM User for your Snowflake Account

Step 5: Grant the IAM User Permissions to Access Bucket Objects

Step 6: Create an External Stage

Step 7: Loading Data from S3 Stage to Snowflake Table

