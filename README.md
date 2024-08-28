# SQL-Data-Pull
This repository contains the SQL script used to create a program that exchanges patient test results with the Department of Health. The process involves pulling data from various tables in the database, cleaning and processing this data in Python, and then generating a HL7 file. This overview includes only the SQL script for simplicity.

## Project Overview
This project is designed to extract and process data for generating Health Level 7 (HL7) messages, enabling seamless interoperability between the lab and the Department of Health. The HL7 format actively ensures compliance with health regulations, facilitating and enhancing public health monitoring and reporting. Additionally, HL7 standardizes the exchange of healthcare information, ensuring accurate and efficient communication across different systems and organizations.

##  Data Sources
The SQL script pulls data from the following tables:

Order Table: Contains information on orders placed.<br/>
Results Table: Holds the results of the tests performed.<br/>
Assay Table: Provides details on the assays used.<br/>
Patient Table: Includes patient demographics and identifiers.<br/>
Physician Table: Contains information on the ordering physicians.<br/>
Practice Table: Lists the practices associated with the orders.<br/>

## Automation
After rigours end to end testing with Department of Health, the script was then automated using a batch file and Task Scheduler with a run schedule of Monday through Friday. 
