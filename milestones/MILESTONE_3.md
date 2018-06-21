# Milestone 3

## Introduction
Your components are set and ready to work, but they don't look really pretty, do they? Let's turn this ugly duckling into a beautiful swan! In this milestone you will work with [Flexboxes](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) and you will add some styling to your components.

At the end of this milestone, the styled version of the calculator should look like this: [Calculator](https://github.com/microverseinc/project-react-calculator-solution/blob/master/images/calculator.png)

## Requirements

1. Use flex display mode for **App**, **Display**, **ButtonPanel** components
   - The Calculator width should be 700px.
2. Style **Display** component
   - It should have a gray background.
   - It should have a height set to 100px.
   - The result should be presented with a white and bold text.
   - The result should have padding from the edges.
   - The result should be aligned to the right.
3. Style **ButtonPanel** component
   - Each row (display and group buttons) should have a height of 100 px.
   - The Button groups should be displayed horizontally in rows.
4. Style **Button** component
   - Button should take 25% of the container width, except for the button that represents the "0" (zero).
   - Text in buttons should be centered and displayed in black color.
   - Each button should have border.
5. Pass "color" and "wide" props to Button
   - `color` prop should be used to customize the color of the button. If it is not passed, the button should have an orange background.
   - `wide` prop should accept a boolean to indicate that the button should have twice the standard width (used for the "0" button).
