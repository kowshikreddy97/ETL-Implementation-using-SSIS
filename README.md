Objective
-
The objective of this homework is to perform an ETL task to extract the data from an OLTP database to a staging database that you have created. Then load the data into a data mart. The data mart is based on the star schema given below in Visio.

Schema and visio
-
![image](https://github.com/user-attachments/assets/f1f52ec0-f937-4a20-ad7f-506a245e419d)

Steps
-
- Created a StagingDB using SSMS.
- Created tables such as cust_staging and prod_staging in StagingDB using SSIS.
- Populated these tables in the staging area from the data in tablesof AdventureWorks.
  - cust_staging table (ContactID, FirstName, LastName, EmailAddress) data in your staging DB will come from Person.Contact table (in AdventureWorks - an OLTP DB).
  - prod_staging table (ProductID, Name, ListPrice, Weight) in your staging data will come from Production.Product table of the AdventureWorks
- Created a data mart and 2 dimensional tables DimCustomer, DimProduct using SSMS.
- Loaded data from staging table to dimensional tables using SSIS.

Tools and Techologies
-
- SSMS - SQL Server Management Studio
- SSIS - SQL Server Integration Services
- Visual Studio
- OLTP
- OLAP
