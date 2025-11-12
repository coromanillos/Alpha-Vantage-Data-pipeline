Description: Cloud based ELT using Alphqa Vantage API Endpoints

Tech Stack: 
- Python (Extraction, Validation, and Loading into Azure Blob)
- Azure Blob (General Storage for incoming raw data, and transformations)
- Snowflake (For data warehousing, compute, transformations, analytics, and reporting)

Python Layer: Focus primarily on extarcting data from API, validation and type enforcement, before
loading it to Azure Blob.

Extract: Different Endpoints, of differing frequencies?
Some hisotrical, some daily..? How to reconcile?

Validation: Great Expectations, Type enforcement, run through schema like previously, or some other way..?

Load: Straightforward, load to Azure (ADLS Gen2), maybe the use of a python library 

Transform data within Azure via Snowflake       