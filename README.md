# Udacity-Data-Engineering-Nanodegree
## C1. Welcome to the Data Engineering Nanodegree Program
* Program Introduction: projects, pre-requisites, instructors, careers team, getting help..
* Introduction to Data Engineering
* What do data engineers do?

## C2. Data Modeling
* NoSQL Database: Apache Cassandra
* OLAP vs. OLTP
* Normalization, Denormalization
* Fact and Dimension tables
* Star and Snowflake Schema
* **Project 1: Data Modeling with Postgres** [Details](https://github.com/cc59chong/Data-Modeling-with-Postgres) <br>
 > This project builds a star schema in Postgres with fact and dimension tables for analytics. A Python ETL pipeline transfers data from local JSON files into these tables.
Apache Cassandra exercises: create tables, primary key, clustering column, where clause
* Apache Cassandra **exercises 1-4**: create tables, primary key, clustering column, where clause
* **Project 2: Data Modeling with Apache Cassandra** [Details](https://github.com/cc59chong/Data-Modeling-with-Apache-Cassandra) <br>
 > This project involves designing and implementing an ETL pipeline to analyze music streaming data using Apache Cassandra. The goal is to transform raw event data stored in CSV files into a structured database optimized for specific query patterns.
## C3. Cloud Data Warehouse
### L1. Introduction to Data Warehouse
* Data Warehouse
* Primary key, partition key, composite key, and clustering key
* Dimensional Modeling: Fact & Dimensions
* **Exercise 1: 3NF to Star Shema**
 > This exercise effectively demonstrates the practical process of converting a database from Third Normal Form (3NF) to a Star Schema. The key takeaway is the strategic denormalization of tables to optimize for analytical querying. By creating a central fact table (sales_fact) surrounded by descriptive dimension tables (dim_customer, dim_product, etc.), the resulting schema simplifies data retrieval and enhances performance for business intelligence tasks like sales analysis. This transformation highlights the fundamental difference between a schema designed for transactional efficiency (3NF) and one designed for analytical speed and simplicity (Star Schema).
* DWH Architecture: Kimball’s Bus Architecture, Independent Data Marts, Inmon’s Corporate Information Factory (CIF), Hybrid Kimball Bus & Inmon CIF
* Data marts
* OLAP Cubes and **exercises: Roll-up, Drill-down, Slice, Dice, query optimization**
* OLAP Cubes Technologies: MOLAP, ROLAP
* **Exercise 3: Column format in ROLAP**
### L2. Introduction to Cloud Computing and AWS
* Create an IAM Role, Security Group, an IAM User, Bucket
* Lunch and delete a Redshift Cluster
* Create PostgreSQL Database
### L3. Implementing Data Warehouse on AWS
* Redshift technology, Architecture, ETL
* **Exercise 1: Launch Redshift cluster**
* Infrastructure as Code (IaC)
* **Exercise 2: Creating Redshift Cluster using the AWS python SDK**
* **Exercise 3 Parallel ETL**
* Optimizing Table Design
* Distribution Style: Even, All, Auto, Key
* Sorting Key
* **Exercise 4: Table Design**
### L4. Project: Data Warehouse
 > This project designs and implements a cloud-based Data Warehouse on Amazon Redshift. It demonstrates an end-to-end ETL pipeline that extracts song and user activity data from files stored in an Amazon S3 bucket, stages and processes it in Redshift, and transforms it into a set of optimized dimensional tables (a star schema). 

