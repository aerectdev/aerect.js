# aerect.js
A light-weight wrapper to make your coding easier with simple functions

# Examples
- Import the Package
```js
const aerect = require('aerect.js');
```
- Get a random element from an array. Parameters: `array`: The array to choose the random element from (required)
```js
const array = ['a', 'b', 'c', 'd', 'e']
console.log(aerect.randomize(array)); // a
```
- Generate random numbers. Parameters: `digits`: Number of digits (required)
```js
const digits = 5 // Number of digits
console.log(aerect.generateNumber(digits)); // 54759
```
- Generate random ID. Parameters: `length`: Length of the ID (required)
- ```js
const length = 10 // Length of the ID
console.log(aerect.generateID(length)); // MqXXuvhPAl
```
