# Uber Data Analytics | Modern Data Engineering Project on GCP

## Introduction

This project demonstrates how to perform data analytics on Uber ride data using modern cloud tools and technologies. Leveraging Google Cloud Platform (GCP), the pipeline facilitates scalable data storage, processing, analysis, and visualization. Technologies such as GCP Storage, Python, Compute Instances, Mage for data pipeline orchestration, BigQuery for querying large datasets, and Looker Studio for visualization are key components.

## Project Architecture

The architecture involves ingesting Uber trip data into GCP Storage, processing the data on Compute Instances using Python and Mage AI, and storing the results in BigQuery. Visualizations are created in Looker Studio to provide actionable insights.

<img src="architecture.jpg">

## Technology Used
Programming Language
- Python : Core programming language used for data manipulation, analysis, and pipeline scripting.

Google Cloud Platform
- Google Cloud Storage : Centralized cloud storage solution for raw data.
- Compute Instance : Virtual Machine for processing data using Python scripts and Mage AI. 
- BigQuery : GCP's fully-managed data warehouse for storing and querying large datasets.
- Looker Studio : Business intelligence platform for creating interactive dashboards and reports.

Data Pipeline Tool 
- Mage AI : An open-source data pipeline tool used to orchestrate the data flow, transforming raw Uber trip data into actionable insights.

Contribute to Mage AI - https://www.mage.ai/

Contibute to this open source project - https://github.com/mage-ai/mage-ai


## Dataset Used
The project uses TLC Trip Record Data, which includes detailed information on yellow and green taxi trips in New York City. This dataset provides comprehensive insights into:

- Pickup and drop-off times and locations
- Trip distances
- Fares and payment methods
- Passenger counts 

Dataset Access - https://github.com/dutta30arka/uberstream-etl-pipeline-project/blob/main/data/uber_data.csv

More information about dataset can be found here:
1. Website - https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page
2. Data Dictionary - https://www.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf

## Data Model

The data model outlines how Uber trip data is structured and processed. It involves organizing trips by date, location, fare breakdown, and other essential metrics for efficient querying and reporting in BigQuery.

<img src="data_model.jpeg">
