# Class 01 Reading Notes | Putting it all together

[React Docs - Thinking in React](https://reactjs.org/docs/thinking-in-react.html)

## Discussion Questions

- Q: What is the single responsibility principle and how does it apply to components?

  - A: A component should ideally only do one thing. If it ends up growing, it should be decomposed into smaller subcomponents. ^[1](https://reactjs.org/docs/thinking-in-react.html)

- Q: What does it mean to build a ‘static’ version of your application?

  - A: A static version of the application that takes all of your data model and renders the UI but has no interactivity.

- Q: Once you have a static application, what do you need to add?

  - A: State

- Q: What are the three questions you can ask to determine if something is state?

  - A:
    1. Is it passed in from a parent via props? If so, it probably isn’t state.
    2. Does it remain unchanged over time? If so, it probably isn’t state.
    3. Can you compute it based on any other state or props in your component? If so, it isn’t state.

- Q: How can you identify where state needs to live?

  - A:
    1. Identify every component that renders something based on that state.
    2. Find a common owner component (a single component above all the components that need the state in the hierarchy).
    3. Either the common owner or another component higher up in the hierarchy should own the state.
    4. If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.

[Higher-Order Functions](https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK)

## Discussion Questions

- Q: What is a “higher-order function”?

  - A: Higher-Order Functions operate on other functions, either by taking them as arguments or by returning them.^[2](https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK)

- Q: Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?

  - A: Line two is returning the boolean value of true or false depending on if `m` is greather than `n`

- Q: Explain how either map or reduce operates, with regards to higher-order functions.

  - A: - map(): The map method transforms an array by applying a function to all of its elements and building a new array from the returned values. The new array will have the same length as the input array, but its content will have been mapped to a new form by the function. - reduce(): It builds a value by repeatedly taking a single element from the array and combining it with the current value.

## Things I want to know more about

Hooks!
