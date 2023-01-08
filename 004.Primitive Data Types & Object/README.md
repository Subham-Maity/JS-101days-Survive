# Primitives and Objects – CodeXam
JavaScript has 7 primitive data types:

1.  String: A string is a sequence of characters, represented by either single or double quotes. Examples: "hello", 'world'.
    
2.  Number: A number can be an integer (e.g. 42) or a float (e.g. 3.14). JavaScript does not have a separate type for representing integers and floating-point values, so they are both represented as numbers.
    
3.  BigInt: A BigInt is a special type for representing integers that are too large to be represented by the Number type. It is denoted by appending "n" to the end of the integer. Examples: 9007199254740991n, -9007199254740991n.
    
4.  Boolean: A boolean represents a true or false value. Examples: true, false.
    
5.  Undefined: A value is undefined if it has not been assigned a value. If you try to access a variable that has not been declared, it will also be undefined.
    
6.  Symbol: A symbol is a unique and immutable data type that is used to identify object properties. Symbols are created using the Symbol() function.
    
7.  Null: Null represents the absence of a value or a null reference. It is an empty or non-existent value.
    

```
const name = "Xam";//string literal
 
const age = 21;//number literal
 
const isApproved = true;//boolean literal
 
const firstName = undefined;//undefined literal
 
const selectedColor = null;//null literal
 
const lastName = Symbol("last name");//symbol literal
 
const bigInt = 9007199254740991n;//bigint literal
```


Explaining Objects or non-primitive data types:

In JavaScript, an object is a collection of properties, where a property is an association between a name (or key) and a value. Objects in JavaScript are similar to objects in real life. For example, a car is an object that has properties such as make, model, year, color, etc. Each of these properties has a value, such as "Toyota" for make, "Corolla" for model, and so on.

Here is an example of how you might represent a car object in JavaScript:

```
 const car = {
    make: 'Toyota', //property
    model: 'Corolla',//property
    year: 2020, //property
    color: 'silver', //property
    mileage: 0, //property
    drive: function() { //method
    console.log('The car is driving.');
 }
};
```


In this example, the `car` object has five properties: `make`, `model`, `year`, `color`, and `mileage`. The `make` and `model` properties have string values, the `year` property has a number value, and the `color` property has a string value. The `mileage` property has a number value that represents the number of miles the car has driven.

The `car` object also has a method called `drive`, which is a function that can be called to make the car drive. To call the `drive` method, you can use the following syntax:

This will output the string "The car is driving." to the console.

You can access the properties of an object using dot notation or bracket notation. For example, to access the `make` property of the `car` object, you can use either of the following:

```
console.log(car.make);  // Toyota
console.log(car['make']);  // Toyota
```


You can also add, modify, or delete properties of an object using the same dot notation or bracket notation. For example, to add a new property called owner to the car object, you can use the following syntax:

To modify the value of an existing property, you can simply assign a new value to it. For example, to change the `color` of the `car` object to "red", you can use the following syntax:

To `delete` a property from an object, you can use the delete operator. For example, to delete the `owner` property from the `car` object, you can use the following syntax:

Another Example:

Here is an example of an object that represents a mobile phone:

*   This object has six properties: `make`, `model`, `year`, `color`, `storage`, and `call`. The `make` and `model` properties are strings that represent the brand and model of the phone, the `year` property is a number that represents the year the phone was released, the color property is a string that represents the `color` of the phone, and the `storage` property is a number that represents the amount of storage the phone has.
    
*   The `call` and `text` properties are methods that allow you to make a phone call or send a text message. You can call these methods using the dot notation, like this:
    
*   You can also add new properties to the `phone` object or modify existing ones using assignment:
    

Advance Example:(Extra Knowledge)

In JavaScript, an object can be used to represent a social media account. For example:

```
 
const socialMediaAccount = {
  username: 'Subham Maity',
  platform: 'Instagram',
  followers: 1400,
  posts: [
    {
      caption: 'Having a great time at the beach!',
      likes: 50,
      comments: ['Looks like fun!', 'Wish I was there!']
    },
    {
      caption: 'Check out my new recipe for chocolate cake',
      likes: 100,
      comments: ['Yum! I can't wait to try it', 'Looks delicious']
    }
  ]
}
 
```


This object represents a social media account with a username, platform (e.g. Instagram), number of followers, and an array of posts. Each post has a caption, number of likes, and an array of comments.

In a real website, this object could be used to display information about a social media account, such as the number of followers and recent posts. For example, a website could display the caption and number of likes for each post, along with the comments left by other users.

```
const renderPosts = () => {
  const postList = document.getElementById('post-list');
  socialMediaAccount.posts.forEach(post => {
    const postElement = document.createElement('li');
    postElement.innerHTML = `
      <h3>${post.caption}</h3>
      <p>Likes: ${post.likes}</p>
      <ul>
        ${post.comments.map(comment => `<li>${comment}</li>`).join('')}
      </ul>
    `;
    postList.appendChild(postElement);
  });
}
 
renderPosts();
```


This code would create an `li` element for each post in the `socialMediaAccount` object and append it to the `post-list` element on the page. The `li` element would include the post's caption, number of likes, and a list of comments.