# Review, Research, and Discussion
## Describe (in plain English) what Array.map() does
Array.map() is a glorified for() loop. It iterates through an array completely, applying the provided function to each element in series. It returns a new array, and does not modify the original. 
It is extremely useful for things like parsing api objects, adding formatting to strings, or performing math on a list. 
[source](https://codefellows.github.io/code-301-guide/curriculum/class-07/challenges/)
## Describe (in plain English) what Array.reduce() does
Array.reduce() iterates through each item in an array, and returns a single "accumulator" value. Each iteration, it applies the provided function given an accumulator (like a running total), current element, and index. 
You may provide an initial value for the accumulator, otherwise the default action is to use the first array value. This method is super useful for things like summing a list of numbers, or changing the shape of data. 
[source](https://codefellows.github.io/code-301-guide/curriculum/class-09/challenges/) 
## Provide code snippets showing how to use superagent() to fetch data from a URL and log the result
### With normal Promise .then() syntax
```javaScript
const superagent = require('superagent')

  superagent.get('https://swapi.dev/api/people')
  .then(result => console.log(result.body))
  .catch(console.error);
  
```
### Again with async / await syntax
```javaScript
const superagent = require('superagent')

Async function getCharacters() {
  const character = await superagent.get('https://swapi.dev/api/people');
  console.log(character);
  }
```
## Explain promises as though you were mentoring a Code 301 level student
Promises are a way for JavaScript to handle processes that take too long to happen in-line. By choosing to have a function return a promise, we can tell javascript "do this work, and when you finish just let me know and give me the data."
This lets you choose how to handle the data once it's returned. This is basically the same as what a callback function does, but writes much more semantically and is therefore easier to manage compared to extensive callback use (callback hell). 

All promises must be either *Resolved* or *Rejected*, which we handle with `.then()` and `.catch()`, respectively. This allows us to take different actions depending on the result of the function.
[source.](https://www.youtube.com/watch?v=4bPdjAerRzQ&t=364s)
## Are all callback functions considered to be Asynchronous? Why or Why Not?
Not necessarily! Plenty of callback functions are able to be run synchronously - asynchrony depends upon if the function returns a promise, or if it can simply be run inline. 
