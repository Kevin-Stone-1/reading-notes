# JS Operators & Loops

## JS Operators

### Assignment Operator
- This assigns a value to the left of the operand based off the value on its right.
```
x = y
```
### Comparison Operator
- This compares the operands and returns a value whether the value is true.
```
==
```
### Arithmetic Operator
- This allows numerical values to create another numerical value.
```
5 / 10;
```
### Bitwise Operator
- This lets the operand be a set of 32 bits rather than a decimal hexadeciaml, or octal numbers.
```
b | c
```
### Logical Operator
- This is mostly used with boolean values.
```
expression1 && expression2
```
### String Operator
- This can be used with concatenations from one string to another string.
```
console.log('this is a'  + ' string');
```
### Conditional (ternary) Operator
- This takes three operands.
```
condition ? val3 : val4
```
### Comma Operator
- This evaluates its operands and returns the last operand value.
```
var y = [1, 3, 5, 7, 9]
```
### Unary Operator
- This uses only a single operand.
```
delete Math.property;
```
### Relational Operator
- This compares the operand and returns a Boolean value based on whether the ecomparison is true or not.
```
propertyName in object
```

JavaScript has quite a few operators and these operators can be used to create functions and other statements that help sift through data.

## Expressions

There are two types of expressions the first type is called an expression with side effects and those that do not have side effects.

### For Instance:

y = 10, is an example of an expression with side effects

whereas

3 + 4 is an exapmle of an expression without side effects

### JavaScript Expression Categories

- Left-hand-side expressions: The values on the left are the destination of an assignment
- Primary expressions: These are general expressions and keywords that are in JavaScript
- Logical expressions: These expressions evaluate to a Boolean true or false
- String expressions: These expressions always will evaluate to a string
- Arithmetic: These evaluate to integers and numbers

## Loops and Iteration

Loops are ways to allow you to do something repeatedly. Instead of writing a single function for one action and then repeating that function multiple times. You cna instead create a loop that starts at the beginning of a set of data and iterate through the data to accomplish the task you put it out to do. There are multiple types of loop statements.

### Loop Statements

- for
- do...while
- while
- labeled
- break
- continue
- for...in
- for...of

Although there are all these loops we are going to focus on two. The for loop statement and the while loop statement.

### For Loop
For loops repeat until a specified end condition is evaluated to false. It basically starts at 0 and goes through the amount of data and stops.

#### Take a look at this example:

```
let string = '';

for (let idx = 0; i < 5; idx++) {
  string = string + i;
}
```

### While Loop
While loops only carry out its statements as long as the specified condition evaluates to true *not* false.

#### Take a look at this example:

```
while (index < 5) {
  text += "The number is " + index;
  index++;
}
```

[Home](README.md)