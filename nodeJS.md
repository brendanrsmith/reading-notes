# Node.js

What is Node.js? 
## Node.js is a JavaScript runtime built on the V8 JS engine
### Node is a program we can use to execute JS on our computers

It is installed via NPM package manager

Node has excellent support for ES6. 

## Essentailly, Node lets us run JavaScript on a server
 Because JS is *event-driven* and single-threaded, it does not experience the same blocking problems as other languages.
 
 This allows Node to be capable of handling a large number of simultaneous connections. 
 
 ### Node Hello, World!
    const http = require('http');

    http.createServer((request, response) => {
     response.writeHead(200);
     response.end('Hello, World!');
    }).listen(3000);

    console.log('Server running on http://localhost:3000');
## What can we use it for?
Node is well-suited to building applications that feature real-time interaction (chat, sharing app) or Data Streaming.

This also allows you to use JS for both the server and browser code bases. 

Node speaks JSON. 

Node uses JS, and JS is ubiquitous. 

## Express
Express is a super-popular framework for Node. 

