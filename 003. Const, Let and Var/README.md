<h1><span className="text-center font-bold  text-transparent text-4xl tex bg-clip-text bg-gradient-to-r from-purple-400 to-pink-600">  Variables and Datatypes in JavaScript </span></h1>


## ➡️ What is a Variable?
<div className= "mt-3"></div>
<div className="cardTexture1 texture01">
    <h11 className="textStyle1" >
        <h10  style={{padding: "8px"}} className = " font-bold md:text-1xl text-cyan-400 " align="left">
       
            Explain
        </h10>
             A variable in JavaScript is a named storage location for a value. You can use variables to store any type of data, such as numbers, strings, arrays, and objects.
                <div align="center">
                <PhotoProvider  toolbarRender={({ rotate, onRotate }) => {return  <Icon9 onClick={() => onRotate(rotate + 90)} />}}>
        <PhotoView className=" mt-6 border-sky-200 border-opacity-20 imageBorderNormal" src="https://github.com/Subham-Maity/javascript_codexam/blob/main/003.%20Const,%20Let%20and%20Var/picndvid_xam/xam1.png?raw=true" width="350" alt="example">
            <img  className=" mt-6 border-sky-200  border-opacity-20 imageBorderNormal" src="https://github.com/Subham-Maity/javascript_codexam/blob/main/003.%20Const,%20Let%20and%20Var/picndvid_xam/xam1.png?raw=true" width="350" alt="example" />
        </PhotoView>
        </PhotoProvider>
</div>
you can imagine variables as a container that can hold numbers, strings, arrays, and objects inside of it instead of rice, water or any other thing.

To declare a variable in JavaScript, you use the `var` keyword, followed by the name of the variable. Here is an example:
```js
var x;
```
This declares a variable named `x`, but it does not have a value yet. You can assign a value to a variable using the assignment operator `=`. For example:
```js
var x;
x = 10;
```
This assigns the value 10 to the variable x.

You can also declare and assign a value to a variable in a single line:
```js
var x = 10;
```
In addition to the `var` keyword, there are two other keywords that can be used to declare variables in JavaScript: `let` and `const`. The main difference between `var`, `let`, and `const` is the scope in which they are defined and the ability to reassign their values.


`var` variables are function-scoped, which means they are only accessible within the function in which they are defined.


`let` variables are block-scoped, which means they are only accessible within the block of code (delimited by curly braces) in which they are defined.


`const` variables are also block-scoped, but they cannot be reassigned after they are declared.

  <div align="center">
                <PhotoProvider  toolbarRender={({ rotate, onRotate }) => {return  <Icon9 onClick={() => onRotate(rotate + 90)} />}}>
        <PhotoView className=" mt-6 border-sky-200 border-opacity-20 imageBorderNormal" src="https://github.com/Subham-Maity/javascript_codexam/blob/main/003.%20Const,%20Let%20and%20Var/picndvid_xam/a%201.png?raw=true" width="350" alt="example">
            <img  className=" mt-6 border-sky-200  border-opacity-20 imageBorderNormal" src="https://github.com/Subham-Maity/javascript_codexam/blob/main/003.%20Const,%20Let%20and%20Var/picndvid_xam/a%201.png?raw=true" width="350" alt="example" />
        </PhotoView>
        </PhotoProvider>
</div>

    </h11>
</div>




## ➡️ Rules for choosing variable names

