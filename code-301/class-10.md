# Class 10 Reading Notes

## Understanding the JS Call Stack

1. What is a ‘call’?

- A call means that you are invoking a function.

2. How many ‘calls’ can happen at once?

- There can only be one call called at a time and they go from top to bottom

3. What does LIFO mean?

- LIFO means Last in First out.

4. Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.

![IMG](/img/CallStack.PNG)

5. What causes a Stack Overflow?

- A stack oveflow occurs when there is a recursive function without an exit point and the call stack overflows.

## JavaScript Error Messages

1. What is a ‘refrence error’?

- A reference error occurs when you try and use a variable that is not defined.

2. What is a ‘syntax error’?

- A syntax error occurs when something cannot be parsed through in the syntax.

3. What is a ‘range error’?

- The range error occcurs when a value is not in the set or range of allowed values.

4. What is a ‘type error’?

- A tyoe error is when an operation could not be performed, typically when a value is not of the expected type.

5. What is a breakpoint?

- A breakpoint error breaks the code from wherever you placed the debugger at to allow for further investigation into your code.

6. What does the word ‘debugger’ do in your code?

- The debugger allows us to dive deeper into our code and run certain functions while not running others.
