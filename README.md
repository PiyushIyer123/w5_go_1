# Go Sample Program

## Overview
This is a simple Go program that demonstrates basic function calls, arithmetic operations, and formatted output.

## Code Explanation
### Main Function
The `main` function is the entry point of the program. It:
- Calls `Greeting()` and `advanceGreeting("M")`.
- Prints the result of `add(1, 2)`.
- Performs arithmetic operations and prints the result.
- Uses a `divide` function to calculate and print the quotient and remainder of divisions.

### Additional Functions
- `Greeting()`: Prints a greeting message.
- `advanceGreeting(name string)`: Prints a personalized greeting.
- `add(a int, b int) int`: Returns the sum of two integers.
- `divide(a int, b int) (int, int)`: Returns the quotient and remainder of two integers.

## Running the Program
1. Save the code to a file named `main.go`.
2. Open a terminal and navigate to the directory containing `main.go`.
3. Run the program using the following command:
   ```sh
   go run main.go
