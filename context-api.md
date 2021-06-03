# Context API

## Review, Research, and Discussion

### Describe use cases for `useMemo()` and `useReducer()`

'useMemo()' memoizes large functions so that you can avoid calling them on every render, instead only re-rendering when a passed value is changed. This is good for when we have large, expensive functions that we want to avoid running on every render. [src](https://usehooks.com/useMemo/)

'useReducer()' is analogous to `useState()`, but give a more structured approach for updating complex values. This works well for states that contain multiple variables which may be inter-dependent. [src](https://www.react.express/hooks/usereducer)

### Why do custom hooks need the use prefix?

Semantics - this helps us as developers quickly identify them as hooks.

### What do custom hooks usually do?

Usually they are designed to remove logic from the UI layer and allow common code functions to be shared among different components (api calls, for instance).

### Using any list of custom hooks, research and name one that you think will be useful in your applications

[`useToggle`](https://usehooks.com/useToggle/) will come in handy in any number of use cases. Gotta love toggles.

### Describe how a hook that fetches API data might work

Using state and useEffect to fetch API parameters from the UI, then make an API call using axios or some other service on the server side.

## Document the following Vocabulary Terms

**reducer** - A built-in hook that can change an application's state using a given dispatch function.

## Preparation Materials

[context api](https://reactjs.org/docs/context.html)

[hooks and context example](https://medium.com/swlh/snackbars-in-react-an-exercise-in-hooks-and-context-299b43fd2a2b)

[react context links](https://github.com/diegohaz/awesome-react-context)
