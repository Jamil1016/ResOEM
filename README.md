# Data Processing Script

## Overview
This script processes various datasets related to **Actual Orders**, **Prior Orders**, **Shipments**, **Demand Planning**, and **Adjustments**. It consolidates, cleans, and structures the data for analysis.

## Features
- Reads and processes multiple datasets from a specified folder.
- Cleans and merges Actual and Prior Orders data.
- Applies adjustments based on residential data.
- Integrates Demand Plan data from **Demantra**.
- Generates a final cleaned dataset and exports it as a `.csv` file.

## Prerequisites
- Python 3.x
- Required libraries:
  ```sh
  pip install pandas pathlib chardet openpyxl