# Class 04 Reading Notes

## Forms

1. What is a ‘Controlled Component’?

- A controlled component set and gets value from the state property.

2. Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.

- Yes, we should wait until the user submits the form. It therefore will not have to render everytime and the user can go back and change soe data if they need to.

3. How do we target what the user is entering if we have an event handler on an input field?

- The way you would handle the multiple inputs with an event handler is by calling the event.target.name

## Conditional (Ternary) Operator

1. Why would we use a ternary operator?

- This allows for a lot less code and once you understand the conditional operators then will make you code more DRY.

2. Rewrite the following statement using a ternary statement:

```
if(x === y){
  console.log(true);
} else {
  console.log(false);
}
```

```
let z = x === y ? true : false;
```
