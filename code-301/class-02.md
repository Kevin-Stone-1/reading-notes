# Class 02 Reading Notes

## React Lifecycle

1. Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?

- Render is before componentDidMount.

2. What is the very first thing to happen in the lifecycle of React?

- Mounting
  1. constructor
  2. getDerivedStateFromProps
  3. render
  4. componentDidMount

The render is the only required one that will always be called.

3. Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates

- constructor, render, componentDidMount, React Updates, componentWillUnmount

4. What does componentDidMount do?

- The componentDidMount method executes the code when the component is already placed in the DOM. This occurs only after a component is mounted.

## React State vs Props

1. What types of things can you pass in the props?

- Props are similar to arguments in a function. Things to initialize a component to or what you want your component to render like. They can easily be changed.

2. What is the big difference between props and state?

- PROPS you pass into a component and are handled outside of the component while STATE is handled inside that component and can be updated inside that component

3. When do we re-render our application?

- When the state is changed

4. What are some examples of things that we could store in state?

- State is something inside of a component that can store event listeners, strings, and numbers.
