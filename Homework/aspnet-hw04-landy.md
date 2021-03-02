## NAME: Dmitry Landy
## ASSIGNMENT: ASP.NET Chapter 4 HW
## DATE: 3/1/2021
---
**1. What are the .NET SDK command line tools used for? Is their use required? Why or why not?**
- Provides access to all features of ASP.NET core developement. 
- Depending on the features, CLI might have to be used because IDEs (VS, VSC) have limitations

**2. What kind of applications do the following templates create? Run these commands and read the documentation. A brief summary of each template is sufficient.**
```
dotnet new console --help ||| This is a new Console App
dotnet new mvc --help ||| This is a new MVC app
dotnet new web --help ||| This is a new Web app
```
**3. What, specifically, do the following commands do?**

Creates a template for a project
```
dotnet new globaljson --sdk-version 3.1.101 --output MySolution/MyProject
```
Creates a new web app in the project file
```
dotnet new web --no-https --output MySolution/MyProject --framework netcoreapp3.1
```
creates new solution
```
dotnet new sln -o MySolution 
```
adds solution file to the project file 
```
dotnet sln MySolution add MySolution/MyProject
```

**4. What is the purpose of the global.json file?**
- Specifies version of the .NET core 

**5. What does the method app.UseStaticFiles() do?**
- uses static content in wwwroot folder

**6. What do the following two commands do?**
```
dotnet build
dotnet run
```
- Builds and runs a program respectively

**7. (not in book) You can manage pacakges using the NuGet package manager and the command line tool dotnet add package. What are packages and what are they used for.**
- Packages are additional files that are used to extend the functionality of the project.

**8. What are tool packages and what are they used for?**
- commands for the CLI to perform operations on .NET projects

**9. What are tool packages and what are they used for?**
**10. What are client side packages and what are they used for?**
- Contain content that is delivered to the client (Images, CSS stylesheets, static HTML, etc).

**11. List two ways that a developer can debug code.**
- Using a debugger
- Add additional code that prints values 
