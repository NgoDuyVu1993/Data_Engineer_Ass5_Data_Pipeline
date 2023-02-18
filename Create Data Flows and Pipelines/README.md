## Create Data Flow and Pipeline for "2021 Payroll" from Azure Data Lake to SQL Database
Before Creating Dataflow we must switch ON **Data flow debug** option that run on Spark to let the Data Factory get the data and debug </br>
![alt text](https://github.com/NgoDuyVu1993/Data_Engineer_Ass5_Data_Pipeline/blob/main/Create%20Data%20Flows%20and%20Pipelines/image/Turn%20ON%20Dataflow%20debug.jpg)

For the 2021 Payroll we must first create Data Flow </br>
![alt text](https://github.com/NgoDuyVu1993/Data_Engineer_Ass5_Data_Pipeline/blob/main/Create%20Data%20Flows%20and%20Pipelines/image/Create%20Payroll%202021%20Dataflow.jpg)

Then we created Pipeline to send data from Data Lake to SQL Database </br>
![alt text](https://github.com/NgoDuyVu1993/Data_Engineer_Ass5_Data_Pipeline/blob/main/Create%20Data%20Flows%20and%20Pipelines/image/Create%20Pipeline%20for%20Payroll%202021%20to%20SQLDB.jpg)

We can run debug on the pipeline to test if the pipeline can run successfully, We can check the pipeline by running SQL code on the target SQL Database table to check </br>
![alt text](https://github.com/NgoDuyVu1993/Data_Engineer_Ass5_Data_Pipeline/blob/main/Create%20Data%20Flows%20and%20Pipelines/image/Pipeline%202021%20Payrol%20to%20SQLDB%20Run%20Success.jpg)

## Create Data Flow and Pipeline for "2021 Payroll" from SQL Database to Synapse
Similarly with the first Data Flow and Pipeline, we do the same for data pipeline from SQL Database to Synapse. We first built the Data Flow </br>
![alt text](https://github.com/NgoDuyVu1993/Data_Engineer_Ass5_Data_Pipeline/blob/main/Create%20Data%20Flows%20and%20Pipelines/image/Create%20Payroll%20Dataflow%20from%20SQLDB%20to%20Synapse.jpg)

Build the Pipeline </br>
![alt text](https://github.com/NgoDuyVu1993/Data_Engineer_Ass5_Data_Pipeline/blob/main/Create%20Data%20Flows%20and%20Pipelines/image/Create%20Payroll%20Pipeline%20from%20SQLDB%20to%20Synapse.jpg)

Test the pipeline </br>
![alt text](https://github.com/NgoDuyVu1993/Data_Engineer_Ass5_Data_Pipeline/blob/main/Create%20Data%20Flows%20and%20Pipelines/image/Pipeline%20Payroll%20to%20Synapse%20Run%20Success.jpg)
## Create Data Flow and Pipeline for "Employee Master" from Azure Data Lake to Synapse
Build the Data Flow </br>
![alt text](https://github.com/NgoDuyVu1993/Data_Engineer_Ass5_Data_Pipeline/blob/main/Create%20Data%20Flows%20and%20Pipelines/image/Create%20Employee%20Dataflow.jpg)

Build the Pipeline </br>
![alt text](https://github.com/NgoDuyVu1993/Data_Engineer_Ass5_Data_Pipeline/blob/main/Create%20Data%20Flows%20and%20Pipelines/image/Create%20Employee%20Pipeline%20to%20Synapse.jpg)

Test the pipeline </br>
![alt text](https://github.com/NgoDuyVu1993/Data_Engineer_Ass5_Data_Pipeline/blob/main/Create%20Data%20Flows%20and%20Pipelines/image/Pipeline%20Employee%20to%20Synapse%20Run%20Success.jpg)

## Create Data Flow and Pipeline for "Agency Master" from Azure Data Lake to Synapse
Build the Data Flow </br>
![alt text](https://github.com/NgoDuyVu1993/Data_Engineer_Ass5_Data_Pipeline/blob/main/Create%20Data%20Flows%20and%20Pipelines/image/Create%20Agency%20Dataflow.jpg)

Build the Pipeline </br>
![alt text](https://github.com/NgoDuyVu1993/Data_Engineer_Ass5_Data_Pipeline/blob/main/Create%20Data%20Flows%20and%20Pipelines/image/Create%20Agency%20Pipeline%20to%20Synapse.jpg)

Test the pipeline </br>
![alt text](https://github.com/NgoDuyVu1993/Data_Engineer_Ass5_Data_Pipeline/blob/main/Create%20Data%20Flows%20and%20Pipelines/image/Pipeline%20Agency%20to%20Synapse%20Run%20Success.jpg)

## Create Data Flow and Pipeline for "Title Master" from Azure Data Lake to Synapse
Build the Data Flow </br>
![alt text](https://github.com/NgoDuyVu1993/Data_Engineer_Ass5_Data_Pipeline/blob/main/Create%20Data%20Flows%20and%20Pipelines/image/Create%20Title%20Dataflow.jpg)

Build the Pipeline </br>
![alt text](https://github.com/NgoDuyVu1993/Data_Engineer_Ass5_Data_Pipeline/blob/main/Create%20Data%20Flows%20and%20Pipelines/image/Create%20Title%20Pipeline%20to%20Synapse.jpg)

Test the pipeline </br>
![alt text](https://github.com/NgoDuyVu1993/Data_Engineer_Ass5_Data_Pipeline/blob/main/Create%20Data%20Flows%20and%20Pipelines/image/Pipeline%20Title%20to%20Synapse%20Run%20Success.jpg)

## Create Pipeline Load All Data into Synapse
We can combined all of the above Pipeline to a be single pipeline so that all of the pipeline can be run at once </br>
![alt text](https://github.com/NgoDuyVu1993/Data_Engineer_Ass5_Data_Pipeline/blob/main/Create%20Data%20Flows%20and%20Pipelines/image/Create%20Pipeline%20Load%20All%20Data%20into%20Synapse.jpg)

Test the pipeline </br>
![alt text](https://github.com/NgoDuyVu1993/Data_Engineer_Ass5_Data_Pipeline/blob/main/Create%20Data%20Flows%20and%20Pipelines/image/Pipeline%20Load%20All%20Data%20into%20Synapse%20Run%20Success.jpg)

## End of Create Data Flows and Pipelines
The following Data Flows and Pipelines are available in our Data Factory after we finished the forth step </br>
![alt text](https://github.com/NgoDuyVu1993/Data_Engineer_Ass5_Data_Pipeline/blob/main/Create%20Data%20Flows%20and%20Pipelines/image/All%20Dataflows%20and%Pipelines.jpg)
