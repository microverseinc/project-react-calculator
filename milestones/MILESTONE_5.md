# Milestone 5

## Introduction
We are now very close to the final line. Your last task is to tie the calculations module with the components and to add the interaction to the buttons. If you remember how to pass event handlers as a props from Parent to Children components, you will complete this lesson faster than the speed of light!

## Requirements

1. **App** component
    - The **App** component is going to be your stateful parent component. Initialize its state in the constructor with three
     properties: `total`, `next` and `operation`, just like in your `calculate.js` module. By default, they should all
     be set to `null`.
    - Implement the `handleClick` function which takes `buttonName` as an argument and changes the state based on the result of the `calculate` function.
    - Pass the `total` or `next` value to **Display** to display the current result.
    - Pass `handleClick` as a `clickHandler` property to **ButtonPanel**
2. **ButtonPanel**
    - Implement the `handleClick` function which takes `buttonName` as an argument and returns `clickHandler` from props.
    - Pass the `clickHandler` property to each button in the panel.
3. **Button**
    - Implement the `handleClick` function which takes `buttonName` as an argument and returns `clickHandler` from props.
    - Use the `onClick` event to attach the `handleClick` event to the button.
    - Documentation: https://reactjs.org/docs/events.html#mouse-events

Voila! You have finished your first React project.
