# Class 29 Reading Notes | Advanced State with Reducers

## [Extracting State Logic into a Reducer](https://react.dev/learn/extracting-state-logic-into-a-reducer)

- Q: What is the motivation for adding a reducer?

  - A: The motivation for adding a `useReducer` hook in React is to provide an alternative state management solution for complex components that have multiple states and actions. The `useReducer` hook allows developers to organize their state logic into a separate reducer function, which receives the current state and an action object and returns the new state based on the action type. This approach is similar to the Redux pattern and provides a centralized way to manage state changes, which can make the code more predictable and easier to debug. Additionally, by using the `useReducer` hook, developers can avoid the use of mutable states and reduce the number of unnecessary re-renders of the component.

- Q: What are actions in the context of a reducer? How are they different than setting state directly?

  - A: Actions are dispatched from event handlers and tell the developer what the user just did. They are an objets followed by the keyword `dispatch({"action...})` Setting state in react is different as we are telling what to React to do. With actions, we are receiving what the user just did. 
  

- Q: What common list operation is useReduce named for, and why?

  - A: The `useReducer()` hooks name is derived from the `reduce()` operation which allows the developer to take an array and "accumulate" a single value out of several. The function you pass to reduce is known as a “reducer”. It takes the result so far and the current item, then it returns the next result. `useReducer()` is the same as we pass in the action and state and return the next state.

- Q: When should you switch from useState to useReducer?

  - A: Its recommended to use `useReducer()` when bugs arrise with incorrect state updates.

## Bookmark and Review

- [useReducer hook](https://react.dev/reference/react/useReducer)

- [Keeping Components Pure](https://react.dev/learn/keeping-components-pure)

- [Queueing a Series of State Updates](https://react.dev/learn/queueing-a-series-of-state-updates)

## Reflection

- Q: What are your learning goals after reading and reviewing the class README?

  - A: Learning goals are to build a foundation of `useReducer` and be able to implement it as easily as useState

## Things I want to know more about

React and all those hooks
