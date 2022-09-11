# presentation-starter
Starter presentation template

## 15 MINUTES Intro
Home page 

What is Analytics?  (5)

Ingest . . . Publish walkthrough

Data storage options  (5)

- SQL Server Family

- Cosmos DB

- SQL Data Warehouse (Synapse Dedicated Pool)

- Data Lake  (UNSTRUCTURED DATA OR DATA YOU ARE NOT SURE HOW YOU WANT TO USE YET)
  
Synapse and Power BI - End-to-end Analytics (5)

Azure Synapse Analytics Overview

## 20 mintues  Demonstration  (20 minutes)

- Ingestion
  
  - Raw data (excel file to SQL)
  
      Description from UG of what was done for data flow and data cleansing.
        Explain Data Flow / Ingestion stored in Parquet Data Lake / SQL DW Dedicated
        - PowerBI hits dedicated SQL Pool running 
        - More optimized for reporting and dashboarding
  
        - Serverless more suited for data scientest / adhoc data exploration

      Parquet - queries show serverless against lake

      Dedicated - 

  - IoT Stream Simulation (Cosmos DB)
  
- Analysis

  - SQL Serverless

  - Dedicated SQL

  - Power BI Integration visualizations
    - Show
    - Desktop
    - Change / change back
    - Teams / Share
    - Web publish


## 10 minute demonstration - SWITCH STORY TO IOT FOR MINES  (10 minutes)

  - Spark Serverless  (notebooks)

    - Cosmos DB Data Store

      iot FROM 1 MINE - SIMULATING 50 SENSORS THROUGH OUT THE MINE
      HAVE 1 OF THEM SPIKE

    - HTAP

    - Analytics and visualizations inside Synapse VIA SPARK
    - REFERENCE THAT WE COULD ALSO DO IN POWER BI (REMIND THEM OF WHAT THEY JUST SAW)
  
    - Anamoly Detector
