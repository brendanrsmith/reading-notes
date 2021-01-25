# EJS 
EJS is a templating lang which lets you generate HTML markup with plain javaScript. 
We load it like any other js libary. 
Along with express and cors, it will allow us to easily create repeatable elements frokm our server. 

Create template files, which we call on different "views"
`<% raw html %>`
by using For loops and Arrays, we can dynamically provide content to the client. 

If statements let you provide different content based on the data provided. 

## Layouts 
layouts are not native to EJS, but are very useful for layouts.
  `npm install --save express-ejs-layouts`
Layout file is our wrapper for all layout html. 
Allows you to easily build common layout elemts that render to each page, with only the page content chaning. 

## Partials
`<% include('partials/onepartial') %>`
easy way to use reusable text that aren't a complete file. 
