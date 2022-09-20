# Data Insights

## To Do

- Remove Data Stores from Nav
- Add Azure Data Lake G2, Azure SQL Database, Cosmos DB to Analytics Simplified with Hot Spots
- Validate links to "learn"
- Synapse Image from Ujval with hot links
- Publish page
- Ingest page



# Agenda

Introduction (2 minutes)

- Ujval / Kevin

- Too much content (multi-day summit on just data/analytics to cover the topic)

- Goal to create onestop website for you which is
  - prescriptive with PaaS Storate and Analytics options
  - always available resource for data and analytics

- Describe content features of website

- Drive into presentation

Analytics (5 minutes)

- 1 - start with publish (3)
  - Define Analytics
  - Analytics continuum
  - Power BI beyond scope of presentation (will be showing in Demos though)
  - Review resources
  
- 2 - ingest (1)
  - Show page and brief conversation

- 3 - enrich, explore, disover (1)
  - Show page and brief conversation

Data stores (12 minutes)

- Azure Blob Storage

- Azure Data Lake Gen2
  - Data Lake  (UNSTRUCTURED DATA OR DATA YOU ARE NOT SURE HOW YOU WANT TO USE YET)
  - https://learn.microsoft.com/en-us/azure/storage/blobs/data-lake-storage-introduction
  - https://medium.com/awesome-azure/azure-difference-between-azure-blob-storage-and-azure-data-lake-storage-comparison-azure-blob-vs-adls-gen2-81af5ef2a6e1
  - https://www.linkedin.com/pulse/azure-data-engineering-series-part-1-blob-storage-vs-lake-grandy/

- SQL Family (PaaS)
  - SQL MI
  - Azure SQL
  - SQL Data Warehouse (Synapse)

- Cosmos DB
    - Azure store models

      - https://learn.microsoft.com/en-us/azure/architecture/guide/technology-choices/data-store-overview


Simplified Analytics (2 minutes)

Synapse slide (5 minutes)

Synapse environment (5 minutes)

Demos (10 minutes)



## 15 MINUTES Intro
Home page 

What is Analytics?  (5)

Ingest . . . Publish walkthrough

Data storage options  (5)


- SQL Server Family

- Cosmos DB

- SQL Data Warehouse (Synapse Dedicated Pool)

  
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
