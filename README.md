# Data Pipeline with Medallion Architecture using Databricks

### About this Project
This project is for understanding the implementation of Medallion Architecture. We skip the ingestion part and assume that we ingested the data in some way and stored it in our Amazon S3. In this project, we will only try to understand how the data from bronze to silver and silver to gold layers be going to look like.

### Setting Up
You have 2 ways to setup your environment for this project:
1. Create free trail Databricks accout with express setup, you will get 40$ free credit for processing. The bad thing of this method is you cannot create external table because there is no cloud storage provided; Databricks only provides metastore.
2. Create free trail Databricks accout through AWS Marketplace. You can setup by following along the video online. But there are 2 things to keep in mind because these two is one of the reason that cause the error to link Databricks to AWS Marketplace when I tried to, and I don't know which one is actually the thing.
   - You use free trial of AWS
   - You create Databricks account in the Marketplace setup with existed Databricks account (i.e., you should create with the email that never regist to Databricks).
