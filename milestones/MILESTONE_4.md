# Milestone 4

## Introduction
Let's put aside the React work for a moment. We will now focus on the heart of the calculator, its logic. In this milestone we will implement two JavaScript modules: `calculate.js` and `operate.js` which will be responsible for all calculations. Finally, we will include those modules in the **App** component so we can hook them up to other components in the next milestone.

## Requirements

1. Preparation
    - Create a new `logic` folder inside `src` and initialize two javascript files there: `calculate.js` and `operate.js`.
    - Add the [Big](https://www.npmjs.com/package/big-js) package to your project dependencies.
2. Implement the `calculate.js` module
    - It should contain one default method: `calculate`.
    - The `calculate` method should accept a calculator data object and a button name as arguments.
    - The calculator data object should contain three properties: `total`, `next` and `operation`.
    - This method should use the buttonName argument to mutate the calculator's data object and return its modified version. For instance if `buttonName == "+/-"`, it should multiply `total` and `next` by `-1` to make it negative or positive.
3. Implement the `operate.js` module
    - It should import the `big.js` module from the corresponding npm package.
    - It should implement one default function named `operate`.
    - The `operate` function should accept `numberOne`, `numberTwo` and `operation` as arguments.
    - Using the value of the `operation` argument, this method should perform a simple math operation. For instance if `operation == "-"`, it should return the result of subtracting the two passed numbers. Remember to wrap the numbers with `big.js` classes so you can operate on big numbers.
    - If the `buttonName` in `calculate.js` is equal to any operation (e.g. +, -, x, ÷, %), `operate.js` should be used to calculate the `total` property.
4. Add `calculate.js` to the **App** component
    - Import the `calculate` function.
