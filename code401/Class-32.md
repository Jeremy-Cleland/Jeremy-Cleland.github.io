# Class 32 Reading Notes | Context API - Behaviors

## [Scaling Up with Reducer and Context](https://react.dev/learn/scaling-up-with-reducer-and-context)

- Q: How do useReducer and useContext work together to simplify state management in a React application? (At least two paragraphs of prose.)

  - A: Without painstakingly handing the props down to each level, the useContext hook is used to create shared data that can be accessed throughout the component hierarchy. Every child components will have access to context defined without the use of "props." A potent state-management tool in React is React Context. React Context enables you to broadcast props to the components below rather than sending them down through each one one at a time.

  For complicated state transitions and manipulations, the useReducer hook is utilized. A reducer function and an initial state are both required arguments for the React hook function useReducer. Const [state, dispatch] = useReducer(reducer, initialState); Returns an array containing two values from this hook method.

## Bookmark and Review

## Things I want to know more about
