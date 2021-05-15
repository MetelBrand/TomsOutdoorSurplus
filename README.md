# TomsOutdoorSurplus
This is a build of a demo MVC app from Adam Freeman's ASP.NET Core 3 Textbook. This is for the purpose of demonstration.

## Link
This is an exercise in Adam Freeman's Pro ASP.NET Core 3, Eighth Edition. For more information, follow this link: https://www.apress.com/gp/book/9781484254394.

## Chapter 7
## Build Powershell Script

```
dotnet new globaljson --sdk-version 5.0.201 --output TomsOutdoorSurplusSln/OutdoorProducts
dotnet new web --no-https --output TomsOutdoorSurplusSln/OutdoorProducts --framework net5.0
dotnet new sln -o TomsOutdoorSurplusSln
dotnet sln TomsOutdoorSurplusSln add TomsOutdoorSurplusSln/OutdoorProducts
dotnet new xunit -o TomsOutdoorSurplusSln/OutdoorProducts.Tests --framework net5.0
dotnet sln TomsOutdoorSurplusSln add TomsOutdoorSurplusSln/OutdoorProducts.Tests 
dotnet add TomsOutdoorSurplusSln/OutdoorProducts.Tests reference TomsOutdoorSurplusSln/OutdoorProducts
```
## Step 2 
Project running after inital configuration
![image](https://github.com/MetelBrand/TomsOutdoorSurplus/blob/master/Images/sportsStore1.png)
## Step 3
*What is Entity Framework?*

It is Microsoft's Object-to-Relational Mapping (ORM) framework. It is used to link databases and web applications together.

*What is a Connection String?*

A connection string points your code toward a database to migrate to. It is comprised of all the applicable information to connect to and access the database.

*What is a Database Context?*

While connection strings allow for connection, Database Context is essentially a specific reference
to the database that allows integration of the program Models to the database tables.

*What is a Model Repository?*

The repository layer separates the Business layer from the Data Access Layer.

*Migration vs Scaffolding?*

Migration parses the C# Model data and plugs it into a database; Scaffolding takes a database and
generates model code off of the data that adheres to MVC conventions.

*Seeding the database:*
![image](https://github.com/MetelBrand/TomsOutdoorSurplus/blob/master/Images/sportsStoreStep4.0.png)
## Step 4
Added page links, tests and styling
![image](https://github.com/MetelBrand/TomsOutdoorSurplus/blob/master/Images/sportsStore%20Step%204.1.png)
![image](https://github.com/MetelBrand/TomsOutdoorSurplus/blob/master/Images/sportsStore%20Step%204.2.png)
![image](https://github.com/MetelBrand/TomsOutdoorSurplus/blob/master/Images/sportsStore%20Step%204.3.png)

## Chapter 8
### Step 2: Add, Filter, and Highlight Category
![image](https://github.com/MetelBrand/TomsOutdoorSurplus/blob/master/Images/sportsStore%208.0.png)
### Step 3: Add Shopping Cart and Session data
![image](https://github.com/MetelBrand/TomsOutdoorSurplus/blob/master/Images/sportsStore%208.1.png)
![image](https://github.com/MetelBrand/TomsOutdoorSurplus/blob/master/Images/sportsStore%208.2.png)
### Step 4: Expanded Test Explorer Displaying All Unit Tests
![image](https://github.com/MetelBrand/TomsOutdoorSurplus/blob/master/Images/sportsStore%208.3.png)






