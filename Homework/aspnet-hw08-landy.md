## NAME: Dmitry Landy
## ASSIGNMENT: ASP.NET Chapter 7 HW
## DATE: 3/23/2021
---
**1. For chapter 8 of the ASP.NET Core 3 book, what are the three requirements as the quthor describes them?**

- Index action of home controller filters product in repository
- enhance url scheme
- create sidebar

**2. When adding new routes in Startup.cs, in what order should you add the new routes? Why?**

- In the order you want them executed

**3. Does ASP.NET Core 3 handle outgoing HTTP requests as well as incoming requests? If so, what is one reason that this is important?**

- yes
- You can create a scheme that keeps URLs consistent

**4. What is a view component? Why do you use view components?**

- partial views
- they are small and reusable sections of logic

**5. When you use a view component in a view, how is the view component referenced, and what nameing convention do you use?**

- uses the <vc> tag

**6. When ASP.NET Core 3 needs to create a instance of a component, how does it know what value to give the new instance?**

- Through the Constructor's parameter list

**7. How do ASP.NET Core 3 components get information about a user’s current HTTP request? Why would it be important for the component to get this information?**

-  The RouteData property
- This allows the appropriate info to be returned

**8. What does the PathAndQuery extension method do with an incoming HTTP request? What does the method do with the return value? What is the return value?**
- generates a URL to the browers

**9. What is session state?**
- data associated with user's requests.

**10. What three types does a session state store? Suppose you want to store data that has a type that session state does not store, is it possible to do so? If so, how do you do it?**

- int, string, byte[]
- Use JSON format