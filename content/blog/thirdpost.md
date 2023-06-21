---
title: Intro to JS Practicals 
description: Advanced control flow and writing functions.
date: 2023-06-03
tags:
  - Control Flow
  - Functions
  - Conditional Logic 
  - If Else 
  - Switch Statement
---

This session was more of a practical task but we reviewed in depth more about the conditional logic needed to complete the tasks. 

#### if-else if-else Statements: Sequential Logic
The if-else if-else statement provides a way to execute different blocks of code based on multiple conditions. It follows a sequential order, executing the first block of code that meets the specified condition. If none of the conditions are met, the code within the else block is executed as a default.

```javascript
if (condition1) {
  // code to execute if condition1 is true
} else if (condition2) {
  // code to execute if condition1 is false and condition2 is true
} else if (condition3) {
  // code to execute if condition1 and condition2 are false and condition3 is true
} else {
  // code to execute if all conditions are false
}
```

#### Switch Statements: Simplifying Multiple Outcomes
Switch statements are used when we have a single variable and want to perform different actions based on its value. They provide a more concise and readable alternative to multiple if-else statements.

```javascript
switch (variable) {
  case value1:
    // code to execute if variable matches value1
    break;
  case value2:
    // code to execute if variable matches value2
    break;
  case value3:
    // code to execute if variable matches value3
    break;
  default:
    // code to execute if no case matches the variable
    break;
}
```

#### Comparison and Usage:
- if-else if-else statements are suitable when you have different conditions that are not directly related to the same variable. They provide flexibility in handling various scenarios.
- Switch statements are ideal when you need to perform different actions based on the value of a single variable. They offer a more streamlined and readable approach.

### Tasks
##### Task 1 - Percentage Calculator


Create a function that is able to return a specific percentage of any number.

For example you want to know what 30% of 135 is.


Create a function named percentageCalculator

Add 2 arguments for “number” and “percentage”

Do the maths required to work out a percentage with the arguments

Return the result of the maths

Console.log the returned value

##### Task 2 - Switch Statement


Customers can order 3 different types of drink and also select 3 sizes.

Cola, Lemonade and  Orangeade

Small, Medium and Large

The button they press have the values “cola”,”lemon”,”orange”

Create a function that will output the message “You have ordered a {size} of {softDrinkLabel}”


Create a function named drinkOrder

Add 2 arguments for “size” and “drink”

Use a switch statement to determine where the functional code needs to be written

Create a message in each case statement to be returned.

Console.log the returned message


##### Task 3 - Calculator

We need to create a function capable of using the addition, subtraction, multiply, divider or modulus operator on 2 numbers provided.


Create a function named calculator

Add 3 arguments for “number1”, “number2” and “operator”

Use a switch statement to determine which operator to use

Add the math code for each operator in the case statement to return the value

Console.log a message “{number1} {operator} {number2} = {value}”

###### Please find a link to the tasks completed in my codepen <a href="https://codepen.io/C-siegel31/pen/bGmMQQV?editors=1012">here</a>.