# Milestone 2

## Introduction
Your project is setup and working. Yay! Now, it is time to start with the real coding and define the basic React components which will compose your whole calculator.

Our calculator must have a root component called **App** which will contain a **Display** component, responsible for
displaying the outcome of calculations, and a **ButtonPanel** component, which is just container for all buttons. Finally each button in
**ButtonPanel** will implement the **Button** component which represents a single button.

## Requirements

1. Prepare directory structure
   - Create `components` directory in `src` folder.
   - Create four files in there, each one representing one React component. For instance, `App` component should be
     placed in `src/components/App.js`.
2. Implement **App** component
   - **App** should implement the `render` function.
   - Render function should display **Display** and **ButtonPanel**.
   - **REMEMBER!** JSX will not compile unless your render function returns a single element. Wrap the children components with a div tag and give it an appropriate ID.
3. Implement **Display** component
   - It should accept the result of the calculation as an incoming prop.
   - Result prop should be a String.
   - Default value of result prop should be 0.
4. Implement **Button** component
   - It should accept button name as a prop.
   - Button name prop should be a String.
5. Implement **ButtonPanel** component
   - It should render the calculator panel with all the buttons in the following groups: (use divs to divide buttons into groups)
     - Group 1: AC, +/-, %, +
     - Group 2: 7, 8, 9, X
     - Group 3: 4, 5, 6, -
     - Group 4: 1, 2, 3, +
     - Group 5: 0, ., =

If you fulfilled all requirements properly, you should see a pretty ugly page full of non-functional buttons. Don't worry, you will add some functionality in the next milestone!
