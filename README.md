# Simple Calculator

## Overview

The Simple Calculator is a basic web-based calculator designed to perform basic arithmetic operations. It features a user-friendly interface built with Bootstrap for responsive design and JavaScript for functionality. The calculator supports operations such as addition, subtraction, multiplication, division, and percentage calculations.

## Features

- **Basic Arithmetic Operations**: Addition, subtraction, multiplication, and division.
- **Percentage Calculation**: Compute percentages using the `%` button.
- **Error Handling**: Displays 'Error' if an invalid expression is entered.
- **Responsive Design**: Optimized for different screen sizes using Bootstrap.

## Technologies Used

### 1. Bootstrap

- **Version**: 4.5.2
- **Description**: A popular CSS framework for developing responsive and mobile-first websites. It provides pre-styled components and a grid system to create a visually appealing layout.
- **CDN Links**:
  - CSS: `https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css`
  - JS and Dependencies:
    - jQuery: `https://code.jquery.com/jquery-3.5.1.slim.min.js`
    - Popper.js: `https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.2/dist/umd/popper.min.js`
    - Bootstrap JS: `https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js`

### 2. JavaScript `eval()` Function

- **Description**: The `eval()` function evaluates a string as JavaScript code. In this application, it is used to calculate the result of arithmetic expressions displayed on the calculator.
- **Caution**: `eval()` should be used carefully due to potential security risks. It is generally suitable for simple use cases like this but may not be ideal for more complex or security-sensitive applications.

### 3. Browser DOM API

- **Description**: Utilized for interacting with HTML elements and handling user events. This includes updating the display, handling button clicks, and managing the calculator's state.

## Usage

To use the calculator:

1. Open the HTML file in a web browser.
2. Enter numbers and operators by clicking the corresponding buttons.
3. Press the `=` button to calculate the result.
4. Press the `C` button to clear the display.

## Code Overview

### JavaScript Functions

- **`appendToDisplay(value)`**: Appends the clicked button's value to the display. Clears the display if it shows `'0'` or `'Error'`.
- **`clearDisplay()`**: Resets the display to `'0'`.
- **`calculateResult()`**: Evaluates the expression shown on the display and updates it with the result. Displays `'Error'` if the expression is invalid.

## Example

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <!-- Head content with Bootstrap and custom styles -->
</head>
<body>
    <div class="container">
        <!-- Calculator markup with Bootstrap grid system -->
    </div>
    <!-- Bootstrap JS and dependencies -->
    <script>
        // JavaScript functions for calculator functionality
    </script>
</body>
</html>
