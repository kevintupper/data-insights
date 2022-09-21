# Data Insights

## Introduction (3 minutes)  

[Agenda page]

- Who am I and who is Ujval
- Goal for today
  - create onestop website for you which is
  - prescriptive with PaaS Storate and Analytics options
  - always available resource for data and analytics
  
- Agenda
  
  - Analtyics (5 minutes)
    - Continuum
    - Process and tools
  
  - Data stores (15 minutes)
    - Polyglot persistence
    - Azure Data Lake Gen2
    - Azure SQL Database
    - Azure Cosmos DB
  
  - Analytics Simplified (1 minute)
  
  - Synapse overview (10 minutes)

  - Synapse studio walk through (10 minutes)

  - Synapse demos (10 minutes)

## Analytics (5 minutes)

[Analytics continuum page]

- The analyticts continuum
  - What is analytics?
  - Walk through the continuum and maturity cycle

[Analytics page]

- The process and tools to get there  
- Why do we start with publish as 1?
- Inform about click-throughs for all the content
- Click-through publish, ingest, store, enrich

- Silos / different skills / as tools mature the lines blur
  
## Data stores (10 minutes)

[Data stores slide]

- Data stores conceptual (what, when, why)

- PaaS Options
  - Azure Data Lake Gen2 (3 minute overview) [ADLS G2 page]
  - Azure SQL Database (3 minute overview)  [Azure SQL page]
  - Azure Cosmos DB (3 minute overview)  [Cosmos DB page]

- 






## To Do

- Remove Data Stores from Nav
- Add pages for Azure Data Lake G2, Azure SQL Database, Cosmos DB to Analytics Simplified with Hot Spots
- Validate links to "learn"
- Synapse Image from Ujval with hot links
- Add good content to the Publish / Ingest / Data / Enrich pages.
- Add analytics continuum page and the 4 types of analytics.
- Verify each page works on Site-Index page and click through all links on each page to make sure all function
- Verify Image maps for all images.

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
 
  - Spark Serveless


## 10 minute demonstration - SWITCH STORY TO IOT FOR MINES  (10 minutes)

  - Spark Serverless  (notebooks)

    - Cosmos DB Data Store

      iot FROM 1 MINE - SIMULATING 50 SENSORS THROUGH OUT THE MINE
      HAVE 1 OF THEM SPIKE

    - HTAP

    - Analytics and visualizations inside Synapse VIA SPARK
    - REFERENCE THAT WE COULD ALSO DO IN POWER BI (REMIND THEM OF WHAT THEY JUST SAW)
  
    - Anamoly Detector
