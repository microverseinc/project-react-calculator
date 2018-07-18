# Milestone 2

## Introduction
Your basic project structure is all setup and working. Yay! Now, it is time to start with the real coding by defining the basic React components which will compose your whole calculator.

The calculator must have a root component called **App** which will contain a **Display** component responsible for
displaying the outcome of the calculations, and a **ButtonPanel** component which will just be a container for all the buttons. Finally each button in **ButtonPanel** will implement the **Button** component which represents a single button.

## Requirements

1. Prepare the directory structure
    - Create a `components` directory in the `src` folder.
    - Create four files in there, each one representing one React component. For instance, the `App` component should be
     placed in `src/components/App.js`.
2. Implement the **App** component
    - **App** should implement the `render` function.
    - The `render` function should display **Display** and **ButtonPanel**.
    - **REMEMBER!** JSX will not compile unless your render function returns a single element. Wrap the children components with a div tag and give it an appropriate ID.
3. Implement the **Display** component
    - It should accept the result of the calculation as an incoming prop.
    - The result prop should be a String.
    - The default value of the result prop should be 0.
4. Implement the **Button** component
    - It should accept a button name as a prop.
    - The button name prop should be a String.
5. Implement the **ButtonPanel** component
    - It should render the calculator panel with all the buttons in the following groups: (use divs to divide buttons into groups)
        - Group 1: AC, +/-, %, +
        - Group 2: 7, 8, 9, X
        - Group 3: 4, 5, 6, -
        - Group 4: 1, 2, 3, +
        - Group 5: 0, ., =

If you fulfilled all requirements properly, you should see a pretty ugly page full of non-functional buttons. Don't worry, you will add some functionality in the next milestone!