<div className= "mt-3"></div>
<div className="cardTexture1 texture01">
    <h11 className="textStyle1" >
        <h10  style={{padding: "8px"}} className = " font-bold md:text-1xl text-cyan-400 " align="left">
       
           Rules for naming variables
        </h10>

        <h2 className="font-bold text-amber-600">1. Use camelCase:</h2> In JavaScript, it is common to use camelCase, where the first word is lowercase and subsequent words are capitalized. For example, a variable representing a user's first name might be called `firstName`.

        <h2 className="font-bold text-amber-600">2. Use descriptive names:</h2> It's important to choose names that accurately describe the value that the variable holds. For example, a variable representing a user's age might be called `age`, not x or num.

        <h2 className="font-bold text-amber-600">3. Avoid using reserved words:</h2> JavaScript has a set of reserved words that cannot be used as variable names. These include words like `var`, `function`, and `if`.

        <h2 className="font-bold text-amber-600">4. Avoid using abbreviations:</h2> While abbreviations can save space, they can also make your code harder to read. Try to use full words rather than abbreviations, unless the abbreviation is well-known and widely understood (such as HTML or CSS). For example, `firstName` is easier to understand than `fn`.

        <h2 className="font-bold text-amber-600">5. Be consistent:</h2> It's important to be consistent in your naming conventions throughout your code. Pick one style and stick with it to make your code more readable and easier to understand. for example, if you use camelCase for your variable names, you should use camelCase for your function names as well.

        <h2 className="font-bold text-amber-600">6. Use lowercase letters:</h2> JavaScript is case-sensitive, so `firstName` and `firstname` are two different variables. It's best to use lowercase letters for your variable names, as this is the convention used by most JavaScript developers.

        <h2 className="font-bold text-amber-600">7. Use semicolons:</h2> JavaScript statements are often separated by semicolons. It's best to use semicolons at the end of each statement, even if they are optional.

        <h2 className="font-bold text-amber-600">8. Use single quotes:</h2> JavaScript strings are surrounded by single or double quotes. It's best to use single quotes for strings, as this is the convention used by most JavaScript developers.

        <h2 className="font-bold text-amber-600">9. Starts with keyword:</h2> JavaScript variables must begin with a letter, underscore (_), or dollar sign ($). For example, `$name`, `_name`, and `name` are all valid variable names. However, numbers are not allowed as the first character. For example, `1name` is not a valid variable name.

        By following these rules, you can create clear and easy-to-read variable names that accurately represent the values they hold. This will make your code more maintainable and easier to understand for yourself and others.
            
</h11>

</div>


## ➡️ let vs const vs var

<div className= "mt-3"></div>
<div className="cardTexture1 texture01">
    <h11 className="textStyle1" >
        <h10  style={{padding: "8px"}} className = " font-bold md:text-1xl text-cyan-400 " align="left">
       
              let vs const vs var explain
        </h10>

        var, let, and const are three different ways to declare variables in JavaScript. One key difference between these three declarations is the scope of the variables they create.


        <h2 className="mt-3 font-bold text-amber-600">1. Globally scoped & Block scoped:</h2> 

      -  `var` is function-scoped, which means that the variable is only accessible within the function in which it is declared. If a `var` variable is not declared within a function, it is accessible globally, which means that it can be accessed from anywhere in the code. Here's an example of declaring a global `var` variable:
    
    <div  className="flex justify-between ">
            <iframe className="mt-6 border-sky-200 border-opacity-20 imageBorderNormal"
                src="https://stackblitz.com/edit/js-s7w49r?devToolsHeight=33&file=index.js"
                style={{
                    width:"806px",
                    height:"457px",
                    border: 0,
                    overflow: 'hidden',
                    background: 'rgb(21, 21, 21)'
                }}
                title="CodeXam"
                allow="accelerometer; ambient-light-sensor; camera; encrypted-media; geolocation; gyroscope; hid; microphone; midi; payment; usb; vr; xr-spatial-tracking"
                sandbox="allow-autoplay allow-forms allow-modals allow-popups allow-presentation allow-same-origin allow-scripts"
            />
        </div>

       - `let` and `const` are block-scoped, which means that they are only accessible within the block in which they are declared. A block is a piece of code surrounded by curly braces, such as an `if`statement or a `for` loop. Here's an example of declaring a block-scoped `let` variable:
        
        <div  className="flex justify-between ">
            <iframe className="mt-6 border-sky-200 border-opacity-20 imageBorderNormal"
                src="https://stackblitz.com/edit/js-euam8f?devToolsHeight=33&file=index.js"
                style={{
                    width:"806px",
                    height:"457px",
                    border: 0,
                    overflow: 'hidden',
                    background: 'rgb(21, 21, 21)'
                }}
                title="CodeXam"
                allow="accelerometer; ambient-light-sensor; camera; encrypted-media; geolocation; gyroscope; hid; microphone; midi; payment; usb; vr; xr-spatial-tracking"
                sandbox="allow-autoplay allow-forms allow-modals allow-popups allow-presentation allow-same-origin allow-scripts"
            />
        </div>

        Block-scoped variables are not accessible outside of the block in which they are declared, unlike `var` variables which are accessible globally if they are not declared within a function. This can be helpful in preventing unintended behavior and making your code more predictable and maintainable.

