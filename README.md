# Calculator-System-by-using-Methods

A simple command-line calculator designed to demonstrate method separation and functional design in Java. 
This project moves logic away from the main method into dedicated arithmetic functions.

How It Works

The program follows a strict separation of concerns:

Main Method: Handles user interaction (input/output) and controls the flow.

Logic Methods: Independent methods perform the actual calculations.

💻 Logic Flow
Input: The user is prompted to select an operation (1–4).
Data Entry: The user enters two integer values.
Execution:
main identifies the choice.
main calls the specific method (e.g., add(a, b)).
The method calculates the result and "returns" it to main.
Output: main prints the final result to the console.

