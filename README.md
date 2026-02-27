# PySpark Income Classification Pipeline

## Overview
This project builds a distributed machine learning pipeline using PySpark to classify income levels based on demographic and employment features. It demonstrates scalable preprocessing, feature engineering, and model training using Spark ML.

## Dataset
- UCI Adult Income Dataset
- Binary target: <=50K or >50K

## Workflow
- Data loading using Spark
- Handling missing values
- Categorical encoding (StringIndexer + OneHotEncoder)
- Feature vector assembly
- Train/Test split
- Model training using Spark ML
- Model evaluation

## Technologies Used
- PySpark
- Spark ML
- Python

## Key Skills Demonstrated
- Distributed data processing
- Scalable ML pipeline creation
- Feature engineering in Spark
- Model evaluation in big data environment

## How to Run
1. Install PySpark:
   pip install pyspark
2. Run:
`spark_income_ml_pipeline.ipynb`
