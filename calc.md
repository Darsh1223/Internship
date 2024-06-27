// Simple Calculator in Node.js

// Function to perform addition
function add(a, b) {
    return a + b;
}

// Function to perform subtraction
function subtract(a, b) {
    return a - b;
}

// Function to perform multiplication
function multiply(a, b) {
    return a * b;
}

// Function to perform division
function divide(a, b) {
    if (b === 0) {
        return 'Cannot divide by zero!';
    }
    return a / b;
}

// Example usage:
console.log("Addition:", add(5, 3));       // Output: 8
console.log("Subtraction:", subtract(5, 3));  // Output: 2
console.log("Multiplication:", multiply(5, 3));  // Output: 15
console.log("Division:", divide(10, 2));   // Output: 5
console.log("Division by zero:", divide(5, 0));   // Output: "Cannot divide by zero!"
