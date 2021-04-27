## NAME: Dmitry Landy
## ASSIGNMENT: ASP.NET Chapter 10 HW
## DATE: 4/19/2021
---
**1. How are user authentication and authorization handled in ASP.NET?**
- Through Identity system

**2. What ASP.NET package supports the database functionality backing the identity system?**
- EntityFrameworkCore

**3. In our Sports Store application, what is the connection string that allows access to our identity database?**
- IdentityConnection

**4. What methods are required to configure the middleware that supports user authentication and authorization?**
- Another DBContext is added
- AddIdentity is added
- UseAuthentication
- UseAuthorization

**5. When you have multiple databases supporting one ASP.NET application, how do you ensure that specific components use the correct database?**
- You use the correct DBContext

**6. (not in book) In what namespace is the UserManager<T> class located? What is the purpose of the class? What interface(s) does the class require?**
- Part of Identity
- Provides the APIs for managing users 
- Implements IDisposable

**7. How are authentication credentials submitted to the application server? What services does the login manager use in submitting the authentication credentials?**
- POST Version of the login view
- SignInManger and UserManger authenticate the user 

**8. How does an ASP.NET application determine the environment in which it is running?**
-IWebHostEnvironment parameter in the Configure method

**9. How do you define configuration settings for different environments, such as development or production?**
- env.IsProduction checks if its the production environment

**10. (not in book) What is Docker? What is a container?**
- Docker automates the deployment of apps
- Containers are Paas technology that run within an operating system and contain apps.
