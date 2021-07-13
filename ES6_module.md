##################################################################
########################### ES6 ##################################
##################################################################

ES5 was finalized in 2009
ES6 was released in 2015.
Create new features such as 'let' and 'const'.

### Var vs let and const
Var can be overwritten.
``` Javascript
var camper = 'James'
var camper = 'David'
console.log(camper)
```
outputs as 'David'

Let
```Javascript
let camper = 'James';
let camper = 'David';
```
gives an error


Var is declared globally unless inside of a function. 'Let' is global unless inside of a block, statement, or expression.
```Javascript
var numArray = [];
for (var i = 0; i < 3; i++) {
  numArray.push(i);
}
console.log(numArray);
console.log(i);
// outputs [0, 1, 2] and 3
```