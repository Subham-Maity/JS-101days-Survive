# Operators & Expressions – CodeXam
Operators & Expressions explained

Operators are special symbols in JavaScript that perform specific operations on one, two, or three operands, and then return a result.

![](https://github.com/Subham-Maity/javascript_codexam/blob/main/006.%20Operator%20and%20Expression/1.png?raw=true)

### ⭐ Arithmetic Operators[](#-arithmetic-operators)

#### ⚡ Example[](#-example)

```
let x = 5;// x = 5
let y = 4;// y = 4
let z = x + y;// output: 9 (addition)
 
let x1 = 5;// x1 = 5
let y1 = 4;// y1 = 4
let z1 = x1 - y1;// output: 1 (subtraction)
 
let x2 = 5;// x2 = 5
let y2 = 4;// y2 = 4
let z2 = x2 * y2;// output: 20 (multiplication)
 
let x3 = 5;// x3 = 5
let y3 = 4;// y3 = 4
let z3 = x3 / y3;// output: 1.25 (division)
 
let x4 = 5;// x4 = 5
let y4 = 4;// y4 = 4
let z4 = x4 % y4;// output: 1 (modulus)
 
let x5 = 5;// x5 = 5
let y5 = 4;// y5 = 4
let z5 = x5++;// output: 6 (increment)
 
let x6 = 5;// x6 = 5
let y6 = 4;// y6 = 4
let z6 = x6--;// output: 4 (decrement)
 
```


#### ⚡ Playgrounds[](#-playgrounds)

#### ⚡ Extra Doubts[](#-extra-doubts)

##### 💥 What is the difference between ++x and x++?[](#-what-is-the-difference-between-x-and-x)

In JavaScript, the "++" operator is used to increment a value by 1. This operator can be used in either a "pre" or "post" form.

**Pre-Increment**

The pre-increment operator (++x) increments the value of the operand before the expression is evaluated.

```
        let x = 10;
        console.log(++x); // Output: 11
        console.log(x); // Output: 11
```


In this example, the value of "x" is incremented from 10 to 11 before it is logged to the console. The value of "x" is then logged to the console, which outputs 11.

**Post-Increment**

The post-increment operator (x++) increments the value of the operand after the expression is evaluated.

```
        let x = 10;
        console.log(x++); // Output: 10
        console.log(x); // Output: 11
```


In this example, the value of "x" is logged to the console (which outputs 10), and then the value of "x" is incremented to 11.

The main difference between pre-increment and post-increment is the order in which the operand is incremented and the expression is evaluated. In the case of pre-increment, the value is incremented before the expression is evaluated, while in the case of post-increment, the value is incremented after the expression is evaluated.

##### 💥 What is the difference between --x and x--?[](#-what-is-the-difference-between---x-and-x--)

In JavaScript, the "--" operator is used to decrement a value by 1. This operator can be used in either a "pre" or "post" form.

**Pre-Decrement**

The pre-decrement operator (--x) decrements the value of the operand before the expression is evaluated.

```
        let x = 10;
        console.log(--x); // Output: 9
        console.log(x); // Output: 9
```


In this example, the value of "x" is decremented from 10 to 9 before it is logged to the console. The value of "x" is then logged to the console, which outputs 9.

**Post-Decrement**

The post-decrement operator (x--) decrements the value of the operand after the expression is evaluated.

```
        let x = 10;
        console.log(x--); // Output: 10
        console.log(x); // Output: 9
```


In this example, the value of "x" is logged to the console (which outputs 10), and then the value of "x" is decremented to 9.

The main difference between pre-decrement and post-decrement is the order in which the operand is decremented and the expression is evaluated. In the case of pre-decrement, the value is decremented before the expression is evaluated, while in the case of post-decrement, the value is decremented after the expression is evaluated.

### ⭐ Assignment Operators[](#-assignment-operators)

#### ⚡ Example[](#-example-1)

```
 
let x = 5;// x = 5
let y = 4;// y = 4
let z = x + y;// output: 9 (assignment operator)
 
let x1 = 5;// x1 = 5
let y1 = 4;// y1 = 4
let z1 += x1 + y1;// output: 14 (add and assignment operator)
 
let x2 = 5;// x2 = 5
let y2 = 4;// y2 = 4
let z2 -= x2 + y2;// output: 0 (subtract and assignment operator)
 
let x3 = 5;// x3 = 5
let y3 = 4;// y3 = 4
let z3 *= x3 + y3;// output: 45 (multiply and assignment operator)
 
let x4 = 5;// x4 = 5
let y4 = 4;// y4 = 4
let z4 /= x4 + y4;// output: 1.25 (divide and assignment operator)
 
let x5 = 5;// x5 = 5
let y5 = 4;// y5 = 4
let z5 %= x5 + y5;// output: 1 (modulus and assignment operator)
 
```


#### ⚡ Playgrounds[](#-playgrounds-1)

### ⭐ Comparison Operators[](#-comparison-operators)

#### ⚡ Example[](#-example-2)

```
 
let x = 5;// x = 5
let y = 4;// y = 4
let z = x == y;// output: false (equal to operator)
 
let x1 = 5;// x1 = 5
let y1 = 4;// y1 = 4
let z1 = x1 != y1;// output: true (not equal to operator)
 
let x2 = 5;// x2 = 5
let y2 = 4;// y2 = 4
let z2 = x2 > y2;// output: true (greater than operator)
 
let x3 = 5;// x3 = 5
let y3 = 4;// y3 = 4
let z3 = x3 < y3;// output: false (less than operator)
 
let x4 = 5;// x4 = 5
let y4 = 4;// y4 = 4
let z4 = x4 >= y4;// output: true (greater than or equal to operator)
 
let x5 = 5;// x5 = 5
let y5 = 4;// y5 = 4
let z5 = x5 <= y5;// output: false (less than or equal to operator)
 
let x6 = 5;// x6 = 5
let y6 = 4;// y6 = 4
let z6 = x6 === y6;// output: false (strict equal to operator)
 
let x7 = 5;// x7 = 5
let y7 = 4;// y7 = 4
let z7 = x7 !== y7;// output: true (strict not equal to operator)
 
```


#### ⚡ Playgrounds[](#-playgrounds-2)

#### ⚡ Extra Doubts[](#-extra-doubts-1)

##### 💥 What is the difference between == and ===?[](#--what-is-the-difference-between--and-)

In JavaScript, the "==" operator is used to perform a loose comparison, which means that it compares the values of the operands without considering their types. The "===" operator, on the other hand, is used to perform a strict comparison, which means that it compares the values and the types of the operands.

Here are a few examples to illustrate the difference between "==" and "===":

```
        console.log(10 == '10'); // Output: true
        console.log(10 === '10'); // Output: false
 
        console.log(null == undefined); // Output: true
        console.log(null === undefined); // Output: false
 
        console.log(true == 1); // Output: true
        console.log(true === 1); // Output: false
 
        let x = {};
        let y = {};
        console.log(x == y); // Output: false
        console.log(x === y); // Output: false
```


In the first example, the "==" operator returns true because the values of the operands are equal, even though their types are different (one is a number and the other is a string). The "===" operator returns false because it also checks the types of the operands, and the types are not equal.

In the second example, the "==" operator returns true because both operands are considered "falsy" values (null and undefined are considered falsy). The "===" operator returns false because it also checks the types of the operands, and the types are not equal.

In the third example, the "==" operator returns true because the value of the "true" operand is coerced to 1, which is equal to the value of the "1" operand. The "===" operator returns false because it also checks the types of the operands, and the types are not equal.

In the fourth example, the "==" operator returns false because the operands are references to two different objects, which are not considered equal. The "===" operator also returns false because it checks the types of the operands, which are both objects.

### ⭐ Logical Operators[](#-logical-operators)

#### ⚡ Example[](#-example-3)

```
let x = 5;// x = 5
let y = 4;// y = 4
let z = x && y;// output: 4 (logical and operator)
 
let x1 = 5;// x1 = 5
let y1 = 4;// y1 = 4
let z1 = x1 || y1;// output: 5 (logical or operator)
 
let x2 = 5;// x2 = 5
let y2 = 4;// y2 = 4
let z2 = !x2;// output: false (logical not operator)
```


#### ⚡ Playgrounds[](#-playgrounds-3)

### ⭐ Bitwise Operators[](#-bitwise-operators)

#### ⚡ Example[](#-example-4)

```
 
let a = 5; // 0000 0101
let b = 1; // 0000 0001
 
let c = a & b; // 0000 0001
let d = a || b; // 0000 0101
let e = a ^ b; // 0000 0100
let f = ~a; // 1111 1010
let g = a << 2; // 0001 0100
let h = a >> 2; // 0000 0001
```


#### ⚡ Playgrounds[](#-playgrounds-4)

### ⭐ String Operators[](#-string-operators)

#### ⚡ Example[](#-example-5)

```
 
let firstName = "John";
let lastName = "Doe";
let fullName = firstName + " " + lastName; // John Doe
 
let x = "Hello ";
x += "world!"; // Hello world!
```


#### ⚡ Playgrounds[](#-playgrounds-5)

### ⭐ Conditional (Ternary) Operator[](#-conditional-ternary-operator)

#### ⚡ Example[](#-example-6)

```
 
let age = 18;
let voteable = (age < 18) ? "Too young" : "Old enough";
console.log(voteable); // Old enough
```


#### ⚡ Playgrounds[](#-playgrounds-6)

### ⭐ Comma Operator[](#-comma-operator)

#### ⚡ Example[](#-example-7)

```
 
let a = (1 + 2, 3 + 4);
console.log(a); // 7
```


#### ⚡ Playgrounds[](#-playgrounds-7)

### ⭐ typeof Operator[](#-typeof-operator)

#### ⚡ Example[](#-example-8)

```
 
typeof 37 === 'number'; // true
typeof 3.14 === 'number'; // true
typeof Math.LN2 === 'number'; // true
typeof Infinity === 'number'; // true
typeof NaN === 'number'; // true
typeof Number(1) === 'number'; // true
typeof new Number(1) === 'object'; // true
typeof 'foo' === 'string'; // true
typeof 'bar' === 'string'; // true
typeof String('bar') === 'string'; // true
typeof new String('bar') === 'object'; // true
typeof true === 'boolean'; // true
typeof false === 'boolean'; // true
typeof new Boolean(true) === 'object'; // true
typeof undefined === 'undefined'; // true
typeof null === 'object'; // true
typeof Symbol() === 'symbol'; // true
typeof [] === 'object'; // true
typeof Array(5) === 'object'; // true
typeof function(){} === 'function'; // true
typeof new Function() === 'function'; // true
typeof new Date() === 'object'; // true
typeof /^(.+)$/ === 'object'; // true
typeof new RegExp('^(.+)

#### ⚡ Playgrounds[](#-playgrounds-8)

### ⭐ instanceof Operator[](#-instanceof-operator)

#### ⚡ Example[](#-example-9)

```
let today = new Date();
let answer = today instanceof Date;
 
console.log(answer); // true
```


#### ⚡ Playgrounds[](#-playgrounds-9)

### ⭐ in Operator[](#-in-operator)

#### ⚡ Example[](#-example-10)

```
let tree = { height: 10, color: 'green', grow() { this.height += 2; } };
'height' in tree; // true
'color' in tree; // true
'species' in tree; // false
'grow' in tree; // true
```


#### ⚡ Playgrounds[](#-playgrounds-10)

### ⭐ delete Operator[](#-delete-operator)

#### ⚡ Example[](#-example-11)

```
let tree = { height: 10, color: 'green', grow() { this.height += 2; } };
delete tree.color;
console.log(tree.color); // undefined
```


#### ⚡ Playgrounds[](#-playgrounds-11)

### ⭐ void Operator[](#-void-operator)

#### ⚡ Example[](#-example-12)

```
void 0; // undefined
void (0); // undefined
void 1; // undefined
void (1); // undefined
void 'foo'; // undefined
void ('foo'); // undefined
void true; // undefined
void (true); // undefined
void false; // undefined
void (false); // undefined
void null; // undefined
void (null); // undefined
void NaN; // undefined
void (NaN); // undefined
void Infinity; // undefined
void (Infinity); // undefined
void -Infinity; // undefined
void (-Infinity); // undefined
void 0n; // undefined
void (0n); // undefined
void Symbol(); // undefined
void (Symbol()); // undefined
void Symbol('foo'); // undefined
void (Symbol('foo')); // undefined
void Symbol.iterator; // undefined
void (Symbol.iterator); // undefined
void {}; // undefined
void ({}); // undefined
void []; // undefined
void ([]); // undefined
void function() {}; // undefined
void (function() {}); // undefined
void (() => {}); // undefined
void ((() => {})); // undefined
void class {}; // undefined
void (class {}); // undefined
void new Date(); // undefined
void (new Date()); // undefined
void new Date().getTime(); // undefined
void (new Date().getTime()); // undefined
void new Date().getTime().toString(); // undefined
void (new Date().getTime().toString()); // undefined
void new Date().getTime().toString().split(''); // undefined
void (new Date().getTime().toString().split('')); // undefined
void new Date().getTime().toString().split('').map(Number); // undefined
void (new Date().getTime().toString().split('').map(Number)); // undefined
void new Date().getTime().toString().split('').map(Number).reduce((a, b) => a + b); // undefined
void (new Date().getTime().toString().split('').map(Number).reduce((a, b) => a + b)); // undefined
void new Date().getTime().toString().split('').map(Number).reduce((a, b) => a + b, 0); // undefined
```


#### ⚡ Playgrounds[](#-playgrounds-12)

### ⭐ new Operator[](#-new-operator)

#### ⚡ Example[](#-example-13)

```
function Car(make, model, year) {
  this.make = make;
  this.model = model;
  this.year = year;
}
 
const mycar = new Car('Eagle', 'Talon TSi', 1993);
 
const kenscar = new Car('Nissan', '300ZX', 1992);
 
const vpgscar = new Car('Mazda', 'Miata', 1990);
```


#### ⚡ Playgrounds[](#-playgrounds-13)) === 'object'; // true
typeof {} === 'object'; // true
typeof new Object() === 'object'; // true
typeof new Set() === 'object'; // true
typeof new Map() === 'object'; // true
typeof new WeakSet() === 'object'; // true
typeof new WeakMap() === 'object'; // true
typeof new ArrayBuffer() === 'object'; // true
 
```


#### ⚡ Playgrounds[](#-playgrounds-8)

### ⭐ instanceof Operator[](#-instanceof-operator)

#### ⚡ Example[](#-example-9)

urltomarkdowncodeblockplaceholder140.06038145904944314

#### ⚡ Playgrounds[](#-playgrounds-9)

### ⭐ in Operator[](#-in-operator)

#### ⚡ Example[](#-example-10)

urltomarkdowncodeblockplaceholder150.4900750032336729

#### ⚡ Playgrounds[](#-playgrounds-10)

### ⭐ delete Operator[](#-delete-operator)

#### ⚡ Example[](#-example-11)

urltomarkdowncodeblockplaceholder160.955006542840813

#### ⚡ Playgrounds[](#-playgrounds-11)

### ⭐ void Operator[](#-void-operator)

#### ⚡ Example[](#-example-12)

urltomarkdowncodeblockplaceholder170.7521819218536268

#### ⚡ Playgrounds[](#-playgrounds-12)

### ⭐ new Operator[](#-new-operator)

#### ⚡ Example[](#-example-13)

urltomarkdowncodeblockplaceholder180.43629710155893076

#### ⚡ Playgrounds[](#-playgrounds-13)