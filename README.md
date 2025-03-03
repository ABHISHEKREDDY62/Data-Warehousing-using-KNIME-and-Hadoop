# Presidential Election Contributions 2020 - README

## Project Overview
This project focuses on creating a data warehouse for the 2020 U.S. Presidential Election Contributions dataset. The goal is to extract, transform, and load (ETL) data using KNIME and Hadoop, optimizing data storage and enabling efficient querying and visualization.


## Key Features
- **ETL with KNIME**: Processed over 1 million records, optimizing storage in PostgreSQL using schema-on-write.
- **Hadoop Implementation**: Implemented an ETL pipeline using Pig Latin and HiveQL to efficiently store and manage large-scale election data in HDFS.
- **Data Analysis & Reporting**: Developed interactive visualizations in KNIME to analyze campaign contribution trends, uncovering insights on candidates, donor occupations, and funding patterns.

## Data Pipeline
1. **KNIME ETL**:
   - Extracted data from CSV files.
   - Cleaned missing values and standardized formats.
   - Merged relevant fields (e.g., employer and organization fields).
   - Loaded structured data into PostgreSQL using a star schema.
2. **Hadoop ETL**:
   - Loaded CSV files into HDFS.
   - Processed data using Pig scripts to clean, transform, and extract necessary columns.
   - Stored processed data in Hive tables for querying.

## Business Insights
- Identified candidate popularity among students.
- Analyzed total contributions and number of transactions by state.
- Examined predominant donor occupations and employer affiliations.
- Determined which committees received the highest funds.
- Assessed state-wise contribution patterns over time.

## Tools & Technologies
- **KNIME**: ETL, data preprocessing, reporting, and visualization.
- **PostgreSQL**: Data warehouse storage using a structured star schema.
- **Hadoop (Pig & Hive)**: Distributed storage and large-scale data processing.

## Comparison: KNIME vs. Hadoop
| Feature               | KNIME Data Warehouse  | Hadoop (Pig & Hive) |
|----------------------|----------------------|----------------------|
| **Data Type**        | Structured (SQL-based) | Semi-structured & unstructured |
| **Processing**       | ETL using GUI workflows | Distributed batch processing |
| **Scalability**      | Suitable for medium datasets | Handles large-scale datasets efficiently |
| **Querying**        | SQL-based queries in PostgreSQL | HiveQL queries in Hadoop |
| **Visualization**    | Built-in reporting tools | External tools required |

## Conclusion
KNIME provided an intuitive and structured approach for ETL and visualization, making it ideal for structured data analysis. Hadoop enabled scalable storage and processing, making it suitable for handling large datasets. Both approaches provided valuable insights into the 2020 election contributions.

This repository contains all project files, workflows, and scripts for further exploration.
