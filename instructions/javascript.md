// Step 1: Create a variable named resultDiv to hold the reference to the HTML element where the result will be displayed.
// Define the variable resultDiv using the const keyword because it will hold a reference to the HTML element, and this reference will not be reassigned.
// To access the HTML element where the result will be displayed, use the getElementById method provided by the document object, passing 'result' as the parameter.

// Step 2: Create a function called convertToRoman to handle the conversion process.

    // Step 3: Create a variable named inputNumber to store the value entered by the user.
    // Use the let keyword to define inputNumber since its value will be reassigned during the function execution.


    // Step 4: Validate the user input to ensure it is a valid number and within the acceptable range.
    // Check if the inputNumber is not a number, or if it is less than 1, or if it is greater than 3999.
    // The isNaN function is used to determine if the input is not a number.

        // Step 5: If the input is invalid, display an error message in resultDiv.
        // Set the innerHTML property of resultDiv to show the error message prompting the user to enter a valid number.

        // Step 6: Terminate the function to prevent further execution of unnecessary code.


    // Step 7: Define an object named romanNumerals to hold the Roman numeral symbols and their corresponding decimal values.
    // Each key-value pair represents a symbol and its decimal value.

    // Step 8: Create a variable named romanNumeral and assign an empty string to store the resulting Roman numeral.
    // Initialize it with an empty string to accumulate the Roman numeral symbols.

    // Step 9: Iterate through each symbol in the romanNumerals object for conversion.
    // Use a for...in loop to iterate through each key-value pair in the romanNumerals object.

        // Step 10: Repeat the conversion process until the remaining inputNumber is greater than the decimal value of the current symbol.
        // Use a while loop to continue adding Roman numeral symbols until the remaining inputNumber is greater than the decimal value of the current symbol.

            // Step 11: Add the current symbol to the romanNumeral string based on its decimal value.
            // Append the appropriate Roman numeral symbol to the romanNumeral string based on the decimal value being considered.

            // Step 12: Subtract the decimal value of the current symbol from the inputNumber to continue the conversion process.
            // Subtract the decimal value of the current symbol from the inputNumber to continue the conversion process.

    // Step 13: Update the content of the resultDiv to display the converted Roman numeral.
    // Set the innerHTML property of resultDiv to display the converted Roman numeral string, including the accumulated Roman numeral symbols.
