# CrunchBase Startup Data Analysis using Apache Spark

The startup ecosystem is very vibrant and throbbing. Every day, novel technolo-
gies are emerging and innovative companies get founded, on the other hand, some
companies get sold, and some even get shut down for good. It is a fast-paced world
where entrepreneurs and businesses are always striving to build and develop the next
big idea. With that in mind,this technical project is intended to perform data analysis on CrunchBases 2015 database.CrunchBase is the biggest startup ecosystem database. The 2015 database is freely available online through the
following link: https://github.com/notpeter/crunchbase-data/archive/master.zip
Crunchbase data contains crowdsourced information on a large number of startups
including who invested in them and how much. Specifically, this dataset contains 5
unique CSV worksheets with a single table in each one of them.

This project aims to tackle the project objectives by following the given steps.
1. Data cleaning and preparation using OpenRefine.
2. Installation of Hadoop and Spark.
3. Distributed storage and cluster processing of the data (Hadoop yarn + Spark
or Spark standalone with Hadoop platform).
4. Exploratory data analysis using Spark data frames.
5. Data mining and pattern extraction using Spark SQL, Dataframes and RDD.
6. Visualization

Project Objectives and Goals
1. Which were the top 20 Companies that received largets funding
2. What type of funding degenerated the most money?
3. Who are the top 20 investors in the last decade?
4. Which were the business sectors in growth before the 21st century and after 2000 and its comparision?

# GitHub repository details - Home directory.
1. Cleaned Data   : this folder contain all cleaned data sets.
2. Data cleaning  : folder contain python files for data cleaning corresponding to each data set.
3. Exploratory-Data-Analysis : This folder contains ipython note book files for exploratory data analysis.
4. crunch-base-dataset : The raw dataset used for the project.
5. documents  : Documentation of step by step instalation and configuration of Hadoop, Spark and Jupyter.
6. plots  : plots and visualization generated in the project.
7. decision-tree.ipynb : code for decision tree implementation.
8. regression.ipynb : code for linear regression.
9. sparkSQL-1.ipynb : answers to project objective using SparkSQL.
10. sparkSQL-2.ipynb : answers to project objective using sparkSQL.
