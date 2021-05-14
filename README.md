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

## Step 4
