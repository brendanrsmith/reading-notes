# Hooks API

## Review, Research, and Discussion

### Why do we not need more .html pages in a multi-page React app?

Each "page" is rendered into the index.html page via ract - like a html templating engine for your whole website.

### If we wanted a component to show up on every page, where would we put it and why?

Inside the <BrowserRouter />, outside a <Route />, as the <BrowserRouter /> wraps our entire html, but since we do not want to re-render the component on each <Route /> we would not wrap it in a route tag.

### What does props.children contain?

Anything you include between the open and closing tags of the component invocation. This could be anything.

## Document the following Vocabulary Terms

**Composition** The process of building complex react components using simpler smaller components as building blocks.

**Children / Child Components** The simpler, smaller building blocks used to compose a more complex react component.

**Hash Routing** Using the anchor of the url to render components.

**Link Routing** Using react to handle render logic and routing behavior.

## Preparation Materials

[making sense of hooks](https://medium.com/@dan_abramov/making-sense-of-react-hooks-fdbde8803889)

[the state hook](https://reactjs.org/docs/hooks-state.html)

[hooks api](https://reactjs.org/docs/hooks-overview.html)

[hooks api reference](https://reactjs.org/docs/hooks-reference.html)

[effects hook](https://reactjs.org/docs/hooks-effect.html)
