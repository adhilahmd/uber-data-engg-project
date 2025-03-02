# Uber data engineering project using gcp and mage
## Introduction
Implemented a data engineering project simulating Uber's data pipeline using Google Cloud Platform (GCP) and Mage, focusing on scalable data processing and analysis workflows.
## Architecture
![project_Architecture](architecture.jpg)
## Technology Used
* Programming Language-Python(pandas)
* SQL
* Google Cloud Platform
  * Cloud Storage
  * Compute engine
  * Bigquery
* Mage(Data pipeline tool) 
## Datasets Used
TLC Trip Record data
Trip records Includes Pickup and Dropoff Date/Time, Trip Distance, Pickup and Dropoff Locations, Fare, 
Rate Type, Payment Type and Passenger Count
## Link for the Datasets -- https://github.com/adhilahmd/uber-data-engg-project/blob/main/uber_data_raw.csv
## Data Model
![Data model image](data_model.jpeg)
## Python-pandas transform script
https://github.com/adhilahmd/uber-data-engg-project/blob/main/uber_transform_pandas.ipynb
## Mage script
1. [extract](mage/extract.py)
2. [transform](mage/transform.py)
3. [load](mage/load.py)
