
# Automating an MLB Data Pipeline using Apache Airflow
  <img src="mlb_logo.png" alt="MLB logo">

## Overview
As a baseball enthusiast, I often wonder how sports networks such as ESPN, Bally, and Spectrum Sportsnet can provide viewers with intriguing statistics on their players instantaneously. 
It makes perfect sense once you realize that baseball spearheaded sports analytics, which is now considered by many as the antithesis to the traditional "eye test" that has managed sports 
since its creation. As portrayed in the legendary movie *Moneyball* (10/10, must watch before looking through this project), managers use statistical models based on player performances to make 
decisions such as lineup changes, trades, drafting, etc., all of which are core functions in running an organization.

In this project, I attempt to answer the new-age question, "How are these stats getting fed to me in real-time?" by creating and automating a 5-stage data pipeline that provides users with a continuous feed of player analysis throughout the season. 

## Apache Airflow




-  Automated a 5-stage data pipeline to track player metrics using MLB Data API and Apache Airflow. 
- Processed real-time data, structured JSON results, checked for quality, and analyzed pitching and hitting statistics with pandas. 
- Used PostgreSQL to store all processed and aggregated player information.
- Please refer to [this notebook](dag_creation.ipynb) for the creation of DAG's and pipeline architecture. 


## Packages Used

*Python 3.11*
- airflow
- requests
- json
- pickle
- numpy 
- pandas
- sci-kit learn
- psycopg2

*PostgreSQL*
- SQL

## Notes

As of the creation of this project, there is no Windows compatibility for Airflow. Please refer to this document for setting up 
Windows Subset for Linux (WSL) prior to running the DAGS on Airflow.









