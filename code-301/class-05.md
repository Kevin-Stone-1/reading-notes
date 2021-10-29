# Class 05 Reading Notes

## Thinking in React

1. What is the single responsibility principle and how does it apply to components?

- The single responsibility principle is the idea that every component should do one thing and one thing only. If a single component begins to grow then it should break down into smaller subcomponents.

2. What does it mean to build a ‘static’ version of your application?

- When you build a static app you build out an app that takes the data model and then renders the user interface with no functionality to it. The best practice is to build components and that reuse other comonents that use props to pass from one to the other. DO NOT use state in the static build.

3. Once you have a static application, what do you need to add?

- After you have a static application you should add state next.

4. What are the three questions you can ask to determine if something is state?

- Is it passed in from a parent via props? If so, it probably isn’t state.
- Does it remain unchanged over time? If so, it probably isn’t state.
- Can you compute it based on any other state or props in your component? If so, it isn’t state.
  (I pulled this directly from the React Documents at https://reactjs.org/docs/thinking-in-react.html)

5. How can you identify where state needs to live?

- You identify where the state needs to live by finding the owner or common owners and putting it in the highest part of the heirarchy or possibly even making a new file just for that component above the highest part of the heirarchy you found.

## Higher-Order Functions

1. What is a “higher-order function”?

- Higher order functions are functions that operate on other functions; they can take the as arguments or return them.

2. Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?

- In line 2, I think that the variable m is becoming any number that is greater than or equal to the variable n.

3. Explain how either map or reduce operates, with regards to higher-order functions.

- Map and reduce seem to be higher order functions since they are in fact their own function that is creating its own action. Or basically they are just functions that can operate on other functions.
