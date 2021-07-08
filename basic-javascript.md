##################################################################
########################### Variables ############################
##################################################################

Initializing Variables with the Assignment
``` javascript
var a = 9;
```
if a variable is declared but is not assigned it is undefined and if you do a mathematical operation on it then it will result in NaN (Not a Number)
``` javascript
var a; //undefined
```
variable and function names are case-sensitive 

MYVAR and myvar are different variables
In JavaScript we use camelCase!


// Incrementing a number
``` javascript
let i = 0
i++
//decrementing a variable
let j = 0
j--
```
-- Remainder operator
Great to check if a number is even or odd
``` JavaScript

5 % 2 // = 1
// because 
Math.floor ( 5 / 2 ) = 2
// 2 * 2 // = 4
// 5 - 4 // = 1
```




--  Escaping Literal Quotes in Strings --
You can 'escape' a quote and prevent the computer from thinking it isn the end of hte quote by using a \ (backslash)


``` JavaScript
let sampleStr = "Alan said, \"Peter is learning JavaSCript\".";
// Alan said, "Peter is learning JavaScript".
```




parseInt

Convert a string into a integer

```Javascript
let a = parseInt("007")
```

you can give parseInt() a second variable that is a radix. The radix is an integer between 2 and 36. it tells javascript what base the number is

```Javascript
let a = parseInt("11", 2); // is base 2 and converts string "11" to an integer of the value of 3.
parseInt("10011",2) // returns 19
```

Ternary

```JavaScript
a ? b : c
// a is the condition
// b if true
// c if false
```