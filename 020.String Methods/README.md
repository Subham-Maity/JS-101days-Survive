# String Methods – CodeXam
![](https://media.giphy.com/media/meYkhNY3KtJxS/giphy.gif)

Properties are values that are associated with a string. For example, the length property of a string represents the number of characters in the string. Here is an example of how to use the length property:

```
var str = "Hello World!";
var n = str.length;
```


Methods are functions that can be called on a string to perform a specific action. For example, the toUpperCase() method returns a new string with all of the characters in uppercase. Here is an example of how to use the toUpperCase() method:

```
var str = "Hello World!";
var res = str.toUpperCase();
```


```
let str = 'Hello, world!';
 
// charAt(index)
console.log(str.charAt(0));  // Output: "H"
 
// charCodeAt(index)
console.log(str.charCodeAt(0));  // Output: 72
 
// concat(str1, str2, ...)
console.log(str.concat(' How are you?'));  // Output: "Hello, world! How are you?"
 
// endsWith(searchString, length)
console.log(str.endsWith('world!'));  // Output: true
 
// includes(searchString, position)
console.log(str.includes('world'));  // Output: true
 
// indexOf(searchString, position)
console.log(str.indexOf('world'));  // Output: 7
 
// lastIndexOf(searchString, position)
console.log(str.lastIndexOf('l'));  // Output: 9
 
// localeCompare(compareString, locales, options)
console.log(str.localeCompare('HELLO, WORLD!'));  // Output: 1
 
// match(regexp)
console.log(str.match(/l/g));  // Output: ["l", "l"]
 
// repeat(count)
console.log(str.repeat(3));  // Output: "Hello, world!Hello, world!Hello, world!"
 
// replace(searchValue, replaceValue)
console.log(str.replace(/l/g, 'L'));  // Output: "HeLLo, worLd!"
 
// search(regex)
console.log(str.search(/l/g));  // Output: 2
 
// slice(start, end)
console.log(str.slice(7, 12));  // Output: "world"
 
// split(separator, limit)
console.log(str.split(' '));  // Output: ["Hello,", "world!"]
 
// startsWith(searchString, position)
console.log(str.startsWith('Hello'));  // Output: true
 
// substring(start, end)
console.log(str.substring(7, 12));  // Output: "world"
 
// toLowerCase()
console.log(str.toLowerCase());  // Output: "hello, world!"
 
// toUpperCase()
console.log(str.toUpperCase());  // Output: "HELLO, WORLD!"
 
// trim()
console.log('   Hello, world!   '.trim());  // Output: "Hello, world!"
 
// valueOf()
console.log(str.valueOf());  // Output: "Hello, world!"
 
```


#### ⚡ Playground[](#-playground)