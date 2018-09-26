# Milestone 3

## Introduction
Your components are set and ready to work, but they don't look really pretty, do they? Let's turn this ugly duckling into a beautiful swan! In this milestone you will work with [Flexboxes](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) to add structure to the calculator, and you will add some styling to your components.

At the end of this milestone, the styled version of the calculator should look like this: [Calculator](https://github.com/microverseinc/project-react-calculator/blob/master/images/calculator.png)

*Note: For this milestone, you can optionally use Sass instead of CSS. If you decide to do so, please [follow this guide](https://hackernoon.com/using-sass-with-create-react-app-without-ejecting-b5f4f827ed9e) to be able to use Sass with Create React App without having to eject it.

## Requirements

1. Use flex display mode for **App**, **Display** and **ButtonPanel** components
    - The Calculator width should be 700px.
2. Style the **Display** component
    - It should have a gray background.
    - It should have a height set to 100px.
    - The result should be presented with a white and bold text.
    - The result should have padding from the edges.
    - The result should be aligned to the right.
3. Style the **ButtonPanel** component
    - Each row (display and group buttons) should have a height of 100 px.
    - The Button groups should be displayed horizontally in rows.
4. Style the **Button** component
    - Button should take 25% of the container width, except for the button that represents the "0" (zero).
    - The text in the buttons should be centered and displayed in black color.
    - Each button should have a border.
5. Pass "color" and "wide" props to the Button
    - The `color` prop should be used to customize the color of the button. If it is not passed, the button should have an orange background by default.
    - The `wide` prop should accept a boolean to indicate that the button should have twice the standard width (used for the "0" button).
