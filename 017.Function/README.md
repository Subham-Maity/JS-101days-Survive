# Functions – CodeXam
Modern JavaScript Function Syntax

![](https://media.giphy.com/media/30pykuIQHxzQsfefte/giphy.gif)

In modern JavaScript, there are several ways to define functions. Here are a few examples:

1.  Function Declaration

```
function greet(name) {
console.log("Hello, " + name + "!");
}
```


This is the traditional way to define a function in JavaScript. The function is declared with the `function` keyword, followed by the function name, a list of parameters in parentheses, and the function body in curly braces.

2.  Function Expression

```
const greet = function(name) {
console.log("Hello, " + name + "!");
}
```


In this syntax, the function is assigned to a variable using the const keyword. This is called a "function expression".

3.  Arrow Function:

```
const greet = (name) => {
console.log("Hello, " + name + "!");
}
```


An arrow function is a shorthand syntax for defining a function expression. It is written using the => syntax.

4.  Arrow function with a single parameter and a concise body

```
const greet = name => console.log("Hello, " + name + "!");
```


If the function has a single parameter, you can omit the parentheses around the parameter list. If the function has a single statement in its body, you can omit the curly braces and the return keyword.

5.  Arrow function with no parameters and a concise body

```
const greet = () => console.log("Hello, world!");
```


If the function has no parameters, you must include empty parentheses in the parameter list.

6.  Arrow function with a single parameter and a block body

```
const greet = name => { console.log("Hello, " + name + "!"); }
```


If the function has a single parameter, you can omit the parentheses around the parameter list. If the function has a single statement in its body, you can omit the curly braces and the return keyword.

#### ⚡ Playground[](#-playground-1)