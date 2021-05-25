# Reading: Props and State

## Review, Research, and Discussion

### Does a deployed React application require a server?

No, you can run `npm build` in a create-react-app in order to compile all react code into a `build` directory with a static `index.html` page.

### Why do we prefer to test a React application at the behavior rather than the unit level?

It prevents us from getting false positive tests (where the test passes, but real life user interaction fails) or false negatives (where the test fails, but real life code works) by emulating the actual user interaction instead of simply triggering different functions in the code.

### What does npm run build do?

It compiles all project code into singluar JS and CSS files, in order to decrease load time and file size. The resulting static files can then be served to clients.

### Describe the actual composition / architecture of a React application

React components are located in a `src/index.js` file. The front-end HTML template is stored in a `public/index.html` file. Styles are stored in `src` directory as well. All front-end html is rendered via the `index.html` file to the client.

## Document the following Vocabulary Terms

**BDD** - behaviour driven development: a branch of test-driven-development using human-readable software requirements as the basis of software tests [src](https://medium.com/javascript-scene/behavior-driven-development-bdd-and-functional-testing-62084ad7f1f2).

**Acceptance Tests** - testing with respect to user requirements, based on acceptance criteria [src](https://en.wikipedia.org/wiki/Acceptance_testing).

**mounting** - the act of react adding nodes to the DOM so they can be displayed to the user, and updated by the server.

**build** - a static compilation of all files in a react project, minified and combined for deployment.

## Preparation Materials

[setState explained](https://css-tricks.com/understanding-react-setstate/)

[handling events](https://reactjs.org/docs/handling-events.html)

[forms](https://reactjs.org/docs/forms.html)

[state and lifecycle](https://reactjs.org/docs/state-and-lifecycle.html)

[components and props](https://reactjs.org/docs/components-and-props.html)

[RTL Testing Example](https://thomaslombart.com/beginner-guide-testing-react-apps/)

[Roles Reference](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/ARIA_Techniques#roles)
