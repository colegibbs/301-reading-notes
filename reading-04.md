# Reading 4: React and Forms

## Reading: [React Docs - Forms](https://reactjs.org/docs/forms.html)

### What is a ‘Controlled Component’?

AN input form element whose value is controlled by React in a way that the react componenet contorls what happens on user input.

### Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why

The response will be updated as the user types because the handler will run on every keystroke.

### How do we target what the user is entering if we have an event handler on an input field?

We use the state value that is the target on the same element so it is avialable to the handler.

## [Reading: The Conditional (Terneray Operator Explained)](https://codeburst.io/javascript-the-conditional-ternary-operator-explained-cac7218beeff)

### Why would we use a ternary operator?

The ternary operator is shorter and more concise than an if statement.

### Rewritten statement

`x === y $ console.log(true) : console.log(false);`

## [Bookmark/Skim: React Bootstrap - Forms](https://react-bootstrap.github.io/forms/overview/)

- can make forms with bootstrap
- can disable forms
- Form
- Form.Lable

## [Bookmark/Skim: React Docs - conditional rendering](https://reactjs.org/docs/conditional-rendering.html)

- can render under conitions
- element variables
- inline ifs with  and operator
- in line ternary operators
- can prevent componenets from rendering
