# ALX_Simple_Quiz

A simple interactive quiz application built with vanilla JavaScript, HTML, and CSS.

## Overview

This project demonstrates basic JavaScript concepts including:
- DOM manipulation
- Event handling
- Form validation
- Radio button selection

## How It Works

1. **Question**: "What is 2 + 2?"
2. **Choices**: 4, 22, or 3
3. **Correct Answer**: 4
4. **Feedback**: Dynamic messages based on user selection

## Usage

1. Open `index.html` in your web browser
2. Select one of the radio button choices
3. Click "Submit Answer" to check your response
4. View feedback message below the button

## Technical Implementation

- **HTML**: Semantic structure with radio buttons for choices
- **CSS**: Clean, responsive design with hover effects
- **JavaScript**: 
  - `checkAnswer()` function for validation
  - `document.querySelector()` for radio button selection
  - Event listener for button interaction



# Simple Calculator

A basic calculator application built with HTML, CSS, and vanilla JavaScript that performs arithmetic operations.

## Features

- **Addition (+)**: Adds two numbers
- **Subtraction (-)**: Subtracts the second number from the first
- **Multiplication (*)**: Multiplies two numbers
- **Division (/)**: Divides the first number by the second
- **Input Validation**: Uses parseFloat with default values
- **Error Handling**: Prevents division by zero

## Usage

1. Open `calculator.html` in your web browser
2. Enter two numbers in the input fields
3. Click any operation button (+, -, *, /)
4. View the result in the "Result:" display

## Technical Details

- **parseFloat**: Converts string inputs to floating-point numbers
- **Default Values**: Uses 0 for empty inputs (|| 0)
- **Division by Zero**: Returns "Cannot divide by zero" message
- **Event Listeners**: Attached to each operation button

## Files Structure
ALX_Simple_Quiz/
├── index.html    # Main HTML structure
├── styles.css    # CSS styling
├── quiz.js       # JavaScript functionality
├── calculator.html          # HTML structure
├── calculator.css      # Styling
├── calculator.js       # JavaScript functionality
└── README.md     # Project documentation

## Browser Support

Works in all modern browsers supporting ES6+ JavaScript.

## License

MIT License
