# Conditional Statements – CodeXam
🎉

### Read This on Github

This article is available on Github. You can read it there and contribute to it.

[

Github Link

](https://github.com/Subham-Maity/javascript_codexam)[

Any Issue ?

](https://github.com/Subham-Maity/javascript_codexam/issues/new)

Assuming you are not familiar with any programming language but you know simple english language. And suppose you are a student.

*   let's say you want to decide whether or not to bring an umbrella to school tomorrow. You might use a conditional statement like this:
    
    ![](https://i.pinimg.com/originals/a0/84/65/a08465fcb5cb830adfcbcc3ae9ea1116.gif)
    

In english, you would say:

`If it rains tomorrow, bring an umbrella.`

In JavaScript, you would write:

```
if (it is raining) {
bring an umbrella
 }
```


In this example, the condition is "it is raining". If the condition is true (meaning it is raining), then the code inside the curly braces (`{ }`) will be executed (in this case, bringing an umbrella). If the condition is false (meaning it is not raining), then the code inside the curly braces will not be executed.

*   You can also add an "else" clause to your conditional statement, which will be executed if the condition is false. For example:
    
    ![](https://i.pinimg.com/originals/82/d9/68/82d968e7a704b26a3460d248c3aae8d6.gif)
    

In english, you would say:

`If it rains tomorrow, bring an umbrella. Otherwise, leave it at home.`

In JavaScript, you would write:

```
  if (it is raining) {
 
    bring an umbrella
 
  } else {
 
    do not bring an umbrella
 }
```


This conditional statement says that if it is raining, bring an umbrella, but if it is not raining, do not bring an umbrella.

*   You can also use more complex conditions, using comparison operators like `>` (greater than), `<` (less than), `>=` (greater than or equal to), and `<=` (less than or equal to).
    
    ![](https://media2.giphy.com/media/3oipPTHYlTpCw8oBBy/giphy.gif)
    

For example:

In english, you would say:

`If temperature is greater than 70 degrees, wear shorts. Otherwise, wear pants.`

In JavaScript, you would write:

```
     if (temperature is >= 70 degrees) {
 
        wear shorts
 
    } else {
 
        wear pants
    }
```


This conditional statement says that if the temperature is 70 degrees or higher, wear shorts, but if the temperature is less than 70 degrees, wear pants.

Another example: [Check Here (opens in a new tab)](https://stackblitz.com/edit/js-nas5u7?devToolsHeight=33&file=index.js)

The `if` statement is a conditional statement that allows you to execute a block of code only if a certain condition is true.

It has the following syntax:

```
if (condition) {
     // code to be executed if condition is true
}
```


The condition is a boolean expression that evaluates to either `true` or `false`. If the condition evaluates to `true`, the code inside the curly braces (`{ }`) will be executed. If the condition evaluates to `false`, the code inside the curly braces will not be executed.

For example:

```
        var x = 5;
 
        if (x > 0) {
        console.log("x is positive");
    }
 
        var y = "hello";
 
        if (y.length > 5) {
        console.log("y is a long string");
    }
 
        var z = true;
 
        if (z) {
        console.log("z is true");
    }
```


*   In the first example, the condition is `x > 0`, which means "if the value of `x` is greater than 0". Since the value of `x` is indeed greater than 0, the code inside the curly braces will be executed (printing the message "x is positive" to the console).
    
*   In the second example, the condition is `y.length > 5`, which means "if the length of the string stored in the `y` variable is greater than 5". Since the length of the string "hello" is `5`, the code inside the curly braces will not be executed.
    
*   In the third example, the condition is simply `z`, which means "if the value of `z` is truthy". Since the value of `z` is true, the code inside the curly braces will be executed (printing the message "z is true" to the console).
    

#### ⚡ Playground[](#-playground)

The `if...else` statement is a conditional statement that allows you to execute one block of code if a certain condition is `true`, and another block of code if the condition is `false`.

It has the following syntax:

```
    if (condition) {
 
        // code to be executed if condition is true
 
    } else {
 
        // code to be executed if condition is false
    }
 
```


The `condition` is an expression that evaluates to either `true` or `false`. If the condition is `true`, the code inside the first set of curly braces `({ })` will be executed. If the condition is `false`, the code inside the second set of curly braces will be executed.

Here are some examples of using the `if...else` statement:

For example:

```
var x = 5;
 
if (x > 0) {
console.log("x is positive");
} else {
console.log("x is not positive");
}
 
var y = "hello";
 
if (y.length > 5) {
console.log("y is a long string");
} else {
console.log("y is not a long string");
}
 
var z = true;
 
if (z) {
console.log("z is true");
} else {
console.log("z is not true");
}
 
```


*   In the first example, the condition is x > 0, which means "if the value of x is greater than 0". Since the value of x is indeed greater than 0, the code inside the first set of curly braces will be executed (printing the message "x is positive" to the console).
    
*   In the second example, the condition is y.length > 5, which means "if the length of the string stored in the y variable is greater than 5". Since the length of the string "hello" is 5, the code inside the second set of curly braces will be executed (printing the message "y is not a long string" to the console).
    
*   In the third example, the condition is simply z, which means "if the value of z is truthy". Since the value of z is true, the code inside the first set of curly braces will be executed (printing the message "z is true" to the console).
    

#### ⚡ Playground[](#-playground-1)

The if...else if...else statement is a conditional statement that allows you to execute different blocks of code based on multiple conditions.

It has the following syntax:

```
        if (condition1) {
        // code to be executed if condition1 is true
    } else if (condition2) {
        // code to be executed if condition1 is false and condition2 is true
    } else if (condition3) {
        // code to be executed if condition1 and condition2 are false and condition3 is true
    } ...
        else {
        // code to be executed if all conditions are false
    }
```


The `condition1`, `condition2`, `condition3`, etc. are expressions that evaluate to either `true` or `false`. If condition1 is true, the code inside the first set of curly braces `({ })` will be executed. If condition1 is false but condition2 is true, the code inside the second set of curly braces will be executed. If condition1 and condition2 are both false but condition3 is true, the code inside the third set of curly braces will be executed, and so on. If all conditions are false, the code inside the final set of curly braces `(the else clause)` will be executed.

Here is an example of using the if...else if...else statement:

```
        var grade = 87;
 
        if (grade >= 90) {
 
        console.log("A");
 
    } else if (grade >= 80) {
 
        console.log("B");
 
    } else if (grade >= 70) {
 
        console.log("C");
 
    } else {
 
        console.log("D");
 
    }
```


*   In this example, if the value of grade is 90 or higher, the message "A" will be printed to the console. If the value of grade is between 80 and 89 (inclusive), the message "B" will be printed to the console. If the value of grade is between 70 and 79 (inclusive), the message "C" will be printed to the console. If the value of grade is lower than 70, the message "D" will be printed to the console.

#### ⚡ Playground[](#-playground-2)