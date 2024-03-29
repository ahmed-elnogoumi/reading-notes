## How to use Forms in React

1. What is a ‘Controlled Component’?
    - A form element that's controlled by the React state.
2. Should we wait to store the users responses from the 
form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.
    - Wait to update the state with the responses as soon as they're entered. They get real-time vallidation, instant feedback and a smoother user experience.
3. How do we target what the user is entering if we have an event handler on an input field?
    - event.target.value

## The Conditional (Ternary) Operator Explained

1. Why would we use a ternary operator?
    - A concise way to write conditional statements in JS. It makes code much more readable and maintainable.
2. Rewrite the following statement using a ternary statement:
```
if(x===y){
  console.log(true);
} else {
  console.log(false);
}
```

```
x === y ? console.log(true) : console.log(false);
```