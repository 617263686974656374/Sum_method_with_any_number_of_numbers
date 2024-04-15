# Sum_method_with_any_number_of_numbers
This simple Java program demonstrates the use of variable arguments (varargs) in methods to handle an arbitrary number of input parameters.
The `sumNumber` method accepts any number of integers, sums them up, and prints the total sum along with the count of numbers provided.

**Functionality:**

- **Flexible Input Handling:** The `sumNumber` method can accept any number of integer arguments, or even no arguments at all.
- **Sum Calculation:** It calculates the sum of all the integers passed to it.
- **Output Details:** After calculating the sum, it prints both the total sum and the number of integers summed.

**Usage:**

- The program does not require user input during execution as it is designed to demonstrate the functionality of variable arguments through predefined method calls within the `main` method.
- Simply run the program to see how `sumNumber` handles different sets of arguments.

**Example Outputs:**

1. For the call `sumNumber(10, 20)`, the output will be:
   ```
   Total sum: 30
   Total numbers: 2
   ```
2. For the call `sumNumber(1, 2, 3, 4, 5)`, the output will be:
   ```
   Total sum: 15
   Total numbers: 5
   ```
3. For the call `sumNumber()`, the output will be:
   ```
   Total sum: 0
   Total numbers: 0
   ```

**Features:**

- **Varargs Usage:** Showcases how methods in Java can be designed to accept an unknown number of arguments, providing flexibility.
