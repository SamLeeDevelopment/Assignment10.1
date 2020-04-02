# Assignment10.1
This is Assignment 10.1 for Advanced C# Programming (CIS174) at DMACC. This assignment covers Chapter 12, connecting to a database and using CRUD operations with EF Core.

Because this project uses a local database, the database will have to be re-initialized. To do that, execute the following commands in the Package Manager (PM) Console:

1) Initialize the database schema:
Add-Migration "InitialSchema"

2) Create the local database:
Update-Database
