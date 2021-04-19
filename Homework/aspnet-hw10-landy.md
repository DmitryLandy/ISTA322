## NAME: Dmitry Landy
## ASSIGNMENT: ASP.NET Chapter 10 HW
## DATE: 4/13/2021
---
**1. What is Blazor?**
- Combines client-side JS code with server-side code, connected by persistent http connection

**2. What do the methods AddServerSideBlazor() and MapBlazorHub() do?**
- AddServerSideBlazor creates the services for Blazor and MapBlazorHub registers the blazor middleware components

**3. Where are Blazor files conventionally located?**
- Within pages

**4. What is the purpose of the Routed.razor file?**
- It allows the app to use browser's url to locat the razor component

**5. (Not in book) What is the purpose of the <NavLink> element, and what does it do?**
- A component that renders an anchor tag, automatically toggling its 'active' class based on whether its 'href' matches the current URI.

**6. What is the purpose of an @code { ... } block? Where are they located and what is their purpose?**
- used to annotate HTML elements.
- located in a view
- used in the view section of the component to display details

**7. How can a single component be configured to present two different sets of data without the need to duplicate code and content?**
- partial views

**8. What is CRUD? What are the equivalent SQL statements?**
- Create, Read, Update, Delete
- Insert, Select, update, Remove

**9. Does Blazor use the same approach to validation as the rest of ASP.NET Core? If not, how is Blazor different?**
- For the most part yes, But it does have to account for the more dynamic nature of blazor

**10. What is the purpose of the Inject attribute?**
- Declares that it requires an implementation of the interface

**11. What is the NavigationManager class? What does it do?**
- Navigate between components without triggering a new HTTP request