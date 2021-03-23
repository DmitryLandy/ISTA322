## NAME: Dmitry Landy
## ASSIGNMENT: ASP.NET Chapter 7 HW
## DATE: 3/23/2021
---
**1. For the Sports Store application, what requirements does the author identify for implementation?**
- sports Products, users, admins, SQL Database

**2. What is the purpose of the Startup class in ASP.NET Core applications?**
- configuring the application

**3. What is the purpose of the ConfigureServices method in the Startup class?**
- Set up services for the app and accessed through dependency injection.

**4. What is a request pipeline and how does it work?**
- The path a HTTP request takes through the middleware in order to generate a response or modify it.

**5. What is the View Start class and how do we use it?**
- Specifies what layout file to use for Razor to minimize duplication

**6. What is the feature in ASP.NET Core that generates the database schema for us? What does the file created by this feature contain?**
- Entity Framework Core through migrations
- It contains the layout for the database.

**7. When ASP.NET Core sees that a controller instance needs to be created, and that the controller object required another object that implements some interface, how does it determine which interface should be implemented?**
- Through Dependency injection.

**8. Explain how the paging mechanism works. How does the application calculate the number of pages required? How is this data passed to the view?**
- Pagination allows data to be displayed on multiple pages 
- The controller class applies this in the view action method.
- Data is passed via the parameter for the view

**9. How does the book describe dependency injection? How is dependency injection used?**
- Allows an object to access another object via an interface without needing to know the specific implementation of that interface. 

**10. How are the routes in MapDefaultControllerRoute() method arranged? Why is this important?**
- In the order they are listed.
- If they are in the wrong order, there could be unexpected issues.