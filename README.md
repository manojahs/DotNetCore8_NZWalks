

![image](https://github.com/user-attachments/assets/b8d6659a-a61b-450c-8abf-a7198735da6a)

 <img width="839" alt="image" src="https://github.com/user-attachments/assets/a8f2e15e-f74f-4694-a9a7-2ce1afaf8d4f" />

```
DBcontext
----------
Are classes helps for to connect between models and database

Endpoints are routes that handle HTTP requests (e.g., GET /api/weather).



Appsetting.json
----------------
"ConnectionStrings": {
  "MyConnectionString": "Server=.;Database=NZWalksDb;Trusted_Connection=true;TrustServerCertificate=true"}
}

  "ConnectionStrings": {
    "NZWalksConnectionString": "Server=UI-5CG4126LGL\\MSSQLSERVER01;Database=NZWalksDb;Trusted_Connection=True;TrustServerCertificate=True"

  }

For Migration of db main thing we need to check is installed Nuget packages and sdk should be same verison and also check the connectionstring in appsetting.json


Dependency Injection
----------------------
Its Design pattern to increase maintainability , testability
Di container is responsible for creating and managing instances


Run EF Core Migration
--------------------
add-migration "name"
update-database

DTO(Data transfer Object)
-------------------------------
Used to transfer data between different layers
Typically contain a subset of the properties in the model
for example transferring data over a network





```
