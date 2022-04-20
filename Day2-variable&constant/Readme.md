## JavaScript Variables
In programming, a variable is a container (storage area) to hold data. For example,
```
let num = 5;
```
Here, num is a variable. It's storing 5.

## JavaScript Declare Variables
In JavaScript, we use either var or let keyword to declare variables. For example,
```
var x;
let y;
```
Here, x and y are variables.

```
Note: It is recommended we use let instead of var. However, there are a few browsers that do not support let. Visit JavaScript let browser support to learn more.
```

## JavaScript Initialize Variables
#### We use the assignment operator = to assign a value to a variable.
```
let x;
x = 5;
```
Here, 5 is assigned to variable x.

#### You can also initialize variables during its declaration.
```
let x = 5;
let y = 6;
```
#### In JavaScript, it's possible to declare variables in a single statement.
```
let x = 5, y = 6, z = 7;
```
#### If you use a variable without initializing it, it will have an undefined value.

```
let x; // x is the name of the variable

console.log(x); // undefined
```
Here x is the variable name and since it does not contain any value, it will be undefined

## Change the Value of Variables
It's possible to change the value stored in the variable. For example,
```
// 5 is assigned to variable x
let x = 5; 
console.log(x); // 5

// vaue of variable x is changed
x = 3; 
console.log(x); // 3
```
The value of a variable may vary. Hence, the name variable.

## Rules for Naming JavaScript Variables
The rules for naming variables are:

- Variable names must start with either a letter, an underscore _, or the dollar sign $. For example,
```
//valid
let a = 'hello';
let _a = 'hello';
let $a = 'hello';
```
- Variable names cannot start with numbers. For example,
```
//invalid
Let 1a = 'hello'; // this gives an error
JavaScript is case-sensitive. So y and Y are different variables. For example,
let y = "hi";
let Y = 5;

console.log(y); // hi
console.log(Y); // 5
Keywords cannot be used as variable names. For example,
//invalid
let new = 5; // Error! new is a keyword.
```

#### Notes:

Though you can name variables in any way you want, it's a good practice to give a descriptive variable name. If you are using a variable to store the number of apples, it better to use apples or numberOfApples rather than x or n.
In JavaScript, the variable names are generally written in camelCase if it has multiple words. For example, firstName, annualSalary, etc.
JavaScript Constants
The const keyword was also introduced in the ES6(ES2015) version to create constants. For example,
```
const x = 5;
```
##### Once a constant is initialized, we cannot change its value.

```
const x = 5;
x = 10;  // Error! constant cannot be changed.
console.log(x)
```
Simply, a constant is a type of variable whose value cannot be changed.

Also, you cannot declare a constant without initializing it. For example,
```
const x;  // Error! Missing initializer in const declaration.
x = 5;
console.log(x)
```
Note: If you are sure that the value of a variable won't change throughout the program, it's recommended to use const. However, there are a few browsers that do not support const.