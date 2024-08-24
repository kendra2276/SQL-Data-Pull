# SQL-Data-Pull
This repository contains the SQL script used to create a program that exchanges patient test results with the Department of Health. The process involves pulling data from various tables in the database, cleaning and processing this data in Python, and then generating a HL7 file.  Lastly to err on the side of caution, the Python script will be omitted along with the acutal names of the tables in the database.

## Project Overview
This project is designed to extract and process data for generating Health Level 7 (HL7) messages, enabling seamless interoperability between the lab and the Department of Health. The HL7 program developed actively ensures compliance with health regulations, facilitating and enhancing public health monitoring and reporting. Lastly, each HL7 file went through rigours end to end testing with Department of Health. 

##  Data Sources
The SQL script pulls data from the following tables:

Order Table: Contains information on orders placed.
Results Table: Holds the results of the tests performed.
Assay Table: Provides details on the assays used.
Patient Table: Includes patient demographics and identifiers.
Physician Table: Contains information on the ordering physicians.
Practice Table: Lists the practices associated with the orders.


