# Loan-Risk-Analysis-PySpark

## Overview
Financial institutions such as banks and peer-top-peer lending platforms must evaluate the creditworthiness of applicants before approving loans. Incorrect decisions can increase the probablity of loan defaults, leading to significant financial losses.

This project implements a scalable Loan Risk Analysis Pipeline using PySpark to process customer and loan data, perform feature engineering, calculate risk indicators and generate outputs that can assist in loan approval decisions.

## Business Problem
Determine the risk associated with approving a loan by analyzing customer financial data and loan hostory. The generated insights can help financial institutions
- Approve or reject loan applications
- Categorize customers based on risk
- Recommend appropriate interest rates
- Reduce loan default rates

## Tech Stack
- Python
- Apache Spark (PySpark)
- SparkSQL
- Pytest
- Log4j
- Pipenv

## Project Architecture
Raw Data -> Data Ingestion -> Data Cleaning -> Feature Engineering -> Risk Score -> Calculation -> Output Dataset

## Project Structure
## 📂 Project Structure

```text
Loan-Risk-Analysis-PySpark/
|
├── 📁 configs/              # Configuration files (environment variables, webpack)
├── 📁 data/                 # input data used in project
├── 📁 docs/                 # Project documentation and assets
├── 📁 notebooks/            # Source code
├── 📁 src/                  # Main source code directory
├── 📁 tests/                # Automated unit and integration tests
├── 📁 output/               # Output files generated after analysis on data
└── README.md                 # Project overview and documentation
```

## Features
- Modukar PySpark application
- Config-drivenproject structure
- Logging using Log4j
- Unit testing with Pytest
- Reusable Spark session
- Feature engineering for loan risk assessment
- Clean and scalable codebase

## How to Run
```bash
# Clone the repository
git clone https://github.com/snehal2841/Loan-Risk-Analysis-PySpark.git

# Install dependencies
pipenv install

# Activate the virtual environment
pipenv shell

# Run the application
python scr/application.py

# Execute unit tests
pytest -v
```

## Project Workflow
1. Read customer and loan datasets.
2. Validate and clean the data.
3. Trasform and engineer relevant indicators.
4. Store processed results for downstream analysis.

## Future Enhancements
- Deploy the pipeline on AWS EMR/ Azure Databricks/ Google Dataproc.
- Automate Execution using Apache Airflow.

## Author 
Snehal Suryavanshi

