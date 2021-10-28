# Javascript Functions


## Objective

### By the end of this lesson, students will be able to:

- Recognize the structure of a function.
- Define what the purpose of a function is, and what it accomplishes.
- Be able to declare and call a function in Javascript.
- Know the difference between invoking and referencing a function.

--------------
## What is a function, and why is it important?


### Functions:

- Functions are a fundamental element of Javascript.
- Very simply, functions are chunks of Javascript code that can be re-used in order to perform a given task.

### Benefits of utilizing functions:

- They are easily applied and re-usable.
- They promote the DRY (Do Not Repeat Yourself) paradigm.
- They provide organization and clarity to your code.

----------------
## Components of a Function


### Familiar Syntax

The syntax of a function follows the pattern that is found throughout Javascript.

``` 
function () {}

```

This pattern is easily recognized from for loops and if/else statements. It follows the pattern of accessing the Javascript keyword that we want to use, defining the parameters of that keyword between the parenthesis, and providing the code block that will be executed based on those parameters within the curly bracers. Functions are also typically given a descriptive name, especially when we want to reference or invoke them later.

Example:

```
function findTheSum (a, b) {
    console.log(a + b)
}
```
----------
## Invoking a Function


Now that the ```findTheSum``` function is defined, the next step is to invoke or call the function. This step tells the program when the function is to be executed and what values are to be passed into the function.

Example:

```
function findTheSum (a, b) {
    console.log(a + b)
}

findTheSum(2,3)

// What is the output?

```

## Parameters, Values and Arguments

Knowing the proper format of a function in Javascript is great, but it is important to understand the correct names for each step. 

### Parameters:

The parameters are the variables that are listed as a part of initially defining the function. Functions do not require parameters, but are present in most. In ```findTheSum``` the parameters are ```(a,b)```.

### Values and Arguments:

The values that are going to be passed in to the function are defined when the function is called or invoked. Arguments is the term that is given to the values that are passed into the function. Arguments are applied to the function in the order that they appear in the parenthesis when invoked. The values/arguments of the above example are ```(2,3)```.

---------
## The Difference Between Calling and Referencing a Function


If we have defined a function, in order to see the function in action we need to call it.

Example:

```
// First, we can call the function without passing any values/arguments.
findTheSum() 

// Next, we can call the function by passing in arguments.
findTheSum(1,2)

```

A function can also be referenced by typing the function without the parenthesis.

```
findTheSum

```

The difference between referencing and calling a function is that when a function is called, it is immediately executed. When a function is referenced, it is stored for use based on a given instruction.

--------
## We Do: Put it all together.


We will write a function that takes two integers as parameters and multiplies them together. The output will be the product of the two arguments.

- First, defining the function and its parameters:

```
function multiplication (x,y) {

}
```
- Next, writing the code block that performs the action:

```
function multiplication (x,y) {
    product = x * y
    console.log(product)
}
```
- Lastly, calling the function with arguments:

```
function multiplication (x,y) {
    product = x * y
    console.log(product)
}

multiplication(4,5)

What is the output?
```
----------
## You Do: Write a function!


Write a function that takes a string, ```name``` , as the parameter. The function should take in a name and the output should be "Hello, ```name```. How are you today?".

----------
## Conclusion


Functions are a fundamental component of Javascript. They are snippets of code that are re-useable and perform tasks. They are important for DRY coding, organization, and easy application. Functions follow the same three-part syntax that is found throughout Javascript. The elements of a function are the keyword, the parameters, the code block, and the values/arguments. In order for a function to be executed it needs to be called or referenced to be used later. 





