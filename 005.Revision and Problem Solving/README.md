# Revision and Problem Solving – CodeXam
➡️ Question 1[](#️-question-1)
------------------------------

Create a string type variable and try to add a number to it

To create a variable of type string in JavaScript, you can use the `var` or `let` keyword, followed by the name of the variable and the assignment operator `=`, and then the string value you want to assign to the variable, like this:

```
let str = 'This is a string';
const anotherStr = "This is another string";
```


To add a number to a string in JavaScript, you can use the `+` operator. However, this will result in the number being concatenated to the string, rather than being added to it as a mathematical operation. For example:

```
let str = 'The number is: ';
let num = 42;
 
console.log(str + num);  // Output: 'The number is: 42'
```


If you want to perform a mathematical operation on a number and a string, you will need to first convert the string to a number using JavaScript's `Number()` function. For example:

```
let str = '42';
let num = 2;
 
console.log(Number(str) + num);  // Output: 44
```


*   Note that if you try to perform arithmetic with a string that contains a number, JavaScript will attempt to convert the string to a number before performing the operation. For example:

```
let str = '42';
let num = 2;
 
let result = str * num;
 
console.log(result); // output: 84
```


*   However, if the string cannot be converted to a number (e.g. because it contains non-numeric characters), JavaScript will produce an error. For example:

```
let str = 'Hello, world!';
let num = 2;
 
let result = str * num;
 
// Throws an error: Uncaught TypeError: Cannot convert string to number (NaN - Not a Number)
```


➡️ Question 2[](#️-question-2)
------------------------------

Typeof operator to find the datatype of the concatenated string and number and explain why ?

The `typeof` operator is used to determine the data type of a value in JavaScript. When used on a string and number that have been concatenated (i.e., joined together), `typeof` will always return "string", because in JavaScript, the `+` operator is used to concatenate strings, regardless of the data types of the values being concatenated.

```
let x = "Hello";
let y = 123;
let z = x + y;
 
console.log(typeof z); // Outputs "string"
```


This is because JavaScript converts the number to a string before concatenating it with the string. So even though `y` is a number, the resulting value of `z` is a string.

It's worth noting that if you want to perform mathematical operations on a number that is concatenated with a string, you will need to first convert the string to a number using a function like `parseInt()` or `parseFloat()`.

```
 let x = "123";
 let y = 456;
 let z = x + y;
 
 let a = parseInt(x) + y;
 
 console.log(z); // Outputs "123456"
 console.log(a); // Outputs 579
```


Here, `z` is a string because it is the result of concatenating `x` and `y`, but a is a number because it is the result of adding `x` and `y` after `x` has been converted to a number using `parseInt()`.

➡️ Question 3[](#️-question-3)
------------------------------

Create a const object in javascript can you change it to hold a number later ?

The answer is No. You can't change the type of a constant variable. If you try to change the type of a constant variable, you will get an error.

```
const obj = {
    name: 'John'
};
 
obj = 42; // Throws an error: Uncaught TypeError: Assignment to constant variable.
```


➡️ Question 4[](#️-question-4)
------------------------------

Try to add a new key to the const object ?

you can simply add a new key to the const object. The const keyword only prevents reassignment of the variable identifier.

```
const obj = {
    name: 'John'
};
 
obj.age = 42; // No error
 
console.log(obj); // { name: 'John', age: 42 }
```


➡️ Question 5[](#️-question-5)
------------------------------

Write a JS program to create a word meaning dictionary of 5 words.

```
    const dictionary = {
    "word1": "meaning1",
    "word2": "meaning2",
    "word3": "meaning3",
    "word4": "meaning4",
    "word5": "meaning5"
};
 
    console.log(dictionary);
```


This program creates an object called `dictionary` with five key-value pairs, where the keys are the words and the values are the meanings. The dictionary is then logged to the console.

You can access the meanings of the words by using dot notation or bracket notation. For example:

```
console.log(dictionary.word1); // Output: "meaning1"
console.log(dictionary["word2"]); // Output: "meaning2"
```
