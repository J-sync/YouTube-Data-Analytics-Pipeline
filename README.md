# YouTube Data Analytics Pipeline Using AWS Glue, AWS Wrangler, EMR, Apache Spark, Athena, QuickSight


## Overview

This project is designed to securely handle, organize, and analyze both structured and semi-structured data related to YouTube videos. The focus is on categorizing videos and understanding trending metrics.

## Project Objectives
1. Data Ingestion – Develop a system to collect data from multiple sources.
2. ETL Process – Transform raw data into a clean, structured format for analysis.
3. Data Lake – Centralize data storage from all sources in one repository.
4. Scalability – Ensure the system can handle increasing volumes of data.
5. Cloud Deployment – Use cloud infrastructure (AWS) to manage and process large-scale data efficiently.
6. Reporting – Create a dashboard to derive insights and answer key analytical questions.

## AWS Services Used
1. Amazon S3 – A scalable object storage service providing durability, availability, and security for data.
2. AWS IAM – Identity and Access Management service used to securely control access to AWS resources.
3. Amazon QuickSight – A serverless, machine learning-powered BI tool for creating dashboards and reports.
4. AWS Glue – A serverless data integration service that helps in data discovery, preparation, and combination.
5. AWS Lambda – A compute service to run backend code without provisioning or managing servers.
6. AWS Athena – A serverless, interactive query service that allows querying data directly from S3 without data loading.

## Dataset Description
The dataset is sourced from Kaggle and includes CSV files with daily trending YouTube video statistics across multiple regions. Each file corresponds to a specific country or region and contains information such as:

Video title
Channel title
Publish time
Tags
Views, likes, dislikes
Description
Comment count
Category ID (defined per region in a separate JSON file)

https://www.kaggle.com/datasets/datasnaek/youtube-new

## Architecture Diagram
<img src="architecture.jpeg">
