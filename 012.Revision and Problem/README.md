# Revision and Problem Solving – CodeXam
🎉

### Read This on Github

This article is available on Github. You can read it there and contribute to it.

[

Github Link

](https://github.com/Subham-Maity/javascript_codexam)[

Any Issue ?

](https://github.com/Subham-Maity/javascript_codexam/issues/new)

![](https://media.giphy.com/media/3ov9k4e03yTNRWTgYM/giphy.gif)

```
let age = prompt("Please enter your age:");
age = parseInt(age); // convert the age to an integer
 
if (age >= 13 && age <= 19) {
console.log("Your age is between 13 and 19");
} else {
console.log("Your age is not between 13 and 19");
}
```


### ⚡ Playground[](#-playground)

[Check Here (opens in a new tab)](https://stackblitz.com/edit/js-6nrf8u?devToolsHeight=33&file=index.js)

```
let age = 15;
 
switch (true) {
case age >= 13 && age <= 19:
console.log("Your age is between 13 and 19");
break;
default:
console.log("Your age is not between 13 and 19");
}
```


### ⚡ Playground[](#-playground-1)

[Check Here (opens in a new tab)](https://stackblitz.com/edit/js-xwmpxd?devToolsHeight=33&file=index.js)

```
let number = 12;
 
if (number % 2 == 0 && number % 3 == 0) {
console.log(`${number} is divisible by 2 and 3`);
} else {
console.log(`${number} is not divisible by 2 and 3`);
}
 
```


This code will check if the value of the number variable is divisible by 2 and 3 by using the modulo operator to calculate the remainder of number divided by 2 and 3. If both remainders are equal to 0, it will print a message saying that the number is divisible by 2 and 3. If either remainder is not equal to 0, it will print a message saying that the number is not divisible by 2 and 3.

For example, if the value of number is 12, the code will output: "12 is divisible by 2 and 3"

You can also use the logical OR operator (||) to check if the number is divisible by 2 or 3:

```
if (number % 2 == 0 || number % 3 == 0) {
console.log(`${number} is divisible by 2 or 3`);
} else {
console.log(`${number} is not divisible by 2 or 3`);
}
```


This will check if the value of the number variable is divisible by 2 or 3 by using the modulo operator to calculate the remainder of number divided by 2 and 3. If either remainder is equal to 0, it will print a message saying that the number is divisible by 2 or 3. If both remainders are not equal to 0, it will print a message saying that the number is not divisible by 2 or 3.

### ⚡ Playground[](#-playground-2)

```
let age = 20;
let result = age > 18 ? "You can drive" : "You can not drive";
 
console.log(result);
```


### ⚡ Playground[](#-playground-3)