# Class 38 Reading Notes | Redux - Asynchronous Actions

## [async actions](https://redux.js.org/advanced/asyncactions)

- Q: Why use Redux middleware?

  - A: Redux middleware were designed to enable writing logic that has side effects.

- Q: Consider the Redux Async Data Flow Diagram. Describe the flow in your own words.


  - A: The Redux async data flow diagram illustrates the process of handling asynchronous actions in a Redux application. It typically involves middleware to manage the asynchronous nature of API calls or other external data sources.

  1. User interaction: The user interacts with the application by performing an action, such as clicking a button or s ubmitting a form, that requires fetching data from an API or performing some other asynchronous operation.

  1. Action creator: In response to the user interaction, an action creator function is called. This function returns a plain JavaScript object representing the action, but instead of dispatching the action immediately, it dispatches a function that will handle the asynchronous operation.

  1. Middleware: When the function is dispatched, Redux middleware, such as Redux Thunk or Redux Saga, intercepts it. Middleware acts as a bridge between the action creator and the reducer, allowing you to execute side effects like async API calls or other asynchronous operations.

  1. Async operation: The middleware initiates the asynchronous operation, such as fetching data from an API or reading from a database.

  1. Action dispatch: Once the asynchronous operation is complete, the middleware dispatches a new action, usually with a different action type, to the Redux store. This action contains the results of the async operation, such as the fetched data or any error messages.

  1. Reducer: The Redux store receives the action and calls the corresponding reducer function to handle the action. The reducer updates the application state based on the action type and payload, creating a new state object without modifying the existing one.

  1. Store update: The Redux store updates its state with the new state object returned by the reducer.

  1. UI update: The updated state is propagated to the React components (or components of other view libraries) through the connect function or hooks like useSelector. The components then re-render based on the updated state, reflecting the results of the asynchronous operation in the UI.

- Q: How are we accommodating async in our Redux app?


  - A: C We can help accomadate async in reduct by creating async action creators: Instead of dispatching plain   JavaScript objects as actions, async action creators dispatch functions (or other special objects, depending on the middleware) that handle the async logic. For example, with Redux Thunk, you can create an action creator that returns a function:

## [thunk middleware](https://github.com/reduxjs/redux-thunk)

- Q: Why would you need redux-thunk middleware?


  - A: Thunks are the recommended middleware for basic Redux side effects logic, including complex synchronous logic that needs access to the store, and simple async logic like AJAX requests.

- Q: Redux Thunk middleware allows you to write action creators that return a ____ instead of an action.

  - A: Dispatch functions

- Q: Describe how any return value from the inner thunk function will be made available.

  - A: Any return value from the inner function will be available as the return value of dispatch itself.

## Things I want to know more about
