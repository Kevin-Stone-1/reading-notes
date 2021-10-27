# Class 03 Reading Notes

## Lists and Keys

1. What does .map() return?

- .map() returns a new array with new values after running an operation on an array. It does not manipulate the original array.

2. If I want to loop through an array and display each value in JSX, how do I do that in React?

- You need to use curly braces to build a collection of elements and include them in JSX

3. Each list item needs a unique **\_**.

- Key

4. What is the purpose of a key?

- Keys identify which items in React have been manipulated (changed, added, or removed)

## Spread Operator

1. What is the spread operator?

- The spread operator can take an existing array and add another element to it while not changing the original array.

2. List 4 things that the spread operator can do.

- The spread operator can pass props, generate multiple componenet instances, can set the state with a dynamic key name, and can add a single item to the start or end of an array.

3. Give an example of using the spread operator to combine two arrays.

```
let array1 = [1,2,3];
let array2 = [4,5,6];
let combine = [...array1, ...array2];
```

4. Give an example of using the spread operator to add a new item to an array.

```
let array1 = [1,2,3];
let array2 = [...array1, 4];
```

5. Give an example of using the spread operator to combine two objects into one.

```
let person1 = {name: Jimmy, state: FL};
let person2 = {name: John, state: CA};
let combine = {...person1, ...person2};
```

## How To Pass Functions Between Components

1. In the video, what is the first step that the developer does to pass functions between components?

- The first thing in the video he does is finds the state and creates an increment function right after it.

2. In your own words, what does the increment function do?

- I think the increment function simply changes the state to whatever you want it to be in the function

3. How can you pass a method from a parent component into a child component?

- You pass a method from a parent component into a child component using prop NOT state

4. How does the child component invoke a method that was passed to it from a parent component?

- You simply use the this.props.name
