# Express

## What’s the difference between PUT and PATCH?
PUT allows the client to send data to update and entire resource. It overwrites the entity completely if it already exists, and creates a new resource if it doesn't exist. 

PATCH applies partial updates to resources, only requiring the data you want to update and not affecting anything else. [ref](https://rapidapi.com/blog/put-vs-patch/)

## Provide links to 3 services or tools that allow you to “mock” an API for development like json-server
https://www.npmjs.com/package/dyson

https://github.com/APIDevTools/swagger-express-middleware

https://www.npmjs.com/package/fake-api-server

## Compare and contrast Swagger and APIDoc.js 1 Which HTTP status codes should be sent with each type of (un)successful API call?
Both are tools for documenting API annotations within your source code. Both use modified comments in source code to create this documentation. Swagger uses plain .json files and seems to be more popular currently. 

404 not found

403 forbidden

500 internal server error

## Compare and contrast SOAP and ReST
SOAP operates through performing operations through a set of standardized messaging patterns. 

REST simply accesses data. While SOAP is older and more established(?), REST has become more popular recently. 
REST offers higher performance, greater variety of data formats, JSON support, and current popularity. [ref](https://stackify.com/soap-vs-rest/)
## Terms

**Web Server** - 

**Express** - a popular node web framework. Provides mechanisms to write handlers for requests, integrate with templating engines, run request middleware, and set web application settings. 
[docs](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/Introduction)

**Routing** - determining how an app replies to a client request to a particular endpoint (url + method) [docs](http://expressjs.com/en/starter/basic-routing.html)

**WRRC** - Web request-response cycle. The cycle of client request, server processing, and server response that makes up the back-and-forth of a user accessing a web page. 

**Test Driven Development** is defined by writing unit tests first, then writing just enough code to pass a given test. Code is then refactored, before additional feature tests are written. 
The increase in initial effort and slower pace of development is typically offset by increased code quality and robustness. 

**NPM** Node package manager consists of the [npm website](https://www.npmjs.com/), the command-line-interface, and the registry (large public database of software and metadata. 
ALlows for a centralized location to host packages, store updates, and share packages. 
