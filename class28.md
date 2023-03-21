Reading
#### useEffect hook

What is the main intended use case for the useEffect hook?
useEffect is a React Hook that lets you synchronize a component with an external system. It is a combination of componentDidMount, componentDidUpdate, and componentWillUnmount. It is used to fetch data from an API, set up a subscription, and manually change the DOM in React components.

How does the effect’s logic interact with the component?
The effect’s logic function is called after every render, by default. You can tell React to skip applying an effect if certain values haven’t changed between re-renders. To do so, pass an array as an optional second argument to useEffect. This array contains the values that the effect depends on. If any of these values change between re-renders, the effect will re-run.


What is the importance of the return value from the effect’s logic function? (Ref:https://legacy.reactjs.org/docs/hooks-effect.html)
Every effect may return a function that cleans up after it. This lets us keep the logic for adding and removing subscriptions close to each other. They’re part of the same effect!
The return value from the effect’s logic function is used to clean up the effect. This is important because it allows us to avoid memory leaks. If we don’t clean up the effect, it will continue to run even after the component is unmounted. This can cause memory leaks and other issues.

What are your learning goals after reading and reviewing the class README?
I want to learn more about the useEffect hook and how to use it in my projects.