# YoutubeDataAnalysis-DataEngineering-E2E
## Overview:
The goal of this project is to collect,transform and perform analysis on Youtube videos data (semi-structured and structured) based on certain metrics. Created an end-to-end data pipeline that includes ingesting data from multiple sources (ex. csv, json)  into Amazon S3 bucket(raw data) using Amazon CLI, converting json/csv files to parquet file format using AWS Glue and AWS Lambda, performing necessary transformations using Glue (created a crawler and performed analysis using Athena) and storing the cleansed/transformed data on S3 bucket. This data is then used to create visualizations using Amazon Quicksight to derive insights

## Services used:
1. Amazon CLI
2. Amazon S3
3. AWS Glue (Glue Catalog)
4. Amazon Athena
5. AWS Lambda
6. Aamazon Quicksight

## Dataset:
This Kaggle dataset contains statistics (CSV files) on daily popular YouTube videos over the course of many months. There are up to 200 trending videos published every day for many locations. The data for each region is in its own file. The video title, channel title, publication time, tags, views, likes and dislikes, description, and comment count are among the items included in the data. A category_id field, which differs by area, is also included in the JSON file linked to the region.

https://www.kaggle.com/datasets/datasnaek/youtube-new

## Architecture:
