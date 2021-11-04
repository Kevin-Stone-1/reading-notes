# Class 09 Reading Notes

## Functional Programming

1. What is functional programming?

- Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data. (I pulled this directly from Wikipedia at: https://en.wikipedia.org/wiki/Functional_programming)

2. What is a pure function and how do we know if something is a pure function?

- A pure function is a function that that returns the same result when it is given the same arguments. So it is a function that does not cause any observable side effects when called or invoked.

4. What are the benefits of a pure function?

- One benefit of pure functions is that it is easier to test, they are immutable, and referentially transparent.

5. What is immutability?

- Immutability means that the funciton cannot be changed now or in the future.

6. What is Referential transparency?

- Referential transparency means that an expression can be replaced by its result.

## Node JS and require()

1. What is a module?

- A module is a way to seperate your code logically into different compononets to make it easier to refactor and easier for people to read.

2. What does the word ‘require’ do?

- require is a global function within Node JS that can reauire modules across pages it is written like this...

```
require('./count')
```

3. How do we bring another module into the file the we are working in?

- Inside of the module you are trying to pass you need to tell it to pass into the other module using

```
module.exports = mod you want outside
```

4. What do we have to do to make a module available?

- We need to create a variable and set it to whatever we want to return to whateverthe module we are exporting.
