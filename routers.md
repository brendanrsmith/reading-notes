# React Routing

## Review, Research, and Discussion

### Do child components have direct access to props/state from the parent?

When they are passed via props to the child.

### When a component “wraps” another component, how does the child component’s output get rendered?

When the parent component gets rendered.

```html
<Main>
  <Content />
</Main>
```

### Can a component, such as `<Content />`, which is a child also be used as a standalone component elsewhere in the application?

Yes, each instance of a component gets rendered individually, and all components are reusable.

### What trick can a parent use to share all props with it’s children

Using the spread operator `...` to pass all props to a child [src.](https://medium.com/coding-at-dawn/how-to-pass-all-props-to-a-child-component-in-react-bded9e38bb62)

## Document the following Vocabulary Terms

**props.children** - basically, anything that is passed between the opening and closing tags of the invoking component [src](https://stackoverflow.com/questions/49706823/what-is-this-props-children-and-when-you-should-use-it).

**composition** - the act of creating more complex components in react using simpler components as building blocks.

## Preparation Materials

[browser router tutorial](https://blog.pshrmn.com/simple-react-router-v4-tutorial/)

[browser router api docs](https://reactrouter.com/web/api)

[react-if component](https://www.npmjs.com/package/react-if)

[react testing library queries](https://testing-library.com/docs/queries/about/)

[aria roles](https://www.w3.org/TR/html-aria/)
