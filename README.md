# Serverless Data Integration Pipeline: Transport Tube API to Snowflake's Data Cloud

## Description

The main objective of this project is to create a data integration pipeline that extracts data from the Transport Tube API and loads it into Snowflake's Data Cloud using a serverless architecture. The project involves several components and tools, including Fivetran for data extraction, AWS Lambda for serverless function execution, AWS SAM for local testing and deployment, and GitHub for code management.

## Architecture

<img width="1122" alt="Screen Shot 2023-11-01 at 1 14 18 PM" src="https://github.com/sneha-roseline/fivetran/assets/146040464/21b8e223-0c2c-4b8f-8167-d8c6e442b2ef">

## Tech Stack
* ETL Tool - **[Fivetran](https://www.fivetran.com/)**
* Destination for loading the source data - **[Snowflake](https://www.snowflake.com/en/data-cloud/what-is-data-cloud/)**
* Serverless function to call the API - **[AWS Lambda](https://aws.amazon.com/lambda/)**
* Writing and deploying code - **[Visual Studio Code](https://code.visualstudio.com/)**
* Testing Lambda function locally, packaging and deploying the function to AWS - **[AWS SAM CLI](https://aws.amazon.com/serverless/sam/)**

## Deployment

