# Lab: Temperature Converter

## Objective

The aim of this lab is to practice user input, conditional statements, and arithmetic operations in Java by creating a simple Temperature Converter program. The program will allow the user to choose a conversion type (Celsius to Fahrenheit or Celsius to Kelvin) and then output the converted value.

## Requirements

- Java Development Kit (JDK)
- Any text editor or IDE (e.g., Visual Studio Code, IntelliJ IDEA, etc.)

## Instructions

1. **Create a Java Class**: Create a Java class named `TempConverter`.

2. **Import Scanner**: Import the `java.util.Scanner` class for user input.

3. **Display Menu**: Use `System.out.println` to display a menu asking the user to choose a conversion type.

    ```
    Choose the conversion you'd like to perform:
    1: Celsius to Fahrenheit
    2: Celsius to Kelvin
    ```

4. **User Choice**: Use the `Scanner` class to accept the user's choice (1 or 2).

5. **Enter Temperature**: Ask the user to enter the temperature in Celsius.

6. **Perform Conversion**: Based on the user's choice, perform the corresponding temperature conversion.

    - For Celsius to Fahrenheit: F = C * (9/5) + 32
    - For Celsius to Kelvin: K = C + 273.15


### Sample Input and Output
```
Choose the conversion you'd like to perform:
1: Celsius to Fahrenheit
2: Celsius to Kelvin
Enter your choice: 2
25.0 °C is 298.15 K
```