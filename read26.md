#### React Quick Start

What are the building blocks of a React app?
 The building blocks of a React app include:
Components , JSX

What is the difference between an HTML element and a React component?
An HTML element is a basic building block of a web page, defined by a tag name.
A React component, on the other hand, is a reusable piece of UI that can contain one or more HTML elements, and can have its own properties, state, and lifecycle methods. 
  
What is JSX and why do we use it?
JSX is a syntax extension of JavaScript that allows you to write HTML-like code in your JavaScript files. 

Describe the process of embedding JavaScript expressions in JSX.
In JSX, you can embed JavaScript expressions by wrapping them in curly braces {}.
This allows you to dynamically generate content or apply logic based on the component's properties, state, or other variables.
  
Does React or JSX have any special features for iteration or conditional logic?
For iteration, React provides the map() method, which allows you to iterate over an array of data and return a new array of React elements.
For conditional logic, React provides the ternary operator.
  
How does React know to respond to a user’s inputs?
React responds to a user's inputs through the use of event handlers.
  
What word indicates that a React component manages data with a Hook?
The word that indicates that a React component manages data with a Hook is "useState". 
  
How can two react components share data?
Two react components share data through "props".
Render and Commit

#### Render and Commit
What are the three steps of refreshing a React UI?
Triggering a render 
Rendering the component 
Committing to the DOM 
  
How do you trigger updates to a component after the initial render?
Once the component has been initially rendered, you can trigger further renders by updating its state with the set function.
  
Does React recreate DOM nodes on every rerender?
During the initial render, React will create the DOM nodes.
During a re-render, React will calculate which of their properties, if any, have changed since the previous render. It won’t do anything with that information until the next step, the commit phase.
  
After React has updated the DOM, what still needs to happen before the user sees the change?
After rendering is done and React updated the DOM, the browser will repaint the screen.  
  
Things I want to know more about : hooks
  
  
  
  
