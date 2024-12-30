# Uber Data Analytics | Modern Data Engineering GCP Project

## Introduction
This project leverages modern data engineering principles on Google Cloud Platform (GCP) to perform comprehensive analytics on Uber ride data. We utilize image.ai for data extraction, BigQuery for storage and analysis, and Looker Studio for visualization, creating an end-to-end data pipeline from raw data to actionable insights. The project demonstrates efficient data processing and insightful reporting capabilities within the GCP ecosystem.

## Architecture
![Project Architecture](architecture.jpg)

## Technology Used
1. Programming Language - Python
2. Scripting Language - SQL
3. Google Cloud Platform
   -  BigQuery
   -  Cloud Storage
   -  Looker Studio
   -  Compute Instance
4. Mage.AI (modern data pipeline tool)

**Modern data Pipeline Tool:** https://www.mage.ai/

**Contribute to this project here:** https://github.com/mage-ai/mage-ai

## Dataset Used
TLC Trip Record Data
Yellow and green taxi trip records include fields capturing pick-up and drop-off dates/times, pick-up and drop-off locations, trip distances, itemized fares, rate types, payment types, and driver-reported passenger counts. 

Here is the dataset used in the video - https://github.com/darshilparmar/uber-data-engineering-mage-project/blob/main/data/uber_data.csv

### More Info About Dataset
1. Original Data Source - https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page
2. Data Dictionary - https://www.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf

## Data Model
![Data model image](data_model.jpeg)

## Scripts for project
1. [Extract Python File](mage-files/extract.py)
2. [Load Python File](mage-files/load.py)
3. [Transform Python File](mage-files/transform.py)
