# PySpark Overview

This project provides an overview of PySpark, demonstrating various operations and functionalities using the PySpark library.

## Setup

The project uses Poetry for dependency management. The main dependencies are:
```python
[tool.poetry.dependencies]
python = "^3.11"
pyspark = "^3.4.0"
notebook = "^6.5.4"
pandas = "^2.0.2"
```


## Getting Started

1. Create a SparkSession
2. Read data from various sources (CSV, Parquet)

## Features

- DataFrame creation and manipulation
- Data aggregation and grouping
- Joining datasets
- Using UDFs (User Defined Functions)
- Working with Spark SQL

## Examples

The project includes examples of:

- Reading and writing data
- Performing transformations
- Aggregating data
- Joining datasets
- Using broadcast joins for optimization

For detailed examples, refer to the Jupyter notebooks in the `code` directory.

## Documentation

The project includes documentation on various PySpark topics:

- SparkSession
- SQLContext
- UDFRegistration
- DataFrame
- GroupedData
- Column
- Catalog
- Row
- DataFrameNaFunctions
- DataFrameStatFunctions
- DataFrameReader
- DataFrameWriter
- CoGroupedData
- Types
- Functions
- avro.Functions
- Streaming

For more detailed information on each topic, refer to the `documentation.ipynb` file.
