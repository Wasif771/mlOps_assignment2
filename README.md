# Assignment 2 - MLOps for Cloud Native Applications

## Project Title
Titanic Survival Prediction Pipeline using Apache Airflow and MLflow

## Overview
This project implements an end-to-end machine learning pipeline for Titanic survival prediction using **Apache Airflow** for workflow orchestration and **MLflow** for experiment tracking. The pipeline covers data ingestion, validation, preprocessing, encoding, model training, evaluation, branching logic, and model approval/rejection.

## Assignment Tasks Covered
- Task 1: DAG Design
- Task 2: Data Ingestion
- Task 3: Data Validation
- Task 4: Parallel Processing
- Task 5: Data Encoding
- Task 6: Model Training with MLflow
- Task 7: Model Evaluation
- Task 8: Branching Logic
- Task 9: Model Registration / Rejection
- Task 10: Experiment Comparison

## Project Structure
```text
assignment2_mlops/
├── airflow/
│   └── dags/
│       └── mlops_airflow_mlflow_pipeline.py
├── data/
│   └── Titanic-Dataset.csv
├── screenshots/
├── report/
│   └── technical_report.docx
├── requirements.txt
├── README.md
└── .gitignore
