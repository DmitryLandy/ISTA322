## NAME: Dmitry Landy
## ASSIGNMENT: ASP.NET Chapter 2 HW
## DATE: 2/22/2021
---
**1. What is the difference between Visual Studio and Visual Studio Code?**

- VS is a traditional IDE for .NET app with a large range of tools, but it is resource-heavy and slow
- VSC i light-weight without so many features also very capable of handling .NET apps

**2. What is LocalDB?**

- Windows-only feature provided by SQL Server

**3. What do these commands do?**
```
dotnet new globaljson --sdk-version 3.1.101 --output FirstProject
dotnet new mvc --no-https --output FirstProject --framework netcoreapp3.1
```
- creates a new MVC project

**4. What command do you use to build an ASP.NET project from the command line? What command do you use to run the project?**

```dotnet net```
```dotnet run ```

**5. What is the purpose of an endpoint?**

- To handle incoming requests. 

**6. What is a controller?**

- C# class that is derived from the Microsoft.AspNetCore.Mvc.Controller class, the built-in controller base class.

**7. Where are actions defined?**

- In controllers

**8. What is the purpose of the routing system?**

- Selects which endpoint will handle the incomming request.
- Its a rule.

**9. Assume that your ASP.NET application runs in a browser with a URL like http://localhost:5000. List the three default routes configured by the ASP.NET Core routing system.**

- http://localhost:5000/
- http://localhost:5000/Home
- http://localhost:5000/Home/Index

**10. What does the ViewResult object instruct ASP.NET Core to do?**

- It returns or renders a view.

**11. How does ASP.NET Core know what View is to be called from an action method?**

- By specifying the parameter in the View() method.

**12. What is the job of an action method?**

- to perform an action for the controller to work with.

**13. What is a view model?**

- The data provided to the view.
