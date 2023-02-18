## Create Summary table in Synapse for Payroll
To get the combine data of Payroll 2020 and 2021, we first create a new table call "Payroll Summary" </br>
![alt text](https://github.com/NgoDuyVu1993/Data_Engineer_Ass5_Data_Pipeline/blob/main/Aggregate%20Data%20Flow/image/Create%20Table%20in%20Synapse%20Analytics.jpg)

## Create ne Dataset for Azure Data Lake Gen2 folder that contains the historical files
After that, we must create a dataset within Data Factory </br>
![alt text](https://github.com/NgoDuyVu1993/Data_Engineer_Ass5_Data_Pipeline/blob/main/Aggregate%20Data%20Flow/image/Create%20dataset%20for%20historical%20file.jpg)
## Create new Data Flow
We create two block to get the Payroll data from SQL Database and Historical data, we must create parameter to filter the Fiscal Year </br>
![alt text](https://github.com/NgoDuyVu1993/Data_Engineer_Ass5_Data_Pipeline/blob/main/Aggregate%20Data%20Flow/image/Aggregation%20Dataflow.jpg)

We then create TotalPaid to calculate the total salary </br>
![alt text](https://github.com/NgoDuyVu1993/Data_Engineer_Ass5_Data_Pipeline/blob/main/Aggregate%20Data%20Flow/image/Set%20Total%20fomular.jpg)

After that, we set the Aggregate block </br>
![alt text](https://github.com/NgoDuyVu1993/Data_Engineer_Ass5_Data_Pipeline/blob/main/Aggregate%20Data%20Flow/image/Set%20the%20Aggregate%20Activity.jpg)

The final Data Flow </br>
![alt text](https://github.com/NgoDuyVu1993/Data_Engineer_Ass5_Data_Pipeline/blob/main/Aggregate%20Data%20Flow/image/Aggregation%20Dataflow.jpg)
## Create Pipeline
After creating the Data Flow, we can create Pipeline, the parameter must be created for Pipeline </br>

We run debug to test Pipeline </br>
![alt text](https://github.com/NgoDuyVu1993/Data_Engineer_Ass5_Data_Pipeline/blob/main/Aggregate%20Data%20Flow/image/Aggregation%20Pipeline%20Run%20Success.jpg)