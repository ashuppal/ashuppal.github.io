#### Choosing the State Structure

Summarize the five principles for structuring state.
1. Group related state. If you always update two or more state variables at the same time, consider merging them into a single state variable.
2. Avoid contradictions in state. If two state variables can be derived from each other, then one of them is redundant.
3. Avoid redundant state. If two state variables have the same value, then one of them is redundant.
4. Avoid duplication in state. If two state variables have the same value, then one of them is redundant.
5. Avoid deeply nested state. Deeply hierarchical state is not very convenient to update. When possible, prefer to structure state in a flat way.


#### Passing State Deeply with Context

What problem do Contexts aim to solve?
Context provides a way to pass data through the component tree without having to pass props down manually at every level.

What is one technique to try before useContext?
Pass props

What hook complements useContext for complex applications?
useReducer

