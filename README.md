
# Temperature Conversion Program

This is a C++ program that converts temperatures between Fahrenheit and Celsius.

## Instructions

1. Clone this repository to your local machine.
2. Open the terminal and navigate to the directory where the program files are located.
3. Compile the program using a C++ compiler. For example, you can use `g++`:
   ```bash
   g++ temperature_conversion.cpp -o temperature_conversion
   ```
4. Run the compiled program:
   ```bash
   ./temperature_conversion
   ```

## Usage

1. Upon running the program, you will be prompted to choose the unit you want to convert to (`F` for Fahrenheit or `C` for Celsius).
2. Enter the temperature value in the corresponding unit when prompted.
3. The program will then perform the conversion and display the result.

## Example

```
****** Temperature Conversion ******
F = Fahrenheit
C = Celsius
What unit would you like to convert to: C
Enter the temperature in Fahrenheit: 98.6
The temperature is: 37C
************************************
```

## Note

- The formula used for conversion is based on the relationship between Fahrenheit and Celsius scales:
  - To convert Celsius to Fahrenheit: `F = (C * 1.8) + 32`
  - To convert Fahrenheit to Celsius: `C = (F - 32) / 1.8`

---