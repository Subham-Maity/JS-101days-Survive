# Switch Statement – CodeXam
🎉

### Read This on Github

This article is available on Github. You can read it there and contribute to it.

[

Github Link

](https://github.com/Subham-Maity/javascript_codexam)[

Any Issue ?

](https://github.com/Subham-Maity/javascript_codexam/issues/new)

📖 Syntax of Switch Statement[](#-syntax-of-switch-statement)
-------------------------------------------------------------

```
switch (expression) {
    case value1:
    // code block to execute if expression === value1
    break;
    case value2:
    // code block to execute if expression === value2
    break;
    ...
    default:
    // code block to execute if expression is none of the above values
    break;
}
```


*   `expression` is the value that the switch statement will evaluate. This can be any valid expression in JavaScript, such as a variable, a literal value, or a more complex expression.
    
*   `value1`, `value2`, etc. are the values that the expression will be compared to. If the expression is equal to one of these values, the corresponding code block will be executed.
    
*   The `break` statement is used to exit the switch statement and prevent the code from falling through to the next case. If you do not include a break statement, the code will continue to execute the next case's code block, even if the expression does not match the value of that case.
    
*   The `default` case is optional, and it will be executed if the expression does not match any of the other cases.
    

⭐ Switch Statement Example 1[](#-switch-statement-example-1)
------------------------------------------------------------

![](https://media4.giphy.com/media/Icj7X7GxqNPmCczjzb/giphy.gif?cid=ecf05e471sx8lbstqw8ytb0nbzuo435st3bclrrt491y7ics&rid=giphy.gif&ct=g)

In normal English, we might express this idea as follows:

`"If today is Monday, say 'It is Monday'. If today is Tuesday, say 'It is Tuesday'. If today is Wednesday, say 'It is Wednesday'. If today is some other day, say 'It is some other day'."`

```
let day = 'Monday';
 
switch (day) {
case 'Monday':
console.log('It is Monday');
break;
case 'Tuesday':
console.log('It is Tuesday');
break;
case 'Wednesday':
console.log('It is Wednesday');
break;
default:
console.log('It is some other day');
break;
}
```


This switch statement will evaluate the value of the `day` variable and execute the appropriate code block based on the value. If the value of `day` is `Monday`, the code will log `It is Monday` to the console. If the value is `Tuesday`, it will log `It is Tuesday`. If the value is `Wednesday`, it will log `It is Wednesday`. If the value is none of these, it will log 'It is some other day'.

### ⚡ Playground[](#-playground)

⭐ Switch Statement Example 2[](#-switch-statement-example-2)
------------------------------------------------------------

![](https://media.giphy.com/media/xFnxVuOe6jAbqgy9uR/giphy.gif)

In normal English, we might express this idea as follows:

`If the grade is an A, say 'Excellent job!'. If the grade is a B, say 'Good job!'. If the grade is a C, say 'Okay job'. If the grade is a D, say 'Needs improvement'. If the grade is an F, say 'Fail'. If the grade is none of these, say 'Invalid grade'.`

```
let grade = 'A';
 
switch (grade) {
case 'A':
console.log('Excellent job!');
break;
case 'B':
console.log('Good job!');
break;
case 'C':
console.log('Okay job');
break;
case 'D':
console.log('Needs improvement');
break;
case 'F':
console.log('Fail');
break;
default:
console.log('Invalid grade');
break;
}
 
```


This switch statement will evaluate the value of the `grade` variable and execute the appropriate code block based on the value. If the value of grade is `A`, the code will log 'Excellent job!' to the console. If the value is `B`, it will log 'Good job!'. If the value is `C`, it will log 'Okay job'. If the value is `D`, it will log 'Needs improvement'. If the value is `F`, it will log 'Fail'. If the value is none of these, it will log 'Invalid grade'.

### ⚡ Playground[](#-playground-1)

⭐ Switch Statement Example 3[](#-switch-statement-example-3)
------------------------------------------------------------

![](https://media.giphy.com/media/26u6dryuZH98z5KuY/giphy.gif)

In normal English,

we might express this idea as follows:

`If the weather is sunny, say 'It is sunny outside. Wear sunscreen and a hat.'. If the weather is cloudy, say 'It is cloudy outside. Bring an umbrella just in case.'. If the weather is rainy, say 'It is rainy outside. Make sure to bring a raincoat or umbrella.'. If the weather is snowy, say 'It is snowy outside. Make sure to bundle up and wear warm clothes.'. If the weather is none of these, say 'It is some other type of weather. Make sure to check the forecast and dress appropriately.'.`

```
let weather = 'sunny';
 
switch (weather) {
case 'sunny':
console.log('It is sunny outside. Wear sunscreen and a hat.');
break;
case 'cloudy':
console.log('It is cloudy outside. Bring an umbrella just in case.');
break;
case 'rainy':
console.log('It is rainy outside. Make sure to bring a raincoat or umbrella.');
break;
case 'snowy':
console.log('It is snowy outside. Make sure to bundle up and wear warm clothes.');
break;
default:
console.log('It is some other type of weather. Make sure to check the forecast and dress appropriately.');
break;
}
 
```


This switch statement will evaluate the value of the weather variable and execute the appropriate code block based on the value. If the value of weather is 'sunny', the code will log 'It is sunny outside. Wear sunscreen and a hat.' to the console. If the value is 'cloudy', it will log 'It is cloudy outside. Bring an umbrella just in case.'. If the value is 'rainy', it will log 'It is rainy outside. Make sure to bring a raincoat or umbrella.'. If the value is 'snowy', it will log 'It is snowy outside. Make sure to bundle up and wear warm clothes.'. If the value is none of these, it will log 'It is some other type of weather. Make sure to check the forecast and dress appropriately.'.

### ⚡ Playground[](#-playground-2)

⭐ Switch Statement Example 4[](#-switch-statement-example-4)
------------------------------------------------------------

![](https://media.giphy.com/media/l5xTOiFpcs8u8kgQQQ/giphy.gif)

In normal English,

we might express this idea as follows:

`If the action is eating, say 'Eating is important for maintaining good health.'. If the action is sleeping, say 'Getting enough sleep is essential for maintaining energy and productivity.'. If the action is exercising, say 'Exercise helps to improve physical fitness and overall well-being.'. If the action is studying, say 'Studying helps to increase knowledge and improve academic performance.'. If the action is none of these, say 'It is important to engage in a variety of activities to maintain balance and well-being.'.`

```
let action = 'eat';
 
switch (action) {
case 'eat':
console.log('Eating is important for maintaining good health.');
break;
case 'sleep':
console.log('Getting enough sleep is essential for maintaining energy and productivity.');
break;
case 'exercise':
console.log('Exercise helps to improve physical fitness and overall well-being.');
break;
case 'study':
console.log('Studying helps to increase knowledge and improve academic performance.');
break;
default:
console.log('It is important to engage in a variety of activities to maintain balance and well-being.');
break;
}
 
 
```


This switch statement will evaluate the value of the action variable and execute the appropriate code block based on the value. If the value of action is 'eat', the code will log 'Eating is important for maintaining good health.' to the console. If the value is 'sleep', it will log 'Getting enough sleep is essential for maintaining energy and productivity.'. If the value is 'exercise', it will log 'Exercise helps to improve physical fitness and overall well-being.'. If the value is 'study', it will log 'Studying helps to increase knowledge and improve academic performance.'. If the value is none of these, it will log 'It is important to engage in a variety of activities to maintain balance and well-being.'.

### ⚡ Playground[](#-playground-3)