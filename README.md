# CSandun WebApi Crud Template
This is a solution template for creating a simple CRUD ASP.NET Core Api for helping to create sample peoject every blogpost.
You can use this as a template or solution to create a simple Asp.Net sample Web Api application.


## Technologies
* Asp.Net Core 6
* Entity Framework Core 6
* SQL Server

## Getting Started
1. Install the latest .NET 6 SDK.
2. Run ```dotnet new --install  .\``` in Command Line from the projet root folder to install the project template.
3. Create a folder for your solution and cd into it (the template will use it as project name).
4. Run ```dotnet new csandun-webapi-crud --name <name of the solution>``` to create a new project.
5. Navigate to project folder and launch the project using dotnet run.


## Database Migrations
You can use below commands to migrate sample ```TodoItem``` entity into the database.

* This is can be use to update database in current state of the database

```dotnet ef database update --project <starting project name>```

* This command helps to create a new migration

```dotnet ef migrations add <migration comment> --project <starting project name> ```
