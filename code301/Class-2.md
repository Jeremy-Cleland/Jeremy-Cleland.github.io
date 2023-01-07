# Class 02 Reading Notes | State and Props

[React lifecycle](https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093)

## Discussion Questions

- Q: Based on the diagram, what happens first, the `render` or the `componentDidMount`?

  - A: Render

- Q: What is the very first thing to happen in the lifecycle of React?

  - A: Constructor

- Q: Put the following things in the order that they happen: `componentDidMount`, `render`, `constructor`, `componentWillUnmount`, `React Updates`

  - A: Life Cycle in Order
    1. Constructor
    2. Render
    3. React Updates
    4. ComponentDidMount
    5. ComponentWillUnmount

- Q: What does componentDidMount do?

  - A: componentDidMount() is invoked immediately after a component is mounted (inserted into the tree). Initialization that requires DOM nodes should go here.

[React State vs Props](https://www.youtube.com/watch?v=IYvD9oBCuJI)

## Discussion Questions

- Q: What types of things can you pass in the props?

  - A: Data

- Q: What is the big difference between props and state?

  - A:

    - State is inside the component and updated inside the component.

    - Props are passed to other components, handled outside, and must be updated.

- Q: When do we re-render our application?

  - A: When the state changes and you want to display it.

- Q: What are some examples of things that we could store in state?

  - A: Counter, user input, forms. If the information is only handled inside the component and only inside that component, you should make it state.

## Things I want to know more about

Hooks!
