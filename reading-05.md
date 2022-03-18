# Reading 05: Putting it all together

## [Reading: React Docs - Thinking in React](https://reactjs.org/docs/thinking-in-react.html)

### What is the single responsibility principle and how does it apply to components?

The single responsibility principle means that each component should only do one think and if it should grow it should be split into multiple components.

### What does it mean to build a ‘static’ version of your application?

A static version of an app is a pre-product version that looks how you want it to but doesn't account for desired user interaction.

### Once you have a static application, what do you need to add?

You need to add state to your app so that the user can interact with it.

### What are the three questions you can ask to determine if something is state?

1. Is it passed in from a parent via props? If so, it probably isn’t state.

2. Does it remain unchanged over time? If so, it probably isn’t state.

3. Can you compute it based on any other state or props in your component? If so, it isn’t state.

### How can you identify where state needs to live?

- Identify every component that renders something based on that state.

- Find a common owner component (a single component above all the components that need the state in the hierarchy).

- Either the common owner or another component higher up in the hierarchy should own the state.

- If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.

## [Reading: Higher-Order Functions](https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK)

### What is a “higher-order function”?

Functions that operate on other functions are call higher order functions.

### Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?

greaterThan is returning an arrow function that returns a boolean when m, the inner function param, is compared to n, the outer function param.

### Explain how either map or reduce operates, with regards to higher-order functions

.map takes an arrow function as a param and uses it to inflict that param function on each item in a specifed array.
