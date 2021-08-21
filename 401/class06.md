# Authentication


1. Explain what a “Singleton” is (in Computer Science terms)
> A singleton is a class that allows only a single instance of itself to be created and gives access to that created instance.

2. Explain how the Singleton pattern can be used with Node modules, specifically with classes
> Singleton design pattern restricts the instantiation of a class to a single instance Example: // recreation.js file class Recreation { constructor ( city , park ) { this . city = city ; this . park = park ; } } module . exports = Recreation ; // adventure.js file const Recreation = require ( ‘ recreation.js ‘ ); const greenlake = new Recreation ( ‘ Seattle ‘ , ‘ Greenlake ‘ );

3. If you were tasked with building a middleware system like Express uses, what approach might you take to construct/operate it?
> npm init npm install express –save Create server.js and paste the following code:

const express = require(‘express’); const app = express();

app.get(‘/’, (req, res, next) => { res.send(‘Welcome Home’); });

app.listen(3000);


-------------------------------------------------------------

Router Middleware - The term is composed of 2 words router and middleware. Middleware. It is a piece of code that comes in the middle of request and response . It kind of hijacks your request so that you can do anything that you want with your request or response eg: Modify the data or call the next middleware.

Dynamic Module Loading - Dynamic loading is a mechanism by which a computer program can, at run time, load a library (or other binary) into memory, retrieve the addresses of functions and variables contained in the library.

Singleton Pattern - the singleton pattern is a software design pattern that restricts the instantiation of a class to one "single" instance

CRUD -> REST Method Matches - POST            Creates a new resource.
GET             Retrieves a resource.
PUT             Updates an existing resource.
DELETE          Deletes a resource.

Mock Testing - Mock testing is an approach to unit testing that lets you make assertions about how the code under test is interacting with other system modules.