<h2 className="mt-3 font-bold text-amber-600">2. Var can be re-declared and updated:</h2> 


- In JavaScript, the `var` keyword is used to declare a variable. Variables declared with `var` have function scope, meaning they are only accessible within the function in which they are declared or within any functions that are nested within that function.

Here is an example of declaring and updating a variable with `var`:

        <div  className="flex justify-between ">
            <iframe className="mt-6 border-sky-200 border-opacity-20 imageBorderNormal"
                src="https://stackblitz.com/edit/js-9kygks?devToolsHeight=33&file=index.js"
                style={{
                    width:"806px",
                    height:"457px",
                    border: 0,
                    overflow: 'hidden',
                    background: 'rgb(21, 21, 21)'
                }}
                title="CodeXam"
                allow="accelerometer; ambient-light-sensor; camera; encrypted-media; geolocation; gyroscope; hid; microphone; midi; payment; usb; vr; xr-spatial-tracking"
                sandbox="allow-autoplay allow-forms allow-modals allow-popups allow-presentation allow-same-origin allow-scripts"
            />
        </div>


In this example, the `doSomething` function declares a variable `x` and assigns it the value `10`. The value of `x` is then logged to the console. The value of `x` is then updated to `20` and logged to the console again.


- It's also possible to re-declare a variable with var within the same scope. For example:

      <div  className="flex justify-between ">
            <iframe className="mt-6 border-sky-200 border-opacity-20 imageBorderNormal"
                src="https://stackblitz.com/edit/js-gkegqr?devToolsHeight=33&file=index.js"
                style={{
                    width:"806px",
                    height:"457px",
                    border: 0,
                    overflow: 'hidden',
                    background: 'rgb(21, 21, 21)'
                }}
                title="CodeXam"
                allow="accelerometer; ambient-light-sensor; camera; encrypted-media; geolocation; gyroscope; hid; microphone; midi; payment; usb; vr; xr-spatial-tracking"
                sandbox="allow-autoplay allow-forms allow-modals allow-popups allow-presentation allow-same-origin allow-scripts"
            />
        </div>

In this case, the variable x is re-declared with the value 20. The value of x that was originally assigned to 10 is replaced by the new value.


- It's important to note that re-declaring a variable with var does not result in an error, but it can lead to confusing or unexpected behavior in your code. It's generally a good practice to avoid re-declaring variables within the same scope.



<h2 className="mt-3 font-bold text-amber-600">3. Let can be updated but not re-declared:</h2>


In JavaScript, variables declared with the let keyword can be updated or reassigned, but they cannot be redeclared in the same block of code.


- Here is an example of updating a variable declared with let: 


     <div  className="flex justify-between ">
            <iframe className="mt-6 border-sky-200 border-opacity-20 imageBorderNormal"
                src="https://stackblitz.com/edit/js-jmj6rf?devToolsHeight=33&file=index.js"
                style={{
                    width:"806px",
                    height:"457px",
                    border: 0,
                    overflow: 'hidden',
                    background: 'rgb(21, 21, 21)'
                }}
                title="CodeXam"
                allow="accelerometer; ambient-light-sensor; camera; encrypted-media; geolocation; gyroscope; hid; microphone; midi; payment; usb; vr; xr-spatial-tracking"
                sandbox="allow-autoplay allow-forms allow-modals allow-popups allow-presentation allow-same-origin allow-scripts"
            />
        </div>



