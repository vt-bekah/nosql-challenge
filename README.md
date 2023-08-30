# nosql-challenge
This repository contains challenge files for UT DAV Bootcamp Module 12 NSQL Databases

# File Notes
* Resources folder contains the data that must be loaded prior to executing any of provided code
  * establishments.json contains the data provided in BCS for this challenge. Use the following command in terminal to import the data: <br>
    mongoimport --type json -d uk_food -c establishments --drop --jsonArray establishments.json
* NoSQL_setup.ipynb was based off NoSQL_setup_starter.ipynb to complete the solution for Part 1: Database and Jupyter Notebook Set Up & Part 2: Update the Database of the challenge
* NoSQL_analysis.ipynb was based off NoSQL_analysis_starter.ipynb to complete the solution for Part 3: Exploratory Analysis
* Starter_Code folder contains the files provided in BCS/Canvas for completing the challenge.

    
# Challenge Instructions are written within the jupyter files  


# References
* The following links were used as references to implement a query using $geoWithin
    * https://stackoverflow.com/questions/25734092/query-locations-within-a-radius-in-mongodb
    * https://www.mongodb.com/docs/manual/reference/operator/query/geoWithin/#mongodb-query-op.-geoWithin
    * https://www.mongodb.com/docs/manual/reference/operator/query/centerSphere/#mongodb-query-op.-centerSphere


# Getting Started

## Prerequisites
You must have python, jupyter notebok / lab, conda, pandas 

## Cloning Repo
$ git clone https://github.com/vt-bekah/nosql-challenge.git

$ cd nosql-challenge

# Built With
* Python v3.10.11
* jupyter notebook v6.5.2
* jupyterlab v3.6.3
* conda v23.5.0

**Python Modules**
* pandas v1.5.3
* pymongo v3.12.0
* pprint 

