# Create Data Flow and Pipeline for "2021 Payroll" from Azure Data Lake to SQL Database
Before Creating Dataflow we must switch ON **Data flow debug** option that run on Spark to let the Data Factory get the data and debug </br>
![alt text](https://github.com/NgoDuyVu1993/Data_Engineer_Ass5_Data_Pipeline/blob/main/Create%20Data%20Flows%20and%20Pipelines/image/Turn%20ON%20Dataflow%20debug.jpg)

For the 2021 Payroll we must first create Data Flow </br>
![alt text](https://github.com/NgoDuyVu1993/Data_Engineer_Ass5_Data_Pipeline/blob/main/Create%20Data%20Flows%20and%20Pipelines/image/Create%20Payroll%20Dataflow%20fromSQLDB%20to%20Synapse.jpg)

Then we created Pipeline to send data from Data Lake to SQL Database </br>

We can run debug on the pipeline to test if the pipeline can run successfully </br>

We can check the pipeline by running SQL code on the target SQL Database table to check </br>

# Create Data Flow and Pipeline for "2021 Payroll" from SQL Database to Synapse
Similarly with the first Data Flow and Pipeline, we do the same for data pipeline from SQL Database to Synapse. We first built the Data Flow </br>


Build the Pipeline </br>

Test the pipeline </br>

# Create Data Flow and Pipeline for "Employee Master" from Azure Data Lake to Synapse
Build the Data Flow </br>

Build the Pipeline </br>

Test the pipeline </br>
# Create Data Flow and Pipeline for "Agency Master" from Azure Data Lake to Synapse
Build the Data Flow </br>

Build the Pipeline </br>

Test the pipeline </br>
# Create Data Flow and Pipeline for "Title Master" from Azure Data Lake to Synapse
Build the Data Flow </br>

Build the Pipeline </br>

Test the pipeline </br>
# Create Pipeline Load All Data into Synapse
We can combined all of the above Pipeline to a be single pipeline so that all of the pipeline can be run at once </br>

Test the pipeline </br>