## NAME: Dmitry Landy
## ASSIGNMENT: ASP.NET Chapter 3 HW
## DATE: 2/28/2021
---
**1. What is the most important part of an ASP.NET Core 3 application?**

- The data model. 

**2. What is the domain model?**

- The data model.
- Its the representation of the real -world objects, processes, and rules that define the domain. 

**3. Where are the model classes in an ASP.NET Core 3 application placed?**

- In the Models folder

**4. How many action methods can a controller class define?**

- Multiple. No limit.

**5. What is a tag helper?**

- An action that is performed when the view is rendered.

**6. What does the asp-action attribute do?**

- An instruction to add a "href" attribute to the "a" element that contains a URL for the action method.

**7. What is the difference between HTTP GET and HTTP POST? This is an important question, and you should understand the difference.**

- GET request is what the browser issues to retrieve data that the user requests.
- POST request is used to receive submitted data.

**8. What is model binding?**

- Feature that parses data into key/value pairs in the HTTP request to populate properties of the domain model types.

**9. Why should we validate user data? How do we validate user data?**

- To make sure that the input data is appropriate
- ModelState.IsValid property

**10. What, specifically, is the ModelState.IsValid property?**

- A Boolean property that checks for input data constraints and validates them

**11. What does the asp-validation-summary do?**

- Attribute applied to the "div" element to display a lust of validation errors when view is rendered

**12. Static content consists of content such as images, script files, style files, etc. In an ASP.NET Core application, what is the name of the folder that cotains static content?**

- wwwroot

**13. What is Bootstrap? Who developed Bootstrap? Is Bootstrap a proprietary package? If not, what is it?**

- Its the styling of the basic web app objects 