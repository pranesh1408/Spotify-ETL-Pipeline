# Spotify Data ETL Pipeline

An automated ETL pipeline that fetches Spotify's global trending songs and processes them using AWS cloud services.

## 🎵 Overview

This project builds a complete data pipeline for Spotify's trending music data, from extraction to analytics-ready storage in Snowflake.

## 🏗️ Architecture

**Extract** → **Transform** → **Load**
- **AWS Lambda** (Python) → **S3** → **Snowflake**

## 🛠️ Tech Stack

- **Language**: Python
- **Cloud Platform**: AWS (Lambda, S3, Triggers)
- **Data Warehouse**: Snowflake
- **APIs**: Spotify Web API
- **Data Ingestion**: Snowpipe

## 📊 Pipeline Flow

1. **Extraction**: AWS Lambda function fetches trending songs via Spotify API
2. **Storage**: Raw data stored in S3 bucket
3. **Transformation**: Second Lambda function processes and cleans data
4. **Automation**: AWS triggers automate the extraction and transformation
5. **Loading**: Snowpipe automatically loads transformed data to Snowflake

## ⚡ Key Features

- **Fully Automated**: Trigger-based execution
- **Cloud-Native**: Built entirely on AWS infrastructure
- **Scalable**: Serverless Lambda functions handle varying data loads
- **Real-time**: Continuous data pipeline for trending songs
- **Analytics-Ready**: Data structured for business intelligence

## 🚀 Setup

1. Configure AWS Lambda functions
2. Set up S3 buckets for raw and processed data
3. Configure Spotify API credentials
4. Establish AWS-Snowflake integration
5. Set up Snowpipe for automated loading

---
**Built with**: Python | AWS Lambda | S3 | Snowflake | Spotify API
