# For Loop – CodeXam
For Loops Explained with Example

Now imagine this is our syntax of for loop:

```
For (statement1; statement2; statement 3){
//code to be executed
}
```


Now we will explain each statement one by one when and how it will be executed.

![](https://media.giphy.com/media/k11ZKxvUQa1xLYzExd/giphy.gif)

✨ 1. `Initialization` (statement1): The first step in a for loop is the initialization, which is the first statement inside the for loop. This statement is executed only once, before the loop starts. It is used to initialize a loop counter variable, which is a variable that is used to keep track of the number of times the loop has run.

For example:

```
  for (let i = 0; statement2; statement3) {
  // code to be executed
  }
```


In this example, the loop counter variable is i, which is initialized to 0.

✨ 2. `Condition` (statement2): The second step in a for loop is the condition, which is the second statement inside the for loop. This statement is evaluated before each iteration of the loop. If the condition evaluates to true, the loop will continue to run. If the condition evaluates to false, the loop will stop running.

For example:

```
for (statement1; i < 10; statement3) {
// code to be executed
}
```


In this example, the condition is i < 10, which means that the loop will continue to run as long as i is less than 10.

✨ 3. `Code block:`: If the condition is true, the code inside the for loop's code block will be executed. This is the third step in a for loop.

For example:

```
for (statement1; statement2; statement3) {
 
    console.log(i);
}
```


In this example, the code block consists of a single line that prints the value of i to the console.

✨ 4. `Increment/Decrement` (statement3): The fourth and final step in a for loop is the increment/decrement, which is the third statement inside the for loop. This statement is executed after each iteration of the loop. It is used to update the loop counter variable so that the loop can continue running or stop when the condition is met.

For example:

```
for (statement1; statement2; i++) {
// code to be executed
}
```


In this example, the increment/decrement statement is i++, which means that the value of i will be increased by 1 after each iteration of the loop.

😊 Here is an example of a for loop that puts all these steps together:

```
for (let i = 0; i < 10; i++) {
console.log(i);
}
```


This for loop will print the numbers 0 through 9 to the console. The loop will start by initializing the loop counter variable i to 0. It will then check the condition i < 10, which will be true because 0 is less than 10. The code inside the loop's code block, which is console.log(i), will be executed, printing the value of i (0) to the console. The increment/decrement statement i++ will then be executed, increasing the value of i by 1. The loop will then repeat, starting with the condition statement again. This process will continue until the value of i becomes 10, at which point the condition i < 10 will be false and the loop will stop.

```
Initialization (e.g. let i = 0)
 
Loop:
Condition (e.g. i < 10)
If condition is true:
Code block (e.g. console.log(i))
Increment/decrement (e.g. i++)
Go back to Loop
If condition is false:
Exit loop
```
