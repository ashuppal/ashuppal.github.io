Reading
#### Extracting State Logic into a Reducer

What is the motivation for adding a reducer?
A reducer is a function that takes the current state and an action as arguments, and returns a new state result. In other words, the reducer is a pure function that takes the previous state and returns the next state.

What are actions in the context of a reducer? How are they different than setting state directly?
Actions are payloads of information that send data from your application to your store. They are the only source of information for the store. You send them to the store using store.dispatch().

What common list operation is useReduce named for, and why?
The reduce() method executes a reducer function on each member of the array resulting in a single output value.

When should you switch from useState to useReducer?
When you have complex state logic that involves multiple sub-values or when the next state depends on the previous one.

Bookmark and Review
Keep these pages handy - they answer questions that show up regularly for this lab.


What are your learning goals after reading and reviewing the class README?
Using the reducer hook to manage state in my application.