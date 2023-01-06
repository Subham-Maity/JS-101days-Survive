# Loops in JavaScript – CodeXam
🎉

### Read This on Github

This article is available on Github. You can read it there and contribute to it.

[

Github Link

](https://github.com/Subham-Maity/javascript_codexam)[

Any Issue ?

](https://github.com/Subham-Maity/javascript_codexam/issues/new)

In programming, a loop is a control structure that allows a block of code to be executed repeatedly for a specified number of times or until a certain condition is met. Loops are useful for automating repetitive tasks and can save a lot of time and effort.

![](https://mir-s3-cdn-cf.behance.net/project_modules/max_1200/8442df95494195.5e98965c07269.gif)

`Washing dishes:` Imagine you have a stack of dirty dishes in your sink and you want to wash them all. You could manually wash each dish one by one, but that would be time-consuming and tedious. Instead, you could use a loop to automate the process. You could set up a loop that runs until all the dishes are washed. Inside the loop, you could include a block of code that tells the dishwasher to wash a single dish. The loop would then repeat until all the dishes are clean.

![](https://media.giphy.com/media/JS9cA2mnPbpoiwsQ3A/giphy.gif)

`Sending emails:` Suppose you want to send an email to a group of people. You could manually type and send each email one by one, but that would take a long time. Instead, you could use a loop to automate the process. You could set up a loop that runs for the number of people you want to email. Inside the loop, you could include a block of code that sends an email to a single person. The loop would then repeat until all the emails are sent.

![](https://media.giphy.com/media/l46Cq6Bro9CsP149q/giphy.gif)

`Checking inventory:` Imagine you work in a store and you need to check the inventory of all the items on the shelves. You could manually check each item one by one, but that would be time-consuming and error-prone. Instead, you could use a loop to automate the process. You could set up a loop that runs for the number of items you need to check. Inside the loop, you could include a block of code that checks the inventory of a single item. The loop would then repeat until all the items are checked.

![](https://media.giphy.com/media/KH90Li6p4bUxSYFMm9/giphy.gif)

```
 Initialize loop counter (e.g. i = 0)
 
 Loop:
 Perform loop action (e.g. print i)
 Update loop counter (e.g. i = i + 1)
 Check loop condition (e.g. i < 10)
 If condition is true, go back to Loop
 If condition is false, exit loop
```


![](https://miro.medium.com/max/960/1*6h2tm01a-mraPcwRf53Yog.gif)

*   `For loop`: This loop is used to execute a block of code a specified number of times. It has three parts: the initialization, the condition, and the increment/decrement.
    
    *   For in loop: This loop is used to iterate over the properties of an object.
    *   For of loop: This loop is used to iterate over the values of an iterable object.
*   `While loop`: This loop is used to execute a block of code while a certain condition is true.
    
*   `Do-while loop`: This loop is similar to the while loop, but it always executes the block of code at least once before checking the condition.
    

Simple example of the three loops:

```
// For loop
for (let i = 0; i < 10; i++) {
console.log(i);
}
 
// While loop
let i = 0;
while (i < 10) {
console.log(i);
i++;
}
 
// Do-while loop
let i = 0;
do {
console.log(i);
i++;
}
while (i < 10);
```
