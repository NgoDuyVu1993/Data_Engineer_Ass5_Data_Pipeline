## Create Summary table in Synapse for Payroll

![alt text](https://github.com/NgoDuyVu1993/Data_Engineer_Ass5_Data_Pipeline/blob/main/Create%20Datasets/image/Create%20Datasets%20for%20Data%20Lake.jpg)

## Create ne Dataset for Azure Data Lake Gen2 folder that contains the historical files

## Create new Data Flow
We create two block to get the Payroll data from SQL Database and Historical data, we must create parameter to filter the Fiscal Year </br>

We then create TotalPaid to calculate the total salary </br>

After that, we set the Aggregate block </br>

## Create Pipeline
After creating the Data Flow, we can create Pipeline, the parameter must be created for Pipeline </br>

We run debug to test Pipeline </br>
