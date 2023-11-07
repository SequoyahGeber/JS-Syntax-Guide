# 1. Variables

Variables are used to store data values.

### Declare a variable

`let x;`
let declares a variable that can/will be changed later
`const x;`
const declares a variable that should not be changed later in the code
`var x;`
var is not used as much anymore, it was replaced by let

### Assign a value to a variable

`x = 5;`

### Single Line

`let/const/var y = 10;`

# 2. Comparison Statements

Comparison statements are used to compare values and make decisions.

### Equality

```
if (x == y) "==" is equal to
{

Code to execute if x is equal to y

}


if (x === y) "===" is equal value and equal type
{

Code to execute if x is equal to y

}

```

### Inequality

```
if (x != y) "!=" is not equal to
{

Code to execute if x is not equal to y

}

if (x !== y) "!==" is not equal value and equal type
{

Code to execute if x is not equal to y

}
```

Less than, less than or equal to, greater than, greater than or equal to

```

if (x < y)
if (x <= y)
if (x > y)
if (x >= y)

```

# 3. Boolean Statements/Logical Operators

Logical operators are used to determine the logic between variables or values.

### AND

```
if (x < 10 && y > 1) is x less than 10 and is y > 1
{

Code to execute if both conditions are true

}
```

### ELSE

```
else (no parameter needed, activated if the "if" statement cannot activate)
{

Code to execute if the conditions are not met

}
```

### OR

```

if (x == 5 || y == 5) is x equal to 5 or is y equal to 5
{

Code to execute if at least one condition is true

}

```

### NOT

```

if !(x == y) is x not equal to y
{

Code to execute if the condition is false

}

```

# 4. Arrays

Arrays are used to store collections of data.
`let/const/var animals = ['cat', 'dog', 'bird'];`

### Target an element in the array by index

`let firstanimal = animals[0];`

### Modify/reassign an element in the array

`animals[1] = 'moose';`

# 5. Objects

Objects are used to group related data and functions.

Properties must have a ":" and after the value a ","

Property values can be variables

```

let user = {
firstName: 'Sequoyah',
lastName: 'Geber',
age: 18,
};

```

### Target a property in the object

`let firstName = user.firstName;`

### Modify object properties

`user.age = 20;`

### Set object property name as a variable

```

let user = {
[firstName]: 'Sequoyah'
}

```

# 6. Functions

Functions are blocks of code that can be called and reused.

Functions can be nested

Variables declared inside a function do not exist outside the function

```

function printValue() {
let x = 10;
console.log(x);
}

```

### Call the function

`printValue();`

### Nested function and function parameters

add() is the nested function

```

let x = 5;
function add(){
x++;
console.log(x);
}
function printValue() {
console.log(x);
add();
}

```

### Functions and Parameters

Functions can accept parameters

"name" is the parameter

```

function greet(name) {
console.log('Hello, ' + name + '!');
}

```

### Call the function with an argument

`greet('Alice');`

When called it will replace the variable 'name' in the function with 'Alice'

# 7. Loops

Loops are used to execute a block of code repeatedly.

### "For" Loop

i is the index, can be declared elsewhere

let i = 0; what index to start the loop at

i < 5; as long as i is less than 5 continue running

i++ (no ; needed as it`s the last parameter) add 1 to the index value each time the loop executes

```

for (let i = 0; i < 5; i++) {

Code to repeat 5 times

}

```

### "While" Loop

```

let count = 0;
while (count < 5) {

Code to repeat as long as the condition is true

count++;

If the value is not increased every loop, the code runs infinitely, will freeze your computer if it's not stopped

}

```

# 8. Data Types

The various data types include null, numbers, strings, booleans, arrays, and objects.

```

let x; => Empty Variable
let x = null; => Null Variable
let x = 10; => Number
let x = 'Hi'; => String
let x = true; => Boolean
let x = [1, 2, 3]; => Array
let x = { name: 'Sequoyah', age: 18 }; => Object

Arrays can contain strings, numbers, objects, booleans etc
```

# 9. Comments

Comments are used to explain what your code does. It's important to make it readable in case someone else needs to read your code or in case you forget what it does
`//This is a single-line comment in JS`

```

/* This is a
multi-line
comment */

```

```

```
