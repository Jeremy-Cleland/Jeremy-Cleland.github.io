# Class 27 Reading Notes | `useState()` Hook

## [Thinking in React](https://react.dev/learn/thinking-in-react)

- Q: Summarize the five steps of thinking in react.

  - 1. Break the UI into a components by drawing boxes around components and placing them in a hierarchy.
  - 1. Build a static version in React that only renders the UI, but don't add interactivity.
  - 1. Find the minimal but complete representation of UI state.
  - 1. Identify where your state should live. 
  - 1. Add inverse data flow

## [State: A Component’s Memory](https://react.dev/learn/state-a-components-memory)

- Q: What is one reason a local variable isn’t sufficient for managing a React component?

  - A:
    - Local variables don’t persist between renders. When React renders this component a second time, it renders it from scratch—it doesn’t consider any changes to the local variables.
    - Changes to local variables won’t trigger renders. React doesn’t realize it needs to render the component again with the new data.

- Q: What is the argument to the `useState` hook, and what are the two parts of its return array?

  - A: The argument passed in the `useState` hook is the inital state value. When the component is rendered for the first time the first value will be the initial value followerd by state setter function. The

- Q: How can Component A access state from Component B?

  - A: You need to lift the state up to the parent component.

    - Steps
  
      1. Remove state from the child components.
      1. Pass hardcoded data from the common parent.
      1. Add state to the common parent and pass it down together with the event handlers.

## Bookmark and Review

- [Passing Props to a Component](https://react.dev/learn/passing-props-to-a-component)

- [Rendering Lists](https://react.dev/learn/rendering-lists)

- [State as Snapshot](https://react.dev/learn/state-as-a-snapshot)

- [useState hook](https://react.dev/reference/react/useState)

## Reflection

- Q: What are your learning goals after reading and reviewing the class README?
A: The learning goal for this class is to become comfortable with the `useState` hook.

## Things I want to know more about

ALL THE HOOKS