- Here is an example of attempting to redeclare a variable declared with let:


     <div  className="flex justify-between ">
            <iframe className="mt-6 border-sky-200 border-opacity-20 imageBorderNormal"
                src="https://stackblitz.com/edit/js-xvu8ef?devToolsHeight=33&file=index.js"
                style={{
                    width:"806px",
                    height:"457px",
                    border: 0,
                    overflow: 'hidden',
                    background: 'rgb(21, 21, 21)'
                }}
                title="CodeXam"
                allow="accelerometer; ambient-light-sensor; camera; encrypted-media; geolocation; gyroscope; hid; microphone; midi; payment; usb; vr; xr-spatial-tracking"
                sandbox="allow-autoplay allow-forms allow-modals allow-popups allow-presentation allow-same-origin allow-scripts"
            />
        </div>


- On the other hand, variables declared with the var keyword can be updated or reassigned, and they can also be redeclared within the same block of code.




     <div  className="flex justify-between ">
            <iframe className="mt-6 border-sky-200 border-opacity-20 imageBorderNormal"
                src="https://stackblitz.com/edit/js-7echxd?devToolsHeight=33&file=index.js"
                style={{
                    width:"806px",
                    height:"457px",
                    border: 0,
                    overflow: 'hidden',
                    background: 'rgb(21, 21, 21)'
                }}
                title="CodeXam"
                allow="accelerometer; ambient-light-sensor; camera; encrypted-media; geolocation; gyroscope; hid; microphone; midi; payment; usb; vr; xr-spatial-tracking"
                sandbox="allow-autoplay allow-forms allow-modals allow-popups allow-presentation allow-same-origin allow-scripts"
            />
        </div>




It's generally recommended to use let instead of var when declaring variables in modern JavaScript, as let provides more precise control over variable declarations and can help prevent unintended behavior in your code.


<h2 className="mt-3 font-bold text-amber-600"> 4. const can neither be updated nor re-declared:</h2>

In JavaScript, the const keyword is used to declare a constant variable. Constant variables are variables that cannot be reassigned or redeclared.

Here is an example of declaring a constant variable:



```js
const PI = 3.14;
```

In this example, PI is a constant variable that has a value of 3.14.

- If you try to reassign a value to a constant variable, you will get an error:


```js  
PI = 3.14159; // This will throw an error
```


- Similarly, if you try to redeclare a constant variable, you will also get an error:



```js  
const PI = 3.14;
const PI = 3.14159; // This will throw an error
```


     <div  className="flex justify-between ">
            <iframe className="mt-6 border-sky-200 border-opacity-20 imageBorderNormal"
                src="https://stackblitz.com/edit/js-mkpt5k?devToolsHeight=33&file=index.js"
                style={{
                    width:"806px",
                    height:"457px",
                    border: 0,
                    overflow: 'hidden',
                    background: 'rgb(21, 21, 21)'
                }}
                title="CodeXam"
                allow="accelerometer; ambient-light-sensor; camera; encrypted-media; geolocation; gyroscope; hid; microphone; midi; payment; usb; vr; xr-spatial-tracking"
                sandbox="allow-autoplay allow-forms allow-modals allow-popups allow-presentation allow-same-origin allow-scripts"
            />
        </div>


- Even if you declare with let or var, you will still get an error:

```js
const PI = 3.14;
let PI = 3.14159; // This will throw an error
var PI = 3.14159; // This will throw an error
```
 <div  className="flex justify-between ">
            <iframe className="mt-6 border-sky-200 border-opacity-20 imageBorderNormal"
                src="https://stackblitz.com/edit/js-y37fbo?devToolsHeight=33&file=index.js"
                style={{
                    width:"806px",
                    height:"457px",
                    border: 0,
                    overflow: 'hidden',
                    background: 'rgb(21, 21, 21)'
                }}
                title="CodeXam"
                allow="accelerometer; ambient-light-sensor; camera; encrypted-media; geolocation; gyroscope; hid; microphone; midi; payment; usb; vr; xr-spatial-tracking"
                sandbox="allow-autoplay allow-forms allow-modals allow-popups allow-presentation allow-same-origin allow-scripts"
            />
        </div>


