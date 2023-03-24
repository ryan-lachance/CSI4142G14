# CSI4142 Group14

##Database SQL file
The Database SQL file
>csi4142g14.sql

##Imported csv files
The following files in this repository are the csv files we imported to extract data from. Their use can be found in the *datacleaning.py* file. 
>mh.csv
>sr.csv
>ur.csv

##Exported csv files
The following files are the cleaned data files exported from *datacleaning.py* file. 
>Mental Health.csv
>Suicide Rate.csv
>Unemployment Rate.csv

The following file is merged data of all three exported csv files from above, merged by *datamerge.py* file. This file's data is uploaded to the database 'merge' table with the *datamigration.py* file.
>master.csv

##SQL queries
All the SQL queries used to populate the dimensions and the fact table can be found in the following md file.
>SQLqeuries.md
