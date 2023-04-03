What is the first principle of Redux?
You are going to represent the whole state of your application in a single javascript object. All changes are explicit and predictable. This is the first principle of Redux.

what is a store and what do we use our reducers for within that store?
A store is a javascript object that holds the state of your application. We use reducers to update the state of our application.

Name three Redux store methods given to us by createStore and describe their use.

getState(): This method returns the current state of the Redux store. It can be useful for debugging or for accessing a particular value from the store.

dispatch(action): This method is used to dispatch an action to the store.

subscribe(listener): This method is used to subscribe a listener function to the store. 

Explain to a non-technical recruiter what combineReducers() does and why it is useful.
Imagine you have a large puzzle with many pieces. Instead of trying to put all the pieces together at once, you break the puzzle down into smaller sections and work on each section individually. Once each section is complete, you combine them together to form the entire puzzle.
Similarly, combineReducers() allows you to break down a large and complex state into smaller, more manageable pieces, each with its own reducer function. This makes it easier to manage your application state and also makes your code more modular and easier to maintain.

Looking ahead at this module’s course schedule, What do you look forward to learning?
I look forward to learning about the Redux in more detailed.

What are your learning goals after reading and reviewing the class README?
Redyx store methods, combineReducers(), and the Redux in more detailed.