It's important to note that the value of a constant variable is still mutable. For example, you can still modify the properties of an object that is assigned to a constant variable:


```js  
const obj = {};
obj.name = "John"; // This is allowed
```
However, you cannot reassign the object itself to the constant variable:


```js  
obj = {}; // This will throw an error
```

In summary, const variables cannot be reassigned or redeclared, but the values they hold may still be mutable.


<h2 className="mt-3 font-bold text-amber-600"> 5. Var variables are initialized with undefined let and const are not initialized with undefined in javascript explain with simple example </h2>

In JavaScript, variables declared with the `var` keyword are initialized with the value `undefined` when they are created. This means that if you declare a variable with var and don't assign it a value, it will have a value of `undefined`. For example:

 <div  className="flex justify-between ">
            <iframe className="mt-6 border-sky-200 border-opacity-20 imageBorderNormal"
                src="https://stackblitz.com/edit/js-ukjmjb?devToolsHeight=33&file=index.js"
                style={{
                    width:"806px",
                    height:"457px",
                    border: 0,
                    overflow: 'hidden',
                    background: 'rgb(21, 21, 21)'
                }}
                title="CodeXam"
                allow="accelerometer; ambient-light-sensor; camera; encrypted-media; geolocation; gyroscope; hid; microphone; midi; payment; usb; vr; xr-spatial-tracking"
                sandbox="allow-autoplay allow-forms allow-modals allow-popups allow-presentation allow-same-origin allow-scripts"
            />
        </div>


On the other hand, variables declared with the `let` and `const` keywords are not automatically initialized with a value. If you try to access the value of a `let` or `const` variable that has not been assigned a value, you will get a `ReferenceError` because the variable has not been defined. For example:
 <div  className="flex justify-between ">
            <iframe className="mt-6 border-sky-200 border-opacity-20 imageBorderNormal"
                src="https://stackblitz.com/edit/js-urwsrn?devToolsHeight=33&file=index.js"
                style={{
                    width:"806px",
                    height:"457px",
                    border: 0,
                    overflow: 'hidden',
                    background: 'rgb(21, 21, 21)'
                }}
                title="CodeXam"
                allow="accelerometer; ambient-light-sensor; camera; encrypted-media; geolocation; gyroscope; hid; microphone; midi; payment; usb; vr; xr-spatial-tracking"
                sandbox="allow-autoplay allow-forms allow-modals allow-popups allow-presentation allow-same-origin allow-scripts"
            />
        </div>
- It's important to note that the let and const keywords were introduced in ECMAScript 2015 (ES6) and are generally considered to be better alternatives to var for declaring variables. This is because let and const have more strict rules for variable declarations and can help prevent common coding mistakes.



<h2 className="mt-3 font-bold text-amber-600"> 6. Const must be initialized during declaration unlike let and var </h2>

In JavaScript, the const keyword is used to declare a constant variable, which means that the value of the variable cannot be reassigned. The value of a constant variable can be changed if it is an object, but the variable identifier cannot be reassigned.

For example:

```js
const PI = 3.14;
PI = 3.14159; // This will throw an error

const obj = {};
obj.name = "John"; // This is allowed
obj = {}; // This will throw an error
```

It is important to note that const variables must be initialized during declaration. This means that you must specify a value for the constant when you declare it.

For example:

```js
const PI; // This will throw an error because PI is not initialized

const PI = 3.14; // This is allowed
```

On the other hand, the let and var keywords are used to declare variables in JavaScript. These variables can be reassigned and do not have to be initialized during declaration.

For example:

```js
let x;
x = 10;
x = "hello";

var y;
y = 20;
y = false;
```
In general, it is considered best practice to use const whenever possible and only use let or var when reassignment is necessary. This helps to prevent accidental reassignment and makes the code easier to understand.
</h11>
</div>