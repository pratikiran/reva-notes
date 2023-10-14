# I/O Stream Operators

1. **Insertion Operator (`<<`)**
   
   **Usage**: Primarily used with `cout` for output.
   
   **Description**: Sends the value on its right to the object on its left.
   
   **Example**
     ```cpp
     int x = 10;
     cout << "The value of x is: " << x;
     ```

2. **Extraction Operator (`>>`)**
   
   **Usage**: Primarily used with `cin` for input.
   
   **Description**: Retrieves the value from the object on its left and assigns it to the variable on its right.
   
   **Example**
     ```cpp
     int y;
     cout << "Enter a value for y: ";
     cin >> y;
     ```

3. **Stream Manipulators**
   These are not operators per se, but they are used in conjunction with the I/O operators to modify the behavior of input and output operations.
   
   **Examples**
     - `endl`: Inserts a new line.
     - `setw(n)`: Sets the width of the next input/output field.
     - `setprecision(n)`: Sets the precision for floating-point number output.
     - `fixed`: Uses fixed-point notation.
     - `hex`, `oct`, `dec`: Change the base of numeric output.
     ```cpp
     double z = 3.14159265;
     cout << setprecision(4) << z << endl;  // Outputs: 3.142
     ```

