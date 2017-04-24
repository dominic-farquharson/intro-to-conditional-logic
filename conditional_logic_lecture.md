# Intro to Conditional Logic

### Codepen: [Link](https://codepen.io/dfarquharson/pen/eWdKYV?editors=0010)

## Objectives
- Be able to define what a condition is.
- Be Able to make a program 'react' to a condition
- Define an if statement
- Define an else statement

## What is a condition? 
You can think of a condition as a requirement that must be met before something can be done.

**Ex 1:** When you use your metrocard in a bus or subway, the bus/subway system is checking for a condition. That condition is whether or not you have money on your card! If the condition is met, you are allowed to ride on that bus/vehicle.

<img src="http://ww1.prweb.com/prfiles/2012/06/05/9451397/Cole%20Haan%20Station%20Domination.jpg" height="300" width="300" style="display: block; margin: 0 auto;"/>

**Ex 2:** When you go to a fast food restaurant, when is your order complete? Your order is complete **AFTER** you pay. That is the condition that must be met to receive your food.

<img src="http://www.lonepinephoto.ca/image/42616/TEEN_WORKING_AS_CASHIER_AT_A_AND_W_FAST_FOOD_RESTAURANT_SASKATOON.jpg" height="300" width="300" style="display: block; margin: 0 auto;"/>


## What is a Conditional Statement? - Why are conditions used?
Conditional statements are used to perform different actions based on different conditions. [w3](https://www.w3schools.com/js/js_if_else.asp)
Imagine you are an ATM. How could you prevent someone from withdrawing more money than they have?? 
- Ans: You must set a condition and then check for it.


## Name the condition 
1. If you do your homework you will get a passing grade.
   1.  condition: Do homework.
1. If you go to sleep early, you'll be able to stay awake in class. 
   1. condition: sleep early.

## The If statement
The if statement is used to specify a block of code that can only be executed (or performed) when the condition is met.

```javascript
    // specifiying the codition to be met
    if( Suzie paid for her food){
    // Executed if condition is met
        give Suzie the food
    }
```

One way to check if a condition is met is to use the comparison operator.  ``` var1 === var2``` The comparison operator checks to see if two things are equal.

Now let's rewrite the above example, using the comparison operator to see if Suzie paid for her food.


``` javascript
    // example 1 - codepen
    var status = 'paid';

    if(status === 'paid') {
        alert('Suze has paid for her food');
    }

```

## Example: 
Let's write an if statement that checks if a person has gotten an A on a test.

```javascript
// example 2 - codepen
let grade = 'A';

if(grade === 'A') {
 alert ('You have received an A!');
}

```

Now we know that the alert will only execute when someone has received an A. But how could we send an alert if someone has not received an A?

We could add another if statement but is there a better option?

## Else Statement

An else statement can be combined or chained to an If statement. An else statement will only execute if the if statement was false.

```javascript
if(condition) {
   // Executes when condition is true
} else {
 // Executes when condition is false
}

```

Now let's add an else statement to our grade checker.

```javascript
// example 3 on codepen
let grade = 'B';

if(grade === 'A') {
 alert ('You have received an A!');
} else {
 alert ('You did not receive an A');
}

```

## Quick Recap

### What is a condition?
     Ans: A requirement that must be met.
### Why are conditions used?
     Ans: To allow for choices in programs.


