# `<Login />` and `<Auth />`

## Review, Research, and Discussion

### Why is the Context API useful?

It allows you to pass props down multiple levels of a component tree without having to manually pass the prop each time, essentailly providing a shortcut for props to granchildren etc. [src](https://reactjs.org/docs/context.html)

### Can a component outside of a provider get its context?

### What are some common use cases for using the Context API?

Passing UI Themes, local preferences, or any parameter which needs to be consumable to many different levels of components at the same time.

### Describe “Context Hell”

When you have too many nested contexts... This is similar to callback hell. Can be addressed with the 'React.cloneElement()' function which returns a new element using the initial 'element' as a starting point. [src](https://reactjs.org/docs/react-api.html#cloneelement)

## Document the following Vocabulary Terms

**global state** - state which is declared at the app-level. [src](https://codeburst.io/global-state-with-react-hooks-and-context-api-87019cc4f2cf)

**global context** - context which is visible to the entire app.

**provider** - a component who's context changes can be subscribed to by a consumer.

**consumer** - A React component that subscribes to context changes. Using this component lets you subscribe to a context within a function component.

## Preparation Materials

[what is role based access control?](https://digitalguardian.com/blog/what-role-based-access-control-rbac-examples-benefits-and-more)

[react-cookies component](https://www.npmjs.com/package/react-cookies)

[react-cookie library](https://www.npmjs.com/package/react-cookie)
