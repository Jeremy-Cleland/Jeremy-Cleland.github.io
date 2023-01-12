# Class 04 Reading Notes | React and Forms

[React Docs - Forms](https://reactjs.org/docs/forms.html)

## Discussion Questions

- Q: What is a ‘Controlled Component’?

  - A: In React, Controlled Components are those in which form’s data is handled by the component’s state. It takes its current value through props and makes changes through callbacks like onClick,onChange, etc. A parent component manages its own state and passes the new values as props to the controlled component.^[1]

- Q: Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.

  - A: The state is updated on every keystroke

- Q: How do we target what the user is entering if we have an event handler on an input field?

  - A: handleChange and value prop

[The Conditional (Ternary) Operator Explained](https://codeburst.io/javascript-the-conditional-ternary-operator-explained-cac7218beeff)

## Discussion Questions

- Q: Why would we use a ternary operator?

  - A: A ternary operator makes the assignment of a value to a variable easier to see, because it's on a single line instead of an if else block.

- Q: Rewrite the following statement using a ternary statement:

  ```JS

  if(x===y){
  console.log(true);
  } else {
  console.log(false);
  }

  ```

  - A:

  ```jsx
  x === y ? console.log(true) : console.log(false);
  ```

## Sources

^[1](https://www.geeksforgeeks.org/what-are-controlled-components-in-reactjs/)

## Things I want to know more about

React Hooks
