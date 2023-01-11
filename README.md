# Load-data-into-the-IBM-Db2-database-from-a-CSV-file
In order to work with the data we must know how to load the data in IBM Db2 database from a CSV file. 
The dataset used in this repository comes from the following source: https://www.kaggle.com/antfarol/car-sale-advertisements under a CC0: Public Domain license. We are using a modified subset of that dataset for this lab.
1) Go to: https://cloud.ibm.com/catalog/services/db2 to access your Db2 dashboard on Cloud.
2) Logging in will take you to your **Db2 service dashboard**.
3) The **Manage** tab will be active by default in your services dashboard. Click on** Go to UI.**
4) Click on **Load** > **Load Data**
5) **Drag** or **upload** your files 
6) The name of the CSV file you have uploaded will appear in the **Selected** file section on the right.
7) Click **Next** to proceed.
8) You will be asked to select a **Schema** from a list of schema names.
9) Click on **New Table**.
10) Enter the name **CARSALESTABLE** in the input box prompting you with **NEW TABLE NAME**.
11) Now click on **Create** to create the new table.
12) A table by the name of **CARSALESTABLE** has been created.
13) Click **Next** at the bottom right of the page to proceed.
14) Then click **Begin Load** to begin the process of loading the data from the CSV into your database.
15) Data from your CSV file is now loaded into your Db2 instance.
