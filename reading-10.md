# Reading 10: In memory storage

## [Reading: Understanding the JavaScript Call Stack](https://medium.freecodecamp.org/understanding-the-javascript-call-stack-861e41ae61d4)

### What is a ‘call’?

A call is a function invocation.

### How many ‘calls’ can happen at once?

Calls can happen one at a time.

### What does LIFO mean?

Last In, First Out

### Draw an example of a call stack and the functions that would need to be invoked to generate that call stack

function firstFun () {
  console.log('yo from number one');
}

function secondFun () {
  firstFun();
  console.log('yo from number two');
}

secondFun

stack:
firstfun()
secondFun()

### What causes a Stack Overflow?

When a function calls itself it will cause stack overflow because the function will continueosly call itself.

## [Reading: JavaScript error messages](https://codeburst.io/javascript-error-messages-debugging-d23f84f0ae7c)

### What is a ‘refrence error’?

Occurs when you try to use a variable that hasn't been declared yet.

### What is a ‘syntax error’?

When something cannot be correctly parsed b/c of incorrect syntax.

### What is a ‘range error’?

When you try to give something with a set length a different length.

### What is a ‘tyep error’?

When the data type you are trying to access is incompatable.

### What is a breakpoint?

Allows you to stop the code and see the lines before it for debugging purposes.

### What does the word ‘debugger’ do in your code?

The debugger puts a breakpoint in your code.

## [Skim/Bookmark: JavaScript errors reference on MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors)
