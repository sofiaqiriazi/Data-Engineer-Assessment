# Data-Engineer-Assessment
Welcome to the Data Engineer assessment. You have a total of three hours to complete the tasks as best as you can. 
Create a fork in your own Github account. <br />
Once complete, please send a link to your repository to @unhcr.org and CC: @unhcr.org <br />

FIRST TASK:

Create a data architecture plan.  <br />
Describe step by step how you would organise the data. How you would make sure the data is clean and as expected, how you would run tests and maintain the architecture. 
What are best practices which should be taken into account?

SECOND TASK:

The randomly created refugee dataset consists of the number of refugees per country of origin and country of asylum along with its process status. 
Use this as your data source and create an ETL pipeline which extracts data from a created database into a csv file.  <br />
The data is expected to be transformed by excluding "inactive" cases and adding an extraction date to the file. 

| variable | description | type | example |
| --- | --- |--- |--- |
| id       | unique identifier | string | "Cda88" |
| COOName       | country of origin | string | "Ethiopia" |
| CountryName       | country of asylum | string | "Sudan" |
| ProcessStatus       | process status of case | string | "Active" |


First step: Create a database to store the data using a Dimensional Modelled Design. <br />
            The expected output is a SQL script. 
            
Second step: Create a Python or R program that will run the above script and extract and load the data from the database into a csv file. 

Third step: Transform the data by excluding "erroneous" cases. Run checks to see if the data is complete and clean. 

Fourth step: Write a sql script which will state how many cases there are per country of origin (COOName) and Process Status. 


