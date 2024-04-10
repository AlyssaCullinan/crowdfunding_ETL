
# Crowdfunding ETL Project

We built an ETL pipeline using Python, Pandas, Python dictionary methods and regular expressions to extract and transform the data. After we transformed the data, we created four CSV files and used the data to create an ERD and a table schema. Finally, we uploaded the CSV files into a Postgres database.


## Features

* Extract the data from crowdfunding.xlsx

* Extract the data from contact.xlsx

* Transform the crowdfunding data into category and subcategory database table

* Transform the crowdfunding data into a campaign database table

* Transform the contact data into a contacts database table

* Load the tables into the crowdfunding_db database

* Verify that the data loads correctly in each table

## Notes
* crowdfunding_db_schema.sql is the SQL script for creating the SQL tables.

* ETL_Mini_Project_SBidkar_ACullinan.ipynb is the file where we extracted the data and created the dataFrames

* Resource folder contains the CSV files and xlsx files.

* Images folder contains the ERD diagram as well as examples of queries ran in pgAdmin4.

## Images 

### ERD Diagram 
![Crowdfunding_db_ERD](https://github.com/AlyssaCullinan/crowdfunding_ETL/assets/141466633/7727534e-1824-4038-b60d-277808fe52e8)

### Campaign Table
<img width="1499" alt="Campaign Table Data" src="https://github.com/AlyssaCullinan/crowdfunding_ETL/assets/141466633/52f60544-0d5b-49b7-aa06-4bb3069a2c15">

### Category Table
<img width="1023" alt="Category Table Data" src="https://github.com/AlyssaCullinan/crowdfunding_ETL/assets/141466633/14c910a8-a6d5-4485-a41f-4697fe96aec9">

### Subcategory Table
<img width="847" alt="Subcategory Table Data" src="https://github.com/AlyssaCullinan/crowdfunding_ETL/assets/141466633/137d33fc-450e-407b-96d5-d49feedb5632">

### Contacts Table
<img width="997" alt="Contacts Table Data" src="https://github.com/AlyssaCullinan/crowdfunding_ETL/assets/141466633/70736eb7-6651-4d36-b1fa-1b63f7adcaeb">


## Built With

* Python 
    * Modules
    * Pandas
    * JSON
    * Numpy
* Jupyter Notebook
* Postgres SQL
* pgAdmin4
* QuickDB.com

## Sources
* Google
* Chat GPT 
* In Class Activities

## Contributors
* Alyssa Cullinan
* Shubhangi Bidkar

