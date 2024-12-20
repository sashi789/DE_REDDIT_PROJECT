# Reddit ETL Pipeline

A project that extracts data from Reddit using its API, processes it with Apache Airflow, and stores it efficiently in Amazon S3. This data is then cataloged with AWS Glue, queried using Amazon Athena, and loaded into Amazon Redshift for analytics. Docker is used to containerize and orchestrate the project.

---

## Features

- 🌐 **Extract Data from Reddit**: Using Reddit's API, extract subreddit posts based on custom filters.
- 🔄 **ETL Orchestration**: Manage ETL workflows using **Apache Airflow** and **Celery**.
- 📦 **Amazon S3 Integration**: Store extracted and transformed data efficiently.
- 🧠 **AWS Glue**: Catalog and transform data for seamless querying.
- 📜 **Amazon Athena**: Perform SQL queries directly on data stored in S3.
- 🏢 **Amazon Redshift**: Set up a Redshift cluster and load data for analytics.
- 🐳 **Dockerized Solution**: All services containerized with **Docker** for consistent and portable deployments.

---

## Architecture

Below is the high-level architecture diagram for the ETL pipeline:

![Architecture Diagram] (https://github.com/sashi789/DE_REDDIT_PROJECT/blob/226665f252285d1ed87921f68f0417fb96f2f9b2/RedditDataEngineering.png)

---

## Tech Stack

- **Programming Language**: Python
- **Workflow Orchestration**: Apache Airflow with Celery Executor
- **Data Storage**: Amazon S3
- **Data Cataloging**: AWS Glue
- **Data Querying**: Amazon Athena
- **Data Warehousing**: Amazon Redshift
- **Containerization**: Docker and Docker Compose
- **API**: Reddit API via PRAW

---

## Installation

### Prerequisites
- Python (v3.9 or later)
- Docker and Docker Compose
- AWS Account with necessary permissions for S3, Glue, Athena, and Redshift

### Clone Repository
```bash
git clone <your-repository-url>
cd <repository-folder>
