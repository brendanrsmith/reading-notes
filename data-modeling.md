# Data Modeling

## Name 3 advantages to Test Driven Development

- leads to more efficient code writing (base-case scenario)
- you can test your code as you build your app, so you know which parts are working.
- usually produces more robust code base than other methods of development

## In what case would you need to use beforeEach() or afterEach() in a test suite?

If you wanted to test database functionality without adding live data to a live database, these functions let you provision an in-memory db for each test

## What is one downside of Test Driven Development

Initial set-up can take much longer, and if your app is changing quickly and frequently, keeping the tests up to date can be a pain

## What’s the primary difference between ES6 Classes and Constructor/Prototype Classes?

Class inheritance creates a specific Parent-Child relationship (taxonomy), whereas object prototypes do not. [src](https://medium.com/javascript-scene/master-the-javascript-interview-what-s-the-difference-between-class-prototypal-inheritance-e4cd0a7562e9)

## Why REST?

By attaching the state to the transfer protocol, the server does not have to keep track of what each client is doing at any given time. Every request from a given path with a given method will provide the same result each time. 

## Document the following Vocabulary Terms

**functional programming** - paradigm where programs are constructed by creating and imposing functions 

**object-oriented programming** - paradigm where programs are constructed out of objects which contain data as properties, and code as methods

**class** - a wrapper for object prototypes that allows for inheritance

**`super`** - global middleware that runs on every incoming request. Called on the server.

**`this`** - middleware that specifically runs on individual routes. Called within the route callback.

**Test Driven Development** - the dev process of building key requirement tests first, then building out code such that your code fulfills the requirements of the tests.

**jest** - javascript testing framework that provides for specific code testing

**continuous integration** - the practice of creating a workflow that automatically tests and deploys code as it is pushed up to a project.  

**REST** - REpresentation State Transfer is a protocol by which to pass states between clients and servers. Rest verbs include `GET` `POST` `PUT` and `DELETE`

**data model** - a model that organzies data and data relationships in a standardized way. Ensures that all data added to a database conforms to a common format. 

## Preview

### Which 3 things had you heard about previously and now have better clarity on? 

noSql, the difference between Sql and document-based databases, the advantages of each. 

### Which 3 things are you hoping to learn more about in the upcoming lecture/demo?

implementing tests on databases, why you might implement both Sql and noSql on the same project, and how you would do that. 

### What are you most excited about trying to implement or see how it works?

Successfully implementing a mongoDB database to heroku. 

## Preparation Materials

[sql vs nosql(Video)](https://www.youtube.com/watch?v=ZS_kXvOeQ5Y)

[nosql vs sql](https://www.thegeekstuff.com/2014/01/sql-vs-nosql-db/?utm_source=tuicool)

[nosql modeling techniques](https://highlyscalable.wordpress.com/2012/03/01/nosql-data-modeling-techniques/)
