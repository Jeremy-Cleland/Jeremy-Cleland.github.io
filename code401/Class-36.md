# Class 36 Reading Notes | Application State with Redux

## [Dan Abramov Redux Tutorials](https://egghead.io/courses/getting-started-with-redux)

- Q: What is the first principle of Redux?

  - A: The first principal is that all of the state will be in a single JavaScript object.

- Q: what is a store and what do we use our reducers for within that store?

  - A: In Redux, a store is an object that holds the application state and provides a way to access and update the state. It is created using the createStore function provided by the Redux library.

``` JS
import { createStore } from 'redux';

const initialState = {
  counter: 0
};

function counterReducer(state = initialState, action) {
  switch (action.type) {
    case 'INCREMENT':
      return { ...state, counter: state.counter + 1 };
    case 'DECREMENT':
      return { ...state, counter: state.counter - 1 };
    default:
      return state;
  }
}

const store = createStore(counterReducer);

``` 

  In this example, we first import the `createStore` function from the Redux library. We then define an initial state object and a reducer function called `counterReducer` that handles actions related to a counter. The `createStore` function is called with the reducer function as an argument, and it returns a new store object.

  Reducers are functions that take in the current state and an action object and return a new state based on the action type. In the example above, the `counterReducer` function handles actions with the types INCREMENT and DECREMENT and updates the counter in the state accordingly.

  The store object provides several methods to interact with the state, such as `getState()` to retrieve the current state, `dispatch(action)` to dispatch an action to the reducer, and `subscribe(listener)` to register a listener function that is called whenever the state changes.

  Overall, the store and reducers in Redux work together to provide a predictable and manageable way to manage the application state.

- Q: Name three Redux store methods given to us by createStore and describe their use.

  - A:
    - `getState()`
    - `dispatch()`
    - `subscribe()`

- Q: Explain to a non-technical recruiter what combineReducers() does and why it is useful.

  - A: `combineReducers()` is a function provided by the Redux library in JavaScript that allows you to combine multiple reducers into a single reducer function.

  In a Redux application, a reducer is a pure function that takes the current state and an action, and returns a new state. It's responsible for updating the state of the application in response to actions dispatched by the user or other parts of the application.

  When you have a complex application with many different features and pieces of state to manage, you might have multiple reducers, each responsible for updating a different part of the application's state.

  `combineReducers()` allows you to combine these individual reducers into a single reducer function, which can then be used to create the store. This makes it easier to manage the state of your application as it grows and becomes more complex.

  For example, if you have two reducers, one for managing the user's authentication state and another for managing their shopping cart, you can use `combineReducers()` to combine them into a single reducer function that handles both states.

  Using `combineReducers()` can also make your code more modular and easier to maintain, as each reducer can focus on a specific part of the application's state without needing to worry about the rest of the state.

  Overall, `combineReducers()` is a useful tool for managing complex application state in a more organized and modular way.


## Bookmark and Review

[worlds easiest guide to redux](<https://medium.freecodecamp.org/understanding-redux-the-worlds-easiest-guide-to-beginning-redux-c695f45546f6>)
)

[testing reducers](https://medium.com/@netxm/testing-redux-reducers-with-jest-6653abbfe3e1)

[Redux Docs](https://redux.js.org/)

## Things I want to know more about
