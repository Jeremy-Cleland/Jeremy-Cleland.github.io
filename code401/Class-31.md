# Class 1 Reading Notes | Context API

## [Choosing the State Structure](https://react.dev/learn/choosing-the-state-structure)

- Q: Summarize the five principles for structuring state.

  - A: 
    1. Group-related state. Consider combining many state variables into one if you consistently update two or more of them at once.
    1. Avoid state inconsistencies. There is space for error when the state is set up so that different parts of the state may conflict and "disagree" with one another.
    1. Avoid being redundant. You shouldn't add information to a component's state if it can be calculated from its props or already-existing state variables during rendering.
    1. Avoid state duplication. It is challenging to keep them in sync when the same data is duplicated between numerous state variables or within nested objects. As far as you can, lessen duplication.
    1. Avoid states that are deeply nested. An extremely hierarchical state is difficult to update. Prefer a flat structure for states whenever practical.

## [Passing State Deeply with Context](https://react.dev/learn/passing-data-deeply-with-context)

- Q: What problem do Contexts aim to solve?

  - A: Prop drilling. Without explicitly giving it through props, context enables the parent component to make some information accessible to all components in the tree below it, regardless of how deeply they are nested.

- Q: What is one technique to try before useContext?

  - A:
  
  1. Pass props where needed to make sure you actually need useContext()
  1. Extract components and pass JSX as children to them. (When you nest content inside a JSX tag, the parent component will receive that content in a prop called children)

- Q: What hook complements useContext for complex applications?

  - A:  A reducer and context are frequently used to manage complex state and smoothly transfer it to far-off components.

## Bookmark and Review

[Sharing State Between Components Preserving and Restting State](https://react.dev/learn/sharing-state-between-components)

## Things I want to know more about
