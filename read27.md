#### Thinking in React

Summarize the five steps of thinking in react.
1. Break the UI into a component hierarchy
2. Build a static version in React
3. Identify the minimal (but complete) representation of UI state
4. Identify where your state should live
5. Add inverse data flow



#### State: A Component’s Memory

What is one reason a local variable isn’t sufficient for managing a React component?
Local variables are not accessible to other components. They are only accessible to the component that created them.

What is the argument to the useState hook, and what are the two parts of its return array?
The argument to the useState hook is the initial state. The two parts of the return array are the current state and a function that updates the state.

How can Component A access state from Component B?
Component A can access state from Component B by passing a function as a prop to Component B. The function can then be called by Component B to update the state of Component A.

What are your learning goals after reading and reviewing the class README?
Using hooks to manage state and props, and using the useState hook to manage state.