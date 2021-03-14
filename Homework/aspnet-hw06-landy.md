## NAME: Dmitry Landy
## ASSIGNMENT: ASP.NET Chapter 6 HW
## DATE: 3/8/2021
---
**1. What is unit testing as defined by the book?**
- Testing individual components while isolating them from the rest of the program

**2. What is the convention for creating unit tests in ASP.NET Core applications?**
- Create a separate project for the unit test.

**3. Name three unit test project tools used for ASP.NET Core applications.**
- MS Test Framework
- NUnit Framework
- XUnit Framework

**4. What is the convention for naming unit tests in ASP.NET Core applications?**
- Extension is ".Tests"

**5. What is the convention for naming the test classes in ASP.NET Core? What is the convention for naming the methods in the test classes?**
- Add Tests to the class name. Describes what is being tested.
- Method names describe what the test does

**6. What is the purpose of the Fact attribute in Xunit? (not in book) What is the purpose of the Theory attribute in Xunit?**
- This component should be tested by the test runner
-Fact is non-parameterized test
- Theory is parameterized.

**7. Describe the different elements of the AAA testing pattern.**
- Arrange, act, assert

**8. Describe the use of the methods in the Assert class. Describe the purpose, parameters, and return value of the Assert.Equals() method.**
- They are static and used to perform compariosn between expected and actual values
- The Equal() takes the expected value first and then the result second.

**9. What is the key to isolating a component for testing?**
- c# interfaces.

**10. What is a mocking package? What does it do?**
- create fake or mock objects for tests.

**11. (not in book) What is the difference between the Setup() and the SetupGet() methods of Moq**
- Setup() mocks the method or property
- SetupGet() mocks the getter of a property