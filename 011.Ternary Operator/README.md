# Ternary Operator – CodeXam
🎉

### Read This on Github

This article is available on Github. You can read it there and contribute to it.

[

Github Link

](https://github.com/Subham-Maity/javascript_codexam)[

Any Issue ?

](https://github.com/Subham-Maity/javascript_codexam/issues/new)

❓ Syntax of Ternary Operator[](#-syntax-of-ternary-operator)
------------------------------------------------------------

![](https://media.giphy.com/media/z9QKjUcaIjJbbacGyw/giphy.gif)

In JavaScript, the ternary operator (also known as the conditional operator) is a short, concise way to write an if-else statement. It has the following syntax:

```
condition ? valueIfTrue : valueIfFalse
```


*   `condition` is an expression that is evaluated to a boolean value (either true or false).
*   `valueIfTrue` is the value that will be returned if condition is true.
*   `valueIfFalse` is the value that will be returned if condition is false.

📖 Simple Example of Ternary Operator[](#-simple-example-of-ternary-operator)
-----------------------------------------------------------------------------

```
let x = 10;
let y = (x > 0) ? 'positive' : 'negative';
console.log(y); // Output: 'positive'
```


*   In this example, the ternary operator will evaluate the condition x > 0, which is true because x is greater than 0. Therefore, the value of y will be set to 'positive'.

```
let a = 10;
let b = 20;
let max = (a > b) ? a : b;
console.log(max); // Output: 20
```


*   In this example, the ternary operator will evaluate the condition a > b, which is false because a is not greater than b. Therefore, the value of max will be set to b, which is 20.

The ternary operator can be used to concisely write if-else statements that only have two branches, but it is not suitable for more complex if-else statements with multiple branches. In those cases, it is recommended to use a regular if-else statement.

### ⚡ Playground[](#-playground)