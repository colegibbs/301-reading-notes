# Reading 02: States and Props

## Reading: [React Lifecycle](https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093)

### Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?

Bassed off of the diagram, the render happens first.

### What is the very first thing to happen in the lifecycle of React?

The constructor in the mounting phase is the first think to occur in the lifecycle.

### Put the following things in the order that they happen: `componentDidMount`, `render`, `constructor`, `componentWillUnmount`, `React Updates`

1. `constructor`
2. `render`
3. `componentDidMount`
4. `React Updates`
5. `componentWillUnmount`

### What does componentDidMount do?

- invoked immediately after mounting
- used to load network request or initialize the DOM
- good place for subscriptions
- don't forget to unsubscribe in componenetWillUnmount()

## Video: [React State Vs Props](https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093)

### What types of things can you pass in the props?

You can pass initial values or renders or titles into props.

### What is the big difference between props and state?

props are handled outisde the componenet and state is handled inside the component.

### When do we re-render our application?

When you change the state it re-renders.

### What are some examples of things that we could store in state?

Updating application by user interaction. Useful for displayinging in a component without hard coding.

## Bookmark/Skim

### [React Docs - State and Lifecycle](https://reactjs.org/docs/state-and-lifecycle.html)

- convert function to class in 5 steps
- this.props and this.state
- can add lifecycle methods to a class
- do not modify setState() directly
- the only place you can assign this.state is the constructor
- state updates may be asynchronous
- state updates are merged
- data flows down single path

### [React Docs - handling events](https://reactjs.org/docs/handling-events.html)

- handleing event in react is similar to handleing event in DOM
- syntax is different
- react has event listeners and handlers

### [React Tutorial through ‘Developer Tools’](https://reactjs.org/tutorial/tutorial.html)

- dev tools still useful for react
