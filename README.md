# What I Learned In Term 2, Week 15 At Code Immersives

&nbsp;

## Functional Programming JavaScript Libraries

https://lodash.com/

Lodash makes JavaScript easier by taking the hassle out of working with arrays, numbers, objects, strings, etc.
Lodash’s modular methods are great for:

Iterating arrays, objects, & strings
Manipulating & testing values
Creating composite functions

https://underscorejs.org/

Underscore is a JavaScript library that provides a whole mess of useful functional programming helpers without extending any built-in objects.

&nbsp;

## Callback Functions

A callback function is a function passed into another function as an argument, which is then invoked inside the outer function to complete some kind of routine or action.

    function greeting(name) {
    alert('Hello ' + name);
    }

    function processUserInput(callback) {
    var name = prompt('Please enter your name.');
    callback(name);
    }

    processUserInput(greeting);

&nbsp;

## nodemon

https://www.npmjs.com/package/nodemon

nodemon
nodemon is a tool that helps develop node.js based applications by automatically restarting the node application when file changes in the directory are detected.

nodemon does not require any additional changes to your code or method of development. nodemon is a replacement wrapper for node. To use nodemon, replace the word node on the command line when executing your script.

Installation, either through cloning with git or by using npm (the recommended way):

    npm install -g nodemon

&nbsp;

## Postman App

https://www.postman.com/downloads/

Postman is a collaboration platform for API development. Postman's features simplify each step of building an API and streamline collaboration so you can create better APIs—faster.

&nbsp;

## HTTP Methods

### CRUD

- PUT - Create
- PUT: Lets you replace an existing file or resource in a server.
- GET - Retrieve
- GET : Enables you to retrieve data from server.
- POST - Update
- POST: Enables you to add data to an existing
  file or resource in a server.
- DELETE - Delete
- DELETE: Lets you delete data from server.

&nbsp;

## HTTP Status Codes

https://en.wikipedia.org/wiki/List_of_HTTP_status_codes

Status codes are issued by a server in response to a client's request made to the server.

- 1xx informational response – the request was received, continuing process
- 2xx successful – the request was successfully received, understood, and accepted
- 3xx redirection – further action needs to be taken in order to complete the request
- 4xx client error – the request contains bad syntax or cannot be fulfilled
- 5xx server error – the server failed to fulfil an apparently valid request
