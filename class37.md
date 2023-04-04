#### Multiple Reducers Example

Why create multiple reducers?
Creating multiple reducers allows you to split the responsibility of managing different parts of the application state among different functions. This can make the code easier to maintain, test, and reason about.

How would you combine multiple reducers?
You can combine multiple reducers using the combineReducers function. The combineReducers function takes in an object as an argument. The object contains key-value pairs where the key is the name of the reducer and the value is the reducer function.

How will you manage state as an immutable object? why?
You will manage state as an immutable object because it is easier to reason about and test. It also makes it easier to detect changes in the state.

#### Redux Docs: Using Combined Reducers

combineReducers is a utility function to simplify the most common use case when writing Redux reducers. 

Explain how combineReducers assembles the new state tree.
 When an action is dispatched, combineReducers calls all of the individual reducers and combines their results into a single state tree. The process involves calling each reducer with the current slice of state that corresponds to its part of the state tree and the current action, then merging all of the updated slices of state into a single object. The returned object contains all of the updated state slices.

How would you define initial state in an app using combineReducers?
You can define initial state in an app using combineReducers by passing an object as the second argument to the combineReducers function. The object contains key-value pairs where the key is the name of the reducer and the value is the initial state for that reducer.

Redux Docs: Combined Reducer Syntax

Why will you want to split your reducing functions as your app becomes more complex?
You will want to split your reducing functions as your app becomes more complex because it makes it easier to maintain and test your code.

The combineReducers helper function turns an object whose values are different reducing functions into a single reducing function you can pass to createStore.

What is a popular convention when naming reducers?
A popular convention when naming reducers is to name them after the state slice they manage.