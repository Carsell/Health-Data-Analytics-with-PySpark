# Health-Data-Analytics-with-PySpark

This project focuses on cleaning and analyzing clinical trials data using PySpark. The dataset includes clinical trial information from multiple years, and the goal is to preprocess the data, handle inconsistencies, and prepare it for analysis. The project also integrates data from pharmaceutical companies to enhance the analysis.

## Table of Contents

- [Introduction](#introduction)
- [Project Structure](#project-structure)
- [Data Sources](#data-sources)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project uses PySpark to process and analyze clinical trials data from different years (2020, 2021, and 2023). The project includes functions to load, clean, and transform the data, as well as to integrate additional data from pharmaceutical companies. The main objectives are to clean and split the data, adjust row lengths, and convert RDDs to DataFrames for further analysis.

## Project Structure

The project consists of the following key components:

- **Data Loading:** Functions to load data from CSV files using PySpark.
- **Data Cleaning:** Functions to clean the data by removing unwanted characters and splitting the data into columns.
- **Data Transformation:** Functions to adjust row lengths and convert RDDs to DataFrames.
- **Analysis Preparation:** Preparing cleaned data for analysis by converting cleaned RDDs to DataFrames.

## Data Sources

The clinical trials data is sourced from CSV files for the years 2020, 2021, and 2023. Additionally, there is a CSV file containing data from pharmaceutical companies.

- `/FileStore/tables/clinicaltrial_2020.csv`
- `/FileStore/tables/clinicaltrial_2021.csv`
- `/FileStore/tables/clinicaltrial_2023.csv`
- `/FileStore/tables/pharma.csv`

## Setup and Installation

To run this project, you need to have the following dependencies installed:

- Python 3.x
- PySpark
- Pandas
- Seaborn
- Matplotlib

You can install the required Python packages using pip:

```sh
pip install pandas seaborn matplotlib pyspark
