# Express REST API

## Name 3 real world use cases where you’d want to change the request with custom middleware

- adding a name validation
- checking user credentials
- flagging a database input based on the url used

## True or false: The route handler is middleware?

True, however they can be bypassed if they use a callback to invoke `next(route)`.

## In what ways can a middleware function end the process and send data to the browser?

`res.send()`, `res.status()`

## At what point in the request lifecycle can you “inject” middleware?

Functionally between the client and the route handler, as middleware is processed before a route handler begins processing the request.

## What can cause express to error with “Request headers sent twice, cannot start a second response”

Anything that happens after the body has been sent to the client can cause this issue, as headers cannot be changed once they have been sent. [src](https://stackoverflow.com/questions/7042340/error-cant-set-headers-after-they-are-sent-to-the-client)

## Document the following Vocabulary Terms

**Middleware** - code that runs in between a request object being sent to the server and a server route processing that request

**Request Object** - the HTTP object sent from the client to the server. Contains HTTP method, body, and headers with metadata.

**Response Object** - the HTTP object sent from the server to the client. Contains http status, body, and headers.

**Application Middleware** - global middleware that runs on every incoming request. Called on the server.

**Routing Middleware** - middleware that specifically runs on individual routes. Called within the route callback.

**Test Driven Development** - the dev process of building key requirement tests first, then building out code such that your code fulfills the requirements of the tests.

**Behavioral Testing** - 'black box testing' functional testing that evaluates the external behaviour of a program(?)

## Notes

### Classes

Classes are templates for creating objects. They are built on prototypes, and are special functions. They can be expressed or declared, however they are NOT hoisted like functions declarations.

A constructor of a class can use the `super` keyword to call the constructor of the super class.

You can sub-class with the `extends` keyword to create a child class. If there is a constructor present in the subclass, it needs to first call `super()` before using `this`.

## Preview

### Which 3 things had you heard about previously and now have better clarity on? 

Express routers, JS Classes, and app-level middleware.

### Which 3 things are you hoping to learn more about in the upcoming lecture/demo?

Extending classes, middleware syntax, more express routers.

### What are you most excited about trying to implement or see how it works?

Using subclasses to make data modeling simper and more modular. 

## Preparation Materials

[Review: ES6 Classes](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes)

[Using Express Routing](https://expressjs.com/en/guide/routing.html)

[Express Routing](https://scotch.io/tutorials/learn-to-use-the-new-router-in-expressjs-4)
