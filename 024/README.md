# Js25 – CodeXam
Array methods are functions built-in to JavaScript that we can apply to our arrays — Each method has a unique function that performs a change or calculation to our array and saves us from writing common functions from scratch.

▶️ toString()[](#️-tostring)
----------------------------

Converts an array to a string of (comma separated) array values.

▶️ join()[](#️-join)
--------------------

Converts all elements of an array into a string using a separator string.

▶️ pop()[](#️-pop)
------------------

Removes the last element from an array and returns that element.

▶️ push()[](#️-push)
--------------------

Adds new items to the end of an array, and returns the new length.

▶️ shift()[](#️-shift)
----------------------

Removes the first element from an array and returns that element.

▶️ unshift()[](#️-unshift)
--------------------------

Adds new items to the beginning of an array, and returns the new length. pnpm

▶️ delete()[](#️-delete)
------------------------

Deletes an element from an array.

▶️ concat()[](#️-concat)
------------------------

Creates a new array by merging (concatenating) existing arrays.

▶️ sort()[](#️-sort)
--------------------

Sorts the elements of an array.

In this case, the compare function returns the difference of a and b, which determines the order of the elements in the sorted array. If a is smaller than b, a - b will be negative, so a will come before b in the sorted array. If a is greater than b, a - b will be positive, so b will come before a in the sorted array. If a is equal to b, a - b will be zero, so the order of the elements will not change.

**Let's consider the following numbers: \[22, 14, 5\].**

*   When comparing 22 and 14, the compare function returns 22 - 14 = 8, which is a positive number. This means that 14 should come before 22 in the sorted array.
*   When comparing 14 and 5, the compare function returns 14 - 5 = 9, which is a positive number. This means that 5 should come before 14 in the sorted array.
*   When comparing 5 and 22, the compare function returns 5 - 22 = -17, which is a negative number. This means that 22 should come before 5 in the sorted array.

**After these comparisons, the sorted array is \[5, 14, 22\].**

▶️ splice()[](#️-splice)
------------------------

Adds/Removes items to/from an array, and returns the removed item(s).

▶️ slice()[](#️-slice)
----------------------

Selects a part of an array, and returns the new array.

▶️ reverse()[](#️-reverse)
--------------------------

Reverses the order of the elements in an array.

▶️ forEach()[](#️-foreach)
--------------------------

Calls a function for each array element.

▶️ map()[](#️-map)
------------------

Creates a new array with the result of calling a function for each array element.

▶️ filter()[](#️-filter)
------------------------

Creates a new array with every element in an array that pass a test.

▶️ reduce()[](#️-reduce)
------------------------

Runs a function on each array element to produce (reduce it to) a single value.

▶️ Array from()[](#️-array-from)
--------------------------------

Used to create an array from an object.

▶️ for of[](#️-for-of)
----------------------

Used to get the value from an array.

▶️ for in[](#️-for-in)
----------------------

Used to get the keys from an array.





| No | Method | Purpose | Example |
| ---| ------ | ------- | ------- |
| 1 | map( ) | Transforms each element of an array using a function | [1,2,3].map(x => x * 2) returns [2,4,6] |
| 2 | filter( ) | Filters elements of an array using a function | [1,2,3].filter(x => x > 1) returns [2,3] |
| 3 | sort( ) | Sorts elements of an array | [3,1,2].sort() returns [1,2,3] |
| 4 | forEach( ) | Calls a function for each element of an array | [1,2,3].forEach(console.log) logs 1, then 2, then 3 |
| 5 | concat( ) | Concatenates two or more arrays | [1,2].concat([3,4]) returns [1,2,3,4] |
| 6 | every( ) | Tests if all elements of an array pass a test | [1,2,3].every(x => x > 0) returns true |
| 7 | some( ) | Tests if some elements of an array pass a test | [1,2,3].some(x => x > 2) returns true |
| 8 | includes( ) | Tests if an array includes a value | [1,2,3].includes(2) returns true |
| 9 | join( ) | Joins elements of an array into a string | [1,2,3].join() returns "1,2,3" |
| 10 | reduce( ) | Reduces the elements of an array to a single value by applying a function | [1,2,3,4].reduce((acc, cur) => acc + cur) returns 10 |
| 11 | find( ) | Returns the first value that passes a test | [1,2,3].find(x => x > 1) returns 2 |
| 12 | findIndex( ) | Returns the index of the first value that passes a test | [1,2,3].findIndex(x => x > 1) returns 1 |
| 13 | indexOf( ) | Returns the index of the first occurrence of a value | [1,2,3].indexOf(2) returns 1 |
| 14 | fill( ) | Fills elements of an array with a value | [1,2,3].fill(0) returns [0,0,0] |
| 15 | slice( ) | Extracts elements of an array into a new array | [1,2,3].slice(1,2) returns [2] |
| 16 | reverse( ) | Reverses the order of elements of an array | [1,2,3].reverse() returns [3,2,1] |
| 17 | push( ) | Adds one or more elements to the end of an array | [1,2,3].push(4) returns [1,2,3,4] |
| 18 | pop( ) | Removes the last element of an array | [1,2,3].pop() returns 3 |
| 19 | shift( ) | Removes the first element of an array | [1,2,3].shift() returns 1 |
| 20 | unshift( ) | Adds one or more elements to the beginning of an array | [1,2,3].unshift(0) returns [0,1,2,3] |
| 21 | splice() | Adds or removes elements of an array | [1,2,3].splice(1, 0, 4) returns [1,4,2,3] |
| 22 | copyWithin() | Copies elements within an array to a different position | [1,2,3,4].copyWithin(0, 2) returns [3,4,3,4] |
| 23 | entries() | Returns an iterator of key-value pairs for each element in the array | [1,2,3].entries() returns an iterator of [[0,1],[1,2],[2,3]] |
| 24 | keys() | Returns an iterator of the keys for each element in the array | [1,2,3].keys() returns an iterator of [0,1,2] |
| 25 | values() | Returns an iterator of the values for each element in the array | [1,2,3].values() returns an iterator of [1,2,3] |
| 26 | flat() | Flattens an array to a specified depth | [[1,2],[3,4]].flat() returns [1,2,3,4] |
| 27 | flatMap() | Maps elements of an array to a new array and then flattens it | [1,2,3].flatMap(x => [x * 2]) returns [2,4,6] |
| 28 | toString() | Returns a string representation of an array | [1,2,3].toString() returns "1,2,3" |
| 29 | toLocaleString() | Returns a localized string representation of an array | [1,2,3].toLocaleString() returns "1,2,3" (may vary based on locale) |
| 30 | toSource() | Returns a string representation of the source code of an array | [1,2,3].toSource() returns "([1, 2, 3])" |
| 31 | reduceRight( ) | Reduces elements of an array to a single value by applying a function from right to left | [1,2,3,4].reduceRight((acc, cur) => acc + cur) returns 10 |
| 32 | Object.entries( ) | Returns an array of key-value pairs for an object | Object.entries(\{a: 1, b: 2}) returns [['a', 1], ['b', 2]] |
| 33 | Object.keys( ) | Returns an array of the keys for an object | Object.keys(\{a: 1, b: 2}) returns ['a', 'b'] |
| 34 | Object.values( ) | Returns an array of the values for an object | Object.values(\{a: 1, b: 2}) returns [1, 2] |
| 35 | Array.isArray( ) | Determines if a value is an array | Array.isArray([1,2,3]) returns true |
| 36 | Array.of( ) | Creates a new array with a given length and values | Array.of(1, 2, 3) returns [1, 2, 3] |
| 37 | Array.from( ) | Creates a new array from an array-like or iterable object | Array.from('abc') returns ['a', 'b', 'c'] |
