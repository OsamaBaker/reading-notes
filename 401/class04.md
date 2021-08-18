#  Data Modeling

1. Name 3 advantages to Test Driven Development
> Better program design and higher code quality, Detailed project documentation, Code flexibility and easier maintenance.

2. In what case would you need to use beforeEach() or afterEach() in a test suite?
> beforeEach and afterEach can handle asynchronous code in the same ways that tests can handle asynchronous code - they can either take a done parameter or return a promise. For example, if initializeCityDatabase() returned a promise that resolved when the database was initialized, we would want to return that promise:

3. What is one downside of Test Driven Development
> slow process

4. What’s the primary difference between ES6 Classes and Constructor/Prototype Classes?
> Classes can’t be called without new, but functions intended as constructors can (and their this will be wrong)

5. Why REST?
>REST aims to make caching easier. Since the server is stateless and each request can be processed individually, GET requests should usually return the same response regardless of previous ones and the session.


functional programming - a programming paradigm where programs are constructed by applying and composing functions

object-oriented programming (OOP) - a programming paradigm based on the concept of "objects", which can contain data and code: data in the form of fields, and code, in the form of procedures

class - Classes are a template for creating objects. They encapsulate data with code to work on that data.

super - The super keyword is used to access and call functions on an object's parent.

this - The JavaScript this keyword refers to the object it belongs to.

Test Driven Development (TDD) - a software development practice that focuses on creating unit test cases before developing the actual code.

Jest - Jest is a JavaScript testing framework designed to ensure correctness of any JavaScript codebase. It allows you to write tests with an approachable manner

Continuous Integration (CI) - automation process for developers.

REST - REST, or REpresentational State Transfer, is an architectural style for providing standards between computer systems on the web

Data Model - A data model (or datamodel) is an abstract model that organizes elements of data and standardizes how they relate to one another and to the properties


