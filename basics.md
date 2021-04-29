# Language: Javascript (the most basic and entry level language to learn I think ¯\_◉‿◉_/¯)

## Key Concepts
### Comments
To annotate your code or organize it

#### Example
```javascript
// Single-line comment

/* Multiline
comment */
```

### Variable or `var`
You can use variables to store and get data

#### Example
```javascript
var x; // to make the variable x but not put anything in it  
var x = 5; // a variable x with the value of the number 5 which can be changed
const x = 5; // a variable x with the value of the number which cant be changed 
var x = 'five'; // a variable x with the value of the string 'five' 
var x = [1, 2, 3]; // a variable x with the value of a array with the contents of the numbers 1, 2, and 3 
var x = {
  name: "John Doe",
} // a variable x with the value of a object with the key:value pair of name to John Doe 
var x = function () {
  console.log('hello');
} /* 
  a variable x with the value of a function when executed will print hello to the console 
  NOTE: if you have a variable with a function in it as a value, instead of doing 'x', you would do 'x()'
*/
```
### Functions
A chunk of code to do something

#### Example
```javascript
function log(x) {
  console.log(x);
} // a function called log which when executed with a arguments (the x), it would execute console.log(x)
/* You would run it by doing */
log('hello'); /* which equals to */ console.log('hello');
```

### Objects
Like a variable but is a collection of related data and/or functionality

#### Example
```javascript
var person = {
  firstName: "John",
  lastName: "Doe",
  greeting: function() {
    console.log("Hello! I'm " + this.firstName + " " + this.lastName + ".")
  }
}

/* now if we wanted get the person's first name we would do */
person.firstName
/* or if we wanted to get the person's last name we would do */
person.lastName
/* --- NOTE --- 
 * you dont have to put a dot; you can also do person['lastName'] instead
 * --- NOTE --- */
/* lastly if we wanted the person to greet us then we would do */
person.greeting()
```
# :warning: `everything in Javascript is a object` :warning:

### Arrays
List-like objects <br>
:warning: instead of it starting from 1, it starts from 0 :warning:
#### Example
```javascript
var groceries = ['eggs', 'milk', 'butter', 'cheese', 'bread'] // a basic list with 5 items
/* to add something at the end you would do */
groceries.push('juice')
/* to delete something at the end you would do */
groceries.pop()
/* to add something at the beginning you would do */
groceries.unshift('juice')
/* to remove something at the beginning you would do */
groceries.shift()
/* to get the index of a item */
groceries.indexOf('milk') /* equals to 1 */
/* finally to get the length of the array */
groceries.length
/* to access the last thing in the array */
var last = groceries[groceries.length - 1]
```

### Classes
A template for objects

### Example
```javascript

```
