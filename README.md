# Commander
 Learning .NET core 3.1 WebAPI

1. Update connectionString in appSetting to Connect DB
```
"Server={Server_name};Initial Catalog={DB_name};User ID={User_ID};Password={User_Password};Trusted_Connection=True;"
``` 
3. Install EF Core Tools
```
dotnet tool install --version 3.1.23 --global dotnet-ef
```  
3. Update database
```
dotnet ef database update
```  
