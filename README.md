# Zillow Data Analytics (RapidAPI) | End-To-End Python ETL Pipeline

Welcome to the Zillow Data Analytics project! This comprehensive data engineering initiative takes you through the creation and automation of a Python ETL (Extract, Transform, Load) pipeline. The primary goal is to extract real estate properties data from the Zillow Rapid API, perform transformations, and visualize the insights. The entire workflow is orchestrated using Apache Airflow on the AWS cloud platform.

## Project Overview

1. **Data Extraction from Zillow Rapid API:**
   - Python scripts extract real estate data from the Zillow Rapid API.

2. **Data Loading to Amazon S3:**
   - Extracted data is loaded onto an Amazon S3 bucket.

3. **Triggering Lambda Functions:**
   - Lambda functions automate data transformation processes.

4. **Data Transformation and CSV Conversion:**
   - Transform data and convert it into a CSV file format.

5. **Secondary S3 Bucket Loading:**
   - Load transformed data into another S3 bucket.

6. **Apache Airflow Orchestration:**
   - Apache Airflow orchestrates the end-to-end workflow.

7. **S3KeySensor for Monitoring:**
   - Use the S3KeySensor operator in Apache Airflow to monitor data uploads to AWS S3.

8. **Amazon Redshift Integration:**
   - Load data into Amazon Redshift for storage and analysis.

9. **Amazon QuickSight Visualization:**
   - Connect Amazon QuickSight to the Redshift cluster for visualizing Zillow (Rapid API) data.

## Technologies Used

- **Apache Airflow:** Open-source platform for orchestrating workflows and data pipelines.
  
- **AWS Cloud Platform:** The entire project is implemented on the AWS cloud.

## Getting Started

1. **Installation:**
   - Follow the video guide to install Apache Airflow from scratch.

2. **Configuration:**
   - Set up AWS Lambda functions, Redshift, and QuickSight.

3. **Run the ETL Pipeline:**
   - Execute the Python scripts to run the end-to-end ETL pipeline.

##  Guide

Watch the step-by-step video guide to:

- Install Apache Airflow
- Schedule your ETL pipeline
- Use sensors in your ETL pipeline
- Set up AWS Lambda functions, Redshift, and QuickSight

## Note

This is a hands-on project.  Enjoy the learning journey!
