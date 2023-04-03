# Class 39 Reading Notes | 

## [Redux Toolkit (RTK)](https://redux-toolkit.js.org/introduction/getting-started)

- Q: What concerns are addressed by Redux Toolkit?

  - A:

  1. Configuring a Redux store is too complicated

  1. I have to add a lot of packages to get Redux to do anything useful

  1. Redux requires too much boilerplate code

- Q: What does configureStore() do?

  - A: `configureStore()`: wraps createStore to provide simplified configuration options and good defaults. It can automatically combine your slice reducers, adds whatever Redux middleware you supply, includes redux-thunk by default, and enables use of the Redux DevTools Extension.

- Q: How would I use createSlice()?

  - A: 
    1. createSlice accepts a single configuration object parameter, with the following options
    1. The initial state value for this slice of state.
    1. An object containing Redux "case reducer" functions (functions intended to handle a specific action type, equivalent to a single case statement in a switch).
    1. Lastly, extraReducers which allows createSlice to respond to other action types besiders the types it has generated. 

## [MobX](https://mobx.js.org/getting-started.html)

- Q: What is Mobx?

  - A: MobX is a simple, scalable and battle tested state management solution.

- Q: How does MobX make it “impossible” to produce an inconsistent state?

  - A: MobX makes state management simple again by addressing the root issue: it makes it impossible to produce an inconsistent state The strategy to achieve that is simple: Make sure that everything that can be derived from the application state, will be derived. Automatically.

- Q: How would we build a reactive user interface?

  - A: React components are (despite their name) not reactive out of the box. The observer HoC wrapper from the mobx-react-lite package fixes that by basically wrapping the React component in autorun. This keeps the component in sync with the state. This is conceptually not different from what we did with the report before.

## [Tutorial](https://redux-toolkit.js.org/tutorials/intermediate-tutorial)

- Q: What take-away(s) did this tutorial provide?

  - A: React components dispatch actions to update the store using the useDispatch hook

## Things I want to know more about
