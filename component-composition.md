# Component Composition

## Review, Research, and Discussion

### Can a parent component access the state of a child component?

Yes, but only by creating a ref assigned to the child component in the parent [src](https://www.geeksforgeeks.org/how-to-access-childs-state-in-react/)

### What can be passed along in a prop variable?

Any Javascript object can be passed.

### How can a child component “know” the state of another component?

The simplest way would be to pass the state as props to the child.

## Document the following Vocabulary Terms

**component props** - data passed into a component from it's parent. Stands for Properties. Variable.

**component state** - Information about the parent component that is stored in the parent component but readable from the children. When state updates, the object re-renders [src](https://www.w3schools.com/react/react_state.asp)

**application state** - current state of an entire react application.

## Preparation Materials

[react basics recap](https://www.freecodecamp.org/news/these-are-the-concepts-you-should-know-in-react-js-after-you-learn-the-basics-ee1d2f4b8030/)

[props.children](https://codeburst.io/a-quick-intro-to-reacts-props-children-cb3d2fce4891)

[composition vs inheritance](https://reactjs.org/docs/composition-vs-inheritance.html)

[react testing library api example](https://testing-library.com/docs/react-testing-library/example-intro/)

[react-if component](https://www.npmjs.com/package/react-if)

[react-testing-library-async](https://testing-library.com/docs/dom-testing-library/api-async/)
