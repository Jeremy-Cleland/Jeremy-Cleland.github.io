# Class 28 Reading Notes | Component Lifecycle / `useEffect` Hook

## [useEffect hook](https://react.dev/reference/react/useEffect#reference)

- Q: What is the main intended use case for the useEffect hook?

  - A: Call `useEffect` at the top level of your component to declare an Effect:

- Q: How does the effect’s logic interact with the component?

  - A: We need to put our side-effect logic into the callback function, then use the dependencies argument to control when you want the side-effect to run. It's important that the component rendering and the side-effect logic are independent.

- Q: What is the importance of the return value from the effect’s logic function?

  - A:  It should return a cleanup function with cleanup code that disconnects from that system.

## Bookmark and Review

- [Responding to Events](https://react.dev/learn/responding-to-events)

- [Conditional Rendering](https://react.dev/learn/conditional-rendering)

- [Updating Arrays in State](https://react.dev/learn/updating-arrays-in-state)

- [Updating Objects in State](https://react.dev/learn/updating-objects-in-state)

## Relection

- Q: What are your learning goals after reading and reviewing the class README?

  - A:
  
## Things I want to know more about
