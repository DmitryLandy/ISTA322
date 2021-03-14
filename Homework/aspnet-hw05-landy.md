## NAME: Dmitry Landy
## ASSIGNMENT: ASP.NET Chapter 5 HW
## DATE: 3/7/2021
---
**1. What is the purpose of the null conditional operator? Does it apply to value types or reference types? Why or why not?**

- null conditional operator allows a variable to be set to null and this only applies to value types, because value types live on the stack and must be specified.

**2. What is the null coalescing operator? What does it do?**

- ??
- It sets a fallback value to prevent null values from being used.

**3. How is the null conditional operator different from a nullable type? What is the purpose of nullable types?**

- Not all data types are nullable and null operator allows then to be nullable.


**4. When you create an automatic property and initialize the property with a value, can the value be changed later? Can another value be assigned to the property? Can the value be changed in the constructor?**

- It can be changed if the property can be set.
- The constructor can still assign it a value

**5. What is an object initializer and what is it for? What is an collection initializer and what is it for?**

- Object initializer allows to initialize an object and set its property in a single step
- collection initializer creates a collention and implements its contents in a single step.

**6. What does the is keyword do? What does the as keyword do?**

- is performs a type test (returns true or false)
- as check if it could be the type then casts it if it can be. if not then it returns null.

**7. How are extension methods defined?**

- using the "this" keyword to pass a parameter type of the extending method.

**8. What is implicit typing or type inference? How do you implement it?**

- Using var keyword to assign a generic data type.


**9. What is a default implementation of an interface? What is the purpose of a default implementation of an interface?**

- Null is the default
- define default implementations for properties and methods of the interface

**10. What are asynchronous methods? Why should we use them? How are they used?**

- perform work in the background
- Useful for removing bottlenecks in code and incorporate multi-processing
- Keywords "async", "await"

**11. When you use the await keyword, do you have to use the async keyword? Why or why not?**

- Yes, because await is meant to be paired with async.

**12. (not in book) What is the yield keyword used for? How do you use it?**

- iteration through a collection or method. Basically a foreach loop

**13. What is the effect of using the nameof() expression?**

- produces a Name string