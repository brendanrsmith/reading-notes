# Authentication

## Explain what a “Singleton” is (in Computer Science terms)

"A software design pattern that restricts the installation of a class to a single instance" - [wikipedia](https://en.wikipedia.org/wiki/Singleton_pattern)

## Explain how the Singleton pattern can be used with Node modules, specifically with classes

It can be used to ensure that a module is only instantaited once, by the module itself.

## If you were tasked with building a middleware system like Express uses, what approach might you take to construct/operate it?

I might use singletons in order to ensure that each middlware function is only once within my express application.

## Document the following Vocabulary Terms

**Router Middleware** - code that acts on the user request before it reaches the given express route code.

**Dynamic Module Loading** - the act of dynamically loading modules when they are needed, rather than loading everything up front. Call import() as a function, passing the path the the module as parameter. This returns a promise which fulfills with a module object. [MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules#dynamic_module_loading)

**Singleton Pattern** - a mathematical pattern that restricts instantiaton to a single instance in software.

**CRUD -> REST Method Matches** - Create-GET, Read-PUT, Update-POST, Delete-DELETE.

**Mock Testing** - the process of running in-memory tests of code in order to assure it's functionality before pushing to a live application.

## Which 3 things had you heard about previously and now have better clarity on?

Hash Collision Attack - two input strings of a hash that produce the same hash output. 

## Which 3 things are you hoping to learn more about in the upcoming lecture/demo?

Salting, BCrypt, and key stretching. What are they, how do they work?

## What are you most excited about trying to implement or see how it works?

Hashing a user input to store in a local database.

## Preparation Materials

[Securing Passwords](https://thehackernews.com/2014/04/securing-passwords-with-bcrypt-hashing.html)

[Basic Auth](https://en.wikipedia.org/wiki/Basic_access_authentication)

[OWASP auth cheatsheet](https://cheatsheetseries.owasp.org/cheatsheets/Authentication_Cheat_Sheet.html)

[bcrypt docs](https://www.npmjs.com/package/bcrypt)
