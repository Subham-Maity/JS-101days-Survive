
# ⭐ Arrays Practice Problems



1. Create an array of numbers and take input from the user to add numbers to this array
2. Keep adding numbers to the array in 1. until 0 is added to the array
3. Filter for numbers divisible by 10 from a given array
4. Create an array of square of given numbers
5. use reduce to calculate factorial of a given number from an array of first n natural numbers( n being the number whose factorial to calculated)

## ⭐ Solutions



1. Create an array of numbers and take input from the user to add numbers to this array

```js
    let arr = []; // create an empty array
    let input = prompt("Enter numbers to add to the array separated by space"); // ask for user input
    if (input !== null) { // check if input is not null
      // if the user clicks cancel, the input will be null and we don't want to process it
      let inputArr = input.split(" "); // split the input string by space and create an array of elements
      // the split method takes a separator as an argument and returns an array of substrings that are separated by that separator in the original string
      // for example, "12 13 14 15".split(" ") will return ["12", "13", "14", "15"]
      arr = arr.concat(inputArr); // concatenate the two arrays and assign it to arr
      // the concat method takes one or more arrays as arguments and returns a new array that contains all the elements from those arrays in order
      // for example, [1,2].concat([3,4]) will return [1,2,3,4]
    }
    console.log(arr); // show the array in console
    // the console.log method prints a value to the browser's console which can be accessed by pressing F12 or Ctrl+Shift+I on most browsers
```






2. Keep adding numbers to the array in 1. until 0 is added to the array

```js
       let arr = []; // create an empty array
       let input; // declare a variable to store user input
       do {
         input = prompt('Enter numbers to add to the array separated by space, or enter 0 to stop'); // ask for user input
         arr.push(input); // add the input to the end of the array
       } while (input !== '0'); // continue looping as long as the input is not 0
       console.log(arr); // show the array in console
```



3. Filter for numbers divisible by 10 from a given array

```
    let arr = [25, 26, 24, 23, 20];
    let filter = arr.filter((z) => {
      return z % 10 ==0;
    });

    console.log(filter);
```

```js
    let arr = [10, 20, 30, 40, 50, 60, 70, 80, 90, 100]; // create an array of numbers
    let filteredArr = arr.filter((num) => num % 10 === 0); // filter the array to get numbers divisible by 10
    // the filter method takes a callback function as an argument and returns a new array that contains all the elements for which the callback function returns true
    // for example, [1,2,3,4,5].filter((num) => num % 2 === 0) will return [2,4]
    console.log(filteredArr); // show the filtered array in console
```


4. Create an array of square of given numbers

```js
    // Declare a variable named arr and assign it an array of numbers
    let arr = [1, 2, 3, 4, 5];

    // Declare a variable named filter and assign it the result of calling the map() method on arr
    // The map() method takes a function as a parameter and applies it to each element of arr
    // The function takes a parameter named z and returns the square of z
    let filter = arr.map((z) => {
      return z * z;
    });

    // Print the value of filter to the console
    // filter is an array of square of numbers from arr
    console.log(filter); // [1, 4, 9, 16, 25]
```
5. use reduce to calculate factorial of a given number from an array of first n natural numbers( n being the number whose factorial to calculated)

```js
  // Declare a variable named arr and assign it an array of numbers
  let arr = [1, 2, 3, 4, 5];

  // Declare a variable named filter and assign it the result of calling the reduce method on arr
  // The reduce method takes a function as a parameter and applies it to each pair of elements of arr
  // The function takes two parameters named z1 and z2 and returns the product of z1 and z2
  let filter = arr.reduce((z1, z2) => {
    return z1 * z2;
  });

  // Print the value of filter to the console
  // filter is the product of all the numbers in arr
  console.log(filter); // 120
```




#### ⚡ [Playground](https://stackblitz.com/edit/js-wkp7i7?devToolsHeight=33&file=index.js)

