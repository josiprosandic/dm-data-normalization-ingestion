# Data normalization, cleaning and ingestion 
This project was part of the Data Management (Datenbanken) course at Graz University of Technology.

## Functionality
This projects' main technology is Python and it's modules. Main goal was to make a Python script which takes a huge .csv file with lots of records, normalizes it respecting all normalization rules for the relational databases (dependencies, data types, normal forms...) and ingests it into the relational MySQL database.

One of the main requirements was to make processing time as low as possible. 

Python script inputs:
* AthleteEvents.csv (formatted to xlsb in order to reduce files' size)
* HostCities.csv
* NOCRegions.csv
