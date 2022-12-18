<h1><span className="text-center font-bold  text-transparent text-4xl tex bg-clip-text bg-gradient-to-r from-purple-400 to-pink-600">  Primitive Data Types & Object </span></h1>


## ➡️ Primitive Data Types?

<div className= "mt-3"></div>
<div className="cardTexture1 texture01">
    <h11 className="textStyle1" >
        <h10  style={{padding: "8px"}} className = " font-bold md:text-1xl text-cyan-400 " align="left">
            JavaScript has 7 primitive data types:
        </h10>


        1. String: A string is a sequence of characters, represented by either single or double quotes. Examples: "hello", 'world'.

        2. Number: A number can be an integer (e.g. 42) or a float (e.g. 3.14). JavaScript does not have a separate type for representing integers and floating-point values, so they are both represented as numbers.

        3. BigInt: A BigInt is a special type for representing integers that are too large to be represented by the Number type. It is denoted by appending "n" to the end of the integer. Examples: 9007199254740991n, -9007199254740991n.

        4. Boolean: A boolean represents a true or false value. Examples: true, false.

        5. Undefined: A value is undefined if it has not been assigned a value. If you try to access a variable that has not been declared, it will also be undefined.

        6. Symbol: A symbol is a unique and immutable data type that is used to identify object properties. Symbols are created using the Symbol() function.

        7. Null: Null represents the absence of a value or a null reference. It is an empty or non-existent value.
```js
const name = "Xam";//string literal

const age = 21;//number literal

const isApproved = true;//boolean literal

const firstName = undefined;//undefined literal

const selectedColor = null;//null literal

const lastName = Symbol("last name");//symbol literal

const bigInt = 9007199254740991n;//bigint literal
```
</h11>
</div>


<Callout type="info" emoji="ℹ️">
   For remmeber this you can simply remember this by using the acronym "SSBBNNU" for the primitive data types.
</Callout>
<Callout type="info" emoji="ℹ️">
    You can also check the variable type by using the typeof operator.
    ```js
    let d = BigInt(9007199254740991);
    console.log(typeof d); //output: bigint
    ```
</Callout>

## ➡️ Objects

<div className= "mt-3"></div>
<div className="cardTexture1 texture01">
<h11 className="textStyle1" >
    <h10  style={{padding: "8px"}} className = " font-bold md:text-1xl text-cyan-400 " align="left">
        Explaining Objects or non-primitive data types:
    </h10>
    In JavaScript, an object is a collection of properties, where a property is an association between a name (or key) and a value. Objects in JavaScript are similar to objects in real life. For example, a car is an object that has properties such as make, model, year, color, etc. Each of these properties has a value, such as "Toyota" for make, "Corolla" for model, and so on.

    Here is an example of how you might represent a car object in JavaScript:

```js
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

```js
car.drive();
```
This will output the string "The car is driving." to the console.

You can access the properties of an object using dot notation or bracket notation. For example, to access the `make` property of the `car` object, you can use either of the following:

```js
console.log(car.make);  // Toyota
console.log(car['make']);  // Toyota
```

You can also add, modify, or delete properties of an object using the same dot notation or bracket notation. For example, to add a new property called owner to the car object, you can use the following syntax:

```js
car.owner = 'Subham';
```
To modify the value of an existing property, you can simply assign a new value to it. For example, to change the `color` of the `car` object to "red", you can use the following syntax:
```js
car.color = 'red';
```
To `delete` a property from an object, you can use the delete operator. For example, to delete the `owner` property from the `car` object, you can use the following syntax:
```js
delete car.owner;
```


<h13 className ="font-bold text-cyan-400" > Another Example: </h13>

Here is an example of an object that represents a mobile phone:

    <div  className="flex justify-between ">
        <iframe className="mt-6 border-sky-200 border-opacity-20 imageBorderNormal"
                src="https://stackblitz.com/edit/js-t3zvut?devToolsHeight=33&file=index.js"
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

- This object has six properties: `make`, `model`, `year`, `color`, `storage`, and `call`. The `make` and `model` properties are strings that represent the brand and model of the phone, the `year` property is a number that represents the year the phone was released, the color property is a string that represents the `color` of the phone, and the `storage` property is a number that represents the amount of storage the phone has.
- The `call` and `text` properties are methods that allow you to make a phone call or send a text message. You can call these methods using the dot notation, like this:

- You can also add new properties to the `phone` object or modify existing ones using assignment:

<h13 className ="font-bold text-cyan-400" > Advance Example:(Extra Knowledge) </h13>

In JavaScript, an object can be used to represent a social media account. For example:

```js

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

```jsx
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

</h11>
</div>