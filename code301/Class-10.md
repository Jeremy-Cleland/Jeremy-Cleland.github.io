# Class 10 Reading Notes

[Understanding the JavaScript Call Stack](https://medium.freecodecamp.org/understanding-the-javascript-call-stack-861e41ae61d4)

## Discussion Questions

- Q: What is a ‘call’?

  - A: function invocation

- Q: How many ‘calls’ can happen at once?

  - A: one at a time

- Q: What does LIFO mean?

  - A: Last In, First Out: The last function that gets pushed into the stack is the first to be pop out, when the function returns.

- Q: Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.

  - A:

```JS

  function func1(){
  console.log("Hello from firstFunction");
}

function func2(){
  func1();
  console.log("The end from secondFunction");
}

func2();

```

- Q: What causes a Stack Overflow?

  - A: A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point. The browser (hosting environment) has a maximum stack call that it can accomodate before throwing a stack error.

[JavaScript error messages](https://codeburst.io/javascript-error-messages-debugging-d23f84f0ae7c)

## Discussion Questions

- Q: What is a ‘reference error’?

  - A:

- Q: What is a ‘syntax error’?

  - A:

- Q: What is a ‘range error’?

  - A:

- Q: What is a ‘type error’?

  - A:

- Q: What is a breakpoint?

  - A:

- Q: What does the word ‘debugger’ do in your code?

  - A:

## Things I want to know more about

- Hooks!
