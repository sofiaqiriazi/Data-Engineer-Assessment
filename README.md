# Data-Engineer-Assessment
Welcome to the Data Engineer assessment. You have a total of three hours to complete the tasks as best as you can. 
Create a fork in your own Github account.
Once complete, please send a link to your repository to @unhcr.org and CC: @unhcr.org


Main task:

The randomly created refugee dataset consists of the number of refugees per country of origin and country of asylum along with its process status. 

| variable | description | type | example |
| --- | --- |--- |--- |
| id       | unique identifier | string | "Cda88" |
| COOName       | country of origin | string | "Ethiopia" |
| CountryName       | country of asylum | string | "Sudan" |
| ProcessStatus       | process status of case | string | "Active" |

Create an ETL pipeline which extracts data from a created database into a csv file. 
The data is expected to be transformed by excluding "inactive" cases and adding an extraction date to the file. 

First task: Create a database to store the data using a Dimensional Modelled Design. (MSSQL / MySQL / Postgres).
            The expected output is a SQL script. 
            
Second task: Create a Python or R program that will run the above script and extract and load the data from the database into a csv file. 

Third task: Transform the data by excluding "erroneous" cases. 

Fourth task: Write a sql script which will state how many cases there are per country of origin (COOName) and Process Status. 


