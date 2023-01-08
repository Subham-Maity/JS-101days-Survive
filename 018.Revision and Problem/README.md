# Revision 3 – CodeXam
Let's revise what we have learned so far.

![](https://media.giphy.com/media/4SjlyrGuMvxxS/giphy.gif)

### ⁉️ Question 1:[](#️-question-1)

Write a program to print the marks of a student in an object using for loop

```
obj = {Subham: 90, Rahul: 80, Subhasish: 70, Rohit: 60, Xam: 50}
```


#### ℹ️ Answer:[](#ℹ️-answer)

```
let marks = {Subham: 90, Rahul: 80, Subhasish: 70, Rohit: 60, Xam: 50}
 
//type 1
for (let prop of Object.keys(marks)){
console.log(marks[prop])
}
 
//type 2
for(let i=0; i<Object.keys(marks).length;i++){
console.log("The marks of " + Object.keys(marks)[i] + " is " + marks[Object.keys(marks)[i]])
}
```


##### 📌 Explanation:[](#-explanation)

Type 1:

*   The `Object.keys(marks)` function returns an array of the keys (i.e., student names) of the marks object.

*   The for-of loop iterates over the elements of this array. On each iteration, the loop assigns the current key (i.e., student name) to the variable prop.
*   Inside the loop, the value of `marks[prop]` is logged to the console. This uses the square bracket notation to access the property of marks with the key stored in prop.

Type 2:

*   The loop initializes a counter variable i to 0.
    
*   The loop continues as long as i is less than the length of the array of keys returned by Object.keys(marks). The Object.keys(marks) function returns an array of the keys (student names) of the marks object.
    
*   On each iteration of the loop, the loop logs a string to the console that includes the name of the student (which is the current key stored in Object.keys(marks)\[i\]) and their marks (which is the value stored in marks\[Object.keys(marks)\[i\]\]).
    
*   The loop increments i by 1 on each iteration.
    

##### ⚡ Playground[](#-playground)

### ⁉️ Question 2:[](#️-question-2)

Try to solve the following question(Question 1) using the `for-in` loop.

#### ℹ️ Answer:[](#ℹ️-answer-1)

```
let marks = { Subham: 90, Rahul: 80, Subhasish: 70, Rohit: 60, Xam: 50 };
 
//type 1
for (let key in marks) {
console.log(marks[key]);
}
```


##### 📌 Explanation:[](#-explanation-1)

*   The for-in loop iterates over the properties (keys) of the marks object. On each iteration, the loop assigns the current key (student name) to the variable key.
*   Inside the loop, the value of `marks[key]` is logged to the console. This uses the square bracket notation to access the property of marks with the key stored in key.

##### ⚡ Playground[](#-playground-1)

### ⁉️ Question 3:[](#️-question-3)

Write a program to print "Ahh! Wrong Answer" until the user entered the correct number.

#### ℹ️ Answer:[](#ℹ️-answer-2)

```
let num = 8;
let nums;
while (nums != num) {
nums = prompt('Enter a number');
if (nums == num) {
console.log('Correct!');
break;
} else {
console.log('Ahh! Wrong Answer');
}
}
```


##### 📌 Explanation:[](#-explanation-2)

This code prompts the user to enter a number repeatedly until the user enters the number 8. If the user enters the number 8, the program prints "Correct!" and ends. If the user enters any other number, the program prints "Ahh! Wrong Answer" and continues prompting the user to enter a number. The program will continue to run until the user enters the correct number.

##### ⚡ Playground[](#-playground-2)

### ⁉️ Question 4:[](#️-question-4)

Write a function to find mean of 5 numbers.

#### ℹ️ Answer:[](#ℹ️-answer-3)

```
const mean = (a, b, c, d, e) => {
return (a + b + c + d + e) / 5;
};
 
let main = mean(1, 2, 3, 4, 5);
 
console.log(main);
```


##### 📌 Explanation:[](#-explanation-3)

*   The code defines a function `mean()` that takes 5 arguments: a, b, c, d, and e.
    
*   Inside the function, the code calculates the mean of the 5 numbers by adding them together and dividing the result by 5.
    
*   The code uses the `return` statement to return the result of the calculation.
    
*   The code calls the `mean()` function and passes it the values 1, 2, 3, 4, and 5 as arguments. The result of the function is stored in the `main` variable.
    
*   The code logs the value of main to the console.
    

##### ⚡ Playground[](#-playground-3)