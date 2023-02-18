# Create an Azure Data Lake Gen2 (Storage Account)
The first resource that is needed to be create is Azure Data Lake Gen2 where the csv files will be uploaded. When creating the resource, the option "Enable Heirarchical Namespaces" must be ticked. </br>
![alt text](https://github.com/NgoDuyVu1993/Data_Engineer_Ass5_Data_Pipeline/blob/main/Create%20Azure%20Resources/image/Creating%20Azure%20Data%20Lake%20Gen2%20with%20Heirarchical%20Namespaces.jpg)
After the Storage account is created, we created a Blog container </br>
![alt text](https://github.com/NgoDuyVu1993/Data_Engineer_Ass5_Data_Pipeline/blob/main/Create%20Azure%20Resources/image/Create%20Blog%20Container%20within%20Data%20Lake%20Gen2.jpg)
We then created 3 directories within the Blog container </br>
![alt text](https://github.com/NgoDuyVu1993/Data_Engineer_Ass5_Data_Pipeline/blob/main/Create%20Azure%20Resources/image/Create%20Directory%20within%20Blog%20Container.jpg)
We then uploaded the csv files from local machine to the directories in Blog container </br>
![alt text](https://github.com/NgoDuyVu1993/Data_Engineer_Ass5_Data_Pipeline/blob/main/Create%20Azure%20Resources/image/Upload%20Files%20to%20Directories.jpg)

# Create Azure Data Factory Resource
The second Azure Service is Data Factory </br>
![alt text](https://github.com/NgoDuyVu1993/Data_Engineer_Ass5_Data_Pipeline/blob/main/Create%20Azure%20Resources/image/Create%20Data%20Factory.jpg)

The Data Factory workspace can be access after it was created </br>
![alt text](https://github.com/NgoDuyVu1993/Data_Engineer_Ass5_Data_Pipeline/blob/main/Create%20Azure%20Resources/image/Access%20Data%20Factory.jpg)

# Create SQL DB resource and table
The SQL DB is created to host the tables. </br> 
![alt text](https://github.com/NgoDuyVu1993/Data_Engineer_Ass5_Data_Pipeline/blob/main/Create%20Azure%20Resources/image/Create%20SQL%20Database.jpg)

Before we can access the SQL DB to create tables, we must configure the Firewall of the service by adding our IP address. We can do this by adding the IP to Firewall setting.</br>
![alt text](https://github.com/NgoDuyVu1993/Data_Engineer_Ass5_Data_Pipeline/blob/main/Create%20Azure%20Resources/image/Setup%20IP%20address%20for%20SQL%20DB%20firewall.jpg)
Or the database will ask to add the IP Address when we first login </br>
![alt text](https://github.com/NgoDuyVu1993/Data_Engineer_Ass5_Data_Pipeline/blob/main/Create%20Azure%20Resources/image/Add%20IP%20address%20when%20Login%20to%20SQL%20Database.jpg)
After our IP address is added successfully we can create table in SQL Database </br>
![alt text](https://github.com/NgoDuyVu1993/Data_Engineer_Ass5_Data_Pipeline/blob/main/Create%20Azure%20Resources/image/Create%20table%20within%20Azure%20Query%20Editor.jpg)

# Create Synapse Analytics workspace and SQL pool with data tables
The Azure Service that we need is Synapse Analytic, We must first create Synapse Analytics workspace. </br>
![alt text](https://github.com/NgoDuyVu1993/Data_Engineer_Ass5_Data_Pipeline/blob/main/Create%20Azure%20Resources/image/Create%20Synapse%20Workspace.jpg)
We create Dedicated SQL Pool in Synapse Analytics workspace </br>
![alt text](https://github.com/NgoDuyVu1993/Data_Engineer_Ass5_Data_Pipeline/blob/main/Create%20Azure%20Resources/image/Create%20SQL%20Dedicated%20Pool.jpg)
We can run SQL code on Dedicated SQL Pool to create tables, notice to set the **Connect to** to SQL Pool </br>
![alt text](https://github.com/NgoDuyVu1993/Data_Engineer_Ass5_Data_Pipeline/blob/main/Create%20Azure%20Resources/image/Create%20Tables%20in%20SQL%20Dedicated%20Pool.jpg)
We can see the created table in the Workspace </br>
![alt text](https://github.com/NgoDuyVu1993/Data_Engineer_Ass5_Data_Pipeline/blob/main/Create%20Azure%20Resources/image/Tables%20in%20SQL%20Dedicated%20Pool.jpg)

# End of Create and Configure Resources
The following resources are available in our resource group after we finished the first step </br>
![alt text](https://github.com/NgoDuyVu1993/Data_Engineer_Ass5_Data_Pipeline/blob/main/Create%20Azure%20Resources/image/Services%20Created%20in%20Resource%20Group.jpg)