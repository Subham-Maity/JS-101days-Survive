# Js23 – CodeXam
Let's revise what we have learned so far.

![](https://media.giphy.com/media/ffWn2Q0OFgXXCEdfyn/giphy.gif)

### ⁉️ Question 1:[](#️-question-1)

What is the output of the following code? and why ?

The output of this code will be 4. In this case, the string is "Xam"" which contains 4 characters (X, a, m, ") and the backslash is used as an escape character for the quotation mark, so it does not count as a character in the string. So, when we run the console.log(str.length) it will print the number of characters in the string which is 4.

#### ⚡ Playground[](#-playground)

### ⁉️ Question 2:[](#️-question-2)

Explore the includes, startsWith, endsWith methods of the String object.

#### ⚡ Playground[](#-playground-1)

### ⁉️ Question 3:[](#️-question-3)

Write a program to convert a given string into lowercase.

#### ⚡ Playground[](#-playground-2)

### ⁉️ Question 4:[](#️-question-4)

Extract the amount out of the following string and print it in the console.

"Please pay 100 for the product"

### ⁉️ Question 50:[](#️-question-50)

Try to change 4th character of the given string `let student = "xam"`

### ⚡ Type 1[](#-type-1)

You can change the 4th character of the given string "xam" by using the substring() method and the concat() method.

Here is an example of how you might use these methods:

This will create a new string by extracting the substring from the original string from the start index 0 to the index 3 (not including index 3) and then concatenating the character "b" to it. It will output the new string xamb in the console.

### ⚡ Type 2[](#-type-2)

You can also use the splice() method to change the 4th character of the given string

Here is an example of how you might use this method:

This will convert the string to an array using split('') and then splice the array at the 4th index, replacing it with the new character 'b' and then join the array back to a string and will output the new string xamb in the console.

### ⚡ Type 3[](#-type-3)

You can also use destructuring assignment to change the 4th character of the string

Here is an example of how you might use this method:

This will convert the string to an array using split('') and then assign the characters to the variables a, b, c, d. Then, it will output the new string xamb in the console.