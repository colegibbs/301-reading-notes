# Reading 03: Passing Functions as Props

## [Reading: React Docs - lists and keys](https://reactjs.org/docs/lists-and-keys.html)

### What does .map() return?

A new array where each is an original item with the callback function inflicted on it.

### If I want to loop through an array and display each value in JSX, how do I do that in React?

This can be done by putting the JSX in the code block of the map callbabck function.

### Each list item needs a unique ____

Key.

### What is the purpose of a key?

Keys help react identify what item have been changed, added, or removed from the list.

## [Reading: The Spread Operator](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)

### What is the spread operator?

The spread operator is `...`.

### List 4 things that the spread operator can do

1. Spread an array/object into seperate arguments.
2. Copying an array
3. concatonating or combining arrays
4. Adding to state in React

### Give an example of using the spread operator to combine two arrays

`let newArr = [...arrayOne, ...arrayTwo];`

### Give an example of using the spread operator to add a new item to an array

`let newArr = [newItem, ...array];`

### Give an example of using the spread operator to combine two objects into one

`let newOBJ = {...objOne, ...objTwo}`

## [Video: How to Pass Functions Between Components](https://www.youtube.com/watch?v=c05OL7XbwXU)

### In the video, what is the first step that the developer does to pass functions between components?

Add the function to as a prop to the object from the child component.

### In your own words, what does the increment function do?

The increment function is is counting how many times the add button is clicked.

### How can you pass a method from a parent component into a child component?

Add the function to as a prop to the object from the child component.

### How does the child component invoke a method that was passed to it from a parent component?

this.props.functionFromParent(relaventParam)

## [Bookmark/Skim: React Tutorial through ‘Declaring a Winner’](https://reactjs.org/tutorial/tutorial.html)

- the correct text will display if the play has won or lost
- status will be reaplaced in the render function
- use the handleClick function after the status is replaced

## [Bookmark/Skim: React Docs - Lifting State Up](https://reactjs.org/docs/lifting-state-up.html)

- adding a secon imput involves creating an object with both as properties
- redefine this.state with setState()
