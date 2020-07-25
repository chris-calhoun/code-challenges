## Definitions

# Variables

Variables are used to hold a value. An example is x = 5. In this case, x is the variable and it has a value of 5. In Javascript, you can call variables using var, let, and const:

var x = 5;
let y = 6;
const z = 7;

If you want to find the sum of x, y, and z you could do:

console.log(x + y + z)

and the values that x, y, and z represent will be added together.

# Strings

Strings are used to represent data in text form. An example is 'Hello, World'. The single quotes signal that the data is a string. However, double quotes can be used as well.

# Functions (arguments, `return`)

Functions are blocks of code used to perform a specific task. Functions are useful because they are reusable and section off related portions of code. For example, if you wanted to add two numbers you could create the function below.

const addNumbers = (a,b) => {
return a + b;
}
console.log(addNumbers(2,4))

The 'a' and 'b' represent the parameters of the function. The 2 and 4 represent the arguments of the functions. The 2 is being passed in for the 'a' parameter and the 4 is being passed in for the 'b' parameter.

Functions must be invoked to be used. In this example, the invocation takes place with 'addNumbers(2,4))

# `if` statements

If statements are used to run a specific block of code if an expression is 'true'. In the scenario below, if the value of variable a is equal to the value of variable b, the string 'Equal' will be returned. However, if it is not equal, the string 'Not Equal' will be returned.

if (a===b) {
return 'Equal';
} else {
return 'Not Equal';
}

# Boolean values (`true`,`false`)

Booleans values represent either true or false. Which is similar to 1/0, yes/no, and on/off, respectively. Booleans values of an expression are used for conditional statements.
