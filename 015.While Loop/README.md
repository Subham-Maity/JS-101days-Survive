# While Loop – CodeXam
🎉

### Read This on Github

This article is available on Github. You can read it there and contribute to it.

[

Github Link

](https://github.com/Subham-Maity/javascript_codexam)[

Any Issue ?

](https://github.com/Subham-Maity/javascript_codexam/issues/new)

⭐ Syntax of For Loop[](#-syntax-of-for-loop)
--------------------------------------------

![](https://media2.giphy.com/media/gguXs55Ih0T4FOLjBL/giphy.gif?cid=ecf05e471as2p6vrwj5osvc9rzr1cxbxa6ipbs2vug5t6mw5&rid=giphy.gif&ct=g)

```
while (condition) {
// code to be executed
}
```


1.  `Condition`: This is the first part of the while loop and is used to specify the condition that must be met for the loop to continue running. As long as the condition is true, the loop will continue to execute. When the condition becomes false, the loop will stop. For example:

2.  `Code block`: If the condition is true, the code inside the while loop's code block will be executed. This is the second part of the while loop. For example:

```
while (condition) {
console.log(i);
}
```


In this example, the code block consists of a single line that prints the value of i to the console.

Here is an example of how a while loop can be used in JavaScript:

```
let i = 0;
while (i < 10) {
console.log(i);
i++;
}
```


This while loop will print the numbers 0 through 9 to the console. The loop will start by evaluating the condition `i < 10`, which will be true because the value of `i` is 0. The

⭐ Explaining Step by Step of While Loop[](#-explaining-step-by-step-of-while-loop)
----------------------------------------------------------------------------------

### 💥 While Loop Example[](#-while-loop-example)

![](https://github.com/Subham-Maity/javascript-for-beginners/blob/main/015.While%20Loop/whileloop.gif?raw=true)

```
let count = 0;
 
    while (count < 3) {
    console.log(count);
    count++;
   }
```


### 💥 Visualize the Example[](#-visualize-the-example)

```
Initialize count to 0
    |
    v
+-----------+
| count = 0 |
+-----------+
    |
    v
 count < 3  |  TRUE
    |       |
    v       |
+-----------+
| print 0   |
+-----------+
    |       |
    v       |
+-----------+
| count = 1 |
+-----------+
    |       |
    v       |
 count < 3  |  TRUE
    |       |
    v       |
+-----------+
| print 1   |
+-----------+
    |       |
    v       |
+-----------+
| count = 2 |
+-----------+
    |       |
    v       |
 count < 3  |  TRUE
    |       |
    v       |
+-----------+
| print 2   |
+-----------+
    |       |
    v       |
+-----------+
| count = 3 |
+-----------+
    |       |
    v       |
 count < 3  |  FALSE
    |       |
    v       |
    +-------+
    stop
```


### 💥 Explain the Example[](#-explain-the-example)

1.  A variable `count` is defined and initialized to `0`.
    
2.  The while loop begins with the condition `count < 3`.
    
    *   At this point, the value of `count` is 0, so the condition `count < 3` is `true`.
    *   The loop body runs, and the current value of `count (0)` is logged to the console.
    *   The value of `count` is incremented by `1` (using the postfix increment operator `++`). The value of `count` is now `1`.
    *   The loop checks the condition again. The condition `count < 3` is still `true`, so the loop runs again.
3.  The loop body runs again, and the current value of count (1) is logged to the console.
    
    *   The value of `count` is incremented by 1 (using the postfix increment operator ++). The value of `count` is now 2.
    *   The loop checks the condition again. The condition `count < 3` is still `true`, so the loop runs again.
4.  The loop body runs again, and the current value of `count (2)` is logged to the console.
    
    *   The value of `count` is incremented by 1 (using the postfix increment operator `++`). The value of `count` is now 3.
    *   The loop checks the condition again. The condition `count < 3` is now `false`, so the loop ends.
5.  The loop has ended, and the program continues with any code that follows the loop.
    
    #### ⚡ Playground[](#-playground)
    

⭐ Example of While Loop[](#-example-of-while-loop)
--------------------------------------------------

![](https://media.giphy.com/media/TG9kihFV7EBuz3iJ23/giphy.gif)

✨ 1. Printing the numbers from 1 to 10:

```
let i = 1;
while (i <= 10) {
console.log(i);
i++;
}
```


✨ 2. Printing the numbers from 10 to 1:

```
let i = 10;
while (i >= 1) {
console.log(i);
i--;
}
```


✨ 3. Printing the even numbers from 1 to 10:

```
let i = 2;
while (i <= 10) {
console.log(i);
i += 2;
}
```


✨ 4. Printing the odd numbers from 1 to 10:

```
let i = 1;
while (i <= 10) {
console.log(i);
i += 2;
}
```


✨ 5. Calculating the sum of the first 10 numbers:

```
let sum = 0;
let i = 1;
while (i <= 10) {
sum += i;
i++;
}
 
console.log(sum);
```


✨ 6. Calculating the sum of the first 10 even numbers:

```
let sum = 0;
let i = 2;
while (i <= 10) {
sum += i;
i += 2;
}
 
console.log(sum);
```


✨ 7. Calculating the sum of the first 10 odd numbers:

```
let sum = 0;
let i = 1;
while (i <= 10) {
sum += i;
i += 2;
}
 
console.log(sum);
```


✨ 8. Printing the numbers from 1 to 10 in reverse:

```
let i = 10;
while (i >= 1) {
console.log(i);
i--;
}
```
