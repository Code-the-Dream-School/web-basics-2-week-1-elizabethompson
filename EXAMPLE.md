# Web Basics 2: Week 1 Assignment Example

## Challenge 1: Create a variable and print the value

Create a variable and assign it any value:

```javascript
const hello = 'hello world'
```

Use `console.log` to print out your variable:

```javascript
console.log(hello)
```

### Final code:

```javascript
const hello = 'hello world'

console.log(hello)
```

### Output:

```javascript
'hello world'
```

## Challenge 2: Create variables for your first and last name then print your full name

Create a variable called `firstName` and assign your first name as the string value:

```javascript
const firstName = 'Elizabeth'
```

Create a variable called `lastName` and assign your last name as the string value:

```javascript
const lastName = 'Thompson'
```

Use `console.log` to print out your full name:

Method 1: String Concatenation

```javascript
console.log(firstName + ' ' + lastName)
```

OR

Method 2: Template Literals

```javascript
console.log(`${firstName} ${lastName}`)
```

> Read more about [Template Literals](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Template_literals)

### Final code:

```javascript
const firstName = 'Elizabeth'
const lastName = 'Thompson'

console.log(`${firstName} ${lastName}`)
```

### Output:

```javascript
'Elizabeth Thompson'
```

## Challenge 3: Calculate the total price rounded to two decimals

Create a variable called `price` and assign a float value:

```javascript
const price = 9.98
```

Create a variable called `quantity` and assign an integer value:

```javascript
const quantity = 5
```

Create a variable called `total` and assign the value of `price` multiplied by `quantity`:

```javascript
const total = price * quantity
```

Use `console.log` to print out the `total` (rounded to the nearest two decimals):

```javascript
const totalRounded = total.toFixed(2)
console.log(`$${totalRounded}`)
```

> Read more about the [toFixed() method](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number/toFixed)

### Final code:

```javascript
const price = 9.98
const quantity = 5
const total = price * quantity
const totalRounded = total.toFixed(2)

console.log(`$${totalRounded}`)
```

### Output:

```javascript
'$49.90'
```

## Challenge 4: Declare a variable and conditionally assign it a value

Create a variable called `weather` and assign "Rainy" as the string value:

```javascript
const weather = 'Rainy'
```

> Read more about the [const statement](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/const)

Declare a variable called `message` and don't assign it a value:

```javascript
let message
```

> Read more about the [let statement](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/let)

Create a conditional statement that checks if `weather` is equal to "Sunny":

```javascript
if (weather === 'Sunny') {

}
```

If `weather` meets the condition above, then set `message` equal to "Yay! It's sunny outside":

```javascript
if (weather === 'Sunny') {
  message = "Yay! It's sunny outside"
}
```

Add an `else` clause that sets `message` equal to "Aww! It's not sunny outside":

```javascript
if (weather === 'Sunny') {
  message = "Yay! It's sunny outside"
} else {
  message = "Aww! It's not sunny outside"
}
```

Use `console.log` to print out the value of `message`:

```javascript
console.log(message)
```

### Final code:

```javascript
const weather = 'Rainy'
let message

if (weather === 'Sunny') {
  message = "Yay! It's sunny outside"
} else {
  message = "Aww! It's not sunny outside"
}

console.log(message)
```

### Output:

```javascript
"Yay! It's sunny outside"
```

## Challenge 5: Create a function that returns any string

Create a function called `myFunction` using the function keyword:

```javascript
function myFunction() {

}
```

Add a return statement in your function which returns a random string:

```javascript
function myFunction() {
  return 'I called a function!'
}
```

Use `console.log` to print out the output of `myFunction()`:

```javascript
console.log(myFunction())
```

### Final code:

```javascript
function myFunction() {
  return 'I called a function!'
}

console.log(myFunction())
```

### Output:

```javascript
'I called a function!'
```

## Challenge 6: Rewrite the function in Challenge #5 as an arrow function

Create a function called `myArrowFunction` using the arrow syntax:

```javascript
const myArrowFunction = () => {
  
}
```

Add a return statement in your function which returns a random string:

Method 1: Explicit Return

```javascript
const myArrowFunction = () => {
  return 'I called an arrow function!'
}
```

OR

Method 2: Implicit Return

```javascript
const myArrowFunction = () => 'I called an arrow function!'
```

> Read more about [arrow function return rules](https://medium.com/@bunlong/arrow-functions-return-rules-in-javascript-b63ed5f25994)

Use `console.log` to print out the output of `myArrowFunction()`:

```javascript
console.log(myArrowFunction())
```

### Final code:

```javascript
const myArrowFunction = () => 'I called an arrow function!'

console.log(myArrowFunction())
```

### Output:

```javascript
'I called an arrow function!'
```

## Challenge 7: Create a function returns a string in all uppercase

Create a function called `stringToUpper`:

```javascript
const stringToUpper = () => {}
```

Add a parameter called `str` in your function signature:

```javascript
const stringToUpper = (str) => {}
```

Add a return statement in your function which returns the input string in all uppercase letters:

```javascript
const stringToUpper = (str) => str.toUpperCase()
```

> Read more about the [toUpperCase() method](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/toUpperCase)

Use `console.log` to print out the output of `stringToUpper(str)`:

```javascript
console.log(stringToUpper('why am i screaming'))
```

### Final code:

```javascript
const stringToUpper = (str) => str.toUpperCase()

console.log(stringToUpper('why am i screaming'))
```

### Output:

```javascript
'WHY AM I SCREAMING'
```

## Challenge 8: Create a function that accepts a number argument and returns double its value

Create a function called `multiplyByTwo`:

```javascript
function multiplyByTwo() {

}
```

Add a parameter called `number` in your function signature:

```javascript
function multiplyByTwo(number) {

}
```

Add a return statement in your function which returns `number` times two:

```javascript
function multiplyByTwo(number) {
  return number * 2
}
```

Create a variable called `num1` and assign it to the result of `multiplyByTwo(1)`:

```javascript
const num1 = multiplyByTwo(1)
```

Create a variable called `num2` and assign it to the result of `multiplyByTwo(5)`:

```javascript
const num2 = multiplyByTwo(5)
```

Create a variable called `num3` and assign it to the result of `multiplyByTwo(10)`:

```javascript
const num3 = multiplyByTwo(10)
```

Use `console.log` to print out the value of `num1`, `num2`, and `num3`:

```javascript
console.log(num1, num2, num3)
```

### Final code:

```javascript
function multiplyByTwo(number) {
  return number * 2
}

const num1 = multiplyByTwo(1)
const num2 = multiplyByTwo(5)
const num3 = multiplyByTwo(10)

console.log(num1, num2, num3)
```

### Output:

```javascript
2, 10, 20
```
